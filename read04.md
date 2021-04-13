# Chapter 4

* Links are the defining feature of the web
because they allow you to move from
one web page to another — enabling the
very idea of browsing or surfing.

* we have 5 types of links:

1-Links from one website to another

2- Links from one page to another on the same website

3- Links from one part of a web page to another part of the
same page

4- Links that open in a new browser window

5- Links that start up your email program and address a new
email to someone

* a> other-sites.html HTML
Links are created using the a>
element which has an attribute
called href. The value of the
href attribute is the page that
you want people to go to when
they click on the link.

* When you are linking to other
pages within the same site,
you do not need to specify the
domain name in the URL. You
can use a shorthand known as a
relative URL.

* mailto:

To create a link that starts up
the user's email program and
addresses an email to a specified
email address, you use the a>
element. However, this time the
value of the href attribute starts
with mailto: and is followed by
the email address you want the
email to be sent to.

* target

If you want a link to open in a
new window, you can use the
target attribute on the opening
a> tag. The value of this
attribute should be _blank.


* Links are created using the a> element.
* The a> element uses the href attribute to indicate
the page you are linking to.
*  If you are linking to a page within your own site, it is
best to use relative links rather than qualified URLs.
* You can create links to open email programs with an
email address in the "to" field.
* You can use the id attribute to target elements within
a page that can be linked to.




# Chapter 15:

* what we learn in this chapter :

how to control where each element sits
on a page and how to create attractive
page layouts.

* Containing Elements
If one block-level element sits inside another
block-level element then the outer box is
known as the containing or parent element.

* Relative positioning moves an
element in relation to where it
would have been in normal flow.
For example, you can move it 10
pixels lower than it would have
been in normal flow or 20% to
the right.

* When the position property
is given a value of absolute,
the box is taken out of normal
flow and no longer affects the
position of other elements on
the page. (They act like it is not
there.)

* Fixed positioning is a type
of absolute positioning that
requires the position property
to have a value of fixed.


* When you use relative, fixed, or
absolute positioning, boxes can
overlap. If boxes do overlap, the
elements that appear later in the
HTML code sit on top of those
that are earlier in the page.

* The clear property allows you
to say that no element (within
the same containing element)
should touch the left or righthand
sides of a box. It can take
the following values:
* left
The left-hand side of the box
should not touch any other
elements appearing in the same
containing element.
* right
The right-hand side of the
box will not touch elements
appearing in the same containing
element.
* both
Neither the left nor right-hand
sides of the box will touch
elements appearing in the same
containing element.
* none
Elements can touch either side.


* <div  elements are often used as containing elements
to group together sections of a page.
*  Browsers display pages in normal flow unless you
specify relative, absolute, or fixed positioning.
*  The float property moves content to the left or right

of the page and can be used to create multi-column
layouts. (Floated items require a defined width.)




# the Duckett JS

## Chapter 3


* Functions let you group a series of statements together to perform a
specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than repeating the same set of statements).

* Expressions produce a value. They can be used where values are expected.
If a function is placed where a browser expects to see an expression,
(e.g., as an argument to a function), then it gets treated as an expression. 

FUNCTION DECLARATION
A function declaration creates a function that you
can call later in your code. It is the type of function
you have seen so far in this book. 

# 6 Reasons for Pair Programming

* How does pair programming work?
While there are many different styles, pair programming commonly involves two roles: the Driver and the Navigator. The Driver is the programmer who is typing and the only one whose hands are on the keyboard. Handling the “mechanics” of coding, the Driver manages the text editor, switching files, version control, and—of course writing—code.

* Why pair program?
While learning to code, developers likely study several programming languages.

1. Greater efficiency
It is a common misconception that pair programming takes a lot longer and is less efficient.

2. Engaged collaboration
When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone.

3. Learning from fellow students
Everyone has a different approach to problem solving; working with a teammate can expose developers to techniques they otherwise would not have thought of

4. Social skills
Pair programming is great for improving social skills.

5. Job interview readiness
A common step in many interview processes involves pair programming between a current employee and an applicant, either in person or through a shared screen.

6. Work environment readiness
Many companies that utilize pair programing expect to train fresh hires from CS-degree programs on how they operate to actually deliver a product.





























