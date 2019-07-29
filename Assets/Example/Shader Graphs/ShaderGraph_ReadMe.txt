This folder contains the Shader Graph assets that are used in our example scene. 

- Grass 
    This shader uses the custom toon shading from the blog post and adds vertex animation from a Sub Graph. See the Sub Graph readme for more information about the animation. 

- Ground
    This shader blends multiple planar projected textures together using a Sub Graph. See the Sub Graph readme for more information about the blending. 
    Only the top of the diorama should render the grass texture, so we use vertex colors to dtermine the grassy area and triplanar blending to seamlessly blend between the grass and dirt. 

- Props
    This is the base shader used for the materials of the rocks, the fence, and the arrow sign post in the scene.

- SubSurface Scattering 
    This shader approximates subsurface scattering using a wrapped lambertian diffuse model and translucency using a technique described by Colin Barré-Brisebois and Marc Bouchard at GDC 2011.

- Water
    This shader uses voronoi noise to simulate small waves on the water surface. The water color and transparency is based on the depth of that water at a given point.
    Finally, we calculate the distance between the water surface and the closest object behind it to create an intersection value, then use this to mask a noise based foam effect.   