WREN — OFFLINE APP SETUP
========================

You put Wren on a free website ONCE. Then you install her from there.
After that she lives on your phone and works with no internet at all.
Her memory stays on your phone. Nothing you tell her is uploaded.

You can do all of this from your phone. Takes about 10 minutes.


STEP 1: UNZIP
-------------
iPhone: open the Files app, tap wren-app.zip. It makes a "wren-app" folder.
Android: open your Files app, tap wren-app.zip, tap Extract.

You should have these 8 files:
  index.html, sw.js, manifest.webmanifest, README.txt,
  icon-192.png, icon-512.png, icon-maskable-512.png, apple-touch-icon.png


STEP 2: PUT HER ONLINE (free, GitHub Pages)
-------------------------------------------
1. Go to github.com and make a free account (skip if you have one).
2. Tap + (top right) -> New repository.
   Name: wren    |    Public    |    Create repository.
3. Tap "uploading an existing file".
4. Choose ALL the files from the wren-app folder (not the folder itself).
5. Scroll down, tap "Commit changes".
6. Go to the repo's Settings -> Pages.
   Source: "Deploy from a branch"  |  Branch: main  |  Folder: / (root)  |  Save.
7. Wait 1-2 minutes. Your app is at:
     https://YOUR-USERNAME.github.io/wren/

Note: the website is public, but it's only the empty app. Your
conversations and memories never leave your phone.


STEP 3: INSTALL ON YOUR PHONE
-----------------------------
Open https://YOUR-USERNAME.github.io/wren/ while you have internet. Wait
until Wren says she's saved for offline use. Then:

  Android (Chrome): tap Install at the top of Wren, or the menu (three dots)
                    -> Install app / Add to Home screen.
  iPhone (Safari):  tap Share (square with an arrow) -> Add to Home Screen -> Add.
                    (Must be Safari. Other iPhone browsers can't install apps.)

Open Wren from the new home-screen icon from now on.

TEST IT: turn on airplane mode and open her. She should work normally.


STEP 4: BRING HER MEMORIES OVER
-------------------------------
The app is a fresh copy, so move what she learned from the old file:
1. Open the OLD Wren file -> Brain -> Export backup. Save the file.
2. Open the NEW app -> Brain -> Import backup -> pick that file.


WHAT WORKS BETTER AS AN APP
---------------------------
- Opens full screen from her own icon, instantly, offline.
- GPS and the compass work properly (phones block sensors for loose files).
- Your phone is far less likely to clear her memory.
- She updates herself quietly when you have internet.

PHOTOS (the 📷 button)
---------------------
Send a photo (camera or gallery). She describes it, and if you tell her
what it is, she learns it. Show her 2-4 photos of the same thing from
different angles and light, and she'll start recognizing it.
Photos stay on your phone. Like books, they are NOT part of "Export backup".
She never treats a photo guess as safe ID for plants, mushrooms, or animals.

BOOKS (the 📚 button)
--------------------
Download free books while you're online, then tap 📚 -> Add book:
  The Art of War:  gutenberg.org/ebooks/132   (choose Plain Text or EPUB)
  The Odyssey:     gutenberg.org/ebooks/1727  (Samuel Butler translation)
  More: gutenberg.org and standardebooks.org
She reads .txt, .epub, .html, and .md. Not PDFs or Kindle/store ebooks.
Books are saved inside the app on your phone. They are NOT part of
"Export backup", so keep the book files if you ever switch phones.

STILL TRUE
----------
- Reminders and alarms ring only while she's open. Use your phone's clock
  app for anything you must not miss.
- Export a backup now and then (Brain -> Export backup).
- On iPhone, open her at least every few weeks; iOS can clear storage for
  apps that go unused a long time.


OPTIONAL: A REAL ANDROID APP FILE (.apk)
----------------------------------------
After Step 2, go to pwabuilder.com, enter your Wren address, and choose
Package for Stores -> Android. It builds an installable Android app file
for free. (Not needed; the home-screen app from Step 3 works the same.)


UPDATING WREN LATER
-------------------
Upload the new index.html to the same GitHub repo (replace the old one),
and in sw.js raise VERSION by one (this copy is "wren-v7"). Phones update
themselves next time they're online.
