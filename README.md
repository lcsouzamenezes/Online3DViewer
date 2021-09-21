# Online 3D Viewer

Online 3D Viewer (https://3dviewer.net) is a free and open source web solution to visualize and explore 3D models right in your browser. This repository contains the source code of the website and the library behind it.

[![Build status](https://ci.appveyor.com/api/projects/status/exypq43a8kjby5n0?svg=true)](https://ci.appveyor.com/project/kovacsv/online3dviewer)
[![Build status](https://github.com/kovacsv/Online3DViewer/actions/workflows/build.yml/badge.svg)](https://github.com/kovacsv/Online3DViewer/actions/workflows/build.yml)
[![Language grade: JavaScript](https://img.shields.io/lgtm/grade/javascript/g/kovacsv/Online3DViewer.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/kovacsv/Online3DViewer/context:javascript)

![Start Page](assets/images/3dviewer_net_start_page.png?raw=true)

[Check the live version!](https://3dviewer.net/#model=https://raw.githubusercontent.com/kovacsv/Online3DViewer/dev/test/testfiles/gltf/DamagedHelmet/glTF-Binary/DamagedHelmet.glb)

## Documentation

The repository is separated into two parts. See more information in the [Developer Documentation](https://github.com/kovacsv/Online3DViewer/wiki).

* **Online 3D Viewer Website**: Source code of the web solution with all of the pages and functions.
* **Online 3D Viewer Engine**: Source code of the library to visualize models easily.

## Supported file formats

### Import

- obj (with mtl and texture)
- 3ds (with texture)
- stl (text and binary)
- ply (text and binary)
- gltf (text and binary)
- 3dm (experimental)
- fbx (experimental)
- off (text only)

### Export

- obj (with mtl)
- stl (text and binary)
- ply (text and binary)
- gltf (text and binary)
- 3dm (experimental)
- off (text only)

## Features

- Load model:
  - Select files from a file browser dialog.
  - Drag and drop files from your computer.
  - Specify files by web url.
  - Specify files by web url in hash parameters.
- Explore model:
  - Orbit, pan, zoom.
  - Set up direction.
  - Fit to window.
- Investigate model:
  - List used and missing files.
  - List all materials and meshes.
  - Show/hide and zoom to a specific mesh.
  - List materials used by a specific mesh.
  - Show model information (model size, vertex and polygon count).
  - Show custom properties stored in the model.
- Export model to various format.
- Embed viewer in your website.

## External Libraries

Online 3D Viewer uses these wonderful libraries: [three.js](https://github.com/mrdoob/three.js), [assimpjs](https://github.com/kovacsv/assimpjs), [jquery](https://github.com/jquery/jquery), [pickr](https://github.com/Simonwep/pickr), [fflate](https://github.com/101arrowz/fflate), [draco](https://github.com/google/draco), [rhino3dm](https://github.com/mcneel/rhino3dm), [web-ifc](https://github.com/tomvandig/web-ifc).
