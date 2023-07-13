# Reflection Probes

**Reflection Probes** are a **Prim** property that allows the capturing of reflections for IBL and HDR  
- **Reflection Probes** are a Sphere or Box  
- **Ambiance** is a setting that Affects how much objects within the volume are lit  
- **Near Clip** will make the Probe volume exclude objects N meters from the center so they don’t get included in the reflection  
- Probe reflections can also be **Dynamic**. This means there is movement in the reflections  
- They can rotate and stretch like other objects but they cannot be changed in other ways other than Sphere, Box, Ambiance, or Near clip  
- They are Yellow in color and Blue when inside mesh geometry  

Below is a demonstration of Second Life's UI demonstrating how to show Reflection Probes and making them selectable.

![ReflectionProbeUI](https://github.com/tobiasthemole/content-dev/assets/137837207/6b7b56e4-a563-4e6d-a4a6-1668ce5baaaf)

Below is an ideal arrangement of box probes in a 3D scene as featured in Counter-Strike: Global Offensive by Valve Software (Video credit to 3ClicksPhilip on youtube)

![ReflectionProbes_CSGO_2ClicksPhilip](https://github.com/tobiasthemole/content-dev/assets/137837207/4fc2e516-1451-4059-bbd7-62ff11f8cbda)
