
# JourneyTrails Landing Page Specification
## Project Type: Marketing Website / Landing Page (No booking system)

This document is for AI code generation (Claude Code compatible).

---

## 1. PROJECT SUMMARY
JourneyTrails will be a modern travel **landing page website** that showcases tour packages and destinations.
It is NOT a booking engine or CRM.

Goal:
- Beautiful UI better than GT Holidays
- Showcase packages
- Blog-style tour pages
- WhatsApp enquiry as primary CTA

---

## 2. TECH STACK
- Laravel (latest)
- Blade + TailwindCSS
- Alpine.js
- Minimal database (optional JSON or DB)
- No admin panel required initially (can add later)

---

## 3. CORE FEATURES

### 3.1 Homepage
- Hero section
- Featured packages
- Popular destinations
- Testimonials
- CTA sections
- Floating WhatsApp button
- Smooth animations
- Mobile-first design

---

### 3.2 Packages Page
URL: /packages

- Grid layout
- Filters:
  - Destination
  - Budget
  - Duration
- Each package card:
  - Image
  - Title
  - Price
  - Duration
  - “View Details”

---

### 3.3 Package Detail Page
URL: /packages/{slug}

Sections:
- Image gallery
- Overview
- Itinerary
- Inclusions
- Price
- Sticky WhatsApp button

WhatsApp message format:
Hello, I'm interested in the package:
{Package Title}

---

### 3.4 Blog Style Tours
Packages should also appear like blog posts.

URL: /tours/{slug}

---

### 3.5 About Page
- Company info
- Mission
- Contact

---

### 3.6 Contact
No forms required.
Primary contact = WhatsApp.

---

## 4. WHATSAPP INTEGRATION (KEY FEATURE)

### Floating button
Visible on all pages.

### Package CTA
Button: “Enquire on WhatsApp”

Link format:
https://wa.me/{number}?text={encoded_message}

Message includes:
- Package name
- Page URL

---

## 5. UI DESIGN REQUIREMENTS
- Modern travel UI
- Large imagery
- Smooth transitions
- Fast load
- Clean typography
- Better UX than GTHolidays

Colors:
Primary: Teal/Blue
Accent: Orange

Fonts:
- Poppins
- Inter

---

## 6. PERFORMANCE
- Lazy load images
- Optimized assets
- SEO friendly
- Sitemap

---

## 7. DELIVERABLE
Generate Laravel project named:

journeytrails-landing

Include:
- Routes
- Blade templates
- Tailwind design
- Package pages
- WhatsApp integration
- Responsive UI

No booking system.
No payment gateway.
No CRM.

Focus: UI + package showcase + WhatsApp enquiries.
