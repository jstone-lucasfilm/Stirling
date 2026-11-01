# Stirling
Stirling is an official Pixar asset derived from the Finn McMissile character in Pixar's *Cars 2* and designed to showcase MaterialX. The asset was authored using MaterialX 1.39 base building blocks and does not use monolithic materials such as Standard Surface and OpenPBR.  

<div align="center">
	<img src="renders/RenderMan/WideCam.png" width="100%" />
	<img src="renders/RenderMan/HeadLightCam.png" width="19%" />
	<img src="renders/RenderMan/TailLightCam.png" width="19%" />
	<img src="renders/RenderMan/InteriorCam.png" width="19%" />
	<img src="renders/RenderMan/TireCam_Front.png" width="19%" />
	<img src="renders/RenderMan/TireCam_Back.png" width="19%" />
</div>

<br><br>
Stirling comes in two openUSD variants, which share the same materials and represent the same colors:

Real Time: 
- Polys - High res mesh
- PNG raster textures
- sRGB texture encoding, Linear Rec.709 color space
- 2K max resolution, with 4K seats and tire inscriptions
- Games | Web | Mobile

Offline:
- SubD - Low res mesh
- TEX Mipmap textures (tiled OpenEXR)
- Linear Rec.709 color space
- 4K max resolution
- Production rendering

<br><br>
Stirling running in Houdini 22 and RenderMan 28:

<img width="2555" height="1536" alt="Houdini-22-RenderMan-XPU" src="renders/RenderMan/Solaris_RenderMan_XPU.png" />

## Trivia
Stirling also has some fun RenderMan historical trivia:

* A113 \- Tag (Number of the classroom at CalArts where many legendary Disney, Pixar, and indie animators studied)  
* Utah Teapot \- Rearview mirror prop (famous open source testing model from University of Utah)  
* Cornell Box \- Rearview mirror prop (inspired by the famous test scene and redone with primitive geometry)  
* MaterialX logo  
* OpenUSD Logo  
* 001988 \- Dashboard Mileage \- RenderMan RiSpec publishing year  
* RenderMan Tires \- Assorted RenderMan trivia on the tire sidewall  

## About the Authors
Stirling is an initiative by Pixar's Dylan Sisson and modeled by Andrew Schmidt. MaterialX Stirling was created by Pixar's Leif Pedersen and in collaboration with Pixar's Fran Gonzalez and Jonathan Stone from Lucasfilm.  
A special thanks to the technical direction and contributions of Arnon Marcus from OTOY.
