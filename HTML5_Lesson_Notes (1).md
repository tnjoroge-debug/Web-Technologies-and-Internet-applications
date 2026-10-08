# HTML5 Full Lesson Notes

## Course Topic: HTML5

This lesson introduces HTML5 from the basics of an HTML document to semantic page structure. Every major topic contains:

- Explanation
- Multiple practical examples
- Complete code
- Expected output
- Short practice activities

The examples are designed to be copied directly into `.html` files and tested in a web browser.

---

# 1. Introduction to HTML5

## What is HTML?

**HTML (HyperText Markup Language)** is the standard markup language used to structure content on web pages.

HTML tells the browser what a piece of content is:

- A heading
- A paragraph
- A link
- An image
- A table
- An audio file
- A video
- A navigation area
- A section of a page

HTML is a **markup language**, not a programming language.

## What is HTML5?

HTML5 is the modern version of HTML. It introduced improved document structure, multimedia elements, semantic elements, and many features that make web development easier.

---

# 2. Basic HTML5 Document Structure

A normal HTML5 page begins with `<!DOCTYPE html>`.

## Example 1: Minimal HTML5 Page

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My First HTML5 Page</title>
</head>
<body>

    <h1>Welcome to HTML5</h1>
    <p>This is my first HTML5 web page.</p>

</body>
</html>
```

### Expected Output

The browser displays:

> **Welcome to HTML5**  
> This is my first HTML5 web page.

---

## Example 2: HTML5 Page with More Content

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Computing Department</title>
</head>
<body>

    <h1>Computing Department</h1>

    <p>Welcome to the Computing Department.</p>

    <h2>Our Programmes</h2>

    <p>We offer Computer Science and Information Technology programmes.</p>

</body>
</html>
```

### Expected Output

> **Computing Department**  
> Welcome to the Computing Department.
>
> **Our Programmes**  
> We offer Computer Science and Information Technology programmes.

---

## Example 3: Understanding the Main Parts

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>HTML Structure</title>
</head>

<body>
    <h1>HTML5 Lesson</h1>
    <p>HTML gives structure to web content.</p>
</body>

</html>
```

### Expected Output

> **HTML5 Lesson**  
> HTML gives structure to web content.

### Important Parts

| Part | Purpose |
|---|---|
| `<!DOCTYPE html>` | Declares HTML5 |
| `<html>` | Root element |
| `<head>` | Page information and metadata |
| `<title>` | Text shown in browser tab |
| `<body>` | Visible page content |

---

# 3. HTML Elements

An HTML element normally consists of an opening tag, content, and a closing tag.

```html
<p>This is a paragraph.</p>
```

For some elements, there is no closing tag.

Examples:

```html
<br>
<hr>
<img>
<meta>
```

## Example 1: Different Elements

```html
<h1>University Website</h1>
<p>Welcome to our website.</p>
<hr>
<p>Admissions are now open.</p>
```

### Expected Output

> **University Website**  
> Welcome to our website.
>
> A horizontal line
>
> Admissions are now open.

---

## Example 2: Nested Elements

```html
<p>
    Welcome to the
    <strong>Computing Department</strong>.
</p>
```

### Expected Output

> Welcome to the **Computing Department**.

---

## Example 3: Multiple Nested Elements

```html
<p>
    HTML is
    <strong>easy</strong>
    and
    <em>powerful</em>.
</p>
```

### Expected Output

> HTML is **easy** and *powerful*.

---

# 4. HTML Attributes

Attributes provide additional information about an element.

Basic syntax:

```html
<element attribute="value">Content</element>
```

## Example 1: Link Attribute

```html
<a href="https://www.google.com">Visit Google</a>
```

### Expected Output

A clickable link:

> Visit Google

Clicking the link opens Google.

---

## Example 2: Image Attributes

```html
<img src="images/logo.png" alt="University Logo" width="200">
```

### Expected Output

A university logo appears at approximately **200 pixels wide**.

If the image cannot be displayed, the alternative text is:

> University Logo

---

## Example 3: Multiple Attributes

```html
<p id="intro" class="highlight">Welcome to HTML5.</p>
```

### Expected Output

> Welcome to HTML5.

The `id` and `class` are not normally visible, but they can be used by CSS and JavaScript.

---

# 5. Headings

HTML provides six heading levels:

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

## Example 1: All Heading Levels

```html
<h1>Level 1</h1>
<h2>Level 2</h2>
<h3>Level 3</h3>
<h4>Level 4</h4>
<h5>Level 5</h5>
<h6>Level 6</h6>
```

### Expected Output

The browser displays six headings, from the largest/most important heading to the smallest:

> **Level 1**  
> **Level 2**  
> **Level 3**  
> **Level 4**  
> **Level 5**  
> **Level 6**

---

## Example 2: Headings for a Course Page

```html
<h1>HTML5 Course</h1>
<h2>Module 1: Introduction</h2>
<h3>HTML Document Structure</h3>
<h3>Elements and Attributes</h3>
<h2>Module 2: Multimedia</h2>
<h3>Audio</h3>
<h3>Video</h3>
```

### Expected Output

A structured page outline:

> **HTML5 Course**  
> **Module 1: Introduction**  
> &nbsp;&nbsp;**HTML Document Structure**  
> &nbsp;&nbsp;**Elements and Attributes**  
> **Module 2: Multimedia**  
> &nbsp;&nbsp;**Audio**  
> &nbsp;&nbsp;**Video**

### Good Practice

Use headings according to document structure. Do not choose a heading only because it looks large.

---

# 6. Paragraphs

The `<p>` element defines a paragraph.

## Example 1

```html
<p>HTML is used to structure web pages.</p>
<p>CSS is used to style web pages.</p>
<p>JavaScript is used to add behaviour and interactivity.</p>
```

### Expected Output

Three separate paragraphs:

> HTML is used to structure web pages.
>
> CSS is used to style web pages.
>
> JavaScript is used to add behaviour and interactivity.

---

## Example 2: Long Paragraph

```html
<p>
    The Computing Department trains students in programming,
    databases, artificial intelligence, networking, web development,
    software engineering, and other areas of computing.
