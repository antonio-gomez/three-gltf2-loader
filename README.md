## Three-glTF2-loader

[![npm-image](https://img.shields.io/badge/npm-v1.2.0-ff69b4.svg)](https://www.npmjs.com/package/three-gltf2-loader)
![version-image](https://img.shields.io/badge/license-MIT-ff69b4.svg)


#### Install
--------

```
npm install three-gltf2-loader --save
```


#### Description
-----------

Node.js wrapper for the **GLTF2Loader** library from [three.js][0] so that it can be installed through npm and used with bundle libraries like webpack, browserify, etc.

[glTF](1) (Graphic Library Transmission Format) was developed and mantained by [KhronosGroup](2) as the specification for efficient transmission and loading of 3D scenes and models by **WebGL**, **OpenGL ES**, and **OpenGL** applications.



#### Usage
--------

```
import THREE from 'three'
import GLTF2Loader from 'three-gltf2-loader'

GLTF2Loader(THREE)

console.log(typeof THREE.GLTF2Loader)
// => "function"
```


#### Changelog
--------

**1.2.0 (Oct 22 2017)**
* Updated to latest glTF loader from Three.js r87.

**1.1.0 (Jun 28 2017)**
* Updated to latest glTF spec from Three.js r86.

**1.0.0 (Mar 24 2017)**
* Main module functionality.

**0.0.0 (Mar 21 2017)**
* Initial development.


--------
## License
MIT © [Antonio Gomez][3]

[0]: https://github.com/mrdoob/three.js
[1]: https://github.com/KhronosGroup/glTF
[2]: https://www.khronos.org
[3]: http://antoniogomez.me/