# Use CPU and GPU for Quest3 

> You can't do image processing on Unity Main Thread due to [complexity](https://github.com/EloiStree/HelloSharpForUnity3D/issues/49)

[<img width="740" height="415" alt="image" src="https://github.com/user-attachments/assets/3dcde71a-04cd-40fc-9670-f72e9d886c38" />](https://www.pcmag.com/news/what-is-8k-should-you-buy-a-new-tv-or-wait)

Photo of the Quest3:
| | |
|-|-|
|<img width="1280" height="960" alt="LightNightLine" src="https://github.com/user-attachments/assets/959f7be3-46d9-4276-9c87-b888903cf86e" />|<img width="1280" height="960" alt="BigLightInKitchen" src="https://github.com/user-attachments/assets/b1736f24-79f1-4891-b45d-0db2ea28090f" />|

**Kinect**: 520x400 = 208,000  
**Quest3**: 1280x960 = 883,200  
**Phone Camera**: 1920x1080 = 2,073,600  
**Quest Screen**: 3840x2160 = 8,294,400  

### Exercice: Comfronter vous a l impuissance de votre CPU face a 16 ms

You game must run on 16 milliseconds to be over 60 FPS.
Unity and the reste take 8 ms out. 
You have 8 ms for your full game. 
If you are out of 1-4 ms are going to feel it.

- Filtrer la couleur orange  d'un image
  - Avec vos connaissances actuelles
  - Avec un compute Shader
    - Utiliser le [GPU](https://youtu.be/Ge-g3xZ5bb8?t=18) 
  - Avec un Job System
    - Utiliser plusieurs [CPU](https://youtu.be/Ge-g3xZ5bb8?t=18) 
 
  
 




# Hello Cpu Gpu For Quest3 From Kinect

I learn to use GPU and CPU in Unity for the Kinect 1 and 2. Now that the Quest3 have a mini RGB Depth kinect. I need to make a workshop on the topic...

Main Keywords :
> Job System , Compute Shader, Shader Graph, Copy Buffer ,Texture2D, Color32 ,Texture2D ,RenderTexture, Native Array, Graphic Blit



Let's check what GPT 🤖 have to say on the Buffer vs RenderTexture vs NativeArray<Color32> ? GPC VS CPU
- https://chatgpt.com/share/68672651-42d0-800e-b0e1-4348bc9174e1
- https://chatgpt.com/share/68672d9b-a72c-800e-9bac-3eefc7399b01


# What I have done with Job System



----------------

Some cool Shader and Job to fetch:  
https://github.com/EloiStree/2022_06_06_IrregularQuadrilateralsToTexture2D  


Some cool code to turn Texture to Bytes:    
https://github.com/EloiStree/2022_06_12_TextureByteTransfertShader  

