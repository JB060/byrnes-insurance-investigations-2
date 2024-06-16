# Byrne Insurance Investigations Website

Welcome to the Byrne Insurance Investigations website repository. This project includes three main web pages: Home, Booking, and Testimonials. The website serves as a platform for clients to learn about our services, book investigations, and read testimonials.

## Table of Contents

- [Project Overview](#project-overview)
- [Pages and Features](#pages-and-features)
- [Getting Started](#getting-started)
- [Directory Structure](#directory-structure)
- [Contributing](#contributing)
- [License](#license)

## Project Overview

The Byrne Insurance Investigations website provides information on our insurance investigation services. The website is designed to be responsive, user-friendly, and informative, featuring essential sections and forms to facilitate client interactions.

## Pages and Features

### 1. Home Page (`index.html`)

**Description:**
The home page introduces Byrne Insurance Investigations, highlighting our expertise in motor, public, and employer's liability claims.

**Key Features:**
- Welcome message with a brief description of our services.
- Centralized heading with a horizontal line for visual separation.

**HTML Structure:**
- `<header>`: Logo and navigation menu.
- `<main>`: Introduction section with text content.
- `<footer>`: Contact information and social media links.

### 2. Booking Page (`booking.html`)

**Description:**
The booking page allows clients to schedule an investigation by filling out a form with their details and preferences.

**Key Features:**
- Centralized heading with a horizontal line for visual separation.
- Form for booking an investigation, including fields for name, email, phone, investigation type, preferred date, and additional details.
- Form submission via POST method to a designated URL.

**HTML Structure:**
- `<header>`: Logo and navigation menu.
- `<main>`: Booking form.
- `<footer>`: Contact information and social media links.

### 3. Testimonials Page (`testimonials.html`)

**Description:**
The testimonials page showcases feedback from our clients, demonstrating the value and effectiveness of our services.

**Key Features:**
- Centralized heading with a horizontal line for visual separation.
- Client testimonials displayed with names and feedback messages.

**HTML Structure:**
- `<header>`: Logo and navigation menu.
- `<main>`: Testimonials section.
- `<footer>`: Contact information and social media links.

### Directory structure:**
byrne-investigations/
├── assets/
│   ├── CSS/
│   │   └── styles.css      # Custom CSS styles
│   └── images/
│       └── fenderbender.jpeg  # Image used in the booking page
├── index.html                # Home page
├── booking.html              # Booking page
├── testimonials.html         # Testimonials page
└── README.md                 # Project README

## contributing 
We welcome contributions to improve the website. Please follow these steps:

1. Fork the repository.
2. Create a new branch (git checkout -b feature-branch).
3. Make your changes.
4. Commit your changes (git commit -m 'Add some feature').
5. Push to the branch (git push origin feature-branch).
6. Open a Pull Request.

### bugs squashed 
Navigation Menu Inconsistencies:
- Bug: The active link style wasn't properly applied across different pages.
- Fix: Ensured the class="active" was correctly set for the current page in each navigation menu.

Responsive Design Issues:
- Bug: Pages had layout issues on smaller screens, causing elements to overlap or be misaligned.
- Fix: Added media queries and adjusted CSS to improve responsiveness and ensure elements are properly aligned on various devices.

Social Media Icons Misalignment:
- Bug: Social media icons were not aligned properly or scaled differently across pages.
- Fix: Standardized the size and alignment of icons using consistent CSS rules.

## index.html (Home Page) Bugs

Header Misalignment:
- Bug: The header content wasn't centered properly.
- Fix: Adjusted CSS to align the header and ensure it appears centered on the page.

Welcome Message Not Readable:
- Bug: The welcome message overlapped with the background, making it difficult to read.
- Fix: Modified text color and added a background overlay to enhance readability.

Missing Horizontal Line:
- Bug: As seen on other pages, the horizontal line for visual separation was missing.
- Fix: A horizontal line element was added to match the design consistency of other pages.

## booking.html (Booking Page) Bugs

Form Submission Issue:
- Bug: The form wasn’t submitting correctly due to incorrect form action URL or method.
- Fix: Updated the form action to point to https://formdump.codeinstitute.net and ensured the method was set to POST.

Form Fields Validation:
- Bug: Form validation wasn’t functioning correctly, allowing empty fields to be submitted.
- Fix: Added HTML5 required attributes to all necessary input fields to enforce proper form validation.

Image Misalignment:
- Bug: The image beside the booking form wasn’t aligned properly or scaled correctly.
- Fix: Adjusted CSS properties to ensure the image aligns properly with the booking form and scales well on different devices.

Date Field Format:
- Bug: Date input field wasn’t displaying in a consistent format across different browsers.
- Fix: Ensured the date input type is supported by modern browsers and provided a placeholder for non-supported browsers.

## testimonials.html (Testimonials Page) Bugs

Testimonial Text Overflow:
- Bug: Long testimonial texts overflowed their containers.
- Fix: Implemented CSS rules to handle text overflow and ensured proper wrapping and truncation where necessary.

Testimonial Alignment:
- Bug: Testimonials were not evenly spaced or aligned.
- Fix: Used flexbox and CSS grid to evenly space and align testimonials for a cleaner layout.

Missing Horizontal Line:

- Bug: The page lacked a horizontal line separator for visual separation, like on other pages.
- Fix: Added a horizontal line to maintain consistent visual separation across all pages.

## Additional Minor Bugs

Missing alt Attributes:
- Bug: Several images across the pages lacked alt attributes.
- Fix: Added appropriate alt attributes to all images to improve accessibility and SEO.

Inconsistent Button Styles:
- Bug: Buttons had inconsistent styling across different pages.
- Fix: Standardized button styles in the CSS to ensure a consistent look and feel.

Broken Social Media Links:
- Bug: Social media links directed to incorrect or non-existent pages.
- Fix: Updated the URLs to point to the correct social media pages and ensured target="_blank" and rel="noopener" attributes were properly set.

Favicon Issues:
- Bug: Favicons were not appearing on all pages.
- Fix: Ensured favicon links were correctly included in the <head> section of each page.

By addressing these bugs, the website now offers a more consistent, responsive, and user-friendly experience across all pages.

## Getting Started

### Prerequisites

Ensure you have the following:
- A web browser (e.g., Chrome, Firefox, Edge).
- Basic understanding of HTML and CSS.

### Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/yourusername/byrne-investigations.git


