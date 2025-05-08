# Skilled eLearning Landing Page

<img src="./preview.jpg" alt="design preview" width="800">

## Skills

This project showcases a responsive flexbox layout. It also uses repsonsive images, minimal CSS with custom CSS properties and relative colors, as well as semantic HTML. 

## Instructions 

- Fork and clone this project.
- Create a **dev** branch to work in.
- Follow the requirments listed below.
- Have fun!
- When you're ready, push up your changes and open an Merge Request (MR) requesting to merge your changes from the **dev** branch into your **main** branch.

## Requirements

- Create **skilled-elearning.html** and **skilled-elearning.css** files.
- Do you best to recreate this website as close as possible to the design. See the design by opening **skilled-elearning-landing-page.pdf**. (You may need to install the **vscode-pdf** extension by *tomoki1207*.)
- Use CSS Flexbox to layout the cards
- Make it responsive (i.e. looks good on mobile, tablet, and desktop)
- Use semantic HTML elements
- Use flex-wrap with the cards.
- Use CSS Variables.

#### Bonus
- Use [responsive images](https://developer.mozilla.org/en-US/docs/Web/HTML/Responsive_images).

### Fonts

(See assets/fonts/ folder for Work Sans font.)

Here's an example of how you would add the font as a "font face" in your CSS. 

```css
@font-face {
  /* Declare it as a font-family */
  font-family: "Plus Jakarta Sans";
  src: url(./assets/fonts/PlusJakartaSans-VariableFont-wght.ttf);
}

body {
  /* using the new Work Sans font family */
  font-family: "Plus Jakarta Sans", "Helvetica Neue", Helvetica, Arial, sans-serif;
}
```
### Media queries

[Targeting Media Features](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries#targeting_media_features)

[Range Syntax](https://css-tricks.com/the-new-css-media-query-range-syntax/)


#### Responsive breakpoints 

These are examples that you can adjust to your needs.

```css
/* Default: Extra-small devices such as small phones (less than 640px) */

/* Small devices such as large phones (640px and up) */
@media only screen and (min-width: 640px) {...}

/* Medium devices such as tablets (768px and up) */
@media only screen and (min-width: 768px) {...}

/* Large devices such as laptops (1024px and up) */
@media only screen and (min-width: 1024px) {...}

/* Largest devices such as desktops (1280px and up) */
@media only screen and (min-width: 1280px) {...}
```
[Source](https://blog.logrocket.com/css-breakpoints-responsive-design/)

### Colors 

See the design PDF