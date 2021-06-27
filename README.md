# VideoAdBlockForTwitch

Swaps Twitch video ads for an ad-free stream between 1080p and 480p quality and then automatically switches back to original quality once the ad is done.

This is all done locally, so no VPN's, Proxies or third party websites.

You must remove any Twitch related user-scripts or other Twitch specific ad block extensions to prevent conflicts. You can use this extension with uBlock Origin though.

This extension is not compatible with AdGuard (AdGuard Extra Extension). If you have this installed you will get a loading loop. It must be disabled as their script will block this script. Use UBlock Origin instead.

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

4.5:</br>
Caught Chrome runtime error.</br>
Fixed a bug with tab visibility listeners.</br>

4.4:</br>
Unified content.js code for both extensions.</br>
Extension settings now apply correctly after tab refresh.</br>

4.3:</br>
Roll-back random device ID due to bugs for some users on Chrome.</br>

