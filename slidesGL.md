---
marp: true
backgroundColor: black;
color: white;

style: |
  a{
    color: #847c54;
  }

---
# WebGL and GIS

DEUS Concilium coffee on Fri 8Apr 2022

---

# What is and when use GL (Graphic Libraries)

A small trip from vertex to massive data representation

---

# Which are GL (Graphic Libraries)

- WebGL
- OpenGL
- Vulkan
- DirectX

---

# Which are not GL

- Most common chart libraries
- Static images
- Videos
- Paralax effects on headers websites

---

# So when should we use GL?

- 2D/3D expensive calculated rendering
- Create object/models which user can interact with

---

# And... why?

Because we get the GPU power over the CPU for parallell processing!
Graphic libraries take advantage of the GPU to calculate multiple small things.

And we can also do that in Web development

---

# Examples of GL rendering

The examples on this link are made for web but they can be generalize to other platforms.

## <https://webglsamples.org/>

Art and tech united again

## <https://le-voyage-azarien.art/>

---

# GL 101

## _Vertex_

Each one of the point that delimit a poligon

## _Fragment_

Space that can be drawn between vertex

## _Shader_

Program that runs for every fragment and vertex on the model

---

## _Buffers_

Contiguous memory space in GPU loaded with data ( attributesunidimensional array)

## _Atribute_

These variables represent a particular vertex in our mesh.

## _Uniforms_

Global read-only variables that can be use in the vertex and fragment shaders.

## _Varyings_

Variables you can write in your vertex shader which then is passed to the fragment shader.

---
<!-- backgroundColor: white;
color: black -->

# The rendering pipeline concepts assembled

![img](https://miro.medium.com/max/700/1*yNeQKJ2BRAonXxBhKgvucg.png)

---
<!-- backgroundColor: white;
color: black -->

# The rendering pipeline

![img](https://www.tutorialspoint.com/webgl/images/fragment_operations.jpg)

---
<!-- backgroundColor: black;
color: white -->

# Show me the code

- The 2D Triangle
  - <https://codesandbox.io/s/color-triangle-fqoy28>
- Multicolor 3D cube 
  - <https://web.cs.upb.de/cgvb/WebGLEditor/>

---

## Analytics and GL? Overpowered

- <https://deck.gl/>
- <https://kepler.gl/>
- <https://threejs.org/examples/#webgl_geometry_spline_editor>

---

# Bibliography

- <https://webglfundamentals.org>
- <https://thebookofshaders.com/>
- <https://www.cis.upenn.edu/~cis277/16sp/lectures/2_9_OpenGL_Shaders.pdf>
- <http://learnwebgl.brown37.net>
- <https://developer.mozilla.org/es/docs/Web/API/WebGL_API/Tutorial/Getting_started_with_WebGL>
- <https://eater.net/quaternions> <-- just for freaks

---
# And that's all! 
## Q&A ?