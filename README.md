# JUCE CMake project example

## Getting started

```
git clone juce-project
cd juce-project
git clone https://github.com/juce-framework/JUCE
cp JUCE/examples/CMake/AudioPlugin/* .
# edit CMakeLists.txt; uncomment "add_subdirectory(JUCE)"
mkdir build
cmake ..
cmake --build .
```

## VSCode...

Install the c++ intellisense extension.

Add this to your `c_cpp_properties.json`:

```
                "${workspaceFolder}",
                "${workspaceFolder}/JUCE/modules/**"
```