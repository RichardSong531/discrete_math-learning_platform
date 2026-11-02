# Graphs references

Primary source: **Steven T. Dougherty, Frederique Oggier, and Murong Xu, Graphs**,
supplied as five PDF parts. No publication date was identified in the supplied
chapter. Reviewed 2026-11-02; the original PDFs are not redistributed here.

| Supplied file | Printed pages | Main material |
| --- | --- | --- |
| `Graphs-pages-1.pdf` | 1–10 | Bridges, graph definitions, simple graphs, counting, subgraphs, adjacency, start of degree sequences |
| `Graphs-pages-2.pdf` | 11–20 | Degree sequences, regular graphs, complete and multipartite graphs, graph families, isomorphism |
| `Graphs-pages-3.pdf` | 21–30 | Paths, distance, eccentricity, connectivity, component bounds, Euler routes |
| `Graphs-pages-4.pdf` | 31–40 | Euler examples, Hamilton routes, sufficient degree conditions, TSP, vertex coloring |
| `Graphs-pages-5.pdf` | 41–46 | Components and coloring, planarity, four-color theorem, chromatic polynomials, bibliography |

Lesson page references use the continuous printed page numbers. In part j, local PDF
page 1 corresponds to printed page `10(j−1)+1`; the last part has six pages.
Some printed pages also contain lecture slides.

## Source corrections and conventions

- Page 25, Example 36: for a simple graph with 9 vertices and 3 components, the
  theorem gives `6 ≤ m ≤ C(7,2)=21`; the example prints 15 as its upper bound.
  The imported map already uses 21, consistent with the theorem and its proof.
- Page 45: the printed C5 expression gives 36 for three labeled colors. Direct
  enumeration gives 30. The map retains the correct cycle formula
  `P_Cn(x)=(x−1)^n+(-1)^n(x−1)` for `n≥3`; the lab counts assignments directly.
- Pages 38–45 call the minimum number of vertex colors the “chromatic index.”
  This map uses **chromatic number** for vertex coloring; chromatic index normally
  refers to edge coloring.
- The slide on page 31 must qualify the two-odd-vertices statement as an **open**
  Euler trail. A closed Euler circuit has zero odd-degree vertices. The map also
  requires connectivity among vertices incident to edges; isolated vertices do not
  prevent an edge-covering tour. A graph with no edges admits a trivial closed trail.
- The source's broad path/cycle definitions on page 21 permit repeated vertices.
  The map distinguishes that walk/closed-walk usage from simple paths/cycles and
  uses Hamilton cycles with at least three vertices.
- Adjacency-preserving vertex bijections characterize simple-graph isomorphism.
  General multigraph isomorphism must also preserve edge multiplicities and loops.
- Simple-graph component bounds and the Ore/Dirac criteria are not applied to the
  multigraph preset; the latter also require at least three vertices. Four-color
  statements concern finite loopless planar graphs. Loops prevent proper vertex
  coloring and count twice toward degree.

The source collection is [Discrete Mathematics Resources](https://sites.google.com/view/discretemathematicsresources/home).
This record identifies the supplied material; it does not establish course endorsement
or alter source reuse terms.
