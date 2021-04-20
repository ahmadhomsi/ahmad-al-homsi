# Chapter 7: “Forms” (p.144-175)


* HTML borrows the concept of a form to refer to different
elements that allow you to collect information from visitors to
your site.

* Whether you are adding a simple search box to your website or
you need to create more complicated insurance applications,
HTML forms give you a set of elements to collect data from
your users. In this chapter you will learn:

* How to create a form on your website
* The different tools for collecting data
* New HTML5 form controls

* The best known form on the web is probably
the search box that sits right in the middle of
Google's homepage.

* There are several types of form controls that
you can use to collect information from visitors
to your site.

* A form may have several form controls, each
gathering different information. The server
needs to know which piece of inputted data
corresponds with which form element.

You have probably seen forms
on the web that give users
messages if the form control has
not been filled in correctly; this is
known as form validation.
Traditionally, form validation
has been performed using
JavaScript (which is beyond the
scope of this book). But HTML5
is introducing validation and
leaving the work to the browser.

* Whenever you want to c XX ollect information from
visitors you will need a form, which lives inside a
form> element.

* Information from a form is sent in name/value pairs.
* Each form control is given a name, and the text the
user types in or the values of the options they select
are sent to the server.

*  HTML5 introduces new form elements which make it
easier for visitors to fill in forms.

# Chapter 14: “Lists, Tables & Forms” (pp.330-357)

* In this chapter you will learn how to:
Specify the type of bullet point or numbering on lists
*  Add borders and backgrounds to table cells
*  Control the appearance of form controls
Together, these properties allow you to take finer control over
specific parts of your pages.

* Nobody I know enjoys filling
in forms, so if you can make
yours look more attractive and
easier to use, more people are
likely to fill it in. Also, when you
come to look at a form in a few
different browsers (as shown
on the right), you will see that
each browser displays them
differently.

* CSS is commonly used to
control the appearance of form
elements. This is both to make
them more attractive and to
make them more consistent
across different browsers
It is most common to style:

1. Text inputs and text areas
2. Submit buttons
3. Labels on forms, to get the
form controls to align nicely
In the coming pages you will see
how to control these with CSS.

* Here are the most commonly
used values for this property:
1. auto
2. crosshair
3. default
4. pointer
5. move
6. text
7. wait
8. help
9. url("cursor.gif");




* In addition to the CSS properties covered in other
chapters which work with the contents of all elements,
there are several others that are specifically used to
control the appearance of lists, tables, and forms.
*  List markers can be given different appearances
using the list-style-type and list-style image
properties.
*  Table cells can have different borders and spacing in
different browsers, but there are properties you can
use to control them and make them more consistent.
*  Forms are easier to use if the form controls are
vertically aligned using CSS.
*  Forms benefit from styles that make them feel more
interactive.

# Chapter 6: “Events” (pp.243-292)

* When you browse the web, your browser registers different
types of events. It's the browser's way of saying, "Hey, this
just happened." Your script can then respond to these events. 

* Here is a selection of the events that occur in the browser while you are
* browsing the web. Any of these events can be used to trigger a function
in your JavaScript code. 

1. TERMINOLOGY
EVENTS FIRE OR ARE RAISED
When an event has occurred, it is often described as having fired or
been raised. In the diagram on the right, if the user is tapping on a  link, a
cl ick event would fire in the browser.

2. EVENTS TRIGGER SCRIPTS
Events are said to trigger a function or script. When the click event
fires on the element in this diagram, it could trigger a script that enlarges
the selected item. 

* When the user interacts with the HTML on a web page, there are three
steps involved in getting it to trigger some JavaScript code.
Together these steps are known as event handling

All modern browsers understand this way of creating an event handler,
but you can only attach one function to each event handler.


* When an event occurs, the event object tells
you information about the event, and the
element it happened upon.

Every time an event fires, the The event object is passed to
event object contains helpful any function that is the event
data about the event, such as: handler or listener.
1. Which element the event
happened on If you need to pass arguments
2. Which key was pressed for a to a named function, the event
keypress event object will first be passed to the
3. What part of the viewport the anonymous wrapper function
user clicked for a c 1 i ck event (this happens automatically);
(the viewport is the part of then you must specify it as a
the browser window that parameter of the named function
shows the web page)

The HTML elements you can interact with, such as links and form
elements, can gain focus. These events fire when they gain or lose focus.
If you can interact with an HTML element, then it
can gain (and lose) focus. You can also tab between
the elements that can gain focus (a technique often
used by those with visual impairments).


* In older scripts, the focus and b 1 ur events were
often used to change the appearance of an element
as it gained focus, but now the CSS : focus pseudoclass is a better solution (unless you need to affect
an element other than the one that gained focus).
EVENT TRIGGER
The focus and b 1 ur events are most commonly used
on forms. They can be particularly helpful when:
* You want to show tips or feedback to users as
they interact with an individual element within a
form (the tips are usually shown in other elements
and not the one they are interacting with)
* You need to trigger form validation as a user
moves from one control to the next (rather than
waiting for them to submit the entire form first) 
Events are the browser's way of indicating when
something has happened (such as when a page has
finished loading or a button has been clicked).


* Binding is the process of stating which event you are
waiting to happen, and which element you are waiting
for that event to happen upon.

* When an event occurs on an element, it can trigger a
JavaScript function. When this function then changes
the web page in some way, it feels interactive because
it has responded to the user.

*You can use event delegation to monitor for events
that happen on all of the children of an element.

* The most commonly used events are W3C DOM
events, although there are others in the HTMLS
specification as well as browser-specific events. 