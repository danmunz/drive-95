# I-95 Stop Guide

A no-build, mobile-first static page for a northbound Jacksonville, FL → Alexandria, VA I-95 drive.

## Publish on GitHub Pages

1. Create a GitHub repository and put these files on its default branch.
2. In **Settings → Pages**, choose **Deploy from a branch**, then select the default branch and `/ (root)`.
3. GitHub will publish the page at `https://<account>.github.io/<repository>/`.

The page works without a map or location API key. It asks for browser location only after the reader taps **Use my location**, then keeps following it so distances stay current; coordinates never leave the phone. The **Whole route** view is a drawing built into the page, so it needs no map tiles or network (the only outside request is the Overpass font from Google Fonts). Dots show approximate stop areas; tap one for that stop. Each **Directions** button opens the destination in Google Maps, which supplies the real-time routing and business-hours check. `index.previous.html` is the earlier version of the page.
