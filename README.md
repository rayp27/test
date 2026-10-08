# Safety Monthly September 2025 — Vercel Presentation

This static website reproduces the visual appearance of the supplied **24-slide PowerPoint**. Slides are losslessly encoded WebP images at 2560 × 1440 pixels (16:9), with a gentle 420 ms fade transition added between them.

## Presenting

- **Right arrow / Space / Page Down** — next slide
- **Left arrow / Backspace / Page Up** — previous slide
- **Home / End** — first / last slide
- **F** — toggle fullscreen
- **Click slide** — next slide
- **Swipe sideways** on a touchscreen — change slides
- **Slide counter** — open thumbnail chooser

The original PowerPoint had no built-in slide transitions or object animations. Existing slide visuals are preserved as rendered image snapshots; individual text boxes, charts, and photos cannot be edited separately within the website.

## Deploy on Vercel via GitHub

1. Extract this ZIP and keep `index.html` and `slides/` together.
2. Create a new GitHub repository and upload **the contents of the extracted folder** (not the ZIP itself).
3. Visit https://vercel.com/new and choose **Import Git Repository**.
4. Pick the repository. If requested, set **Framework Preset: Other**; leave Build Command empty and Output Directory at the project root (default).
5. Click **Deploy**. Vercel will give you a `.vercel.app` address.

This is an ordinary static website; no `npm install`, server, or framework build is required.

## Run on your PC before uploading

Double-click `index.html` to try it locally in a browser. Or, in this folder run:

```sh
python -m http.server 8080
```

Then visit http://localhost:8080.

## Privacy and licensing

Vercel-hosted websites are generally public by default. Do **not** publish internal safety data without permission. Vercel offers deployment protection; see https://vercel.com/docs/deployment-protection. Also, Vercel's free Hobby plan is restricted to personal, non-commercial use. A corporate presentation may require a paid plan; check https://vercel.com/docs/plans/hobby.
