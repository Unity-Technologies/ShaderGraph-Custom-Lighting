The Sub Graphs in this folder achieve some custom effects in Shader Graph for our toon shaded scene. 

- Grass Animation
    This Sub Graph calculates the vertex animation for our grass based on the simple vertex animation in our blog post from last year, which you can find here: 

- Triplanar Blend
    This Sub Graph calculates the blending between two planar-projected textures based on normal angle and vertex color. 

- Calculate Lighting Subsurface
    This Sub Graph approximates subsurface scattering for additional lights using a wrapped lambertian diffuse model and translucency using a technique described by Colin Barré-Brisebois and Marc Bouchard at GDC 2011.

- Calculate Main Light Subsurface 
    This Sub Graph approximates subsurface scattering for the main light using a wrapped lambertian diffuse model and translucency using a technique described by Colin Barré-Brisebois and Marc Bouchard at GDC 2011.