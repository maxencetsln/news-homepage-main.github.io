# Frontend Mentor - News homepage solution

This is a solution to the [News homepage challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/news-homepage-H6SWTa1MFl). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page
- **Bonus**: Toggle the mobile menu (requires some JavaScript)

### Links

- Solution URL: [GibHub](https://github.com/maxencetsln/news-homepage-main.github.io)
- Live Site URL: [GitHub Pages](https://maxencetsln.github.io/news-homepage-main.github.io/)

### Built with

- HTML5 markup
- CSS
- Flexbox
- JavaScript (Mobile Menu)

- For the Mobile Menu

```js
const openhamburger = document.querySelector(".openHamburger");
const closehamburger = document.querySelector(".closeHamburger");
const navMenu = document.querySelector(".nav-links");

closehamburger.addEventListener("click", () => {
  navMenu.classList.toggle('mobilemenu');
  closehamburger.classList.toggle('closeHamburgerMobile');
  openhamburger.classList.toggle('openHamburgerMobile');
})

openhamburger.addEventListener("click", () => {
  navMenu.classList.toggle('mobilemenu');
  closehamburger.classList.toggle('closeHamburgerMobile');
  openhamburger.classList.toggle('openHamburgerMobile');
})
```

## Author

- GitHub Pages - [maxencetsln](https://github.com/maxencetsln)
