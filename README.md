# Bevy voxel
Open source voxel with [Bevy](https://bevyengine.org/) (Rust).

## ⚠️ Archiving the repository
I've been thinking for a long time that at a certain point I'd want to try and bring a commercial game to life, based on the foundation laid in this repo.

If succesful this would allow me to quit my day job and focus on this vision that I love, but I didn't want to do that until solid Bevy voxel foundations were laid here, in the open, to help other make their own "minecraft but better".

With the rise of AI 2 things have happened:
1. The value of this repository as a learning resource has gone down 
2. Bringing my vision for a Riverbed game to life has become way easier

Riverbed lacks polish but has already achieved a lot:
- performant meshing with LODs (implemented in binary-greedy-meshing)
- performant, biome-driven terrain generation
- asset-based definitions of blocks, biome conditions, plants conditions, crafting recipe, block breaking, etc.  
*all of this (mostly) AI-free*

All of this is compatible with any voxel game, but I have a very specific vision for my game.  
The more I push towards this vision the less useful this repository becomes as a foundation for other games.

Considering all of this, now is a good time for me to archive this repository and fully commit to the game I want to bring to life.

That said, I will still contribute to voxels in other, more sustainable and useful ways:
- maintaining separate voxel crates such as binary-greedy-meshing
- doing open research on under-developped topics such as terrain generation, water sim, etc.

## Current state
![riverbed_new_pic](https://raw.githubusercontent.com/Inspirateur/riverbed/refs/heads/main/assets/screenshot.png)
*featured on this screenshot is an infinitely generated, editable terrain, and a 4km render distance (250 in Minecraft)*  

### Thanks
- [@kokounet](https://github.com/kokounet): major contributions on rendering  
*he's a big part of why we're able to reach 4km of render distance, many thanks!*
- [@Involture](https://github.com/Involture): contributed to the efficient packing of chunk data in RAM  
*one of the many invisible optimisations required to make such a game work*

I'm also very grateful for Bevy - the engine powering the game - and the open source Rust ecosystem as a whole, which I will continue to contribute back to.
