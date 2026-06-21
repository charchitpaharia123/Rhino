# Rhino 8 Cheat Sheet

> A quick reference for the most commonly used Rhino commands.
>
> **Legend**
>
> * ⌨ Shortcut = Default keyboard shortcut (if assigned)
> * ❌ = No default shortcut (type the command or create an alias)

---

# Navigation

| Command      | Shortcut            | Description                                           |
| ------------ | ------------------- | ----------------------------------------------------- |
| Zoom         | Z                   | Zoom the active viewport.                             |
| ZoomExtents  | ZE                  | Zoom to show all objects.                             |
| ZoomSelected | ZS                  | Zoom to selected objects.                             |
| Pan          | Shift + Right Mouse | Move the viewport without rotating.                   |
| RotateView   | Right Mouse Drag    | Rotate perspective view.                              |
| SetView      | ❌                   | Change to predefined views (Top, Front, Right, etc.). |
| NamedView    | ❌                   | Save and restore camera views.                        |

---

# Selection

| Command          | Shortcut | Description                     |
| ---------------- | -------- | ------------------------------- |
| SelAll           | Ctrl + A | Select all objects.             |
| SelNone          | Esc      | Clear current selection.        |
| Invert           | ❌        | Invert the current selection.   |
| SelLast          | ❌        | Select the last created object. |
| SelDup           | ❌        | Select duplicate objects.       |
| SelBadObjects    | ❌        | Select invalid geometry.        |
| SelOpenPolysrf   | ❌        | Select open polysurfaces.       |
| SelClosedPolysrf | ❌        | Select closed solids.           |
| SelMesh          | ❌        | Select all meshes.              |
| SelCrv           | ❌        | Select all curves.              |
| SelSrf           | ❌        | Select all surfaces.            |

---

# Object Snaps (OSNAP)

| Snap       | Shortcut   | Description                    |
| ---------- | ---------- | ------------------------------ |
| End        | Status Bar | Snap to endpoint.              |
| Mid        | Status Bar | Snap to midpoint.              |
| Near       | Status Bar | Snap to nearest point.         |
| Center     | Status Bar | Snap to circle center.         |
| Quad       | Status Bar | Snap to quadrant.              |
| Vertex     | Status Bar | Snap to mesh/SubD vertices.    |
| Int        | Status Bar | Snap to intersections.         |
| Perp       | Status Bar | Snap perpendicular.            |
| Tan        | Status Bar | Snap tangent.                  |
| SmartTrack | Status Bar | Temporary construction guides. |

---

# Curve Creation

| Command           | Shortcut | Description                              |
| ----------------- | -------- | ---------------------------------------- |
| Line              | ❌        | Draw a straight line.                    |
| Polyline          | ❌        | Draw connected line segments.            |
| PolylineOnSrf     | ❌        | Draw a polyline directly on a surface.   |
| Arc               | ❌        | Create an arc.                           |
| Circle            | ❌        | Create a circle.                         |
| Ellipse           | ❌        | Create an ellipse.                       |
| Rectangle         | ❌        | Draw a rectangle.                        |
| Polygon           | ❌        | Create a regular polygon.                |
| ControlPointCurve | ❌        | Draw a NURBS curve using control points. |
| InterpCrv         | ❌        | Draw a curve through specified points.   |
| Helix             | ❌        | Create a helix or spring.                |
| Spiral            | ❌        | Create a spiral.                         |

---

# Curve Editing

| Command    | Shortcut | Description                                         |
| ---------- | -------- | --------------------------------------------------- |
| Move       | ❌        | Move selected objects.                              |
| Copy       | ❌        | Copy objects.                                       |
| Rotate     | ❌        | Rotate objects.                                     |
| Scale      | ❌        | Scale uniformly or non-uniformly.                   |
| Mirror     | ❌        | Mirror objects.                                     |
| Array      | ❌        | Create linear arrays.                               |
| ArrayPolar | ❌        | Create circular arrays.                             |
| ArrayCrv   | ❌        | Array along a curve.                                |
| Offset     | ❌        | Offset curves.                                      |
| Trim       | ❌        | Trim objects.                                       |
| Split      | ❌        | Split curves or surfaces.                           |
| Join       | Ctrl + J | Join curves or surfaces.                            |
| Explode    | ❌        | Separate joined geometry.                           |
| Extend     | ❌        | Extend curves or surfaces.                          |
| Fillet     | ❌        | Create rounded corners.                             |
| Chamfer    | ❌        | Create beveled corners.                             |
| Rebuild    | ❌        | Rebuild a curve or surface with new control points. |
| Match      | ❌        | Match curve continuity.                             |

---

# Surface Modeling

| Command     | Shortcut | Description                                 |
| ----------- | -------- | ------------------------------------------- |
| PlanarSrf   | ❌        | Create a planar surface from closed curves. |
| Loft        | ❌        | Create a surface through profile curves.    |
| Sweep1      | ❌        | Sweep using one rail.                       |
| Sweep2      | ❌        | Sweep using two rails.                      |
| Revolve     | ❌        | Revolve a profile around an axis.           |
| RailRevolve | ❌        | Revolve while following a rail.             |
| ExtrudeCrv  | ❌        | Extrude a curve into a surface or solid.    |
| ExtrudeSrf  | ❌        | Extrude an existing surface.                |
| EdgeSrf     | ❌        | Surface from 2–4 edges.                     |
| NetworkSrf  | ❌        | Surface from intersecting curves.           |
| Patch       | ❌        | Fit a surface through curves/points.        |
| BlendSrf    | ❌        | Blend two surfaces smoothly.                |
| MatchSrf    | ❌        | Match surface continuity.                   |
| OffsetSrf   | ❌        | Offset a surface.                           |

