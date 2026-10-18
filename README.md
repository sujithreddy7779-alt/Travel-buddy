# Travel Buddy

A trip planner. Enter where you're leaving from, where you're going, your dates and how you'll travel, and Travel Buddy lays out the trip as a stop-by-stop route: scenic spots, drives, restaurants, cafes, hotels and Airbnb areas, each with map and photo links. A plan change box updates the route, and a "Not sure where to go?" panel suggests places for a country or state.

This is a single static page (`index.html`) with no build step.

## Host it on GitHub Pages

1. Keep `index.html` in the root of this repository.
2. Open **Settings → Pages**.
3. Under **Source**, choose the `main` branch and the root folder, then save.
4. After a minute or two the site is live at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## What works today

The form, layout, photo background, glass styling and the map and photo links all work as plain static files. The AI parts (writing the plan, applying changes, suggesting places) need a small server function to call Claude, which is not connected yet. Until then the page shows an example Sedona plan.

Never put a Claude API key in this repository.
