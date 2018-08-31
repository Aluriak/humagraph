# humagraph
Graph viewing and editing for humans, with an emphasis on dot and bridges to other formats.

## Objectives
- [ ] WYSIWYG GUI, with colors, shapes and oriented edges support
- [ ] tooltips on edges and nodes
- [ ] call and apply positionning engines on graph (graphviz for instance)
- [ ] import from dot, nnf,…
- [ ] click and drag to modify (and fix) node position
- [ ] add (dot) attributes to nodes and edges
- [ ] export to dot, nnf, svg,…
- [ ] export view to png, svg,…

## Techno
Python + pyqt || Cpp + Qt


## Features

### Animation codes
User can define animation functions, that are python generators yielding styling to apply on (particular) elements. With a pause between each appliance, you can, for instance, show a graph traversal where already walked node in white and current node in green.

