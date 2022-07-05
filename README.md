# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

- [Frontend Mentor - Product preview card component solution](#frontend-mentor---product-preview-card-component-solution)
  - [Overview](#overview)
    - [The challenge](#the-challenge)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
  - [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements
  
### Screenshot

<details>
  <summary>Mobile:</summary>

![Mobile screenshot](./screenshot-mobile.png)
</details>

<details>
  <summary>Desktop:</summary>

![Desktop screenshot](./screenshot-desktop.png)
</details>

### Links

- Solution URL: [Vercel](https://product-preview-cbserra.vercel.app/)
- Live Site URL: [GitHub](https://github.com/cbserra/product-preview)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

That I'm quite dependent on frameworks!

If you wish to add rounded borders to the parent container, such that the child elements do not overflow and square-off the `border-radius`, you can add the CSS property `overflow: hidden` to the parent container. However, you may need to explicitly size the parent container to fit the children, otherwise they may become cut-off:

```css
main {
  ...
  border-radius: calc(10 / 10 * 1rem);
  overflow: hidden;
  ...
}
```

```html
<main>
  <div class="product-image ...">
    ...
  </div>

  <section class="product-text">
    ...
  </section>
</main>
```

### Continued development

I would like to not allow myself to become completely dependent on frameworks -- they're constantly changing and it's important to be able to standup any type of application using bare tools.

- Website - [GitHub](https://www.github.com/cbserra)
- Frontend Mentor - [@cbserra](https://www.frontendmentor.io/profile/cbserra)

## Acknowledgments

Frontend Mentor's [Slack channel](https://www.frontendmentor.io/slack) is always helpful!
