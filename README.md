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
      let emailAddress = email.value;
      const regEx = /^[a-zA-Z0-9._-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,6}$/;
      const isValid = regEx.test(emailAddress);
      checkEmail(isValid);
    }
```

### Useful resources

- [HTML DOM Elements](https://www.w3schools.com/js/js_htmldom_elements.asp) - This helped me learn about HTML DOM elements and methods to access them.
- [JS Regular Expressions](https://www.w3schools.com/js/js_regexp.asp) - This helped me learn about JS regular expressions.

- [RegEx for Email Validation](https://zparacha.com/validate-email-address-using-javascript-regular-expression) - This helped me understand the regEx required for email validation.

## Author

- Frontend Mentor - [@b16h22](https://www.frontendmentor.io/profile/b16h22)