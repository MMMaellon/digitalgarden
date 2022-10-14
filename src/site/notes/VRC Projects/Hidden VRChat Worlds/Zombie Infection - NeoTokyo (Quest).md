---
{"dg-publish":true,"permalink":"/vrc-projects/hidden-vr-chat-worlds/zombie-infection-neo-tokyo-quest/","dgHomeLink":true,"dgPassFrontmatter":false,"dgShowBacklinks":true,"dgShowLocalGraph":true}
---

# [VRChat Link](https://vrchat.com/home/world/wrld_0e6b77e6-ce49-425f-9b9a-4fc3978c5dd4)

I'm having lots of trouble getting it optimized enough for Quest. Right now, I average 30 fps in an empty lobby :(

I was trying to pioneer a new optimization where I condense many different textures into one with texture arrays. This would allow me to have one material for many different meshes without atlassing. The reason why I didn't want to atlas my textures was because there's a lot of tiling on this map.

Unity was able to batch all the merged materials into one batchcall, but unfortunately the fps didn't improve. I also deleted all the Udon scripts to make sure they weren't the source of the lag, so I suspect texture arrays come with their own overhead.