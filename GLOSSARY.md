## GLOSSARY TERMS

**Prim**
 - Refers to **Primitive** which is the most basic building block of the Second Life experience engine
 - Also describes the 3D primitive shapes which users can assign textures, materials, LSL code, and inventory objects to be contained within.

**LSL** is the Linden Scripting Language**
 - **LSL** assigns behavior to Second Life Primitives, Objects, and Avatars

**Blinn-Phong**
 - Second Life's original Materials system was based from a **Blinn-Phong Shader**
 - The shader worked with a specular-Glossiness system

**PBR** refers to Physically Based Rendering**
 - **PBR** is a realistic way of rendering physically accurate materials in a 3D world.
 - **PBR** can also refer to types of Materials
 - Second Life's **PBR** is based from the **PBR-glTF Standard**

**glTF** is the GL Transmission Format from the Khronos Group**
 - It has been described as the JPEG of 3D formats
 - It will soon be Second Life’s 3D format starting with Materials
 - It includes the formats **.glb** and **.gltf**
 - **.glb** is the file container format for glTF. It bundles all materials into a single file
 - In this documentation PBR-glTF (PBR) will refer to the Materials side of the format as it relates to Second Life's object system.

**Advanced Lighting Model (ALM)** is the soon to be deprecated lighting system**
 - The removal of multiple renderers will create unity between graphics settings and clients.
 - What you see is what you get from Low to High graphics settings.

**Image Based Lighting (IBL)** via **Reflections and Probes**
 - **IBL** will allow the colors from one object to appear on another via reflection.
 - Light can bounce and scatter lighting up areas or darkening others.

**EEP** refers to the Dynamic Skies system of the Second Life experience engine.**
- The dynamic skies system will allow HDRI import in the near future
- The Name EEP referred to a project called the Enhanced Environment Project.
- Skies in SL are still called EEPs due to this historical naming convention

**High Dynamic Range (HDR)** is now present in Second Life EEP lighting**
 - **HDR** allows bright things to appear bright and very dark things to appear even darker.
 - Second Life before **HDR** was always ambiently lit via gamma manipulation. 

**Tonemapping**
 - To be compliant with industry standards, **ACES** is now Second Life’s Tonemapper
 - **Tonemapping** will allow “what you see is what you get” from Substance Painter to SL
 - Second Life uses an **ACES** implementation based on the AP1 primaries, and the final rendered image is in the **ACEScg** color space.

**Materials** are a type of object or object data**
 - Materials are a type of object in your inventory to use on Prims, Mesh, and Terrain
 - There are 2 types of Materials in Second Life: Blinn-Phong and PBR glTF

**ORM** is the texture format for Materials PBR glTF**
 - **O** is for **Occlusion (as in Ambient Occlusion or AO)** stored in R of the RGB
 - **R** is for **Roughness** as in how rough a material will be stored in G of the RGB
 - **M** is for **Metalness** as in how metallic a material will be stored in the B of the RGB
	
**Reflection Probes** are a Prim property that allow the capturing of reflections for IBL and HDR**
 - **Reflection Probes** are a Sphere or Box (in the form of a **Prim**)
 - They feature **Ambiance** and **Nearclip settings**
 - They can also be set to **Dynamic**

**MikkT Space Normals** are the new style of normals dictated by PBR glTF** 
 - They are Second Life’s new 3D normals format
 - These are activated on assets in SL by applying a **PBR Material** to them
