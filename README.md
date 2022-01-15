
# project_soft_bunny
An attempt at creating a smooth and jitter free First Person Controller.
## Contents

1. [ Description ](#description)
2. [ Changelog ](#changelog)

<a name="description"></a>
## 1. Description
#### What is this project and why does it exist?
After working on a couple of small project, most of them being FPS, I've noticed that there is a persistent camera jitter. After a bit of research, I've stumbled upon the idea that it might be due to having different components (character & camera) work in different Updates (FixedUpdate() or Update()). <br/><br/>
If you find this interesting, please consult these links:
- https://johnaustin.io/articles/2019/fix-your-unity-timestep#margin=
- https://youtu.be/qtV8JEIq0Ng

Please Note:
- I'm using Unity version 2021.2.3f1;
- The controller is using the new input system;
- Both character and camera are implemented in Update();


<a name="changelog"></a>
## 2. Changelog

Changelog Legend :

- <span style="color:green">**Green**</span> -  Version successful with no known issues;
- <span style="color:gold">**Yellow**</span> -  Version successful with few known issues;
- <span style="color:orange">**Orange**</span> -  Version partially successful with a couple of known/unknown issues;
- <span style="color:red">**Red**</span> -  Version partially successful with many known/unknown issues;
- <span style="color:black">**Black**</span> -  Version failed;
<br/><br/>

>## 0.0.1
>01/15/2022 • 10:37AM GMT+1
> <span style="color:green">**Green**</span>
>
>Created a FPS character controller using the new unity input system. 
>
>The controller has features like: 
>
>- WASD movement;
>- Gravity;
>- Jumping;
>- Camera control.
>
>Please Note that both character movement and camera control have been implemented in Update(). Keeping that in mind, the stuttering/jitter is still present, although it is inconsistent.
>
<br/><br/>

>## 0.0.2
>01/15/2022 • 3:35PM GMT+1
> <span style="color:green">**Green**</span>
>
>Moved the camera rotation and movement to LateUpdate() as of a suggestion. 
>However the stutter still persists.
>
<br/><br/>
