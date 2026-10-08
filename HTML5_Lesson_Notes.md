# HTML5 — Full Lesson Notes

## Course Topic

**HTML5: HTML Document Structure, Elements, Attributes, Text, Links, Lists, Tables, Multimedia, Metadata and Semantic HTML5**

---

## 1. Introduction to HTML5

**HTML** stands for **HyperText Markup Language**. It is the standard markup language used to create and structure content on web pages.

HTML is **not a programming language**. It is a **markup language** because it uses elements/tags to describe the structure and meaning of web content.

HTML5 is the modern version of HTML and provides support for:

- Structured web pages
- Semantic page elements
- Images
- Audio
- Video
- Forms
- Tables
- Metadata
- Multimedia
- Modern web applications

### Basic HTML5 Example

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Web Page</title>
</head>

<body>
    <h1>Welcome to HTML5</h1>
    <p>This is my first web page.</p>
</body>
</html>
```

---

# 2. HTML5 Document Structure

A standard HTML5 document has the following basic structure:

```html
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>My Web Page</title>
</head>

<body>

    <h1>Welcome</h1>
    <p>This is a web page.</p>

</body>
</html>
```

### Explanation

| Element | Purpose |
|---|---|
| `<!DOCTYPE html>` | Declares that the document uses HTML5 |
| `<html>` | Root element of the document |
| `<head>` | Contains information about the document |
| `<meta>` | Provides metadata |
| `<title>` | Defines the browser tab title |
| `<body>` | Contains visible page content |

### Complete Example

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Computing Department</title>
</head>

<body>

    <h1>Computing Department</h1>

    <p>
        Welcome to the Computing Department.
        We offer programs in Computer Science and Information Technology.
    </p>

</body>

</html>
```

---

# 3. The `<!DOCTYPE html>` Declaration

The first line of an HTML5 document should normally be:

```html
<!DOCTYPE html>
```

It tells the browser that the document should be interpreted as an HTML5 document.

It is **not an HTML element**.

### Example

```html
<!DOCTYPE html>
<html>
    <body>
        <h1>HTML5</h1>
    </body>
</html>
```

---

# 4. The `<html>` Element

The `<html>` element is the root of the entire HTML document.

```html
<html>

    <!-- Other HTML elements go here -->

</html>
```

It is common to specify the language:

```html
<html lang="en">
```

For a Kiswahili page:

```html
<html lang="sw">
```

### Example

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <title>My Website</title>
</head>

<body>

    <h1>Hello World</h1>

</body>

</html>
```

---

# 5. HTML Elements

An HTML element normally consists of:

```html
<tag>Content</tag>
```

For example:

```html
<p>Hello World</p>
```

Here:

- `<p>` is the opening tag
- `Hello World` is the content
- `</p>` is the closing tag

Another example:

```html
<h1>Introduction to HTML</h1>
```

## 5.1 Nested Elements

HTML elements can be placed inside other elements.

```html
<p>
    Welcome to
    <strong>HTML5</strong>
    development.
</p>
```

Another example:

```html
<div>
    <h1>Computing Department</h1>
    <p>Welcome to our department.</p>
</div>
```

The `<h1>` and `<p>` elements are inside the `<div>`.

---

# 6. HTML Attributes

Attributes provide additional information about an HTML element.

General syntax:

```html
<tag attribute="value">
```

Example:

```html
<p id="intro">Welcome to HTML5.</p>
```

Here:

- `p` = element
- `id` = attribute
- `"intro"` = attribute value

### Example

```html
<p id="paragraph1" class="important">
    This is an important paragraph.
</p>
```

## Common Attributes

```text
id
class
style
title
href
src
alt
width
height
lang
target
```

### Attribute Examples

```html
<h1 id="main-heading">HTML5 Lesson</h1>

<p class="intro">
    Welcome to the lesson.
</p>

<img src="campus.jpg" alt="University campus">

<a href="about.html" target="_blank">
    About Us
</a>
```

---

# 7. Headings

HTML provides six levels of headings:

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

### Example

```html
<h1>Computing Department</h1>

<h2>Computer Science</h2>

<h3>Year One</h3>

<h4>Semester One</h4>

<h5>Web Technologies</h5>

<h6>HTML5 Introduction</h6>
```

### Important

`<h1>` should normally represent the main heading of the page.

Use headings according to their **meaning and hierarchy**, not simply because one looks bigger.

---

# 8. Paragraphs

Paragraphs are created using `<p>`.

```html
<p>This is a paragraph.</p>
```

Multiple paragraphs:

```html
<p>
    HTML is used to structure web pages.
</p>

<p>
    CSS is used to style web pages.
</p>

<p>
    JavaScript is used to add behaviour and interactivity.
</p>
```

### Paragraph with Formatting

```html
<p>
    HTML is <strong>important</strong> for web development.
