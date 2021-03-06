# Build a Product Landing Page with Plain HTML/CSS

![Product Landing Page Exercise for HTML/CSS](https://github.com/breatheco-de/exercise-product-landing-page-plain-css/blob/master/.learn/assets/preview.png?raw=true)

Doing layouts is one of the most difficult things in CSS/HTML, it has never been a good technology for that purpose, which is weird and sad because it's its main focus. 🤔🤪

But in the past couple of years everything has been improving, since 2018 we can use now the CSS rules `display: flex;` and `display: grid;`.

There are also some CSS frameworks like Bootstrap [that is broadly used in ~30% of the world websites.](https://w3techs.com/technologies/details/js-bootstrap), Foundation, Material UI, etc. But this exercise is focused mainly on polishing your plain CSS/HTML skills.

## 📝 Instructions

1. Replicate [this exact product page](https://github.com/breatheco-de/exercise-product-landing-page-plain-css/blob/master/.learn/assets/preview.png?raw=true) in HTML/CSS. You cannot use any CSS framework and the landing does not have to be responsive.
2. Use the images on the `./assets` folder.
3. Use the flex-box CSS rules, here is a great document explaining about it: https://css-tricks.com/snippets/css/a-guide-to-flexbox/

## 🌱  How to start this project

1. This project comes with the necessary files to start working.
2. Clone this repository locally or open it with gitpod for a better experience.
3. Run the following command to preview your changes: `npx --yes http-server`

Note: you will have to refresh your browser every time you update your code.

## 🥵 No one tells you this:

- 40% of the errors when doing HTML are missing or misplaced closing tags, to avoid that you should open a close the tag at the same time and then you fill the tag content.

- Picking the names of the CSS classes is the real trick: The names of the classes shape your mindset. Instead of using business-oriented naming like product1, product2, about-us, etc. You should use behavior-oriented names like `menu` or `horizontal-list`, etc. That will help you re-use classes a lot.

- Don't use the `<img>` for images that will be uploaded later by a user, you should instead use `<div>` with background images, the image tag is only used for little things.
