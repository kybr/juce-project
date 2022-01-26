# JUCE CMake project example

## Getting started

```
git clone https://github.com/kybr/juce-project
cd juce-project
git clone https://github.com/juce-framework/JUCE
cp JUCE/examples/CMake/AudioPlugin/* .
# edit CMakeLists.txt; uncomment "add_subdirectory(JUCE)"
mkdir build
cmake ..
cmake --build .
# see AudioPluginExample_artefacts/
```

Edit the CMakeLists.txt file to configure the project.

## VSCode...

Install the c++ intellisense extension.

Add this to your `c_cpp_properties.json`:

```
                "${workspaceFolder}",
                "${workspaceFolder}/JUCE/modules/**"
```
