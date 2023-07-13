# Material: Blinn-Phong

 **Blinn-Phong** for the Specular Glossiness workflow (SpecGloss) is the older of Second Life's two material types. 

## **Blinn-Phong** for Second Life has has 3 texture slots:

**Diffuse** (aka **DIFF**)

This is your basic color texture for an object
In Second Life **Blinn-Phong** objects **Diffuse** also has **Emission** in its **Alpha Channel**. 
JPEG, PNG, and TARGA live here

**Normal** (aka **NRML**)
Can store **Glossy** information in its **Alpha Channel**
This map is normally purple/blue coloured. It will give your mesh height and depth.

**Specular** (aka **SPEC**)
A Specular texture dictates how Rough or Shiny an object is
Environmental Intensity (more Glossy) in its **Alpha Channel**

**Specularity Options** for Blinn-Phong

![Blinn-Phong_SpecularGlossy_Options](https://github.com/tobiasthemole/content-dev/assets/137837207/0658a9c9-50ff-4f17-a8e9-8bc507079075)

**Specularity** (Shininess) can be manipulated with 3 tabs:

**Glossiness** tells the object how shiny the object is

**Environment** tells the object how mirror like the object is

**Color** tells the object what color to make the Glossy highlighting

## **Mapping / Tiling options for Blinn-Phong**

<img width="955" alt="Blinn-Phong_TextureAlignment_Manipulation" src="https://github.com/tobiasthemole/content-dev/assets/137837207/16638e47-a715-43cd-9de1-860ce96e70dc">

**Texture alignment** for all the material slots is controlled separately by 3 bubble switches or locked together by the Lock repeats checkbox

**Mapping** controls the type or style of mapping for the selected faces by parent face
Controlled by activating the pulldown tab and selecting between Planar or Default
**Planar** aligns selected faces planarly by parent object to grid plane by pressing **Align**
Best with **Prims** or mostly grid facing meshes made with flat UV projection

**Horizontal scale** Controls scale in the horizontal from side to side

**Vertical scale** Controls scale up and down

**Repeats per meter** controls the tiling or repeats per meter of the texture map

**Rotation degrees** rotates the texture in degrees from the center of the grid

**Horizontal offset** offsets the texture from side to side

**Vertical offset** offsets the texture up and down
