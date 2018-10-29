Project Base
====
## Requirement
1. cmake
2. conan - package manager
```bash
pip3 install conan
```
3. download package
```bash
mkdir build && cd build
conan install .. -s build_type=Debug
```

## Configure
```bash
cd build
cmake .. -G "Visual Studio 15 2017 Win64"
```

## Build
```bash
cd build
cmake --build .
```

## Thirdparty
1. GLFW3
2. ImGui