# Engineering Interactive Tools

Standalone interactive engineering tools hosted with GitHub Pages. No build step, server, or package installation is required.

## Tools

- [Emergency Lighting Devices Simulator](./Emergency_Lighting_Devices_Simulator.html) — interactive emergency lighting power paths, UL 924 control/bypass behavior, and UL 1008 source transfer.

## Use locally

Open `index.html` in a browser, or open any simulator HTML file directly.

## GitHub Pages

In the repository's **Settings → Pages**, select **Deploy from a branch**, choose **main** and **/ (root)**, then save. The `.nojekyll` file keeps hosting as plain static files.

Changes pushed to `main` are automatically published by GitHub Pages.

## Add another tool

1. Add the standalone `.html` file to the repository root. Include any required local assets with relative paths.
2. Add a link/card in `index.html` and an entry to the tools list above.
3. Commit the changes to `main` and wait for the Pages deployment to finish.

Use relative links so tools work both locally and under the repository's GitHub Pages URL. Each HTML file also has its own directly shareable URL.
