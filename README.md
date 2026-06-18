# Mossy Hollow

Mossy Hollow is a fictional cozy stationery and collectibles website inspired by tiny forest creatures.

Repository: https://github.com/gzambrano-lo/mossy_hollow
Live site: https://gzambrano-lo.github.io/mossy_hollow/

## Module 3 Requirements

### Homepage HTML Structure

The homepage for the website is located in `index.html`.

This page introduces Mossy Hollow, a fictional cozy stationery and collectibles shop inspired by tiny forest creatures.

### Paragraph Element

The homepage uses paragraph elements to describe the website and characters.

Example from `index.html`:

```html
<p>Discover our unique collection of stationery and collectibles inspired by tiny forest creatures!</p>
```

Another example:

```html
<p>Our Hollows are the heart of our shop. Each Hollow is unique and has its own personality! We have:</p>
```

### Heading Element

The homepage uses heading elements such as `h1` and `h2`.

Example from `index.html`:

```html
<h1>Mossy Hollow</h1>
```

```html
<h2>Meet the Hollows</h2>
```

### Unordered List and List Items

The homepage uses an unordered list to list the Hollows.

Example from `index.html`:

```html
<ul>
    <li><a href="#mossling">Mosslings</a></li>
    <li><a href="#sporeling">Sporelings</a></li>
    <li><a href="#dewling">Dewlings</a></li>
</ul>
```

### Anchor Element

The homepage uses anchor elements for navigation and same-page links.

Example from `index.html`:

```html
<a href="pages/about.html">About</a>
```

Another example:

```html
<a href="#mossling">Mosslings</a>
```

### Main Element

The homepage includes a `main` element to hold the main content of the page.

Example from `index.html`:

```html
<main class="home-grid">
```

### Footer Element

The homepage includes a footer at the bottom of the page.

Example from `index.html`:

```html
<footer>
    <p>&copy; 2026 Mossy Hollow. All rights reserved.</p>
</footer>
```

### Image Element

The homepage includes images for the Mossy Hollow characters.

Example from `index.html`:

```html
<img src="images/characters/mossling.png" alt="Mossling forest character">
```

Other character images are also included for Sporeling and Dewling.

### Character Entity

The homepage uses the copyright character entity in the footer.

Example from `index.html`:

```html
&copy;
```

This displays the copyright symbol in the footer:

```html
<p>&copy; 2026 Mossy Hollow. All rights reserved.</p>
```

### HTML Comments

The homepage includes comments that document the structure of the page.

Examples from `index.html`:

```html
<!-- 1. header -->
```

```html
<!-- 2. main -->
```

```html
<!-- 3. footer -->
```

These comments help label the major sections of the webpage.

## Module 4 Requirements

### Type Selector

The CSS uses type selectors to style HTML elements directly.

Example from `styles/theme.css`:

```css
body {
    color: #582F0E;
    font-family: "Poppins";
    font-size: 0.9em;
}
```

Another example:

```css
h2 {
    font-weight: bold;
}
```

### ID Selector

The CSS uses ID selectors to style specific sections of the Home page.

Examples from `styles/theme.css`:

```css
#mossling {
    color: #333D29;
}
```

```css
#sporeling {
    color: #8c3220;
}
```

```css
#dewling {
    color: #205069;
}
```

### Relational Selector

The CSS uses relational selectors to style elements based on where they are located in the HTML.

Example from `styles/theme.css`:

```css
nav a {
    color: #7F4F24;
    text-decoration: none;
}
```

This targets links that are inside the navigation menu.

Another example:

```css
#mossling h2 {
    color: #333D29;
}
```

This targets an `h2` inside the section with the ID `mossling`.

### Combination Selector

The CSS uses a combination selector to apply the same style to more than one type of element.

Example from `styles/theme.css`:

```css
h1,
h2 {
    color: #572C0F;
}
```

This applies the same color to both `h1` and `h2` elements.

### Pseudo-Class Selector

The CSS uses a pseudo-class selector to style links when the user hovers over them.

Example from `styles/theme.css`:

