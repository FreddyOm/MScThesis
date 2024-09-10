# Masters Thesis M. Sc. Computer Science and Media

![Latest PDF Version](https://github.com/FreddyOm/MScThesis/actions/workflows/latex-to-pdf.yml/badge.svg)

The thesis LaTeX project for the master's thesis "Optimizing Voxel Rendering using a Mesh Shading Rendering Pipeline".


## Feedback Topics

- [x] "We" or "I" in thesis text -> We
- [x] Passive Formulierungen anstatt aktiver -> ("... der Fokus liegt auf..." anstatt "... wir fokussieren uns auf ...")? -> Englisch: Leser addresieren, we 
- [x] 05_MeshShading -> Explain every possible GPU program or only relevant ones? -> Von Fachpublikum ausgehen (Spiele-Entwicklung) -> Quellen referenzieren -> Publikum soll dasselbe bleiben
- [x] Show complete evolution of rendering or only the two compared pipelines -> Bisschen zur Historie, anekdotisch drauf eingehen, kurz auf Deferred Rendering eingehen, 
- [x] Only Rasterization Pipeline possible. How to differentiate from Raytraced Pipeline etc. -> RT ganz weg vlt., oder ganz klar machen, dass irellevant
- [x] "Related Work" before or after "Voxel Rendering"? -> Voxel Rendering zu Introduction & History
- [x] Meshlet Culling algorithm in chapter 5 or 6? 
- [x] History of Renderpipeline in Mesh Shading. Mesh Shading vor Related Work. 

## Problems

- [x] Shader invocation limit at 65536 -> Multiple Batches? -> Not a problem after occlusion culling? -> Multiple passes?
- [ ] Lighting? Texturing? Normals?