</p>
```

### Expected Output

One paragraph containing the full sentence. The browser automatically wraps the text according to the available screen width.

---

# 7. Line Breaks and Horizontal Rules

## `<br>` Example

```html
<p>
    Dr. Thomas Njoroge<br>
    Computing Department<br>
    Karatina University
</p>
```

### Expected Output

> Dr. Thomas Njoroge  
> Computing Department  
> Karatina University

---

## `<hr>` Example

```html
<h2>Announcements</h2>
<p>Registration is open.</p>

<hr>

<p>Classes begin next week.</p>
```

### Expected Output

> **Announcements**  
> Registration is open.
>
> ─────────────────────
>
> Classes begin next week.

---

# 8. Text Formatting

HTML provides several elements for communicating meaning or applying common text treatments.

## Example 1: Bold and Italic Meaning

```html
<p>
    <strong>Important:</strong> Submit your assignment by Friday.
</p>

<p>
    Artificial intelligence is <em>transforming</em> many industries.
</p>
```

### Expected Output

> **Important:** Submit your assignment by Friday.
>
> Artificial intelligence is *transforming* many industries.

---

## Example 2: Bold and Italic Presentation

```html
<p>This is <b>bold text</b>.</p>
<p>This is <i>italic text</i>.</p>
```

### Expected Output

> This is **bold text**.
>
> This is *italic text*.

---

## Example 3: Highlighted Text

```html
<p>HTML5 is a <mark>modern web standard</mark>.</p>
```

### Expected Output

> HTML5 is a **highlighted** phrase.

The browser normally displays the marked text with a highlighted background.

---

## Example 4: Deleted and Inserted Text

```html
<p>
    Old price: <del>KSh 10,000</del>
    New price: <ins>KSh 8,000</ins>
</p>
```

### Expected Output

> Old price: ~~KSh 10,000~~ New price: KSh 8,000

---

## Example 5: Subscript

```html
<p>Water formula: H<sub>2</sub>O</p>
```

### Expected Output

> Water formula: H₂O

---

## Example 6: Superscript

```html
<p>Area of a square: A = a<sup>2</sup></p>
```

### Expected Output

> Area of a square: A = a²

---

## Example 7: Small Text

```html
<p>Main content</p>
<small>Copyright © 2026 Computing Department</small>
```

### Expected Output

> Main content
>
> Copyright © 2026 Computing Department

The copyright text appears smaller.

---

# 9. Hyperlinks

The `<a>` element creates hyperlinks.

## Example 1: External Link

```html
<a href="https://www.karu.ac.ke">
    Visit Karatina University
</a>
```

### Expected Output

A clickable link:

> Visit Karatina University

---

## Example 2: Open Link in a New Tab

```html
<a href="https://www.karu.ac.ke" target="_blank">
    Open Karatina University
</a>
```

### Expected Output

A clickable link that normally opens the website in a new browser tab.

---

## Example 3: Email Link

```html
<a href="mailto:info@example.com">
    Send Email
</a>
```

### Expected Output

> Send Email

Clicking it opens the user's configured email application.

---

## Example 4: Telephone Link

```html
<a href="tel:+254700000000">
    Call the Department
</a>
```

### Expected Output

> Call the Department

On supported devices, clicking starts a phone call.

---

## Example 5: Link to a Section on the Same Page

```html
<a href="#about">Go to About Section</a>

<h2 id="about">About Us</h2>
<p>We teach computing courses.</p>
```

### Expected Output

A clickable link:

> Go to About Section

Clicking it moves the browser to:

> **About Us**  
> We teach computing courses.

---

# 10. Lists

## 10.1 Unordered Lists

## Example 1

```html
<h2>Computing Courses</h2>

