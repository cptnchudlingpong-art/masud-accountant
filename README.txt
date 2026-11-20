MASUD RANA - PORTFOLIO (GitHub + Cloudflare Pages)
==================================================

FILES (plain HTML + CSS + JavaScript, no build step, no framework)
  index.html          Page structure and all text (Home, Resume, Works, Contact).
  css/style.css       All design.
  js/config.js        ONE setting: your Web3Forms access key (contact form).
  js/main.js          Page switching, preloader, cursor dot, card tilt/glow,
                      scroll reveal, contact form.
  images/portrait.jpg Your photo.
  favicon.* , apple-touch-icon.png, icon-192.png, icon-512.png, site.webmanifest
                      Browser-tab icon.
  Fonts load from Google Fonts.

STEP 1 - CONTACT FORM TO YOUR EMAIL (free)
  1. Go to https://web3forms.com and create an access key with
     masud905868@gmail.com. The key is emailed to you.
  2. Open js/config.js and replace PASTE_YOUR_ACCESS_KEY_HERE with the key.
  3. Messages from the form then arrive in your inbox. Check Spam the first time.
  Until the key is added, the form falls back to opening the visitor's email app.

STEP 2 - PUT THE FILES ON GITHUB
  1. Create a free account at https://github.com
  2. New repository (name e.g. masud-portfolio, Public).
  3. Add file -> Upload files -> drag the CONTENTS of this folder
     (index.html, css, js, images, favicon files...) -> Commit changes.
     index.html must be at the top level of the repository.

STEP 3 - PUBLISH ON CLOUDFLARE PAGES (free)
  1. Create a free account at https://dash.cloudflare.com
  2. Workers & Pages -> Pages -> Connect to Git -> choose your GitHub repository.
  3. Production branch: main. Build command: leave empty (or exit 0).
     Build output directory: leave empty or / (the repository root).
  4. Save and Deploy. You get a link like your-project.pages.dev.

UPDATING LATER
  Edit or upload files on GitHub and commit. Cloudflare redeploys by itself.
