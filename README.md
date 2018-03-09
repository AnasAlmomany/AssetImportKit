<p align="center">
    <img src="Media/AssetImportKit.png", width="844">
</p>

[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

**AssetImportKit** is a cross platform library (macOS, iOS) that coverts the files supported by [`Assimp`](https://github.com/assimp/assimp) to [`SceneKit`](https://developer.apple.com/reference/scenekit) scenes.

<p align="center">
    <img src="Media/AssetImportKit_Demonstration.png", width="818">
</p>

Features
---

AssetImportKit allows you to import ***Assimp supported file formats*** directly in SceneKit at runtime.
The library supports:
* Geometry
* Materials (with color, embedded textures and external textures)
* Cameras and
* Skeletal animations.
* Serialization to `.scn` format

#### Supported file formats ####

AssetImportKit supports the following file formats:
3D, 3DS, 3MF, AC, AC3D, ACC, AMJ, ASE, ASK, B3D, BLEND (Blender), BVH, COB, CMS, DAE/Collada, DXF, ENFF, FBX, glTF 1.0 + GLB, glTF 2.0, HMB, IFC-STEP, IRR / IRRMESH, LWO, LWS, LXO, MD2, MD3, MD5, MDC, MDL, MESH / MESH.XML, MOT, MS3D, NDO, NFF, OBJ, OFF, OGEX, PLY, PMX, PRJ, Q3O, Q3S, RAW, SCN, SIB, SMD, STL, STP, TER, UC, VTA, X, X3D, XGL, ZGL.

Demos
---
This repository includes 2 small demos for macOS and iOS.

<a href="3DViewer/README.md"><img src="Media/iOS Example App.png" width=50%></a><a href="SceneKitAssetImport/README.md"><img src="Media/macOS Example App.png" width=50%></a>

Requirements
---

- Xcode 9.0 or later
- Swift 4
- iOS 11.0 or later
- macOS 10.12 or later

Usage
---

Read the [`how-to-install`](HowToInstall.md) guide.

Carthage support will be added in future.

Note for `iOS` builds: if you are developing an `iOS` application, set the `Enable Bitcode` under `Build Settings->Build Options` of your target to `NO`.

License
---

[AssetImportKit's license](LICENSE.md) is based on the modified, 3-clause BSD-License.
