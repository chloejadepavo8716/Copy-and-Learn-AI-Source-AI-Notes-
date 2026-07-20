# 📘 Digital Resume Documentation (Beginner-Friendly)

Think of a **website** like a **house**.

* **HTML** builds the house (walls, rooms, doors).
* **CSS** paints and decorates the house (colors, furniture, layout).

A **digital resume** is simply a webpage that introduces **you** to employers or clients.

---

# Project Structure

```
Resume Project
│
├── index.html
└── styles.css
```

* **index.html** → The content (your information).
* **styles.css** → The design (how it looks).

---

# Part 1: HTML

HTML stands for **HyperText Markup Language**.

It tells the browser:

> "Here is a heading."
>
> "Here is a paragraph."
>
> "Here is a table."

Think of HTML like labeling boxes when moving into a new house.

---

# Line-by-Line Explanation

---

## 1. Document Type

```html
<!DOCTYPE html>
```

### What is it?

This tells the browser:

> "This is an HTML5 webpage."

Without it, browsers might display your webpage incorrectly.

Imagine giving your teacher the correct type of paper before writing.

---

## 2. HTML Element

```html
<html lang="en">
```

Everything inside this tag is your webpage.

`lang="en"` tells browsers:

> "This webpage is written in English."

---

## 3. Head

```html
<head>
```

The **head** contains information **about** the webpage.

People usually don't see what's inside it.

Think of it as the settings menu of a game.

Inside the head:

---

### Character Encoding

```html
<meta charset="UTF-8">
```

This allows letters and symbols like:

```
A
B
C
@
#
₱
✓
```

to display correctly.

---

### Viewport

```html
<meta name="viewport"
content="width=device-width, initial-scale=1.0">
```

This tells phones:

> "Make the webpage fit the screen."

Without it, mobile websites often appear tiny.

---

### Title

```html
<title>Digital Resume</title>
```

Appears on the browser tab.

Example:

```
Chrome

Digital Resume
```

---

### CSS Link

```html
<link rel="stylesheet" href="styles.css">
```

This connects HTML to CSS.

Imagine plugging a lamp into electricity.

Without this line, your webpage has no styling.

---

# Body

```html
<body>
```

Everything inside the body is visible.

---

# Container

```html
<div class="container">
```

A `<div>` is simply a box.

Imagine placing all your papers inside one folder.

That's what this container does.

---

# Header

```html
<header>
```

The header is the introduction.

It usually contains:

* Name
* Profession
* Contact information

---

## Heading

```html
<h1>John Doe</h1>
```

`<h1>` is the biggest heading.

There should usually only be **one** `<h1>` on a page.

Think of it as the title of a book.

---

## Paragraph

```html
<p>
Web Developer | UI Designer
</p>
```

Paragraphs are normal text.

---

# Contact List

```html
<ul>
```

This creates an **unordered list**.

Example:

* Email
* Phone
* Website

Each item uses:

```html
<li>
```

Meaning:

**List Item**

---

# Main

```html
<main>
```

This contains the most important information.

Everything about your career goes here.

---

# Sections

```html
<section>
```

A section groups related information.

Think of chapters in a book.

Examples:

```
Summary

Skills

Education

Projects
```

Each is its own section.

---

# Headings

```html
<h2>
```

A smaller heading than `<h1>`.

Hierarchy:

```
h1
    h2
        h3
```

Just like:

```
Book
    Chapter
        Topic
```

---

# Professional Summary

```html
<p>
```

Explains who you are.

Example:

> Passionate developer...

---

# Skills

```html
<ul>
```

Displays

* HTML
* CSS
* JavaScript

Because order doesn't matter.

---

# Ordered Lists

```html
<ol>
```

Used when order matters.

Example:

1. Certificate A
2. Certificate B
3. Certificate C

---

# Tables

Tables organize information into rows and columns.

```html
<table>
```

Imagine a classroom attendance sheet.

---

## Table Header

```html
<thead>
```

Contains titles.

Example:

| Skill | Level | Experience |

---

## Table Body

```html
<tbody>
```

Contains the actual data.

Example:

| HTML | Advanced | 3 Years |

---

## Table Row

```html
<tr>
```

One horizontal row.

---

## Table Heading

```html
<th>
```

Bold heading.

Example:

```
Skill
```

---

## Table Data

```html
<td>
```

Normal information.

Example:

```
HTML
```

---

# Article

```html
<article>
```

Represents one complete item.

Example:

```
Work Experience

Frontend Developer
```

