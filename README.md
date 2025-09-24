# HTML-5-Revision

### HTML 5 NOTES

# HTML Basics

## What is HTML?
HTML ka full form hai **Hyper Text Markup Language**.  
Ye ek language hai jiska use hum web pages banane ke liye karte hain.  
HTML basically batata hai ki ek web page ka **structure** kaisa hoga.  

Isme alag-alag **elements** hote hain jo browser ko guide karte hain ki content kaise show karna hai.  
Jaise:  
- `<h1>` → Heading dikhata hai  
- `<p>` → Paragraph banata hai  
- `<a>` → Link create karta hai  

---

## Ek Simple HTML Document
Agar ek simple HTML page banana hai to wo kuch aisa dikhega:

```html
<!DOCTYPE html>
<html>
<head>
  <title>Page Title</title>
</head>
<body>

  <h1>My First Heading</h1>
  <p>My first paragraph.</p>

</body>
</html>
```

## Example Samajhte Hain

```Example
<!DOCTYPE html> → Ye browser ko batata hai ki ye ek HTML5 document hai.

<html> → Ye sabse outer element hota hai, jise root element bhi kehte hain.

<head> → Iske andar page ki extra info hoti hai (jaise title, metadata, links).

<title> → Page ka naam set karta hai (jo browser tab me dikhai deta hai).

<body> → Ye main content rakhta hai jo user ko dikhai deta hai (heading, text, images, links etc.).

<h1> → Ye ek badi heading banata hai.

<p> → Ye ek paragraph banata hai.
```

---

## What is an HTML Element?

Ek HTML element teen parts se milkar banta hai:

- Start tag

- Content

- End tag

```html
<tagname> Content goes here... </tagname>
Example in real:
<h1>My First Heading</h1>
<p>My first paragraph.</p>
```

⚡ Note: Kuch elements ke andar content nahi hota, jaise "br" tag.
Unhe empty elements kehte hain, aur inka end tag nahi hota.

---

# HTML Tags

## What is a Tag?
- **Tag** ek markup entity hoti hai jiske through hum apne content ko structured define kar sakte hain.  
- Ye content ko **meaning** provide karta hai aur **formatting** me help karta hai.  
- Example: `<h1>`, `<h2>`, `<p>`, `<body>`, `<head>` etc.  

---

## Types of Tags in HTML

| Semantic Tags           | Structure Tags            | Formatting Tags        |
|-------------------------|---------------------------|------------------------|
| `<h1>` - `<h6>`         | `<html>`                  | `<b>` (bold)           |
| `<p>`                   | `<head>`, `<body>`        | `<i>` (italic)         |
| `<a>`                   | `<header>`                | `<u>` (underline)      |
| `<ul>`, `<ol>`          | `<main>`                  | `<s>` (strikethrough)  |
| `<table>`               | `<footer>`                | `<strong>`             |
| `<tr>`, `<td>`          | `<aside>`                 | `<em>` (emphasis)      |
| `<img>`                 | `<article>`               | `<sup>`, `<sub>`       |
| `<form>`                | `<section>`               | `<pre>`                |
| `<input>` etc.          | `<nav>` etc.              | `<code>` etc.          |

---

👉 Simple shabdon me:
- **Semantic Tags**: Jo content ko proper meaning dete hain (jaise heading, paragraph, links).  
- **Structure Tags**: Jo page ki basic structure define karte hain (html, head, body, header, footer).  
- **Formatting Tags**: Jo text ki styling/formatting karne ke liye use hote hain (bold, italic, underline). 

---

# HTML Attribute & Element

## What is an Attribute?
- **Attribute** ek special property hoti hai jo kisi **tag** me add ki jati hai.  
- Iska kaam hota hai tag ko **specific behavior ya functionality** dena.  
- Example: `<a href="https://example.com">Link</a>` me `href` ek attribute hai jo link ka URL define karta hai.  

---

## What is an Element?
- **Element** ek complete HTML block hota hai.  
- Ye **opening tag se lekar closing tag tak** hota hai, including content.  
- Example:
```html
<p>This is a paragraph.</p>
```

---

## 1. Semantic Tags
Ye tags content ko meaning provide karte hain, jaise heading, paragraph, link, list etc.

| Tag           | Description                                              |
|---------------|----------------------------------------------------------|
| `<h1>`-`<h6>` | Headings, `<h1>` sabse bada heading, `<h6>` sabse chhota |
| `<p>`         | Paragraph text                                           |
| `<a>`         | Link (anchor)                                            |
| `<ul>`        | Unordered list (bullet points)                           |
| `<ol>`        | Ordered list (numbered)                                  |
| `<table>`     | Table banata hai                                         |
| `<tr>`        | Table row                                                |
| `<td>`        | Table data/cell                                          |
| `<img>`       | Image insert karta hai                                   |
| `<form>`      | Form create karta hai                                    |
| `<input>`     | Form me input field                                      |

---

## 2. Structure Tags
Ye tags page ke structure ko define karte hain.  

| Tag        | Description                           |
|------------|---------------------------------------|
| `<html>`   | Root element of page                  |
| `<head>`   | Page ke meta information ke liye      |
| `<body>`   | Visible content ka container          |
| `<header>` | Page ka header section                |
| `<main>`   | Main content area                     |
| `<footer>` | Page ka footer section                |
| `<aside>`  | Side content ya sidebar               |
| `<article>`| Independent article content           |
| `<section>`| Page ka section                       |
| `<nav>`    | Navigation links ka container         |

---

## 3. Formatting Tags
Ye tags text ya content ko style karne ke liye use hote hain.  

