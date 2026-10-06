# QR Code Component

This is my solution to the QR code component challenge from Frontend Mentor.

## Overview

I built this responsive QR code component using HTML and CSS.

The goal of this challenge was to practice translating a Figma design into a real webpage while keeping the structure semantic and the CSS maintainable.

## Built With

- HTML5
- CSS3
- CSS Custom Properties
- CSS Flexbox
- Responsive CSS
- Semantic HTML

## What I Learned

During this challenge, I practiced:

- Using semantic HTML elements such as `<main>` and `<h1>`.
- Creating global CSS variables with `:root`.
- Using CSS custom properties as design tokens for colors, spacing, and typography.
- Understanding the CSS box model.
- Using `box-sizing: border-box`.
- Centering content with Flexbox.
- Using `gap` to control spacing between flex items.
- Making a fixed-size design responsive with `max-width`.
- Styling images while preserving their aspect ratio.
- Matching typography from a Figma design using `font-size`, `line-height`, `font-weight`, and `letter-spacing`.

## Challenges

One of the main challenges was understanding why the card became larger than the dimensions specified in the design.

The problem was related to the CSS box model: the default `content-box` sizing adds padding outside the declared width and height.

I solved this by using:

```css
* {
    box-sizing: border-box;
}