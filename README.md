# The Basics of a HTML Webpage
by Ryan Barnard

Hello! This tutorial goes over the very basics of an HTML webpage and explains what each main part does.

Target audience:  
People who are new to HTML or website development and want a basic idea of how a simple page is put together.

---

## Introduction

When you visit a website, the browser usually begins by loading an HTML file called index.html.  
HTML stands for **HyperText Markup Language**. It tells the browser what to show on the screen.

In this tutorial, we will look at an example HTML page and then go through it line by line.

---

## What is an HTML file?

An HTML file is just a text file that ends in `.html`.  
Inside it are tags like `<html>`, `<head>`, `<body>`, `<h1>`, and `<p>`.

Typically the first HTML file you create is named index.html.

- `index.html` → many web servers treat this as the “home page” of a site or folder. So when you visit https://example.com, the browser downloads the index.html located in the directory you are accessing.

---

## Example `index.html`

Here is a small HTML page we will use as our example:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Title of Webpage</title>
  </head>
  <body>
    <h1>(Largest heading - h1) Hello, world!</h1>
    <p>(Paragraph tag - p) This is my first HTML page.</p>
  </body>
</html>
```

If you were to save this file as `index.html` and open it in a browser, your browser would render page with the heading and paragraph below it. The title would be displayed on the browser tab.

---

## Breaking down the example

### 1. `<!DOCTYPE html>`

- This line tells the browser that the page is written in HTML5.
- It goes at the very top of most HTML files.
- You usually just copy this as is.

---

### 2. `<html>` and `</html>`

- The `<html>` tag wraps everything in the page.
- The closing tag `</html>` at the bottom marks the end of the document.
- Everything in between `<html>` and `</html>` is part of the page.

---

### 3. `<head>` and `</head>`

```html
<head>
  <title>Title of Webpage</title>
</head>
```

- The `<head>` section holds the information that describes the page.
- Most of the things in `<head>` do not show up as normal text or content on the page.
- It usually includes the title of the page or links to CSS files which are used for styling.

---

### 4. `<title>Title of Webpage</title>`

- The `<title>` tag sets the text that appears in the **browser tab**.
- In this example, the tab will say “Title of Webpage”.
- This title can also show up in bookmarks and search results.

---

### 5. `<body>` and `</body>`

```html
<body>
  <h1>(Largest heading - h1) Hello, world!</h1>
  <p>(Paragraph tag - p) This is my first HTML page.</p>
</body>
```

- The `<body>` section is where all the **visible content** goes.
- Headings, paragraphs, images, links, lists, etc are all stored inside the `<body>` section.
- Anything you want the user to see should be inside these tags.

---

### 6. `<h1>(Largest heading - h1) Hello, world!</h1>`

- `<h1>` is a heading tag.
- It is the largest heading HTML offers without additional styling. Usually the most important heading on the page is enclosed in an h1 tag.
- Here it simply prints “(Largest heading - h1) Hello, world!” at the top of the page.

There are also `<h2>`, `<h3>`, and so on for smaller headings.

---

### 7. `<p>(Paragraph tag - p) This is my first HTML page.</p>`

- `<p>` stands for “paragraph”.
- It is used for regular blocks of text.
- In this example it just shows a short sentence explaining the page.

You can add more paragraphs by using more `<p> </p>` tags.

---

## How this fits together

To recap:

- `<!DOCTYPE html>` tells the browser to use HTML5.
- `<html>` wraps the entire page.
- `<head>` holds information about the page (like the title and styling documents).
- `<body>` holds the content that actually shows up on the screen.
- Inside `<body>` you can use tags like `<h1>` for headings and `<p>` for paragraphs.

This simple structure (doctype, html, head, body) is used on almost every website, even if real sites are much more complex. Once you understand this basic layout, you can start adding more tags and styling later.
