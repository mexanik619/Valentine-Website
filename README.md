# Documentation for "Be My Valentine?" Webpage

## Overview
This is a fun and interactive Valentine's Day webpage designed to ask someone to be your Valentine. It features playful animations, GIFs, and an interactive button experience.

## Technologies Used
- HTML5
- CSS3
- JavaScript

## Features
1. **Animated GIFs**: Displays different GIFs based on user interaction.
2. **Two Button Choices**:
   - "Yes" button: Shows a happy bunny GIF and displays an alert.
   - "No" button: Increases the size of the "Yes" button each time it's clicked to make saying "No" harder.
3. **Styled Buttons**:
   - The "Yes" button is red with a white border.
   - The "No" button is white with a red border.
4. **Responsive Design**: The page is designed to look good on various screen sizes.

## File Breakdown
- `index.html`: The main HTML structure and content.
- Inline CSS for styling the page and buttons.
- Inline JavaScript for handling button interactions and changing GIFs.

## JavaScript Functions
### `acceptLove()`
- Changes the main GIF to a happy bunny.
- Displays an alert message confirming the acceptance.

### `growYes()`
- Increases the font size of the "Yes" button.
- Changes the main GIF to a sad bunny.

## Customization
- You can replace the GIF URLs with your own.
- Modify colors and fonts in the CSS to personalize the page.
- Adjust the growth factor in JavaScript by modifying `sizeFactor` in the `growYes` function.

## Usage
1. Open `index.html` in a browser.
2. Click "Yes" to confirm your love.
3. If you click "No", the "Yes" button grows, making it harder to refuse.

This fun interactive page is a creative way to ask someone to be your Valentine!

