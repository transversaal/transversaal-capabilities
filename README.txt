TRANSVERSAAL — EXPERIENTIAL MARKETING CAPABILITIES PAGE
=======================================================

WHAT'S IN THIS FOLDER

  transversaal-capabilities-PASTE.html
      The whole page in one file — every photo, the logo and the code are
      inside it. This is the one to paste into a Squarespace code block.
      About 3 MB. Photos are 900px wide.

  index.html + support.js + transversaal-logo-alpha.png + media/web/
      The same page using separate image files. Sharper photos (1600px),
      loads faster, but needs the whole folder kept together. Use this if
      you host the page instead of pasting it.

  README.txt
      This file.

Open either HTML file in Chrome to check it before uploading.


-------------------------------------------------------
ROUTE A — PASTE INTO A SQUARESPACE CODE BLOCK
-------------------------------------------------------

1. Open transversaal-capabilities-PASTE.html in a plain text editor
   (TextEdit, Notepad, VS Code — not Word).
2. Select all, copy.
3. In Squarespace, add a Code block to your page.
4. Set the block's type to HTML.
5. Paste. Save.
6. Set the page to full width and remove page padding so it sits edge to edge.

IMPORTANT: it's about 3 MB of text, so the editor may take 10-30 seconds to
accept the paste and may feel frozen while it does. Give it a minute before
assuming it failed. If Squarespace refuses it outright, use Route B.

Note: code blocks that run JavaScript require a Business plan or above.


-------------------------------------------------------
ROUTE B — HOST THE FOLDER, EMBED WITH AN IFRAME
-------------------------------------------------------

More reliable than pasting, and the photos are sharper.

1. Go to app.netlify.com/drop (free, no account needed to start).
2. Drag this entire folder onto the page. You'll get a URL like
   https://random-name-123.netlify.app
3. Open that URL and confirm the page looks right.
4. In Squarespace, add a Code block and paste this, swapping in your URL:

   <iframe
     src="https://YOUR-URL-HERE"
     style="width:100%; height:100vh; border:0; display:block;"
     title="Transversaal capabilities"
     loading="lazy">
   </iframe>

5. Set the page to full width and remove page padding.

If you want it on your own domain rather than a netlify.app address, point a
subdomain (e.g. work.transversaal.io) at the host in your DNS settings, then
use that in the iframe src.


-------------------------------------------------------
ROUTE C — HOST ON GITHUB PAGES (FREE)
-------------------------------------------------------

1. Go to github.com/new. Name the repo (e.g. transversaal-capabilities),
   set it to Public, click Create repository.
2. On the empty repo page, click "uploading an existing file".
3. Open this launch folder on your computer, select everything INSIDE it
   (index.html, support.js, the logo, and the media folder) and drag it
   onto the upload area. Do not drag the folder itself.
4. Wait for the upload to finish, then click Commit changes.
5. Go to Settings > Pages. Under "Build and deployment", set Source to
   "Deploy from a branch", Branch to "main", folder "/ (root)". Save.
6. Wait 1-2 minutes, refresh, and copy the URL it shows:
   https://YOUR-USERNAME.github.io/transversaal-capabilities/
7. Open it to confirm, then embed it in Squarespace with the iframe from
   Route B, using that URL.

To update later: open the file in GitHub, click the pencil icon, edit,
commit. The live page updates in about a minute.

-------------------------------------------------------
BEFORE YOU LAUNCH — ONE REQUIRED STEP
-------------------------------------------------------

THE CONTACT FORM NEEDS ACTIVATING.

Form submissions go to FormSubmit, which forwards them to aa@transversaal.io
with the sender's name, email, company, the need chips they picked, and their
brief.

The FIRST submission triggers a confirmation email from FormSubmit to
aa@transversaal.io. You must click the activation link in it. Until you do,
submissions will NOT arrive.

So: once the page is live, fill in the form yourself, submit it, then check
your inbox and your spam folder for the FormSubmit confirmation. Click the
link. Then test once more to confirm it lands.

If you'd rather not use a third party, a native Squarespace Form block can
replace that section instead — ask and I'll adjust the layout to suit.


-------------------------------------------------------
OTHER THINGS TO KNOW
-------------------------------------------------------

THE VIDEO TILE
  The nameless project's "Digital kiosk" tile opens a YouTube lightbox
  (youtube.com/shorts/l2R5kdoYxnA). It must stay Public with embedding
  allowed. If you see "error 153" while testing from a local file, that's a
  domain check failing on file:// — it resolves once the page is on a real
  domain.

INTERNET REQUIRED
  The page loads React and the Google Fonts from public CDNs at runtime, so
  it needs a connection. Nothing to install.

FONTS
  Caprasimo (headlines), Figtree (body copy), DM Mono (small uppercase
  labels). All free Google Fonts, loaded automatically.

THE LOGO
  transversaal-logo-alpha.png is your logo with the white background removed.
  Useful elsewhere on the site.

SWAPPING A PHOTO LATER
  Easiest in the folder version: drop the new file into media/web/ and update
  the filename in index.html. Each project's images sit together in the
  PROJECTS data near the bottom of the file, alongside a mediaCrop value that
  controls how each photo is cropped ("cover 50% 40%" means fill the frame,
  centered horizontally, 40% down). Or just send me the photo.

PROJECTS ON THE PAGE
  1. The Moro Pride Ride
  2. Liquid I.V. Beverage Carts & Hydration Stations
  3. Up In Smoke Tour 25th Anniversary
  4. GoPuff x Hoopbus College Takeover Tour
  5. nameless at ETH Denver
  6. Gratitude For Sale Podcast
