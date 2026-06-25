# Tile the Floor

A visual simulation demonstrating the principles of Euclidean tessellation and regular tiling constraints.

## Core Features
* **Grid Tessellation:** Allows users to attempt to tile a flat surface with no gaps and no overlaps using regular polygons (triangles, squares, pentagons, hexagons).
* **Vertex Angle Calculator:** Dynamically computes the sum of interior angles at any shared vertex to demonstrate why only three regular tessellations exist ($\sum \theta = 360^\circ$).

## Mathematical Logic
The application enforces the regular tessellation rule:
$$\frac{2n}{n-2} = k$$
where $n$ is the number of sides of the polygon and $k$ must be an integer.
