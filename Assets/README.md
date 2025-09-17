[TOC]
# MGS.CubemapRenderer

## Summary
- Unity Cubemap renderer.

## Ability
- Render a scene into a static Cubemap asset for Skybox material or reflective material.

## Install

- Unity --> Window --> Package Manager --> "+" --> Add package from git URL...

  ```text
  https://github.com/mogoson/MGS.CubemapRenderer.git?path=/Assets
  ```

## Prerequisite
- Unity provide the ScriptableWizard class to quickly create extend editor window.
- Unity provide the API(RenderToCubemap method of the Camera class) to render Cubemap.

## Scheme
- Write extend editor code, select source camera and config the parameters for create Cubemap.
- Select path and input file name to save the render Cubemap.

## Usage
1. Find the menu item "Tool/Cubemap Renderer" in Unity editor menu bar and click it or press key combination Alt+C to open the editor window.
1. Create/Select a scene camera as the "Camera" field if no MainCamera in your scene.
1. Config the "Size", "Format" and "Mipmap" fields.
1. Click the "Render" button to open the dialog of save new render cubemap.
1. Select a path and input a file name to dialog and save.

---

Copyright © 2025 Mogoson.	mogoson@outlook.com