</p>
```

---

# 9. Line Breaks

The `<br>` element creates a line break.

```html
<p>
    Thomas Kinyanjui Njoroge<br>
    Computing Department<br>
    Karatina University
</p>
```

`<br>` does not require a closing tag.

### Another Example

```html
<p>
    HTML<br>
    CSS<br>
    JavaScript
</p>
```

---

# 10. Horizontal Rule

The `<hr>` element creates a thematic horizontal break.

```html
<h1>About Us</h1>

<p>We provide computing education.</p>

<hr>

<h2>Our Programmes</h2>

<p>Computer Science and Information Technology.</p>
```

---

# 11. Text Formatting

HTML provides several elements for giving meaning or emphasis to text.

## 11.1 Strong Text

```html
<strong>Important information</strong>
```

Example:

```html
<p>
    <strong>Warning:</strong> Submit your assignment before the deadline.
</p>
```

---

## 11.2 Emphasized Text

```html
<em>This is emphasized text.</em>
```

Example:

```html
<p>
    HTML is <em>very important</em> in web development.
</p>
```

---

## 11.3 Bold Using `<b>`

```html
<b>Computer Science</b>
```

`<b>` draws attention to text without necessarily indicating importance.

---

## 11.4 Italic Using `<i>`

```html
<i>Artificial Intelligence</i>
```

---

## 11.5 Underlined Text

```html
<u>Important text</u>
```

Example:

```html
<p>
    <u>Read the instructions carefully.</u>
</p>
```

---

## 11.6 Highlighted Text

HTML5 provides `<mark>`.

```html
<p>
    HTML5 is <mark>important</mark> for web development.
</p>
```

---

## 11.7 Deleted Text

```html
<del>Old price: KSh 5,000</del>
```

Example:

```html
<p>
    <del>KSh 5,000</del> KSh 3,500
</p>
```

---

## 11.8 Inserted Text

```html
<ins>New information</ins>
```

---

## 11.9 Subscript

```html
H<sub>2</sub>O
```

Result:

**H₂O**

---

## 11.10 Superscript

```html
x<sup>2</sup>
```

Result:

**x²**

Another example:

```html
E = mc<sup>2</sup>
```

---

## 11.11 Small Text

```html
<small>Terms and conditions apply.</small>
```

---

## 11.12 Combined Formatting

```html
<p>
    HTML is <strong>very important</strong> for
    <em>web development</em>.
</p>
```

---

# 12. Hyperlinks

Hyperlinks are created using the `<a>` element.

Basic syntax:

```html
<a href="URL">Link Text</a>
```

### Example

```html
<a href="https://www.google.com">
    Visit Google
</a>
```

---

## 12.1 Link to Another Page

```html
<a href="about.html">
    About Us
</a>
```

---

## 12.2 Link to a Department Page

```html
<a href="computing.html">
    Computing Department
</a>
```

---

## 12.3 Open Link in New Tab

```html
<a href="https://www.google.com" target="_blank">
    Open Google
</a>
```

A safer modern pattern for an external link is:

```html
<a href="https://www.google.com"
   target="_blank"
   rel="noopener noreferrer">
    Open Google
</a>
```

---

## 12.4 Email Link

```html
<a href="mailto:info@example.com">
    Email Us
</a>
```

---

## 12.5 Telephone Link

```html
<a href="tel:+254700000000">
    Call Us
</a>
```

---

## 12.6 Link to a Section on the Same Page

First create an ID:

```html
<h2 id="courses">Our Courses</h2>
```

Then link to it:

```html
<a href="#courses">
    View Courses
</a>
```

Complete example:

```html
<h1>Computing Department</h1>

<a href="#courses">Jump to Courses</a>

<p>
    This is some information about the department.
</p>

<p>
    More information about the department.
</p>

<h2 id="courses">Courses Offered</h2>

<ul>
    <li>Computer Science</li>
    <li>Information Technology</li>
</ul>
```

---

# 13. Lists

HTML supports several types of lists.

## 13.1 Unordered List

An unordered list uses `<ul>` and `<li>`.

```html
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
```

### Example

```html
<h2>Programming Languages</h2>

<ul>
    <li>Python</li>
    <li>Java</li>
    <li>JavaScript</li>
    <li>C++</li>
</ul>
```

---

# 14. Ordered Lists

An ordered list uses `<ol>`.

```html
<ol>
    <li>Open your browser</li>
    <li>Create an HTML file</li>
    <li>Write your code</li>
    <li>Save the file</li>
    <li>Open it in the browser</li>
</ol>
```

## 14.1 Changing the Starting Number

```html
<ol start="5">
    <li>Fifth item</li>
    <li>Sixth item</li>
    <li>Seventh item</li>
