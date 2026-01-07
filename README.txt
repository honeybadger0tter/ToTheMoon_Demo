ToTheMoon_DemoKit_v4

OPEN
- Open index.html in Safari/Chrome.
- If the Google map embed acts up, hit "Alternate Map" or use "Open in Google Maps".

QUICK EDITS (no regeneration needed)
1) Rewards signup URL:
   In index.html find:
     const DEMO = { rewardsSignupUrl: "" ... }
   Paste your URL between the quotes.

2) Replace photos:
   Swap images in /assets/ (keep filenames the same) to update the Gallery quickly:
     assets/gallery-01.jpg ... gallery-08.jpg

3) Add/rename nav links:
   Edit the <nav class="navlinks"> section in index.html (and other pages if desired).
   Placeholder pages already exist:
     sweet-story.html, rewards.html, shop.html, contact.html, events.html

RESET DEMO
Bottom-right "Reset Demo" clears the theme + popup 'seen' state.
