### OpenCV.js WASM binaries
In this repo you can find my own build of OpenCV.js built with Emscripten and the build_js.py script from the OpenCV source files.

## Current version
The previously mentioned binaries are built from OpenCV 3.4.5 source files. The repository will be updated later to keep up with the newer releases of OpenCV 3.

## Compiling options
Here are the compiling options I used to build the binaries:
- USE_PTHREADS=0
- ASSERTIONS=1
- DISABLE_EXCEPTION_CATCHING=0
- WASM=1 (corresponds to the flag --build_wasm when calling the build_js.py script)