<ul>
    <li>Computer Science</li>
    <li>Information Technology</li>
    <li>Data Science</li>
</ul>
```

### Expected Output

> **Computing Courses**
>
> • Computer Science  
> • Information Technology  
> • Data Science

---

## Example 2: Nested Unordered List

```html
<ul>
    <li>Programming
        <ul>
            <li>Python</li>
            <li>Java</li>
            <li>JavaScript</li>
        </ul>
    </li>

    <li>Databases
        <ul>
            <li>MySQL</li>
            <li>PostgreSQL</li>
        </ul>
    </li>
</ul>
```

### Expected Output

> • Programming  
> &nbsp;&nbsp;◦ Python  
> &nbsp;&nbsp;◦ Java  
> &nbsp;&nbsp;◦ JavaScript  
> • Databases  
> &nbsp;&nbsp;◦ MySQL  
> &nbsp;&nbsp;◦ PostgreSQL

---

# 11. Ordered Lists

## Example 1: Basic Ordered List

```html
<ol>
    <li>Open the browser</li>
    <li>Open your editor</li>
    <li>Create an HTML file</li>
    <li>Write your code</li>
</ol>
```

### Expected Output

> 1. Open the browser  
> 2. Open your editor  
> 3. Create an HTML file  
> 4. Write your code

---

## Example 2: Starting from a Different Number

```html
<ol start="5">
    <li>Testing</li>
    <li>Debugging</li>
    <li>Deployment</li>
</ol>
```

### Expected Output

> 5. Testing  
> 6. Debugging  
> 7. Deployment

---

## Example 3: Reversed List

```html
<ol reversed>
    <li>Final report</li>
    <li>Testing</li>
    <li>Implementation</li>
</ol>
```

### Expected Output

> 3. Final report  
> 2. Testing  
> 1. Implementation

---

# 12. Description Lists

Description lists are useful for terms and their definitions.

## Example

```html
<dl>
    <dt>HTML</dt>
    <dd>Structures web page content.</dd>

    <dt>CSS</dt>
    <dd>Styles web page content.</dd>

    <dt>JavaScript</dt>
    <dd>Adds behaviour and interactivity.</dd>
</dl>
```

### Expected Output

> **HTML**  
> &nbsp;&nbsp;Structures web page content.
>
> **CSS**  
> &nbsp;&nbsp;Styles web page content.
>
> **JavaScript**  
> &nbsp;&nbsp;Adds behaviour and interactivity.

---

# 13. HTML Tables

Tables are used to present data in rows and columns.

Basic table elements:

- `<table>`
- `<tr>`
- `<th>`
- `<td>`

## Example 1: Basic Table

```html
<table border="1">
    <tr>
        <th>Name</th>
        <th>Course</th>
        <th>Year</th>
    </tr>

    <tr>
        <td>Mary</td>
        <td>Computer Science</td>
        <td>3</td>
    </tr>

    <tr>
        <td>Peter</td>
        <td>Information Technology</td>
        <td>2</td>
    </tr>
</table>
```

### Expected Output

| Name | Course | Year |
|---|---|---:|
| Mary | Computer Science | 3 |
| Peter | Information Technology | 2 |

> **Teaching note:** `border="1"` is useful for a simple classroom demonstration, but modern production sites normally style tables using CSS.

---

## Example 2: Table with `thead`, `tbody`, and `tfoot`

```html
<table border="1">

    <caption>Student Results</caption>

    <thead>
        <tr>
            <th>Student</th>
            <th>CAT</th>
            <th>Exam</th>
            <th>Total</th>
        </tr>
    </thead>

    <tbody>
        <tr>
            <td>Mary</td>
            <td>25</td>
            <td>60</td>
            <td>85</td>
        </tr>

        <tr>
            <td>John</td>
            <td>22</td>
            <td>55</td>
            <td>77</td>
        </tr>
    </tbody>

    <tfoot>
        <tr>
            <td colspan="3">Class Average</td>
            <td>81</td>
        </tr>
    </tfoot>

</table>
```

### Expected Output

| Student | CAT | Exam | Total |
|---|---:|---:|---:|
| Mary | 25 | 60 | 85 |
| John | 22 | 55 | 77 |
| **Class Average** |  |  | **81** |

---

## Example 3: `colspan`

```html
<table border="1">
    <tr>
        <th colspan="3">Computing Department</th>
    </tr>

    <tr>
        <td>CS</td>
        <td>IT</td>
        <td>AI</td>
    </tr>
</table>
```

### Expected Output

| **Computing Department** |  |  |
|---|---|---|
| CS | IT | AI |

The heading occupies three columns.

---

## Example 4: `rowspan`

```html
<table border="1">
    <tr>
        <th rowspan="2">Programme</th>
        <th>Year</th>
        <th>Students</th>
    </tr>

    <tr>
        <td>Year 1</td>
        <td>50</td>
    </tr>
