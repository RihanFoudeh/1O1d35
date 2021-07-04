# Read: 02 - HTML Text, CSS Introduction, and Basic JavaScript Instructions

# HTML

* Structural markup: the elements that you can use to  describe both headings and paragraphs
* Semantic markup: which provides extra information; such  as where emphasis is placed in a sentence.
* HTML has six "levels" of  headings: `<h1>, <h2>, <h3>, <h4>, <h5> ,<h6>`.
* `<H1>` : elements are a great way to give more structure to a page so that users and search engines can understand which parts of a page are kind of under different headings.
* `<p>` : To create a paragraph.
* `<b>` : can make  characters appear bold.
* `<i>` : can make characters appear italic.
* `<sup>` : used  to contain characters that  should be superscript.
* `<sub>` : used to  contain characters that should  be subscript.
* White Space : to make code easier to  read.
* `<br/>` : line break tag.
* `<hr/>` :  create a break between  themes  you can add a  horizontal rule between sections.
* visual editor : is computer software for editing text files using a textual or graphical user interface which displays the content (text) in an easy to look at and good view; that is, it displays a portion of the opened file and updates it in real time.
* CodeView : is a way of viewing and using code. certain characteristics and properties of the text are emphasized or located for easy visibility.
* `<strong>` : content has strong importance, browsers will show  the contents of element in bold.
* `<em>` : emphasis that subtly changes  the meaning of a sentence, By default browsers will show  the contents of element  in italic.
* `<blockquote>` :  indicates that the enclosed text is an extended quotation.
* `<q>` : shorter quotes that sit within  a paragraph.
* `<abbr>` :  the optional title attribute can provide an expansion or description for the abbreviation.
* `<cite>` : used to describe a reference to a cited creative work, and must include the title of that work.
* `<dfn>` : used to indicate the term being defined within the context of a definition phrase or sentence.
* `<address>` : provides contact information for a person or people, or for an organization.
* `<ins>` : show content that has been inserted into a document.
* `<del>` : lement can show text  that has been deleted.
* `<s>` : element to represent things that are no longer relevant or no longer accurate.

# Css

### A CSS rule  contains two parts

* Selectors indicate which  element the rule applies to.
* Declarations indicate how  the elements referred to in  the selector should be styled.

```Css
 p { >> Selector
    font-family: Arial; >> Declaration
 } 
 ```

### CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value

### `<link>` : The HTML External Resource Link element specifies relationships between the current document and an external resource. This element is most commonly used to link to stylesheets

* href : This specifies the path to the  CSS file .
* type : This attribute specifies the type  of document being linked to.
* rel : This specifies the relationship  between the HTML page and  the file it is linked to.

### `<style>` : element allows style sheets to be embedded directly within content

### CSS Selectors

* Universal  >> * { ..... }
* Type >> h1, h2, h3 { ..... }
* Class >> .note { ..... }
* ID >> #introduction { ..... }
* Child >> li>a { ..... }
* Descendant >> p a { ..... }
* Adjacent Sibling >> h1+p { ..... }
* General Sibling >> h1~p { ..... }

## An external stylesheet is a standalone . css file that is linked from a web page. The advantage of external stylesheets is that it can be created once and the rules applied to multiple web pages

# JAVASCRIPT

* script : is a series of instructions that a computer can follow one-by-one.

* statement : each individual instruction or step.

* comments : help you and others who read your code. ex( ` //SINGLE-LINE , /* MULTI-LINE */ ` ).

* VARIABLE : A script will have to temporarily  store the bits of information it  needs to do its job. It can store this  data in variables.

* DATA TYPES : NUMERIC, STRING, BOOLEAN.

* Array : it stores a list of values. var Name = new Array('....' ,'....', .... );

* Operators :
  * arithmetic : `( +, -, *, /, % )`.
  * logical : `( And >> &&, or >> ||, not >> ! )`.
  * Comparison operator: `( == , != , === , !== , > , < , <= , >= )`.

## IF STATEMENTS

### The If...Then... Else statement allows conditional execution based on the evaluation of an expression. ... The thenpart is executed if condition is true; if condition is false, then elsepart is executed. If the Else clause is not present, control passes to the next statement in the program

```JAVASCRIPT
if ( Condition ){
    // code to execute if value is true
} else {
    // code to execute if value is false 
}
```

## SWITCH STATEMENTS

### executes a block of code depending on different cases. which are used to perform different actions based on different conditions

```JAVASCRIPT
switch(expression) {
  case n:
        code block
        break;
  case n:
        code block
        break;
  default:
        default code block
}
```

[Back To README!](https://yousefabujalboush.github.io/reading-notes/)