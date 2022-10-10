# Classic Sponza - Unity Remaster

![Sponza-HDRP-4](https://user-images.githubusercontent.com/1553981/194602585-91518cf8-8ee5-486b-946b-991d5bb3148e.jpg)

## Summary

The Atrium Sponza Palace scene is widely used by graphics programmers and artists. It provides with an ideal lighting test environment, as it features both indoor and outdoor areas. 

The goal of this conversion was to modernize the project in key areas, making it compliant with modern rendering standards.

Please refer to the [Releases](https://github.com/Unity-Technologies/Classic-Sponza/releases) page for Unity editor and Render Pipeline compatibility.

### Features

- Full compatibility with Unity's High Definition, Universal, and Built-in Render Pipelines.
- All textures and materials are PBR-compliant.
- Physical lighting and exposure.
- Manually authored lightmap UVs.
- Baked global illumination using the Progressive Lightmapper.

## Setup

### Cloning the project

#### Important note
This project makes use of [Git Large Files Support (LFS)](https://git-lfs.github.com). You need to install LFS on your local machine first. **Do not download the project via the Download ZIP option.** Once you have installed LFS, please follow the steps outlined below.

#### Branch structure

This project contains multiple branches:
* [`main`](https://github.com/Unity-Technologies/Classic-Sponza/tree/main) branch contains the **High Definition Render Pipeline** version of the project.
* [`URP`](https://github.com/Unity-Technologies/Classic-Sponza/tree/URP) branch contains the **Universal Render Pipeline** version of the project.
* [`BiRP`](https://github.com/Unity-Technologies/Classic-Sponza/tree/BiRP) branch contains the **Built-in Render Pipeline** version of the project.

After pulling the project, checkout the branch which contains your desired render pipeline version of the project.

#### Using the GitHub Desktop client
Click on the green Code button at the top, and select *Open in Desktop* option.

#### Using alternative git clients
Paste the following web URL into your preferred git client: `https://github.com/Unity-Technologies/Classic-Sponza.git`.

#### Using command line or terminal
Open your preferred command line application and enter the following command: `git clone https://github.com/Unity-Technologies/Classic-Sponza.git`.

### Setting up the project in Unity
This project makes use of multi-scene workflow. In order to make sure that everything works as expected, please follow these steps:
1. In the **Project** tab, navigate to **Assets > ClassicSponza > Scenes**.
2. Open **Sponza** scene.
3. Once it finishes loading, right-click on the **SponzaLightingDay** scene and select the **Open Scene Additive** option.
4. In the **Hierarchy** panel, right-click on the SponzaLightingDay scene, and select the **Set Active Scene** option.

Note that the initial shader compilation stage might take some time. There is a chance that nothing might be visible in the viewport before its completion.

## Credits

- Sponza model authored by Frank Meinl at [Crytek](https://www.crytek.com/).
- Sponza model acquired from [McGuire Computer Graphics Archive](https://casual-effects.com/data/).
- HDRI acquired from [NoEmotion HDRs](http://noemotionhdrs.net/).
- Unity conversion carried out by [Kristijonas Jalnionis](https://github.com/radishface).
- Special thanks to [Kemal Akay](https://github.com/kemalakay) and [Laurent Harduin](https://github.com/laurenth-personal) for their assistance with the initial project setup.
