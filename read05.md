
# chapter5 Images

* what we learn here in this chapter :

There are many reasons why you might
want to add an image to a web page: you
might want to include a logo, photograph,
illustration, diagram, or chart.

1.  Include an image i ●● n your web pages using HTML
2. Pick which image format to use
3. Show an image at the right size
4. Optimize an image for use on the web to make pages
load faster

* img> 
images.html HTML
To add an image into the page
you need to use an img>
element. This is an empty
element (which means there is
no closing tag).

* src
This tells the browser where
it can find the image file. This
will usually be a relative URL
pointing to an image on your
own site. (Here you can see that
the images are in a child folder
called images — relative URLs
were covered on pages 83-84).

* alt
This provides a text description
of the image which describes the
image if you cannot see it.
* title
You can also use the title
attribute with the img> element
to provide additional information
about the image. Most browsers
will display the content of this
attribute in a tootip when the
user hovers over the image.

* height
This specifies the height of the
image in pixels.
* width
This specifies the width of the
image in pixels.


* figure>
Images often come with
captions. HTML5 has introduced
a new  figure> element to
contain images and their caption
so that the two are associated.

* figcaption>
The  figcaption> element has
been added to HTML5 in order
to allow web page authors to add
a caption to an image.

* The img> element is used to add images to a
web page.
* You must always specify a src attribute to indicate the
source of an image and an alt attribute to describe the
content of an image.
*  You should save images at the size you will be using
them on the web page and in the appropriate format.
*  Photographs are best saved as JPEGs; illustrations or
logos that use flat colors are better saved as GIFs.

# chapter 11

 there are three common ways in
which you can indicate your choice of colors (plus extra
ways made available in CSS3)
*  Color terminology, as there are some terms that are very
helpful to understand when it comes to picking colors
* Contrast, and ensuring that your text is readable
*  Background colors for behind either your entire page or
parts of a page


 * The color property allows you
to specify the color of text inside
an element. You can specify any
color in CSS in one of three ways:
rgb values
These express colors in terms
of how much red, green and
blue are used to make it up. For
example: rgb(100,100,90)
hex codes
These are six-digit codes that
represent the amount of red,
green and blue in a color,
preceded by a pound or hash #
sign. For example: #ee3e80
color names
There are 147 predefined color
names that are recognized
by browsers. For example:
DarkCyan

Color not only brings your s XX ite to life, but also helps
convey the mood and evokes reactions.
* There are three ways to specify colors in CSS:
RGB values, hex codes, and color names.
*  Color pickers can help you find the color you want.
* It is important to ensure that there is enough contrast
between any text and the background color (otherwise
people will not be able to read your content).
* CSS3 has introduced an extra value for RGB colors to
indicate opacity. It is known as RGBA.
* CSS3 also allows you to specify colors as HSL values,
with an optional opacity value. It is known as HSLA.


# chapter 12 

The properties that allow you to control
the appearance of text can be split into
two groups:
Those that directly affect the font and its appearance
(including the typeface, whether it is regular, bold or italic,
and the size of the text)
Those that would have the same effect on text no matter
what font you were using (including the color of text and
the spacing between words and letters)

There are several ways to use fonts other than those listed on the
previous page. However, typefaces are subject to copyright, so the
techniques you can choose from are limited by their respective licenses.



The people who are visiting
your site need the typeface you
have specified installed on their
computer in order for it to be
displayed.
You can specify a list of fonts
separated by commas so that,
if the user does not have your
first choice of typeface installed,
the browser can try to use an
alternative font from the list.


* pixels
Pixels are commonly used
because they allow web
designers very precise control
over how much space their text
takes up. The number of pixels is
followed by the letters px.
percentages

* The default size of text in
browsers is 16px. So a size of
75% would be the equivalent of
12px, and 200% would be 32px.
If you create a rule to make all
text inside the  body> element
to be 75% of the default size (to
make it 12px), and then specify
another rule that indicates the
content of an element inside the
 body> element should be 75%
size, it will be 9px (75% of the
12px font size).
ems
An em is equivalent to the width
of a letter m.


* font-family
This specifies the name of the
font. This name can then be used
as a value of the font-family
property in the rest of the style
sheet (as shown in the rule for
the h1> and  h2> elements).
* src
This specifies the path to the
font. In order for this technique
to work in all browsers, you will
probably need to specify paths
to a few different versions of the
font, as shown on the next page.
format
This specifies the format that the
font is supplied in. (It's discussed
in detail on the next page.)



# JPEG vs PNG vs GIF — which image format to use and when?

* TL;DR
Use JPEG format for all images that contain a natural scene or photograph where variation in colour and intensity is smooth.


* Compression
Almost all forms of data that we see on the internet — text, image, video etc.

* Transparency
In a simple form, transparency indicates something that is completely invisible. Logos and icons often need to be placed on backgrounds with variable colours.

* JPEG images don’t support transparency and are hence not usable for such cases.

* Colours
There is a significant difference in the number of colours that can be supported by these 3 formats

* Animation
Animation, in this case, refers to any change or movement in the image. It doesn’t necessarily have to have frame rates like an animated video, but essentially a part or the entire image changes with time.





















