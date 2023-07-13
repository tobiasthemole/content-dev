# Content Creation Software: Blender 3D 3.0+

**Blender 3D** can now export entire materials as glTF binaries **(.glb)** or GLTF Imbedded files **(.glTF)** and import these into Second Life as a **Material object** in your Second Life inventory.
Direct exporting from Blender to PBR glTF results in higher quality textures with less compression than the legacy method. The procedures for creating glTF files are documented below.

First install the plugin **Import-Export glTF 2.0 format** in the **Add-ons** section of the **Preferences Menu** if it is not installed already.

![Blender_glTF_Plugin_AddonsUI](https://github.com/tobiasthemole/content-dev/assets/137837207/40ad2a97-e0fa-4212-a10b-f96cbcd9cfb1)

## **Short form Node Setup for Blender to glTF Export**

Press Spacebar in the Node Editor and Search **gltf**, select **Add (Shift A) Output glTF Material Output** to add your GLTF export node for **Occlusion**. 

![Blender_Nodes_ glTF_Shortform](https://github.com/tobiasthemole/content-dev/assets/137837207/6ed3b827-03b4-4743-81f5-3f539ad4a52f)

## **Long form Node Setup for Blender to glTF Export**

Press Spacebar in the Node Editor and Search **gltf** and select **Add (Shift A) Output glTF Material Output** to add your glTF export node for **Occlusion**.

![Blender_Node_ glTF_Longform](https://github.com/tobiasthemole/content-dev/assets/137837207/4f2bd465-dc6b-4778-812a-acce2f17d6ec)

## File Export for glTF in the Blender user interface

![Blender_ExportUI](https://github.com/tobiasthemole/content-dev/assets/137837207/12bdbdc2-a186-4592-a806-b9b01e14bd48)

## glTF export Window for Blender user interface

![Blender_glTF_ExportUI](https://github.com/tobiasthemole/content-dev/assets/137837207/aee4d99b-40e0-4677-9c72-55a4f7f59e13)

glTF export types are glTF Binary (**.glb**), glTF Separate (**.gltf** + **.bin** + **textures**), glTF Imbedded (**.gltf**)
