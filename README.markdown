# Parashar College Website

Welcome to the official website for Parashar College, built with HTML, CSS, and JavaScript. This static site is hosted on GitHub Pages and features a responsive design with a dynamic notices system.

## Features
- **Responsive Navbar**: Sticky navigation with a centered search bar, mobile-friendly with a toggle menu.
- **Hero Section**: Displays a college background image with a welcome message.
- **Admissions**: Includes an 'Enroll Now' button linking to a Google Form (placeholder link).
- **Events & Notices**: Dynamic notices loaded from `notices.json`, with hover effects and popups for details.
- **Programs, Facilities, and Gallery**: Showcase the college's offerings with responsive grids.

## Setup
1. Clone this repository to your local machine.
2. Ensure `index.html` and `notices.json` are in the root directory.
3. Uncomment the `fetch` code in `index.html` to load notices dynamically.
4. Host on GitHub Pages by pushing to a repository and enabling Pages in the settings.

## Updating Notices
- Edit `notices.json` to add or update notices.
- Format: `{"title": "Notice Title", "date": "Date", "details": "Full description"}`.
- Commit and push changes to GitHub to update the site.

## Notes
- Replace the placeholder Google Form link in the Admissions section with your actual link.
- Update the hero section's background image URL with an actual college photo if available.

## License
This project is for educational purposes and not licensed for commercial use.