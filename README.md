# Lohdipphotograph Portfolio

A simple static portfolio website for Lohdipphotograph with a dynamic hero slideshow, responsive navigation, and a modern dark/light theme.

## Project Structure

- `index.html` — main page structure
- `style.css` — site styling and responsive layout
- `script.js` — theme toggle, mobile menu, hero slideshow, and reveal animations
- `Assets/` — images and visual assets

## Run locally

Open `index.html` directly in a browser, or serve the folder with a local web server for the best preview.

### Using a simple local server

If you have Python installed:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deploy

This site is a static website, so it can be deployed to any static host.

### Recommended options

- **GitHub Pages**
- **Netlify**
- **Vercel**
- **Firebase Hosting**

### Notes for deployment

- Keep the `Assets/` folder and all referenced files in the same root directory.
- If you deploy from a subfolder, update asset paths if needed.
- No build step is required.

## Features

- Responsive navigation
- Dynamic hero image transition
- Dynamic hero text updates
- Theme toggle (dark/light)
- Mobile menu
- Portfolio filtering
- Contact form demo interaction

## Troubleshooting

- If images do not load, confirm the `Assets/` folder is included in the deployment.
- If the hero slideshow is not updating, make sure `script.js` is loaded after the HTML.

## Optional next steps

- Add a real contact form backend
- Connect analytics
- Replace placeholder text and links with your real branding
