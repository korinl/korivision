# KoriVision

KoriVision is the personal professional website of Korin Lifshits, Senior Computer Vision / AI Engineer.

The site is a static GitHub Pages portfolio for `korivision.com`, built with plain HTML and CSS only. It presents a serious, public-safe overview of Korin's work across computer vision, AI, 3D vision, tracking, ReID, calibration, model training, and real-world perception systems.

## Files

- `index.html` — page content, metadata, navigation, and sections.
- `styles.css` — responsive dark visual system, layout, cards, and mobile styling.
- `CNAME` — custom GitHub Pages domain configuration for `korivision.com`.

## Local preview

Open `index.html` directly in a browser, or run a small static server from the repository root:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Deploying with GitHub Pages

1. Push these files to the repository's default branch.
2. In GitHub, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the default branch and repository root (`/`).
5. Save the settings.
6. Confirm the custom domain is set to:

```text
korivision.com
```

GitHub Pages will use the `CNAME` file to keep the custom domain attached to the site.

## Editing the site

- Update text and links in `index.html`.
- Update colors, spacing, and responsive layout in `styles.css`.
- Keep the site public-safe: do not add confidential employer details, proprietary architectures, customer names, internal datasets, screenshots, logs, sensitive operational details, or unpublished performance numbers.

## Contact links

The current contact links are intentionally conservative placeholders. Replace them in `index.html` with Korin's preferred LinkedIn URL, GitHub profile, email address, and resume URL when ready.