</table>
```

### Expected Output

The word **Programme** spans two rows.

---

# 14. Images

The `<img>` element displays an image.

Important attributes:

- `src`
- `alt`
- `width`
- `height`

## Example 1: Basic Image

```html
<img src="images/campus.jpg" alt="University Campus">
```

### Expected Output

The image `campus.jpg` appears on the page.

---

## Example 2: Image with Width

```html
<img
    src="images/campus.jpg"
    alt="University Campus"
    width="500">
```

### Expected Output

The campus image appears at approximately **500 pixels wide**.

---

## Example 3: Image with Width and Height

```html
<img
    src="images/logo.png"
    alt="Department Logo"
    width="250"
    height="120">
```

### Expected Output

The logo appears at approximately **250 × 120 pixels**.

---

## Example 4: Figure and Caption

```html
<figure>
    <img src="images/lab.jpg" alt="Computing Laboratory" width="500">
    <figcaption>Computing Laboratory</figcaption>
</figure>
```

### Expected Output

> [Computing laboratory image]
>
> *Computing Laboratory*

---

# 15. Audio

HTML5 supports audio without requiring third-party browser plugins.

## Example 1: Basic Audio

```html
<audio controls>
    <source src="audio/lecture.mp3" type="audio/mpeg">
</audio>
```

### Expected Output

An audio player appears with controls such as:

> ▶ Play | Volume | Timeline

The user can play `lecture.mp3`.

---

## Example 2: Multiple Audio Formats

```html
<audio controls>
    <source src="audio/lecture.mp3" type="audio/mpeg">
    <source src="audio/lecture.ogg" type="audio/ogg">
    Your browser does not support the audio element.
</audio>
```

### Expected Output

The browser attempts to use a supported audio format.

---

## Example 3: Loop Audio

```html
<audio controls loop>
    <source src="audio/background.mp3" type="audio/mpeg">
</audio>
```

### Expected Output

The audio player appears and the audio repeats after reaching the end.

---

# 16. Video

HTML5 also supports video.

## Example 1: Basic Video

```html
<video controls width="640">
    <source src="video/lecture.mp4" type="video/mp4">
</video>
```

### Expected Output

A video player appears approximately 640 pixels wide.

The controls normally include:

> ▶ Play | Timeline | Volume | Full Screen

---

## Example 2: Video with Poster Image

```html
<video controls width="640" poster="images/preview.jpg">
    <source src="video/lesson.mp4" type="video/mp4">
</video>
```

### Expected Output

Before the video starts, the browser displays `preview.jpg` as the preview image.

---

## Example 3: Multiple Video Sources

```html
<video controls width="640">

    <source src="video/lesson.mp4" type="video/mp4">
    <source src="video/lesson.webm" type="video/webm">

    Your browser does not support HTML5 video.
</video>
```

### Expected Output

The browser selects a supported video source.

---

# 17. Metadata

Metadata provides information about the web page.

## Example 1: Character Encoding

```html
<meta charset="UTF-8">
```

### Expected Output

No visible output. It tells the browser how to interpret characters.

---

## Example 2: Viewport Metadata

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

### Expected Output

No visible output. It helps the page display correctly on mobile devices.

---

## Example 3: Page Description

```html
<meta
    name="description"
    content="HTML5 lesson notes for computing students.">
```

### Expected Output

No visible output on the page. The metadata describes the page to software such as search engines.

---

## Example 4: Author

```html
<meta name="author" content="Computing Department">
```

### Expected Output

No visible output.

---

## Note on `meta keywords`

```html
<meta name="keywords" content="HTML5, web development, computing">
```

This is useful for demonstrating metadata concepts, but modern major search engines generally do not use the `keywords` meta tag as a primary ranking signal.

---

# 18. Semantic HTML5

Semantic HTML uses elements whose names describe the meaning of the content.

Common semantic elements:

```text
<header>
<nav>
<main>
<section>
<article>
<aside>
<footer>
<figure>
<figcaption>
```

## Example 1: Basic Semantic Structure

```html
<header>
    <h1>Computing Department</h1>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Courses</a>
    <a href="#">Contact</a>
</nav>

<main>
    <section>
        <h2>About the Department</h2>
        <p>We offer computing programmes.</p>
    </section>
</main>

<footer>
    <p>© 2026 Computing Department</p>
</footer>
```

### Expected Output

A page containing:

> **Computing Department**
>
> Home | Courses | Contact
>
> **About the Department**
>
> We offer computing programmes.
>
> © 2026 Computing Department

---

# 19. `<header>`

A header normally contains introductory content, a logo, title, or navigation.

## Example

```html
<header>
    <h1>Student Portal</h1>
    <p>Welcome to the student information system.</p>
