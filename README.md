# Frie von Aigner Website

Static HTML website converted from WordPress.

## Local Development

To run the website locally, you can use any static file server:

### Option 1: Python (built-in)
```bash
python3 -m http.server 8000
```

Then visit: http://localhost:8000

### Option 2: Node.js http-server
```bash
npx http-server -p 8000
```

Then visit: http://localhost:8000

## Structure

- `index.html` - Home page
- `termine.html` - Termine (appointments) page
- `impressum.html` - Impressum (imprint) page
- `datenschutz.html` - Privacy policy page
- `assets/` - CSS, JavaScript, and images
