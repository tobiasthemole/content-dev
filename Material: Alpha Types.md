# Material: Alpha Types

There are three stages of **Alpha** in Second Life. They are **Opaque**, **Alpha Blended**, and **Alpha Masked**.

**Opaque** (aka **None**)
- This is a texture’s default state without Alpha.
- Photoshop and Substance may export alpha layers. Only do this on purpose.
  
**Alpha Blending**
- **Alpha Blending** is reserved for things you must see through and nothing else.
- Suffers from **Alpha Sorting** issues that are common to almost all 3D graphics engines
- Most of the time creators should not use this as it causes CPU/GPU slowdown.
  
**Alpha Masking**
- **Alpha Masking** is the preferred method for doing anything that must feature alpha.
- The strength of the **Alpha Masking** effect is modulated via the number box 
- It is more efficient than Alpha Blending and suffers from no **Alpha Sorting** distortions

 ## **Alpha for Blinn-Phong Dropdown**

![Blinn-Phong_AlphaModes](https://github.com/tobiasthemole/content-dev/assets/137837207/9a4d4fb0-c0da-4a6d-9475-1ecdbadd7532)

## **Alpha Mask Cutoff Number Box for Blinn-Phong**

![Blinn-Phong_Alpha_Masking](https://github.com/tobiasthemole/content-dev/assets/137837207/8771af91-c9e8-4617-b84b-fe296d95cbbe)

## **Alpha for PBR glTF with Transparency**
**Alpha Mode selection dropdown box as well as Alpha Cutoff featured internally in Material object**

![PBR-glTF_AlphaModes](https://github.com/tobiasthemole/content-dev/assets/137837207/3d035332-9196-4aa1-afc2-e86f09066c27)
