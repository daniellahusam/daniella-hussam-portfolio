DANIELLA HUSSAM — ARTIST PORTFOLIO
==================================

This is a responsive, multi-page static website starter.

PAGES
-----
index.html                 Home
selected-works.html        Finished / selected artworks
studies.html               Studies & Explorations
ceramics.html              Ceramics & Clay
installations.html         Installation & Spatial Work
about.html                 Biography and exhibition history
contact.html               Contact and external links

BEFORE PUBLISHING
-----------------
1. Replace the coloured artwork placeholders with photographs of your own work.
2. Replace the portrait placeholder on about.html with a professional portrait.
3. Add your professional email address on contact.html (replace YOUR-EMAIL@example.com).
4. Check the About page exhibition details, titles and dates. They are starter copy and should be verified.
5. Update artwork titles, media, dimensions and years. The three example titles are based on works previously discussed.
6. Add image alt text when you insert your photographs.

HOW TO ADD YOUR ARTWORK
-----------------------
Create image files in assets/images/, for example:
  fool.jpg
  barbies-wanderlust.jpg
  reverie-red-poppies.jpg
  artist-portrait.jpg

In the HTML, replace a placeholder <div class="visual"> with:
  <img src="assets/images/fool.jpg" alt="The Fool, mixed media artwork by Daniella Hussam">

For the large homepage image, replace:
  <div class="art-placeholder">...</div>
with an <img> element using a class such as:
  <img class="hero-image" src="assets/images/featured-work.jpg" alt="...">
Then add .hero-image { width:100%; height:100%; object-fit:cover; } to the stylesheet.

LOCAL PREVIEW
-------------
Open index.html in a web browser. For best results, preview using a simple local server or upload the folder to a hosting service.

FREE PUBLISHING OPTION: NETLIFY DROP
------------------------------------
1. Visit https://app.netlify.com/drop
2. Sign in or create a free account.
3. Drag the entire folder (or a ZIP extracted to a folder) onto the drop area.
4. Netlify will publish it and provide a free *.netlify.app address.
5. You can change the site name in the Netlify site settings.
6. Keep the folder as your master copy. When you update it, deploy the updated folder again.

ALTERNATIVE: GITHUB PAGES
-------------------------
1. Create a GitHub account at https://github.com/
2. Create a new public repository, e.g. daniella-hussam-portfolio.
3. Upload all files and folders from this package to the repository root.
4. Open Settings > Pages.
5. Under Build and deployment, choose Deploy from a branch.
6. Select main and /(root), then Save.
7. GitHub will provide a free address similar to:
   https://YOUR-USERNAME.github.io/daniella-hussam-portfolio/

NOTES
-----
- No paid domain is required.
- Google Fonts load from the internet; if unavailable, the site falls back to system fonts.
- Contact form functionality is not included; the email link opens the visitor's email app.
- The site is a starter template, not yet populated with your actual artwork photographs.
