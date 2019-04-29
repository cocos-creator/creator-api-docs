## `textureCache` 类型



模块: [cc](../modules/cc.md)
父模块: [cc](../modules/cc.md)


cc.textureCache is a singleton object, it's the global cache for cc.Texture2D


### 索引



##### 方法

  - [`description`](#description) Description
  - [`getTextureForKey`](#gettextureforkey) Returns an already created texture. Returns null if the texture doesn't exist.
  - [`getTextureColors`](#gettexturecolors) 
  - [`getAllTextures`](#getalltextures) 获取所有贴图
  - [`removeAllTextures`](#removealltextures) <p>Purges the dictionary of loaded textures. <br />...
  - [`removeTexture`](#removetexture) Deletes a texture from the cache given a texture.
  - [`removeTextureForKey`](#removetextureforkey) Deletes a texture from the cache given a its key name.
  - [`addImage`](#addimage) If the file image was not previously loaded, it will create a new Texture2D
  - [`cacheImage`](#cacheimage) Cache the image data.



### Details




<!-- Method Block -->
#### 方法


##### description

Description

| meta | description |
|------|-------------|
| 返回 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> 
| 定义于 | [cocos2d/core/textures/CCTextureCache.js:44](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/core/textures/CCTextureCache.js#L44) |



##### getTextureForKey

Returns an already created texture. Returns null if the texture doesn't exist.

| meta | description |
|------|-------------|
| 返回 | <a href="../classes/Texture2D.html" class="crosslink">Texture2D</a> &#124; Null 
| 定义于 | [cocos2d/core/textures/CCTextureCache.js:53](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/core/textures/CCTextureCache.js#L53) |

###### 参数列表
- `textureKeyName` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> 

##### 示例

```js
------------------
var key = cc.textureCache.getTextureForKey("hello.png");

```

##### getTextureColors



| meta | description |
|------|-------------|
| 返回 | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Array" class="crosslink external" target="_blank">Array</a> 
| 定义于 | [cocos2d/core/textures/CCTextureCache.js:83](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/core/textures/CCTextureCache.js#L83) |

###### 参数列表
- `texture` HTMLImageElement 

##### 示例

```js
---------------
var cacheTextureForColor = cc.textureCache.getTextureColors(texture);

```

##### getAllTextures

获取所有贴图

| meta | description |
|------|-------------|
| 返回 | <a href="../classes/Texture2D.html" class="crosslink">Texture2D[]</a> 
| 定义于 | [cocos2d/core/textures/CCTextureCache.js:104](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/core/textures/CCTextureCache.js#L104) |



##### removeAllTextures

<p>Purges the dictionary of loaded textures. <br />
Call this method if you receive the "Memory Warning"  <br />
In the short term: it will free some resources preventing your app from being killed  <br />
In the medium term: it will allocate more resources <br />
In the long term: it will be the same</p>

| meta | description |
|------|-------------|
| 定义于 | [cocos2d/core/textures/CCTextureCache.js:119](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/core/textures/CCTextureCache.js#L119) |


##### 示例

```js
--------
cc.textureCache.removeAllTextures();

```

##### removeTexture

Deletes a texture from the cache given a texture.

| meta | description |
|------|-------------|
| 定义于 | [cocos2d/core/textures/CCTextureCache.js:137](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/core/textures/CCTextureCache.js#L137) |

###### 参数列表
- `texture` HTMLImageElement 

##### 示例

```js
-----
cc.textureCache.removeTexture(texture);

```

##### removeTextureForKey

Deletes a texture from the cache given a its key name.

| meta | description |
|------|-------------|
| 定义于 | [cocos2d/core/textures/CCTextureCache.js:156](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/core/textures/CCTextureCache.js#L156) |

###### 参数列表
- `textureKeyName` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> 

##### 示例

```js
------
cc.textureCache.removeTexture("hello.png");

```

##### addImage

Returns a Texture2D object given an file image <br />
If the file image was not previously loaded, it will create a new Texture2D
object and it will return it. It will use the filename as a key.
Otherwise it will return a reference of a previously loaded image. <br />
Supported image extensions: .png, .jpg, .gif

| meta | description |
|------|-------------|
| 返回 | <a href="../classes/Texture2D.html" class="crosslink">Texture2D</a> 
| 定义于 | [cocos2d/core/textures/CCTextureCache.js:178](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/core/textures/CCTextureCache.js#L178) |

###### 参数列表
- `url` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> 
- `cb` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a> 
- `target` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 

##### 示例

```js
----
cc.textureCache.addImage("hello.png");

```

##### cacheImage

Cache the image data.

| meta | description |
|------|-------------|
| 定义于 | [cocos2d/core/textures/CCTextureCache.js:229](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/core/textures/CCTextureCache.js#L229) |

###### 参数列表
- `path` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> 
- `texture` HTMLImageElement &#124; HTMLCanvasElement 



