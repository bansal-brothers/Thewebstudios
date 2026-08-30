# TheWebStudios — Agency Website

A professional, animated one-page website for **TheWebStudios**, a web design & development agency. Built with plain HTML, CSS, and JavaScript — no build step, no framework — so it can be uploaded to GitHub / GitHub Pages directly.

## Structure

```
thewebstudios/
├── index.html          # All page sections
├── css/style.css        # Design tokens, layout, animations
├── js/script.js         # Scroll reveals, nav, counters, WhatsApp form
├── assets/favicon.svg    # Placeholder favicon / logo mark
└── README.md
```

## Replacing the logo

The navbar and footer currently use a text mark (`TW` on a gradient square) as a placeholder logo. To use your real logo:

1. Add your logo file to `assets/` (e.g. `assets/logo.png`).
2. In `index.html`, find every `<span class="mark">TW</span>` and replace it with:
   ```html
   <img src="assets/logo.png" alt="TheWebStudios" class="mark-img" />
   ```

## Editing contact details

- WhatsApp number is set to `919897286952` everywhere (search-and-replace this in `index.html` if it changes).
- Email placeholder: `hello@thewebstudios.in` — update to your real email.

## Running locally

Just open `index.html` in a browser, or serve the folder with any static server:

```bash
npx serve .
```

## Deploying on GitHub Pages

1. Push this folder to a GitHub repository.
2. Go to **Settings → Pages**.
3. Set source to the `main` branch, root folder.
4. Your site will be live at `https://<username>.github.io/<repo-name>/`.
