# I-95 Stop Guide

A no-build, mobile-first static page for a northbound Jacksonville, FL → Alexandria, VA I-95 drive.

## Publish on GitHub Pages

1. Create a GitHub repository and put these files on its default branch.
2. In **Settings → Pages**, choose **Deploy from a branch**, then select the default branch and `/ (root)`.
3. GitHub will publish the page at `https://<account>.github.io/<repository>/`.

The page works without a map or location API key. It requests browser location only after the reader taps **Use my location**, keeps coordinates in the page session, and uses them to put the listed northbound stop clusters in route order. The optional map uses Leaflet and OpenStreetMap tiles, requiring an internet connection; tile requests reveal the displayed map area to the tile provider. Markers represent approximate stop areas, not exact entrances. Each **Directions** button opens the destination in Google Maps, which supplies the real-time routing and business-hours check.
