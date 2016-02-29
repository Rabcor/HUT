# HUT
Hydra UI Toolkit

Version: **Proof of concept**

The Hydra UI toolkit will not feature any software rendering modes (I think it's time to do away with that, every modern consumer PC has a GPU, whether it's intergrated or dedicated).

**It will support:**
* OpenGL ES
* WebGL
* Vulkan

It will also have some basic game engine capablities (in the future I will make samples of spinning gears and triangles, and I will create minigames (like solitaire and minesweeper) within it to use as showcase demos)

The toolkit will be written in C and will support Linux(Wayland) and Windows. It may support X11 (may also just support X11 by running wayland nested in X11, this is something I'll decide at a later date).

This will be the main UI toolkit for all software I will develop in the foreseeable feature, and will be designed around the concept of being an independent UI library with support for plugging just about any application or code in as it's backend without any specific support libraries for using the UI toolkit with the language, or the language with the UI toolkit, it should all just work as long as the compiler can compile all languages.

**(High Level)To Do:**

* Create the basic toolkit with OpenGL ES support
* Testing phase (Basic feature-set and OpenGL ES)
* Port to WebGL
* Testing phase (WebGL)
* Port to Vulkan
* Testing phase (Vulkan)
* Port to Windows
* Testing phase (Windows)
* Implement themeing support, and compatibility with GTK theme packs. (or based on GTK theme format)
* Implement HUT to GTK theme converter.
* ....
