## .vscode
### c_cpp_properties.json
``` 
    {
        "configurations": [
            {
                "name": "DKP aarch64",
                "includePath": [
                    "${env:DEVKITPRO}/devkitA64/aarch64-none-elf/include/**",
                    "${env:DEVKITPRO}/devkitA64/lib/gcc/aarch64-none-elf/10.1.0/include/**",
                    "${env:DEVKITPRO}/libnx/include/**",
                    "${env:DEVKITPRO}/portlibs/switch/include/**"
                ],
                "defines": [
                    "SWITCH",
                    "__SWITCH__",
                    "DEBUG"
                ],
                "compilerPath": "/opt/devkitpro/devkitA64/bin/aarch64-none-elf-g++",
                "cStandard": "c11",
                "cppStandard": "c++17",
                "intelliSenseMode": "gcc-x64"
            }
        ],
        "version": 4
    }
```