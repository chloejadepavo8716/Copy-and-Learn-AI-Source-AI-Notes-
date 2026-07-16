# Personal Portfolio Documentation

## What is a Personal Portfolio?

Imagine you have a giant scrapbook that tells people:

> "Hi! This is who I am. These are the things I've made. Here's how you can talk to me."



A portfolio website is exactly that, except it's on the internet.


---

## Overall Structure

<pre>
Website
│
├── Head (Information for the browser)
│
└── Body (Everything people can see)
    │
    ├── Navigation Bar
    ├── Header
    ├── Main
    │   ├── About
    │   ├── Projects
    │   └── Contact
    │
    └── Footer
</pre>

Think of it like building a LEGO house.

The **body** is the whole house.

Inside it are different rooms.


---

# 1. DOCTYPE


`<!DOCTYPE html>`


#### Explanation

Imagine telling someone,

> "Today we're building with LEGO."


Before building, everyone knows what rules to follow.

<!DOCTYPE html> tells the browser,

> "This is an HTML5 webpage."



It isn't something people see.


---

# 2. html Element

`<html lang="en">`

Everything goes inside this tag.

Think of it as a giant backpack.

Everything the website owns goes inside this backpack.

`lang="en`

This tells the browser:

> "The language is English."



It helps:

- Search engines
- Screen readers
- Translators



---

# 3. Head Element

<head>

The head is like your brain.

People cannot see your brain.

But it controls important information.

**Inside:**

<pre>
  
<code>&lt;head&gt<code>

Title
Meta information
CSS
JavaScript

<code>&lt/head&gt</code>
</pre>

---

# 4. Meta Charset


`<meta charset="UTF-8">`

Imagine you have hundreds of letters.

<pre>
A
B
C
あ
한
ñ
€
</pre>  

The browser needs to know how to read them.

UTF-8 is like saying

> "Use the world's biggest alphabet."



Without it, text may become:

<pre>
â€™
Ã©
????
</pre>


---

# 5. Viewport

`<meta name="viewport" content="width=device-width, initial-scale=1.0">`

Phones are tiny.

Computers are big.

This line tells the browser:

> "Fit the webpage to whatever screen is being used."



Without it,

your website could look tiny on phones.


---

### 6. Title

<title>Personal Portfolio</title>

This becomes

Chrome Tab

Personal Portfolio

Not inside the webpage.

Only on the browser tab.


---

### 7. Style

<style>
...
</style>

HTML builds the house.

CSS paints the house.

Without CSS:

Black text
White background
Very boring

With CSS:

Colors
Spacing
Rounded corners
Animations
Layouts


---

### 8. Universal Selector

*{

The * means

> "EVERYTHING."



Example:

Imagine a teacher saying,

> "Everyone sit down."



Not just one student.

Every student.

That's what * does.


---

### 9. Margin

margin:0;

Margin is outside space.

Imagine two books.

Book      Book

The empty space between them

is margin.


---

### 10. Padding

padding:0;

Padding is inside space.

Imagine a gift box.

+---------+
|         |
| Present |
|         |
+---------+

The empty area around the present

is padding.


---

### 11. Box-sizing

box-sizing:border-box;

Imagine a pizza box.

You order a 12-inch box.

You expect the ENTIRE box to be 12 inches.

Without border-box

adding padding makes it bigger.

With it,

the total size always stays the same.


---

### 12. Font Family

font-family: Arial, Helvetica, sans-serif;

Fonts are handwriting styles.

Like:

Comic
Neat
Fancy
Professional

The browser tries:

1. Arial


2. Helvetica


3. Any sans-serif font




---

### 13. Body

body{

This styles the whole webpage.

Think of it as painting the walls of an entire house.


---

14. Background Color

background-color:#f4f4f4;

This paints the webpage.

Like painting your bedroom walls.


---

### 15. Color

color:#333;

Changes text color.


---

### 16. Line Height

line-height:1.6;

Imagine writing in a notebook.

Hello
World

Now imagine

Hello


World

More breathing room.

That's line height.


---

Navigation

<nav>

This is the website's map.

Like signs in a mall.

Food Court →

Cinema →

Exit →

Users can jump anywhere.


---

Unordered List

<ul>

Creates a list.

•
•
•


---

List Item

<li>

Each bullet is one item.

Home
About
Projects


---

Anchor

<a href="#about">

Anchor means

> "Go somewhere."




---

If it's

href="#about"

Go to

<section id="about">

inside the same page.


---

If it's

href="https://github.com"

Go to another website.


---

Header

<header>

Usually contains

Name

Logo

Introduction


Like the cover page of a book.


---

Image

<img src="..." alt="Profile picture">

Image has two important parts.

src

Where the picture lives.

alt

Text describing the picture.

If the image fails,

people still know what it was.

Screen readers also read it.


---

Heading

<h1>

The biggest heading.

Imagine a newspaper.

Huge title.

WORLD NEWS

There should usually be only one <h1> per page.


---

Paragraph

<p>

Regular text.

Like sentences in a story.


---

Main

<main>

The main content.

Everything important goes here.

Search engines like this.

Screen readers like this.


---

Section

<section>

A chapter of the webpage.

Example:

About

Projects

Contact

Each is its own section.


---

ID

id="projects"

An ID is a unique name.

Imagine students.

John

Mary

Alex

Each has one name.

Same idea.


---

Article

<article>

A complete piece of content.

Each project card is an article.

It could stand on its own.


---

Div

<div class="projects">

A box.

Nothing more.

It groups things together.


---

Class

class="card"

A class is like giving stickers.

Imagine

🍎 Apple

🍎 Apple

🍎 Apple

Every fruit with an 🍎 sticker gets the same style.


---

Flexbox

display:flex;

Normally

A

B

C

Flexbox lets them sit beside each other.

A   B   C


---

Gap

gap:20px;

Adds space between Flexbox items.

Instead of touching,

A B C

becomes

A    B    C


---

Border Radius

border-radius:10px;

Without

□□□□

With

◻️

Rounded corners.


---

Box Shadow

box-shadow:...

Creates a shadow.

Like lifting paper off a table.


---

Footer

<footer>

The bottom of the page.

Usually contains

Copyright

Contact

Links



---

External Links

target="_blank"

Means

> "Open in a new tab."



The current page stays open.


---

Website Flow

Browser opens webpage

↓

Reads HTML

↓

Reads CSS

↓

Builds the page

↓

Shows it to the user

↓

User clicks navigation

↓

Browser jumps to the section

↓

User clicks GitHub

↓

Opens GitHub in another tab

Beginner Analogy

Think of building a website like making a comic book:

HTML is the story and the panels—it decides what is on the page.

CSS is the coloring and decoration—it decides how everything looks.

JavaScript (which you'll learn later) is the magic that makes things move and respond when you click them.


As you continue learning, you'll see this same pattern in almost every website you build:

1. Structure with HTML.


2. Style with CSS.


3. Interactivity with JavaScript.



Once you're comfortable with these three layers, you'll be able to understand and create increasingly complex web applications.
