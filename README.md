# Unity--UNET
## Introduction
> The information of objects i.e data, trans-receives between server and client using TCP/IP in internet.
> The data converts into packets thus sends to the client from server over the internet.
> The server are of types: 
> 1. Authoritative
> 2. Non-Authoritative
> * [Follow for more info.](https://forum.unity.com/threads/authoritative-non-authoritative-server-questions.49942)
 ### [Unity desc. link for more info. on this topic](https://docs.unity3d.com/Manual/UNetOverview.html)
 ***************************************************
 ## Executable Steps
 > 1. Basic Client server interaction:
 > * Get to known with Unity [Network manager](https://docs.unity3d.com/Manual/UNetManager.html) and [Network manager HUD](https://docs.unity3d.com/Manual/UNetManagerHUD.html)(GUI).
 > * Network Identity and Network transform.
 > 2. Dealing with [Latency](https://en.wikipedia.org/wiki/Latency_(engineering)).
 > *  Interpolation and its working methodology. P=P0 + V0T + 1/2*A0T^2
 > *  The Netwrok Transform.(https://docs.unity3d.com/Manual/class-NetworkTransform.html)
 > 3. Customising Player Character
 > *  When you are in game mode, both the player prefab in local and server side instantiates on same position, so to avoid it follow the steps:
 > * 1. Create two or as many as gameobjects as the players connected throughout the network, attach network identity and network starting position to them.
 > * 2. Drag their references to Network Manager gameobject's spawn position section.
 > * [Syncvar](https://docs.unity3d.com/ScriptReference/Networking.SyncVarAttribute.html)
#### Reference links
###### [Udemy](https://www.udemy.com/unet_intro/) 
