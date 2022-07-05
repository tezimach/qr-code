
## Table of Contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Links

- Solution URL: (https://glitch.com/edit/#!/pepper-glory-verse)
- Live Site URL: (https://pepper-glory-verse.glitch.me)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Used "meyerweb reset" (http://meyerweb.com/eric/tools/css/reset/)
- [Glitch] (https://glitch.com)
- [Figma for Style Components and information about challenge] (https://www.figma.com)

### What I learned

- connecting html and css files
- searching and linking fonts from google
- adding favicon to html

```html
 - <link rel="stylesheet" href="style.css">
 - <link rel="icon" type="image/x-icon" href="https://cdn.glitch.global/a4c35a8d-4440-4091-9413-d1531f1f2a0c/favicon-32x32.png?v=1655419938984"/>
 - <link href="https://fonts.googleapis.com/css2?family=Outfit:wght@400;700&display=swap" rel="stylesheet">
```
- positioning objects
- changing colour of backgrounds and fonts
- changing font, line, margin, and object sizes
- changing object corners
- creating shadows

```css
body {
	line-height: 0;
  background: hsl(212, 45%, 89%);
  width: 1440px;
  height: 800px;
  display: flex;
  justify-content: center;
  align-items: center;
}

main {
  background: hsl(0, 0%, 100%);
  height: 497px;
  width: 320px;
  margin: 0 auto;
  border-radius: 20px;
  box-shadow: 0px 25px 25px hsla(0, 0%, 0%, 0.05);
}

img {
  width: 288px;
  height: 288px;
  margin: 16px;
  margin-bottom: 24px;
  border-radius: 10px;
}

h1 {
  margin:0 16px;
  text-align: center;
  font-family: Outfit, sans-serif;
  color: hsl(218, 44%, 22%);
  font-weight: 700;
  font-size: 22px;
  line-height: 28px;
}

p {
  margin: 16px 32px;
  text-align: center;
  font-family: Outfit, sans-serif;
  color: hsl(220, 15%, 55%);
  font-weight: 400;
  font-size: 15px;
  line-height: 19px;
  letter-spacing: 0.1875px;
  font-style: normal;
}
```

### Continued development

- I am not sure favicon is added by the rules.
- I don't know how to check if favicon is add or not.

### Useful resources

- https://learn.shayhowe.com/html-css/getting-to-know-css/
- https://www.digitalocean.com/community/tutorials/how-to-load-and-use-custom-fonts-with-css
- https://www.w3schools.com
- https://www.javatpoint.com
- https://css-tricks.com/centering-css-complete-guide/

## Author

- Tengiz Machavariani