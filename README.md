# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm).

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
This is a front-end challenge from Frontend Mentor. The task is to build out a recipe page and to make it as similar as possible to the original design.

### Screenshot

![Desktop Version](./Screenshot%20(Desktop).png)
![Mobile Version](./Screenshot%20(Mobile).png)

### Links

- Solution URL: [https://github.com/abigbroomstick/recipe-page](https://github.com/abigbroomstick/recipe-page)
- Live Site URL: [https://abigbroomstick.github.io/recipe-page/](https://abigbroomstick.github.io/recipe-page/)

## My process
I started by visualizing and structuring the HTML so that each section is logically organized. I then styled the page using CSS and color scheme provided in the style guide, focusing on making it responsive and looking as close as possible to the design photos.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

By tackling this challenge, I learned how to use grid more effectively and especially familiarizing myself with tables and lists as I haven't got many opportunities using them. Moreover, this is the first challenge that I used variables and custom properties. I think they are super useful when making a responsive website.

```html
<h1>Some HTML code I'm proud of</h1>
<section class="ingredients">
        <h2>Ingredients</h2>
        <ul>
          <li>2-3 large eggs</li>
          <li>Salt, to taste</li>
          <li>Pepper, to taste</li>
          <li>1 tablespoon of butter or oil</li>
          <li>Optional fillings: cheese, diced vegetables, cooked meats, herbs</li>
        </ul>
      </section>
      <div class="divider"></div>
      <section class="instructions">
        <h2>Instructions</h2>
        <ol>
          <li><span class="bold">Beat the eggs:</span> In a bowl, beat the eggs with a pinch of salt and pepper until they are well mixed.
            You can add a tablespoon of water or milk for a fluffier texture.</li>
          <li><span class="bold">Heat the pan:</span> Place a non-stick frying pan over medium heat and add butter or oil.</li>
          <li><span class="bold">Cook the omelette:</span> Once the butter is melted and bubbling, pour in the eggs. Tilt the pan to ensure
            the eggs evenly coat the surface.</li>
          <li><span class="bold">Add fillings (optional):</span> When the eggs begin to set at the edges but are still slightly runny in the
            middle, sprinkle your chosen fillings over one half of the omelette.</li>
          <li><span class="bold">Fold and serve:</span> As the omelette continues to cook, carefully lift one edge and fold it over the
            fillings. Let it cook for another minute, then slide it onto a plate.</li>
          <li><span class="bold">Enjoy:</span> Serve hot, with additional salt and pepper if needed.</li>
        </ol>
      </section>
      <div class="divider"></div>
      <section class="nutrition">
        <h2>Nutrition</h2>
        <p>The table below shows nutritional values per serving without the additional fillings.</p>
        <table>
          <tr>
            <td data-cell="nutrient">Calories</td>
            <td data-cell="nutrient-value"><span class="bold">277kcal</span></td>
          </tr>
          <tr>
            <td data-cell="nutrient">Carbs</td>
            <td data-cell="nutrient-value"><span class="bold">0g</span></td>
          </tr>
          <tr>
            <td data-cell="nutrient">Protein</td>
            <td data-cell="nutrient-value"><span class="bold">20g</span></td>
          </tr>
          <tr class="no-divider">
            <td data-cell="nutrient">Fat</td>
            <td data-cell="nutrient-value"><span class="bold">22g</span></td>
          </tr>
        </table>
      </section>
```
```css
.proud-of-this-css {
  table {
    width: 100%;
    padding: 1rem;
    border-collapse: collapse;
    margin-top: 1rem;
}

[data-cell= "nutrient-value"] {
    color: var(--Nutmeg);
}

tr {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    padding: 0.75rem;
}

tr:not(.no-divider) {
    border-bottom: 1px solid var(--Light-Grey);
}

[data-cell= "nutrient"], [data-cell= "nutrient-value"] {
    padding-left: 1.5rem;
}
}
```
### Continued development

I want to learn more javascript to integrate it to this project and maybe build out the full website some day. 

### Useful resources

- [Two simple layouts that work better with Grid](https://www.youtube.com/watch?v=r1IitKbJRFE&list=PL4-IK0AVhVjPv5tfS82UF_iQgFp4Bl998&index=14) - Kevin Powell's channel has helped me tremendously when I started learning how to use CSS Gride. I really liked it and will use it going forward.

## Author

- Github - [@abigbroomstick](https://github.com/abigbroomstick)
- Frontend Mentor - [@abigbroomstick](https://www.frontendmentor.io/profile/abigbroomstick)
- Facebook - [@Nam Nguyen](https://www.facebook.com/nam.nguyenbathanh/)

## Acknowledgments

Ashleynguci- she gave me huge motivation to learn web development :D
Colt Steele- best Udemy Front-End class I've taken so far
Kevin Powell- a great source for learning web development for FREE!
Nheo Hi- my lovely girlfriend who puts up with me every time I stayed up late to code.
