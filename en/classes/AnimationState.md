## `AnimationState` Class

Extends [`Playable`](Playable.md)


Module: [cc](../modules/cc.md)


The AnimationState gives full control over animation playback process.
In most cases the Animation Component is sufficient and easier to use. Use the AnimationState if you need full control.


### Index

##### Properties

  - [`animator`](#animator) `AnimationAnimator` 
  - [`curves`](#curves) `Object[]` The curves list.
  - [`delay`](#delay) `Number` The start delay which represents the number of seconds from an animation's start time to the start of
  - [`repeatCount`](#repeatcount) `Number` The animation's iteration count property.
  - [`duration`](#duration) `Number` The iteration duration of this animation in seconds.
  - [`speed`](#speed) `Number` The animation's playback speed.
  - [`wrapMode`](#wrapmode) `WrapMode` Wrapping mode of the playing animation.
  - [`time`](#time) `Number` The current time of this animation in seconds.
  - [`clip`](#clip) `AnimationClip` The clip that is being played by this animation state.
  - [`name`](#name) `String` The name of the playing animation.
  - [`isPlaying`](#isplaying) `Boolean` Is playing or paused in play mode?
  - [`isPaused`](#ispaused) `Boolean` Is currently paused? This can be true even if in edit mode(isPlaying == false).



##### Methods

  - [`constructor`](#constructor) 
  - [`onPlay`](#onplay) 
  - [`onPause`](#onpause) 
  - [`onResume`](#onresume) 
  - [`onStop`](#onstop) 
  - [`onError`](#onerror) 
  - [`play`](#play) Play this animation.
  - [`stop`](#stop) Stop this animation.
  - [`pause`](#pause) Pause this animation.
  - [`resume`](#resume) Resume this animation.
  - [`step`](#step) Perform a single frame step.



### Details


#### Properties


##### animator

> 

| meta | description |
|------|-------------|
| Type | AnimationAnimator |
| Defined in | [cocos2d/animation/animation-state.js:74](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/animation-state.js#L74) |



##### curves

> The curves list.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object[]</a> |
| Defined in | [cocos2d/animation/animation-state.js:80](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/animation-state.js#L80) |



##### delay

> The start delay which represents the number of seconds from an animation's start time to the start of
the active interval.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/animation/animation-state.js:90](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/animation-state.js#L90) |



##### repeatCount

> The animation's iteration count property.

A real number greater than or equal to zero (including positive infinity) representing the number of times
to repeat the animation node.

Values less than zero and NaN values are treated as the value 1.0 for the purpose of timing model
calculations.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/animation/animation-state.js:101](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/animation-state.js#L101) |



##### duration

> The iteration duration of this animation in seconds. (length)

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/animation/animation-state.js:118](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/animation-state.js#L118) |



##### speed

> The animation's playback speed. 1 is normal playback speed.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/animation/animation-state.js:128](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/animation-state.js#L128) |



##### wrapMode

> Wrapping mode of the playing animation.
Notice : dynamic change wrapMode will reset time and repeatCount property

| meta | description |
|------|-------------|
| Type | <a href="../enums/WrapMode.html" class="crosslink">WrapMode</a> |
| Defined in | [cocos2d/animation/animation-state.js:137](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/animation-state.js#L137) |



##### time

> The current time of this animation in seconds.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> |
| Defined in | [cocos2d/animation/animation-state.js:151](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/animation-state.js#L151) |



##### clip

> The clip that is being played by this animation state.

| meta | description |
|------|-------------|
| Type | <a href="../classes/AnimationClip.html" class="crosslink">AnimationClip</a> |
| Defined in | [cocos2d/animation/animation-state.js:402](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/animation-state.js#L402) |



##### name

> The name of the playing animation.

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> |
| Defined in | [cocos2d/animation/animation-state.js:413](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/animation-state.js#L413) |



##### isPlaying

> Is playing or paused in play mode?

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined in | [cocos2d/animation/playable.js:43](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/playable.js#L43) |



##### isPaused

> Is currently paused? This can be true even if in edit mode(isPlaying == false).

| meta | description |
|------|-------------|
| Type | <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> |
| Defined in | [cocos2d/animation/playable.js:55](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/playable.js#L55) |






<!-- Method Block -->
#### Methods


##### constructor



| meta | description |
|------|-------------|
| Defined in | [cocos2d/animation/animation-state.js:50](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/animation-state.js#L50) |

###### Parameters
- `clip` <a href="../classes/AnimationClip.html" class="crosslink">AnimationClip</a> 
- `name` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">String</a> 


##### onPlay



| meta | description |
|------|-------------|
| Defined in | [cocos2d/animation/playable.js:70](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/playable.js#L70) |



##### onPause



| meta | description |
|------|-------------|
| Defined in | [cocos2d/animation/playable.js:75](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/playable.js#L75) |



##### onResume



| meta | description |
|------|-------------|
| Defined in | [cocos2d/animation/playable.js:80](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/playable.js#L80) |



##### onStop



| meta | description |
|------|-------------|
| Defined in | [cocos2d/animation/playable.js:85](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/playable.js#L85) |



##### onError



| meta | description |
|------|-------------|
| Defined in | [cocos2d/animation/playable.js:90](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/playable.js#L90) |

###### Parameters
- `errorCode` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/String" class="crosslink external" target="_blank">string</a> 


##### play

Play this animation.

| meta | description |
|------|-------------|
| Defined in | [cocos2d/animation/playable.js:99](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/playable.js#L99) |



##### stop

Stop this animation.

| meta | description |
|------|-------------|
| Defined in | [cocos2d/animation/playable.js:120](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/playable.js#L120) |



##### pause

Pause this animation.

| meta | description |
|------|-------------|
| Defined in | [cocos2d/animation/playable.js:135](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/playable.js#L135) |



##### resume

Resume this animation.

| meta | description |
|------|-------------|
| Defined in | [cocos2d/animation/playable.js:147](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/playable.js#L147) |



##### step

Perform a single frame step.

| meta | description |
|------|-------------|
| Defined in | [cocos2d/animation/playable.js:159](https://github.com/cocos-creator/engine/blob/de46973d0b5edcff4f973186ce89752080cb6b7c/cocos2d/animation/playable.js#L159) |




