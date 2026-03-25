# Portfolio Website

A stunning, fully responsive single-page portfolio website built with HTML5, CSS3, and Vanilla JavaScript.

## Features
- **Modern Design**: Refined dark theme with Deep Charcoal (`#0d1117`) background, Cream White (`#f5f0e8`) text, and Gold (`#c9a84c`) accents.
- **Typography**: Paired Google Fonts: *Playfair Display* for headings and *Inter* for body text.
- **Smooth Animations**: IntersectionObserver-based scroll reveals, custom CSS keyframes, and smooth scrolling.
- **Fully Responsive**: Mobile-first architecture adapting cleanly to all screen sizes.
- **Dynamic Elements**: 
  - Sticky navigation bar with ScrollSpy (active highlights on scroll).
  - Custom fullscreen lightbox for viewing certificates.
  - Animated preloader entry screen.
  - Toast notifications for the contact form submission.
- **No Dependencies**: 100% Vanilla JS and CSS (icons provided by Devicon & Boxicons).

## How to use
1. Customize `index.html` with your personal information.
2. Replace `assets/cv.pdf` with your actual resume document.
3. Update the images in `index.html` (currently using Unsplash placeholders).
4. Update the contact form logic in `js/main.js` to connect to a backend like Formspree or EmailJS.
5. Deploy to GitHub Pages, Netlify, Vercel, or any static host.

## File Structure
- `index.html`: Main HTML file containing all 8 sections (Hero, About, Skills, Projects, Certificates, Education, CV, Contact)
- `css/style.css`: All custom styling, including CSS variables, layout, interactions, and responsive media queries
- `js/main.js`: Scroll observing, lightbox logic, preloader timeout, Menu Toggle, and navigation logic
- `assets/cv.pdf`: Placeholder CV file

---
Designed & Built structurally according to modern web development best practices.
