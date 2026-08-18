# NOIR GIRLS — Fashion E-Commerce Frontend

A clean, responsive, multi-page fashion e-commerce frontend built with **HTML5, CSS3, and Vanilla JavaScript**. NOIR GIRLS features a minimalist monochromatic design, dynamic product pages, client-side catalog filtering, an interactive product gallery, and a multi-step checkout experience.

## Overview

NOIR GIRLS is a frontend fashion storefront designed around a modern **light grey and black aesthetic**. The project focuses on responsive design, semantic HTML, accessibility, reusable styling, and client-side interactivity without relying on external frameworks.

## Features

### Semantic HTML & Accessibility

* Semantic HTML5 structure using:

  * `<header>`
  * `<nav>`
  * `<main>`
  * `<section>`
  * `<article>`
  * `<aside>`
  * `<footer>`
* Logical heading hierarchy using `<h1>` through `<h3>`
* Accessible form controls with native HTML validation
* Required fields and appropriate input types such as:

  * `email`
  * `tel`
* Accessible garment measurement table using:

  * `<details>`
  * `<table>`
  * `<caption>`
  * `<thead>`
  * `<tbody>`
  * `<th scope>`
* Screen-reader utility class (`.sr-only`)
* Functional skip navigation link
* Open Graph metadata for improved social sharing and SEO

### Responsive CSS Design

* Mobile-first responsive approach
* CSS Custom Properties for centralized color management
* Monochromatic color palette featuring:

  * Light Grey
  * Soft Grey
  * Jet Black
* CSS Grid for product and page layouts
* Flexbox for navigation and component alignment
* Responsive breakpoints for:

  * Desktop
  * Tablet
  * Mobile
* Smooth CSS transitions and hover interactions
* Interactive filter chips and product swatches

### JavaScript Interactivity

* Dynamic product detail routing using URL parameters
* Product information loaded dynamically on `product-detail.html`
* Interactive product image gallery
* Real-time thumbnail switching
* Catalog filtering by:

  * Category
  * Maximum price
  * Size
  * Stock availability
* In Stock / Sold Out filtering
* Multi-step checkout workflow
* Dynamic order summary
* Payment form validation

## Pages

| Page                  | Description                                                             |
| --------------------- | ----------------------------------------------------------------------- |
| `index.html`          | Landing page with hero section, featured products, and brand highlights |
| `products.html`       | Product catalog with filtering and product listings                     |
| `product-detail.html` | Dynamic product page with gallery, product information, and size guide  |
| `checkout.html`       | Multi-step checkout form with order summary and payment validation      |

## Project Structure

```text
fashion-ecommerce-frontend/
│
├── .gitignore
├── README.md
├── index.html
├── products.html
├── product-detail.html
├── checkout.html
├── styles.css
│
└── assets/
    └── images/
        ├── product1.jpg
        ├── product2.jpg
        ├── product3.jpg
        ├── product4.jpg
        ├── product5.jpg
        ├── product6.jpg
        ├── product7.jpg
        └── product8.jpg
```

## Technologies Used

* **HTML5** — Semantic page structure and accessible forms
* **CSS3** — Responsive layouts, Grid, Flexbox, animations, and custom properties
* **JavaScript (ES6+)** — Dynamic routing, filtering, gallery interactions, and form validation

## Dynamic Product Routing

The product detail page supports dynamic product information through URL parameters.

Example:

```text
product-detail.html?img=product1.jpg&title=Classic%20Black%20Dress&price=4999&stock=In%20Stock
```

JavaScript reads these parameters and dynamically displays the relevant product information.

## Catalog Filtering

The catalog includes a client-side filtering system that allows users to narrow products based on:

* Product category
* Maximum price
* Available sizes
* Stock status

Filtering occurs directly in the browser without requiring a backend server.

## Checkout Flow

The checkout page provides a structured multi-step purchasing experience including:

1. Customer information
2. Shipping details
3. Payment information
4. Order summary
5. Client-side form validation

## Design Philosophy

NOIR GIRLS follows a minimalist fashion aesthetic centered around:

* Clean layouts
* Generous whitespace
* Neutral colors
* Strong typography
* Product-focused presentation
* Responsive interactions

The interface is designed to provide a simple and modern shopping experience across desktop, tablet, and mobile devices.

## Accessibility

Accessibility was considered throughout the project with:

* Semantic HTML landmarks
* Keyboard-friendly native controls
* Skip navigation
* Screen-reader-only content
* Accessible tables
* Logical heading hierarchy
* Native form validation
* Proper form input types

## Getting Started

### 1. Clone the Repository

```bash
git clone <repository-url>
```

### 2. Navigate to the Project

```bash
cd fashion-ecommerce-frontend
```

### 3. Run the Project

Since this is a static frontend project, it can be opened directly in a browser.

Alternatively, use **VS Code Live Server** or another local development server.

## Browser Support

The project is designed for modern browsers that support:

* HTML5
* CSS3
* ES6 JavaScript
* CSS Grid
* CSS Flexbox
* URLSearchParams
* Native HTML form validation

## Future Improvements

Potential future enhancements include:

* Backend API integration
* Database-driven products
* User authentication
* Persistent shopping cart
* Wishlist functionality
* Real payment gateway integration
* Product search
* Order history
* Admin product management
* Persistent user accounts

## Project Purpose

NOIR GIRLS was developed to demonstrate practical frontend development skills including **semantic HTML, responsive CSS, JavaScript DOM manipulation, URL-based routing, client-side filtering, accessibility, and form validation**.