| Tag        | Description                           |
|------------|---------------------------------------|
| `<b>`      | Bold text                             |
| `<i>`      | Italic text                           |
| `<u>`      | Underline text                        |
| `<s>`      | Strikethrough text                    |
| `<strong>` | Strong importance (usually bold)      |
| `<em>`     | Emphasis (usually italic)             |
| `<sup>`    | Superscript (text upar)               |
| `<sub>`    | Subscript (text neeche)               |
| `<pre>`    | Preformatted text (maintains spacing) |
| `<code>`   | Code text                             |

---

# HTML Block and Inline Elements

## Overview
- Har HTML element ka ek default **display value** hota hai, jo define karta hai ki element kaise dikhai dega.  
- Do most common display types hain: **Block** aur **Inline**.

---

## Block-level Elements
- Block-level element hamesha **nayi line** se start hota hai.  
- Browser automatically **margin** add karta hai element ke upar aur neeche.  
- Block element **poori available width** le leta hai.  

### Common Block Elements
- `<p>` → Paragraph define karta hai  
- `<div>` → Section ya division create karta hai  

### Example
<p>Hello World</p>
<div>Hello World</div>

### List of Block-level Elements

```
<address>, <article>, <aside>, <blockquote>, <canvas>, <dd>, <div>, <dl>, <dt>, <fieldset>, 
<figcaption>, <figure>, <footer>, <form>, <h1>-<h6>, <header>, <hr>, <li>, <main>, <nav>, 
<noscript>, <ol>, <p>, <pre>
```

---

# Inline Elements

## Overview
- Inline element **nayi line se start nahi hota**.  
- Ye sirf **jitni width content ko chahiye**, utni hi width leta hai.  

### Example

```html
<p>This is a <span>Hello World</span> inside a paragraph.</p>
```

### Here are the inline elements in HTML:
```
<a>,<abbr>,<acronym>,<b>,<bdo>,<big>,<br>,<button>,<cite>,<code>,<dfn>,<em>,<i>,<img>,<input>,<kbd>,<label>,<map>,<object>,<output>,<q>,<samp>,<script>,<select>,<small>,<span>,<strong>,<sub>,<sup>,<textarea>,<time>,<tt>,<var>
```
Note: An inline element cannot contain a block-level element!

---

# The <div> Element

## Overview
- `<div>` element ko aksar ek **container** ki tarah use kiya jata hai.  
- Ye dusre HTML elements ko ek group me rakhne ka kaam karta hai.  
- Iske liye koi special attribute required nahi hota, lekin commonly **style**, **class** aur **id** use kiye jate hain.  

---

## Use with CSS
- Jab `<div>` ko CSS ke sath use karte hain to ye ek **block of content** ko easily style karne ke liye helpful hota hai.  

### Example
```html
<div style="background-color:black; color:white; padding:20px;">
  <h2>London</h2>
  <p>
    London is the capital city of England. It is the most populous city in the United Kingdom,
    with a metropolitan area of over 13 million inhabitants.
  </p>
</div>
```

---

# The <span> Element

## Overview
- `<span>` ek **inline container** hota hai jo text ke kisi specific part ko mark up karne ke liye use hota hai.  
- Iske liye koi required attribute nahi hota, lekin commonly **style**, **class** aur **id** use hote hain.  

---

## Use with CSS
- `<span>` ko CSS ke sath use karke hum text ke chhote-chhote parts ko **style** kar sakte hain (jaise color, font-weight, size).  

### Example
```html
<p>
  My mother has <span style="color:blue; font-weight:bold;">blue</span> eyes 
  and my father has <span style="color:darkolivegreen; font-weight:bold;">dark green</span> eyes.
</p>
```

---

# Difference Between <div> and <span> | Block vs Inline Elements

## 1. <div> vs <span>
| Feature              | `<div>`                                     | `<span>`                                      |
|----------------------|---------------------------------------------|-----------------------------------------------|
| Type                 | Block-level element                         | Inline element                                |
| Usage                | Large content blocks ko group karne ke liye | Text ke chhote part ko mark karne ke liye     |
| Default Behavior     | Hamesha nayi line se start hota hai         | Same line me rehta hai                        |
| Styling              | Page sections ko style karne ke liye        | Text ke specific words ko style karne ke liye |
| Example              | `<div><h1>Title</h1><p>Content</p></div>`   | `<p>Hello <span>World</span></p>`             |

---

## 2. Block Elements vs Inline Elements
| Feature              | Block Elements                            | Inline Elements                             |
|----------------------|-------------------------------------------|---------------------------------------------|
| Line Break           | Nayi line se start hote hain              | Nayi line se start nahi hote                |
| Width                | Poora available width le lete hain        | Sirf content ki width lete hain             |
| Example Tags         | `<div>`, `<p>`, `<section>`, `<article>`  | `<span>`, `<a>`, `<strong>`, `<img>`        |
| Usage                | Layout aur structure banane ke liye       | Text ya content ko style/mark karne ke liye |

---
👉 Simple shabdon me:  
- **`<div>` = Block element** → bade sections ke liye  
- **`<span>` = Inline element** → text ke chhote part ke liye 

---

# HTML Lists

## Overview
HTML me lists ka use related items ko ek group me dikhane ke liye hota hai.  
3 main types ke lists hote hain: **Unordered List**, **Ordered List**, aur **Description List**.

---

## 1. Unordered HTML List
- `<ul>` tag se start hota hai.  
- Har list item `<li>` tag me hota hai.  
- By default items **bullets (●)** ke sath dikhte hain.  

