# Setup info

## Adding the Search Paths

Add `/usr/local/include` and `/Users/paul.sohns/VulkanSDK/1.3.236.0/macOS/include` to `Header Search Paths` for Development as well as Release.
Add `/usr/local/lib` and `/Users/paul.sohns/VulkanSDK/1.3.236.0/macOS/lib` to `Library Search Paths` for Development as well as Release.

## Linking the binaries

1) Open the `Build Phases` tab in xCode and navigate to `Link Binary With Libraries`
2) Open the folder `usr/local/lib` and drag the file `libglfw.3.x.dylib` into the table
3) Open the folder `/Users/paul.sohns/VulkanSDK/1.3.236.0/macOS/lib` and drag the files `libvulkan.1.dylib` and `libvulkan.1.x.xx.dylib` into the table
4) Go to `Copy Files` and select the Destination `Frameworks` and clear the Subpath and deselect `Copy only when installing` 
5) Select all Libraries you just added in the table below 
