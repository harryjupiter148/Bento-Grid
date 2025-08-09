# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learnt](#what-i-learnt)
  - [Continued development](#continued-development)
- [Author](#author)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![Desktop View](./assets/images/grid-main.png)
![Mobile View](./assets/images/grid-main-respo.jpeg)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learnt

I was impressed with myself for getting to understand the usage of this:
```css
main {
    grid-template-areas:
      "seven one one four"
      "seven two three four"
      "eight two three four"
      "eight two three four"
      "eight six five five";
}

main section {
    &:first-child {
        grid-area: one;
    &:nth-child(2) {
        grid-area: two;
    &:nth-child(3) {
        grid-area: three;
    &:nth-child(4) {
        grid-area: four;
    &:nth-child(5) {
        grid-area: five;
    &:nth-child(6) {
        grid-area: six;
    &:nth-child(7) {
        grid-area:  seven;
    &:last-child {
        grid-area: eight;
```

### Continued development

The `grid` property is something I would like to look into soon, as there are other properties associated with it. Playing around with it was fun, especially the `grid-template-areas` property, where I had to manipulate certain selectors to placements of my choice. This wouldn't be possible without the `grid-area` property I learnt along with the others.

## Author

- Github - [@harryjupiter148](https://github.com/harryjupiter148)