### Example
```html
<ul>
  <li>Apple</li>
  <li>Banana</li>
  <li>Cherry</li>
</ul>
```

### Unordered HTML List - Choose List Item Marker

# CSS `list-style-type` Property

## Overview
- CSS me `list-style-type` property ka use **list item markers** (bullets ya numbering) ka style set karne ke liye hota hai.  
- Ye mainly `<ul>` (unordered list) aur `<ol>` (ordered list) ke liye use hoti hai.  

---

## Common Values

| Value   | Description                                | Example Output              |
|---------|--------------------------------------------|-----------------------------|
| `disc`  | Default marker, solid bullet (●)           | ● Item                      |
| `circle`| Empty circle marker (○)                    | ○ Item                      |
| `square`| Square marker (■)                          | ■ Item                      |
| `none`  | No marker show hoga                        | Item                        |

## Example
```html
<ul style="list-style-type:disc;">
  <li>Disc type (default)</li>
</ul>

<ul style="list-style-type:circle;">
  <li>Circle type</li>
</ul>

<ul style="list-style-type:square;">
  <li>Square type</li>
</ul>

<ul style="list-style-type:none;">
  <li>No marker</li>
</ul>
```

---

### 2. Ordered HTML List
- <ol> tag se start hota hai.
- Har list item <li> tag me hota hai.
- By default items numbers (1, 2, 3) ke sath dikhte hain.

### Example
```html
<ol>
  <li>First Step</li>
  <li>Second Step</li>
  <li>Third Step</li>
</ol>
```

# Ordered HTML List - The `type` and `start` Attributes

## 1. The `type` Attribute
- `<ol>` tag me `type` attribute use karke hum **list item marker ka style** change kar sakte hain.  

### Possible Values
| Type       | Description                                  | Example Output |
|------------|----------------------------------------------|----------------|
| `type="1"` | Numbering with numbers (default)             | 1, 2, 3, ...   |
| `type="A"` | Uppercase letters                            | A, B, C, ...   |
| `type="a"` | Lowercase letters                            | a, b, c, ...   |
| `type="I"` | Uppercase Roman numerals                     | I, II, III, ...|
| `type="i"` | Lowercase Roman numerals                     | i, ii, iii, ...|

### Example
```html
<ol type="A">
  <li>First item</li>
  <li>Second item</li>
</ol>
```

### Control List Counting (The start Attribute)
- By default, ordered list 1 se start hoti hai.
- Agar aap chahte ho ki numbering kisi aur number se start ho, to start attribute use karte ho.

### Example
```html
<ol type="1" start="5">
  <li>Fifth item</li>
  <li>Sixth item</li>
</ol>
```

---

### 3. HTML Description List
- Description list me term aur uski description hoti hai.
- <dl> → Description List container
- <dt> → Term (ya Name)
- <dd> → Term ki Description

### Example
```html
<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language - structure define karta hai</dd>

  <dt>CSS</dt>
  <dd>Cascading Style Sheets - styling ke liye use hota hai</dd>
</dl>
```

### Summary
```html
- Unordered List (<ul>) → Bullets wali list
- Ordered List (<ol>) → Numbered wali list
- Description List (<dl>) → Term aur description wali list
```

---

# HTML Tables

## Overview
- HTML tables ka use data ko **rows aur columns** me arrange karne ke liye hota hai.  
- Table ke andar **cells** hote hain jo rows (`<tr>`) aur columns (`<td>` / `<th>`) se bante hain.  

---

## Basic Table Structure
- `<table>` → Table create karta hai  
- `<tr>` → Table row define karta hai  
- `<th>` → Table header cell (bold & centered by default)  
- `<td>` → Table data cell  

---

# HTML Table Tags

| **Tag**       | **Description**                                                                               |
|---------------|-----------------------------------------------------------------------------------------------|
| `<table>`     | Table ko define karta hai.                                                                    |
| `<th>`        | Table header cell define karta hai (bold & centered hota hai by default).                     |
| `<tr>`        | Table row ko define karta hai.                                                                |
| `<td>`        | Table data cell ko define karta hai.                                                          |
| `<caption>`   | Table ke upar ek **title/caption** add karta hai.                                             |
| `<colgroup>`  | Ek ya zyada columns ko group karta hai **formatting ke liye**.                                |
| `<col>`       | `<colgroup>` ke andar use hota hai, har column ke liye specific **properties** set karta hai. |
| `<thead>`     | Table ke **header content** ko group karta hai.                                               |
| `<tbody>`     | Table ke **body content** ko group karta hai.                                                 |
| `<tfoot>`     | Table ke **footer content** ko group karta hai (jaise summary, totals, etc.).                 |

---

## Example with Advanced Tags
```html
<table border="1">
  <caption>Employee Details</caption>
  <colgroup>
    <col span="1" style="background-color:lightgray;">
    <col span="2" style="background-color:lightyellow;">
  </colgroup>
  <thead>
    <tr>
      <th>Name</th>
      <th>Position</th>
      <th>Country</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>John Doe</td>
      <td>Developer</td>
      <td>USA</td>
    </tr>
    <tr>
      <td>Maria Anders</td>
      <td>Manager</td>
      <td>Germany</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td colspan="3">Total Employees: 2</td>
    </tr>
  </tfoot>
</table>
```

---

# HTML Table Borders

## 1. Collapsed Table Borders
- By default, table me double borders aa jati hain.  
- Isko hatane ke liye **CSS `border-collapse: collapse;`** use karte hain.

### Example
```html
<style>
  table, th, td {
    border: 1px solid black;
    border-collapse: collapse;
  }
</style>
```

---

