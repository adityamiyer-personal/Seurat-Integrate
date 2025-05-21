<!-- # SeuratIntegrate (development version) -->

# SeuratIntegrate 0.4.1

* Revised score rescaling with a new option enabling min-max rescaling of ranks
(default) rather than scores directly (as in
[Luecken *et al.*, 2021](https://doi.org/10.1038/s41592-021-01336-8))

* Speed up Dijkstra's algorithm-like used in `ExpandNeighbours` with a new c++
implementation

* The most suited matrix format is automatically chosen for corrected counts
output by integration methods (should be dense matrix most of the time)

* Add support for scGraph metric ([Wang *et al.*, 2024](https://doi.org/10.1101/2024.04.02.587824))

* Improved speed of `CreateIntegrationGroups` for non-SCT assay in unambiguous cases


# SeuratIntegrate 0.4.0

* Initial public release
