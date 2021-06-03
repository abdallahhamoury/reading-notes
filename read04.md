 # What is CSS


Browser compatibility
What's next
In this module
What is CSS?
Overview: First steps
Next
CSS **(Cascading Style Sheets)** allows you to create great-looking web pages, but how does it work under the hood? This article explains what CSS is, with a simple syntax example, and also covers some key terms about the language.

> * Prerequisites:Basic computer literacy, basic software installed, basic knowledge of working with files, and HTML basics
> * Objective: To learn what CSS

![Css](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS/html-example.png)

## What is CSS for

`As we have mentioned before, CSS is a language for specifying how documents are presented to users — how they are styled, laid out, etc.`


A **document** is usually a text file structured using a markup language — HTML is the most common markup language, but you may also come across other markup languages such as SVG or XML.

**Presenting** a document to a user means converting it into a form usable by your audience. Browsers, like Firefox, Chrome, or Edge , are designed to present documents visually, for example, on a computer screen, projector or printer.

### Browser support information

Once CSS has been specified then it is only useful for us in developing web pages if one or more browsers have implemented it. This means that the code has been written to turn the instruction in our CSS file into something that can be output to the screen. We'll look at this process more in the lesson How CSS works. It is unusual for all browsers to implement a feature at the same time, and so there is usually a gap where you can use some part of CSS in some browsers and not in others. For this reason, being able to check implementation status is useful.

-----------------------------------
### CSS color Property

#### Ex
----------------------------------------
body {
  color: red;
}

h1 {
  color: #00ff00;
}

p.ex {
  color: rgb(0,0,255);
}

---------------------------------

[more details ](https://www.w3schools.com/cssref/pr_text_color.asp)