Another article:

```
Junior Developer
```

Each job is independent.

---

# Footer

```html
<footer>
```

The bottom of the webpage.

Usually contains:

* Copyright
* Links
* Contact

---

# CSS Documentation

CSS stands for

**Cascading Style Sheets**

It controls appearance.

---

# Universal Selector

```css
* {
}
```

The asterisk means:

> "Select everything."

Used for resetting default browser spacing.

---

# Margin

```css
margin:0;
```

Margin is the space **outside** an object.

Imagine two books.

The gap between them is margin.

```
Book     Book
```

---

# Padding

```css
padding:20px;
```

Padding is the space **inside** an object.

Imagine a gift box.

```
+-------------+
|             |
|   Present   |
|             |
+-------------+
```

The empty space around the present is padding.

---

# Box Sizing

```css
box-sizing:border-box;
```

Makes width calculations easier.

Instead of becoming larger when padding is added, everything stays inside the defined width.

---

# Font Family

```css
font-family:Arial;
```

Changes the writing style.

Examples:

* Arial
* Times New Roman
* Verdana

---

# Background

```css
background:#f4f4f4;
```

Changes background color.

---

# Color

```css
color:#333;
```

Changes text color.

---

# Line Height

```css
line-height:1.6;
```

Adds space between text lines.

Makes reading easier.

---

# Width

```css
width:90%;
```

Makes the container use 90% of the screen width.

---

# Max Width

```css
max-width:1000px;
```

Stops the webpage from becoming too wide on large monitors.

---

# Margin Auto

```css
margin:auto;
```

Centers the container horizontally.

---

# Display Grid

```css
display:grid;
```

Turns the layout into a grid.

Think of graph paper.

---

# Grid Columns

```css
grid-template-columns:
1fr 1fr;
```

Creates two equal columns.

```
+---------+---------+
|         |         |
|         |         |
+---------+---------+
```

`1fr` means **one fraction** of the available space.

---

# Gap

```css
gap:20px;
```

Adds space between grid items.

---

# Border Radius

```css
border-radius:10px;
```

Rounds the corners.

Without:

```
+------+
```

With:

```
(------)
```

---

# Table Border

```css
border:1px solid #ccc;
```

Creates a border around tables.

---

# Text Align

```css
text-align:center;
```

Centers text.

---

# Responsive Design

```css
@media (max-width:768px)
```

This means:

"If the screen is **768 pixels wide or smaller**, use the following rules."

Usually phones and small tablets.

---

Inside:

```css
grid-template-columns:1fr;
```

Instead of:

```
□ □
```

It becomes:

```
□
□
```

Everything stacks vertically, making it easier to read on small screens.

---

# Why Use Semantic Elements?

Instead of putting everything inside `<div>` tags, semantic elements tell browsers and developers what each part means.

| Element     | Purpose                                           |
| ----------- | ------------------------------------------------- |
| `<header>`  | Introductory content (name, title, contact)       |
| `<main>`    | The primary content of the page                   |
| `<section>` | Groups related information                        |
| `<article>` | A standalone item, such as one job or one project |
| `<footer>`  | Closing information at the bottom                 |

Semantic HTML improves accessibility, search engine optimization (SEO), and code readability.

---

# Flow of the Resume

```
HTML
│
├── Head
│   ├── Meta
│   ├── Title
│   └── CSS Link
│
└── Body
    │
    └── Container
        │
        ├── Header
        │   ├── Name
        │   ├── Profession
        │   └── Contact
        │
        ├── Main
        │   ├── Summary
        │   ├── Skills
        │   ├── Skills Table
        │   ├── Work Experience
        │   ├── Education
        │   ├── Certifications
        │   └── Projects
        │
        └── Footer
```

# Key Concepts Learned

By building this digital resume, you've practiced:

* Creating a complete HTML document structure.
* Using semantic elements like `<header>`, `<main>`, `<section>`, `<article>`, and `<footer>`.
* Organizing content with headings, paragraphs, lists, and tables.
* Linking an external CSS file to style the page.
* Using CSS for spacing, colors, typography, borders, and rounded corners.
* Building a two-column layout with CSS Grid.
* Making the layout responsive with a media query so it adapts to phones and tablets.
* Structuring a webpage in a way that is readable, maintainable, and suitable for professional use.

This project combines many of the fundamental HTML and CSS concepts you'll encounter in real-world web development and serves as a strong foundation for creating personal portfolios, résumé websites, and other structured informational pages.