## 2. Dotted Table Borders

- CSS me border-style se border ka look change kar sakte ho.

- Available styles: dotted, dashed, solid, double, groove, ridge, inset, outset, none, hidden

### Example 
```html
th, td {
  border-style: dotted;
}
```

## 3. Border Color

- CSS property border-color se border ka color set karte hain.

### Example
```html
th, td {
    border: 2px solid;
    border-color: #96D4D4; 
  }
```

---

# HTML Table: Header for Multiple Columns

Kabhi kabhi hume ek hi **header** ko multiple columns ke upar lagana hota hai.  
Iske liye **`colspan` attribute** use karte hain.  

---

## Example

```html
<table border="1">
  <tr>
    <th colspan="2">Name</th>
    <th>Age</th>
  </tr>
```

---

## HTML Table: Caption

Agar hume poore table ke upar ek **heading ya title** dena ho, to uske liye **`<caption>` tag** use hota hai.  
Ye table ke liye ek short description jaisa kaam karta hai.  

Note: The `<caption>` tag should be inserted immediately after the `<table>` tag.

---

### Example

```html
<table style="width:100%" border="1">
  <caption>Monthly savings</caption>
  <tr>
    <th>Month</th>
    <th>Savings</th>
  </tr>
```

---

# HTML Table: Cell Spacing

👉 **Cell Spacing** ka matlab hai table ke har cell ke **beech ka space**.  
By default ye space **2 pixels** hota hai.  

Agar hume is spacing ko badalna ya kam karna ho, to hum **CSS property `border-spacing`** use karte hain.  

---

## Example

```html
<table style="border:1px solid black; border-spacing:30px;">
  <tr>
    <th>First Name</th>
    <th>Last Name</th>
  </tr>
```

---

# HTML Table: Colspan & Rowspan

HTML tables me kabhi-kabhi ek cell ko **multiple rows ya columns** me extend karna padta hai.  
Iske liye hum **`colspan`** aur **`rowspan`** attributes ka use karte hain.  

---

## 1. Colspan  
👉 Agar hume ek **cell ko multiple columns** me spread karna hai to **`colspan`** use hota hai.  

### Example
```html
<table border="1">
  <tr>
    <th colspan="2">Name</th>
    <th>Age</th>
  </tr>
```

## 2. Rowspan
👉 Agar hume ek cell ko multiple rows me spread karna hai to rowspan use hota hai.

### Example
```html
<table>
  <tr>
    <th>Name</th>
    <td>Jill</td>
  </tr>
```

- Note: The value of the colspan attribute represents the number of columns to span.
- Note: The value of the rowspan attribute represents the number of rows to span.

---

# HTML Table Styling with CSS

Tables ko visually better dikhane ke liye hum CSS use karte hain.  
Ek common styling technique hai **Zebra Stripes Effect** jisme alternate rows ko alag background color dete hain.

---

## Zebra Stripes Effect
👉 Zebra stripes ka matlab hai ki **har dusri row** ka background color change karna.  
Isse table read karna easy ho jata hai.

### Example
```html
tr:nth-child(even) {
  background-color: #D6EEEE;  /* Even rows ka background */
}
```

# HTML Table - Vertical Zebra Stripes

Jaise hum horizontal zebra stripes banate hain rows ke liye, waise hi hum **vertical zebra stripes** bana sakte hain columns ke liye.  
Isme alternate columns ka background color change hota hai.

### Example
```html
/* Vertical Zebra Stripes */
td:nth-child(even), th:nth-child(even) {
  background-color: #D6EEEE;
}
```

---

# HTML Table - Combine Vertical and Horizontal Zebra Stripes

Hum **horizontal (row-wise)** aur **vertical (column-wise)** zebra stripes ko combine kar sakte hain.  
Isse table me **rows aur columns dono par stripes** dikhai dengi.  

Agar hum transparent color use karein (jaise `rgba()`), to overlapping effect bhi milega.

---

### Example
```html
/* Horizontal Zebra Stripes */
tr:nth-child(even) {
  background-color: rgba(150, 212, 212, 0.4);
}

/* Vertical Zebra Stripes */
th:nth-child(even), td:nth-child(even) {
  background-color: rgba(150, 212, 212, 0.4);
}
```

---

# HTML Table - `<colgroup>` Element

👉 **`<colgroup>` element** ka use hum table ke specific columns ko style karne ke liye karte hain.  
Ye ek container hota hai jo columns ke styling rules rakhta hai, aur iske andar hum **`<col>` elements** use karte hain.

---

## Important Points
- `<colgroup>` hamesha **`<table>` ke andar** likha jata hai.  
- Agar table me **caption** ho, to ye **caption ke baad** aata hai.  
- Ye hamesha `<thead>`, `<tr>`, `<td>` se pehle likhna hota hai.  
- `<col>` tag ke **span attribute** ka use ek saath multiple columns ko style dene ke liye hota hai.  
- Sirf limited CSS properties kaam karti hain:  
  - `width`  
  - `visibility`  
  - `background` properties  
  - `border` properties  

### Example
```html
<table>
  <colgroup>
    <col span="2" style="background-color: #D6EEEE;">
    <col style="background-color: #f2f2f2;">
  </colgroup>
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  ```

---

# HTML Forms

👉 **HTML Form** ka use user se input lene ke liye hota hai.  
Form ke through liya gaya input server par bheja ja sakta hai taaki uska processing ho sake (jaise login, signup, search, etc.).

# HTML `<form>` Attributes

Form ke andar hum different **attributes** use karte hain jo decide karte hain ki form ka data kaise, kahan aur kis format me send hoga.  