</ol>
```

## 14.2 Reversed List

```html
<ol reversed>
    <li>Third</li>
    <li>Second</li>
    <li>First</li>
</ol>
```

---

# 15. Description Lists

Description lists use:

```html
<dl>
    <dt>Term</dt>
    <dd>Description</dd>
</dl>
```

Example:

```html
<dl>

    <dt>HTML</dt>
    <dd>Structures web pages.</dd>

    <dt>CSS</dt>
    <dd>Styles web pages.</dd>

    <dt>JavaScript</dt>
    <dd>Adds behaviour and interactivity.</dd>

</dl>
```

---

# 16. Nested Lists

Lists can contain other lists.

```html
<ul>

    <li>
        Programming
        <ul>
            <li>Python</li>
            <li>Java</li>
            <li>C++</li>
        </ul>
    </li>

    <li>
        Web Development
        <ul>
            <li>HTML</li>
            <li>CSS</li>
            <li>JavaScript</li>
        </ul>
    </li>

</ul>
```

---

# 17. HTML Tables

Tables are used to display tabular data.

Main elements:

```text
<table>
<tr>
<th>
<td>
<thead>
<tbody>
<tfoot>
```

### Basic Table

```html
<table border="1">

    <tr>
        <th>Name</th>
        <th>Course</th>
        <th>Year</th>
    </tr>

    <tr>
        <td>John</td>
        <td>Computer Science</td>
        <td>Year 1</td>
    </tr>

    <tr>
        <td>Mary</td>
        <td>Information Technology</td>
        <td>Year 2</td>
    </tr>

</table>
```

> In modern HTML, CSS should normally be used for table borders and presentation rather than the old `border` attribute.

---

# 18. Table with Semantic Sections

```html
<table>

    <thead>
        <tr>
            <th>Student Name</th>
            <th>Course</th>
            <th>Marks</th>
        </tr>
    </thead>

    <tbody>

        <tr>
            <td>John</td>
            <td>Web Technologies</td>
            <td>78</td>
        </tr>

        <tr>
            <td>Mary</td>
            <td>Web Technologies</td>
            <td>85</td>
        </tr>

    </tbody>

    <tfoot>
        <tr>
            <td colspan="2">Average</td>
            <td>81.5</td>
        </tr>
    </tfoot>

</table>
```

---

# 19. Table Caption

Use `<caption>` to describe the table.

```html
<table>

    <caption>Student Examination Results</caption>

    <tr>
        <th>Name</th>
        <th>Marks</th>
    </tr>

    <tr>
        <td>John</td>
        <td>75</td>
    </tr>

</table>
```

---

# 20. `colspan`

`colspan` allows a cell to span multiple columns.

```html
<table>

    <tr>
        <th colspan="3">Student Information</th>
    </tr>

    <tr>
        <th>Name</th>
        <th>Course</th>
        <th>Year</th>
    </tr>

    <tr>
        <td>John</td>
        <td>Computer Science</td>
        <td>3</td>
    </tr>

</table>
```

---

# 21. `rowspan`

`rowspan` allows a cell to span multiple rows.

```html
<table>

    <tr>
        <th>Name</th>
        <th>Course</th>
    </tr>

    <tr>
        <td rowspan="2">John</td>
        <td>HTML</td>
    </tr>

    <tr>
        <td>CSS</td>
    </tr>

</table>
```

---

# 22. Images

Images are inserted using `<img>`.

Basic syntax:

```html
<img src="image.jpg" alt="Description">
```

Example:

```html
<img src="university.jpg"
     alt="University campus">
```

---

## 22.1 Image with Width and Height

```html
<img src="computer.jpg"
     alt="Desktop computer"
     width="500"
     height="300">
```

CSS is generally preferred for controlling presentation dimensions, but HTML `width` and `height` can also communicate intrinsic dimensions.

---

## 22.2 Image from a Folder

Suppose your project has:

```text
website/
│
├── index.html
│
└── images/
    └── campus.jpg
```

Use:

```html
<img src="images/campus.jpg"
     alt="University campus">
```

---

# 23. Importance of `alt`

The `alt` attribute provides alternative text.

Good:

```html
<img src="student.jpg"
     alt="Student using a laptop in a computer laboratory">
```

Poor:

```html
<img src="student.jpg"
     alt="image">
```

Decorative image:

```html
<img src="decoration.png" alt="">
```

---

# 24. Audio

HTML5 allows audio to be embedded directly.

```html
<audio controls>
    <source src="lecture.mp3" type="audio/mpeg">
</audio>
```

### Multiple Formats

```html
<audio controls>

    <source src="lecture.mp3" type="audio/mpeg">
    <source src="lecture.ogg" type="audio/ogg">

    Your browser does not support audio.

