# How to build your first website

## What is HTML?

HTML stands for hyper text markup langauge.  Let's break down what all that means.

## Hyper Text

This is referring to a feature that allows you to write code that can link one page to another page. 

## Markup

This is pointing to the idea that you will "markup" with tags or elements.  A tag or element represent various things on your webpage, like paragraphs, images, and links.  Notice you have an open tag and a closing tag. The opening tag is `<p>` and the closing tag is `</p>`.  The closing tag has a / at the beginning of the tag.

```html
<p>This a paragraph</p>
```

## HTML is like a house without any paint

HTML provides what is suppose to be on the page but does not control the look or style of the page.



```html
<!DOCTYPE html>
    <html>
        <title>HTML Tutorial</title>
    <body>

        <h1>This is a heading</h1>
        <p>This is a paragraph.</p>

    </body>
</html>
```
- DOCTYPE tag is a special tags that let's the browser know it's are dealing with an HTML 5 webpage
- All other html tags must be inside the `<html></html>` tag.
- head tag contains meta data about the website, like SEO information.  Most of the data can not be seen by the vistor.
- The title tag in the head tag controls tab name for the page.
- All the tags in the body tag are visible to the user by default.
- h1 tag means header 1 and is usually the title of your web page
- p is a paragraph tag and is used for displaying text.

## What is CSS?

CSS stands for cascade style sheets.  They are used for controlling the look of your site.  The word cascade is meant to indicate that styles on the bottom of your site will override styles on the top of your site.  Meaning if they conflict the last style will win.

## Breaking down CSS?

The style above will make the background color of our website purple.


```css
body {
    background-color: purple;
}
```

### How to create a style


1\. Type the name of the element you want to style

2\. Then type in curly braces {}

3\. Type in the property you want to style, in the example above the property is background-color.

4\. Type in the value that you want the property to have.  In our case that's purple. 