---

## Common `<form>` Attributes

| Attribute         | Simple Explanation                                                                                                                  |
|------------------ |-------------------------------------------------------------------------------------------------------------------------------------|
| `action`          | Form submit hone par data kahan bhejna hai (server file ka URL).                                                                    |
| `method`          | Data bhejne ka method (GET ya POST). <br>• `GET` → URL me data dikhega <br>• `POST` → Data hidden rahega.                           |
| `enctype`         | Data ko encode karne ka tarika (sirf `POST` ke sath use hota hai). Example: `multipart/form-data` file uploads ke liye.             |
| `target`          | Response kahan dikhana hai: <br>• `_self` (default) → same page <br>• `_blank` → new tab <br>• `_parent`, `_top` bhi use hote hain. | 
| `autocomplete`    | Suggestion ya auto-fill allow kare ya nahi. Values: `on` / `off`.                                                                   |
| `name`            | Form ka naam set karta hai (JavaScript ya backend me form ko identify karne ke liye).                                               |
| `novalidate`      | Browser validation ko disable karta hai (submit hone se pehle check nahi karega).                                                   |
| `accept-charset`  | Kaunse character encoding use karni hai (default: UTF-8).                                                                           |
| `rel`             | Form ka relationship define karta hai ek resource ke sath (rarely used).                                                            |

---

## Example:

```html
<form action="/submit.php" method="post" enctype="multipart/form-data" autocomplete="on" target="_blank">
  <label for="username">Username:</label>
  <input type="text" id="username" name="username" required>
  <input type="submit" value="Submit">
</form>
🔹 Yahaan form ka data submit.php ko POST method se bheja jaayega, file uploads allowed hain, autocomplete on hai, aur response new tab me open hoga.
```

---

## `<form>` Element

- `<form>` ek container element hai jismein alag-alag **form controls (input elements)** hote hain.  
- Form ke andar hum text fields, checkboxes, radio buttons, buttons, dropdowns aur aur bhi input types use kar sakte hain.  

---

## Syntax
```html
<form>
  <!-- form elements -->
</form>

<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br><br>

  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname"><br><br>

  <input type="submit" value="Submit">
</form>
```

---

# 🔑 Important Note about `<label>` and `<input>`

- Jab hum `<label>` tag use karte hain, to uska `for` attribute **hamesha** us input field ki **id** ke sath match karna chahiye jiske liye wo label bana hai.  
- Isse **Accessibility** improve hoti hai aur jab user label par click kare, to directly us input box me focus chala jaata hai.  

---

## Example (Correct Way ✅)

```html
<label for="username">Username:</label>
<input type="text" id="username" name="username">
```

✅ Notes

- `<form>` ke andar ke input fields ka data key-value pairs ke form me send hota hai.

- Data ko process karne ke liye backend language (PHP, Node.js, Python, etc.) ki zarurat hoti hai.

- Form ke behavior ko action aur method attributes se control kiya jata hai (ye hum agle section me seekhenge).

---

# HTML Form Elements

HTML forms me alag-alag **tags** use hote hain jo user se input lene me help karte hain.  
Yaha mai simple language me har element ke baare me samjha raha hu:

| Tag           | Description in simple words                                                                             |
|---------------|---------------------------------------------------------------------------------------------------------|
| `<form>`      | Ye form ka main container hai jisme sab input elements rakhe jaate hain.                                |
| `<input>`     | Ye sabse common input field hai, jaise text box, password box, checkbox, radio button, etc.             |
| `<textarea>`  | Ye ek bada text box hai jisme user multiple lines me text type kar sakta hai.                           |
| `<label>`     | Ye input field ke liye name ya description provide karta hai, user ko samjhata hai ki ye field kya hai. |
| `<fieldset>`  | Ye related input fields ko group karta hai, jaise ek section banata hai form me.                        |
| `<legend>`    | Ye fieldset ka title ya heading dikhata hai.                                                            |
| `<select>`    | Ye drop-down list banata hai, jisme user ek option choose kar sakta hai.                                |
| `<optgroup>`  | Ye drop-down ke andar related options ko group karne ke kaam aata hai.                                  |
| `<option>`    | Ye drop-down ke individual option ko define karta hai.                                                  |
| `<button>`    | Ye ek clickable button create karta hai, jaise submit ya reset button.                                  |
| `<datalist>`  | Ye input field ke liye pre-defined suggestions provide karta hai, user type karte waqt.                 |
| `<output>`    | Ye calculation ka result ya output show karta hai form me.                                              |

---

✅ **Summary**
- Form elements user se data collect karte hain.  
- `<label>`, `<fieldset>`, `<legend>` form ko organize aur accessible banate hain.  
- `<select>`, `<option>`, `<datalist>` se user ke liye choices easy aur clear ho jati hain.  
- `<button>` aur `<output>` se actions aur results handle hote hain.  

---

# HTML Input Types

HTML me `<input>` element ka **type attribute** decide karta hai ki user ko kis tarah ka input field milega.  
Default type agar specify na kare to wo **text** hota hai.

---

## Common Input Types and Use

