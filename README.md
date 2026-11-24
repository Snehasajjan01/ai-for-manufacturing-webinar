# ai-for-manufacturing-webinar
Responsive landing page for "AI for Manufacturing: From Pilot to Production Floor", a live webinar on predictive maintenance, visual inspection and AI pilot planning. Built with plain HTML, CSS and JavaScript.
# AI for Manufacturing: Webinar Landing Page

A single-page, responsive landing page to promote a live webinar on how manufacturers can use AI to cut downtime, scrap and inspection time.

**Live demo:** https://<username>.github.io/ai-for-manufacturing-webinar/

## Webinar details (sample data)
- **Title:** AI for Manufacturing: From Pilot to Production Floor
- **Date:** Sat, 12 Dec 2026, 11:00 AM IST (90 minutes, live on Zoom)
- **Speakers:** Dr. Meera Iyer and Rohan Kulkarni (fictional)
- **Price:** ₹499 early-bird, 300 seats

## Features
- Hero section with live countdown and registration form
- Animated conveyor strip showing AI use cases (respects reduced-motion settings)
- Learning outcomes, timed agenda, speaker profiles, audience list and FAQ
- Light and dark mode support
- Mobile-friendly layout, keyboard-accessible, no frameworks or build step

## Tech stack
HTML5, CSS3 and vanilla JavaScript in a single `index.html` file. Fonts: Barlow Condensed and IBM Plex Sans (Google Fonts).

## Run locally
Download or clone the repo and open `index.html` in a browser.

## Deploy
Enable GitHub Pages: Settings → Pages → Deploy from branch → `main` / root.

## Customize
- Event date and countdown: edit the `Date.UTC(...)` line in the script at the bottom of `index.html`
- Copy, speakers and pricing: edit the text directly in the HTML
- Registration form: it currently only shows a confirmation message. Connect it to Formspree, Google Forms or your CRM to collect sign-ups.

## Note
All speakers, company names and figures are fictional sample content.
