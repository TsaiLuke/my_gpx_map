# Route Map (GitHub Pages)


This repository hosts an interactive hiking map built with Folium.

## Quick publish
1. Upload all files in this folder to a new GitHub repository.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Set **Branch** to `main` and **Folder** to `/ (root)`, then **Save**.
5. Your site will be available at:
   `https://<your-account>.github.io/<your-repo>/`
   - The map is `index.html`, so the root URL should work directly.
   - You can also access `route_map_advanced_v4.html` explicitly if needed.

## Embed in Notion
Use `/embed` and paste the GitHub Pages URL (the one ending with `/` or `/index.html`).

## Notes
- The map uses public basemaps (OpenStreetMap and Carto Positron); no API key required.
- `.nojekyll` is included to bypass Jekyll processing.