| Input Type              | Description in simple words                                |
|-------------------------|------------------------------------------------------------|
| `text`                  | Simple text box, default type                              |
| `password`              | Text box jo input ko hide karta hai (dots ya stars)        |
| `email`                 | Email address ke liye field, validation automatic hoti hai |
| `number`                | Sirf numbers input karne ke liye                           |
| `tel`                   | Phone number ke liye field                                 |
| `url`                   | Website address ke liye field                              |
| `date`                  | Date pick karne ke liye calendar popup                     |
| `time`                  | Time select karne ke liye                                  |
| `datetime-local`        | Date aur time select karne ke liye                         |
| `month`                 | Month select karne ke liye                                 |
| `week`                  | Week number select karne ke liye                           |
| `checkbox`              | Multiple choice ke liye checkbox                           |
| `radio`                 | Single choice ke liye radio button                         |
| `color`                 | Color picker ke liye                                       |
| `range`                 | Slider input ke liye                                       |
| `file`                  | User se file upload lene ke liye                           |
| `hidden`                | Hidden field, user ko dikhai nahi deta                     |
| `submit`                | Form submit karne ke liye button                           |
| `reset`                 | Form ke values reset karne ke liye button                  |
| `button`                | Simple clickable button, koi action attach karne ke liye   |
| `search`                | Search input box                                           |
| `image`                 | Image button, click par form submit ho sakta hai           |

---

✅ **Notes**
- Input type choose karne se **validation** aur user experience automatic improve ho jata hai.  
- Example: `email` type me browser check karega ki user ne valid email format enter kiya hai ya nahi.  
- Always input type set karna best practice hai for accessibility and proper behavior. 

# HTML Input Restrictions

HTML input fields me **attributes** use karke hum user input ko restrict ya control kar sakte hain.  
Ye ensure karte hain ki user sirf valid data hi enter kare.

---

## Common Input Restrictions

| Attribute    | Description in simple words                                              |
|--------------|--------------------------------------------------------------------------|
| `checked`    | Checkbox ya radio button ko page load par pre-selected banata hai        |
| `disabled`   | Input field ko disable karta hai, user edit nahi kar sakta               |
| `max`        | Maximum value set karta hai (number, date, range types ke liye)          |
| `min`        | Minimum value set karta hai (number, date, range types ke liye)          |
| `maxlength`  | Maximum number of characters allow karta hai text input me               |
| `pattern`    | Regular expression set karta hai, input us pattern se match hona chahiye |
| `readonly`   | Input field read-only banata hai, user change nahi kar sakta             |
| `required`   | Input field fill karna mandatory banata hai                              |
| `size`       | Input box ka width (characters me) define karta hai                      |
| `step`       | Number input ke liye legal increments define karta hai (jaise 1, 5, 0.1) |
| `value`      | Input field ka default value set karta hai                               |

---

✅ **Notes**
- `required` attribute se form submit hone se pehle browser check karta hai ki field filled hai ya nahi.  
- `pattern` attribute se text validation easy ho jata hai without JavaScript.  
- `readonly` aur `disabled` me difference:  
  - `readonly` → value dekhi ja sakti hai par change nahi kar sakte  
  - `disabled` → value dekhi nahi ja sakti aur form me submit bhi nahi hoti 

---

# 🖼️ HTML Images

## 📌 Basic Syntax
- Image ko web page me dikhane ke liye `<img>` tag use hota hai.  
- Image actually **insert** nahi hoti, balki HTML me **link** hoti hai (browser us path se image load karta hai).  
- `<img>` ek **empty tag** hai → iska closing tag nahi hota.  

---

## ✅ Required Attributes
1. **src (source)** → Ye image ka path batata hai (kahaan se image load hogi).  
2. **alt (alternate text)** → Agar image load na ho paye to ye text dikhai dega. Ye accessibility ke liye bhi zaroori hai (screen readers ke liye).  

---

## 🔎 Example
```html
<img src="flower.jpg" alt="A beautiful red flower">
```

---

# 📏 HTML Image Size (Width, Height, Style)

## ✅ Image Size Set Karne ke 2 Tareeke
1. **width / height attributes** → Directly tag me use karte hain.  
```html
<img src="html5.gif" alt="HTML5 Icon" width="128" height="128">
```

## style attribute (recommended) → CSS ke through inline style likhna.

```html
<img src="html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">
```

## Note- style attribute (recommended) → CSS ke through inline style likhna.

```html 
<img src="html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;"> 
```

---

# 🖼️ HTML Images from Different Locations

## 📂 1. Images in Another Folder
Agar aapke images kisi **sub-folder** me stored hain, to `src` attribute me folder ka naam dena zaroori hai.  

### Example:
```html
<img src="/images/html5.gif" alt="HTML5 Icon" style="width:128px;height:128px;">
```

---

## 🌍 2. Images from Another Server / Website

Aap kisi dusre server ya website ki image bhi use kar sakte ho. Iske liye src me absolute URL dena hota hai.

### Example:
```html
<img src="https://www.w3schools.com/images/w3schools_green.jpg" alt="W3Schools.com">
```

---

## 3. Image as a Link
To use an image as a link, put the <img> tag inside the <a> tag:

### Example
```html
<a href="default.asp">
  <img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
```

---

# 🖼️ Common Image Formats in HTML

Web pages me images use karte waqt hamesha **file format** important hota hai. Har browser (Chrome, Edge, Firefox, Safari, Opera) kuch **common formats** ko support karta hai.  

---

## 📌 1. APNG
- **Full Form:** Animated Portable Network Graphics  
- **Extension:** `.apng`  
- **Use Case:** GIF ki tarah animation support karta hai, but **better quality** ke sath.  

---

## 📌 2. GIF
- **Full Form:** Graphics Interchange Format  
- **Extension:** `.gif`  
- **Use Case:** Small animations ya simple graphics.  
- Limitation → sirf **256 colors** support karta hai.  

---

## 📌 3. ICO
- **Full Form:** Microsoft Icon  
- **Extension:** `.ico`, `.cur`  
- **Use Case:** Website ka **favicon** ya application icons.  

