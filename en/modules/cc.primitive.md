
## `cc.primitive` Module






一个创建 3D 物体顶点数据的基础模块，你可以通过 "cc.primitive" 来访问这个模块。





### Index



##### Methods

  - [`box`](#box) Create box vertex data
  - [`cone`](#cone) Create cone vertex data
  - [`cylinder`](#cylinder) Create cylinder vertex data
  - [`plane`](#plane) Create plane vertex data
  - [`quad`](#quad) Create quad vertex data
  - [`sphere`](#sphere) Create sphere vertex data
  - [`torus`](#torus) Create torus vertex data
  - [`capsule`](#capsule) Create capsule vertex data
  - [`polyhedron`](#polyhedron) Create polyhedron vertex data



### Details




<!-- Method Block -->
#### Methods


##### box

Create box vertex data

| meta | description |
|------|-------------|
| Returns | <a href="../classes/primitive.VertexData.html" class="crosslink">primitive.VertexData</a> 
| Defined in | [cocos2d/core/3d/primitive/index.js:24](https://github.com/cocos-creator/engine/blob/9fcea4ca5a6c5c1d8ce45ebc6ba7ad7d1b723f25/cocos2d/core/3d/primitive/index.js#L24) |

###### Parameters
- `width` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `height` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `length` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `opts` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 
	- `widthSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `heightSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `lengthSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 


##### cone

Create cone vertex data

| meta | description |
|------|-------------|
| Returns | <a href="../classes/primitive.VertexData.html" class="crosslink">primitive.VertexData</a> 
| Defined in | [cocos2d/core/3d/primitive/index.js:39](https://github.com/cocos-creator/engine/blob/9fcea4ca5a6c5c1d8ce45ebc6ba7ad7d1b723f25/cocos2d/core/3d/primitive/index.js#L39) |

###### Parameters
- `radius` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `height` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `opts` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 
	- `radialSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `heightSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `capped` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 
	- `arc` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 


##### cylinder

Create cylinder vertex data

| meta | description |
|------|-------------|
| Returns | <a href="../classes/primitive.VertexData.html" class="crosslink">primitive.VertexData</a> 
| Defined in | [cocos2d/core/3d/primitive/index.js:54](https://github.com/cocos-creator/engine/blob/9fcea4ca5a6c5c1d8ce45ebc6ba7ad7d1b723f25/cocos2d/core/3d/primitive/index.js#L54) |

###### Parameters
- `radiusTop` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `radiusBottom` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `height` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `opts` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 
	- `radialSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `heightSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `capped` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 
	- `arc` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 


##### plane

Create plane vertex data

| meta | description |
|------|-------------|
| Returns | <a href="../classes/primitive.VertexData.html" class="crosslink">primitive.VertexData</a> 
| Defined in | [cocos2d/core/3d/primitive/index.js:70](https://github.com/cocos-creator/engine/blob/9fcea4ca5a6c5c1d8ce45ebc6ba7ad7d1b723f25/cocos2d/core/3d/primitive/index.js#L70) |

###### Parameters
- `width` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `length` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `opts` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 
	- `widthSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `lengthSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 


##### quad

Create quad vertex data

| meta | description |
|------|-------------|
| Returns | <a href="../classes/primitive.VertexData.html" class="crosslink">primitive.VertexData</a> 
| Defined in | [cocos2d/core/3d/primitive/index.js:83](https://github.com/cocos-creator/engine/blob/9fcea4ca5a6c5c1d8ce45ebc6ba7ad7d1b723f25/cocos2d/core/3d/primitive/index.js#L83) |



##### sphere

Create sphere vertex data

| meta | description |
|------|-------------|
| Returns | <a href="../classes/primitive.VertexData.html" class="crosslink">primitive.VertexData</a> 
| Defined in | [cocos2d/core/3d/primitive/index.js:91](https://github.com/cocos-creator/engine/blob/9fcea4ca5a6c5c1d8ce45ebc6ba7ad7d1b723f25/cocos2d/core/3d/primitive/index.js#L91) |

###### Parameters
- `radius` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `opts` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 
	- `segments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 


##### torus

Create torus vertex data

| meta | description |
|------|-------------|
| Returns | <a href="../classes/primitive.VertexData.html" class="crosslink">primitive.VertexData</a> 
| Defined in | [cocos2d/core/3d/primitive/index.js:102](https://github.com/cocos-creator/engine/blob/9fcea4ca5a6c5c1d8ce45ebc6ba7ad7d1b723f25/cocos2d/core/3d/primitive/index.js#L102) |

###### Parameters
- `radius` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `tube` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `opts` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 
	- `radialSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `tubularSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `arc` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 


##### capsule

Create capsule vertex data

| meta | description |
|------|-------------|
| Returns | <a href="../classes/primitive.VertexData.html" class="crosslink">primitive.VertexData</a> 
| Defined in | [cocos2d/core/3d/primitive/index.js:116](https://github.com/cocos-creator/engine/blob/9fcea4ca5a6c5c1d8ce45ebc6ba7ad7d1b723f25/cocos2d/core/3d/primitive/index.js#L116) |

###### Parameters
- `radiusTop` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `radiusBottom` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `height` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `opts` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 
	- `sides` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `heightSegments` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `capped` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Boolean" class="crosslink external" target="_blank">Boolean</a> 
	- `arc` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 


##### polyhedron

Create polyhedron vertex data

| meta | description |
|------|-------------|
| Returns | <a href="../classes/primitive.VertexData.html" class="crosslink">primitive.VertexData</a> 
| Defined in | [cocos2d/core/3d/primitive/index.js:132](https://github.com/cocos-creator/engine/blob/9fcea4ca5a6c5c1d8ce45ebc6ba7ad7d1b723f25/cocos2d/core/3d/primitive/index.js#L132) |

###### Parameters
- `type` <a href="../enums/primitive.PolyhedronType.html" class="crosslink">primitive.PolyhedronType</a> 
- `Size` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
- `opts` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Object" class="crosslink external" target="_blank">Object</a> 
	- `sizeX` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `sizeY` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 
	- `sizeZ` <a href="https://developer.mozilla.org/en/JavaScript/Reference/Global_Objects/Number" class="crosslink external" target="_blank">Number</a> 



