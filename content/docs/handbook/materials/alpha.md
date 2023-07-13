---
title: Alpha Types
weight: 1
---

# Alpha Types

There are three states of **Alpha** in Second Life. They are **Opaque**, **Alpha Blended**, and **Alpha Masked**.

## Opaque (aka **None**)
- This is a texture’s default state without Alpha.
- Photoshop and Substance may export alpha layers. Only do this on purpose.
  
## Alpha Blending
- **Alpha Blending** is reserved for things you must see through and nothing else.
- Suffers from **Alpha Sorting** issues that are common to almost all 3D graphics engines
- Most of the time creators should not use this as it causes CPU/GPU slowdown.
  
## Alpha Masking
- **Alpha Masking** is the preferred method for doing anything that must feature alpha.
- The strength of the **Alpha Masking** effect is modulated via the number box 
- It is more efficient than Alpha Blending and suffers from no **Alpha Sorting** distortions

## Alpha for Blinn-Phong Dropdown

![Blinn-Phong_AlphaModes](/images/Blinn-Phong_AlphaModes.jpg)

## Alpha Mask Cutoff Number Box for Blinn-Phong

![Blinn-Phong_Alpha_Masking](/images/Blinn-Phong_Alpha_Masking.jpg)

## Alpha for PBR glTF with Transparency

Alpha Mode selection dropdown box as well as Alpha Cutoff featured internally in Material object

![PBR-glTF_AlphaModes](/images/PBR-glTF_AlphaModes.jpg)