</header>
```

### Expected Output

> **Student Portal**  
> Welcome to the student information system.

---

# 20. `<nav>`

The `<nav>` element contains important navigation links.

## Example

```html
<nav>
    <a href="index.html">Home</a>
    <a href="courses.html">Courses</a>
    <a href="students.html">Students</a>
    <a href="contact.html">Contact</a>
</nav>
```

### Expected Output

> Home | Courses | Students | Contact

---

# 21. `<main>`

The `<main>` element contains the primary content of the page.

## Example

```html
<main>
    <h1>HTML5 Course</h1>
    <p>This page contains the main lesson content.</p>
</main>
```

### Expected Output

> **HTML5 Course**  
> This page contains the main lesson content.

---

# 22. `<section>`

A section groups related content.

## Example

```html
<section>
    <h2>Web Technologies</h2>
    <p>This section introduces HTML5.</p>
</section>

<section>
    <h2>Programming</h2>
    <p>This section introduces JavaScript.</p>
</section>
```

### Expected Output

> **Web Technologies**  
> This section introduces HTML5.
>
> **Programming**  
> This section introduces JavaScript.

---

# 23. `<article>`

An article represents a self-contained piece of content.

## Example

```html
<article>
    <h2>Introduction to Artificial Intelligence</h2>
    <p>Artificial intelligence enables machines to perform tasks that normally require human intelligence.</p>
</article>
```

### Expected Output

> **Introduction to Artificial Intelligence**
>
> Artificial intelligence enables machines to perform tasks that normally require human intelligence.

---

# 24. `<aside>`

An aside contains related or supplementary information.

## Example

```html
<main>
    <h1>HTML5</h1>
    <p>HTML5 is used to structure web pages.</p>

    <aside>
        <h2>Tip</h2>
        <p>Always include meaningful alt text for important images.</p>
    </aside>
</main>
```

### Expected Output

> **HTML5**  
> HTML5 is used to structure web pages.
>
> **Tip**  
> Always include meaningful alt text for important images.

---

# 25. `<footer>`

The footer normally contains copyright, contact details, or related links.

## Example

```html
<footer>
    <p>© 2026 Computing Department</p>
    <p>Email: computing@example.com</p>
</footer>
```

### Expected Output

> © 2026 Computing Department  
> Email: computing@example.com

---

# 26. `<div>` and `<span>`

These are generic containers.

## Example 1: `<div>`

```html
<div>
    <h2>Student Information</h2>
    <p>Name: Mary</p>
    <p>Course: Computer Science</p>
</div>
```

### Expected Output

> **Student Information**  
> Name: Mary  
> Course: Computer Science

---

## Example 2: `<span>`

```html
<p>
    The status is
    <span>Active</span>.
</p>
```

### Expected Output

> The status is Active.

`<span>` is an inline container and does not normally create a new line.

---

# 27. HTML Comments

Comments are ignored by the browser.

## Example

```html
<!-- This is a comment -->

<h1>HTML5 Lesson</h1>
<p>This text is visible.</p>
```

### Expected Output

> **HTML5 Lesson**  
> This text is visible.

The comment does not appear on the page.

---

# 28. HTML Entities

Entities are used to display reserved or special characters.

## Example 1

```html
<p>&lt;h1&gt; is a heading element.</p>
```

### Expected Output

> `<h1>` is a heading element.

---

## Example 2

```html
<p>Copyright &copy; 2026 Computing Department</p>
```

### Expected Output

> Copyright © 2026 Computing Department

---

## Example 3

```html
<p>Tom&nbsp;Njoroge</p>
```

### Expected Output

The browser displays the names with a non-breaking space between them.

---

# 29. `<details>` and `<summary>`

These elements create expandable content.

## Example

```html
<details>
    <summary>What is HTML5?</summary>
    <p>HTML5 is the modern version of HTML.</p>
</details>
```

### Expected Output

Initially:

> ▶ What is HTML5?

When clicked:

> ▼ What is HTML5?  
> HTML5 is the modern version of HTML.

---

# 30. `<time>`

The `<time>` element represents a date or time.

## Example

```html
<p>
    The practical lesson is scheduled for
    <time datetime="2026-10-10">10 October 2026</time>.
</p>
```

### Expected Output

> The practical lesson is scheduled for 10 October 2026.

---

# 31. `<address>`

The `<address>` element represents contact information.

## Example

```html
<address>
    Computing Department<br>
    Karatina University<br>
    Kenya
