# 3D models

[https://www.youtube.com/watch?v=l2PQDI7uEFM](https://www.youtube.com/watch?v=l2PQDI7uEFM)

[https://www.youtube.com/watch?v=oW1mAlkRdRI&t=2552s](https://www.youtube.com/watch?v=oW1mAlkRdRI&t=2552s)

Process for importing from Eldritch Foundry:

1. Download .stl, use the "unified" version
2. Paint the model using Adobe Substance Painter 3D
3. When finished, re-export the model as .fbx in addition to its textures so the UV map is correct
4. Import the .fbx into a new Blender project and resize all dimensions by 0.04
5. Rotate so the model is "facing" in the negative X direction (red line)
6. Make sure "shade smooth" is checked?
7. Export as .obj
8. Import into TTS modding project along with generated texture files from Substance
9. Check "read/write" on the created gameobject and extract the material
10. Add the texture files to the material
11. Create a prefab by dragging the gameobject to the bottom pane
12. Select an assetbundle target for the prefab in the lower right
13. Right-click the prefab and export assetbundle
14. Import into TTS as custom assetbundle of type "figurine"

Process for importing from HeroForge:

1. Download .stl from HeroForge
2. Open a new project in Blender and import the .stl
3. Delete default cube, camera, and light
4. Rescale model to 0.04 in all dimensions
5. Translate model 0.11m on Z axis
6. Rotate model on Z axis as needed to align front with Red gridline (-25 degrees or so, usually)
7. Decimate model with ratio 0.25
8. Export as .obj
9. In TTS, add a new object → component → custom → model
10. For "Model/Mesh", select the .obj file & upload to steam cloud
11. Optionally, turn off specular highlights in "material"
12. Import!
13. Set the type to "figurine" so that the model rights itself automatically
14. Set the collision mesh to: [http://cloud-3.steamusercontent.com/ugc/787500561500165346/A029BDDDB83C8DDDCF42CE357C5C7D0C9865944C/](http://cloud-3.steamusercontent.com/ugc/787500561500165346/A029BDDDB83C8DDDCF42CE357C5C7D0C9865944C/)
15. Make the object ignore fog of war and reveal fog of war
16. Set up the revealer

# TTS table settings

The custom RPG table is:

- 1.693:1 as an aspect ratio
- 88 1" squares by 52 1" squares as grid spaces, or 4,576 grid squares
- 440ft by 260ft as in-game space, or 114,400 square feet
- 1600px by 945px or 3200px by 1890px as an image (for One World)

580ft x 420ft = 116in x 84in

# Eldritch Foundry

## Wearer of Purple costume

- Neck: underdark collar
- Torso: robe top or monk's vestments
- Pants: simple robe bottom
- Cape: short cape
- Runic base?

# Common models TODO

- Dragonclaw/fang/soul/wing
-