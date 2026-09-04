# Md Irfan Raza Portfolio V6

This version is redesigned to closely follow the supplied dark retro pixel-game portfolio reference while staying original.

## Key fixes
- Project Gallery is a real separate page: `gallery.html`
- Project Gallery button is visible in the top header
- Instagram button is visible in the top header
- Both buttons stay visible on desktop and mobile
- Mobile navigation now uses a hamburger instead of silently hiding navigation
- Homepage layout follows the supplied reference more closely
- 5 best reels stay in one horizontal row
- Payoff section uses:
  - This One Change Can Reduce Your Electricity Bill by 95%
  - 1.1M views
  - On ground documentary + motion graphics
- Animated flags, animated stars and moving clouds
- Responsive desktop/tablet/mobile layout
- User photo used in the hero
- Client/brand screenshots at the end

## Contact
- Email: irfanraza055@gmail.com
- Phone / WhatsApp: 7717777075
- Instagram: https://www.instagram.com/edit_aspire/

## Deploy
Upload the whole extracted folder to Netlify Drop.
Do NOT upload an older V4/V5 folder if you want Gallery and Instagram fixes.


## V7 changes
- Added real PNG UI/game assets inside `assets/`
- Homepage and gallery now use PNG assets instead of only CSS-drawn shapes
- Assets added:
  - cloud.png
  - star.png
  - coin.png
  - brick.png
  - question-block.png
  - pipe.png
  - ground-tile.png
  - flag-red.png
  - flag-blue.png
  - ladder.png


## V8 IMPORTANT FIX
- Profile frame is now a single PNG asset: `assets/profile-card-v8.png`
- Clouds, coins, pipe, flags, bricks and ground are combined into: `assets/hero-scenery-v8.png`
- Gallery decoration uses: `assets/gallery-scenery-v8.png`
- Old CSS-drawn cloud/frame system is disabled
- CSS renamed to `styles-v8.css`
- JS renamed to `script-v8.js`
- `?v=8` cache-busting added so Netlify/browser cannot keep showing the old design

When deploying, extract this ZIP and upload the ENTIRE V8 folder.


## V9 fixes
- Added a real sky background PNG: `assets/sky-v9.png`
- Replaced the About-section mini scene with a real PNG: `assets/mini-scene-v9.png`
- Fixed screenshot cards so images show fully using `object-fit: contain`
- Updated CSS reference to `styles-v9.css?v=9`
- Updated JS reference to `script-v9.js?v=9`
- This version should visibly look different even with browser cache


## V10 asset replacement
The website now uses the newly approved visual assets:
- `assets/cloud.png`
- `assets/coin.png`
- `assets/star.png`
- `assets/pipe.png`

They were trimmed, optimized and resized for the portfolio.
Hero and gallery scenery were rebuilt as:
- `assets/hero-scenery-v10.png`
- `assets/gallery-scenery-v10.png`

Cache busting:
- `styles-v10.css?v=10`
- `script-v10.js?v=10`


## V11 sky fix
- Used your edited V10 package as source
- Rebuilt hero and gallery scenery from the CURRENT assets folder
- New files:
  - assets/hero-scenery-v11.png
  - assets/gallery-scenery-v11.png
- Fixed crop by removing `object-fit: cover` behavior from scenery images
- New stylesheet: styles-v11.css
- New script reference: script-v11.js
- Cache busting: ?v=11