```css
nav a:hover {
    color: #656D4A;
    text-decoration: underline;
}
```

Another example:

```css
a:hover {
    color: #8c3220;
    text-decoration: underline;
}
```

### Relative Units of Measurement

The CSS uses relative units such as `em`, `rem`, and percentages.

Examples from `styles/theme.css`:

```css
body {
    font-size: 0.9em;
}
```

```css
header {
    padding: 2em;
    margin: 1.5em;
}
```

```css
img {
    width: 40%;
    max-width: 15rem;
}
```

### Hex Color Values

The CSS specifies colors using hex codes.

Examples from `styles/theme.css`:

```css
body {
    color: #582F0E;
}
```

```css
header {
    background-color: #f7f3e8;
    border: 0.2em solid #7F4F24;
}
```

```css
footer {
    background: linear-gradient(to right, #c2c5aa, #a4ac86);
}
```

### Element Color

The CSS sets the color of multiple elements.

Example from `styles/theme.css`:

```css
body {
    color: #582F0E;
}
```

The character sections also have their own colors:

```css
#mossling {
    color: #333D29;
}
```

### Font Styling

The CSS uses font-related properties.

Examples from `styles/theme.css`:

```css
body {
    font-family: "Poppins";
    font-size: 0.9em;
}
```

```css
h2 {
    font-weight: bold;
}
```

## Module 5 Requirements

### Padding and Margins

The website uses padding and margins on multiple elements to improve spacing and presentation.

Examples from `styles/theme.css` include:

```css
header {
    padding: 2em;
    margin: 1.5em;
}
```

```css
main {
    padding: 1.5em;
    margin: 1.5em;
}
```

```css
section {
    padding: 1.5em;
    margin-bottom: 2em;
}
```

Additional spacing is also used in the navigation:

```css
nav ul {
    padding: 1em;
    margin-top: 1em;
}

nav li {
    margin: 0 1em;
}
```

### Borders

The website includes borders on the header, images, and footer.

Examples from `styles/theme.css`:

```css
header {
    border: 0.2em solid #7F4F24;
}
```

```css
img {
    border: 0.25em solid #656D4A;
}
```

```css
footer {
    border-top: 0.2em solid #582F0E;
}
```

### Background Image or Gradient

The website uses a background image on the body:

```css
body {
    background: url("../images/background/background.png") repeat;
}
```

The footer also uses a gradient background:

```css
footer {
    background: linear-gradient(to right, #c2c5aa, #a4ac86);
}
```

### 2- or 3-Column Layout

The Shop page uses a 3-column layout for product images.

The layout is located in `pages/shop.html`:

```html
<section id="display-images">
    <img src="../images/products/product_line_up.png" alt="A line up of our products, including journals, stickers, washi tapes, stamps and thank you cards.">
    <img src="../images/products/stamp_set.png" alt="A set of our stamp designs.">
    <img src="../images/products/thank_you_cards.png" alt="A selection of our thank you cards.">
</section>
```

The CSS for the 3-column layout is located in `styles/theme.css`:

```css
#display-images {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1em;
    justify-items: center;
}
```

This creates three columns for the product image section on the Shop page.

## Module 6 Requirements

### Horizontal Navigation Menu

The website includes a consistent horizontal navigation menu on every page:

- `index.html`
- `pages/about.html`
- `pages/shop.html`
- `pages/contact.html`

Example navigation code:

```html
<nav>
    <ul>
        <li><a href="../index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="shop.html">Shop</a></li>
        <li><a href="contact.html">Contact</a></li>
    </ul>
</nav>
```

### At Least 3 HTML Pages

The site has four pages:

- Home: `index.html`
- About: `pages/about.html`
- Shop: `pages/shop.html`
- Contact: `pages/contact.html`

### External Link Opening in a New Tab

The external links are located on the About page in `pages/about.html`.

Example:

```html
<a href="https://smiski.com/e/smiski/" target="_blank" rel="noopener noreferrer">Smiski</a>
```

This link opens an external website in a new browser tab.

