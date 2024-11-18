# Masters Thesis M. Sc. Computer Science and Media

![Latest PDF Version](https://github.com/FreddyOm/MScThesis/actions/workflows/latex-to-pdf.yml/badge.svg)

The thesis LaTeX project for the master's thesis "Optimizing Voxel Rendering using a Mesh Shading Rendering Pipeline".


## Feedback Topics

- [x] Chapters 6.1 & 6.2 and chapter 6.3 are kind of redundant, but I would still like to seperate high level 
pipeline discussion and in depth data visualization.
- [x] Citation okay?
- [x] Check title. Is it fitting? What is the second pass? If it is reprojection, then rename!!
- [x] Kolloquium, Paper & Thesis -> Koll. Nach Abgabe 1h (~40-45 Präsi mit Live Demo); Paper zur gleichen Zeit wie MA
- [ ] Games as related work?
- [ ] Try implementing dynamic build up of models so the dynamic part can be shown here!
- [x] How to structure plots (Systems, per octree vs meshlet oc, models, scene sizes, ...)


## Problems

- [x] Shader invocation limit at 65536 -> Multiple Batches? -> Not a problem after occlusion culling? -> Multiple passes?


## Kolloquium

- If I were do redo it Id focus on the aggregation of the best occluders as the central innovation
and do experiments with dynamically updating and changing the voxel meshes.