</address>
```

### Expected Output

> Computing Department  
> Karatina University  
> Kenya

---

# 32. Complete Semantic HTML5 Page

The following example combines many topics.

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">

    <meta
        name="viewport"
        content="width=device-width, initial-scale=1.0">

    <meta
        name="description"
        content="Computing Department website">

    <meta
        name="author"
        content="Computing Department">

    <title>Computing Department</title>
</head>

<body>

    <header>
        <h1>Computing Department</h1>
        <p>School of Computing and Informatics</p>
    </header>

    <nav>
        <a href="#home">Home</a>
        <a href="#programmes">Programmes</a>
        <a href="#news">News</a>
        <a href="#contact">Contact</a>
    </nav>

    <main>

        <section id="home">
            <h2>Welcome</h2>
            <p>
                Welcome to the Computing Department.
            </p>
        </section>

        <section id="programmes">
            <h2>Programmes</h2>

            <ul>
                <li>Computer Science</li>
                <li>Information Technology</li>
                <li>Other Computing Programmes</li>
            </ul>
        </section>

        <section id="news">

            <h2>Latest News</h2>

            <article>
                <h3>HTML5 Practical Lesson</h3>

                <p>
                    Students are learning HTML5 document structure,
                    multimedia, tables, lists, and semantic elements.
                </p>
            </article>

        </section>

        <aside>
            <h2>Important Notice</h2>
            <p>
                Students should practise each HTML example in a browser.
            </p>
        </aside>

    </main>

    <footer id="contact">

        <address>
            Computing Department<br>
            Karatina University<br>
            Kenya
        </address>

        <p>© 2026 Computing Department</p>

    </footer>

</body>
</html>
```

### Expected Output

The browser displays a complete webpage containing:

> **Computing Department**  
> School of Computing and Informatics
>
> Home | Programmes | News | Contact
>
> **Welcome**  
> Welcome to the Computing Department.
>
> **Programmes**
>
> • Computer Science  
> • Information Technology  
> • Other Computing Programmes
>
> **Latest News**
>
> **HTML5 Practical Lesson**  
> Students are learning HTML5 document structure, multimedia, tables, lists, and semantic elements.
>
> **Important Notice**  
> Students should practise each HTML example in a browser.
>
> Computing Department  
> Karatina University  
> Kenya
>
> © 2026 Computing Department

---

# 33. Full Student Portal Example

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Student Portal</title>
</head>

<body>

    <header>
        <h1>Student Portal</h1>
        <p>Computing Department</p>
    </header>

    <nav>
        <a href="#dashboard">Dashboard</a>
        <a href="#courses">Courses</a>
        <a href="#results">Results</a>
        <a href="#contact">Contact</a>
    </nav>

    <main>

        <section id="dashboard">
            <h2>Dashboard</h2>
            <p>Welcome, Mary.</p>
        </section>

        <section id="courses">

            <h2>Registered Courses</h2>

            <table border="1">

                <caption>2026 Semester Courses</caption>

                <thead>
                    <tr>
                        <th>Code</th>
                        <th>Course</th>
                        <th>Credits</th>
                    </tr>
                </thead>

                <tbody>
                    <tr>
                        <td>CS101</td>
                        <td>Web Technologies</td>
                        <td>3</td>
                    </tr>

                    <tr>
                        <td>CS102</td>
                        <td>Programming</td>
                        <td>3</td>
                    </tr>

                    <tr>
                        <td>CS103</td>
                        <td>Database Systems</td>
                        <td>3</td>
                    </tr>
                </tbody>

            </table>

        </section>

        <section id="results">

            <h2>Latest Result</h2>

            <p>
                Web Technologies:
                <strong>82%</strong>
            </p>

        </section>

    </main>

    <footer id="contact">
        <p>Email: student@example.com</p>
        <p>© 2026 Student Portal</p>
    </footer>

</body>
</html>
```

### Expected Output

> **Student Portal**  
> Computing Department
>
> Dashboard | Courses | Results | Contact
>
> **Dashboard**  
> Welcome, Mary.
>
> **Registered Courses**
>
> | Code | Course | Credits |
> |---|---|---:|
> | CS101 | Web Technologies | 3 |
> | CS102 | Programming | 3 |
> | CS103 | Database Systems | 3 |
>
> **Latest Result**  
> Web Technologies: **82%**
>
> Email: student@example.com  
> © 2026 Student Portal

---

# 34. Complete Example: Department Homepage

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Computing Department homepage">

    <title>Computing Department</title>
</head>

<body>

<header>
    <h1>Computing Department</h1>
    <p>School of Computing and Informatics</p>
</header>

<nav>
    <a href="#">Home</a>
    <a href="#">Programmes</a>
    <a href="#">Staff</a>
    <a href="#">Students</a>
    <a href="#">Contact</a>
</nav>

<main>

    <section>
        <h2>Welcome</h2>

        <figure>
            <img
                src="images/computing-lab.jpg"
                alt="Computing laboratory"
                width="500">

            <figcaption>
                Computing laboratory
            </figcaption>
        </figure>

        <p>
            Welcome to our Computing Department website.
        </p>
    </section>

    <section>

        <h2>Programmes Offered</h2>

        <ol>
            <li>Computer Science</li>
            <li>Information Technology</li>
            <li>Other Computing Programmes</li>
        </ol>

    </section>

    <section>

        <h2>Announcement</h2>

        <article>

            <h3>HTML5 Practical</h3>

            <p>
                Students should complete the HTML5 practical exercises.
            </p>

            <details>
                <summary>Read More</summary>
                <p>
                    Submit your practical work according to the instructions
                    provided by the lecturer.
                </p>
            </details>

        </article>

    </section>

    <aside>

        <h2>Quick Links</h2>

        <ul>
            <li><a href="#">Student Portal</a></li>
            <li><a href="#">Library</a></li>
            <li><a href="#">E-learning</a></li>
        </ul>

    </aside>

</main>

<footer>

    <address>
        Computing Department<br>
        Karatina University<br>
        Kenya
    </address>

    <p>
        © 2026 Computing Department
    </p>

</footer>

</body>
</html>
```

