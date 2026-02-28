# Activity: CSS Styling (Part 1)

In this activity you will practise using **CSS** to change how a web page looks.  
This is your first time working with CSS, so the instructions are clear and step by step.

---

## What you are learning

- **HTML** provides the structure and content of a web page  
- **CSS** controls how that content looks  

CSS works by writing **rules** in the following format:

```css
selector {
  property: value;
}
```

- A **selector** chooses what you want to style  
- A **property** is what you want to change
- A **value** is how you change it  

---

## Files you will use

For this activity you will work with:
- `index.html`
- `style.css` (you will create this file if it does not already exist)

Tip: Make small changes and save often.

---

# Task 1: Create and Link a CSS File

In this task you will create a CSS file and link it correctly so the browser can apply the styling.

## Step 1: Create `style.css`

- In your project folder, create a new file called:

`style.css`

## Step 2: Link the CSS file in `index.html`

- Open `index.html`
- Inside the `<head>` section, add the following line:

```html
<link rel="stylesheet" href="style.css">
```

Your `<head>` section should look similar to this:

```html
<head>
  <title>CSS Practice</title>
  <link rel="stylesheet" href="style.css">
</head>
```

## Step 3: Check that it works

- Open `style.css`
- Add the following rule:

```css
body {
  background-color: lightyellow;
}
```

- Save the file and refresh the page  

If the background changes colour, your CSS file is linked correctly.

If nothing happens:
- Check the file name is exactly `style.css`
- Check the link is inside the `<head>` section
- Check for spelling mistakes

---

# Task 2: Using Basic CSS Selectors

In this task you will style common HTML elements using simple selectors.

## Step 1: Style the whole page

```css
body {
  font-family: Arial, sans-serif;
}
```

## Step 2: Style the main heading

```css
h1 {
  color: blue;
}
```

## Step 3: Style paragraphs

```css
p {
  color: black;
}
```

## Step 4: Style list items

```css
li {
  color: darkgreen;
}
```

### What to notice

- A selector such as `p` styles **all** paragraphs  
- A selector such as `li` styles **all** list items  

This is why CSS is described as *cascading*.

---

# Task 3: Fonts and Colours Practice

In this task you will practise changing fonts, colours and spacing.

## Step 1: Improve section headings

```css
h2 {
  background-color: lightblue;
  color: navy;
  padding: 8px;
}
```

## Step 2: Improve readability

```css
p {
  font-size: 16px;
  line-height: 1.5;
}
```

## Step 3: Style links

```css
a {
  color: blue;
}
```

Optional hover effect:

```css
a:hover {
  color: red;
}
```

---

## Checkpoint

When you have completed Tasks 1 to 3, save and push your changes:

```bash
git add .
git commit -m "Completed tasks 1-3"
git push origin main
```

---

# Extension Activities

## Extension 1: Class Selectors

Class selectors allow you to style one specific element.

### Step 1: Add a class in HTML

```html
<p class="highlight">This text should stand out.</p>
```

### Step 2: Style the class in CSS

```css
.highlight {
  background-color: lightgreen;
  border: 1px solid green;
  padding: 6px;
}
```

Class selectors always start with a dot `.`

---

## Extension 2: Grouping Selectors

You can style multiple elements with one rule.

```css
h1, h2 {
  font-family: "Trebuchet MS", Arial, sans-serif;
}
```

Try grouping:
- `h1, h2`
- `p, li`

---

## Extension 3: Create a Simple Colour Theme

Try creating a simple colour theme using basic colours only.

```css
body {
  background-color: lightgrey;
}

h1, h2 {
  color: darkblue;
}

p, li {
  color: black;
}
```

---

## Checkpoint

When you have completed the extensions, save and push your changes:

```bash
git add .
git commit -m "Completed extension activities"
git push origin main
```

---

# Advanced Activity: Styling Challenge

This activity is a challenge.  
You are not given step-by-step instructions.

Use what you have learned so far about:
- Selectors
- Properties
- Values
- Fonts
- Colours
- Spacing

## Your Challenge

Try to improve the appearance of your page by achieving **at least two** of the following:

- Make the main content stand out from the page background  
- Add space around sections so the page feels less crowded  
- Add a visible outline or edge to a section  
- Improve how the header area looks compared to the rest of the page  

You may need to:
- Experiment with different CSS properties
- Look back at earlier examples
- Try values and see what happens

There is no single correct solution.

---

## Checkpoint

When you are happy with your changes, save and push your work:

```bash
git add .
git commit -m "Completed advanced activity"
git push origin main
```

--- 

## Self-Check

By the end of this activity you should be able to:
- Link a CSS file correctly  
- Write CSS rules using selectors, properties and values  
- Change fonts and colours  
- Style text and links  
- Use a class selector  
- Improve spacing and appearance through experimentation  

---
