# Masters Thesis M. Sc. Computer Science and Media

![Latest PDF Version](https://github.com/FreddyOm/MScThesis/actions/workflows/latex-to-pdf.yml/badge.svg)

The thesis LaTeX project for the master's thesis "Optimizing Voxel Rendering using a Mesh Shading Rendering Pipeline".


## Feedback Topics

- [x] "We" or "I" in thesis text -> S.R.
- [x] How much of the implementation should be discussed? All implementation to appendix anyway.
- [] Chapters 6.1 & 6.2 and chapter 6.3 are kind of redundant, but I would still like to seperate high level 
pipeline discussion and in depth data visualization.
- [x] Introduction & Motivation? Redundant?
- [x] Technical Background & Related Work? Redundant? Maybe related work more of specific application instead of 
scientific and presentational work.
- [] Citation okay?
- [x] Mention less (sub-) chapters in contents?
- [x] Results and Discussion seperately? Or together?
- [x] Implementation before Methodoligy, then Case-Study and Results?
- [] Introduction topics (GPU Driven, Deferred Rendering, ... )
- [x] Show any code at all in the normal chapters? Or only use pseudo code?
- [x] Wikipedia source (DirectX) okay? Or not?
- [] Check title. Is it fitting? What is the second pass? If it is reprojection, then rename!!
- [] What else in Introduction?
- [] Kolloquium, Paper & Thesis -> Koll. Nach Abgabe 1h (~40-45 Präsi mit Live Demo); Paper zur gleichen Zeit wie MA
- [x] Methodology as part of case study?
- [] Games as related work?

## Problems

- [x] Shader invocation limit at 65536 -> Multiple Batches? -> Not a problem after occlusion culling? -> Multiple passes?
- [x] Lighting? Texturing? Normals? -> Can be easily added to shader