</audio>
```

---

## 24.1 Audio with Autoplay

```html
<audio controls autoplay>
    <source src="music.mp3" type="audio/mpeg">
</audio>
```

Autoplay may be blocked by browsers, especially when audio is unmuted.

---

## 24.2 Looping Audio

```html
<audio controls loop>
    <source src="music.mp3" type="audio/mpeg">
</audio>
```

---

# 25. Video

HTML5 also supports video.

```html
<video controls width="640">

    <source src="lecture.mp4" type="video/mp4">

    Your browser does not support video.

</video>
```

---

## 25.1 Video with Height

```html
<video controls
       width="640"
       height="360">

    <source src="lesson.mp4" type="video/mp4">

</video>
```

---

## 25.2 Video with Poster Image

```html
<video controls
       width="640"
       poster="thumbnail.jpg">

    <source src="lesson.mp4" type="video/mp4">

</video>
```

The poster is displayed before the video starts.

---

## 25.3 Video with Multiple Formats

```html
<video controls>

    <source src="lesson.mp4" type="video/mp4">
    <source src="lesson.webm" type="video/webm">

    Your browser does not support video.

</video>
```

---

# 26. Metadata

Metadata provides information about the HTML document.

Metadata is normally placed inside `<head>`.

## 26.1 Character Encoding

```html
<meta charset="UTF-8">
```

UTF-8 supports a very large range of characters.

---

## 26.2 Viewport Metadata

Important for responsive web pages:

```html
<meta name="viewport"
      content="width=device-width, initial-scale=1.0">
```

---

## 26.3 Description

```html
<meta name="description"
      content="Computing Department website">
```

---

## 26.4 Keywords

```html
<meta name="keywords"
      content="HTML, CSS, JavaScript, computing">
```

---

## 26.5 Author

```html
<meta name="author"
      content="Computing Department">
```

---

## 26.6 Complete Head Example

```html
<head>

    <meta charset="UTF-8">

    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">

    <meta name="description"
          content="Computing Department website">

    <meta name="author"
          content="Computing Department">

    <title>Computing Department</title>

</head>
```

---

# 27. Semantic HTML5

Semantic HTML means using elements that clearly describe their purpose and meaning.

Instead of:

```html
<div>
    ...
</div>
```

HTML5 provides elements such as:

```text
<header>
<nav>
<main>
<section>
<article>
<aside>
<footer>
```

These make the structure of a page clearer to browsers, developers, search engines and assistive technologies.

---

# 28. `<header>`

The `<header>` element represents introductory content.

```html
<header>

    <h1>Computing Department</h1>

    <p>School of Computing and Informatics</p>

</header>
```

A page can also have headers within sections or articles.

---

# 29. `<nav>`

The `<nav>` element contains navigation links.

```html
<nav>

    <a href="index.html">Home</a>
    <a href="about.html">About</a>
    <a href="courses.html">Courses</a>
    <a href="contact.html">Contact</a>

</nav>
```

A better structured version:

```html
<nav>
    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="courses.html">Courses</a></li>
        <li><a href="contact.html">Contact</a></li>
    </ul>
</nav>
```

---

# 30. `<main>`

`<main>` contains the primary content of a document.

```html
<main>

    <h1>Computer Science</h1>

    <p>
        Computer Science is the study of computation,
        algorithms and information systems.
    </p>

</main>
```

A page should normally have one main `<main>` element.

---

# 31. `<section>`

A section groups related content.

```html
<section>

    <h2>About the Department</h2>

    <p>
        The department offers computing programmes.
    </p>

</section>
```

Another example:

```html
<section>

    <h2>Our Programmes</h2>

    <ul>
        <li>BSc Computer Science</li>
        <li>BSc Information Technology</li>
    </ul>

</section>
```

---

# 32. `<article>`

An `<article>` represents a self-contained piece of content.

Examples include:

- News article
- Blog post
- Magazine article
- Forum post
- Announcement

```html
<article>

    <h2>New Computing Laboratory Opened</h2>

    <p>
        The department has opened a new computer laboratory.
    </p>

</article>
```

Multiple articles:

```html
<section>

    <h2>Latest News</h2>

    <article>
        <h3>New Laboratory</h3>
        <p>A new laboratory has been opened.</p>
    </article>

    <article>
        <h3>Student Innovation</h3>
        <p>Students developed a new software application.</p>
    </article>

</section>
```

---

# 33. `<aside>`

`<aside>` contains related or secondary content.

```html
<aside>

    <h2>Quick Links</h2>

    <ul>
        <li><a href="#">Student Portal</a></li>
        <li><a href="#">Library</a></li>
        <li><a href="#">Email</a></li>
    </ul>

</aside>
```

It can also be used for:

- Sidebars
- Related information
- Advertisements
- Additional notes

---

# 34. `<footer>`

The `<footer>` contains footer information.

```html
<footer>

    <p>
        &copy; 2026 Computing Department.
    </p>

