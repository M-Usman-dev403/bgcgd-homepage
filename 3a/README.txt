BGCGD Homepage — Direction 3a (dark)
====================================

WHAT'S HERE
  index.html   The complete homepage. Open it in any browser.
  img/         All photography, video, logos and background artwork.

TO PUT IT ON GITHUB PAGES
  1. Unzip this folder.
  2. In your repo: Add file > Upload files.
  3. Drag the WHOLE folder in (keep index.html and img/ together).
  4. Commit to main, wait for the green check, then hard-refresh (Ctrl+Shift+R).

NOTES
  - The Find a Club map uses Leaflet + OpenStreetMap from a CDN, so that
    section needs an internet connection. Everything else works offline.
  - The hero film (img/sizzle.mp4) autoplays muted and loops. The pill
    button bottom-right of the hero pauses and resumes it.
  - Animations respect the visitor's "reduce motion" system setting.
  - Partner logos in "BGCGD Featured In" are the five real press logos.
    Send more logo files and they can be dropped into img/ and listed
    in the pressLogos array near the top of the <script> block.
  - Layout is responsive at 1100px and 680px breakpoints.

EDITING TEXT
  All copy lives in the DATA object at the top of the <script> block in
  index.html — nav labels, program names, club addresses, news headlines.
  Change it there and every section that uses it updates.
