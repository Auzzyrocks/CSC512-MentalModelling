> A good visualization means choosing the visual form whose structure matches the structure of the task. When fit is good, the key inference becomes perceptual (you can *see* it). When fit is poor, users must translate/compute in their heads. Good fit reduces cognitive load, error, and time, which results in a cognitive mental model.
---

## 1) Why “fit” matters for mental models

- Data needs a representation that aligns with the question it is supposed to answer.  
- A well-fitted visual lets users **map task operations** (lookup, compare, trace) onto visual operations (align, scan, trace a path, estimate slope).  
- This turns symbolic reasoning into perceptual inference (e.g., comparing aligned positions is faster/more accurate than comparing angles or areas), which frees working memory and accelerates model formation and correction.

References: Vessey (1991) on cognitive fit, Cleveland & McGill (1984) and Ware (2019) on channel accuracy, Kosslyn (2006) on perception-grounded graph design.

---

## 2) Tasks need to be mapped to appropriate visuals

| Task                                  | Best-fit visuals                   | Fit justification                                   |
| ------------------------------------- | ---------------------------------- | --------------------------------------------------- |
| **Lookup/exact retrieval**            | Table, dot plot with labels        | Direct addressable cells, aligned text              |
| **Compare magnitudes/ranks**          | Bar chart, dot/lollipop            | Aligned position/length grants higher accuracy      |
| **Compare change between two points** | Slope chart, paired bars           | Slope encodes direction/amount without scale shifts |
| **Trend/rate over time**              | Line chart, small multiples        | Continuous change shown as slope                    |
| **Distribution/shape**                | **Histogram**, density, box/violin | Shape & spread visible                              |
| **Outliers/anomalies**                | Scatter, box (whiskers), dot plot  | Highlights points, robust view of tails             |
| **Correlation/relationship**          | Scatter and trend line             | Position on two axes shows direct relation          |
| Network paths (sparse)                | Node-link                          | Paths are traceable visually                        |
| Network block structure (dense)       | Adjacency matrix                   | Communities become blocks                           |
| Hierarchy/taxonomy                    | Tree/dendrogram, indented list     | Structure is explicit                               |
| Causal structure/dynamics             | DAG**                              | Arrows & accumulators mirror cause/effect           |
More information on the types of visuals can be found in [[External Representations]].

References: Vessey (1991); Ware (2019), Kosslyn (2006), Munzner (2014), Tufte (2001).

---

## References

**Core theory of fit**  
  - Vessey, I. (1991). Cognitive fit: A theory-based analysis of graphs vs. tables. *Decision Sciences, 22*(2), 219–240.

**Perception & channel accuracy**  
  - Cleveland, W. S., & McGill, R. (1984). Graphical perception: Theory, experimentation, and application. *JASA, 79*(387), 531–554.  
  - Ware, C. (2019). *Information Visualization: Perception for Design* (4th ed.). Morgan Kaufmann.  
  - Kosslyn, S. M. (2006). *Graph Design for the Eye and Mind*. Oxford University Press.

**Visualization design handbooks**  
  - Munzner, T. (2014). *Visualization Analysis and Design*. CRC Press.  
  - Tufte, E. R. (2001). *The Visual Display of Quantitative Information* (2nd ed.). Graphics Press.