</footer>
```

Another example:

```html
<footer>

    <p>Contact: computing@example.com</p>

    <p>
        &copy; 2026 Computing Department
    </p>

</footer>
```

---

# 35. Complete Semantic HTML5 Page

```html
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">

    <meta name="description"
          content="Computing Department website">

    <meta name="author"
          content="Computing Department">

    <title>Computing Department</title>

</head>

<body>

    <header>

        <h1>Computing Department</h1>

        <p>School of Computing and Informatics</p>

    </header>


    <nav>

        <ul>
            <li>
                <a href="index.html">Home</a>
            </li>

            <li>
                <a href="about.html">About</a>
            </li>

            <li>
                <a href="courses.html">Courses</a>
            </li>

            <li>
                <a href="contact.html">Contact</a>
            </li>
        </ul>

    </nav>


    <main>

        <section>

            <h2>About the Department</h2>

            <p>
                The Computing Department provides education
                and training in modern computing technologies.
            </p>

        </section>


        <section>

            <h2>Programmes</h2>

            <ul>
                <li>Computer Science</li>
                <li>Information Technology</li>
                <li>Data Science</li>
            </ul>

        </section>


        <section>

            <h2>Latest News</h2>

            <article>

                <h3>New Computer Laboratory</h3>

                <p>
                    A new computer laboratory has been
                    established to support practical learning.
                </p>

            </article>

        </section>


        <aside>

            <h2>Quick Links</h2>

            <a href="#">Student Portal</a><br>
            <a href="#">Library</a>

        </aside>

    </main>


    <footer>

        <p>
            &copy; 2026 Computing Department.
        </p>

    </footer>

</body>

</html>
```

---

# 36. `<div>` Element

`<div>` is a generic block-level container.

```html
<div>
    <h2>Student Information</h2>
    <p>Name: John</p>
    <p>Course: Computer Science</p>
</div>
```

It has no special semantic meaning.

It is commonly used together with CSS and JavaScript.

---

# 37. `<span>` Element

`<span>` is a generic inline container.

```html
<p>
    My favourite colour is
    <span>blue</span>.
</p>
```

It is useful when a small portion of text needs styling or scripting.

Example:

```html
<p>
    The price is
    <span>KSh 2,500</span>.
</p>
```

---

# 38. HTML Comments

Comments are ignored by the browser.

```html
<!-- This is a comment -->
```

Example:

```html
<!-- Department heading -->
<h1>Computing Department</h1>
```

Multiple lines:

```html
<!--
    This section contains
    information about our programmes.
-->
```

Comments are useful for documenting code.

---

# 39. HTML Entities

Some characters have special meanings in HTML.

```text
&lt;
&gt;
&amp;
&quot;
&apos;
&nbsp;
```

### Examples

Less than:

```html
&lt;
```

Greater than:

```html
&gt;
```

Ampersand:

```html
&amp;
```

Copyright:

```html
&copy;
```

Example:

```html
<footer>
    <p>&copy; 2026 Computing Department</p>
</footer>
```

---

# 40. Special Characters

```html
<p>
    Copyright &copy; 2026
</p>

<p>
    10 &lt; 20
</p>

<p>
    20 &gt; 10
</p>

<p>
    HTML &amp; CSS
</p>
```

---

# 41. `<figure>` and `<figcaption>`

HTML5 provides `<figure>` for self-contained media/content.

```html
<figure>

    <img src="laboratory.jpg"
         alt="Computing laboratory">

    <figcaption>
        Computing Department Laboratory
    </figcaption>

</figure>
```

This is useful for:

- Images
- Diagrams
- Charts
- Illustrations
- Code examples

---

# 42. `<details>` and `<summary>`

These elements create expandable information.

```html
<details>

    <summary>What is HTML?</summary>

    <p>
        HTML is the standard markup language
        used to structure web pages.
    </p>

</details>
```

Another example:

```html
<details>

    <summary>View Course Information</summary>

    <p>
        This course introduces students to web technologies.
    </p>

</details>
```

---

# 43. `<time>`

The `<time>` element represents dates and times.

```html
<p>
    The lecture starts at
    <time>08:00</time>.
</p>
```

Date:

```html
<time datetime="2026-10-08">
    8 October 2026
</time>
```

Date and time:

```html
<time datetime="2026-10-08T08:00">
    8 October 2026 at 8:00 AM
</time>
```

---

# 44. `<address>`

Used for contact information.

```html
<address>

    Computing Department<br>
    School of Computing and Informatics<br>
    Email: computing@example.com

