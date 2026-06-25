# Professional Developer Portfolio

A modern personal portfolio website built with HTML, CSS, and JavaScript. The site features a polished landing experience, animated sections, a custom cursor, project previews, and interactive UI details.

## Overview

This portfolio project showcases the work and skills of a developer using a minimal yet elegant design. It includes:

- Animated hero section with GSAP scroll reveal effects
- Custom cursor interaction for desktop users
- Loader animation with progress counter
- Project listing with hover preview and external links
- Contact section with a message form
- GitHub-style contribution activity mockup
- Responsive mobile navigation menu

## Technologies

- HTML
- CSS
- JavaScript
- Tailwind CSS CDN (utility support)

## Project Structure

- `index.html` — main portfolio page markup
- `style.css` — project styling and responsive layout rules
- `script.js` — interactive behaviors, animations, and data fetching
- `images/` — project image assets used for previews

## Usage

1. Open `index.html` in a browser.
2. Alternatively, run a local static server if you prefer:

```bash
# using Python 3
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## Notes

- The site uses a custom cursor on desktop screens and hides it on mobile devices.
- The GitHub contributions grid is generated randomly for a stylized activity display.
- The contact form currently shows a success message locally and does not send real emails.

## Customization

To personalize the portfolio:

- Update the text content in `index.html`
- Change the accent colors in `style.css`
- Swap project links and image references in the projects section
- Update the loader and hero branding to match your name

## License

This project is provided as-is for personal portfolio use.