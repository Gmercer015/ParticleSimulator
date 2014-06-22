ParticleSimulator
=================

A particle simulator written with C++ SFML OpenGL. 

**Read more about this project at http://syntaf.github.io/ParticleSimulator/**

*This gif is currently outdated, the whole phsyics system has recently been revamped*
![gif](http://i.imgur.com/duEgiDl.gif)

Or see the full video here: https://vimeo.com/96867903  (**Password:** particles)

**Required Libraries**
--------------------------------------------------------

| Library        | Minimum Version | Architecture |Header Only  |
| -------------  |:-------------:  | :---------:  |-----:       |
| GLM            | 0.9.5.3         | N/A          |  Yes        |
| GLEW           | 1.5.3           | x64          |  No         |
| SFML           | 2.1             | x64          |  No         |

[**GLM**](http://glm.g-truc.net/0.9.5/index.html):  A header only C++ mathematics library for graphics software based on the OpenGL Shading Language (GLSL) specification and released under the MIT license.

[**GLEW**](http://glew.sourceforge.net/):   A cross-platform open-source C/C++ extension loading library. GLEW provides efficient run-time mechanisms for determining which OpenGL extensions are supported on the target platform. OpenGL core and extension functionality is exposed in a single header file. GLEW has been tested on a variety of operating systems, including Windows, Linux, Mac OS X, FreeBSD, Irix, and Solaris.
  
[**SFML**](http://www.sfml-dev.org/):   SFML provides a simple interface to the various components of your PC, to ease the development of games and multimedia applications.

Configuration
-----------------
The current configuration properties are set to the following locations:
* Include directories are set to ```C:/local/(NAME)/include``` where NAME is either *SFML-2.1* or *glm*
* SFML libraries are set to ```C:/local/SFML-2.1/lib```
* GLEW libraries are set to ```C:/local/glew-1.10.0/lib/Release/x64```

######Make sure to change these settings, or you may face a number of confusing errors

Building
-------------------

**Coming Soon**

Additional Notes
-------------------------
- Intel HD 4000 graphics cards currently have issues running ModernGL, however this should not inhibit the simulator from running
- A thanks to opengl-tutorial.org for code structure and teachings
