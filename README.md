# VideoAdBlockForTwitch

Swaps Twitch video ads for an ad-free stream between 1080p and 480p quality and then automatically switches back to original quality once the ad is done.

This is all done locally, so no VPN's, Proxies or third party websites.

You must remove any Twitch related user-scripts or other Twitch specific ad block extensions to prevent conflicts. You can use this extension with uBlock Origin though (Without user-scripts installed).

If you have issues while using this extension, please note, some ad-blocker extensions may interfere with this extension.

</br>

Chrome: https://chrome.google.com/webstore/detail/video-ad-block-for-twitch/kgeglempfkhalebjlogemlmeakondflc

Firefox: https://addons.mozilla.org/en-US/firefox/addon/video-ad-block-for-twitch/

</br>

If you would like to thank me and contribute to this extension:

https://paypal.me/ttvadblock

Or you can contribute with crypto:

https://commerce.coinbase.com/checkout/f289396a-e426-4b23-8daf-1ca9887fe2be

</br>

Some people are worried by the permissions requested by the extension. We ask for various URL permissions. These URL's are either Twitch based ad trackers or Twitch based ad serving URL's, we need the permission for these URL's, to be able to block them inside the background.js file (For Firefox), on Chrome we do this via the block_rules.json file. For this to happen we need WebRequest/WebRequest Blocking for Firefox and declarativeNetRequest for Chrome. We also request the Storage permission, this allows you to click on the extension icon and set settings, like blocking the "Blocking ads" message. To be able to do this, we need the storage permission to save your choice. You can see this in action in the content.js file and the popup.js file of each extension. Please read through all the opensource files to see that this is strictly all we use it for. This extension was made to protect your privacy, not abuse it. Thanks!</br></br>

Changelog:

5.3.0:</br>
Potential fix for stuck videos. Added to all versions.</br>

5.2.7:</br>
Potential fix for Firefox stuck video. Made version numbers the same for all versions.</br>

5.2.6:</br>
Remove temp fix for stuck video on Chrome only (Not needed).</br>

5.2.5:</br>
Temp fix for stuck video.</br>

5.2.3:</br>
Added extra check to prevent ads for some subbed users.</br>

5.2.2:</br>
Added client session, in case it's used in the future. Disabled ad-blocking for squad streams as it causes bugs.</br>

5.2.1:</br>
Fixed subbed channels bug. Fixed error 1000 bug.</br>

5.2.0:</br>
Added fallbacks for eventual UBlock bypass breaking.</br>

5.1.2:</br>
Fixed the non English streams letting ads through bug.</br>

5.1.1:</br>
Fixed video not pausing bug.</br>

5.1.0:</br>
Fixed stream delay bug, when opening background tabs and switching to them later.</br>

5.0.2:</br>
Added install message to let users know, that they must disable TTV LOL and Purple Ad-Block to prevent conflicts.</br>

5.0.1:</br>
Fixed missing video player bug when pausing/resuming.</br>

5.0.0:</br>
The extension will now automatically adjust the ad-free stream quality, without users needing to use the extension settings. This will help new users with buffering issues.</br>

