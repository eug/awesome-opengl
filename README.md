# awesome-opengl [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[<img src="https://rawgit.com/eug/awesome-opengl/master/opengl-logo.svg" align="right" width="140">](https://www.opengl.org)

A curated list of awesome OpenGL libraries, debuggers and resources.

## Contents

* [Articles](#articles)
* [Books](#books)
* [Debug](#debug)
* [GLSL Editors](#glsl-editors)
* [Libraries](#libraries)
* [Profile Loaders](#profile-loaders)
* [References](#references)
* [Talks](#talks)
* [Videos](#videos)
* [Websites](#websites)


## Articles

*OpenGL articles (non-tutorials)*

* [(2014) Ray tracing with OpenGL Compute Shaders](https://github.com/LWJGL/lwjgl3-wiki/wiki/2.6.1.-Ray-tracing-with-OpenGL-Compute-Shaders-%28Part-I%29) by **Kai Burjack** - Detailed tutorial series about ray tracing using OpenGL (LWJGL).
* [(2014) Things that drive me nuts about OpenGL](http://richg42.blogspot.com.au/2014/05/things-that-drive-me-nuts-about-opengl.html) by **Rich Geldreich** - Constructive (or not) criticism of GL API.
* [(2011) A trip through the graphics pipeline](https://fgiesen.wordpress.com/2011/07/09/a-trip-through-the-graphics-pipeline-2011-index) by **Fabian Giesen** - Compreheensive and rich series about the D3D/OpenGL graphics pipeline.
* [(2010) What is OpenGL?](http://duriansoftware.com/joe/An-intro-to-modern-OpenGL.-Chapter-1:-The-Graphics-Pipeline.html) by **Joe Groff** - Brief introduction to the building blocks of OpenGL.


## Books

*Popular books about OpenGL*

* [A Trip Down the Graphics Pipeline](http://www.amazon.com/dp/1558603875) by **Jim Blinn** - Popular book that contains wealth information about the graphics pipeline, and of the best sources to learn the core concepts of Computer Graphics.
* [Computer Graphics](http://www.amazon.com/dp/0321399528) by **John F. Hughes, et al.** - Computer Graphics is indeed a must for anyone being involved in the design and implementation of Computer Graphics algorithms. However, this is not a OpenGL focused book, but contains valuable demonstrations of the technology.
* [Interactive Computer Graphics](http://www.amazon.com/dp/0132545233) by **Edward Angel and Dave Shreiner** - It provides several examples using OpenGL and it covers several aspects at once, but if you are trying to learn OpenGL on your own you might not find this helpful.
* [OpenGL ES 3.0 Programming Guide](http://www.amazon.com/dp/0321933885) by **Dan Ginsburg, et al.** - It presents all the necessary information to use the OpenGL ES 3.0 API in a clear manner.
* [OpenGL Insights](http://www.amazon.com/dp/1439893764) by **Patrick Cozzi, Christophe Riccio** - Rich and comprehensive resource to learn techniques and tips, covering several advanced topics of OpenGL.
* [OpenGL Programming Guide](http://www.amazon.com/dp/0321773039) by **Dave Shreiner, et al.** - It does a good job covering the basics and providing clear reference of the API.
* [OpenGL Shading Language](http://www.amazon.com/dp/0321637631) by **Randi J. Rost, et al.** - Very clear and well written book about Shading Language. Also, it provides several explanations of writing shaders.
* [OpenGL SuperBible](http://www.amazon.com/dp/0321712617) by **Richard S. Wright, et al.** - It covers the basic concepts of computer graphics and provides clear examples using OpenGL. Definitely, it is a must for beginners.
* [Real-Time Rendering](http://www.amazon.com/dp/1568814240) by **Tomas Akenine-Moller, Eric Haines and Naty Hoffman** - It does a good job at explaining concepts for game engine, basis for game client programming as well as the necessary knowledge for understanding DirectX and OpenGL.


## Debug

*Debugging and profiling libraries*

* [apitrace](http://apitrace.github.io) - Tools for tracing OpenGL, Direct3D, and other graphics APIs.
* [CodeXL](https://github.com/GPUOpen-Tools/CodeXL) - AMD's tool suite that includes debugger, profiler and frame/shader analysis.
* [GL-SL Debugger](http://glsl-debugger.github.io) - Tool for debugging OpenGL programs.
* [GLIntercept](https://github.com/dtrebilco/glintercept) - OpenGL function call interceptor for Windows.
* [Intel-GPA](https://software.intel.com/en-us/gpa) - Intel's OpenGL Graphics Performance Analyzer.
* [NVIDIA® Nsight™](https://developer.nvidia.com/nvidia-nsight-visual-studio-edition) - Development platform for graphics applications.
* [RenderDoc](https://github.com/baldurk/renderdoc) - RenderDoc is a stand-alone graphics debugging tool.
* [tracy](https://github.com/wolfpld/tracy) - A real time remote telemetry frame profiler for games and other applications.
* [vogl](https://github.com/ValveSoftware/vogl) - OpenGL capture and playback debugger developed by Valve.


## GLSL Editors

*Online GLSL Editors*

* [GLSL Sandbox](http://glslsandbox.com) - Online live editor for fragment shaders.
* [GLSLbin](http://glslb.in) - Fragment shader sandbox supporting [glslify](https://github.com/stackgl/glslify).
* [SHDR Editor](http://shdr.bkcore.com) - Live GLSL shader editor, viewer and validator.
* [Shader Toy](https://www.shadertoy.com) - Most popular live editor for fragment shaders.
* [ShaderFrog](http://shaderfrog.com/) - WebGL Shader Editor and Composer

## Libraries

*Useful libraries for OpenGL applications*

* [assimp](https://github.com/assimp/assimp) - Portable library to import 3D models in a uniform manner.
* [Bullet](http://bulletphysics.org/wordpress) - It provides state of the art collision detection, soft body and rigid body dynamics.
* [fltk](https://www.fltk.org/) - C++ Toolkit to generate UI widgets portably. [LGPLv2](https://www.fltk.org/COPYING.php)
* [freeGLUT](http://freeglut.sourceforge.net) - Mature library that allows to create/manage windows containing OpenGL contexts.
* [GLFW](http://www.glfw.org) - Modern library for creating/interact windows with OpenGL contexts.
* [GLFM](https://github.com/brackeen/glfm) - Supplies an OpenGL ES context and input events for mobile devices and the web.
* [glm](http://glm.g-truc.net/0.9.6/index.html) - Mathematics library for graphics software based on the GLSL specifications.
* [Magnum](https://github.com/mosra/magnum) - It is a 2D/3D graphics engine for modern OpenGL.
* [MathFu](http://google.github.io/mathfu/) - C++ math library developed primarily for games focused on simplicity and efficiency.
* [Newton](http://newtondynamics.com/forum/newton.php) - It is a cross-platform life-like physics.
* [OGLplus](http://oglplus.org) - Collection of libraries which implement an object-oriented facade over OpenGL.
* [SDL](http://www.libsdl.org) - Designed to provide low level access to multimedia and graphics hardware.
* [SFML](http://www.sfml-dev.org) - Simple interface to ease the development of games and multimedia applications.
* [SOIL](http://www.lonesock.net/soil.html) - Tiny C library used primarily for uploading textures into OpenGL. (see [SOIL2](https://bitbucket.org/SpartanJ/soil2))
* [Pangolin](https://github.com/stevenlovegrove/Pangolin) - Lightweight portable rapid development library for managing OpenGL display / interaction and abstracting video input.


## Profile Loaders

*Profile loaders for OpenGL*

* [gl3w](https://github.com/skaslev/gl3w) - Simple OpenGL core profile loader.
* [glad](https://github.com/Dav1dde/glad) - Multi profile loader-generator based on the official specs.
* [glbindify](https://github.com/nnesse/glbindify) - Command line tool to generate C bindings for OpenGL, wgl, and glX.
* [glbinding](https://github.com/cginternals/glbinding) - Profile loader leveraging C++11 features to provide type safety.
* [GLEW](http://glew.sourceforge.net) - Mature cross-platform library to load OpenGL extensions.
* [glLoadGen](https://bitbucket.org/alfonse/glloadgen/wiki/Home) - Multi profile loader-generator written in Lua.


## References

*OpenGL references*

* [docs.GL](http://docs.gl) - It is an alternative documentation for OpenGL.
* [OpenGL API Tables](http://web.eecs.umich.edu/~sugih/courses/eecs487/common/notes/APITables.xml) - Quick reference of API's for several OpenGL and GLSL versions.
* [OpenGL Cheat Sheet](https://www.khronos.org/files/opengl43-quick-reference-card.pdf) - Quick reference card of OpenGL 4.3 commands and syntax.
* [OpenGL Docs](https://www.opengl.org/sdk/docs) - Official documentation website.
* [OpenGL Wiki](https://www.opengl.org/wiki/Main_Page) - Official OpenGL wiki.


## Talks

*OpenGL related talks*
* [Approaching Zero Driver Overhead in OpenGL](http://gdcvault.com/play/1020791/) - [Slides](http://www.slideshare.net/CassEveritt/approaching-zero-driver-overhead) - [AMA Reddit](https://www.reddit.com/r/gamedev/comments/21mbo8/we_are_the_authors_of_approaching_zero_driver) by **Cass Everitt, Tim Foley, John McDonald, Graham Sellers** [1:15:54]
* [How Modern OpenGL Can Radically Reduce Driver Overhead](https://www.youtube.com/watch?v=-bCeNzgiJ8I) by **Cass Everitt, John McDonald** [51:13]
* [Moving Your Games to OpenGL](https://www.youtube.com/watch?v=45O7WTc6k2Y) by **Rich Geldreich, Dan Ginsburg, Peter Lohrmann, Jason Mitchell** [54:45]


## Videos

*OpenGL video tutorials*

* [Jamie King](https://www.youtube.com/playlist?list=PLRwVmtr-pp06qT6ckboaOhnm9FxmzHpbY) - Comprehensive tutorials about modern OpenGL and Qt.
* [MakingGamesWithBen](https://www.youtube.com/playlist?list=PLSPw4ASQYyymu3PfG9gxywSPghnSMiOAW) - Video tutorials (step-by-step) about OpenGL and game development.
* [SIGGRAPH](https://www.youtube.com/user/ACMSIGGRAPH/playlists) - Popular conference about computer graphics.
* [TheChernoProject](https://www.youtube.com/playlist?list=PLlrATfBNZ98foTJPJ_Ev03o2oq3-GGOS2) - Introduction to OpenGL in C++
* [thebennybox](https://www.youtube.com/user/thebennybox/playlists) - Videos tutorials about OpenGL and game development.
* [ThinMatrix](https://www.youtube.com/user/ThinMatrix/playlists) - Video tutorials about OpenGL and game development using Java.
* [sentdex](https://www.youtube.com/playlist?list=PLQVvvaa0QuDdfGpqjkEJSeWKGCP31__wD) - Videos tutorials about OpenGL (immediate mode) using Python.
* [Sonar Systems](https://www.youtube.com/playlist?list=PLRtjMdoYXLf6zUMDJVRZYV-6g6n62vet8) - Learn about the new and modern OpenGL 3.0+.

## Websites

*OpenGL tutorial websites*

* [3D Game Shaders For Beginners](https://github.com/lettier/3d-game-shaders-for-beginners) by **David Lettier**
* [Learn OpenGL](https://learnopengl.com) by **Joey de Vries**
* [Learning Modern 3D Graphics Programming](https://bitbucket.org/alfonse/gltut/wiki/Home) by **Jason L. McKesson**
* [Light House 3D](http://www.lighthouse3d.com/tutorials/glsl-core-tutorial) by **Light House 3D**
* [Modern OpenGL](http://www.tomdalling.com/blog/category/modern-opengl) by **Tom Dalling**
* [OpenGL Examples](https://github.com/McNopper/OpenGL) by **Norbert Nopper**
* [OpenGL Step by Step](http://ogldev.atspace.co.uk) by **Etay Meiri**
* [OpenGL Tutorial](https://open.gl) by **Alexander Overvoorde**
* [OpenGL Tutorial](http://antongerdelan.net/opengl/index.html) by **Anton Gerdelan**
* [OpenGL Tutorial](http://www.opengl-tutorial.org) by **Bonder Wu**
* [OpenGL Tutorial](http://www.songho.ca/opengl) by **Song Ho Ahn**

## Related lists

*Similar awesome lists*
* [awesome](https://github.com/sindresorhus/awesome) - A curated list of awesome lists.
* [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision) - A curated list of awesome computer vision resources.
* [awesome-webgl](https://github.com/sjfricke/awesome-webgl) - A curated list of awesome WebGL libraries, resources and much more.
* [awesome-vulkan](https://github.com/vinjn/awesome-vulkan) - A curated list of awesome Vulkan projects and ecosystem.
* [gamedev](https://github.com/ellisonleao/magictools) - A awesome list about game development.
* [graphics-resources](https://github.com/mattdesl/graphics-resources) - A list of graphic programming resources.


## License

[![Creative Commons License](http://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).

## Contributing
Please see [CONTRIBUTING](https://github.com/eug/awesome-opengl/blob/master/CONTRIBUTING.md) for details.