</address>
```

---

# 45. HTML5 Page Structure

A typical page can be organized as:

```text
HTML Document
│
├── HEAD
│   ├── Character Encoding
│   ├── Viewport
│   ├── Description
│   └── Title
│
└── BODY
    │
    ├── HEADER
    │
    ├── NAVIGATION
    │
    ├── MAIN
    │   │
    │   ├── SECTION
    │   │
    │   ├── ARTICLE
    │   │
    │   └── ASIDE
    │
    └── FOOTER
```

Equivalent HTML:

```html
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">

    <title>My Website</title>

</head>

<body>

    <header>
        ...
    </header>

    <nav>
        ...
    </nav>

    <main>

        <section>
            ...
        </section>

        <article>
            ...
        </article>

        <aside>
            ...
        </aside>

    </main>

    <footer>
        ...
    </footer>

</body>

</html>
```

---

# 46. Complete HTML5 Example — Student Portal

This example combines many elements taught in the lesson.

```html
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport"
          content="width=device-width, initial-scale=1.0">

    <meta name="description"
          content="Student Portal">

    <meta name="author"
          content="Computing Department">

    <title>Student Portal</title>

</head>

<body>

    <!-- Header -->

    <header>

        <h1>Student Portal</h1>

        <p>
            Welcome to the
            <strong>Computing Department</strong>.
        </p>

    </header>


    <!-- Navigation -->

    <nav>

        <ul>

            <li>
                <a href="#home">Home</a>
            </li>

            <li>
                <a href="#courses">Courses</a>
            </li>

            <li>
                <a href="#students">Students</a>
            </li>

            <li>
                <a href="#contact">Contact</a>
            </li>

        </ul>

    </nav>


    <!-- Main Content -->

    <main>

        <section id="home">

            <h2>Welcome</h2>

            <p>
                This portal provides information
                about computing programmes.
            </p>

            <figure>

                <img src="computer-lab.jpg"
                     alt="Students working in a computer laboratory"
                     width="600">

                <figcaption>
                    Students in the computer laboratory
                </figcaption>

            </figure>

        </section>


        <section id="courses">

            <h2>Courses</h2>

            <ol>

                <li>Web Technologies</li>
                <li>Database Systems</li>
                <li>Computer Networks</li>
                <li>Artificial Intelligence</li>

            </ol>

        </section>


        <section id="students">

            <h2>Student Results</h2>

            <table>

                <caption>
                    Student Examination Results
                </caption>

                <thead>

                    <tr>
                        <th>Name</th>
                        <th>Course</th>
                        <th>Marks</th>
                    </tr>

                </thead>

                <tbody>

                    <tr>
                        <td>John Mwangi</td>
                        <td>Web Technologies</td>
                        <td>82</td>
                    </tr>

                    <tr>
                        <td>Mary Wanjiku</td>
                        <td>Web Technologies</td>
                        <td>76</td>
                    </tr>

                    <tr>
                        <td>Peter Otieno</td>
                        <td>Web Technologies</td>
                        <td>89</td>
                    </tr>

                </tbody>

            </table>

        </section>


        <section>

            <h2>Learning Resources</h2>

            <ul>

                <li>
                    <a href="notes.html">
                        Lecture Notes
                    </a>
                </li>

                <li>
                    <a href="assignments.html">
                        Assignments
                    </a>
                </li>

                <li>
                    <a href="resources.html">
                        Additional Resources
                    </a>
                </li>

            </ul>

        </section>


        <section>

            <h2>Lecture Video</h2>

            <video controls
                   width="640">

                <source src="html5-lesson.mp4"
                        type="video/mp4">

                Your browser does not support video.

            </video>

        </section>


        <aside>

            <h2>Important Notice</h2>

            <p>
                <mark>Assignment submission</mark>
                closes on Friday.
            </p>

        </aside>

    </main>


    <!-- Footer -->

    <footer id="contact">

        <address>

            Computing Department<br>
            School of Computing and Informatics<br>
            Email:
            <a href="mailto:computing@example.com">
                computing@example.com
            </a>

        </address>

        <p>
            &copy; 2026 Computing Department.
        </p>

    </footer>

</body>

