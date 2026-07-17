# Outlining builds

Inside the server, you will see that many buildings are marked by a brick outline on the ground. Although these pregenerated outlines can be useful to get an idea of the general location of the buildings, it is important to verify the outline of each building to ensure that the proportion, rotation, and position are correct.

To do this, we will use WorldEdit and the `/tpll` command:

## Obtaining coordinates from Google Maps

??

`VIDEO WEBP 1`

1. Open Google Maps and search for the location of the building.
2. In the bottom-left corner, make sure that the satellite view is active (realistic image mode) as well as the globe view.
3. Move your cursor to the first corner of the building.
4. Right-click. A dialog box will appear; click on the first option (which shows a set of numbers).
5. The coordinates will be copied to your clipboard in latitude and longitude format.

## Marking down the corners in Minecraft

??

`VIDEO WEBP 2`

1. On the Minecraft server, open the chat and type the following command: `/tpll`, add a space, and press **Ctrl + V** to paste the coordinates you copied earlier. You will be teleported to the exact coordinates on the server.
2. Mark the location with a block of your choice. You can use different colored wools to define different outlines (buildings, sidewalks, streets, trees, etc.).
3. Go back to Google Maps, move your cursor to another corner of the building, and repeat the same process for the rest of the building's corners.

## Creating the outlines

??

`VIDEO WEBP 3`

1. In Minecraft, using the wooden axe (use `//wand` if you don't have the axe, or grab it from your creative inventory), type the command `//sel cuboid` to select the cuboidal selection.
2. Left-click on one of the corners you marked with wool, and right-click on another marked corner that is next to the previous one.
3. Type the command `//line [block]`. In **[block]**, you must enter the name of the block you want to use to create the building's outline. For example, we will use light blue wool, so we will type `//line light_blue_wool`. This way, WorldEdit will create a line with light blue wool outlining one of the facades of the building we want to make.
4. Repeat this process for each of the sides that make up the building until you get a closed outline.