### Expected Output

A complete department homepage with:

- A header containing the department name
- Navigation links
- A laboratory image and caption
- A list of programmes
- An announcement article
- Expandable additional information
- Quick links
- Contact/address information
- Footer information

---

# 35. HTML Example: Student Registration Table

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Student Registration</title>
</head>

<body>

    <h1>Student Registration</h1>

    <table border="1">

        <thead>
            <tr>
                <th>Admission No.</th>
                <th>Student Name</th>
                <th>Programme</th>
                <th>Year</th>
            </tr>
        </thead>

        <tbody>

            <tr>
                <td>P101/0001/22</td>
                <td>Mary Wanjiku</td>
                <td>Computer Science</td>
                <td>3</td>
            </tr>

            <tr>
                <td>P101/0002/22</td>
                <td>John Kamau</td>
                <td>Information Technology</td>
                <td>3</td>
            </tr>

        </tbody>

    </table>

</body>
</html>
```

### Expected Output

| Admission No. | Student Name | Programme | Year |
|---|---|---|---:|
| P101/0001/22 | Mary Wanjiku | Computer Science | 3 |
| P101/0002/22 | John Kamau | Information Technology | 3 |

---

# 36. HTML Example: Multimedia Page

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <title>Multimedia Lesson</title>
</head>

<body>

    <h1>HTML5 Multimedia</h1>

    <h2>Audio</h2>

    <audio controls>
        <source src="audio/lecture.mp3" type="audio/mpeg">
        Your browser does not support audio.
    </audio>

    <h2>Video</h2>

    <video controls width="640">
        <source src="video/lecture.mp4" type="video/mp4">
        Your browser does not support video.
    </video>

</body>
</html>
```

### Expected Output

> **HTML5 Multimedia**
>
> **Audio**
>
> [Audio player]
>
> **Video**
>
> [Video player]

The actual audio/video content depends on the files stored in the project folders.

---

# 37. HTML File and Folder Organization

For local practice, use:

```text
html5-lesson/
│
├── index.html
│
├── notes/
│   └── HTML5_Lesson_Notes.md
│
├── examples/
│   ├── 01-document-structure.html
│   ├── 02-elements.html
│   ├── 03-attributes.html
│   ├── 04-headings.html
│   ├── 05-paragraphs.html
│   ├── 06-formatting.html
│   ├── 07-links.html
│   ├── 08-lists.html
│   ├── 09-tables.html
│   ├── 10-images.html
│   ├── 11-audio.html
│   ├── 12-video.html
│   ├── 13-metadata.html
│   └── 14-semantic-html.html
│
├── practical/
│   └── exercises.md
│
└── assets/
    ├── images/
    ├── audio/
    └── video/
```

---

# 38. Practical Exercise 1: Create a Personal Profile

Create a page containing:

1. Your name as `<h1>`.
2. Your programme as `<h2>`.
3. A paragraph introducing yourself.
4. An unordered list of your interests.
5. A link to a website you frequently use.
6. Your photograph using `<img>`.
7. A footer containing your name.

### Expected Result

The browser should display a personal profile page containing a heading, introduction, list, image, link, and footer.

---

# 39. Practical Exercise 2: Create a Course Page

Create a page for a computing course.

Include:

- Course title
- Course description
- Learning outcomes
- Ordered list of lessons
- Lecturer information
- Contact email
- Course image

### Expected Result

A structured course page containing headings, paragraphs, lists, image and contact information.

---

# 40. Practical Exercise 3: Create a Student Results Table

Create a table containing:

- Admission number
- Student name
- CAT mark
- Examination mark
- Total mark

Use:

- `<caption>`
- `<thead>`
- `<tbody>`
- `<tfoot>`

### Expected Result

A properly structured results table showing all student marks and a summary row.

---

# 41. Practical Exercise 4: Create a Multimedia Page

Create a page containing:

- One image
- One audio file
- One video file
- Captions for images
- Descriptive alternative text

### Expected Result

