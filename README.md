# A website built from scratch

- HTML
- CSS
- Wireframes
- git
- Markdown

## HTML

We start creating the skeleton (! + Enter in VSCode), then we created the header, linked the CSS and the other two big containers, main and footer.

Header, contains a logo, a heading and a navigation

```html
<header>
        <div class="logo">
            <p>My Logo</p>
        </div>
        <h1>Personal Training</h1>
        <nav class="nav-items">
            <a href="">Training</a>
            <a href="">About us</a>
            <a href="">Contact</a>
        </nav>


    </header>
```

33 CSS

Defined Primary and secondary colors, add them to the backgrounds and text colours. 

Flex box for the header to align the three elements inside centered and vertically. 

```CSS
header h1 {
    color:#2D64CF;
    display: flex;
    flex-direction: column;
    align-items: center;
}
```

## Wireframes

["Figma view"](./images/training)