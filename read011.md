# Chapter 16: “Images” (pp.406-427)

* In this chapter you will learn how to:
Specify the size and alignment of an image using
 Add background images to boxes
 Create image rollovers in CSS

 * You can control the size of an
image using the width and
height properties in CSS, just
like you can for any other box.

* Specifying image sizes helps
pages to load more smoothly
because the HTML and CSS
code will often load before the
images, and telling the browser
how much space to leave for an
image allows it to render the rest
of the page without waiting for
the image to download.

* In the last chapter, you saw how
the float property can be used
to move an element to the left or
the right of its containing block,
allowing text to flow around it.

* Rather than using the img>
element's align attribute, web
page authors are increasingly
using the float property to align
images. There are two ways that
this is commonly achieved:

1. The float property is added
to the class that was created to
represent the size of the image

2. New classes are created with
names such as align-left or
align-right to align the images
to the left or right of the page.
These class names are used in
addition to classes that indicate
the size of the image.

* In this example you can see the
align-left and align-right
classes used to align the image.
It is also common to add a
margin to the image to ensure
that the text does not touch their
edges.

* By default, images are inline
elements. This means that they
flow within the surrounding text.

In order to center an image, it
should be turned into a blocklevel
element using the display
property with a value of block.

* Once it has been made into a
block-level element, there are
two common ways in which you
can horizontally center an image:

1. On the containing element,
you can use the text-align
property with a value of center.

2. On the image itself, you can
use the use the margin property
and set the values of the left and
right margins to auto.

* The background-repeat
property can have four values:

1. repeat
The background image is
repeated both horizontally and
vertically (the default way it
is shown if the backgroundrepeat
property isn't used).

2. repeat-x
The image is repeated
horizontally only (as shown in
the first example on the left).

3. repeat-y
The image is repeated vertically
only.

4. no-repeat
The image is only shown once.

The background-attachment
property specifies whether a
background image should stay in
one position or move as the user
scrolls up and down the page.
 It
can have one of two values:

1. fixed
The background image stays in
the same position on the page.

2. scroll
The background image moves
up and down as the user scrolls
up and down the page.

* You can specify the dimensions of images using CSS.
This is very helpful when you use the same sized
images on several pages of your site.

*  Images can be aligned both horizontally and vertically
using CSS.

* You can use a background image behind the box
created by any element on a page.

*  Background images can appear just once or be
repeated across the background of the box.

* You can create image rollover effects by moving the
background position of an image.

*  To reduce the number of images your browser has to
load, you can create image sprites.



# Chapter 19: “Practical Information” (476-492)

* we will learn in this chapter :

1. The basics of search engine optimization
2.  Using analytics to understand how people are using your
site after it has launched
3. Putting your site on the web

* In every page of your website there are seven key places where keywords
(the words people might search on to find your site) can appear in order
to improve its findability.

On-Page SEO

1. Page Title
The page title appears at the top
of the browser window or on the
tab of a browser. It is specified in
the title> element which lives
inside the head> element.

2. URL / Web Address
The name of the file is part of
the URL. Where possible, use
keywords in the file name.

3. Headings
engine will know that this page is
all about that subject and give it
greater weight than other text.

4. Text
Where possible, it helps to
repeat the keywords in the main
body of the text at least 2-3
times. Do not, however, over-use
these terms, because the text
must be easy for a human to
read.

5. Link Text
Use keywords in the text that
create links between pages
(rather than using generic
expressions such as "click here").

6. Image Alt Text
Search engines rely on you
providing accurate descriptions
of images in the alt text. This
will also help your images show
up in the results of image-based
searches.

7. Page Descriptions
The description also lives inside
the  head> element and is
specified using a  meta> tag.
It should be a sentence that
describes the content of the
page. (These are not shown in
the browser window but they
may be displayed in the results
pages of search engines.)

* Signing Up

1. The Google Analytics service
relies on you signing up for an
account at:
www.google.com/analytics
The site will give you a piece of
tracking code which you need to
put on every page of your site.

2. How it Works
Every time someone loads a
page of your site, the tracking
code sends data to the Google
servers where it is stored.

3. Google then provides a webbased
interface that allows you
to see how visitors use your site.
The Tracking Code
A tracking code is provided
by Google Analytics for each
website you are tracking. It
should appear just before the
closing head> tag.

4. The code
does not alter the appearance of
your web pages.


* Search engine optimization helps visitors find your
sites when using search engines.

* Analytics tools such as Google Analytics allow you to
see how many people visit your site, how they find it,
and what they do when they get there.

* To put your site on the web, you will need to obtain a
domain name and web hosting. 

* FTP programs allow you to transfer files from your
local computer to your web server.

* Many companies provide platforms for blogging, email
newsletters, e-commerce and other popular website
tools (to save you writing them from scratch).