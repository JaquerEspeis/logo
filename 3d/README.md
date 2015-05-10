How to convert a SVG to STL
===========================

1. Clone the following project:

	https://github.com/l0b0/paths2openscad

And install the .inx and .py files in ~/.config/inkscape/extensions

2. Open the original SVG image and resize it and join all objects into a single path.

3. Extensions -> Generate from Path -> Paths to OpenSCAD.

4. Open .scad file with OpenSCAD.

	sudo apt-get install openscad

5. Compile (F5), build (F6), Design -> Export to STL.
