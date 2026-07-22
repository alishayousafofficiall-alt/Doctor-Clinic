# Dr. Sajida — Clinic Landing Page

A professional, animated landing page for a family & internal medicine clinic, built with **React**, **Vite**, and **Tailwind CSS**.

## Overview

This project gives an independent physician a modern, trustworthy online presence — showcasing credentials, services, and patient approach, with a fully functional appointment booking form.

## Features

- **Custom design system** — sage green / navy / ochre palette with Fraunces (display), Work Sans (body), and IBM Plex Mono (data/labels) typography
- **Signature animation** — an infinitely scrolling ECG/pulse-line strip tying into the medical theme
- **Scroll-reveal animations** — sections fade and rise into view on scroll (respects `prefers-reduced-motion`)
- **Animated stat counters** — patient numbers, years in practice, and consultation stats count up when scrolled into view
- **Real imagery** — free-license doctor and clinic photography (Unsplash / Pexels)
- **Functional booking form** — client-side validated appointment request form with a confirmation state
- **Fully responsive** — mobile nav, adaptive grids, and touch-friendly layout down to small screens

## Tech Stack

- React 18
- Vite 5
- Tailwind CSS 3

## Project Structure

```
src/
  components/
    Navbar.jsx        # Sticky nav with mobile menu
    Hero.jsx           # Hero section with floating trust cards
    PulseStrip.jsx      # Animated ECG scroll strip
    Vitals.jsx           # Animated stat counters
    About.jsx             # Doctor bio & credentials
    Services.jsx           # Services grid
    Approach.jsx             # Philosophy / approach feature section
    Testimonials.jsx           # Patient testimonials
    Booking.jsx                 # Appointment booking form
    Footer.jsx                   # Footer with contact info
    Reveal.jsx                    # Reusable scroll-reveal wrapper
  App.jsx        # Composes all sections
  main.jsx        # React entry point
  index.css        # Tailwind directives + custom utilities
```

## Getting Started

```bash
# install dependencies
npm install

# start the dev server
npm run dev

# build for production
npm run build

# preview the production build
npm run preview
```
