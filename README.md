# Launch Blender Extensions

Centralised hub for the Launch suite of Blender toolkits.

![3D render of an abstract B-shaped logo made up of blocks with some rounded corners in soft purples and yellow-oranges, text in the image reads Blender Toolkits from the Mograph team at Launch by NTT DATA](images/BlenderToolkits.jpg)



***WARNING: These extensions are in early beta and should be installed only for testing purposes.***



## Installation via Extensions Platform:

- Go to Blender Preferences > Get Extensions > Repositories > **＋** > Add Remote Repository
- Set the URL to `https://jeinselen.github.io/Launch-Blender-Extensions/index.json`
- Set the local directory if desired (relative paths seem to fail, try absolute instead)
- Enable `Check for Updates on Start`
- Filter the available extensions for "Launch" and install as needed



## Installation via Download:

- Download the .zip file for a specific kit
- Drag-and-drop the file into Blender

This method will not connect to the centralised repository here on GitHub and updates will not be automatically available. If you don't need easy updates, don't want GitHub servers to be pinged when you start up Blender, or would just like to try some extensions without adding yet another repository to your Blender settings, this is the option for you.



## Available Toolkits:

### Launch Production Kit — General Utilities

![3D render of an abstract P-shaped logo made up of blocks with some rounded corners in soft blues, text in the image reads Production Kit from the Mograph team at Launch by NTT DATA](images/ProductionKit.jpg)

Extension documentation and bug reports — https://github.com/jeinselen/Blender-ProductionKit

- Sidebar colour palette
- Project version archiving
- Global image updating
- Viewport shading shortcuts
- Driver functions



### Launch Mesh Kit — Geometry Editing

![3D render of an abstract M-shaped logo made up of blocks with some rounded corners in soft purple, text in the image reads Mesh Kit from the Mograph team at Launch by NTT DATA](images/MeshKit.jpg)

Extension documentation and bug reports — https://github.com/jeinselen/Blender-MeshKit

- Copy and paste geometry data
- Planar UV projection
- Generate point arrays
- Radial offset
- Mesh segmentation
- Quantise vertices



### Launch Render Kit — Rendering Management

![3D render of an abstract R-shaped logo made up of blocks with some rounded corners in soft reds and oranges, text in the image reads Render Kit from the Mograph team at Launch by NTT DATA](images/RenderKit.jpg)

Extension documentation and bug reports — https://github.com/jeinselen/Blender-RenderKit

- Output variables
- Autosave videos via FFmpeg
- Autosave images
- Render time estimation and logging
- Proxy rendering
- Batch rendering
- Numerical render region inputs



### Launch Delivery Kit — Quick Exports

![3D render of an abstract D-shaped logo made up of blocks with some rounded corners in soft yellow-oranges and purple, text in the image reads Delivery Kit from the Mograph team at Launch by NTT DATA](images/DeliveryKit.jpg)

Extension documentation and bug reports — https://github.com/jeinselen/Blender-DeliveryKit

- Unity 3D (FBX)
- Unreal Engine (FBX)
- ThreeJS (GLB)
- Element3D (OBJ)
- Xcode (USDZ)
- 3D Printing (STL)
- Unity 3D Volume Field (VF)
- 3D Texture Strip (EXR)
- Item Position (CSV)
- Item Vertices (CSV)



These extensions are a direct continuation of the original VF Tools add-ons by Vectorform for Blender 2.8 through 4.1, and maintain the original GPL licensing.

Software is provided as-is with no warranty or provision of suitability. These are internal tools and are shared because we want to support an open community. Bug reports are welcomed (please use the specific extension repository, not this centralised hub), but we cannot commit to fixing or adding features.
