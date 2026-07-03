# HumanLens Landing Page

This is a static one-page landing page for HumanLens, a working brand focused on pilot-ready first-person POV human-work data collection for physical AI, robotics, embodied AI, and world model data companies.

The site is intentionally lightweight:

- `index.html` contains the page structure and copy.
- `styles.css` contains the full visual system and responsive layout.
- `script.js` contains only the mobile navigation toggle.
- `assets/images/` is reserved for future real image files.

No framework, package install, build step, external images, or client logos are required.

## Preview locally

Open `index.html` directly in a browser, or serve the folder with a small local static server.

From this folder, one simple option is:

```powershell
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Add images later

The page currently uses styled placeholder boxes. When real images are ready, add them to:

```text
assets/images/
```

Suggested filenames:

- `hero.jpg`
- `construction.jpg`
- `manufacturing.jpg`
- `warehouse-logistics.jpg`
- `nursing-training.jpg`
- `commercial-kitchen.jpg`

Then replace each placeholder block in `index.html` with an `<img>` tag. Comments in the HTML show where each image should go.

## Update contact email

The current contact email is:

```text
khalid@humanlens.xyz
```

To change it, search across `index.html` for `khalid@humanlens.xyz` and update each mailto link and visible email address.

## Deploy on GitHub Pages

After this local folder is connected to a GitHub repository, GitHub Pages can serve it directly from the root of the repository.

Suggested GitHub Pages settings:

- Source: Deploy from branch
- Branch: `main`
- Folder: `/root`

Because the site is plain HTML, CSS, and JavaScript, no build command is needed.

## Files to edit

- Edit content and links in `index.html`.
- Edit colors, spacing, typography, cards, and responsive behavior in `styles.css`.
- Edit mobile nav behavior in `script.js`.

## Notes

The page copy avoids naming target companies or implying customers, partners, signed contracts, or incorporation status. It is written for cold outreach and pilot discussions.
