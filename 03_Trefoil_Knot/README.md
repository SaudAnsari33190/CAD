3-Loop — Trefoil Knot

Inspiration: Dr. STONE — Medusa
Software: Autodesk Fusion 360

This was my first attempt at creating a more complex 3D form rather than relying primarily on basic sketch-and-extrude operations.
Before this project, most of my CAD work consisted of 2D sketches, extrusions, fillets, intersections, and combining bodies. 
I initially tried constructing the loop using guide circles and paths, but I couldn't get the geometry to behave like the continuous, bending pipe-like form I wanted.
The turning point was discovering 3D Sketches in Fusion 360.

Construction

I started with a large triangular construction framework and an inverted, smaller triangle inside it. The inner triangle was then extruded symmetrically along the perpendicular direction.
This produced six spatial reference points — three above and three below the main sketch plane. I used these points to construct a 3D fixed-point spline, which became the centerline for the final form.
The spline was then used with Fusion 360's Pipe feature to generate the solid body.
The final geometry itself was relatively quick to create. Most of the time was spent experimenting with the dimensions of the outer triangle, inner triangle, and extrusion distance until the resulting loop had the proportions and symmetry I wanted.

What I learned

3D Sketches can completely change how complex geometry can be approached.
Construction geometry can be more useful than trying to directly model the final shape.
A relatively simple set of reference points can define surprisingly complex 3D geometry.
Creating the feature is often the easy part; getting the proportions and symmetry right takes considerably more iteration.
I also learned that when a 2D approach starts becoming unnecessarily complicated, it can be worth stepping back and looking for a 3D construction method instead.

Process

2D construction → symmetric extrusion → 3D reference points → fixed-point spline → Pipe → dimension iteration → final model