---

# Solid Modeling

| Command             | Shortcut | Description                      |
| ------------------- | -------- | -------------------------------- |
| Box                 | ❌        | Create a box.                    |
| Cylinder            | ❌        | Create a cylinder.               |
| Cone                | ❌        | Create a cone.                   |
| Sphere              | ❌        | Create a sphere.                 |
| Torus               | ❌        | Create a torus.                  |
| Pipe                | ❌        | Create a pipe around curves.     |
| BooleanUnion        | ❌        | Join solids into one.            |
| BooleanDifference   | ❌        | Subtract one solid from another. |
| BooleanIntersection | ❌        | Keep only overlapping volume.    |
| Cap                 | ❌        | Cap planar openings.             |
| Shell               | ❌        | Hollow a solid.                  |
| FilletEdge          | ❌        | Round solid edges.               |
| ChamferEdge         | ❌        | Bevel solid edges.               |
| BlendEdge           | ❌        | Smooth edge transitions.         |

---

# Mesh & SubD

| Command     | Shortcut | Description                        |
| ----------- | -------- | ---------------------------------- |
| Mesh        | ❌        | Convert NURBS to mesh.             |
| QuadRemesh  | ❌        | Generate clean quad topology.      |
| ToSubD      | ❌        | Convert mesh/NURBS to SubD.        |
| SubDBox     | ❌        | Create a SubD box.                 |
| ExtrudeSubD | ❌        | Extrude SubD faces.                |
| InsertEdge  | ❌        | Add supporting edge loops.         |
| Bridge      | ❌        | Bridge SubD edges or faces.        |
| Crease      | ❌        | Harden SubD edges.                 |
| Uncrease    | ❌        | Smooth previously creased edges.   |
| Reflect     | ❌        | Enable symmetry for SubD modeling. |

---

# Analysis

| Command            | Shortcut | Description                                 |
| ------------------ | -------- | ------------------------------------------- |
| Zebra              | ❌        | Analyze surface continuity.                 |
| CurvatureGraph     | ❌        | Display curvature graphs on curves.         |
| DraftAngleAnalysis | ❌        | Analyze manufacturability for molded parts. |
| ShowEdges          | ❌        | Find naked or non-manifold edges.           |
| Check              | ❌        | Validate geometry.                          |
| What               | ❌        | Display detailed object information.        |
| Volume             | ❌        | Calculate enclosed volume.                  |
| Area               | ❌        | Calculate area.                             |
| Length             | ❌        | Measure curve length.                       |
| Distance           | ❌        | Measure distance between points.            |

---

# Import / Export

| Command         | Shortcut         | Description                            |
| --------------- | ---------------- | -------------------------------------- |
| Import          | Ctrl + I         | Import supported file formats.         |
| Export          | Ctrl + E         | Export selected objects.               |
| ExportSelected  | ❌                | Export only selected objects.          |
| SaveAs          | Ctrl + Shift + S | Save under a new filename.             |
| IncrementalSave | ❌                | Save with automatic version numbering. |

---

# Useful Commands

| Command      | Shortcut         | Description                                          |
| ------------ | ---------------- | ---------------------------------------------------- |
| Undo         | Ctrl + Z         | Undo last action.                                    |
| Redo         | Ctrl + Y         | Redo last undone action.                             |
| Gumball      | Status Bar       | Toggle the Gumball manipulator.                      |
| CPlane       | ❌                | Set the active construction plane.                   |
| NamedCPlane  | ❌                | Save and restore construction planes.                |
| Hide         | ❌                | Hide selected objects.                               |
| Show         | ❌                | Show hidden objects.                                 |
| Lock         | ❌                | Lock selected objects.                               |
| Unlock       | ❌                | Unlock objects.                                      |
| Group        | Ctrl + G         | Group objects.                                       |
| Ungroup      | Ctrl + Shift + G | Ungroup objects.                                     |
| Make2D       | ❌                | Generate 2D drawings from 3D geometry.               |
| UnrollSrf    | ❌                | Flatten developable surfaces.                        |
| Squish       | ❌                | Flatten doubly curved surfaces approximately.        |
| FlowAlongSrf | ❌                | Morph objects across a surface.                      |
| OrientOnSrf  | ❌                | Place objects onto a target surface.                 |
| History      | ❌                | Enable construction history for associative updates. |

---

# Recommended Commands to Memorize First

1. Line
2. Polyline
3. Circle
4. Rectangle
5. Move
6. Copy
7. Rotate
8. Scale
9. Trim
10. Split
11. Join
12. Offset
13. ExtrudeCrv
14. Loft
15. Sweep1
16. BooleanUnion
17. BooleanDifference
18. FilletEdge
19. Gumball
20. CPlane
21. QuadRemesh
22. ShowEdges
23. Check
24. Make2D
25. ExportSelected

---

**Tip:** Rhino has relatively few built-in keyboard shortcuts for modeling commands. Most commands are invoked by typing their names or by assigning custom aliases. Many experienced users create personalized aliases (for example, `L` → `Line`, `PL` → `Polyline`, `BC` → `BooleanDifference`) to speed up their workflow.
