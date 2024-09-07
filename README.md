# Metal C++ Headers

## Use - CMake

To use with CMake, you will need to add the headers as a subdirectory, so that they are visible to the compiler.

```CMake
add_exectable(whatever main.cpp)

add_subdirectory(<</package/install/location>>)
target_link_libraries(whatever METAL_CPP)
```

## Use - g++/clang++

IDK + IDC