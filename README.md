# Frontend Mentor - 3-column preview card component

![Design preview for the 3-column preview card component coding challenge](./design/desktop-preview.jpg)
![Design preview for the 3-column preview card component coding challenge](./design/mobile-design.jpg)

## Welcome! 👋

Thank you for watching this front-end coding challenge.

[Frontend Mentor](https://www.frontendmentor.io) challenges help improve coding skills by creating realistic projects.

**To do this challenge, you need a basic understanding of HTML and CSS.**
# CSS Code Overview

This CSS code defines the styles for a responsive grid layout, used for displaying different categories of vehicles on a webpage. The layout adjusts based on the screen size to ensure the best user experience across various devices.

## Key Features:

### Global Styles:
- **Reset and Box-Sizing**: The `*` selector removes default margin and padding for all elements and sets `box-sizing: border-box`, which ensures that padding and border are included in the element's total width and height, preventing overflow issues.
  
- **Body**:
  - The body uses `flexbox` to center the content both horizontally and vertically.
  - The background color is set to aqua, and the height is 100% of the viewport height.
  - The `overflow-y: auto` allows scrolling on vertical overflow.

- **Font Import**: Google Fonts are used for various typography, including `Caprasimo`, `Kumbh Sans`, `Lexend Deca`, `Roboto`, and `Big Shoulders Display`.

### Container and Layout:
- **Grid Layout**: The `.container` class uses a three-column grid layout for larger screens and switches to a single column on smaller screens (below 480px).
  - Columns are equally divided using `grid-template-columns: 1fr 1fr 1fr`.
  - The container width is set to 55% for large screens and 90% for smaller devices.
  - It features rounded corners (`border-radius: 15px`) and a beige background.
  
- **Category Boxes**: The `.sedans`, `.SUVs`, and `.Luxury` classes define styles for each vehicle category.
  - Each category box has a unique background color and white text.
  - The category boxes are padded, and their content is flexible in height.

### Typography:
- **Headings**: The headings (`h1`) inside `.container` use the `Big Shoulders Display` font with a size of 1.2rem for larger screens and 1.5rem for smaller screens.
- **Paragraphs**: The paragraphs (`p`) inside `.container` use the `Roboto` font with a font size of 0.56rem (adjusted to 0.8rem for smaller screens), with increased line-height for better readability.

### Button:
- The `.button` class defines a button with padding, bold text, and rounded corners. It also adjusts its size and margin for smaller screens.

### Images:
- The images inside `.container` have a fixed height and margins for consistent spacing.

### Responsive Design:
- **Media Query**: The design is responsive with a media query targeting screens smaller than 480px:
  - The container switches to a single-column layout.
  - Font sizes for headings and paragraphs are adjusted for readability on smaller screens.
  - The vehicle category boxes are re-ordered vertically in the layout.
  
### Footer:
- The `footer` is centrally aligned with additional padding at the top.

## Conclusion:
This CSS code creates a clean, flexible, and responsive layout that adapts to different screen sizes, ensuring an optimal viewing experience across devices. It uses modern CSS techniques like `flexbox`, `grid`, and media queries to provide a responsive and visually appealing design.
