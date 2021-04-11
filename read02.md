
# Chapter 2: “Text” (pp.40-61)

 * what we learn here ?
HTML elements are used to describe the structure of
the page ( headings, subheadings, paragraphs).
 They also provide semantic information (where
emphasis should be placed, the definition of any
acronyms used, when given text is a quotation).


< h1 >
< h2>
< h3>
< h4>
< h5>
< h6> 

HTML has six "levels" of headings:

< h1> is used for main headings,

< h2> is used for subheadings ,

If there are further sections
under the subheadings then the
< h3> element is used, and so on.


< p> 

To create a paragraph, surround
the words that make up the
paragraph with an opening p>
tag and closing  p> tag.


< b> 

By enclosing words in the tags
 b  and  b> we can make
characters appear bold.


< i>

By enclosing words in the tags
i> and  i> we can make
characters appear italic.


< sup>

The sup> element is used
to contain characters that
should be superscript such
as the suffixes of dates or
mathematical concepts like
raising a number to a power such
as 22.

 < sub> 

The sub> element is used to
contain characters that should
be subscript. It is commonly
used with foot notes or chemical
formulas such as H20.

< hr /> 

To create a break between
themes — such as a change of
topic in a book or a new scene
in a play — you can add a
horizontal rule between sections
using the hr /> tag.


< br> 

As you have already seen, the
browser will automatically show
each new paragraph or heading
on a new line. But if you wanted
to add a line break inside the
middle of a paragraph you can
use the line break tag  br />.


< strong> 

The use of the  strong>
element indicates that its
content has strong importance.
For example, the words
contained in this element might
be said with strong emphasis.


< em> 

The  em> element indicates
emphasis that subtly changes
the meaning of a sentence.
By default browsers will show
the contents of an  em> element
in italic.

< blockquote> 

The blockquote> element is
used for longer quotes that take
up an entire paragraph. Note
how the p> element is still
used inside the  blockquote>
element.


 < q > 
The  q> element is used for
shorter quotes that sit within
a paragraph. Browsers are
supposed to put quotes around
the  q> element, however
Internet Explorer does not —
therefore many people avoid
using the  q> element.



If you use an abbreviation or
an acronym, then the  abbr>
element can be used. A title
attribute on the opening tag is
used to specify the full term.


< cite> 

When you are referencing a
piece of work such as a book,
film or research paper, the
< cite> element can be used 
to indicate where the citation is
from.


 < dfn> 

The first time you explain some
new terminology (perhaps an
academic concept or some
jargon) in a document, it is
known as the defining instance
of it.


 < address> 02/address.html HTML 
The < address> element has 
quite a specific use: to contain
contact details for the author of
the page.


< ins> 

< del>

The < ins> element can be used 
to show content that has been
inserted into a document, while
the del> element can show text
that has been deleted from it.



 < s>
The s> element indicates
something that is no longer
accurate or relevant (but that
should not be deleted).


and we have a lot of exaples for evry element in book .





# Chapter 10: Ch.10 “Introducing CSS” (pp.226-245)


* what we learn here in this chapter 10 ?

How do you update web pages and make them appear beautifully and attractively for the sake of users and this thing we will do by using css as css is a program for designing web pages through which it determines how the shape of the web page should be and other things like specifying colors, backgrounds and things  The other 
CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.




* Declarations indicate how
the elements referred to in
the selector should be styled.


Declarations are split into two
parts (a property and a value),
and are separated by a colon.

Properties indicate the aspects
of the element you want to
change. For example, color, font,
width, height and border.

Values specify the settings
you want to use for the chosen
properties. For example, if you
want to specify a color property
then the value is the color you
want the text in these elements
to be.

You can also include CSS rules
within an HTML page by placing
them inside a style> element,
which usually sits inside the
head> element of the page.
The style> element should use
the type attribute to indicate
that the styles are specified in
CSS. The value should be text/
css.


When building a site with more
than one page, you should use
an external CSS style sheet. This:
●● Allows all pages to use the
same style rules (rather than
repeating them in each page).


●● Keeps the content separate
from how the page looks.

●● Means you can change the
styles used across all pages
by altering just one file
(rather than each individual
page).

Different types of selectors allow you to target your
rules at different elements.

 Declarations are made up of two parts: the properties
of the element that you want to change, and the values
of those properties. For example, the font-family
property sets the choice of font, and the value arial
specifies Arial as the preferred typeface.

CSS rules usually appear in a separate document,
although they may appear within an HTML page.


# Chapter 2: “Basic JavaScript Instructions” (pp.53-84)

# VARIABLES


what we learen here : 

1. The name must begin with
a letter, dollar sign ($) or (_). 

2. If your variable name is made
up of more than one word, use a
capital letter for the first letter of
every word after the first word.

* what is An array ?
t is a type of variable that stores a list of variables, not just one value, and it is very useful when you create a file that contains many values ​​and variables, and you will not face a problem in that.

* It is important to know that array and the values ​​in it are numbered starting from zero, not a single number. This thing is done automatically and is called the index. Here we also learn how to retrieve a file and also each array has a property called the length that carries the number of the array elements. 


**array:**

An array is a special type of variable. It doesn't
just store one value; it stores a list of values.

Values in an array are accessed as if they are in
a numbered list. It is important to know that the
numbering of this list starts at zero (not one).
* operators;

Expressions rely on things called operators; they allow programmers to
create a single value from one or more values. 

# Chapter 4: “Decisions and Loops (pp.145-162)





| Syntax      | Description                                      |
|-------------|--------------------------------------------------|
|     !       | is not equal to  (not the same)                  |
|     ==      | is equal to  (the same   )                       |
|     ===     | is strict equal to  (the same data and ralue  )  |
|    ! ==     | is strict not equal to                           |
|      >      | is greter than                                   |
|      <      | is less than                                     |
|      >=     | is greater that or equal                         |
|      <=     | is less than or equal                            |
|      &&     | is logical and                                   |
|      ||     | is logical or                                    |
|      !      | is logical not                                   |
   


  * and we learen about loops meane : Loops are handy, if you want to run the same code over and over again, each time with a different value.

  * and we learen about different kinds of loops:

* for - loops through a block of code a number of times

* while - loops through a block of code while a specified condition is 
true 




































