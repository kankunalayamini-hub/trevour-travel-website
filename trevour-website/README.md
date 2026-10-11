# Trevour – Travel Planning Website

Trevour is a responsive, single-page travel planning website. Visitors can explore top destinations (Taj Mahal, Lotus Temple, Buddha Statue, Tea Plantations, Buckingham Palace, London Eye), read about each place, and plan a trip using a simple form.

## Features
- Fully responsive: laptop, tablet and mobile (collapsible navbar on small screens)
- Destination cards with a hover caption over the image
- Detail page for every destination, all inside one `index.html` (no page reloads)
- "Plan Your Trip" form with validation: shows a red *"Please enter the details"* message when fields are empty
- "Why choose Trevour?" feature cards and a clean about section

## Tech Stack
HTML5 · CSS3 · Bootstrap 5.3 (CDN) · Vanilla JavaScript

## Project Structure
```
├── index.html     # all pages/sections
├── index.css      # all styles (responsive)
├── assets/        # all images
└── README.md
```

## Run Locally
Open `index.html` in a browser (internet is needed for Bootstrap and Google Fonts CDN).

## Deploy
Static site, no build step. Import the repo in Vercel with **Framework Preset: Other** and leave Build/Output settings empty.
