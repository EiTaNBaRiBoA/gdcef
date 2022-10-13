# Chromium Embedded Framework as Godot 3.4+ native module

This repository contains the source code of some C++ classes wrapping a subset
of the [Chromium Embedded Framework](https://bitbucket.org/chromiumembedded/cef/wiki/Home)
API into a Godot 3.4+ native module (GDNative) which allows you to
implement a web browser for your 2D and 3D games through your gdscripts for
Linux and Windows. We have named this CEF GDNative module `gdcef`.

This module can be downloaded directly from the Godot asset library:

https://godotengine.org/asset-library/asset/1426

*Note:* This current repository is a fork of [the following
repo](https://github.com/stigmee/gdnative-cef) (under GPLv3) with a more
permissive license (MIT). Since the original repo is no longer maintained
by their two original authors (Alain and Quentin), we, the undersigned Alain
and Quentin, gave consent to relicensing the original code under the
MIT license.

## Complete documentation

Since this document is not taken when importing this module from the Godot asset
library, all details are referred in the following
[document](addons/gdcef/doc/README.md) which explains you how to build
this module, how to run demos, describe the architecture, details design and
more ...

**TL;DR:** Compile this project with the Python3 build script:
```
cd addons/gdcef
./build.py
```

Generated artifacts are in the `build/` folder. Use this folder in your Godot
project and add gdns and gdnlib files to refer `build/libgdcef.so/dll`. See
demos given with this repo.

## Gallery

Projects interested in / using this module. Please do not hesitate to share your
project links and pictures by making a GitHub pull request.

- https://elitemeta.city/

Click to see on the image to see the Elitemeta video shared on IPFS.
[![elitemeta](addons/gdcef/doc/gallery/elitemeta.jpg)](https://ipfs.io/ipfs/QmaL7NY5qs3AtAdcX8vFhqaHwJeTMKfP3PbzcHZBLmo1QQ?filename=elitemeta_0.mp4)
Thanks to the team for having shared this video.