</html>
```

---

# 47. HTML5 Elements — Quick Reference

| Element | Purpose |
|---|---|
| `html` | Root of document |
| `head` | Document metadata |
| `title` | Browser page title |
| `meta` | Metadata |
| `body` | Visible page content |
| `h1`–`h6` | Headings |
| `p` | Paragraph |
| `br` | Line break |
| `hr` | Thematic break |
| `strong` | Strong importance |
| `em` | Emphasis |
| `b` | Attention without added semantic importance |
| `i` | Alternate voice/mood |
| `u` | Non-textual annotation |
| `mark` | Highlighted text |
| `del` | Deleted content |
| `ins` | Inserted content |
| `sub` | Subscript |
| `sup` | Superscript |
| `a` | Hyperlink |
| `ul` | Unordered list |
| `ol` | Ordered list |
| `li` | List item |
| `dl` | Description list |
| `dt` | Description term |
| `dd` | Description |
| `table` | Table |
| `tr` | Table row |
| `th` | Header cell |
| `td` | Data cell |
| `thead` | Table header |
| `tbody` | Table body |
| `tfoot` | Table footer |
| `caption` | Table caption |
| `img` | Image |
| `audio` | Audio |
| `video` | Video |
| `source` | Media source |
| `figure` | Self-contained figure |
| `figcaption` | Figure caption |
| `header` | Introductory/header content |
| `nav` | Navigation |
| `main` | Main content |
| `section` | Thematic section |
| `article` | Self-contained content |
| `aside` | Related/secondary content |
| `footer` | Footer |
| `div` | Generic block container |
| `span` | Generic inline container |
| `details` | Expandable information |
| `summary` | Summary for details |
| `time` | Date/time |
| `address` | Contact information |

---

# 48. Practical Exercise 1 — Create Your First HTML5 Page

Create a file called:

```text
index.html
```

Write HTML that displays:

1. Your name
2. Your course
3. Your university
4. A paragraph introducing yourself
5. Your hobbies as an unordered list
6. Your career goals as an ordered list

### Suggested Structure

```html
<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <title>My Profile</title>

</head>

<body>

    <h1>My Profile</h1>

    <h2>Name</h2>
    <p>John Doe</p>

    <h2>Course</h2>
    <p>BSc Computer Science</p>

    <h2>Hobbies</h2>

    <ul>
        <li>Reading</li>
        <li>Programming</li>
        <li>Football</li>
    </ul>

    <h2>Career Goals</h2>

    <ol>
        <li>Become a software developer</li>
        <li>Learn artificial intelligence</li>
        <li>Develop useful applications</li>
    </ol>

</body>

</html>
```

---

# 49. Practical Exercise 2 — Create a Department Page

Create a page containing:

- Department name
- Navigation menu
- About section
- Programmes section
- Staff section
- Contact information
- Footer

Students should use:

```html
<header>
<nav>
<main>
<section>
<article>
<aside>
<footer>
```

---

# 50. Practical Exercise 3 — Student Results Table

Create a table containing:

- Student name
- Registration number
- Course
- CAT marks
- Examination marks
- Total

Example:

```html
<table>

    <caption>Student Results</caption>

    <thead>

        <tr>
            <th>Name</th>
            <th>Registration No.</th>
            <th>CAT</th>
            <th>Exam</th>
            <th>Total</th>
        </tr>

    </thead>

    <tbody>

        <tr>
            <td>John Mwangi</td>
            <td>CS001</td>
            <td>25</td>
            <td>60</td>
            <td>85</td>
        </tr>

        <tr>
            <td>Mary Wanjiku</td>
            <td>CS002</td>
            <td>28</td>
            <td>65</td>
            <td>93</td>
        </tr>

    </tbody>

</table>
```

---

# 51. Practical Exercise 4 — Multimedia Page

Create a page containing an image, audio and video.

### Image

```html
<img src="campus.jpg"
     alt="University campus">
```

### Audio

```html
<audio controls>
    <source src="lecture.mp3"
            type="audio/mpeg">
</audio>
```

### Video

```html
<video controls width="600">

    <source src="lecture.mp4"
            type="video/mp4">

</video>
```

### Figure

```html
<figure>

    <img src="laboratory.jpg"
         alt="Computer laboratory">

    <figcaption>
        Computer Laboratory
    </figcaption>

</figure>
```

---

# 52. Practical Exercise 5 — Build a Complete HTML5 Website

Students should create a small website with **at least four pages**:

```text
website/
│
├── index.html
├── about.html
├── courses.html
├── contact.html
│
└── images/
    ├── campus.jpg
    └── laboratory.jpg
```

Every page should contain:

```html
<header>
<nav>
<main>
<footer>
```

The website should include:

- Headings
- Paragraphs
- Links
- Lists
- Images
- At least one table
- Audio
- Video
- Metadata
- Semantic HTML5
- Internal page links
- External links

---

# 53. Key Principles Students Should Remember

## Principle 1 — HTML Provides Structure

```html
<h1>Web Development</h1>
<p>Introduction to HTML.</p>
```

## Principle 2 — CSS Provides Presentation

HTML:

```html
<h1>Welcome</h1>
```

CSS controls properties such as:

- Colour
- Size
- Font
- Position
- Spacing

## Principle 3 — JavaScript Provides Behaviour

JavaScript can make a button perform an action, validate input, update page content, communicate with servers, and provide interactivity.

## Principle 4 — Use Semantic Elements Where Appropriate

Prefer:

```html
<header>
<nav>
<main>
<section>
<article>
<footer>
```

over using `<div>` for everything.

## Principle 5 — Provide Useful Alternative Text

```html
<img src="student.jpg"
     alt="Student programming on a laptop">
