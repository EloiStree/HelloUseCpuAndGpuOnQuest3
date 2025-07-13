# Use CPU and GPU for Quest3 

> You can't do image processing on Unity Main Thread due to [complexity](https://github.com/EloiStree/HelloSharpForUnity3D/issues/49)

Objectif de la demarche:
- Explorer la triangulation par la couleur d un Quest3.

Challenge du projet:
- Tracker un balle de ping pong via la WebCam
- Tracker des Post It de couleur
- Recalibrer un jouer par rapport aux lumieres blanches d une piece.
- Utiliser le Depth API en partenaria avec la Camera.
- Screen Color Transfert: Inventer un transmittion de donner par la couleur d un ecran.


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
 
### Exercice: Convertir en un RendererTexture 

#### Un [Texture2D](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/216)


#### Un [WebcamTexture](https://github.com/EloiStree/HelloUnityKeywordForJunior/issues/337)




### Exercice: Convertir votre RenderTexture en NativeArray<Color32>



## Exercice: Transmettre votre image en UDP

Would it not be easier if we could see the image on your computer ?
UDP payload is of 65,527 so you need to send 14 packages and reconstruct them to do it.
Doable with Compute, Job and Memory Copy. Did in the past. But complexe and heavy.

Il nous faut donc Scale Down la texture.
Vous pouvez utiliser Blit qui fait tout pour vous.
RenderTexture rt = new RenderTexture(1280, 930, 0);
Graphics.Blit(sourceTexture, rt);

Ou faire la moyen de pixel avec un ComputeShader:
Something like this ( I have to do it later):
https://chatgpt.com/share/6873baef-b1b8-800e-aa01-3f9d8cc6953f


### Exercice: Convertir un image pour rentrer dans un package UDP.
- 128x93 = 11,904 * 3 colors = 35,712 bytes

### Exercice: Convertir un image pour rentrer dans 3 packages UDP RGB.
- 256x196 = 47,616 bytes

  

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

