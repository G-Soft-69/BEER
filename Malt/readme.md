# Malt

Malt is a highly customizable rendering framework written in Python and OpenGL.

BlenderMalt is a Blender addon that integrates Malt into Blender, exposing a minimal user interface suitable for a code-centric workflow.

## Install

> 🔔 *Malt is still in beta state*
 
- Go to [the latest Release page](https://github.com/blendernpr/BEER/releases/tag/v1-beta).
- Download the *BlenderMalt* version that matches your OS.
  - *(Optional)* Download the *Shader Examples* too.
- Open Blender. Go to *Preferences > Addons*, click on the *Install...* button and select *BlenderMalt.zip* from your downloads.
- Tick the box in the *BlenderMalt* panel to enable it.

To test the renderer go to *Scene Settings* and *change the renderer to Malt*. Create a *Sunlight* and add a new object with a *new material*. Inside the material settings *set the Shader Path* to one of the files from the [*Shader Examples*](Shader-Examples).

> 🔔 By default, *Malt* uses very high quality rendering settings.  
If you find it runs too slow on your computer, go to *Properties Panel > Scene > Malt Settings* and lower the *Transparency Layers* (1 should be enough for the viewport) and the *ShadowMaps* resolution (1024 or 512 should be fine).

> ⚠️ There are known issues when using the engine with *Intel* graphics cards.  
A decicated *Nvidia* or *AMD* GPU is highly recommended.

If you could fill [this super short survery](https://forms.gle/e4dTicpsxerL4YdQ6) after testing, that would be really helpfull.

#### Uninstall

- Untick the box in *Preferences > Addons > BlenderMalt* to disable the addon.
- Restart *Blender*.
- Go back to *Preferences > Addons > BlenderMalt*, expand the panel and click the *Remove* button.

## Bug Reports

If you need help or find a bug you can [open a new issue](https://github.com/BlenderNPR/BEER/issues).

**For bug reports include**:
- A ***System Info* report** generated by Blender *(Help > Save System Info)*.
- A **full copy** of the ***System Console* contents** *(Window > Toggle System Console)*.
- A **.blend file** and a **list of steps** to reproduce the error.

## Developer Documentation
- [Malt](Malt)
- [Malt/GL](Malt/GL)
- [Malt/Render](Malt/Render)
- [Malt/Shaders](Malt/Shaders)
- [NPR Pipeline](Malt/Pipelines/NPR_Pipeline)
- [NPR Pipeline Shader Examples](Shader%20Examples)
- [BlenderMalt](BlenderMalt)

