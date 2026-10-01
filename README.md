# app-download-whimsey

Download page for the Whimsey Technologies Android app. Google Play and the App Store are coming soon.

Repository: [josephalexofficial/app-download-whimsey](https://github.com/josephalexofficial/app-download-whimsey)

## What is in this repository

| File | Role |
| --- | --- |
| `index.html` | The page. |
| `assets/whimsey-logo.png` | Brand mark. |
| `assets/Jost-Variable.ttf` | Brand typeface. |
| `downloads/WhimseyTech.apk` | The Android install file, version 1.0.0, 22.5 MB. |

The APK is stored here on purpose. The **Download for Android** button points at `downloads/WhimseyTech.apk`, so a host such as Netlify can serve that file with the page.

## Hosting on Netlify

Connect this repository. The site has no build step. Set the publish directory to the repository root (`.`). Netlify will publish `index.html` and the APK together.

The link you share is the Netlify site address. Visitors use **Download for Android**.

## Local preview

```bash
git clone https://github.com/josephalexofficial/app-download-whimsey.git
cd app-download-whimsey
```

Open `index.html` in a browser.

## Updating the app

Replace `downloads/WhimseyTech.apk` when a newer build is ready, and update the version line in `index.html`.