---

## 📌 4. JPEG
- **Full Form:** Joint Photographic Expert Group  
- **Extension:** `.jpg`, `.jpeg`, `.jfif`, `.pjpeg`, `.pjp`  
- **Use Case:** Photos aur realistic images.  
- Feature → **High compression**, isliye file size chhoti hoti hai.  

---

## 📌 5. PNG
- **Full Form:** Portable Network Graphics  
- **Extension:** `.png`  
- **Use Case:** Transparent background wali images, sharp graphics.  
- Feature → **Lossless compression** (quality degrade nahi hoti).  

---

## 📌 6. SVG
- **Full Form:** Scalable Vector Graphics  
- **Extension:** `.svg`  
- **Use Case:** Icons, logos, shapes jo **resize hone par bhi clear** rahte hain.  
- Feature → Pure text-based XML format, CSS/JS ke sath manipulate ho sakta hai.  

---

## ⚡ Summary
- **APNG / GIF** → Animations  
- **JPEG** → Photos (small size)  
- **PNG** → Transparent images / high quality  
- **SVG** → Logos & scalable graphics  
- **ICO** → Icons (browser favicon, app icon)  

---

# 🎵 HTML Audio

## 📌 The `<audio>` Element
HTML me agar hume web page par **audio file play** karni ho to hum `<audio>` element ka use karte hain.  

---

## ✅ Syntax Example
```html
<audio controls>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
```

---

# 🎵 HTML Audio - How It Works  

## ✅ 1. Controls Attribute
- Agar hum `<audio>` me `controls` lagate hain to player ke andar  
  **Play, Pause, Volume** jaise buttons automatically aa jaate hain.  

---

## ✅ 2. `<source>` Element
- `<source>` ka use **multiple audio formats** dene ke liye hota hai.  
- Browser pe depend karta hai ki wo kaunsa format pehle support kare.  
- Browser **first recognized format** ko play karega.  

---

## ✅ 3. Fallback Text
- `<audio>` aur `</audio>` ke beech ka text sirf un browsers me show hoga  
  jo `<audio>` element support nahi karte.  

## ✅ 4. Autoplay Attribute
- Agar hum chahte hain ki audio file page load hote hi play ho jaye to hum autoplay attribute use karte hain.

## ✅ 5. muted Attribute
- Add muted after autoplay to let your audio file start playing automatically (but muted):

# 🎵 HTML Audio - Important Attributes

| Attribute    | Description                                                              | Example                  |
|--------------|--------------------------------------------------------------------------|                          |
| **controls** | Audio player me **play, pause, volume** buttons show karta hai.          | `<audio controls>`       |
| **autoplay** | Audio page load hote hi **automatic play** ho jaye.                      | `<audio autoplay>`       |
| **muted**    | Audio shuru me **mute** ho (autoplay ke liye required in many browsers). | `<audio muted>`          |
| **loop**     | Audio khatam hone ke baad **repeat** ho.                                 | `<audio loop>`           |
| **preload**  | Audio file **preload** kare: `auto`, `metadata`, ya `none`.              | `<audio preload="auto">` |
| **src**      | Audio file ka path ya URL specify karta hai.                             | `<audio src="song.mp3">` |

---

## ⚡ Notes
- Multiple attributes ek saath bhi use ho sakte hain:  
```html
<audio controls autoplay muted loop>
  <source src="song.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
```

## Example:
```html
<audio controls autoplay muted>
  <source src="horse.ogg" type="audio/ogg">
  <source src="horse.mp3" type="audio/mpeg">
  Your browser does not support the audio element.
</audio>
```

---

# 🎬 HTML Video

## ✅ The `<video>` Element
HTML me video dikhane ke liye `<video>` tag use hota hai.  
Ye tag bilkul `<audio>` jaisa hi kaam karta hai, bas isme video dikhayi jaati hai.

---

## 🔹 Example
```html
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4">
  <source src="movie.ogg" type="video/ogg">
  Your browser does not support the video tag.
</video>
```

---

# 🎥 HTML Video - How it Works

## 🔹 1. `controls` Attribute
- Ye video ke liye play, pause, volume, fullscreen jaise buttons add kar deta hai.  
- Agar `controls` na ho, to video chalegi lekin user ke paas play/pause karne ka option nahi hoga.

---

## 🔹 2. `width` & `height`
- Video ka **size set karne** ke liye use hote hain.  
- Agar width & height specify **na karein**, to video load hote time **page flicker** ya shift ho sakta hai.  

👉 Isliye hamesha width & height attribute dena best practice hai.

---

## 🔹 3. `<source>` Tag
- Multiple formats (like `.mp4`, `.ogg`, `.webm`) provide karne ke liye use hota hai.  
- Browser apne supported format ko choose karega.  
- Example: Chrome `.mp4` prefer karega, Firefox `.ogg` bhi support karta hai.

---

## 🔹 4. Fallback Text
- `<video> ... </video>` ke beech ka text tab show hota hai jab **browser `<video>` tag support nahi karta**.  
- Example: "Your browser does not support the video tag."

---

⚡ **Summary:**  
- `controls` → Video player ke buttons.  
- `width & height` → Stable layout ke liye zaroori.  
- `<source>` → Different formats ke liye.  
- Fallback text → Old browsers ke liye.

---

# 🎬 HTML Video - Important Attributes

