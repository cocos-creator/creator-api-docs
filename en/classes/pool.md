## `Pool` Class



Module: [cc](../modules/cc.md)
Parent Module: [js](../modules/js.md)


A fixed-length object pool designed for general type.<br>
The implementation of this object pool is very simple,
it can helps you to improve your game performance for objects which need frequent release and recreate operations<br/>


### Index

##### Properties

  - [`count`](#count) `Number` The current number of available objects, the default is 0, it will gradually increase with the recycle of the object,...



##### Methods

  - [`constructor`](#constructor) Constructor for creating an object pool for the specific object type.
  - [`get`](#get) Get and initialize an object from pool.
  - [`_get`](#get) Get an object from pool, if no available object in the pool, null will be returned.
  - [`put`](#put) Put an object into the pool.
  - [`resize`](#resize) Resize the pool.



### Details


#### Properties


##### count

> The current number of available objects, the default is 0, it will gradually increase with the recycle of the object,
the maximum will not exceed the size specified when the constructor is called.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/core/platform/js.js:897](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/core/platform/js.js#L897) |






<!-- Method Block -->
#### Methods


##### constructor

Constructor for creating an object pool for the specific object type.
You can pass a callback argument for process the cleanup logic when the object is recycled.

| meta | description |
|------|-------------|
| Defined in | [cocos2d/core/platform/js.js:862](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/core/platform/js.js#L862) |

###### Parameters
- `cleanupFunc` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Function" class="crosslink external" target="_blank">Function</a> the callback method used to process the cleanup logic when the object is recycled.
	- `obj` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 
- `size` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> initializes the length of the array


##### get

Get and initialize an object from pool. This method defaults to null and requires the user to implement it.

| meta | description |
|------|-------------|
| Returns | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 
| Defined in | [cocos2d/core/platform/js.js:887](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/core/platform/js.js#L887) |

###### Parameters
- `params` Any parameters to used to initialize the object


##### _get

Get an object from pool, if no available object in the pool, null will be returned.

| meta | description |
|------|-------------|
| Returns | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> &#124; Null 
| Defined in | [cocos2d/core/platform/js.js:907](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/core/platform/js.js#L907) |



##### put

Put an object into the pool.

| meta | description |
|------|-------------|
| Defined in | [cocos2d/core/platform/js.js:925](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/core/platform/js.js#L925) |



##### resize

Resize the pool.

| meta | description |
|------|-------------|
| Defined in | [cocos2d/core/platform/js.js:941](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/core/platform/js.js#L941) |




