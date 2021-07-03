## Images

Controlling the size and alignment of your images using CSS keeps rules that affect the presentation of your page in the CSS and out of the HTML markup.


#### Controlling sizes of images in CSS

> You can control the size of an
image using the width and
height properties in CSS, just
like you can for any other box.

> Specifying image sizes helps
pages to load more smoothly
because the HTML and CSS
code will often load before the
images, and telling the browser
how much space to leave for an
image allows it to render the rest
of the page without waiting for
the image to download.

> You might think that your site
is likely to have images of all
different sizes, but a lot of sites
use the same sized image across
many of their pages.

![Image](https://static.javatpoint.com/csspages/images/how-to-change-image-size-in-css1.png)


### Aligning images Using CSS

> In the last chapter, you saw how
the float property can be used
to move an element to the left or
the right of its containing block,
allowing text to flow around it.

Rather than using the <img>
element's align attribute, web
page authors are increasingly
using the float property to align
images. There are two ways that
this is commonly achieved:

- The float property is added
to the class that was created to
represent the size of the image
(such as the small class in our
example).

- New classes are created with
names such as align-left or
align-right to align the images
to the left or right of the page.
These class names are used in
addition to classes that indicate
the size of the image.

![Image1](https://static.javatpoint.com/csspages/images/how-to-align-images-in-css.png)

### Centering images Using CSS

By default, images are inline
elements. This means that they
flow within the surrounding text.

In order to center an image, it
should be turned into a blocklevel element using the display
property with a value of block.

Once it has been made into a
block-level element, there are
two common ways in which you
can horizontally center an image:

- On the containing element,
you can use the text-align
property with a value of center.
- On the image itself, you can
use the use the margin property
and set the values of the left and
right margins to auto.

![Image2](https://www.designpieces.com/wp-content/uploads/2012/12/container-img.jpg)


### Background Images

The background-image
property allows you to place
an image behind any HTML
element. This could be the entire
page or just part of the page. By
default, a background image will
repeat to fill the entire box.

`The path to the image follows
the letters url, and it is put
inside parentheses and quotes`

EX:
`body {
background-image: url("images/pattern.gif");}`

----------------------------------------------------------------------------------------------------------------------


## Practical Information

>To wrap up the book we are going to look
>at some practical information that will
>help you launch a successful site


### Search Engine Optimization (SEO)

SEO is a huge topic and several books have been written on the subject.
The following pages will help you understand the key concepts so you can
improve your website's visibility on search engines.



- Use Title Tags
![Image3](https://www.greengeeks.com/blog/wp-content/uploads/2018/11/title-tags.jpg)

Perhaps one of the most important HTML tags for SEO is that of the title. This is the label of your content and how searches see your page in Google and Bing. Every result you see in a search engine is derived from the title tag.

- Fine-Tune Meta Description Tags

![Image4](https://www.greengeeks.com/blog/wp-content/uploads/2018/11/meta-description.jpg)

Another vital HTML tag for SEO is the meta description. Like titles, this information shows in search results of Google. Take a look under the link for any search. The snippet of text under the title is usually pulled from the description tag.

- Add Alt Tags in Images

![Image5](https://www.greengeeks.com/blog/wp-content/uploads/2018/11/alt-tag.jpg)

Without the ALT tag, search engines don’t know what the image is about. And this could reduce exposure during image searches.
