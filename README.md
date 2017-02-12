# EXT:jh_magnificpopup_ad

This extension adds a google ad after each x items.

**Warning:**  
Adding ads to a pop-up or lightbox is not allowed by Google AdSense Policies.
You are using this extension on your own risk.


## Installation
* Install Extension via Extension Manager
* Include static template to your website template
* Copy file `Resources/Private/TypoScript/AdsenseIframe.html` to fileadmin (or any other custom location)
and set `data-ad-client` and `data-ad-slot` in line 13 and 14.
* Set `adsenseIframe` in constants editor to path of your copied file from previous step
* You're done and everything should work well.