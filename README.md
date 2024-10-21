# Masters Thesis M. Sc. Computer Science and Media

![Latest PDF Version](https://github.com/FreddyOm/MScThesis/actions/workflows/latex-to-pdf.yml/badge.svg)

The thesis LaTeX project for the master's thesis "Optimizing Voxel Rendering using a Mesh Shading Rendering Pipeline".


## Feedback Topics

- [] "We" or "I" in thesis text -> S.R.
- [] How much of the implementation should be discussed? All implementation to appendix anyway.
- [] Chapters 6.1 & 6.2 and chapter 6.3 are kind of redundant, but I would still like to seperate high level 
pipeline discussion and in depth data visualization.
- [] Introduction & Motivation? Redundant?
- [] Technical Background & Related Work? Redundant? Maybe related work more of specific application instead of 
scientific and presentational work.
- [] Citation okay?
- [] Mention less (sub-) chapters in contents?
- [] Results and Discussion seperately? Or together?
- [] Implementation before Methodoligy, then Case-Study and Results?

## Problems

- [x] Shader invocation limit at 65536 -> Multiple Batches? -> Not a problem after occlusion culling? -> Multiple passes?
- [x] Lighting? Texturing? Normals? -> Can be easily added to shader