# Frontend Mentor - Base Apparel coming soon page solution

This is a solution to the [Base Apparel coming soon page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/base-apparel-coming-soon-page-5d46b47f8db8a7063f9331a0).

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![](./screenshots/desktop_design.png)
![](./screenshots/desktop_active_state.png)
![](./screenshots/mobile_design.png)
![](./screenshots/mobile_active_state.png)

### Links

- Solution URL: [Github repo](https://github.com/b16h22/base_apparel_coming_soon_solution)
- Live Site URL: [Github pages](https://b16h22.github.io/base_apparel_coming_soon_solution/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Javascript

### What I learned

Learned to validate email addresses using JS regular expression.

```js
    let email = document.getElementById("email");
    
    function submitEmail() {
      if (email.validity.valueMissing) {
        showError();
      } else if (email.validity.typeMismatch) {
        showError();
      } else {
        hideError();
      }
    }
```

### Useful resources

- [HTML DOM Elements](https://www.w3schools.com/js/js_htmldom_elements.asp) - This helped me learn about HTML DOM elements and methods to access them.
- [Email Validation](https://developer.mozilla.org/en-US/docs/Web/API/ValidityState) - This helped me understand the validitystate API for validating Email and other input fields.

## Author

- Frontend Mentor - [@b16h22](https://www.frontendmentor.io/profile/b16h22)