| Attribute           | Description                                                                     | Example                           |
|---------------------|---------------------------------------------------------------------------------|-----------------------------------|
| **autoplay**        | Video page load hote hi automatically play ho jaye.                             | `<video autoplay>`                |
| **muted**           | Video shuru me mute ho (especially autoplay ke liye required in many browsers). | `<video muted>`                   |
| **loop**            | Video khatam hone ke baad **repeat** ho.                                        | `<video loop>`                    |
| **poster**          | Video load hone se pehle ya jab pause ho, **image show** karta hai.             | `<video poster="image.jpg">`      |
| **controls**        | Video player ke **play, pause, volume** buttons dikhata hai.                    | `<video controls>`                |
| **width / height**  | Video ka **size** define karta hai.                                             | `<video width="320" height="240">`|

---

## ⚡ Notes
- Multiple attributes ek saath bhi use ho sakte hain:  
```html
<video width="320" height="240" controls autoplay muted loop poster="thumb.jpg">
  <source src="movie.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

---

# `<title>` Tag in HTML

- `<title>` tag **HTML document ka title define karta hai**  
- Title sirf **text-only** hota hai  
- Ye **browser ke title bar** ya **tab** me show hota hai  
- **Required tag** hai (har HTML document me hona chahiye)  
- **SEO ke liye important** hai (search engine ranking me help karta hai)  

---

## Functions of `<title>` Tag

| Purpose / Use Case          | Explanation                                                           |
|-----------------------------|-----------------------------------------------------------------------|
| **Browser Toolbar / Tab**   | Title tab ke upar ya browser ke title bar me dikhai deta hai          |
| **Favorites / Bookmarks**   | Agar user page ko save kare, to wahi title bookmark ka naam banta hai |
| **Search Engine Results**   | Search engines isi title ko results me dikhate hain                   |

---

## Tips for Writing Good Titles

- Descriptive aur meaningful rakho (sirf 1–2 shabd na likho)  
- **50–60 characters** ke beech rakho (Google iske baad cut kar deta hai)  
- Sirf keywords ka list mat banao (ye SEO ranking gira sakta hai)  
- Accurate aur content ko describe karne wala title best hota hai  

---

## Note
- Ek HTML document me **sirf ek `<title>` tag** allowed hai  

---

# HTML Favicon

- **Favicon** ek chhoti image hoti hai jo **browser tab me page title ke left side** me dikhai deti hai.  
- Ye user ko site ko **recognize karne me help** karti hai.  
- Favicon kaafi chhota hota hai, isliye image **simple aur high contrast** ka use karo.  

---

## How to Add a Favicon in HTML

1. Apna favicon image banao (jaise `.ico`, `.png`, `.jpg`).  
   - Common name: **favicon.ico**  
   - Online tool: [favicon.cc](https://www.favicon.cc)  

2. Apne web server ke **root directory** me favicon image save karo  
   - Example: `favicon.ico`  
   - Ya ek folder banao `images/` aur usme favicon store karo  

3. HTML ke `<head>` section me favicon link add karo:
```Example
<!DOCTYPE html>
<html>
<head>
  <title>My Website with Favicon</title>
  <link rel="icon" type="image/x-icon" href="/favicon.ico">
</head>
```

---

# HTML `charset` Attribute

- Web browser ko HTML page sahi tarike se dikhane ke liye **character set** pata hona chahiye.  
- Character set HTML ke `<meta>` tag ke andar specify kiya jata hai.

### UTF-8 Character Set
- 0 to 127 → ASCII ke values ke saath identical
- 128 to 159 → characters use nahi hote
- 160 to 255 → ANSI aur ISO-8859-1 ke saath identical
- 256 to 10,000+ → aur bhi characters (worldwide symbols, emojis, scripts) support karta hai

---

## Syntax

```html
<meta charset="UTF-8">
```

---

# HTML `<meta>` Tag

## Definition and Usage
- `<meta>` tag HTML document ke **metadata** ko define karta hai.  
- **Metadata = data about data** (jaise description, author, charset, viewport).  
- `<meta>` tag hamesha `<head>` element ke andar hota hai.  
- Metadata **page par display nahi hota**, lekin **machines (browsers, search engines, services)** use karte hain.  

---

## Common Uses of `<meta>` Tag
- **Character encoding** set karna  
- **Page description** (SEO ke liye)  
- **Keywords** add karna  
- **Author information** dena  
- **Viewport settings** (responsive design ke liye)  

---

## Attributes of `<meta>` Tag

| Attribute      | Value / Example                                                                  | Description                                                                  |
|----------------|----------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| **charset**    | `UTF-8`                                                                          | HTML document ke character encoding ko define karta hai                      |
| **content**    | Any text value                                                                   | Value specify karta hai jo `http-equiv` ya `name` attribute ke liye hota hai |
| **http-equiv** | `content-security-policy`, `content-type`, `default-style`, `refresh`            | HTTP header jaisa kaam karta hai                                             |
| **name**       | `application-name`, `author`, `description`, `generator`, `keywords`, `viewport` | Metadata ke liye ek name define karta hai                                    |

---

## Example

```html
<!DOCTYPE html>
<html>
<head>
  <!-- Character encoding -->
  <meta charset="UTF-8">

  <!-- Page description for SEO -->
  <meta name="description" content="Free web tutorials for HTML, CSS, JavaScript, and more.">

  <!-- Keywords for search engines -->
  <meta name="keywords" content="HTML, CSS, JavaScript, Tutorial">

  <!-- Author of the document -->
  <meta name="author" content="Abhishek Jain">

  <!-- Viewport for responsive design -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Auto-refresh after 30 seconds -->
  <meta http-equiv="refresh" content="30">

  <title>Meta Tag Example</title>
</head>
<body>
  <h1>Welcome to HTML Meta Tag Example</h1>
</body>
</html>
```