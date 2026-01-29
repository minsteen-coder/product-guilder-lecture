# Lotto Number Generator

## Overview

A simple, visually appealing web application to generate random lotto numbers. The application will feature a clean, modern design and provide users with a set of 6 unique numbers with a single click.

## Design and Features

### Style & Design
- **Layout:** A centered, clean layout that is mobile-responsive.
- **Color Palette:** A vibrant and energetic color scheme.
- **Typography:** Expressive and clear fonts to emphasize the generated numbers.
- **Iconography:** Use of icons to enhance user understanding.
- **Visual Effects:**
    - Subtle noise texture for the background.
    - Multi-layered drop shadows for depth.
    - "Lifted" card effect for the main container.
    - "Glow" effect for interactive elements like the button.
- **Components:** A custom web component (`<lotto-ball>`) will be used to display each lotto number, making the code modular and reusable.

### Features
- **Number Generation:** Generate 6 unique random numbers between 1 and 45.
- **Display:** Display the generated numbers in a visually appealing way using the `<lotto-ball>` component.
- **Interactivity:** A button to trigger the generation of new numbers.

## Current Plan

1.  **`index.html`**: Set up the basic structure of the application, including the main container, a button, and placeholders for the numbers.
2.  **`style.css`**: Implement the modern design, including layout, colors, fonts, and visual effects.
3.  **`main.js`**:
    - Create the `LottoBall` web component to display individual numbers.
    - Implement the logic for generating and displaying the unique lotto numbers when the button is clicked.
