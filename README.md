# TuyauPipe / Pipe Studio developer site

This repository hosts the public developer website for games and apps published by TuyauPipe / Pipe Studio.

The site is the stable public base for product pages, support pages, privacy policies, user privacy choices, and advertising-system files required by App Store Connect, Google Play, AdMob, and other distribution services.

## Published Site

- Developer / marketing home: <https://tuyaupipe.github.io/>
- Sitemap: <https://tuyaupipe.github.io/sitemap.xml>
- Advertising file: <https://tuyaupipe.github.io/app-ads.txt>

## Games

### HexMinefield 3D

Spherical 3D Minesweeper puzzle for Android.

- Game page: <https://tuyaupipe.github.io/hexminefield-3d/>
- Google Play: <https://play.google.com/store/apps/details?id=net.pipestudio.hexminefield3d>
- Support: <https://tuyaupipe.github.io/hexminefield-3d/support/>
- Privacy Policy: <https://tuyaupipe.github.io/hexminefield-3d/privacy-policy/>
- Privacy Choices: <https://tuyaupipe.github.io/hexminefield-3d/privacy-choices/>

### Flappy Raccoon

Mobile arcade game.

Use the developer home page contact email for support questions until dedicated product pages are added.

## Repository Layout

- `index.html`: public developer / marketing home.
- `sitemap.xml`: crawlable list of public pages.
- `app-ads.txt`: advertising-system declaration for AdMob.
- `hexminefield-3d/index.html`: HexMinefield 3D product page.
- `hexminefield-3d/support/index.html`: HexMinefield 3D support page.
- `hexminefield-3d/privacy-policy/index.html`: HexMinefield 3D privacy policy.
- `hexminefield-3d/privacy-choices/index.html`: HexMinefield 3D privacy and consent choices.

## Maintenance Notes

Keep product routes separate so the site can centralize several apps without implying that every app has identical data practices. Keep pages static, readable on mobile and desktop, and usable without JavaScript. Recheck the policy, store declarations, SDK inventory, and shipped binary together before each public release.
