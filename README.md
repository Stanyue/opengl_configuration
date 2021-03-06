# GLFW/GLEW/GLM and NanoGUI configuration

This is a windows version of GLFW/GLEW/GLM and nanogui binary file collection.

This version is used for Visual Studio 2015 Release/x64 mode.

For other versions of binary file, you can compile it on your own using cmake-gui windows version

# Usage

1: Add this folder into your system variables with:

Variable name: OPENGL

Variable value: YOUR_CURRENT_FOLDER
```
e.g.  
    Variable name: OPENGL
    Variable value: D:\Program Files\opengl
```

2: Add dll folder to your system's "Path":
```
e.g. 
    Variable name: Path
    Variable value: D:\Program Files\opengl\dll
```

2: Create your own empty project in Visual Studio 2015

3: Add OPENGL.prop and then NANOGUI.prop(sequence should be the same) into Visual Studio Property Manager:
```
    View->Other Windows->Property Manager
    Add Existing Property Sheet
```

4: Run code test:

GLFW/GLEW/GLM Test:

Add opengl_example/hellowindow2.cpp provided by LearnOpenGL into your project

NanoGui Test:

Add nanogui_example/example3.cpp provided by NanoGUI into your project

Done

# Reference Links

Xcode verison of NanoGUI configuration: [http://jody-lu-blog.logdown.com/posts/1533525](http://jody-lu-blog.logdown.com/posts/1533525).

Thanks for Jody Lu's help with Mac's configuration on Nanogui.

GLEW: [https://github.com/nigels-com/glew](https://github.com/nigels-com/glew)

GLFW: [https://github.com/glfw/glfw](https://github.com/glfw/glfw)

GLM: [https://github.com/g-truc/glm](https://github.com/g-truc/glm)

NanoGui: [https://github.com/wjakob/nanogui](https://github.com/wjakob/nanogui)

Learn OpenGL: [https://github.com/JoeyDeVries/LearnOpenGL](https://github.com/JoeyDeVries/LearnOpenGL)