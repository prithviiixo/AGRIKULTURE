# Agri KULTURE

A single-page agriculture marketplace prototype built as a demo web experience.

## Overview

`Agri KULTURE` is a farm-to-future marketplace concept for Indian agriculture. It is implemented as a self-contained HTML page with embedded CSS and JavaScript.

The web page includes:

- Landing hero section with mission messaging and CTA buttons
- Auth overlay with Login, Register, Guest access, OTP login, and Forgot Password flows
- Product marketplace section for buying fresh produce
- Seller section for farmers to list produce
- Pesticide marketplace and seller form with regulatory warnings
- Platform feature cards and footer
- Interactive quick view modal, cart float button, and toast notifications

## Key Features

- Role-based auth screens: Customer, Farmer, Admin
- Responsive mobile-friendly layout
- Product filters, search, and sorting for produce and pesticides
- Wishlist toggles for produce and pesticide items
- Local cart state with add-to-cart and buy now flows
- Demo login uses `localStorage` to persist a user session
- Quick view modal for product details
- Custom CSS theming with agricultural color palette

## Files

- `index (1).html` — main page containing HTML, CSS, and JavaScript

## Run Locally

1. Open `index (1).html` in your browser.
2. The page loads with a built-in loading screen.
3. Use the auth overlay to login, register, or continue as a guest.
4. Browse marketplace items, use filters/search, and interact with the demo cart.

## Notes

- This is a front-end prototype only. There is no backend or server required.
- User login and registration are simulated in the browser.
- Product images load from remote Unsplash URLs.
- The page is designed as a standalone `.html` demo and is ready to preview in any modern browser.

## Suggested Improvements

- Add a backend for real authentication and product persistence
- Implement actual checkout flow and payment integration
- Add real user role permissions for farmer and seller actions
- Improve form validation and error messages
- Convert to separate HTML/CSS/JS files for better maintainability

