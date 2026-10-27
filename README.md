# Micah’s personal website

A responsive, static personal website built with HTML and CSS. No build step, package installation, API keys, or backend services are required.

## Develop

From the repository root, run:

```sh
python3 -m http.server 3000 --bind 0.0.0.0
```

The server serves `index.html` and `styles.css` directly. Stop it with Ctrl+C.

## Customize

Edit `index.html` to add your biography, real projects, and contact details. The starter explicitly marks content that is still coming soon. Adjust colors and layout in `styles.css`. The design uses system fonts and has no external runtime dependencies. The contact form is deliberately disabled until a delivery service and server-side validation/spam protection are configured; its honeypot alone is not a complete spam defense. Add a verified LinkedIn URL and optional photo/CV when available. The barcode project omits the supplied approximate 77% reduction pending explicit publication confirmation.

## Validate

Start the server, then check that `/` and `/styles.css` return HTTP 200. Check navigation, keyboard focus, and the layout at narrow and wide viewport sizes after visual changes. There is no automated test suite or compilation step.

## Deploy

These static files can be hosted on GitHub Pages or any static hosting service. For GitHub Pages, choose **Deploy from a branch**, select `main`, and use the repository root in the repository’s Pages settings. Deployment must be enabled separately; pushing the code does not publish a live website.
