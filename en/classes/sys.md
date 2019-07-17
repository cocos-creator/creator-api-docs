## `sys` Class



Module: [_decorator](../modules/_decorator.md)
Parent Module: [cc](../modules/cc.md)


System variables



### Index

##### Properties

  - [`LANGUAGE_ENGLISH`](#languageenglish) `String` English language code
  - [`LANGUAGE_CHINESE`](#languagechinese) `String` Chinese language code
  - [`LANGUAGE_FRENCH`](#languagefrench) `String` French language code
  - [`LANGUAGE_ITALIAN`](#languageitalian) `String` Italian language code
  - [`LANGUAGE_GERMAN`](#languagegerman) `String` German language code
  - [`LANGUAGE_SPANISH`](#languagespanish) `String` Spanish language code
  - [`LANGUAGE_DUTCH`](#languagedutch) `String` Spanish language code
  - [`LANGUAGE_RUSSIAN`](#languagerussian) `String` Russian language code
  - [`LANGUAGE_KOREAN`](#languagekorean) `String` Korean language code
  - [`LANGUAGE_JAPANESE`](#languagejapanese) `String` Japanese language code
  - [`LANGUAGE_HUNGARIAN`](#languagehungarian) `String` Hungarian language code
  - [`LANGUAGE_PORTUGUESE`](#languageportuguese) `String` Portuguese language code
  - [`LANGUAGE_ARABIC`](#languagearabic) `String` Arabic language code
  - [`LANGUAGE_NORWEGIAN`](#languagenorwegian) `String` Norwegian language code
  - [`LANGUAGE_POLISH`](#languagepolish) `String` Polish language code
  - [`LANGUAGE_TURKISH`](#languageturkish) `String` Turkish language code
  - [`LANGUAGE_UKRAINIAN`](#languageukrainian) `String` Ukrainian language code
  - [`LANGUAGE_ROMANIAN`](#languageromanian) `String` Romanian language code
  - [`LANGUAGE_BULGARIAN`](#languagebulgarian) `String` Bulgarian language code
  - [`LANGUAGE_UNKNOWN`](#languageunknown) `String` Unknown language code
  - [`OS_IOS`](#osios) `String` 
  - [`OS_ANDROID`](#osandroid) `String` 
  - [`OS_WINDOWS`](#oswindows) `String` 
  - [`OS_MARMALADE`](#osmarmalade) `String` 
  - [`OS_LINUX`](#oslinux) `String` 
  - [`OS_BADA`](#osbada) `String` 
  - [`OS_BLACKBERRY`](#osblackberry) `String` 
  - [`OS_OSX`](#ososx) `String` 
  - [`OS_WP8`](#oswp8) `String` 
  - [`OS_WINRT`](#oswinrt) `String` 
  - [`OS_UNKNOWN`](#osunknown) `String` 
  - [`UNKNOWN`](#unknown) `Number` 
  - [`WIN32`](#win32) `Number` 
  - [`LINUX`](#linux) `Number` 
  - [`MACOS`](#macos) `Number` 
  - [`ANDROID`](#android) `Number` 
  - [`IPHONE`](#iphone) `Number` 
  - [`IPAD`](#ipad) `Number` 
  - [`BLACKBERRY`](#blackberry) `Number` 
  - [`NACL`](#nacl) `Number` 
  - [`EMSCRIPTEN`](#emscripten) `Number` 
  - [`TIZEN`](#tizen) `Number` 
  - [`WINRT`](#winrt) `Number` 
  - [`WP8`](#wp8) `Number` 
  - [`MOBILE_BROWSER`](#mobilebrowser) `Number` 
  - [`DESKTOP_BROWSER`](#desktopbrowser) `Number` 
  - [`EDITOR_PAGE`](#editorpage) `Number` Indicates whether executes in editor's window process (Electron's renderer context)
  - [`EDITOR_CORE`](#editorcore) `Number` Indicates whether executes in editor's main process (Electron's browser context)
  - [`WECHAT_GAME`](#wechatgame) `Number` 
  - [`QQ_PLAY`](#qqplay) `Number` 
  - [`FB_PLAYABLE_ADS`](#fbplayableads) `Number` 
  - [`BAIDU_GAME`](#baidugame) `Number` 
  - [`VIVO_GAME`](#vivogame) `Number` 
  - [`OPPO_GAME`](#oppogame) `Number` 
  - [`HUAWEI_GAME`](#huaweigame) `Number` 
  - [`XIAOMI_GAME`](#xiaomigame) `Number` 
  - [`JKW_GAME`](#jkwgame) `Number` 
  - [`BROWSER_TYPE_WECHAT`](#browsertypewechat) `String` BROWSER_TYPE_WECHAT
  - [`BROWSER_TYPE_WECHAT_GAME`](#browsertypewechatgame) `String` BROWSER_TYPE_WECHAT_GAME
  - [`BROWSER_TYPE_WECHAT_GAME_SUB`](#browsertypewechatgamesub) `String` BROWSER_TYPE_WECHAT_GAME_SUB
  - [`BROWSER_TYPE_BAIDU_GAME`](#browsertypebaidugame) `String` BROWSER_TYPE_BAIDU_GAME
  - [`BROWSER_TYPE_BAIDU_GAME_SUB`](#browsertypebaidugamesub) `String` BROWSER_TYPE_BAIDU_GAME_SUB
  - [`BROWSER_TYPE_XIAOMI_GAME`](#browsertypexiaomigame) `String` BROWSER_TYPE_XIAOMI_GAME
  - [`BROWSER_TYPE_QQ_PLAY`](#browsertypeqqplay) `String` BROWSER_TYPE_QQ_PLAY
  - [`BROWSER_TYPE_ANDROID`](#browsertypeandroid) `String` 
  - [`BROWSER_TYPE_IE`](#browsertypeie) `String` 
  - [`BROWSER_TYPE_QQ`](#browsertypeqq) `String` 
  - [`BROWSER_TYPE_MOBILE_QQ`](#browsertypemobileqq) `String` 
  - [`BROWSER_TYPE_UC`](#browsertypeuc) `String` 
  - [`BROWSER_TYPE_UCBS`](#browsertypeucbs) `String` uc third party integration.
  - [`BROWSER_TYPE_360`](#browsertype360) `String` 
  - [`BROWSER_TYPE_BAIDU_APP`](#browsertypebaiduapp) `String` 
  - [`BROWSER_TYPE_BAIDU`](#browsertypebaidu) `String` 
  - [`BROWSER_TYPE_MAXTHON`](#browsertypemaxthon) `String` 
  - [`BROWSER_TYPE_OPERA`](#browsertypeopera) `String` 
  - [`BROWSER_TYPE_OUPENG`](#browsertypeoupeng) `String` 
  - [`BROWSER_TYPE_MIUI`](#browsertypemiui) `String` 
  - [`BROWSER_TYPE_FIREFOX`](#browsertypefirefox) `String` 
  - [`BROWSER_TYPE_SAFARI`](#browsertypesafari) `String` 
  - [`BROWSER_TYPE_CHROME`](#browsertypechrome) `String` 
  - [`BROWSER_TYPE_LIEBAO`](#browsertypeliebao) `String` 
  - [`BROWSER_TYPE_QZONE`](#browsertypeqzone) `String` 
  - [`BROWSER_TYPE_SOUGOU`](#browsertypesougou) `String` 
  - [`BROWSER_TYPE_UNKNOWN`](#browsertypeunknown) `String` 
  - [`isNative`](#isnative) `Boolean` Is native ? This is set to be true in jsb auto.
  - [`isBrowser`](#isbrowser) `Boolean` Is web browser ?
  - [`isMobile`](#ismobile) `Boolean` Indicate whether system is mobile system
  - [`platform`](#platform) `Number` Indicate the running platform
  - [`languageCode`](#languagecode) `String` Get current language iso 639-1 code.
  - [`language`](#language) `String` Indicate the current language of the running system
  - [`os`](#os) `String` Indicate the running os name
  - [`osVersion`](#osversion) `String` Indicate the running os version
  - [`osMainVersion`](#osmainversion) `Number` Indicate the running os main version
  - [`browserType`](#browsertype) `String` Indicate the running browser type
  - [`browserVersion`](#browserversion) `String` Indicate the running browser version
  - [`windowPixelResolution`](#windowpixelresolution) `Size` Indicate the real pixel resolution of the whole game window
  - [`localStorage`](#localstorage) `Object` cc.sys.localStorage is a local storage component.
  - [`capabilities`](#capabilities) `Object` The capabilities of the current platform



##### Methods

  - [`glExtension`](#glextension) Is webgl extension support?
  - [`getMaxJointMatrixSize`](#getmaxjointmatrixsize) Get max joint matrix size for skinned mesh renderer.
  - [`getNetworkType`](#getnetworktype) Get the network type of current device, return cc.sys.NetworkType.LAN if failure.
  - [`getBatteryLevel`](#getbatterylevel) Get the battery level of current device, return 1.0 if failure.
  - [`garbageCollect`](#garbagecollect) Forces the garbage collection, only available in JSB
  - [`restartVM`](#restartvm) Restart the JS VM, only available in JSB
  - [`getSafeAreaRect`](#getsafearearect) Return the safe area rect.
  - [`isObjectValid`](#isobjectvalid) In web engine, it will return true if the object exist
  - [`dump`](#dump) Dump system informations
  - [`openURL`](#openurl) Open a url in browser
  - [`now`](#now) Get the number of milliseconds elapsed since 1 January 1970 00:00:00 UTC.



### Details


#### Properties


##### LANGUAGE_ENGLISH

> English language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:52](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L52) |



##### LANGUAGE_CHINESE

> Chinese language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:59](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L59) |



##### LANGUAGE_FRENCH

> French language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:66](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L66) |



##### LANGUAGE_ITALIAN

> Italian language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:73](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L73) |



##### LANGUAGE_GERMAN

> German language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:80](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L80) |



##### LANGUAGE_SPANISH

> Spanish language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:87](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L87) |



##### LANGUAGE_DUTCH

> Spanish language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:94](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L94) |



##### LANGUAGE_RUSSIAN

> Russian language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:101](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L101) |



##### LANGUAGE_KOREAN

> Korean language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:108](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L108) |



##### LANGUAGE_JAPANESE

> Japanese language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:115](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L115) |



##### LANGUAGE_HUNGARIAN

> Hungarian language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:122](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L122) |



##### LANGUAGE_PORTUGUESE

> Portuguese language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:129](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L129) |



##### LANGUAGE_ARABIC

> Arabic language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:136](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L136) |



##### LANGUAGE_NORWEGIAN

> Norwegian language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:143](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L143) |



##### LANGUAGE_POLISH

> Polish language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:150](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L150) |



##### LANGUAGE_TURKISH

> Turkish language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:157](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L157) |



##### LANGUAGE_UKRAINIAN

> Ukrainian language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:164](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L164) |



##### LANGUAGE_ROMANIAN

> Romanian language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:171](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L171) |



##### LANGUAGE_BULGARIAN

> Bulgarian language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:178](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L178) |



##### LANGUAGE_UNKNOWN

> Unknown language code

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:185](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L185) |



##### OS_IOS

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:192](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L192) |



##### OS_ANDROID

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:197](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L197) |



##### OS_WINDOWS

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:202](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L202) |



##### OS_MARMALADE

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:207](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L207) |



##### OS_LINUX

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:212](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L212) |



##### OS_BADA

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:217](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L217) |



##### OS_BLACKBERRY

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:222](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L222) |



##### OS_OSX

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:227](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L227) |



##### OS_WP8

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:232](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L232) |



##### OS_WINRT

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:237](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L237) |



##### OS_UNKNOWN

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:242](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L242) |



##### UNKNOWN

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:248](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L248) |



##### WIN32

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:254](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L254) |



##### LINUX

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:260](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L260) |



##### MACOS

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:266](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L266) |



##### ANDROID

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:272](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L272) |



##### IPHONE

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:278](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L278) |



##### IPAD

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:284](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L284) |



##### BLACKBERRY

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:290](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L290) |



##### NACL

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:296](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L296) |



##### EMSCRIPTEN

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:302](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L302) |



##### TIZEN

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:308](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L308) |



##### WINRT

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:314](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L314) |



##### WP8

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:320](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L320) |



##### MOBILE_BROWSER

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:326](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L326) |



##### DESKTOP_BROWSER

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:332](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L332) |



##### EDITOR_PAGE

> Indicates whether executes in editor's window process (Electron's renderer context)

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:339](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L339) |



##### EDITOR_CORE

> Indicates whether executes in editor's main process (Electron's browser context)

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:346](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L346) |



##### WECHAT_GAME

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:353](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L353) |



##### QQ_PLAY

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:359](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L359) |



##### FB_PLAYABLE_ADS

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:365](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L365) |



##### BAIDU_GAME

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:371](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L371) |



##### VIVO_GAME

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:377](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L377) |



##### OPPO_GAME

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:383](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L383) |



##### HUAWEI_GAME

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:389](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L389) |



##### XIAOMI_GAME

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:395](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L395) |



##### JKW_GAME

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:401](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L401) |



##### BROWSER_TYPE_WECHAT

> BROWSER_TYPE_WECHAT

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:407](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L407) |



##### BROWSER_TYPE_WECHAT_GAME

> BROWSER_TYPE_WECHAT_GAME

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:414](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L414) |



##### BROWSER_TYPE_WECHAT_GAME_SUB

> BROWSER_TYPE_WECHAT_GAME_SUB

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:421](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L421) |



##### BROWSER_TYPE_BAIDU_GAME

> BROWSER_TYPE_BAIDU_GAME

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:428](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L428) |



##### BROWSER_TYPE_BAIDU_GAME_SUB

> BROWSER_TYPE_BAIDU_GAME_SUB

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:435](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L435) |



##### BROWSER_TYPE_XIAOMI_GAME

> BROWSER_TYPE_XIAOMI_GAME

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:442](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L442) |



##### BROWSER_TYPE_QQ_PLAY

> BROWSER_TYPE_QQ_PLAY

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:449](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L449) |



##### BROWSER_TYPE_ANDROID

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:456](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L456) |



##### BROWSER_TYPE_IE

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:463](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L463) |



##### BROWSER_TYPE_QQ

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:470](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L470) |



##### BROWSER_TYPE_MOBILE_QQ

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:477](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L477) |



##### BROWSER_TYPE_UC

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:484](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L484) |



##### BROWSER_TYPE_UCBS

> uc third party integration.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:491](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L491) |



##### BROWSER_TYPE_360

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:498](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L498) |



##### BROWSER_TYPE_BAIDU_APP

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:505](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L505) |



##### BROWSER_TYPE_BAIDU

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:512](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L512) |



##### BROWSER_TYPE_MAXTHON

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:519](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L519) |



##### BROWSER_TYPE_OPERA

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:526](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L526) |



##### BROWSER_TYPE_OUPENG

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:533](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L533) |



##### BROWSER_TYPE_MIUI

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:540](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L540) |



##### BROWSER_TYPE_FIREFOX

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:547](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L547) |



##### BROWSER_TYPE_SAFARI

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:554](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L554) |



##### BROWSER_TYPE_CHROME

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:561](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L561) |



##### BROWSER_TYPE_LIEBAO

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:568](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L568) |



##### BROWSER_TYPE_QZONE

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:575](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L575) |



##### BROWSER_TYPE_SOUGOU

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:582](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L582) |



##### BROWSER_TYPE_UNKNOWN

> 

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:589](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L589) |



##### isNative

> Is native ? This is set to be true in jsb auto.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:597](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L597) |



##### isBrowser

> Is web browser ?

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:604](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L604) |



##### isMobile

> Indicate whether system is mobile system

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:892](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L892) |



##### platform

> Indicate the running platform

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:898](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L898) |



##### languageCode

> Get current language iso 639-1 code.
Examples of valid language codes include "zh-tw", "en", "en-us", "fr", "fr-fr", "es-es", etc.
The actual value totally depends on results provided by destination platform.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:913](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L913) |



##### language

> Indicate the current language of the running system

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:923](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L923) |



##### os

> Indicate the running os name

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:957](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L957) |



##### osVersion

> Indicate the running os version

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:962](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L962) |



##### osMainVersion

> Indicate the running os main version

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:967](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L967) |



##### browserType

> Indicate the running browser type

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:973](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L973) |



##### browserVersion

> Indicate the running browser version

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:1010](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L1010) |



##### windowPixelResolution

> Indicate the real pixel resolution of the whole game window

| meta | description |
|------|-------------|
| Type | <a href="../classes/Size.html" class="crosslink">Size</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:1028](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L1028) |



##### localStorage

> cc.sys.localStorage is a local storage component.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:1061](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L1061) |



##### capabilities

> The capabilities of the current platform

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> |
| Defined in | [cocos2d/core/platform/CCSys.js:1095](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L1095) |






<!-- Method Block -->
#### Methods


##### glExtension

Is webgl extension support?

| meta | description |
|------|-------------|
| Defined in | [cocos2d/core/platform/CCSys.js:610](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L610) |

###### Parameters
- `name` Unknown 


##### getMaxJointMatrixSize

Get max joint matrix size for skinned mesh renderer.

| meta | description |
|------|-------------|
| Defined in | [cocos2d/core/platform/CCSys.js:622](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L622) |



##### getNetworkType

Get the network type of current device, return cc.sys.NetworkType.LAN if failure.

| meta | description |
|------|-------------|
| Returns | <a href="../enums/NetworkType.html" class="crosslink">NetworkType</a> 
| Defined in | [cocos2d/core/platform/CCSys.js:1246](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L1246) |



##### getBatteryLevel

Get the battery level of current device, return 1.0 if failure.

| meta | description |
|------|-------------|
| Returns | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
| Defined in | [cocos2d/core/platform/CCSys.js:1260](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L1260) |



##### garbageCollect

Forces the garbage collection, only available in JSB

| meta | description |
|------|-------------|
| Defined in | [cocos2d/core/platform/CCSys.js:1274](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L1274) |



##### restartVM

Restart the JS VM, only available in JSB

| meta | description |
|------|-------------|
| Defined in | [cocos2d/core/platform/CCSys.js:1282](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L1282) |



##### getSafeAreaRect

Return the safe area rect. <br/>
only available on the iOS native platform, otherwise it will return a rect with design resolution size.

| meta | description |
|------|-------------|
| Returns | <a href="../classes/Rect.html" class="crosslink">Rect</a> 
| Defined in | [cocos2d/core/platform/CCSys.js:1290](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L1290) |



##### isObjectValid

Check whether an object is valid,
In web engine, it will return true if the object exist
In native engine, it will return true if the JS object and the correspond native object are both valid

| meta | description |
|------|-------------|
| Returns | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 
| Defined in | [cocos2d/core/platform/CCSys.js:1304](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L1304) |

###### Parameters
- `obj` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 


##### dump

Dump system informations

| meta | description |
|------|-------------|
| Defined in | [cocos2d/core/platform/CCSys.js:1319](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L1319) |



##### openURL

Open a url in browser

| meta | description |
|------|-------------|
| Defined in | [cocos2d/core/platform/CCSys.js:1338](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L1338) |

###### Parameters
- `url` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> 


##### now

Get the number of milliseconds elapsed since 1 January 1970 00:00:00 UTC.

| meta | description |
|------|-------------|
| Returns | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
| Defined in | [cocos2d/core/platform/CCSys.js:1352](https://github.com/cocos-creator/engine/blob/b4415d3f111db35eb92e588d63bcb560003ea469/cocos2d/core/platform/CCSys.js#L1352) |




