# WildcatWear Website

WildcatWear is an online store that offers official University of Arizona merchandise for students, alumni, and fans. The website features a modern design with a focus on layouting and responsiveness. Built using HTML5 + CSS3 for Web Programming course.

## Features

- Navigation with hamburger menu for mobile devices
- Search functionality with toggle feature
- Neat layout with flex and grid
- A sample Product page
- Responsive to multiple screen sizes

## Project Structure

```
WildcatWear-Website/
├── README.md               # Project description and setup instructions
├── index.html              # Home page
├── store.html              # Sample Product page
├── css/
│   ├── style.css           # Main stylesheet
│   ├── utility-styles.css  # Utility classes
│   └── store.css           # Store-specific styles
└── images/
    ├── wildcat-logo.png    # Site Logo
    ├── home-hero.jpg       # Hero image for index.html
    ├── store-hero.jpg      # Hero image for store.html
    ├── jersey.jpg          # Example product image
    └── ...
```
## Responsive Design

The website is fully responsive and optimized for:
- **Desktop** (1024px and above)
- **Tablet** (768px to 1023px)
- **Mobile** (below 768px)

## Setup Instructions

1. Clone or download this repository to your local machine:
   ```sh
   git clone https://github.com/your-username/WildcatWear-Website.git
   ```
2. Ensure all image files are placed in the `images/` directory.
3. Make sure all CSS files are in the `css/` directory.
4. Open `index.html` in a web browser to view the homepage.

## Testing Guide

### Desktop Testing
1. Open `index.html` in different browsers (Chrome, Firefox, Safari, Edge).
2. Verify that:
   - All images load properly.
   - The layout is consistent across screen sizes and browsers.
   - Navigation bar links work correctly (Home ↔ Store).
   - The homepage's "Shop by Category" and "Featured Products" sections display properly.
   - Product details, size selection, and "Add to Cart" button are shown correctly on `store.html`.

### Mobile Testing
1. Use browser developer tools to test the responsive design.
2. Test at various breakpoints:
   - **Below 768px**: The navigation menu should collapse into a hamburger menu.
   - **Web pages**: Layouts & images should resize correctly, and all details should remain readable.

### Accessibility Testing
1. Use a screen reader to navigate the site.
2. Verify that:
   - All images have descriptive `alt` text.
   - The heading hierarchy is properly structured for screen readers.
   - Text contrast meets accessibility standards.

## Color Scheme

The website uses University of Arizona's official colors.
Obtained from https://phoenixmed.arizona.edu/brand-toolkit/design/color

## Acknowledgments

- University of Arizona for brand guidelines and inspiration
- Font Awesome for icons
- All images are used for demonstration purposes only

For any questions or issues, please open a GitHub issue or contact me at tiffanytjhin@arizona.edu.
