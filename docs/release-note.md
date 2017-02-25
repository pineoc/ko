# Release Notes
---

2.3.10 Release Notes
===
## Highlights
* SDKBOX for Cocos Creator Plugin
* Phunware Ads plugin
* Update SDK for Appnext
* [Issue tracking for SDKBOX](https://github.com/sdkbox/issues/issues)

## Bugfix
* Fix Installer error when trying to update multiple plugins
* Fix SDKBOX Ads error when the weights of different ad units is more than 100
* Fix [Facebook request have different text between iOS and Android](http://discuss.cocos2d-x.org/t/facebook-invitefriendswithinviteids-wrong-action-type-on-ios/34599/2)
* Fix [Facebook logout user when offline](http://www.sdkbox.com/answers/question/bug-android-sdkbox-facebook-auto-logout-when-start-game-without-internet/)
* Fix [AdColony getCustomID not working](http://www.sdkbox.com/answers/question/sdkbox-pluginadcolony-setcustomid-check-for-errors/)
* Fix [SDKBOX Play Documentation issues](https://github.com/sdkbox/issues/issues/2)

2.3.9 Release Notes
===
##Highlights
* Add "Designed for families" flag for admob
* Upgrade InMobi SDK
* SDKBOX LiveOps supports ATS


2.3.8 Release Notes
===
##Highlights
* IAP plugin will report order id by default
* AdColony SDK update
* Apteligent SDK update
* Appodeal SDK update

##Bugfix
* Fix [Installer time out issue](http://discuss.cocos2d-x.org/t/sdkbox-download-server-connection-problems/33892)
* Fix the cookie issue with sdkbox.com
* Fix [Sdkbox Ads crash](http://www.sdkbox.com/answers/question/app-crash-using-sdkbox-and-admob-plugin-on-iphone7/)
* Fix [pre/post popup for adcolony](http://discuss.cocos2d-x.org/t/sdkbox-adcolony-and-chartboost-bugs/33702)
* Add [native share to js/lua](http://discuss.cocos2d-x.org/t/sdkbox-2-3-7-released-native-share-is-here/33695/9?u=nite)
* Fix [OneSignal missing arm64 for iOS](http://discuss.cocos2d-x.org/t/pluginonesignal-ios-missing-arm64/33811)


2.3.7 Release Notes
===
##Highlights
* [Native share](http://docs.sdkbox.com/en/plugins/share/v3-cpp/#native-share)
* Sdkbox Ads supports adjust ads with weight on LiveOps
* Test and verified SDKBOX with NDK 12
* Remove soomla, vungle plugins
* Merge achievement leaderboard plugin with SDKBOX Play

##Bugfix
* Fix [tune plugin crash](http://discuss.cocos2d-x.org/t/tune-plugin-crash-js/32114/4)
* Fix [facebook share cancel callback](http://discuss.cocos2d-x.org/t/facebook-plugin-share-issues/33136/3)
* Fix [One signal bug](http://www.sdkbox.com/answers/question/onesignal-notifications_when_activefalse-not-working/)
* Fix [SdkboxAds shows invalid placement name](http://www.sdkbox.com/answers/question/app-crash-using-sdkbox-and-admob-plugin-on-iphone7/)
* Fix installer caching issue when updating


2.3.6 Release Notes
===
##Highlights
* Support Google Analytics exceptions
* Update SDK for InMobi
* add google access token data to SDKBOX play android

##Bugfix

2.3.5 Release Notes
===
##Highlights
* AdColony 3.0 update (Note: AdColony)

##Bugfix
* Trim ARM x64 build to reduce size

2.3.4 Release Notes
===
##Highlights
* Make sure IAP receipts are always available
* Add `hide()` function to hide banner for SDKBoxAds

##Bugfix
* [Facebook] Fix get user info callback when user login
* [GPG] Fix turn based multiplayer sample for JS
* [LiveOps] Fix a issue happens when user have more than 28 achievements
* [Appodeal] Fix installer for cheetah mobile error


2.3.2 Release Notes
===
##Highlight
* Goolge Play Game Services plugin enable you to implement a huge array of services with ease in your game.
 * Authorization
 * Achievements
 * Leaderboards
 * Turn-based multiplayer
 * Real-time multiplayer
 * Events and Quests
 * Saved Games
 * Nearby Connections (Android only)
 * Player Statistics
* Add Hide banner functionality to sdkboxAds
* Upgrade SDK for Appodeal
* Upgrade SDK for Fyber
* Upgrade SDK for admob
* Upgrade SDK for Flurry
* Upgrade SDK for Kochava
* Upgrade SDK for AdColony
* Upgrade SDK for AppNext

##Bugfix
* Fix Crashing issue for OneSignal

2.3.1 Release Notes
===
##Highlight
* Add achievement notification control to LiveOps
* Support latest cocos2d-x and Cococs Creator

##Bugfix
* Fix a crashing issue with sdkboxads
* Fix setListener on android
* Restore products nolonger returns consumables
* Fix sdkboxplay crash if logged out from google play settings menu
* Fix a crash when finish playing certain Inmobi videos
* Support latest cocos2d-x and Cococs Creator
* Fix facebook callback not triggering when using facebook share dialog
* Fix a sdkboxplay crash on iOS when listener was not set
* Fix appodeal crash when skip videos


2.3.0 Release Notes
===
##Highlight
* SDKBOX installer supports projects created with Cocos Creator 1.2
* SDKBOX play now supports enable/disable achievement popup from GameCenter & Google Play
* Add isAvailable function to SDKBOX Ads to check ads availablility
* Fix google security warning for SDKBOX IAP
* SDKBOX IAP Supports restore subscription for Google Play

##Bugfix
* Fix a crash issue for Admob
* Fix SDKBOX installer issue with windows path that contains spaces
* Fix appodeal create duplicate records issue during update process
* Fix chartboost video went black when press home button on android

2.2.5 Release Notes
===
##Highlight
* SDKBOX supports loading encrypted configuration locally
* SDKBOX partially supports cocos creator project, user will still need to copy sdkbox_config.json manually

##Bugfix
* Fix chartboost crashing issue
* Fix sdkboxplay JS binding crash issue
* Fix sdkboxplay onMyScore callback

2.2.4 Release Notes
===
##Highlight
* Share plugin support email
* add new APIs to sdkboxplay to retrieve player score
* Update Facebook SDK to the latest version
* Update Appodeal to the latest version
* Update Bee7 to the latest version
* Make sure SDKBOX is compliant with google play and iTune store's privacy policy

##Bugfix
* Fix sdkboxplay keep asking user to login
* Fix sdkboxplay crash when there is more than 76 achievements
* Fix review plugin crash

2.2.3 Release Notes
===
##Highlight
* Admob plugin now auto caches ads
* Inmobi plugin now can hide banners
* Upgraded google play services to the latest version
* SDKBOX supports loading encrypted configration locally

##Bugfix
* Fix multiple issue regarding sdkbox play login
* various documentation fixes

2.2.2 Release Notes
===
##Highlight
* Admob will automatically cache ads
* New user id related functions in SDKBOX play
* Youtube plugin supports customize close button
* Vungle SDK has been updated
* Appodeal SDK has been updated
* Share plugin supports composing dialog

##Bugfix
* Fix a crashing issue with facebook
* Fix installer issue with cocos2d-x 3.11

2.2.1 Release Notes
===
##Highlight
* OneSignal plugin for push notification
* update AppNext SDK
* update vungle android SDK
* update InMobi SDK
* add new AD displaying strategy
* Add Text messaging support for share plugin
* Apteligent plugin now will install a uploading script for your debug symbol files
* Share plugin now supports share dialog

##Bugfix
* Fix installer only updates one plugin
* Fix installer will downgrade android API level
* Fix SDKBOX ads js crash issue
* Fix facebook crash issue when no facebook id
* Fix facebook android sample

2.2 Release Notes
===
##Highlight
* SDKBOX play plugin offers cross platform solution for Leaderboard and achievements
* Apteligent plugin offers crash reporting
* Optimize sample projects makes them take less space
* Facebook plugin supports setting App ID with config file

##Bugfix
* Fix IAP crashing issue when user side verification was set.

2.1.3 Release Notes
===
##Highlight
* Developer can enable/disable a plugin using sdkbox.com
* Share plugin now supports share to facebook as well
* Facebook Plugin now supports set Facebook App id through config and code
* Updated Appodeal SDK

##Bugfix
* Add JS callback function for Kochava plugin


2.1.2 Release Notes
===
##Highlight
* Update Appodeal SDK
* Update Fyber SDK


##Bugfix
* Fix js binding for cocos2d-x v2
* Fix appodeal callback for iOS
* Fix playphone been initialized multiple times

2.1.1 Release Notes
===
##Highlight
* Amazon plugin
* Upgrade Adcolony Android SDK to 2.3.2
* Upgrade Appodeal iOS SDK to 0.9.0
* Upgrade Appodeal Android SDK to 1.14.18

##Bug
* fix sdkbox update process will stuck in windows shell
* fix a crash with facebook api call

2.1.0 Release Notes
===
##Highlight
* LeadBolt plugin

##Bug
* sdkbox update command will not overwrite sdkbox_config.json
* Fix tune plugin not sending correct measure event
* Fix InMobi can't preload ads


2.0.0 Release Notes
===
##Highlight
* SDKBOX LiveOps feature which user can update their SDKBOX config files
* Admob plugin
* Share plugin with twitter support
* Update Adcolony, Vungle and Appodeal
* provide a lite version of google play service to avoid android's api limitations, check it out [here](https://github.com/darkdukey/Google-Play-Service-Lite)

##Bug
* Fix IAP crash when google play service are not initalized correctly
* Fix installer will change Android.mk format bug
* Fix compatibility issue with Reachability project
* Fix InMobi banner settings
* Fix conflicts between Tune and other plugins


1.5.2 Release Notes
===
##Highlight
* Include Google Play Services SDK for needed plugins. No need to install it manually anymore.
* Support the coming Cocos 3.10 release

##Bugfix
*

1.5.1 Release Notes
===
##Highlight
* InMobi plugin
* Update Tune plugin
* Update Appodeal plugin
* Installer will not auto detects projects using c++static library and install correct binary
* Add SDKBOX_ENABLED flag to support projects in other platforms (win, osx, linux)

##Bugfix
* Fix a crash when user attempt purchase in offline mode for IAP plugin.
* Fix generate n/a directory for windows
* Fix a bug that will result android platform have incorrect APP_PLATFORM, and failed to build.


1.5 Release Notes
===
##Highlight
* ScientificRevenue Plugin
* Youtube Plugin
* SDKBOX Installer now support switching different android app stores with `sdkbox set store`
* SDKBOX Installer now supports dependencies between plugins
* Created automatic installation script for installer
* c++static lib support
* Add SDKBOX_ENABLED flag to support projects in other platforms (win, osx, linux)


##Bugfix
* Installer download update to the wrong folder
* remove dependency to ANDROID_SDK_ROOT, installer will find android SDK automatically
* remove dependency to COCOS_CONSOLE_ROOT


1.4.1 Release Notes
===
##Highlight
* Automatic installation script help you setup sdkbox in a flash
* Update vungle android SDK to 3.3.3
* Update appodeal to support rewarded video
* Update tune SDK

##Bugfix
* Fix facebook invite app link documentation
* Installer will no longer modify osx projects
* Fix chartboost isAvailable functions
* Fix proguard setttings

1.4 Release Notes
===
##Highlight
* [SDKBOX Playphone plugin](http://cocos2d-x.org/sdkbox/playphone)
* [SDKBOX Valuepotion plugin](http://cocos2d-x.org/sdkbox/valuepotion)
* [SDKBOX Appodeal plugin](http://cocos2d-x.org/sdkbox/appodeal)


1.3 Release Notes
===
##Highlight
* New `update` command in sdkbox installer, which will automatically update your SDKBOX integration to the latest version
* [SDKBOX Fyber plugin](http://cocos2d-x.org/sdkbox/fyber)
* [SDKBOX Bee7 plugin](http://cocos2d-x.org/sdkbox/bee7)
* [SDKBOX SOOMLA Grow plugin](http://cocos2d-x.org/sdkbox/soomlagrow)
* [SDKBOX Ratings and Review plugin](http://cocos2d-x.org/sdkbox/ratings_reviews)

##Bugfix
* [Fix facebook plugin requires login after app restart]()
* [Fix SDKBOX using absolute path for resources]()
* [Fix SDKBOX iap not handling network connection issue]()


1.2.5 Release Notes
===
##Highlight
* we created Review&Rating plugin that developer can use to prompt user to rate their app

##Bugfix
* [Fix Android-Studio integration](http://discuss.cocos2d-x.org/t/sdkbox-v0-5-6-21-android-studio-problem/23866)
* [Fix vungle isCacheAvailable function](http://stackoverflow.com/questions/31979195/failed-to-find-method-id-of-iscacheavailable-on-vungle-android-because-it-cannot)
* [Fix AdColony failed to get reward](http://discuss.cocos2d-x.org/t/adcolony-sdkbox-cant-get-reward-after-complete-view-video-ads-on-version-1-2-3-3/23600)
* [Plugins can't work together](http://discuss.cocos2d-x.org/t/error-facebook-iap-sdkbox-not-working-together/23851)

1.2.4 Release Notes
===
Fix installer failed to find ANDROID_LIB directory issue

1.2.3 Release Notes
===
##Highlight
* 1.2.3 Fixes some major bugs for the plugins, we strongly recommend updating older versions to 1.2.3

##Bugfix
Sometimes using callbacks will result in sprites show up as black, this is due to invoking cocos2d-x from a different thread
[IAP: item description can't contain newline](http://discuss.cocos2d-x.org/t/solved-google-play-iab-hasnt-been-initilized/22761/21)
[Facebook: missing api function for js/lua binding](http://discuss.cocos2d-x.org/t/sdkbox-facebook-no-api-bug/23414)
[Installer: fix COCOS_CONSOLE_ROOT invalid error](http://discuss.cocos2d-x.org/t/installation-error-for-sdkbox-iap/22898)

##AdColony
## Changelog
1. Update AdColony iOS SDK to 2.5.3
2. `register_PluginAdColonyLua_helper` -> `register_all_PluginAdColonyLua_helper`
3. `#include "PluginAdColonyLuaHelper.hpp"` -> `#include "PluginAdColonyLuaHelper.h"`
4. `#include "PluginAdColonyJSHelper.hpp"` -> `#include "PluginAdColonyJSHelper.h"`

##AgeCheq
## Changelog
1. `register_PluginAgeCheqLua_helper` -> `register_all_PluginAgeCheqLua_helper`
2. `#include "PluginAgeCheqLuaHelper.hpp"` -> `#include "PluginAgeCheqLuaHelper.h"`
3. `#include "PluginAgeCheqJSHelper.hpp"` -> `#include "PluginAgeCheqJSHelper.h"`

##Chartboost
## Changelog
1. `register_PluginChartboostJS_helper` -> `register_all_PluginChartboostJS_helper`
2. `register_PluginChartboostLua_helper` -> `register_all_PluginChartboostLua_helper`
3. Update Chartboost iOS SDK to 5.5.3
4. Update Chartboost Android SDK to 5.5.3
5. `#include "PluginChartboostLuaHelper.hpp"` -> `#include "PluginChartboostLuaHelper.h"`

##Facebook
## Changelog
1. `register_PluginFacebookJS_helper` -> `register_all_PluginFacebookJS_helper`
2. `register_PluginFacebookLua_helper` -> `register_all_PluginFacebookLua_helper`
3. Update Facebook iOS SDK to 4.5.1
4. Update Facebook Android SDK to 4.5.1
5. `#include "PluginFacebookLuaHelper.hpp"` -> `#include "PluginFacebookLuaHelper.h"`

##Flurry Analytics
## Changelog
1. `register_PluginFlurryAnalyticsJS_helper` -> `register_all_PluginFlurryAnalyticsJS_helper`
2. `register_PluginFlurryAnalyticsLua_helper` -> `register_all_PluginFlurryAnalyticsLua_helper`
3. Update Flurry iOS SDK to 6.7.0
4. Update Flurry Android SDK to 5.6.0
5. `#include "PluginFlurryAnalyticsLuaHelper.hpp"` -> `#include "PluginFlurryAnalyticsLuaHelper.h"`

##Google Analytics
## Changelog
1. `#include "PluginGoogleAnalyticsLuaHelper.hpp"` -> `#include "PluginGoogleAnalyticsLuaHelper.h"`

##IAP
## Changelog
1. `register_PluginIAPLua_helper` -> `register_all_PluginIAPLua_helper`
2. `#include "PluginIAPLuaHelper.hpp"` -> `#include "PluginIAPLuaHelper.h"`
3. `#include "PluginIAPJSHelper.hpp"` -> `#include "PluginIAPJSHelper.h"`

##Tune
1. `register_PluginTuneJS_helper` -> `register_all_PluginTuneJS_helper`
2. `register_PluginTuneLua_helper` -> `register_all_PluginTuneLua_helper`
3. Update MobileAppTracker Android SDK to 3.10.1
4. `#include "PluginTuneLuaHelper.hpp"` -> `#include "PluginTuneLuaHelper.h"`

##Vungle
## Changelog
1. `register_PluginVungleJS_helper` -> `register_all_PluginVungleJS_helper`
2. `register_PluginVungleLua_helper` -> `register_all_PluginVungleLua_helper`
3. `#include "PluginVungleLuaHelper.hpp"` -> `#include "PluginVungleLuaHelper.h"`



1.2.2 Release Notes
====
##Highlight
* Installer will automatically modify `Cocos2dxActivity.java` for you
* Facebook Plugin supports `getFriends()` function
* IAP supports `onRestoreComplete()` callback
* IAP will auto consume items if

##Bugfix

[IAP: Item already owned](http://discuss.cocos2d-x.org/t/iap-google-play-buying-product-twice/22842)
[Facebook: FB_PHOTO is not defined] (http://discuss.cocos2d-x.org/t/facebook-fb-photo-is-not-defined/23064)
[Facebook: Facebook plugin failed to work with Cocos2d-js 3.0](http://discuss.cocos2d-x.org/t/sdkbox-facebook-work-well-but-other-plugin-fails-whyy/23043)
[Chartboost: too much recursion](http://discuss.cocos2d-x.org/t/chartboost-listeners-too-much-recursion-on-android/23221/2)

1.2.1 Release Notes
====

##Highlight
[Facebook plugin](http://cocos2d-x.org/sdkbox/facebook) is here.

##Bugfix
[IAP JS crash](http://discuss.cocos2d-x.org/t/sdkbox-iap-for-cocos2d-js-crash-when-onproductrequestsuccess/22814/8)
[IAP crash on devices don't have google play](https://trello.com/c/hm1oZrNA)

##1.2.0
Release AgeCheq Plugin.
SDKBOX IAP Supports non-consumable
Chinese version of documentation relased
Bug fixes

##1.1.6
SDKBOX now supports install plugin online
SDKBOX online documentation
Upgrade Vugnle SDK to new version
 * iOS: 3.1.2
 * Android: 3.3.1

##1.1.5
Fix SDKBOX conflicts with Plugin-x

##1.1.4
Fix SDKBOX IAP plugin return invalid pricing data
