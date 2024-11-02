# Masters Thesis M. Sc. Computer Science and Media

![Latest PDF Version](https://github.com/FreddyOm/MScThesis/actions/workflows/latex-to-pdf.yml/badge.svg)

The thesis LaTeX project for the master's thesis "Optimizing Voxel Rendering using a Mesh Shading Rendering Pipeline".


## Feedback Topics

- [] Chapters 6.1 & 6.2 and chapter 6.3 are kind of redundant, but I would still like to seperate high level 
pipeline discussion and in depth data visualization.
- [] Citation okay?
- [] Check title. Is it fitting? What is the second pass? If it is reprojection, then rename!!
- [] What else in Introduction?
- [x] Kolloquium, Paper & Thesis -> Koll. Nach Abgabe 1h (~40-45 Präsi mit Live Demo); Paper zur gleichen Zeit wie MA
- [] Games as related work?
- [] Try implementing dynamic build up of models so the dynamic part can be shown here!
- [] Try implementing raster occlusion culling using depth queries
- [] Add depth queries to thesis text?
- [] Add a short paragraph about what the reader is expected to know (z-buffer, mip-maps, texels, graphics pipeline in general, high level CPU and GPU architecture, ...)

## Problems

- [x] Shader invocation limit at 65536 -> Multiple Batches? -> Not a problem after occlusion culling? -> Multiple passes?
- [x] Lighting? Texturing? Normals? -> Can be easily added to shader