## 1) Why offloading matters 
Working memory is sharply limited (on the order of ~4 chunks) and easily overloaded when we must remember labels, values, and steps while reasoning. Well-designed visuals pin these elements in the world: labels next to marks, stable spatial layouts, visible states. So users can look back rather than remember. This reduces extraneous load and leaves more capacity for germane load (schema building), which is where mental models form and update.

---
## 2) Design decisions that offload memory

- Co-locate labels with marks (minimize legend lookups → fewer memory hops).
- Stable spatial layout (use consistent axes/order so locations become memory indices).
- Chunking via grouping and enclosure (Gestalt grouping turns many items into a few chunks).
- Expose state explicitly (current filters, parameter values, selected subsets shown *on* the canvas).
- Stepwise panels / small multiples (externalize temporal steps so users compare rather than recall).
- Inline annotations & signalling (arrows, highlights) to mark causal or critical relations.
- Externalize calculation (totals, differences, rates shown as derived marks so users don’t compute in head).

---

## 3) When offloading backfires (and how to fix it)

- Split attention: labels in a distant legend, units in a footnote → Fix: co-locate, repeat units inline.  
- Cluttered canvases: everything is visible but nothing is salient → Fix: signaling, hierarchy, progressive disclosure.  
- Transient info in animations: states disappear → Fix: add trails/ghosting, or use small multiples.  
- Too many simultaneous encodings: users must remember mapping rules → Fix: simplify channels; use position/length first.

---

## 4) How to tell it worked

- Prediction tasks: users forecast the next value/state more accurately after offloading changes.  
- Reduced revisits: fewer eye-movement regressions or interaction back-and-forth for lookups.  
- Lower subjective load: NASA-TLX or single-item mental effort ratings drop *with equal or better accuracy*.  
- Transfer: users solve a novel but structurally similar visual task faster.

---

## References
  - Cowan, N. (2001). The magical number 4 in short-term memory. *Behavioral and Brain Sciences, 24*(1), 87–185.
  - Risko, E. F., & Gilbert, S. J. (2016). Cognitive offloading. *Trends in Cognitive Sciences, 20*(9), 676–688.
  - Sweller, J., Ayres, P., & Kalyuga, S. (2011). *Cognitive Load Theory*. Springer.  
  - Mayer, R. E. (2009). *Multimedia Learning* (2nd ed.). Cambridge University Press.
  - Larkin, J. H., & Simon, H. A. (1987). Why a diagram is (sometimes) worth ten thousand words. *Cognitive Science, 11*(1), 65–100.