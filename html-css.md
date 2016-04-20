class: center, middle

![The Iron Yard Shield](http://i.imgur.com/qvZMscb.png)

---
class: middle

## About Me

* Started coding 2015
* Went through the Iron Yard Front End Engineering course
* Currently a TA at the TIY Durham campus
* Loves cats

---
class: center, middle, inverse

## What About You?

---
class: middle

## What is HTML?

* "HyperText Markup Language"
* Structures content on the page
* **HyperText** is the method by which you move around on the web by clicking on special text called hyperlinks. Hyper just means it's not linear - i.e. you can go to any place on the Internet whenever you want by clicking on links - there is no set order to do things in.
* **Markup** is what HTML tags do to the text inside them. They mark it as a certain type of text (italicised text, for example).
* But first and foremost, HTML is a **language**

---
class: center

HTML provides a structure for your site - a skeleton of content.

![spooky](http://i.imgur.com/H6B0LWo.png)

---
class: middle

## What does HTML look like?

```HTML
<tag-name="attribute value">
  <!--tag contents-->
</tag-name>
```
```HTML
  <a href="http://www.google.com">Google</a>
```

```HTML
  <p>Cats are cool!</p>
```

And sometimes there's self-closing tags...

```HTML
<img src="http://placebear.com/g/400/200" alt="bears!!">
```

Let's check out an example!

---
Following is the basic structure, tagwise, for a basic html document

```html
<!-- This is a comment -->
<!DOCTYPE html>
<html>
  <head>
    <title>This is a title</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
    <!-- The <head> tag usually contains any external CSS
    stylesheets or meta information about a particular page -->
  </head>
  <body>
  <!-- The <body> tag is where human-viewable content is stored -->
  </body>
</html>

```

---
class: center, middle, inverse

## Now it's your turn!

---
class: middle

## Go to ```codepen.io```

## You might want to use...

* body
* h1, h2, h3
* p
* links

---
class: center, middle, inverse

## Pop Quiz!

What does HTML provide for your site? (hint: skeleton)

---
class: middle
## Intro to CSS
* What is CSS and how does it differ from HTML?

	* Cascading Style Sheets.

	* CSS defines how HTML elements are displayed. It can't be used without HTML.

	* Primary purpose: separating content from design.

	* CSS should always be written after your basic HTML.

---
class: middle
## CSS Selectors

* What is a selector and how does it look on the page?

* Basic CSS consists of three parts:

```css
selector {
property: value;
}
```

* The selector is the element that you want to style. The property is the actual property title, and the value is the style you apply to that property.


```css
body {
background: DodgerBlue;
font-family: "Trebuchet MS", Verdana, serif;
}
```

---

```css
/* This is a CSS comment */
body {
  background-color: red;
  font-size: 20px;
  font-weight: strong;
}

```

---
class: middle, center, inverse
## Let's add some CSS for our intrepid heroes.

---
class: middle, center, inverse

## Now let's make your site beautiful.

---
class: middle
## You might want to use...

* font-size
* background
* color

---
class: middle, center, inverse

## Pop Quiz!

Should you write HTML or CSS first?

---
class: middle, center

Thank you for coming! Please keep playing around with your sites!
