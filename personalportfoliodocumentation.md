# Personal Portfolio Documentation

> This README is a GitHub-ready version of the documentation.

## What is a Personal Portfolio?

A **personal portfolio** is a website that introduces you, showcases
your work, and provides ways for people to contact you.

Typical information includes:

-   Your name
-   A short introduction
-   Your skills
-   Your projects
-   Contact information
-   Links to social media or professional profiles

------------------------------------------------------------------------

# Overall Structure

``` text
Website
│
├── Head (Information for the browser)
│
└── Body (Everything people can see)
    ├── Navigation Bar
    ├── Header
    ├── Main
    │   ├── About
    │   ├── Projects
    │   └── Contact
    └── Footer
```

## `<!DOCTYPE html>`

``` html
<!DOCTYPE html>
```

Declares that the document uses the HTML5 standard.

## `<html lang="en">`

The root element of every HTML document. The `lang` attribute specifies
the document language.

## `<head>`

Contains metadata such as the title, character encoding, viewport
settings, CSS, and JavaScript.

``` html
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
</head>
```

## `<meta charset="UTF-8">`

Defines the character encoding used by the webpage.

## Viewport

``` html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Allows the webpage to scale correctly on different screen sizes.

## `<title>`

Sets the title shown in the browser tab.

## `<style>`

Contains CSS rules used to style the webpage.

## Universal Selector

``` css
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
}
```

Applies styles to every element.

## Margin

Space outside an element.

## Padding

Space inside an element.

## Box Sizing

``` css
box-sizing:border-box;
```

Makes width and height include padding and borders.

## Font Family

Specifies preferred fonts.

## Body

Styles the entire webpage.

## Background Color

Sets the background color.

## Text Color

Sets the text color.

## Line Height

Controls spacing between lines.

## `<nav>`

Defines the website navigation.

## `<ul>` and `<li>`

Create unordered lists and list items.

## `<a>`

Creates hyperlinks.

-   Internal: `href="#about"`
-   External: `href="https://github.com"`

## `<header>`

Contains introductory content.

## `<img>`

Displays an image.

-   `src` --- image location
-   `alt` --- alternative text

## `<h1>`

Primary page heading.

## `<p>`

Paragraph element.

## `<main>`

Contains the primary content.

## `<section>`

Groups related content.

## `id`

Unique identifier for an element.

## `<article>`

Represents self-contained content.

## `<div>`

Generic container for grouping elements.

## `class`

Reusable identifier shared by multiple elements.

## Flexbox

``` css
display:flex;
```

Creates flexible layouts.

## Gap

``` css
gap:20px;
```

Adds spacing between flex or grid items.

## Border Radius

Rounds corners.

## Box Shadow

Adds depth with shadows.

## `<footer>`

Contains footer information such as copyright and contact links.

## `target="_blank"`

Opens a link in a new browser tab.

## Website Rendering Flow

``` text
Browser opens webpage
↓
Reads HTML
↓
Reads CSS
↓
Builds the page
↓
Displays the webpage
↓
User interacts with the page
```

# Beginner Analogy

-   **HTML** provides the structure.
-   **CSS** provides the appearance.
-   **JavaScript** provides interactivity.

Modern websites combine all three technologies.