```

## Principle 6 — Keep HTML Readable

Good:

```html
<section>

    <h2>Our Courses</h2>

    <p>
        We offer several computing courses.
    </p>

</section>
```

Avoid writing an entire page as one long line.

---

# 54. Suggested Full-Class Practical

## Task: Build a University Computing Department Website

Students should create a complete HTML5 website containing:

1. A semantic header
2. Navigation menu
3. Home section
4. About section
5. Courses section
6. Staff section
7. Student results table
8. Department image
9. Audio announcement
10. Video lecture
11. Useful hyperlinks
12. Ordered and unordered lists
13. Contact information
14. Footer
15. Appropriate metadata
16. At least one `<article>`
17. At least one `<aside>`
18. `<figure>` and `<figcaption>`
19. Internal page navigation
20. HTML comments documenting the code

### Minimum Requirement

The final page should demonstrate **all the major HTML5 concepts covered in this lesson**, rather than simply displaying text.

---

# 55. Suggested Git Project Structure

A good student repository can be organized as follows:

```text
html5-lesson/
│
├── README.md
│
├── notes/
│   └── HTML5_Notes.md
│
├── examples/
│   ├── 01-document-structure.html
│   ├── 02-headings-paragraphs.html
│   ├── 03-text-formatting.html
│   ├── 04-links.html
│   ├── 05-lists.html
│   ├── 06-tables.html
│   ├── 07-images.html
│   ├── 08-audio.html
│   ├── 09-video.html
│   ├── 10-semantic-html.html
│   └── 11-complete-page.html
│
├── practical/
│   ├── exercise-01-profile.html
│   ├── exercise-02-department.html
│   ├── exercise-03-results.html
│   ├── exercise-04-multimedia.html
│   └── exercise-05-complete-website/
│       ├── index.html
│       ├── about.html
│       ├── courses.html
│       ├── contact.html
│       └── images/
│
└── assets/
    ├── images/
    ├── audio/
    └── video/
```

---

# 56. Basic Git Workflow

After creating the lesson repository:

```bash
git init
```

Add the files:

```bash
git add .
```

Commit the lesson:

```bash
git commit -m "Add HTML5 lesson notes and examples"
```

Connect the local repository to GitHub:

```bash
git remote add origin https://github.com/USERNAME/html5-lesson.git
```

Push the files:

```bash
git branch -M main
git push -u origin main
```

For later updates:

```bash
git add .
git commit -m "Update HTML5 lesson examples"
git push
```

---

# 57. Suggested `README.md`

The repository can have a simple README:

```markdown
# HTML5 Lesson

This repository contains comprehensive HTML5 lesson notes,
examples, demonstrations and practical exercises.

## Topics Covered

- HTML5 document structure
- Elements and attributes
- Headings and paragraphs
- Text formatting
- Hyperlinks
- Lists
- Tables
- Images
- Audio
- Video
- Metadata
- Semantic HTML5
- Page structure
- Practical HTML5 projects

## Repository Structure

- `notes/` — Full HTML5 lesson notes
- `examples/` — Individual HTML examples
- `practical/` — Practical exercises
- `assets/` — Images, audio and video resources

## Getting Started

Clone the repository:

```bash
git clone https://github.com/USERNAME/html5-lesson.git
```

Open any `.html` file in a web browser.

## Requirements

No server is required for the basic examples.

Recommended tools:

- Visual Studio Code
- Google Chrome
- Microsoft Edge
- Firefox
- Git
- GitHub
```

---

# 58. Lesson Summary

HTML5 provides the structural foundation of modern web pages.

The most important concepts covered in this lesson are:

```text
HTML5
│
├── Document Structure
│   ├── DOCTYPE
│   ├── html
│   ├── head
│   └── body
│
├── Content
│   ├── Headings
│   ├── Paragraphs
│   ├── Text Formatting
│   └── Comments
│
├── Navigation
│   └── Hyperlinks
│
├── Lists
│   ├── Unordered
│   ├── Ordered
│   └── Description
│
├── Tables
│   ├── Rows
│   ├── Columns
│   ├── Headers
│   ├── Sections
│   ├── Colspan
│   └── Rowspan
│
├── Multimedia
│   ├── Images
│   ├── Audio
│   └── Video
│
├── Metadata
│   ├── Charset
│   ├── Viewport
│   ├── Description
│   └── Author
│
└── Semantic HTML5
    ├── Header
    ├── Navigation
    ├── Main
    ├── Section
    ├── Article
    ├── Aside
    └── Footer
```

The key idea is:

> **HTML5 defines the structure and meaning of web content. CSS controls presentation, while JavaScript provides behaviour and interactivity.**
