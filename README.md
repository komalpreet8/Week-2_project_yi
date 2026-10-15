# Week 2 Task: Implementation of Responsive Web Design

## 1. Project Overview

**Project Name:** TechZone – Responsive Technology Website

**Technologies Used:** HTML5 and CSS3

The objective of this project is to develop a responsive webpage that adapts to different screen sizes, including desktop computers, tablets, and smartphones.

## 2. Website Features

The website contains the following sections:

* Navigation bar
* Hero section with a heading and button
* Product section with three product cards
* About section
* Footer

## 3. Methods Used

### Semantic HTML

Semantic HTML elements such as `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, and `<footer>` were used to organize the webpage.

### CSS Flexbox

Flexbox was used to align the navigation bar elements and arrange content.

### CSS Grid

CSS Grid was used to create a three-column product layout on desktop screens.

### Media Queries

Media queries were used to change the layout according to screen width.

* Above 900 pixels: Three product columns.
* At 900 pixels or below: Two product columns.
* At 600 pixels or below: One product column.

### Responsive Images

Images were given a width of 100% and an appropriate aspect ratio to prevent overflow and maintain a consistent layout.

### Flexible Typography

The CSS `clamp()` function was used to adjust the main heading size according to the viewport.

## 4. Responsive Layout Adjustments

### Desktop

The navigation elements appear in a horizontal row, and all three product cards appear side by side.

### Tablet

The product section changes to two columns to provide sufficient space for each card.

### Mobile

The navigation elements are arranged vertically, and the product cards are displayed in a single column. Padding and font sizes are also adjusted for smaller screens.

## 5. Testing

The webpage was tested using browser developer tools and different viewport widths.

Example test viewports:

* Desktop: 1366 pixels
* Tablet: 768 pixels
* Mobile: 390 pixels
* Small mobile: 320 pixels

The layout, image scaling, text readability, and horizontal overflow were checked at these viewport sizes.

**Testing Status:** Fill in the actual results after testing the webpage.

## 6. Challenges and Solutions

### Challenge 1: Maintaining the layout on smaller screens

**Solution:** CSS media queries were used to change the product grid from three columns to two columns and then to one column.

### Challenge 2: Preventing images from overflowing their containers

**Solution:** Images were assigned a width of 100% and an appropriate aspect ratio.

### Challenge 3: Adjusting text for different screens

**Solution:** Responsive font sizing and appropriate spacing were used to improve readability.

### Challenge 4: Keeping the navigation usable on mobile devices

**Solution:** Flexbox was used to arrange the navigation items vertically on smaller screens.

## 7. Conclusion

This project demonstrates the implementation of responsive web design using HTML5, CSS Grid, Flexbox, fluid images, and CSS media queries. The webpage is designed to provide a consistent and readable experience across desktop, tablet, and mobile screen sizes.

