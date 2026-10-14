# Motiveoflife

A mobile-first, dependency-free static website for the Motiveoflife brand: mood-based inspiration, original short reflections, share/copy controls, locally saved favourites, global perspective themes, T-shirt concept previews, and LinkedIn post drafts.

## Run locally
Open `index.html` in a modern browser. No build command, package manager, database, or paid API is required.

## Deploy on GitHub Pages
1. Open this repository → **Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then Save.
4. Wait for the Pages deployment workflow to finish. The site should be available at `https://tanujkapila.github.io/motiveoflife/`.

## MVP boundaries
- Saved quotes and merch poll votes use this browser's localStorage only; they are not sent to a server.
- Global perspective sections are evergreen editorial prompts, not live news reporting. Verify current stories and cite sources before publishing.
- T-shirts are visual concepts only. No checkout, inventory, fulfilment or payment processing is configured.
- No analytics, tracking pixels or third-party runtime libraries are included.

## Suggested next steps
1. Add reviewed, dated story entries with source links.
2. Validate merch concepts with audience polls.
3. If needed, add a privacy-conscious analytics setup and a real mailing-list provider.
4. Add print-on-demand checkout only after pricing, delivery, tax, returns and privacy details are ready.
