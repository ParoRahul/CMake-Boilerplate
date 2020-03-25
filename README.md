# CMake-Boilerplate
CMake Boilerplate with vcpkg package manager And VS code CMake tools Extension 

include the Following Lines cmake instruction in Workspace/User Settinngs.json
    
    ```"cmake.sourceDirectory": "${workspaceFolder}",
    "cmake.cmakeToolchain" : "vcpkg/scripts/buildsystems/vcpkg.cmake",
    "cmake.configureSettings": {
        "VCPKG_TARGET_TRIPLET" : "x86-windows",
        "CMAKE_TOOLCHAIN_FILE"  : "vcpkg/scripts/buildsystems/vcpkg.cmake",
    },
    "cmake.platform": "x86", ```
