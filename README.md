# cpp-hello-world
Simple C++ Hello World Example Project with CMake

# Build Instructions
## Windows

- Create a directory called build within this repository's root directory.

- From the root directory, execute the following command:
```PowerShell
cmake -G "MinGW Makefiles" -B .\build
```

- Then run:
```PowerShell
cmake --build .\build
```

- HelloWorld.exe can now be found in the .\build folder.