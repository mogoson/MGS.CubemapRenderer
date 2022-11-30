# MGS.CubemapRenderer

## Summary
- Unity Cubemap renderer.

## Environment

- Unity 5.0 or above.
- .Net Framework 3.5 or above.

## Version

- 1.0.0

## Demand

- Render a scene into a static Cubemap asset for Skybox material or reflective material.

## Prerequisite
- Unity provide the ScriptableWizard class to quickly create extend editor window.
- Unity provide the API(RenderToCubemap method of the Camera class) to render Cubemap.

## Scheme
- Write extend editor code, select source camera and config the parameters for create Cubemap.
- Select path and input file name to save the render Cubemap.

## Usage
1. Find the menu item "Tool/Cubemap Renderer" in Unity editor menu bar and click it or press key combination Alt+C to open the editor window.
1. Create/Select a scene camera as the "RenderCamera" if no main camera in your scene.
1. Config the parameters "Face Size", "Texture Format" and "Mipmap" for create Cubemap.
1. Click the "Render" button to open the dialog of save new render cubemap.
1. Select a path and input a file name to dialog and save.

## Source
- https://github.com/mogoson/MGS.CubemapRenderer.

------

Copyright © 2021 Mogoson.	mogoson@outlook.com