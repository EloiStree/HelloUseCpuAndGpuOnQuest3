
Salut à tous, pas de pression 😁, on va faire simple mais techy.

* **Day 1** : Petit drone volant en XR
* **Day 2** : Pratique des shaders selon votre niveau sur la caméra du Quest 3.

# Jeudi

**Intention** : Vous apprendre à configurer un projet XR.

**Matin :**

* Créer un projet Unity URP
* Ajouter OpenXR
* Ajouter le SDK Meta
* Ajouter un objet 3D
* Ajouter un script XRTK
* Dernière vérification
* Build sur le Quest 3

**Après-midi :**

- [ ] Ajouter un drone Tello

  - [ ] [Kid Toy packages](https://github.com/EloiStree?tab=repositories&q=_KidToy&type=&language=&sort=)

    - [ ] [Small double side car](https://github.com/EloiStree/2023_11_01_KidToyCarSkidSteeringCode)
    - [ ] [Tello Drone](https://github.com/EloiStree/2023_02_19_KidToyDroneTelloModeCode)
- [ ] Ajouter une Input Action
- [ ] Relier les deux via le clavier
- [ ] Ajouter le système d’input OpenXR
- [ ] Build and hope
- [ ] Installer Link sur le PC
- [ ] Vérifier si les PC supportent Link
- [ ] Créer un circuit
- [ ] Ajouter un XRTK Grip sur les objets du circuit
- [ ] Jouer à [XRTK](www.youtube.com/watch?v=eDicfcAgJB4&pp=0gcJCb4JAYcqIYzv)

  - [ ] [https://github.com/EloiStree/2024\_07\_16\_MonsXrDesign/releases/tag/V0](https://github.com/EloiStree/2024_07_16_MonsXrDesign/releases/tag/V0)

---

# Vendredi

**Intention** : Vous apprendre à utiliser le Compute Shader pour la XR.

Reproduire cette application perdue dans le temps :
[Reality Hacker VR](https://reality-hacker-vr.en.softonic.com/android)

[<img width="1901" height="995" alt="image" src="https://github.com/user-attachments/assets/d379e7ed-027f-48e4-9bb5-0e97162601aa" />](https://youtu.be/JnZOoryLwAI)
[https://youtu.be/JnZOoryLwAI](https://youtu.be/JnZOoryLwAI)

**Matin :**

- [ ] Créer un diaporama d'images dans un RenderTexture de 1280x930
- [ ] Créer un Canvas avec des RawImage dans lequel appliquer le RenderTexture
- [ ] Créer, pour le fun, un premier Shader Graph qui inverse deux couleurs
- [ ] Créer, pour le fun, un Compute Shader qui inverse deux couleurs
- [ ] Créer un shader qui garde les couleurs entre deux bornes
- [ ] Cloner et configurer le projet de passthrough de Meta
  - [ ] [https://github.com/meta-quest/Meta-Passthrough-Camera-API-Samples](https://github.com/meta-quest/Meta-Passthrough-Camera-API-Samples)
- [ ] Le builder et l’essayer
- [ ] Extraire la `WebCamTexture` de la caméra
- [ ] Prendre des photos au format TGA depuis la caméra
- [ ] Récupérer les photos avec SideQuest
- [ ] *Pause*
- [ ] Transformer une `Texture2D` en `RenderTexture`
  - [ ] [Jouons avec le temps](https://github.com/EloiStree/OpenUPM_WatchExecuteTime)
- [ ] Inverser deux couleurs avec un Compute Shader
- [ ] Pour le fun : séparer les canaux rouge, vert et bleu
- [ ] Appliquer les nouvelles textures sur des cubes

**Après-midi :**

- [ ] Introduction au hackathon :
  - [ ] [https://xrbootcamp.typeform.com/xraihack2025](https://xrbootcamp.typeform.com/xraihack2025)
- [ ] Isoler la couleur de votre post-it / balle de tennis de table
  - [ ] Observer le temps d’exécution
- [ ] Choisir un challenge :
  - [ ] Trouver les quatre coins d’un post-it en moins de 1 ms
  - [ ] Trouver le centre de spheres en moins de 1 ms
  - [ ] Explorer [Open CV Free](https://assetstore.unity.com/search#q=OpenCV) sur le Quest 3
  - [ ] Choisir un [ShaderToy](https://www.shadertoy.com/results?query=&sort=hot&filter=webcam) selon votre niveau et le convertir pour Unity3D
  - [ ] Utiliser Flask pour faire communiquer du code Python sur PC avec
  - [ ] Ghibliser la Webcam du Quest (si vous etes familiariser avec les API de AI en ligne)

---

**Packages utiles :**

- [ ] [Play With Camera API](https://github.com/EloiStree/2025_06_13_PlayWithCameraAPI.git)
- [ ] [Watch Execute Time](https://github.com/EloiStree/2024_04_18_WatchExecuteTime.git)
- [ ] [Texture2D Toolbox](https://github.com/EloiStree/2025_06_13_ToolboxTexture2D)

Utiliser cette image pour les exercices de filtre de couleur : <img width="2048" height="2048" alt="ColorSpectrumWithPingPong" src="https://github.com/user-attachments/assets/b3e3a353-d526-413e-afd5-058113c6da3d" />



------------------

# Foutoir

--------

Link:
Les yeux du Daltonisme: https://lesyeuxdudaltonisme.fr/les-types-de-daltonisme/

Creer un Gardiant de couleur sans Texture2D dans Unity
https://chatgpt.com/share/68760590-a938-800e-b5ba-a99259b6d154


[<img width="600" height="670" alt="image" src="https://github.com/user-attachments/assets/2ab051bc-40d9-457d-8469-5502cbcee609" />
](https://scipython.com/blog/converting-a-spectrum-to-a-colour/)  
https://scipython.com/blog/converting-a-spectrum-to-a-colour/  
Maybe:https://chatgpt.com/share/687609af-98ec-800e-8f90-78556223c6e3


https://gitlab.com/eloistree/2018_06_01_MeshToVoxel  



Frida Wall
[<img width="1260" height="558" alt="image" src="https://github.com/user-attachments/assets/01360622-d91a-421d-bb40-b6ec3a23db2c" />
](https://youtu.be/pVxhmuf2IeA?t=141)  
https://youtu.be/pVxhmuf2IeA?t=141  
https://youtu.be/rso9u7mkP68?t=9  

[<img width="1258" height="558" alt="image" src="https://github.com/user-attachments/assets/473796fd-8d9a-4040-8628-4852884a6c2c" />
<img width="1156" height="623" alt="image" src="https://github.com/user-attachments/assets/99df6a1e-7482-4955-92a3-69700520fcde" />
](https://youtu.be/gT3I8qI2y4E?t=998)  
https://youtu.be/gT3I8qI2y4E?t=998



Replicator
[<img width="1225" height="586" alt="image" src="https://github.com/user-attachments/assets/ec412c3d-c2f8-4c5f-8171-ce402613e3c5" />
](https://youtu.be/BPbTssjNvzs?t=16)
https://youtu.be/BPbTssjNvzs?t=16


Il n y a que trois meshs ici:
[<img width="1374" height="610" alt="image" src="https://github.com/user-attachments/assets/9c37f244-bd94-4004-952e-6bcd62c9ee27" />](https://youtu.be/f21l7T1aFu0?t=14)



[<img width="598" height="647" alt="image" src="https://github.com/user-attachments/assets/d64c9a6b-f153-44b0-9ea1-8b0a3737dfb8" />](https://people.eecs.berkeley.edu/~sequin/CS184/TOPICS/ColorSpaces/Color_0.html)

[<img width="966" height="425" alt="image" src="https://github.com/user-attachments/assets/35ac5bf0-bfec-45b5-b1e5-372a9d40b6e4" />](https://people.eecs.berkeley.edu/~sequin/CS184/TOPICS/ColorSpaces/Color_0.html)  
https://people.eecs.berkeley.edu/~sequin/CS184/TOPICS/ColorSpaces/Color_0.html



Snake https://youtu.be/VphtcDhHj40?t=13
Cow ; No Read https://youtu.be/VphtcDhHj40?t=30
Bird + ulta violet = https://youtu.be/VphtcDhHj40?t=110

Fish = less red https://youtu.be/VphtcDhHj40?t=84
Shark = Grayscale https://youtu.be/VphtcDhHj40?t=94


Bee : red is a dark blue
https://youtu.be/VphtcDhHj40?t=159

Cat: Not red or green but have some borwn yellow  https://youtu.be/VphtcDhHj40?t=177
Better grain intensity

Dog: Cant see red or orange but can see blue and violet with good gray
https://youtu.be/VphtcDhHj40?t=201

Frog only see what is moving
https://youtu.be/VphtcDhHj40?t=220



Capture image of Window
https://github.com/EloiStree/2023_07_23_Fork_uWindowCapture




View in Infrared Light 
[<img width="1286" height="707" alt="image" src="https://github.com/user-attachments/assets/51c76aae-3528-4a80-aa1f-fdbbebc6218a" />](https://youtu.be/PTgBxZ3PMF4?t=70)  
https://youtu.be/PTgBxZ3PMF4?t=70




Note: Eye tracking app
<img width="1368" height="736" alt="image" src="https://github.com/user-attachments/assets/29dc7013-4584-4811-9436-0aa38025f3b4" />
https://youtu.be/alz0f_hmgJk?t=433




-----------------------

Ambiance: 
- Is player is in the full dark ?
- Is player is in a one light environment ?
- Is player is in a room at night
- Is player is in room with not a lots of light ?
- Is player is in a room with light from window ?
- Is player is in a room wiht lots of light ?
- Is player in a room with sun bath of light ?
- Is player is outside ?
- Is player outside with a cloudy day ?
- Is player outside with full light
- Is a sky present in the player view ? 
- Is green present in player view ?
- ... ?

Human:
- 

Reality Hacker:
- [ ] [InvPermute BGR](https://youtu.be/JnZOoryLwAI?t=1)
- [ ] InvPermute BRG https://youtu.be/JnZOoryLwAI?t=10
- [ ] InvPermute GBR https://youtu.be/JnZOoryLwAI?t=13
- [ ] InvPermute GRB https://youtu.be/JnZOoryLwAI?t=18
- [ ] InvPermute RBG https://youtu.be/JnZOoryLwAI?t=23
- [ ] Permute BGR https://youtu.be/JnZOoryLwAI?t=27
- [ ] Permute BRG https://youtu.be/JnZOoryLwAI?t=31
- [ ] Permute GBR https://youtu.be/JnZOoryLwAI?t=37
- [ ] Permute GRB https://youtu.be/JnZOoryLwAI?t=41
- [ ] Permute RBG https://youtu.be/JnZOoryLwAI?t=45
- [ ] Magenta Flash https://youtu.be/JnZOoryLwAI?t=49
- [ ] Yellow Flash https://youtu.be/JnZOoryLwAI?t=54
- [ ] Cyan Flash https://youtu.be/JnZOoryLwAI?t=59
- [ ] Blue Flash https://youtu.be/JnZOoryLwAI?t=63
- [ ] Green Flash https://youtu.be/JnZOoryLwAI?t=68
- [ ] Red Flash https://youtu.be/JnZOoryLwAI?t=72
- [ ] See
  - [ ] Yellow https://youtu.be/JnZOoryLwAI?t=75
  - [ ] Magenta https://youtu.be/JnZOoryLwAI?t=78
  - [ ] Cyan https://youtu.be/JnZOoryLwAI?t=82
  - [ ] Blue https://youtu.be/JnZOoryLwAI?t=86
  - [ ] Green https://youtu.be/JnZOoryLwAI?t=90
  - [ ] Red https://youtu.be/JnZOoryLwAI?t=94
- [ ] Tritanopia Corrected https://youtu.be/JnZOoryLwAI?t=99
- [ ] Tritanopia Simulator https://youtu.be/JnZOoryLwAI?t=105
- [ ] Deuteranopia Corrected https://youtu.be/JnZOoryLwAI?t=109
- [ ] Deuteranopia Simulator https://youtu.be/JnZOoryLwAI?t=113
- [ ] Protanopia Corrected https://youtu.be/JnZOoryLwAI?t=119
- [ ] Protanopia Simulator https://youtu.be/JnZOoryLwAI?t=123
- [ ] Sobel Posterize https://youtu.be/JnZOoryLwAI?t=127
- [ ] Posterize https://youtu.be/JnZOoryLwAI?t=131
- [ ] Sobel Cartoon https://youtu.be/JnZOoryLwAI?t=135
- [ ] Inverted Sobel Edge https://youtu.be/JnZOoryLwAI?t=138
- [ ] Sobel Edge https://youtu.be/JnZOoryLwAI?t=145
- [ ] Inverted https://youtu.be/JnZOoryLwAI?t=149
- [ ] Grayscale https://youtu.be/JnZOoryLwAI?t=155

Disease that affect vision:
- Diabetic Retinapathy https://youtu.be/WHwGegMfiHU?t=128
- Cataract https://www.youtube.com/results?search_query=cataract+simulation
  - Nuclear Cataract https://youtu.be/alz0f_hmgJk?t=290
  - Cortical Cataract https://youtu.be/alz0f_hmgJk?t=349
  - Posterior Subcapsular Cataract https://youtu.be/alz0f_hmgJk?t=360
- Glaucoma https://youtu.be/cVFzDrmAY78?t=14 https://youtu.be/c8tjFByZ-ss?t=20
- Macular Degeneration https://youtu.be/JmQ4oLQXGDQ?t=19


Oculus DK12 Chromatic aberration: 
- https://youtu.be/oE8Zjr5NJrM?t=42
- Unity example https://youtu.be/tDxIeWGBmDc?t=5
  

Sober Edge 
[<img width="673" height="666" alt="image" src="https://github.com/user-attachments/assets/fb5c2504-14f0-4373-b4ba-e1b2993ab894" />](https://youtu.be/uihBwtPIBxM?t=361)  
- https://youtu.be/uihBwtPIBxM?t=361
- Sobel Operator
  - https://www.youtube.com/watch?v=Yz7h9L4gecQ&pp=ygUac29iZWwgZWRnZSBkZXRlY3Rpb24gdW5pdHk%3D 
  - https://youtu.be/ov1nRhlIDLM?t=1
  - Tuto in Unity game https://youtu.be/AtYhrsyxHB0?t=154
  - On Bike https://youtu.be/VL8PuOPjVjY?t=13
    - Good example of how to do it https://youtu.be/VL8PuOPjVjY?t=230
  - Shader toy code of it
    - Example https://www.shadertoy.com/view/MlBSWW
    - Other https://www.shadertoy.com/view/wd3Sz4
    - Other example https://www.shadertoy.com/results?query=sobel&sort=popular&filter=webcam
1 Bit Graphisc ?
[<img width="439" height="243" alt="image" src="https://github.com/user-attachments/assets/cc2af820-d84b-4468-9589-9ac13ccc17a5" />](https://www.youtube.com/watch?v=Ap4fXGTOb7I&pp=ygUac29iZWwgZWRnZSBkZXRlY3Rpb24gdW5pdHk%3D
)  
https://www.youtube.com/watch?v=Ap4fXGTOb7I&pp=ygUac29iZWwgZWRnZSBkZXRlY3Rpb24gdW5pdHk%3D  




Animal:
- What see
  - a cow or a deer
  - Fish
  - A shark
  - Bee
  - Cat
  - Dog
  - Hard Challeng;
    - Frog
    - Ultra Violet: Snake Bird



[<img width="755" height="376" alt="image" src="https://github.com/user-attachments/assets/4d5077ca-3a8f-433b-b8be-109e053cb747" />](https://youtu.be/0k1kqoNi4UM?t=275)  
https://youtu.be/0k1kqoNi4UM?t=275

Job System Pixel
[<img width="764" height="464" alt="image" src="https://github.com/user-attachments/assets/b9220fbe-a42c-4f1c-a573-6963e1ba10eb" />](https://youtu.be/ZS4wBvms3CI?t=2)  
https://youtu.be/ZS4wBvms3CI?t=2  


16k Drones 
[<img width="754" height="373" alt="image" src="https://github.com/user-attachments/assets/0c2fc8b4-31de-4b90-abec-844df4e0a302" />](https://youtu.be/bQcMWHdNHaQ?t=3)

https://youtu.be/bQcMWHdNHaQ?t=3


Rainbow ?
https://youtu.be/Zn80AN4k-0E?t=8

<img width="756" height="423" alt="image" src="https://github.com/user-attachments/assets/8529ba75-c45f-4c30-aa14-f1b3c74793bb" />



Play outside:

[<img width="752" height="375" alt="image" src="https://github.com/user-attachments/assets/d404b169-0eba-4a0d-97b7-d230050459f0" />](https://youtu.be/jzVMX8gSnaI?t=90)  
https://youtu.be/jzVMX8gSnaI?t=90   

[<img width="760" height="420" alt="image" src="https://github.com/user-attachments/assets/a4b9423c-d052-4c23-a8f2-9f05bb8e6a0c" />](https://youtu.be/zGPvU7xLhIQ?t=575)  
https://youtu.be/zGPvU7xLhIQ?t=575  

Postmortem:Can we see outside Quest 1 2 ?
- https://youtu.be/6giMjr7EcXE?t=36


Can we play in the dark ?
[<img width="759" height="372" alt="image" src="https://github.com/user-attachments/assets/d6ef861c-eaed-4e8e-b9d5-79e95df9dcbe" />](https://youtu.be/b91o9Sp-jlU?t=562)  
https://youtu.be/b91o9Sp-jlU?t=562  



Note Shader Toy
[<img width="626" height="349" alt="image" src="https://github.com/user-attachments/assets/24b4e7aa-b234-40ee-99a5-c12699c82977" />](https://www.shadertoy.com/view/33cGDj)  
https://www.shadertoy.com/view/33cGDj  

[<img width="629" height="341" alt="image" src="https://github.com/user-attachments/assets/5cb82be9-4fc1-4118-b612-0e2e8b74c0e1" />](https://www.shadertoy.com/view/XlSSzV)
https://www.shadertoy.com/view/XlSSzV

[<img width="330" height="276" alt="image" src="https://github.com/user-attachments/assets/b57dbc75-268d-490c-80a2-010b59c376ad" />](https://www.shadertoy.com/view/33tGDN)  
https://www.shadertoy.com/view/33tGDN  


Note: Crop the border of the image
<img width="580" height="428" alt="image" src="https://github.com/user-attachments/assets/609472ad-b153-4dd0-8df6-1b8b50129f25" />
You can use shader graph to cut the border of the camera.
Making less squary.


---------------------

# Open CV 

Youtube: https://www.youtube.com/results?search_query=open+cv

## In Asset store

[<img width="1193" height="729" alt="image" src="https://github.com/user-attachments/assets/3859d2d9-d217-4faf-8181-9b467f3b5783" />](https://assetstore.unity.com/search#q=open%20cv)  
https://assetstore.unity.com/search#q=open%20cv  

https://assetstore.unity.com/packages/tools/integration/opencv-for-unity-21088
- Body Detection https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/e2fecce0-c9fc-4b41-a556-7ad4a4a37273.webp
- Face detection https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/645e1296-a64d-4260-a8d1-b0ef3a82258b.webp
- Hand Detection  https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/90da4e3f-fba7-4b05-9beb-10854c61df2f.webp
- AI Yolo Detection https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/534e802d-301e-4f33-9976-e8e0d74b2f8d.webp
- Tag Image detectio https://youtu.be/oUVq20Xb4sM?t=2
- Face shape detection https://youtu.be/u5aDbn5nRbY?t=33
- Bare code detection https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/0b36d674-31a7-40c3-a4d0-55e4a3b05a59.webp
- Background remove https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/0c68d908-82a0-44ef-8e7c-cdc41e7cd0c9.webp
- Text Tesseract detection https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/c1d3bf70-15be-4750-94c6-b192a26a06be.webp
- Document Scanner https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/f41c4ed7-f02f-4ce5-a904-23229f590af2.webp
- AR Code Detector https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/916a6fb9-391a-44f7-aa28-71b5e6817382.webp
- MaskRCNN context detection object https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/86e52316-1824-4c3e-baf8-7e504d5a0664.webp

[<img width="612" height="315" alt="image" src="https://github.com/user-attachments/assets/c1a5414b-61f1-4765-a0a6-660a0b7990fa" />](https://youtu.be/oUVq20Xb4sM?t=45)  
https://youtu.be/oUVq20Xb4sM?t=45  

### Free version
- https://assetstore.unity.com/packages/tools/integration/opencv-plus-unity-85928
  - Detect tag  https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/b1aa054b-ffa2-4dfa-9be7-f4150939eac3.webp
  - Scan document https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/73075c3a-1b74-40ae-88f1-e31aac12893c.webp
  - Scan Letter https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/2faceace-6bdd-4a84-af8f-bd487ba0ddd3.webp
  - Scan Face https://assetstorev1-prd-cdn.unity3d.com/package-screenshot/69c2f15d-0978-4f56-aaf6-6a11b30adeed.webp


- Image tracker https://assetstore.unity.com/packages/tools/camera/imagine-webar-image-tracker-free-246878
- 
## In Python 

Perspective Transformation, important
https://youtu.be/PeMM80WimN4?t=71

Affine Transformation
https://youtu.be/PeMM80WimN4?t=70

Erosion 
https://youtu.be/PeMM80WimN4?t=82

Dilation
https://youtu.be/PeMM80WimN4?t=83

Opening 
https://youtu.be/PeMM80WimN4?t=84
Closing
https://youtu.be/PeMM80WimN4?t=84

Morphological Gradiant
Different of opening and closing
https://youtu.be/PeMM80WimN4?t=85

Laplacian
https://youtu.be/PeMM80WimN4?t=91

Canny Edge
https://youtu.be/PeMM80WimN4?t=93

Blending
https://youtu.be/PeMM80WimN4?t=97

Find Border and corner
https://youtu.be/PeMM80WimN4?t=102

Plotting Histograms
https://youtu.be/PeMM80WimN4?t=104
RGB PLotting
https://youtu.be/PeMM80WimN4?t=107

Fourier Transform Numpy
https://youtu.be/PeMM80WimN4?t=110

Tamplate Matching
https://youtu.be/PeMM80WimN4?t=116

Brute Force Matcher 
https://youtu.be/PeMM80WimN4?t=172

Hough Line 
https://youtu.be/PeMM80WimN4?t=119

Hough Cicle
https://youtu.be/PeMM80WimN4?t=125

Background Remover
https://youtu.be/PeMM80WimN4?t=134

Harris Corner Detection, Important
https://youtu.be/PeMM80WimN4?t=143

Surf Points
https://youtu.be/PeMM80WimN4?t=161

Noice Remover, important:
https://youtu.be/PeMM80WimN4?t=282

HDR 
https://youtu.be/PeMM80WimN4?t=296

# Yolo

https://www.youtube.com/results?search_query=yolo+ai+showcase

[<img width="1136" height="279" alt="image" src="https://github.com/user-attachments/assets/a2587249-4539-40a6-b922-a6aa84991378" />](https://www.youtube.com/watch?v=bZIKVaD3dRk&pp=ygUTb3BlbiBjdiBhc3NldCBzdG9yZQ%3D%3D)  
https://www.youtube.com/watch?v=bZIKVaD3dRk&pp=ygUTb3BlbiBjdiBhc3NldCBzdG9yZQ%3D%3D  


# AR fundation
- No tried

# Vuforia 
- Not yet availaible



# Playstation Note

<img width="1500" height="1110" alt="image" src="https://github.com/user-attachments/assets/96deab61-a063-406a-8af4-1ff1731d5d28" />
Find a ping pong ball with a led in it is the definition of PS Move xD

# Python on server

All those computation are heavy on the GPU and CPU.
You are better in some case to compute on a server and use the result.



# FUCKING GOOD EXAMPLE OF A COOL STUFF TO DO IN QUEST 3

That but with CameraAPI and DEPTH API using COmpute and Job system to process
[<img width="1330" height="705" alt="image" src="https://github.com/user-attachments/assets/fa36f2a1-2b34-4933-9c5f-4360ef0d3cde" />](https://youtu.be/v7XTJbSbcHY?t=4)  
https://youtu.be/v7XTJbSbcHY?t=4  
His code;https://github.com/sugi-cho/FlowingParticles



# What I want to be able to make with color Filtering

[<img width="1388" height="579" alt="image" src="https://github.com/user-attachments/assets/8aa93e5f-056e-4074-b457-97799cb0899f" />](https://youtu.be/VywzZZwTwto?t=3)  
https://youtu.be/VywzZZwTwto?t=3  



# Easy exercice: Convert this to Unity3D 

<img width="1311" height="481" alt="image" src="https://github.com/user-attachments/assets/47644af1-66e2-4d12-be7d-f0ad5c99b759" />



# Cool Shader Toy for web camera

https://www.shadertoy.com/results?query=&sort=hot&filter=webcam

[<img width="1313" height="331" alt="image" src="https://github.com/user-attachments/assets/ae59a34b-8217-4e52-b070-27cd2372c816" />](https://www.shadertoy.com/view/WXG3zy)
https://www.shadertoy.com/view/WXG3zy


[<img width="1507" height="438" alt="image" src="https://github.com/user-attachments/assets/9159b462-9d8f-4938-9a07-71b0a16bbcf8" />](https://www.shadertoy.com/view/lf33WS) https://www.shadertoy.com/view/lf33WS


Detection Movement ;)
[<img width="614" height="342" alt="image" src="https://github.com/user-attachments/assets/86eb58a4-5d54-406d-8293-2ca05a0085ca" />](https://www.shadertoy.com/view/lXj3Wc)  
https://www.shadertoy.com/view/lXj3Wc  
https://www.shadertoy.com/view/tcyGDK

Glitch
[<img width="1221" height="479" alt="image" src="https://github.com/user-attachments/assets/46602606-8571-4256-bad2-2f7a03fe94d9" />](https://www.shadertoy.com/view/ttdXD8)  
https://www.shadertoy.com/view/ttdXD8  

Fake Thermal
[<img width="1360" height="436" alt="image" src="https://github.com/user-attachments/assets/68ad9dbb-49ab-4e81-8148-34a803ba38c0" />
](https://www.shadertoy.com/view/lXBczw)  
https://www.shadertoy.com/view/lXBczw  


Dispersion
[<img width="1121" height="436" alt="image" src="https://github.com/user-attachments/assets/e79b3b52-edb3-451c-a7e7-0aebf2a9e315" />](https://www.shadertoy.com/view/W3BSzR)
https://www.shadertoy.com/view/W3BSzR


Sober Pixel
[<img width="979" height="464" alt="image" src="https://github.com/user-attachments/assets/c1116bac-2347-4c5f-be73-eb80f11edb17" />](https://www.shadertoy.com/view/4sfSR7)
https://www.shadertoy.com/view/4sfSR7


Magic Pencil
[<img width="1507" height="635" alt="image" src="https://github.com/user-attachments/assets/4b62a2c5-c6de-40bd-bb4e-674e34d1a638" />](https://www.shadertoy.com/view/Xd3SWX)
https://www.shadertoy.com/view/Xd3SWX


[Quad Tree on image
<img width="949" height="473" alt="image" src="https://github.com/user-attachments/assets/5e34eee8-2c7f-4b69-b4b3-b0d6fd8d2fc6" />](https://www.shadertoy.com/view/XcS3DW)  
https://www.shadertoy.com/view/XcS3DW   


[<img width="1186" height="432" alt="image" src="https://github.com/user-attachments/assets/a44d9a84-d279-40f9-b971-2dc6e680978d" />](https://www.shadertoy.com/view/333GRr)  
https://www.shadertoy.com/view/333GRr  


Shader and Music
[<img width="1227" height="966" alt="image" src="https://github.com/user-attachments/assets/08fca73b-b29c-454c-a4ca-fa16bbc3db5d" />](https://www.shadertoy.com/view/llVcRG)  
https://www.shadertoy.com/view/llVcRG 

VHS Filter
[<img width="1158" height="454" alt="image" src="https://github.com/user-attachments/assets/d7c8d31e-16e1-4b33-a453-c6e89ed754f6" />](https://www.shadertoy.com/view/DdKBRm)  
https://www.shadertoy.com/view/DdKBRm  

Nice to play around with mouse
[<img width="1245" height="569" alt="image" src="https://github.com/user-attachments/assets/d87cfd9e-1627-4d1c-8f89-0c98e2619291" />](https://www.shadertoy.com/view/33d3zB)
https://www.shadertoy.com/view/33d3zB

[<img width="981" height="472" alt="image" src="https://github.com/user-attachments/assets/a89ade8f-f382-4099-a5cc-a7a04017197b" />](https://www.shadertoy.com/view/3fcXRf)  
https://www.shadertoy.com/view/3fcXRf  


[Fluid with time
<img width="1262" height="479" alt="image" src="https://github.com/user-attachments/assets/c8cd8f9e-4d13-42bc-9a91-99960f8e6a81" />](https://www.shadertoy.com/view/tcsXzr)
https://www.shadertoy.com/view/tcsXzr


[<img width="1400" height="467" alt="image" src="https://github.com/user-attachments/assets/8e001213-f91f-4508-9146-1ab7604fc041" />](https://www.shadertoy.com/view/cll3zf)  
https://www.shadertoy.com/view/cll3zf  

[<img width="1102" height="467" alt="image" src="https://github.com/user-attachments/assets/7dbe8b0f-b849-4bdc-8e07-5fdb06306477" />](https://www.shadertoy.com/view/wX33zl)
https://www.shadertoy.com/view/wX33zl

[<img width="1115" height="441" alt="image" src="https://github.com/user-attachments/assets/056e8d42-2296-4265-b3d9-38e2f7f1a66c" />](https://www.shadertoy.com/view/tcGSD1)
https://www.shadertoy.com/view/tcGSD1

Nice Dot Shader
[<img width="1210" height="460" alt="image" src="https://github.com/user-attachments/assets/03ab01f4-a791-49c1-af57-fda9a9022447" />](https://www.shadertoy.com/view/WXVGWm)
https://www.shadertoy.com/view/WXVGWm

Nice simple Matrix filter
[<img width="1304" height="441" alt="image" src="https://github.com/user-attachments/assets/4b5afc42-e0f7-4d81-bf78-808e892a10e2" />](https://www.shadertoy.com/view/Mffczj)
https://www.shadertoy.com/view/Mffczj


[<img width="892" height="440" alt="image" src="https://github.com/user-attachments/assets/0667dd33-f8bc-478c-9cab-e8b08bc566f4" />](https://www.shadertoy.com/view/XsfcD8)
https://www.shadertoy.com/view/XsfcD8

Psych
[<img width="980" height="464" alt="image" src="https://github.com/user-attachments/assets/2c17b950-9f19-4809-bef7-4d357f1d4eb2" />](https://www.shadertoy.com/view/lltGW2)  
https://www.shadertoy.com/view/lltGW2  

Sober Filter
<img width="1484" height="708" alt="image" src="https://github.com/user-attachments/assets/84bd90be-02c3-4355-9858-805e2b973603" />

Good edge glow 
[<img width="1191" height="550" alt="image" src="https://github.com/user-attachments/assets/76673ad7-9036-4655-95b0-2eadd79520f7" />](https://www.shadertoy.com/view/XssGD7)
https://www.shadertoy.com/view/XssGD7

The fuck :) , Game of life  Sobel Conway
[<img width="1268" height="449" alt="image" src="https://github.com/user-attachments/assets/9f3befed-36e9-46f5-9220-667fa8a7d0f1" />](https://www.shadertoy.com/view/WdXSRr)
https://www.shadertoy.com/view/WdXSRr


Sober but with color
[<img width="1025" height="477" alt="image" src="https://github.com/user-attachments/assets/0a9f007b-5b4d-4ee0-a6cc-5c441e16b650" />](https://www.shadertoy.com/view/3lVBRV)
https://www.shadertoy.com/view/3lVBRV


Toon
[<img width="1252" height="441" alt="image" src="https://github.com/user-attachments/assets/95150b0f-eb07-4f20-8dfe-1df659e506cb" />](https://www.shadertoy.com/view/wdScWD)
https://www.shadertoy.com/view/wdScWD

Try this one with sound
[<img width="1258" height="451" alt="image" src="https://github.com/user-attachments/assets/06777cfc-0513-43f0-8d5d-371d2afbc025" />](https://www.shadertoy.com/view/fdKGDD)  
https://www.shadertoy.com/view/fdKGDD  

[<img width="1209" height="437" alt="image" src="https://github.com/user-attachments/assets/ca57f5ba-a74d-40f4-80bd-902e26e9d55e" />](https://www.shadertoy.com/view/4dyGWm)  
https://www.shadertoy.com/view/4dyGWm  

Gameboy world
[<img width="1445" height="480" alt="image" src="https://github.com/user-attachments/assets/605744fb-2e53-4d43-848c-756b14dec227" />](https://www.shadertoy.com/view/ttsSzr)
https://www.shadertoy.com/view/ttsSzr

Cubery
[<img width="1367" height="481" alt="image" src="https://github.com/user-attachments/assets/23e1df32-8e42-40d3-80f7-eaf555c72699" />](https://www.shadertoy.com/view/XscSWH)
https://www.shadertoy.com/view/XscSWH

Cells Cam
[<img width="1226" height="438" alt="image" src="https://github.com/user-attachments/assets/f38fbc07-d0af-4043-b7ec-39659c33ffeb" />](https://www.shadertoy.com/view/ftVyDR)  
https://www.shadertoy.com/view/ftVyDR  

Green Matrix Sobel  
[<img width="1298" height="438" alt="image" src="https://github.com/user-attachments/assets/cf6a89d9-4ef3-4043-8f33-2e27e93743fc" />](https://www.shadertoy.com/view/7td3Wf)
https://www.shadertoy.com/view/7td3Wf


Good old line scanner
[<img width="1126" height="448" alt="image" src="https://github.com/user-attachments/assets/53b4d311-f916-4d4d-95df-cad174c4f277" />](https://www.shadertoy.com/view/XlVcDz)
https://www.shadertoy.com/view/XlVcDz

Vertical one
[<img width="1070" height="436" alt="image" src="https://github.com/user-attachments/assets/d1d8c24f-dd7c-4b76-b92c-e646c13edf17" />](https://www.shadertoy.com/view/ttKBDR)
https://www.shadertoy.com/view/ttKBDR

neons  nice sobel
[<img width="1436" height="446" alt="image" src="https://github.com/user-attachments/assets/b4c736e6-e097-423e-bda2-b7123d1bb9bc" />](https://www.shadertoy.com/view/wlcyD2)
https://www.shadertoy.com/view/wlcyD2  

Motin Hight Light
[<img width="1028" height="440" alt="image" src="https://github.com/user-attachments/assets/b8140708-e982-4741-a264-43cfbb230395" />](https://www.shadertoy.com/view/4d3GDB)
https://www.shadertoy.com/view/4d3GDB

Would love a "Jurassic park" Game with that kind of shader
[<img width="1583" height="451" alt="image" src="https://github.com/user-attachments/assets/fa463382-dd40-4085-b1d9-666b2ff9de51" />](https://www.shadertoy.com/view/ctVBWm)
https://www.shadertoy.com/view/ctVBWm

Fun time lag
[<img width="1154" height="430" alt="image" src="https://github.com/user-attachments/assets/6bf00ed6-56c1-49f1-8fcb-20c0e388941d" />](https://www.shadertoy.com/view/dsjXWw)
https://www.shadertoy.com/view/dsjXWw


RGB Screen Line shader
[<img width="1193" height="439" alt="image" src="https://github.com/user-attachments/assets/8be49c24-271f-444b-a552-f1d2dbb53619" />](https://www.shadertoy.com/view/4fXXWS)
https://www.shadertoy.com/view/4fXXWS

[<img width="1348" height="469" alt="image" src="https://github.com/user-attachments/assets/bf807dc8-e7ec-4660-a167-2c78b3f6db57" />](https://www.shadertoy.com/view/Mf3yzl)  
https://www.shadertoy.com/view/Mf3yzl  

Convert to Pixel
[<img width="1325" height="512" alt="image" src="https://github.com/user-attachments/assets/6d249a03-6c9e-43ea-bb5f-dedecac54f8c" />](https://www.shadertoy.com/view/3lXGzj)
https://www.shadertoy.com/view/3lXGzj
[<img width="1309" height="449" alt="image" src="https://github.com/user-attachments/assets/1837b91c-4371-4d57-8628-4e97180c6eae" />](https://www.shadertoy.com/view/MssBzn)
https://www.shadertoy.com/view/MssBzn

Mirror classic
[<img width="1206" height="446" alt="image" src="https://github.com/user-attachments/assets/fad5c94e-c9de-4a31-9975-1381024c2863" />](https://www.shadertoy.com/view/WtSXzK)
https://www.shadertoy.com/view/WtSXzK

THere is a way to make music with that
[<img width="1186" height="451" alt="image" src="https://github.com/user-attachments/assets/0a5ce0ac-1a30-46da-9d46-86c6a0f17deb" />](https://www.shadertoy.com/view/wlKczW)
https://www.shadertoy.com/view/wlKczW

## Life with lag ?
I was there 3000 years ago 
[<img width="1238" height="651" alt="image" src="https://github.com/user-attachments/assets/883f8fb0-80b4-4c95-8d85-dea8d8741399" />](https://youtu.be/_fNp37zFn9Q?t=48)
https://youtu.be/_fNp37zFn9Q?t=48

[<img width="1197" height="300" alt="image" src="https://github.com/user-attachments/assets/48a2ba03-1fa7-4b51-a12f-9d51ec058040" />](https://youtu.be/_fNp37zFn9Q?t=71)
https://youtu.be/_fNp37zFn9Q?t=71

[<img width="1396" height="659" alt="image" src="https://github.com/user-attachments/assets/ef591b57-8a12-4bef-abc8-8e7927cb176b" />](https://youtu.be/_fNp37zFn9Q?t=90)

[<img width="868" height="402" alt="image" src="https://github.com/user-attachments/assets/6e1fae1c-fb2d-4c75-80e4-6f1d1bf49fdb" />](https://youtu.be/_fNp37zFn9Q?t=150)
https://youtu.be/_fNp37zFn9Q?t=150
[<img width="1381" height="564" alt="image" src="https://github.com/user-attachments/assets/0a856ccf-f08e-4f0e-96d4-f1bc4598c456" />](https://youtu.be/_fNp37zFn9Q?t=154)
https://youtu.be/_fNp37zFn9Q?t=154





