# Material: PBR GLTF

**PBR-glTF** (**PBR**) is the newest Material type introduced to Second Life.  

It is also most importantly an **Object**. This object contains the textures and associated metadata. All textures are compressed, however the normal map uses “lossless” compression to avoid artifacting. Slots are seen as below:

**Uploading materials as GLB/GLTF files via the Material Upload options tab is recommended over individually uploading textures in-world.  
Placing individual PBR textures into Blinn-Phong material slots expecting the same quality as PBR-glTF will result in compression as this is hardcoded in Second Life for that format and only glTF is exempt from this rule in any form.**

## **PBR uses the ORM format (Occlusion, Roughness, Metallic)**

![RGB_ORM](https://github.com/tobiasthemole/content-dev/assets/137837207/194b4b48-88c5-463b-83d6-efe1a111e6df)

**Base Color** (aka **Albedo**)
- This is your base color texture.
- Includes a **Tint** selection box for color that opens a colorpicker
- **Transparency** box with values from 0 to 1
- Alpha mode with Selection box (**Opaque, Blend, Mask**)
- Albedo is a texture with no lighting information in it.
- Baking lighting into Albedo will result in undesirable lighting on your object.

**Ambient Occlusion, Roughness, Metalness** (aka **ORM**)
- **Ambient Occlusion** is soft shadows
- **Roughness** is how Rough something is
- **Metalness** is how shiny or reflective something is (based on metals)

**Emission**
- **Emission** emits light from a surface
- You can tint it a color (either via the tint selection box, or color data in the emission texture)
- Previously only existed in TARGA files, not in PNG or JPEG

**Normal**
- It is an **OpenGL (Y+)** Normal format
- This map is normally blue and purple coloured. It will give your mesh height and depth.

**Fine Tuning**
- **Roughness** and **Metalness** can be modulated via the number boxes from 0.0 to 1.0
- **Double Sided** (Tickbox at top of Material window)
- You do not need to duplicate mesh and flip normals to get backfaces
- It is set to Off by default to avoid unneeded render cost. Use only when needed.

## **Mapping / Tiling options for PBR**

<img width="955" alt="glTF_TextureAlignment_Manipulation" src="https://github.com/tobiasthemole/content-dev/assets/137837207/2e1a8308-6b56-401c-8cc2-7819d8aa5335">

**Texture alignment** is controlled by the Mapping coordinate entries on each bubble tick slot

**Mapping** controls the type or style of mapping for the selected faces by parent face
- Controlled by activating the pulldown tab and selecting between Planar or Default
- **Planar** aligns selected faces planarly by parent object to grid plane by pressing **Align**
- Best with **Prims** or mostly grid facing meshes made with flat UV projection

**Scale u** Controls scale in the horizontal from side to side from -X to +X on a UV grid

**Scale v** Controls scale up and down from -Y to +Y on a UV grid

**Rotation** from the origin of the UV coordinates (0, 0) which corresponds to the upper left corner of a texture image per Khronos GLTF Specification

**Offset u** Controls **Offset** from side to side from -X to +X on a UV grid

**Offset v** Controls **Offset** up and down from -X to +X on a UV grid
