# Sprite Cutter

This is a tool to manually create .atlastex texures from a single atlas/spriteshit texture

## How To Use

1 - Create a new scene with an AtlasScene root node.
2 - Add as many Sprite nodes as you want using region and the TextureRegion dock to define the region to use. The name of the node will be the name of the exported file.
3 - Set the export path. If it doesn't exist it will be created
4 - Go to Tools->Sprite Cutter: Export Atlas Textures

You can save the AtlasScene as a scene in case you ever need to change the sprite regions

If you change the AtlasScene just repeat step 4. Existing textures will be overwritten.

### License
MIT. See LICENSE.md