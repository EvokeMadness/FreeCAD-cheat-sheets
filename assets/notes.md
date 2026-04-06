## Constraints

- Dimension (D)
	- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_Dimension.svg`
	- Horizontal (L)
		- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_HorizontalDistance.svg`
		> Dimensions the length of a horizontal line or distance between two points.
	- Vertical (I)
		- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_VerticalDistance.svg`
		> Dimensions the length of a vertical line or distance between two points.
	- Distance (K, D)
		- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_Length.svg`
		> Dimensions a line or distance between two points.
	- Radius/Diameter (K, S)
		- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_Radiam.svg`
		> Dimensions the diameter of a circle or the radius of an arc.
	- Radius (K, R)
		- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_Radius.svg`
		> Dimensions the radius of a circle or arc.
	- Diameter (K, O)
		- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_Diameter.svg`
		> Dimensions the diameter of a circle.
	- Angle (K, A)
		- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_InternalAngle.svg`
		> Dimensions the angle between two lines.
	- Lock (K, L)
		- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_Lock.svg`
		> Applies a **Distance** constraint to a point relative to the sketch origin. Preselect one point before invoking this command.
- Coincident (C)
	- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_Coincident.svg`
	- Point on Object (None)
		- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_PointOnObject.svg`
		> A point attached to another point, line, or arc. This constraint is automatically created by Coincident following FreeCAD version 1.0.
- Horizontal/Vertical (A)
	- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_HorVer.svg`
	> Ensures the selected line always stays horizontal or vertical on this sketch plane, determined by its closest alignment.
	- Horizontal (H)
		- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_Horizontal.svg`
		> Ensures the selected line always stays horizontal on this sketch plane.
	- Vertical (V)
		- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_Vertical.svg`
		> Ensures the selected line always stays vertical on this sketch plane.
- Parallel (P)
	- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_Parallel.svg`
	> Orients two lines to be parallel. | Use in conjunction with **Equal** to make both lines the same length.
- Perpendicular (N)
	- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_Perpendicular.svg`
	> Orients two lines to be perpendicular. | Use in conjunction with **Coincident** to create a T-shape.
- Tangent/Collinear (T)
	- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_Tangent.svg`
	> Attach an arc or ellipse to a line or another arc/ellipse. Can also be used to make two arcs/ellipses tangent and two lines collinear.
- Equal (E)
	- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_EqualLength.svg`
	> Ensures two lines share the same length or an arc or circle share the same radius. If both circles or arcs are unconstrained the second shape selected will match the first shape selected.
- Symmetric (S)
	- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_Symmetric.svg`
	> Orients two points to share the same distance and angle from a line. Preselect two points and a line before invoking this command. | Use **Equal** to ensure figures symmetric across the line are mirrored. Use **Distance** to set the distance from the line of symmetry.
- Block (K, B)
	- `https://raw.githubusercontent.com/FreeCAD/FreeCAD/main/src/Mod/Sketcher/Gui/Resources/icons/constraints/Constraint_Block.svg`
	> Prevents lines from changing slope/angle, length or location.

* * *

```

Constraints ensure points or lines with a geometric relationship stay consistent throughout the sketch.

```

```

Menu bar → Tools → Customize... → Keyboard → Category: Sketcher

```
