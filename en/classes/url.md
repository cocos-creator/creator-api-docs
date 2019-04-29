## `url` Class



Module: [cc](../modules/cc.md)
Parent Module: [cc](../modules/cc.md)






### Index

##### Properties

  - [`_rawAssets`](#rawassets) `Object` The base url of raw assets.



##### Methods

  - [`raw`](#raw) Returns the url of raw assets, you will only need this if the raw asset is inside the "resources" folder.



### Details


#### Properties


##### _rawAssets

> The base url of raw assets.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> |
| Defined in | [cocos2d/core/platform/url.js:36](https://github.com/cocos-creator/engine/blob/18c4ff6051c255c06377a9b26bc00d4567180ae4/cocos2d/core/platform/url.js#L36) |






<!-- Method Block -->
#### Methods


##### raw

Returns the url of raw assets, you will only need this if the raw asset is inside the "resources" folder.

| meta | description |
|------|-------------|
| Returns | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> 
| Defined in | [cocos2d/core/platform/url.js:58](https://github.com/cocos-creator/engine/blob/18c4ff6051c255c06377a9b26bc00d4567180ae4/cocos2d/core/platform/url.js#L58) |

###### Parameters
- `url` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> 

##### Examples

```js
---
var url = cc.url.raw("textures/myTexture.png");
console.log(url);   // "resources/raw/textures/myTexture.png"

```


