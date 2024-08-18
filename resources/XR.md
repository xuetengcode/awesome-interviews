# XR specific tech interview

## AR / VR / MR / XR

- Explain what is AR / VR / XR / MR, how are they connected? Why would you choose one over another?
- Your client is saying "I want a HoloLens app that can do X".  How do you qualify if they're wasting their money?
- Tell me about some logistical implications of this tech in the enterprise?
- How does developing an XR app differ from a traditional 2D or 3D game / app?
- Specifically, what are some downsides to translucent displays (HoloLens, Magic Leap), and how do you accommodate for them?

## Rendering Tech

- Explain to me a typical rendering pipeline - how do games go from "there's a cube here" to "this is on the screen"
  - Looking for key concepts: Transforms, Matrices, World Space, Object Space, View Space, Camera, Mesh, Material, Shader, Lighting
- How does texturing work?
- What is culling? (Frustum and Face)
- Are you familiar with shader development? Talk me through how you would implement a force field effect in a shader
- Why is transparency a pain in the butt?

## 3D concepts

- What's the difference between a ray, a vector, a quaternion, a matrix
- What is a ray cast, and when would you do it?
- Why are Quaternions so damn useful?
- What does the data structure for a mesh look like? Why?
- What is a normal? Give some examples of how they are useful

## Performance

- The client wants to render a building with 200K triangles on a mobile / HoloLens.  What things do I need to consider?
  - 2M triangles?
  - 20M triangles?
- Talk to me about a time you've taken a "shortcut" for performance reasons (eg. Blinn-Phong vs Phong)
- What is overdraw, and what are some ways you can prevent it?

## VFX

- Go through the various aspects of lighting for PBR materials
  -  Specifically, Ambient, Diffuse, Specular, Metallic, roughness etc.
-   What specific considerations do you need to take for VFX in a VR or MR?
-   What's a particle system?

## Running the gig

- Explain to me how you capture a client's desire, turn that into reality, and then confirm with the client that it's good?
- You're working with an artist on an XR gig.  How do you share assets and work together (eg. 3d meshes, textures etc.)