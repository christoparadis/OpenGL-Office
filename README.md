Libraires used :
  • GLM
  • GLEW
  • GLFW
The project was originally modeled in blender then exported to an OBJ file. The textures were rendered onto one single 4k file then compressed to DTX3 to improve performance when compiling and rendered in OpenGL. (VisualStudio crashes if not) The shaders have been broken off into 3 different sets:
  1. Depth: Shadow projection and Mipmap smoothing
  2. Mapping: Shadow angle calculation
  3. Passthrough: Classic Vertex and Fragment Shader based off imported texture file.
  
Camera controls are set to 1, 2, 3, and 4 your keyboard (not keypad). When compiling the project, the first camera is not set until pressed for debugging purposes.
