**Top Down Design**
Main function
	gets user inputs
		screen_size, colours
	draws patchwork
		tile 1
		tile 2
		plain tile
		patchwork layout
			conditions for colours
			conditions penultimate tile (tile 1)
			conditions for final tile (tile 2)
	challenge features
		select a tile
		change selected tile
			if key pressed do x
				x - delete patch, leave empty tile
				1,2,3 - new tile 1 in respective colour
				4,5,6 - new tile 2 in respective colour
				7,8,9 - new plain tile in respective colour
				esc - deselect the patch
				arrow keys - move patch in direction if direction tile is empty, leaving current selected tile empty(1 sec animation)
----
**General Notes**
create list of all points

use lists to change colour of specific points

use lists to determine what goes in specific points - how is this affected when screen_size changes? screen_size is a loop condition with abstract values inside loop

for tile 2:
	draw circle
	draw triangle pair
	use flags for alternating circle/triangle
	use flag for alternating direction of triangles based on row they are in

select patch with mouse click
determine top left point

for 'x' pressed:
	match top left point to patch type(1, 2, plain)
	undraw patch