# atlipall.github.io

The site root. It holds `.well-known/assetlinks.json`, which tells Chrome that the Garmin Map
Android apps (`is.atlipall.garminmap` and `.dev`, see
[garmin-maps/android](https://github.com/atlipall/garmin-maps/tree/main/android)) belong to this
site, so they open the app full screen without an address bar. `.nojekyll` makes GitHub Pages
serve that dot-folder. The front page sends visitors to [Garmin Map](https://atlipall.github.io/garmin-maps/).
