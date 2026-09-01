# REVIVE website — static export

Eight plain HTML pages. No build step, no server-side code: any static web host serves this folder as-is.

## Files
  index.html              Home
  about.html              About the project
  work-packages.html      Work Packages
  training-mobility.html  Training & Mobility
  workshops-events.html   Workshops & Events (empty, ready for content)
  publications.html       Publications (empty, ready for content)
  consortium.html         Consortium
  contact.html            Contact
  styles.css              All styling (loads Barlow / Barlow Condensed from Google Fonts)
  assets/                 Images

## Recommended host: Netlify (free)
1. Go to app.netlify.com/drop
2. Drag this whole folder onto the page.
3. The site is live in about 30 seconds on a free HTTPS address, e.g. revive-project.netlify.app.
4. To use your own domain later: Site settings > Domain management > Add custom domain.

Alternative for long-term institutional hosting (MSCA requires the site stay up for years after the
project ends): GitHub Pages — create a repository, upload this folder, then Settings > Pages > deploy
from branch. Also free, no account expiry. Firebase Hosting works the same way via 'firebase deploy'.

Squarespace and Google Sites cannot host multi-page HTML like this — they only embed one page inside a
code block. If you must use one of those, ask for the flattened single-page version.

## Adding logos
Drop PNG or SVG files into assets/logos/ using exactly these names. Any file that is missing simply
leaves an empty framed box — nothing breaks.

  assets/logos/tud.png   — TU Delft
  assets/logos/hsu.png   — Helmut Schmidt University
  assets/logos/urtv.png   — University of Roma Tor Vergata
  assets/logos/uob.png   — University of Bristol
  assets/logos/ul.png   — University of Ljubljana
  assets/logos/sztaki.png   — HUN-REN SZTAKI
  assets/logos/zag.png   — ZAG
  assets/logos/shm.png   — SHM Next
  assets/logos/svti.png   — SVTI
  assets/logos/tzx.png   — Timezyx
  assets/logos/ar.png   — Atkins Réalis
  assets/logos/nh.png   — National Highways
  assets/logos/nr.png   — Network Rail
  assets/logos/rws.png   — Rijkswaterstaat
  assets/logos/da.png   — Die Autobahn
  assets/logos/fib.png   — fib
  assets/logos/rilem.png   — RILEM
  assets/logos/uos.png   — University of Southampton

(If you use SVG instead of PNG, change the .png in the <img src="..."> tags to .svg.)

## Adding photographs
  assets/concrete-infrastructure.jpg   Home page hero (currently a placeholder photograph — replace it)
  assets/about-photo.jpg               About page figure (not yet present; add the file and it appears)

## Editing text
Every page is plain HTML — open it in any text editor and edit the words between the tags. The
navigation and footer are repeated in each file, so a menu change needs the same edit in all eight.
