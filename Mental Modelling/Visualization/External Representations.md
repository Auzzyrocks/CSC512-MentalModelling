## 1) What makes a representation “visual” and “external”?
- **External**: it exists on paper or screen, persistent enough to be inspected and manipulated.  
- **Visual**: it communicates via spatial layout and/or visual channels (position, length, area, angle, color, texture, orientation, shape, motion).  
- **Cognitive role**: a partner to the internal model. People iteratively read from the diagram (extract structure) and write to it (arrange, annotate, re-represent).

The key idea is that a person is augmenting with their visuals, that makes one distributed cognitive system (Hutchins, 1995; Zhang & Norman, 1994).

## 2) Why external visual representations work (mechanisms tied to vision & space)

1) **Perceptual inference**  
   - Encode relations so they are seen (e.g., comparing aligned positions is more accurate than comparing angles or areas).  
   - Supports pop-out for targets using preattentive features (color, size, orientation).  
   *Canonical:* Larkin & Simon (1987); Cleveland & McGill (1984); Ware (2019); Kosslyn (2006).

1) **[[Mental Modelling/Visualization/Memory Offloading|Memory Offloading]]**  
   - Stable marks hold intermediate states/constraints; frees working memory for planning and hypothesis testing.  
   *Canonical:* Risko & Gilbert (2016); Sweller et al. (2011).

3) **Search constraint**  
   - Topology, alignment, axes, and arrows narrow possible interpretations and legal “moves.”  
   *Canonical:* Larkin & Simon (1987).

4) **Re-representation**  
   - Switching form (e.g., node–link ↔ matrix; table ↔ plot) reveals different structure and errors.  
   *Canonical:* Zhang (1997); Munzner (2014).

5) **Spatial indexing / intelligent use of space**  
   - Stable spatial layout doubles as an index into memory; fewer attentional shifts.  
   *Canonical:* Kirsh (1995); Tufte (2001).

---

## 3) Different kinds of **visual** external representations
### A) Charts for quantitative comparison
- Magnitude & ranking: bar charts, dot plots.  
- Trends & rates: line charts and slope charts.  
- Distributions: histograms, density plots, violin/box plots, ridgeline small multiples.  
- Part–whole: stacked bars (few parts), treemaps (hierarchical part–whole).
- Multivariate quickscan: scatterplot (correlation), scatterplot matrix (SPLOM), parallel coordinates (high-dimensional).  


![[bar_chart.png]]

### B) Networks, trees, and sets
- Node–link diagrams for sparse relationships, adjacency matrices for dense graphs.  
- Trees & hierarchies: dendrograms, icicle/sunburst, indented lists.  
- Sets & overlaps: Venn/Euler; UpSet plots.

![[tree_graph.png]]

### C) Temporal & sequential
- Timelines & Gantt for schedules, swimlanes/sequence diagrams, event streams.  ![[timeline.png]]

### D) Spatial & geospatial
- Point/heat maps, choropleths, proportional symbols, flow maps.

### E) Flow, causality, and dynamics
- Sankey/alluvial: flows between categories.  
- Stock–flow (system dynamics).
- Causal DAGs: nodes as variables.
- State machines / BPMN / Petri nets.

### F) Mechanism & structure diagrams
- Exploded views, cutaways, circuit schematics, free-body diagrams.
- UML (class, activity, sequence) for software/system reasoning.

---

## 3) Visual encoding principles (highlight desired features)

- Channel ranking (accuracy): *position (common scale)* > length > angle/slope > area/volume > color luminance/saturation > color hue (for categories) > shape/texture. (Cleveland & McGill, 1984; Ware, 2019)  
- Gestalt & grouping: proximity, similarity, enclosure, connection, continuity.
- Labeling & contiguity: place labels *at* the mark; avoid long legends; maintain left-to-right/time conventions.  
- Color: sequential palettes for ordered data; diverging for centered data; categorical for nominal.
- Scale honesty: zero-baseline for bars; clearly mark breaks/zoom if used; avoid “lie factors.” (Tufte)  
- Uncertainty & variability: intervals, bands, violin shapes, ensembles.

---

## 6) Static, animated, and interactive **visuals** (visual-only lens)

- Static sequences (step panels, small multiples) often beat autoplay animation because transient information overloads working memory.  
- Animation helps when it shows continuous change that is hard to convey otherwise, and when it is user-controlled (pause/scrub) with trails showing history. (Tversky et al., 2002; Hegarty, 2004)  
- Interactivity adds cognitive leverage: brushing & linking, faceting, parameter sliders, tooltips, focus+context (fish-eye/lens), view toggling (e.g., node-link ↔ matrix). (Shneiderman; Card et al.)

---
## References
- Bertin, J. (2011; orig. 1967). *Semiology of Graphics*. ESRI Press.  
- Card, S. K., Mackinlay, J., & Shneiderman, B. (1999). *Readings in Information Visualization*. Morgan Kaufmann.  
- Cleveland, W. S., & McGill, R. (1984). Graphical perception. *JASA, 79*(387), 531–554.  
- Heer, J., & Bostock, M. (2010). Crowdsourcing graphical perception. *CHI ’10*, 203–212.  
- Hegarty, M. (2004). Mechanical reasoning by mental simulation. *Trends in Cognitive Sciences, 8*(6), 280–285.  
- Hutchins, E. (1995). *Cognition in the Wild*. MIT Press.  
- Kirsh, D. (1995). The intelligent use of space. *Artificial Intelligence, 73*(1–2), 31–68.  
- Kosslyn, S. M. (2006). *Graph Design for the Eye and Mind*. Oxford University Press.  
- Larkin, J. H., & Simon, H. A. (1987). Why a diagram is (sometimes) worth ten thousand words. *Cognitive Science, 11*(1), 65–100.  
- Mayer, R. E. (2009). *Multimedia Learning* (2nd ed.). Cambridge University Press.  
- Munzner, T. (2014). *Visualization Analysis and Design*. CRC Press.  
- Risko, E. F., & Gilbert, S. J. (2016). Cognitive offloading. *Trends in Cognitive Sciences, 20*(9), 676–688.  
- Sweller, J., Ayres, P., & Kalyuga, S. (2011). *Cognitive Load Theory*. Springer.  
- Tufte, E. R. (2001). *The Visual Display of Quantitative Information* (2nd ed.). Graphics Press.  
- Tversky, B., Morrison, J. B., & Bétrancourt, M. (2002). Animation: Can it facilitate? *IJHCS, 57*(4), 247–262.  
- Ware, C. (2019). *Information Visualization: Perception for Design* (4th ed.). Morgan Kaufmann.  
- Zhang, J. (1997). The nature of external representations in problem solving. *Cognitive Science, 21*(2), 179–217.  
- Zhang, J., & Norman, D. A. (1994). Representations in distributed cognitive tasks. *Cognitive Science, 18*(1), 87–122.


