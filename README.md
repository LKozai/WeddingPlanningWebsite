# Wedding Planning Website

## Overview
This project is a multi-page wedding planning website built using fundamental JavaScript, HTML, and CSS principles. The site features a registration form with input validation, a navigation bar for seamless page transitions, and aesthetically pleasing UI design to create a professional and user-friendly experience.

## Features
- Multi-page website including Home, Pricing, Testimonials, Consultation (Reservation), Contact, and About pages.
- Responsive navigation bar for easy access to all sections.
- Consultation reservation form with client-side validation to ensure required fields are correctly completed before submission.
- Interactive testimonials section that dynamically displays testimonial text when clicking on corresponding photos.
- Automatic redirect to the homepage after submitting a reservation request.

## JavaScript Functionality
- **Form Validation:** Validates first name, last name, email format, and phone number on the reservation form to prevent incomplete or invalid submissions.
- **Testimonials Interaction:** Enables users to click testimonial images to reveal matching testimonial text.
- **Redirect:** After submitting the reservation form, users are automatically redirected to the homepage after a short delay.

## Project Structure

Wedding Planning Website
├── css
│   ├── about.css
│   ├── contact.css
│   ├── pricing.css
│   ├── reservation.css
│   ├── styles.css
│   ├── template.css
│   └── testimonials.css
├── images
│   ├── about
│   ├── pricing
│   ├── testimonials
│   ├── background-flowers.jpg
│   ├── contact.png
│   ├── phone.jpg
│   ├── service1.jpg
│   ├── service2.jpg
│   ├── service3.jpg
│   └── wedding_logo.png
├── js
│   ├── redirect.js
│   ├── reservation.js
│   └── testmonials.js
├── webpages
│   ├── about.html
│   ├── contact.html
│   ├── pricing.html
│   ├── reservation.html
│   ├── reserve.html
│   ├── testimonials.html
│   └── index.html
└── README.md

## How to Use
1. Clone or download the repository.
2. Open `index.html` in your web browser to start navigating the site.
3. Use the navigation bar to explore different sections including pricing, testimonials, consultation booking, contact, and about pages.
4. Fill out the consultation reservation form with valid details to submit a request.
5. View testimonials by clicking on the images in the Testimonials page.

## Technologies Used
- HTML
- CSS
- JavaScript (simple JS for interactivity and validation)

## Notes
- All styling is managed through separate CSS files.
- JavaScript enhances form validation and dynamic content toggling without reliance on external libraries except jQuery for the testimonials interaction.
- The project is designed for easy maintenance and extensibility.
