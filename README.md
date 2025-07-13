# Use CPU and GPU for Quest3 

> You can't do image processing on Unity Main Thread due to [complexity](https://github.com/EloiStree/HelloSharpForUnity3D/issues/49)

Good News: 
- We have access to the camera of the Quest3
Bad News:
- Image processing need multithreading
  - Solution: Use GPU and CPU Core 
- Sometime compute power outside of a Quest cabability
  - Solution: Compute on local LAN computer or server
- API Creator stop focusing Unity for Godot And Unreal
  - Solution: Use Python OpenCV and other API
  - Solution: Create them ourself
 




# Hello Cpu Gpu For Quest3 From Kinect

I learn to use GPU and CPU in Unity for the Kinect 1 and 2. Now that the Quest3 have a mini RGB Depth kinect. I need to make a workshop on the topic...

Main topic:
- Job System
- Compute Shader
- Shader Graph
- Copy Buffer
- Texture2D
- Color32
- Texture2D
- RenderTexture



Workshop : [Mons 17-18 juillet 2025](https://github.com/EloiStree/HelloCpuGpuForQuest3FromKinect/tree/main/MonsJuly2025)




Buffer vs RenderTexture vs NativeArray<Color32> ? GPC VS CPU
- https://chatgpt.com/share/68672651-42d0-800e-b0e1-4348bc9174e1
- https://chatgpt.com/share/68672d9b-a72c-800e-9bac-3eefc7399b01

Todo:
- List all the project with compute shader amd job system I have done to remember how I did.



----------------

Some cool Shader and Job to fetch:  
https://github.com/EloiStree/2022_06_06_IrregularQuadrilateralsToTexture2D  


Some cool code to turn Texture to Bytes:    
https://github.com/EloiStree/2022_06_12_TextureByteTransfertShader  