### Same-Page Placeholder Links

The same-page placeholder links are located on the Home page in `index.html`.

The "Meet the Hollows" section links to sections lower on the same page:

```html
<a href="#mossling">Mosslings</a>
<a href="#sporeling">Sporelings</a>
<a href="#dewling">Dewlings</a>
```

These links jump to matching section IDs:

```html
<section id="mossling">
<section id="sporeling">
<section id="dewling">
```

There is also a Back to Top link:

```html
<a href="#top">Back to top</a>
```

It links back to:

```html
<header id="top">
```

### Media Queries

The media queries are located in `styles/theme.css`.

They adjust the layout at two screen-size breakpoints using relative units:

```css
@media (max-width: 48rem) {
    .home-grid {
        grid-template-columns: 1fr;
        grid-template-areas:
            "welcome-hook"
            "mossling"
            "sporeling"
            "dewling"
            "back-to-top";
    }

    #about-columns,
    #display-images {
        grid-template-columns: repeat(2, 1fr);
    }

    img {
        width: 70%;
    }
}
```

```css
@media (max-width: 30rem) {
    #about-columns,
    #display-images {
        grid-template-columns: 1fr;
    }

    nav ul {
        flex-direction: column;
        align-items: center;
    }

    img {
        width: 90%;
    }
}
```

### Fluid Layout

The website uses fluid layout techniques instead of fixed layouts.

Examples from `styles/theme.css` include:

```css
#display-images {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
}
```

```css
#about-columns {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
}
```

These use fractional units so the columns adjust to the available space.

### Scalable Image

The website includes scalable images. The image styling is located in `styles/theme.css`.

```css
img {
    width: 40%;
    max-width: 15rem;
}
```

This allows images to scale with the page while still having a maximum size.

### Comments in HTML and CSS

The HTML files include comments that label sections such as the header, navigation, main content, and footer.

The CSS file includes comments that describe selectors, layout styling, link styling, columns, and media queries.

## Module 7 Requirements

### Flexbox Containers

The website includes at least two flex containers.

The navigation menu uses flexbox to arrange the links:

```css
nav ul {
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 1em;
    list-style-type: none;
}
```

The page body also uses flexbox to keep the footer at the bottom of short pages:

```css
body {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
}

footer {
    margin-top: auto;
}
```

### Grid Layout

The Home page uses a grid page layout with named grid areas:

```css
.home-grid {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr;
    grid-template-areas:
        "welcome-hook welcome-hook welcome-hook"
        "mossling sporeling dewling"
        "back-to-top back-to-top back-to-top";
    gap: 1em;
}
```

The About and Shop pages also use grid components for their article columns and product images.

### Responsive Breakpoints

The site uses media queries at `48rem` and `30rem` to adjust grid layouts, image sizing, and navigation layout as the viewport gets smaller.

### Complete Pages

The site includes four complete pages with real content:

- `index.html`
- `pages/about.html`
- `pages/shop.html`
- `pages/contact.html`

## Module 9 Peer Feedback Fixes

### Peer Suggestion #1

A peer suggested improving the footer placement so it stayed at the bottom of shorter pages.

Fix implemented:
I updated the page layout by using flexbox on the body and `margin-top: auto` on the footer.

### Peer Suggestion #2

A peer pointed out that the hyperlink that brings the user back to the top was difficult to recognize as a clickable element. This was because the hyperlink color did not contrast enough from the other body text in the card and other parts of the website, especially since Mossling's body font had a similar color.

**Fix implemented:**  
I updated the back-to-top link styling in `styles/theme.css` so the link is easier to identify. I made the link bold and underlined to improve visibility and make it clearer that the text is clickable.

### Peer Suggestion #3

A peer pointed out an accessibility issue on the home page. The Dewling section text color had a low color contrast score of 2.06-2.47, while the Web Content Accessibility Guidelines recommend a minimum contrast ratio of 4.5.

**Fix implemented:**  
I updated the Dewling text color in `styles/theme.css` to a darker shade so the section is easier to read and has better color contrast.
