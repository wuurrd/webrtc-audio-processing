# About

The AudioProcessing module from WebRTC[1][2]

[1] http://code.google.com/p/webrtc/
[2] https://chromium.googlesource.com/external/webrtc/trunk/webrtc.git

# Build

1. Install Meson: http://mesonbuild.com/Getting-meson.html
2. Install Ninja: https://github.com/ninja-build/ninja/releases
3. Open a Terminal / Visual Studio Command Prompt and run:

```
mkdir build
cd build
meson ../
ninja
```

* To specify a build type, use `meson ../ --buildtype=debug` or `meson ../ --buildtype=release`
* To cross-build for another platform, use `meson ../ --cross-file xxx.txt`
