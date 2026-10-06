# 🌍 FaTravel - European Travel & Destination Booking Website

A modern, responsive frontend web application for travel and tour bookings across Europe. Built using **HTML5**, **CSS3**, **Bootstrap 5**, and **Font Awesome**.

---

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Key Features](#-key-features)
- [Website Sections](#-website-sections)
- [Directory Structure](#-directory-structure)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Customization](#-customization)
- [License & Author](#-license--author)

---

## 📖 Project Overview

**FaTravel** is an elegant, mobile-friendly landing page created for travel agencies, tour operators, and wanderlust enthusiasts. The website showcases popular European destinations, travel packages, accommodations, and itinerary services, complemented by an interactive booking inquiry form and an eye-catching photo gallery.

---

## ✨ Key Features

- 📱 **Fully Responsive Layout**: Built with the **Bootstrap 5** grid system, ensuring a seamless browsing experience across smartphones, tablets, and desktop displays.
- 🎨 **Modern Visual Aesthetics**: Styled with clean typography ([Google Fonts Roboto](https://fonts.google.com/specimen/Roboto)), custom CSS animations, and vibrant accent colors.
- 📅 **Interactive Booking Section**: Includes a streamlined booking inquiry interface with destination inputs, traveler headcount, and arrival/departure date pickers.
- ⭐ **Curated Tour Packages**: Card-based showcase of prime European countries featuring star ratings, pricing, and package descriptions.
- 🖼️ **Photo Gallery Showcase**: High-resolution image grid highlighting scenic attractions and cultural landmarks.
- 🧭 **Intuitive Navigation**: Fixed navigation header featuring smooth anchor scrolling and a responsive mobile toggle menu.

---

## 🖥️ Website Sections

1. **Header & Navigation**:
   - Brand logo (`Travel`)
   - Quick navigation links (*Home*, *Book*, *Packages*, *Services*, *Gallery*, *About*)
   - Instant search bar with mobile drawer support
2. **Hero Section (`.home`)**:
   - Welcome banner introducing European travel destinations with a prominent **"Book Place"** Call-to-Action (CTA).
3. **Booking Form (`#book`)**:
   - Input fields: Destination (*Where To*), Number of guests (*How many*), Arrival date, Departure date, and Additional details.
4. **Tour Packages (`#packages`)**:
   - Featured destinations: United Kingdom, France, Italy, Germany, Spain, Switzerland, Norway, and more.
   - Highlights pricing, descriptive overviews, star ratings, and booking buttons.
5. **Services Section (`#services`)**:
   - Core value offerings: *Affordable Hotel Bookings*, *Food & Drinks Guide*, *Safety Guidelines*, and *Around The World Tours*.
6. **Gallery Section (`#gallery`)**:
   - Grid presentation of travel photography.
7. **About Us (`#about`)**:
   - Introduction to the travel agency's vision, history, and commitment to travelers.
8. **Footer**:
   - Social media connections (Twitter, Facebook, Instagram, YouTube, Pinterest), copyright notice, and quick links.

---

## 📁 Directory Structure

```plaintext
fatravel/
├── image/                    # Image assets (banners, package thumbnails, gallery photos)
│   ├── 1.jpg
│   ├── about.jpg
│   ├── back.jpg
│   ├── UK.jpg
│   ├── france.jpg
│   ├── italy.jpg
│   ├── germany.jpg
│   └── ...
├── index.html                # Main semantic HTML5 webpage structure
├── style.css                 # Custom stylesheet, layout adjustments, and animations
├── LICENSE                   # Project license
└── README.md                 # Project documentation
```

---

## 🛠️ Tech Stack

- **Markup**: [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML)
- **Styling**: [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS)
- **CSS Framework**: [Bootstrap 5.0.2](https://getbootstrap.com/)
- **Icons**: [Font Awesome 6.4.0](https://fontawesome.com/)
- **Typography**: [Google Fonts (Roboto)](https://fonts.google.com/specimen/Roboto)

---

## 🚀 Getting Started

Since this is a lightweight frontend web project with no backend build tools required, you can view it immediately using any modern browser:

### Option 1: Direct File Opening
1. Clone or download this repository:
   ```bash
   git clone https://github.com/shafafariha/fatravel.git
   cd fatravel
   ```
2. Double-click `index.html` or open it with your preferred browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).

### Option 2: Live Server (VS Code Extension)
1. Open the project folder in **Visual Studio Code**.
2. Right-click on `index.html` and select **"Open with Live Server"**.

### Option 3: Python Local HTTP Server
Run a quick local web server from your terminal:
```bash
# Python 3
python -m http.server 8000
```
Then visit `http://localhost:8000` in your web browser.

---

## 🎨 Customization

- **Change Destinations**: Modify the package cards in `index.html` under `<section class="packages">` and update the corresponding images in the `image/` directory.
- **Adjust Colors & Fonts**: Customize color variables, transitions, and hover effects directly in `style.css`.
- **Connect Form Backend**: Connect the form in `<section class="book">` to a backend API, EmailJS, or Formspree to collect live user inquiries.

---

## 📄 License & Author

- **Author**: [@shafafariha](https://github.com/shafafariha)
- **License**: This project is licensed under the [MIT License](LICENSE).