## PBR glTF in Second Life Intro ##

Second Life is now adopting a new lighting engine. This engine is based on the glTF PBR specification by the Khronos Group https://github.com/KhronosGroup/glTF. This specification allows extremely easy and safe interchange between various formats and Second Life.

You may notice older objects (**Blinn-Phong**) look somewhat different post PBR release. 
Some darker texture maps will have become somewhat too dark and some ones too bright. 
This has to do with moving from **sRGB** to a **Linear RGB Intermediary Colorspace** as required by modern standards. 

**HDR** or **High Dynamic Range** and **ACES Tonemapping** is part of Second Life’s transition to PBR. These allow deep dark and intense bright colors as well as lighting. 
Below is a comparison shot between these two new features on and with them off:

**HDR/TONEMAPPING ON**

![SecondLife_HDR_On](https://github.com/tobiasthemole/content-dev/assets/137837207/9c439f63-827a-4793-a679-6edfe1e86731)

**HDR/TONEMAPPING OFF**

![SecondLife_HDR_Off](https://github.com/tobiasthemole/content-dev/assets/137837207/6cf56948-fdb2-4942-9cf0-28d27ed87219)
