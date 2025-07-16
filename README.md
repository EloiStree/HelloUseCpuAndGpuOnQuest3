
> Keep it simple stupide: **A Sphere where the tennis table ball is. (Without OpenCV or Vuforia)**

🎯Meta AI Hackathon 2025: https://xrbootcamp.typeform.com/xraihack2025

---------

# Use CPU and GPU for Quest3 

> You can't do image processing on Unity Main Thread due to [complexity](https://github.com/EloiStree/HelloSharpForUnity3D/issues/49)

Photo of the Quest3:
| | |
|-|-|
|<img width="1280" height="960" alt="LightNightLine" src="https://github.com/user-attachments/assets/959f7be3-46d9-4276-9c87-b888903cf86e" />|<img width="1280" height="960" alt="BigLightInKitchen" src="https://github.com/user-attachments/assets/b1736f24-79f1-4891-b45d-0db2ea28090f" />|

**Kinect**: 520x400 = 208000  
**Quest3**: 1280x960 = 883200   
**Phone Camera**: 1920x1080 = 2073600  
**Quest Screen**: 3840x2160 = 8294400  

### Exercice:  16 ms !

- Filtrer la couleur orange  d'un image
  - Avec vos connaissances actuelles
  - Avec un compute Shader
    - Utiliser le [GPU](https://youtu.be/Ge-g3xZ5bb8?t=18) 
  - Avec un Job System
    - Utiliser plusieurs [CPU](https://youtu.be/Ge-g3xZ5bb8?t=18)
  - Bonus: Avec ShaderGraph
 
#### Exercice: Convertion 

Main Keywords :
> Job System , Compute Shader, Shader Graph, Copy Buffer ,Texture2D, Color32 ,Texture2D ,RenderTexture, Native Array, Graphic Blit
[Texture2D](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/216) - [WebcamTexture](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/337)


- [ ] Basic GPU + Graphic.Blit
  - [ ] Texture2D <-> RenderTexture
  - [ ] WebCamTexture -> RenderTexture
  - [ ] RenderTexture -> Resized RendererTexture
  - [ ] RenderTexture -> Compute Shader -> RenderTexture
- [ ] CPU
  - [ ] RenderTexture -> NativeArray<Color32>
  - [ ] NativeArray<Color32> -> JobSystem -> NativeArray<Color32>
  - [ ] NativeArray<Color32> -> JobSystem -> NativeArray<T>
- [ ]  GPU + CPU  
  - [ ] Webcam -> Resized 128x93 UDP package
  - [ ] Webcam -> Three Resized RGB 256x196 UDP packages
  - [ ] Webcam -> Send N UDP packages -> Received N UDP package -> RenderTexture
- [ ] Save Texture
  - [ ] Texture -> JPEG and PNG
  - [ ] Texture -> TGA
  - [ ] RenderTexture -> .color32



# A lit bit of random words 😉

Let's check what GPT 🤖 have to say on the Buffer vs RenderTexture vs NativeArray<Color32> ? GPC VS CPU
- https://chatgpt.com/share/68672651-42d0-800e-b0e1-4348bc9174e1
- https://chatgpt.com/share/68672d9b-a72c-800e-9bac-3eefc7399b01



----------------

# POC of the past

- [ ] https://github.com/EloiStree/2022_06_06_IrregularQuadrilateralsToTexture2D  
- [ ] https://github.com/EloiStree/2022_06_12_TextureByteTransfertShader  
- [ ] https://youtu.be/aSQFWhV5ur8?t=1030

