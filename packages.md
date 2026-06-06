# Dastoor Makeovers - Salon Packages

This document outlines the available packages and the design system applied to their respective printable HTML brochures.

## Package 1: The Royal Glow Package
*Head-to-toe luxury · 30+ sessions · 12 treatments*

### Services Included

| Service | Quantity | Price |
| :--- | :--- | :--- |
| Hydra Boost Facial | 1 session | ₹2,500 |
| Brightening / AHA+BHA Facial | 1 session | ₹1,500 |
| Glass Glo Cleanup | 2 sessions | ₹1,000 |
| Hairspa Loreal | 2 sessions | ₹2,400 |
| Pedicure | 2 sessions | ₹1,400 |
| Manicure | 2 sessions | ₹800 |
| Face D-Tan / Bleach | 2 sessions | ₹1,000 |
| Full Leg + Hand + Underarm Wax | 2 sessions | ₹2,400 |
| Threading | 6 sessions | ₹600 |
| Head Wash + Blowdry | 6 sessions | ₹2,100 |
| Head Massage | 3 sessions | ₹900 |
| Hand D-Tan | 1 session | ₹400 |

### Pricing & Value
- **Package Value**: ₹17,000
- **You Save**: ₹7,001 (41% OFF)
- **Final Offer Price**: **₹9,999 Only**

### Terms & Conditions
- ◷ Valid for 6 months from the date of package purchase.
- Sessions can be availed individually or combined as per your convenience.

---

## Design System & Implementation Details

The printable package brochure (`package1.html`) is designed with a **Premium Salon Aesthetic** emphasizing luxury, clarity, and printing readiness.

### 1. Typography
- **Headings & Accents**: `Cinzel` (Google Fonts) - A serif font that evokes classic elegance and luxury, used for the main package title, pricing figures, and taglines.
- **Body & Services**: `Montserrat` (Google Fonts) - A clean, highly legible sans-serif font used for service names, terms, and general body text.

### 2. Color Palette
- **Primary Color (`#2c2c2c`)**: Deep Charcoal - Used for main text and structure, providing a softer, more elegant contrast than pure black.
- **Secondary Color (`#d4af37`)**: Soft Gold - Used for highlights, borders, and accents to establish the premium feel.
- **Background (`#faf9f6`)**: Cream / Off-White - A subtle warm background avoiding the starkness of pure white on screens.
- **Highlight Background (`#1a1a1a`)**: A dark charcoal-to-black gradient used for the pricing value block to draw the eye immediately.

### 3. Layout & Structure
- **No Dependencies**: Built entirely with Vanilla HTML and CSS. No jQuery, Bootstrap, or Tailwind to keep the file lightweight and self-contained.
- **Menu-Style Listing**: Services are listed using a flexbox layout with dynamic dotted lines (`....`) connecting the service name to the price, resembling an upscale restaurant or spa menu.
- **Value Emphasis**: The original value, savings, and final price are grouped into a dark, gradient-backed card at the bottom to maximize conversion focus.
- **Decorative Borders**: A double border effect surrounds the page to give it a certificate/brochure vibe.

### 4. Print-to-PDF Capabilities
- **Print Media Queries (`@media print`)**: 
  - Overrides the container shadow and max-width to allow the content to naturally fill an A4 page without being cut off.
  - Forces background color rendering (`-webkit-print-color-adjust: exact`) so the cream background and dark value boxes are preserved in the final PDF.
  - Ensures the document seamlessly scales to standard printer paper sizes without unnecessary margins.