# Case: Paris competitor map

Team: Brunch & Burn Rate. A fictional team. Rename it if you like.

## Business question
We plan to open a brunch and specialty coffee place in the 11th arrondissement of Paris. Who are our competitors, how do they position on price and experience, how big is their audience on social media, and where is the white space for us?

## The app
One page that shows 12 competitors on a map of Paris, with their positioning, their social media followers and their average menu price.

## Users
The founding team, preparing a meeting with an investor.

## Data
- data/competitors.js: 12 fictional competitors. The fields are explained in data/data-dictionary.md.
- data/our-concept.js: our own concept, shown as a star on the chart.

## Libraries allowed for this case
- MapLibre GL JS 5: https://unpkg.com/maplibre-gl@5/dist/maplibre-gl.js and https://unpkg.com/maplibre-gl@5/dist/maplibre-gl.css
- Map style: https://tiles.openfreemap.org/styles/positron. No API key.
- Never call tile.openstreetmap.org directly. Keep the map attribution visible.
- No other library. Draw charts in plain SVG.

## Human checks
- A human checks every figure before it is used outside the workshop.
- The AI Product Owner approves the insights before they are shared.

## Reuse this kit for another case
Rewrite this file with the same headings. Replace or delete the files in data/. Adapt the delivery cards in prompts/4-delivery.md. Keep .github/ and docs/ as they are. Ten ready ideas are in CASE-LIBRARY.md.
