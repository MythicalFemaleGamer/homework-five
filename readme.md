Web4 address: https://in-info-web4.luddy.indianapolis.iu.edu/~jat5/homework-five/

# Homework Five - Responsive Design

A responsive travel booking website built with HTML, SCSS, and vanilla JavaScript featuring adaptive layouts for mobile and desktop viewports.

## Dependencies

- **Font Awesome** (v7.0.1) - Icon library for social media icons
- **Custom Fonts**:
  - Proxima Nova Extra Condensed
  - Gill Sans Light

## Technologies Used

- HTML5
- SCSS/CSS3
- Vanilla JavaScript
- Media Queries for responsive design

## Project Structure

```
homework-five/
├── index.html
├── about.html
├── tours.html
├── special-offers.html
├── blog.html
├── contact.html
├── css/
│   ├── styles.css (compiled)
│   └── fonts/
│       ├── ProximaNovaScOsfExtraCondensed.ttf
│       └── GillSans-Light.ttf
├── scss/
│   ├── styles.scss (main import file)
│   ├── variables.scss
│   ├── components.scss
│   ├── structure.scss
│   ├── nav.scss
│   ├── home.scss
│   └── response.scss (media queries)
├── images/
│   ├── hero.jpg
│   ├── logo/
│   └── [other images]
└── readme.md
```

## Features

- Responsive navigation bar
- Hero section with call-to-action
- Promotional image cards
- Booking form with responsive inputs
- Footer with social media links
- Mobile-first breakpoints at 900px and 1110px

## Setup

1. Clone or download the repository
2. Compile SCSS files to CSS (ensure `response.scss` is imported last)
3. Open `index.html` in a browser

## Media Query Breakpoints

- **Mobile**: max-width: 900px
- **Tablet/Desktop**: max-width: 1110px
