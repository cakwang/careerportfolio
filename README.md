# Curtis Wang Professional Portfolio

This is a professional portfolio website with a persistent vertical navigation bar and iframe content display.

## Structure

The portfolio has the following structure:

- `index.html` - Main entry point with navigation sidebar and content iframe
- `styles.css` - Main stylesheet for the portfolio
- `script.js` - JavaScript for handling navigation and content loading
- Main content pages:
  - `about.html` - About page
  - `ideas.html` - Ideas page
  - `cv.html` - Curriculum Vitae page
- `/content/` directory - Contains individual project pages:
  - Learning Design projects
  - Research projects
  - Creative projects

## Features

- 280px wide persistent vertical navigation bar
- Responsive design
- Clean, professional aesthetic with primary color #f2f2f4
- Organized sections for different domains of work
- Iframe-based content display for seamless navigation

## How to Use

1. Open `index.html` in a web browser to view the portfolio
2. Navigate through sections using the sidebar
3. Content will load in the main iframe area

## Customization

### Adding New Projects

1. Create a new HTML file in the `/content/` directory with a descriptive name
2. Use the existing project pages as templates
3. Add a link to the new project in `index.html` under the appropriate section

### Modifying Navigation

Edit the sidebar in `index.html` to add, remove, or modify navigation items.

### Styling Changes

The main styles are in `styles.css`. The primary color (#f2f2f4) and other styling elements can be modified there.

## Local Development

To test locally, simply open the `index.html` file in a web browser. No server is required for basic functionality.

For more advanced development or to preview changes, you can use a local server:

```
# Using Python (if installed)
python -m http.server

# Or using Node.js (if installed)
npx serve
```

Then open `http://localhost:8000` (or the port specified by your server) in a web browser.
