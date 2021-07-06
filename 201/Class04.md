# Read: 04 - HTML Links, CSS Layout, JS Functions

**Links :** <br>
It allows us to move from one page to another. <br>
 
**Directory :** <br>
Folders on a website are sometimes referred to as directories. <br>

**Relative URLs :** <br>
They can be used when linking pages within your own website. <br>

**Relative Link Types Same Folder:** <br>
To link to a file in the same folder, just use the file name. <br>

**Child Folder:** <br>
child folder, use the name of the child folder, followed by a forward slash, then the file name. <br>
**Grandchild Folder:** <br>
Use the name of the child folder, followed by a forward slash, then the name of the grandchild folder, followed by another forward slash, then the file name. <br>
**Parent Folder:** <br>
Use ../ to indicate the folder above the current one, then follow it with the file name. <br>
**GrandParent Folder:** <br>
Repeat the ../ to indicate that you want to go up two folders (rather than one), then follow it with the file name. <br>

**Email Links:** <br>
use **mailto:** when you want to create a link to an email address. <br>
**Target:** <br>
If you want a link to open in a new window, you can use the target attribute on the opening < a> tag. The value of this attribute should be _blank. <br>
**Linking to a Specific Part of the Same Page:** <br>
use the < a> element again, but the value of the href attribute starts with the # symbol followed by the value of the id attribute of the
the element you want to link to. <br>


**Layouts:** <br> <br>

**Building Blocks:** <br> 

In HTML we either have a **block-level box** or **inline box.** <br>

**Block-level boxes** start on a new line, while **inline boxes** flow between surrounding text.  <br>

**Containing Elements:** <br>

If one block-level element sits inside another block-level element then the outer box is known as the **containing** or **parent element.** <br>

**Controlling the Position of Elements:** <br>

You can specify the positioning scheme using the **position property** in CSS. You can also float elements using the **float property**. <br>
 
**z-index:** <br>
It allows you to control which box appears on top. <br>

**position: relative:**  moves an element in relation to where it would have been in normal flow.) <br>

**There are different position values:** <br>

- **static:** it is always positioned according to the normal flow of the page
- **relative:** it is positioned relative to its normal position.
- **fixed:** it is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled.
- **absolute:**  is taken out of the box of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.)
 
**float:** allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible. <br>

**Clearing Floats :** <br>

The clear property allows you to say that no element (within the same containing element) should touch the left or right-hand sides of a box. <br>

**Screen Sizes:** <br>
Your screen has a different-sized screen. so you should make the design work on different sized screens. <br>

**Screen Resolution:** <br>
Resolution refers to the number of dots a screen shows per inch. Some devices have a higher resolution than desktop computers and most operating systems allow users to adjust the resolution of their screens. <br>

**Page Sizes:** <br>
the sizes and display resolutions of a page may vary, that's why web designers create pages of around 960-1000 pixels round. <br>

**Fixed width layout designs** do not change size as the user increases or decrease the size of their browser window. <br>

**Liquid layout designs** stretch and contract as the user increases or decrease the size of their browser window. <br>

**Grids** help create professional and flexible designs. <br>

**CSS Frameworks** provide rules for common tasks. <br>

You can include **multiple CSS files** on one page. <br>