The browser should show the image, audio controls and video controls.

---

# 42. Practical Exercise 5: Create a Semantic Website

Create a full page using:

```text
<header>
<nav>
<main>
<section>
<article>
<aside>
<footer>
```

### Expected Result

A logically structured webpage with clearly separated major regions.

---

# 43. Practical Exercise 6: University Department Website

Create a complete department website containing:

## Header

- University name
- Department name

## Navigation

- Home
- About
- Programmes
- Staff
- Students
- Contact

## Main Content

- Welcome message
- Department description
- Programmes offered

## Table

Display staff information.

## Multimedia

Add a department image and an introductory video.

## Aside

Add important notices.

## Footer

Add address and copyright information.

### Expected Result

A complete HTML5 university department webpage using semantic HTML5.

---

# 44. Mini Project: Student Information Website

Create a multi-page HTML5 project.

Required pages:

```text
index.html
about.html
courses.html
students.html
contact.html
```

The pages should contain working navigation links.

### Expected Structure

```text
student-information/
│
├── index.html
├── about.html
├── courses.html
├── students.html
├── contact.html
└── assets/
    ├── images/
    ├── audio/
    └── video/
```

### Expected Result

A small but complete multi-page website where students can navigate between pages.

---

# 45. Quick HTML5 Reference

| Element | Purpose |
|---|---|
| `<!DOCTYPE html>` | Declares HTML5 |
| `<html>` | Root of HTML document |
| `<head>` | Metadata and document information |
| `<title>` | Browser tab title |
| `<body>` | Visible page content |
| `<h1>`–`<h6>` | Headings |
| `<p>` | Paragraph |
| `<br>` | Line break |
| `<hr>` | Horizontal rule |
| `<strong>` | Strong importance |
| `<em>` | Emphasis |
| `<b>` | Bold presentation |
| `<i>` | Italic presentation |
| `<mark>` | Highlighted text |
| `<del>` | Deleted text |
| `<ins>` | Inserted text |
| `<sub>` | Subscript |
| `<sup>` | Superscript |
| `<a>` | Hyperlink |
| `<ul>` | Unordered list |
| `<ol>` | Ordered list |
| `<li>` | List item |
| `<dl>` | Description list |
| `<dt>` | Description term |
| `<dd>` | Description |
| `<table>` | Table |
| `<tr>` | Table row |
| `<th>` | Table header cell |
| `<td>` | Table data cell |
| `<caption>` | Table caption |
| `<img>` | Image |
| `<audio>` | Audio player |
| `<video>` | Video player |
| `<figure>` | Figure/media container |
| `<figcaption>` | Figure caption |
| `<header>` | Introductory/header content |
| `<nav>` | Navigation |
| `<main>` | Main content |
| `<section>` | Thematic section |
| `<article>` | Self-contained content |
| `<aside>` | Supplementary content |
| `<footer>` | Footer information |
| `<div>` | Generic block container |
| `<span>` | Generic inline container |
| `<details>` | Expandable content |
| `<summary>` | Summary for details |
| `<time>` | Date/time information |
| `<address>` | Contact information |

---

# 46. Key Principles for Students

1. Always start a normal HTML5 document with `<!DOCTYPE html>`.
2. Use meaningful headings to organize content.
3. Use semantic HTML where possible.
4. Always provide meaningful `alt` text for informative images.
5. Use tables for tabular data, not page layout.
6. Use relative paths carefully when working with images, audio and video.
7. Indent nested HTML so that the structure is easy to read.
8. Test every HTML file in a browser.
9. Keep the code simple before adding CSS and JavaScript.
10. Practise by changing the examples rather than only copying them.

---

# 47. Suggested Git Repository

```text
html5-lesson/
│
├── README.md
├── notes/
│   └── HTML5_Lesson_Notes.md
├── examples/
├── practical/
└── assets/
    ├── images/
    ├── audio/
    └── video/
```

The Markdown lesson can be viewed directly on GitHub, while individual `.html` examples can be downloaded and opened in a browser.

---

# 48. Basic Git Commands

From the project folder:

```bash
git init
git add .
git commit -m "Add HTML5 lesson notes and examples"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/html5-lesson.git
git push -u origin main
```

After making changes later:

```bash
git add .
git commit -m "Update HTML5 lesson examples"
git push
```

---

# 49. Final Lesson Activity

Students should create a webpage titled:

**Computing Department – HTML5 Practical**

The page must demonstrate at least:

- 3 heading levels
- 3 paragraphs
- 5 formatted text examples
- 3 hyperlinks
- 1 unordered list
- 1 ordered list
- 1 description list
- 1 table with at least 5 records
- 1 image
- 1 audio player
- 1 video player
- metadata
- semantic elements
- a footer

### Expected Result

Students should produce a complete HTML5 page that demonstrates the major concepts covered in this lesson.

---

# End of HTML5 Lesson Notes
