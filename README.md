vocaloid-threejs
================

Vocaloid models in three.js
The models are in pmd/pmx which is the file format that miku miku dance (a japanese program to pose and animate vocaloid models)

In order to get them to work in three.js.
Use blender and [blender_mmd_tools](https://github.com/sugiany/blender_mmd_tools)

Good screencast by yomotsu: [http://www.youtube.com/watch?v=ZFb5F8brFLw](http://www.youtube.com/watch?v=ZFb5F8brFLw)

My inital problem was an [ascii error](http://i.imgur.com/9h2woGw). Since the model and everything associated with it was in japanese and blender doesn't handle those character so you have to rename everything.

##[MikuV2](http://jimicy.com/vocaloid-threejs/)

Works.  
Audio syncing needs some work. Currently using setTimeOut() with a delay of 2s before song is played.  
![Imgur](http://i.imgur.com/ZqnTv1L.png)

##MikuTDA

Just displays this and does nothing  
![Imgur](http://i.imgur.com/HlzKLlL.png)

#Sources

Models obtained from:

mikuV2: 
MikuMikuDance default models Miku_Hatsune_Ver2.pmd  
dl: [model](https://dl.dropboxusercontent.com/u/11788669/Model.zip)

mikuTDA:  
miku TDA append by [Tda](http://mikumikudance.wikia.com/wiki/Tda)  
[http://mikumikudance.wikia.com/wiki/Miku_Hatsune_Append_%28Tda%29](http://mikumikudance.wikia.com/wiki/Miku_Hatsune_Append_%28Tda%29])  
dl: [model](http://touko-p.deviantart.com/art/Append-Miku-Tda-Original-MMD-309007204)

Motion data & Music  
Happy hands meme  
[http://learnmmd.com/http:/learnmmd.com/create-an-mmd-video-using-the-happy-hands-meme/](http://learnmmd.com/http:/learnmmd.com/create-an-mmd-video-using-the-happy-hands-meme/)  
dl:[vmd & mp3](https://dl.dropboxusercontent.com/u/11788669/Happy%20Hands%20by%20Emmersaur.zip)


#License
Hatsune Miku, © Crypton Future Media, Inc. 2007 (for Hatsune Miku)  
[Creative Commons-Attribution-NonCommercial 3.0 Unported](http://creativecommons.org/licenses/by-nc/3.0/legalcode)  
[http://piapro.net/en_for_creators.html](http://piapro.net/en_for_creators.html)
