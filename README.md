# Masters Thesis M. Sc. Computer Science and Media

![Latest PDF Version](https://github.com/FreddyOm/MScThesis/actions/workflows/latex-to-pdf.yml/badge.svg)

The thesis LaTeX project for the master's thesis "Optimizing Voxel Rendering using a Mesh Shading Rendering Pipeline".


## Feedback Topics

- [x] Chapters 6.1 & 6.2 and chapter 6.3 are kind of redundant, but I would still like to seperate high level 
pipeline discussion and in depth data visualization.
- [x] Citation okay?
- [x] Check title. Is it fitting? What is the second pass? If it is reprojection, then rename!!
- [x] Kolloquium, Paper & Thesis -> Koll. Nach Abgabe 1h (~40-45 Präsi mit Live Demo); 
- [x] Games as related work?
- [x] Try implementing dynamic build up of models so the dynamic part can be shown here!
- [x] How to structure plots (Systems, per octree vs meshlet oc, models, scene sizes, ...)


## Problems

- [x] Shader invocation limit at 65536 -> Multiple Batches? -> Not a problem after occlusion culling? -> Multiple passes?


## TODO Thesis: 
- [x] Incorporate latest feedback
- [x] Add nocull overdraw for torus
- [x] Move model descriptions down to individual model results
- [x] Add mew measurements into thesis (Best occluder creation)
- [x] Fix capitalization of words
- [x] Write Conclusion
- [] ~~Add Octree hierarchy depth to general information?~~
- [] ~~Evaluate memory footprint in discussion~~
- [] Refer to PMOC average divergence in discussion
- [x] Adjust GPU Performance Results ymax values in plot
- [] Add conclusion in brief chapter overview at the end of motivation? 
- [] Consider removing Virtualized Geometry from conclusion
- [] Remove implementational limitations from discussions limitations
- [] Add different sources for academic sources, image sources, games, ...

- ~~Limitations statt Impl Limits~~
- ~~Experimental Setup~~
- ~~Experimental Results Summary~~
- ~~Experimental Results Interpretation~~
- ~~Implications for Practical Use~~ 

## TODO Paper:
- [x] Memory occupation of models also into paper?
- [] Transpose CPU performance table 

## Kolloquium

- If I were do redo it Id focus on the aggregation of the best occluders as the central innovation
and do experiments with dynamically updating and changing the voxel meshes.
- Compare depth prepass with all voxels against depth prepass with aggregated best occluders
- Would have liked to fix visual errors 
- Show differences for different scene resolutions and different screen resolutions