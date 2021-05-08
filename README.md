# Conquering-Responsive-Layouts

Repo to follow Kevin Powell's Conquering Responsive Layouts Course

## Day 1

Avoid using heights, because it makes our site to become unresponsive.
When setting a width, always use relative sizes such us percentage instead of using fixed values like 10px;
Also complete challenge 1

## Day 2

Quick understanding of how em and rem works

## Day 3

Use max width to avoid our divs to grow when the screen size is bigger.
Also complete challenge 2

## Day 4

Use os units vw, vh, vmin and vmax in texts and maybe in heights.

## Day 5

Challenge number 3, create the desired page from scratch

## Day 6

em should not ve used for font-fize because it can grown exponentialy
rem is better for font-size because it takes the root value

## Day 7

Just a review of challenge number 3

## Day 8

Introduction to flex box.
Use of `display: flex` and `flex-direction`

Challenge number 4 add columns using flex-box

## Day 9

Column widths, hero image.
Second flex box challenge.

## Day 10

It's better to use tags like `<main></main>` or `<aside></aside>` for accesibility reasons.
But if i'm not sure of what tag to use, I could rely on `<div></div>`

## Day 11

Challenge 06: Create a nav with flex box

## Day 12

Challenge 07: Create a complete design from scratch

## Day 13 / 14

Use of `min()`, `max()` and `clamp()`.
Example: `width: min(80%, 720px)` is the same as: `width: 80%; max-width: 720px`

## Day 15

Introduction to media querys.

Mobile first approach

```css
@media (min-width: 600px) {
  .container {
    background: red;
  }
}
```

Desktop first approach

```css
@media (max-width: 600px) {
  .container {
    background: red;
  }
}
```

## Day 16

How to find the breakpoints.
It could depend on the design. Or we can use some hard coded values such as listed here:
[Breakpoints](https://www.freecodecamp.org/news/the-100-correct-way-to-do-css-breakpoints-88d6a5ba1862/)

## Day 17

Must add this meta tag in order to media querys work.

`<meta name="viewport" content="width=device-width, initial-scale=1.0">`

## Day 18

Create a mobile first design.
Use of `media querys` usign `min-width`
