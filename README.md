# atlipall.github.io

The site root. Garmin Map is now [Varda](https://vardamaps.app/) (repo
[atlipall/varda](https://github.com/atlipall/varda)): the front page and `garmin-maps/` send old
links there. `.well-known/assetlinks.json` vouched for the Android apps (`is.atlipall.garminmap` and
`.dev`) while they opened this address; they now use vardamaps.app's own, so it can go once no
installed app opens the old address. `.nojekyll` makes GitHub Pages serve that dot-folder.
