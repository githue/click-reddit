# How to add Click to your subreddit

1. [Open this CSS file](https://raw.githubusercontent.com/githue/click-reddit/master/stylesheet.css) and copy the contents into your subreddit stylesheet.
* [Right click to download this image](https://raw.githubusercontent.com/githue/click-reddit/master/sprite.png) and upload it to your stylesheet.
* [Download this Snoo logo](https://raw.githubusercontent.com/githue/click-reddit/master/snoo.png) or make your own, and upload it to your *subreddit settings*.
* For RES nightmode, add this to your sidebar text: `[](#/RES_SR_Config/NightModeCompatible)`
* See if there's any [customizations](https://www.reddit.com/r/click/wiki) you need to make via addons.

## Contributing

To contribute changes to the main project you will need the CSS preprocessor SASS.

Make your changes in /lib and then run this command from the root directory:

`sass lib/stylesheet.scss stylesheet.css -t compact`.
