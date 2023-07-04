## Glossary Terms

**Prim**
 - Refers to Primitive which is the most basic building block of the Second Life experience engine
 - Also describes the 3D primitive shapes which users can assign textures, materials, LSL code, and inventory objects to be contained within.

**LSL is the Linden Scripting Language**
 - LSL gives behavior to Second Life Primitives, Objects, and Avatars

**PBR refers to Physically Based Rendering**
 - PBR is a realistic way of rendering physically accurate materials in a 3D world.
 - PBR can also refer to types of Materials
 - Second Life's PBR is based from the PBR-glTF standard

**glTF is the GL Transmission Format from the Khronos Group**
 - It has been described as the JPEG of 3D formats
 - It will soon be Second Life’s 3D format starting with Materials
 - It includes the formats .glb and .gltf
 - .glb is the file container format for glTF. It bundles all materials into a single file

**Advanced Lighting Model (ALM) is going away**
 - Now there will be unity between graphics settings and clients.
 - What you see is what you get from Low to High graphics settings.

**Image Based Lighting (IBL) via Reflections and Probes.**
 - IBL will allow the colors from one object to appear on another via reflection.
 - Light can bounce and scatter lighting up areas or darkening others.

**High Dynamic Range (HDR) is now present in Second Life EEP lighting**
 - HDR allows bright things to appear bright and very dark things to appear even darker.
 - Second Life before HDR was always ambiently lit via gamma manipulation. 

**Tonemapping**
 - To be compliant with industry standards, ACES is now Second Life’s Tonemapper
 - Tonemapping will allow “what you see is what you get” from Substance Painter to SL
 - Second Life uses an ACES implementation based on the AP1 primaries, and the final rendered image is in the ACEScg color space.

**Materials are a type of object or object data**
 - Materials are a type of object in your inventory to use on Prims, Mesh, and Terrain
 - There are 2 types of Materials in Second Life: Blinn-Phong and PBR glTF

**ORM is the texture format for Materials PBR glTF**
 - O is for Occlusion (as in Ambient Occlusion or AO) stored in R of the RGB
 - R is for Roughness as in how rough a material will be stored in G of the RGB
 - M is for Metalness as in how metallic a material will be stored in the B of the RGB
	
**Reflection Probes are a Prim property that allow the capturing of reflections for IBL and HDR**
 - Reflection probes are a Sphere or Box
 - They feature Ambiance and Nearclip settings

**MikkT Space Normals are the new style of normals dictated by PBR glTF** 
 - They are Second Life’s new 3D normals format
 - These are activated on assets in SL by applying a PBR material to them
