# Read: Hash Tables

## What is a Hashtable?

### Terminology:

- Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.

- Buckets - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.

- Collisions - A collision is what happens when more than one key gets hashed to the same location of the hashtable.

## Why do we use them?

- Hold unique values

- Dictionary

- Library

### What Are they

- Hashtables are a data structure that utilize key value pairs. This means every Node or Bucket has both a key, and a value.

- The basic idea of a hashtable is the ability to store the key into this data structure, and quickly retrieve the value. This is done through what we call a hash. A hash is the ability to encode the key that will eventually map to a specific location in the data structure that we can look at directly to retrieve the value.

- Since we are able to hash our key and determine the exact location where our value is stored, we can do a lookup in an O(1) time complexity. This is ideal when quick lookups are required.

#### Hash maps do this to store values:
- accept a key
- calculate the hash of the key
- use modulus to convert the hash into an array index
- store the key with the value by appending both to the end of a linked list
- Hash maps do this to read value:
- accept a key
- calculate the hash of the key
- use modulus to convert the hash into an array index
- use the array index to access the short LinkedList representing a bucket
- search through the bucket looking for a node with a key/value pair that matches the key you were given

### Bucket Sizes

- Hash Maps can have any number of buckets. If a hash map has only a few buckets it will be densely full and have many collisions. If a hash map has more buckets it will be more sparsely populated, there will be less collisions, but there may be a lot of extra empty space.
- It’s possible to compute the “load factor” of a hash table. The load factor tells us something about how full the hash table is. A hash table can start with only a few buckets, calculate it’s own load factor, recognize when it gets too full and automatically grow and add more buckets to itself to accommodate more data.
- Recognize: calculating load factors and choosing the optimal number of buckets, and determining the best hash functions is not within the scope of this class. This class intends to introduce you to what a hash table is, how it’s implemented, what hash codes are, how to handle collisions and how to reason generally about what it means for a hash table to be more empty or more full. This class does not intend to calculate theoretical optimal performance limits for how to best balance a Hash Table.

### Internal Methods
- Add()

    - When adding a new key/value pair to a hash table:
    - send the key to the GetHash method.
    - Once you determine the index of where it should be placed, go to that index
    - Check if something exists at that index already, if it doesn’t, add it with the key/value pair.
    - If something does exist, add the new key/value pair to the data structure within that bucket.
- Find()
    - The Find takes in a key, gets the Hash, and goes to the index location specified. Once at the index - - - location is found in the array, it is then the responsibility of the algorithm the iterate through the - bucket and see if the key exists and return the value.
- Contains()
    - The Contains method will accept a key, and return a bool on if that key exists inside the hash table. - - The best way to do this is to have the contains call the GetHash and check the hash table if the key - - exists in the table given the index returned.
- GetHash()
    - The GetHash will accept a key as a string, conduct the hash, and then return the index of the array - - - where the key/value should be placed.
