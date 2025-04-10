---
layout: project
order: 2

name: Universe Island
image: /assets/images/universe-island/thumbnail.png
carousel_images:
        [
          /assets/images/universe-island/1.png,
          /assets/images/universe-island/2.webp,
          /assets/images/universe-island/3.webp,
          /assets/images/universe-island/4.webp,
          /assets/images/universe-island/5.png,
          /assets/images/universe-island/6.png,
        ]
tools: [ Desktop, Android, iOS ]
project_links: [ https://universeisland.games/, https://apkpure.com/universe-island/com.UniverseIslandLLC.UniverseIsland/amp ]
client: Universe Island LLC

description: >-
  Universe Island is a free-to-play, sci-fi themed, 1vs1 shooter game that integrates play-to-earn mechanics fueled by UIM Tokens. \n
  Players engage in fast-paced PvP and PvE combat within an expansive open world, featuring immersive environments and dynamic gameplay. \n
  The game is optimized for mobile devices and offers cross-platform play, allowing players to experience the metaverse on both PC and mobile platforms. 

project_scope: Commercial
project_role: Unity Developer
project_duration: 2 years
team_size: 15
---

### My Contributions

- **Floating Origin System**: Designed and implemented a dynamic floating origin system to support a massive open world without floating-point precision issues. Carefully handled repositioning of Unity components like particle systems, physics objects, and camera logic during origin shifts to maintain visual and gameplay consistency in both singleplayer and multiplayer contexts.
- **Async Proximity-Based Island Loading**: Used Addressables and UniTask to load islands asynchronously based on player proximity, optimizing memory usage and improving performance during exploration.
- **Mirror Networking (Frontend & Backend)**: Implemented core networking systems using Mirror for multiplayer synchronization. Worked on both frontend logic and backend communication to ensure stable and responsive gameplay.
- **Authentication Systems**: Integrated Google, Apple, and email-based sign-in/log-in options to support a seamless multi-platform user experience.
- **Frontend API Integration**: Developed and integrated API endpoints to connect the game client with server-side services, including player data, inventory, and session management.
- **Audio Integration with MasterAudio**: Implemented in-game audio systems using DarkTonic’s MasterAudio, including support for spatial audio and UI feedback.
- **Inventory & Items System**: Built a modular inventory system to manage item data, interactions, and persistence across sessions.
- **Blockchain/NFT Integration**:
  - Integrated blockchain functionality to support in-game item NFTs.
  - Enabled players to view, use, and manage NFT items directly within the game environment.
- **UI Implementation**: Created both screen-space and 3D in-world user interfaces for immersive interaction and clean feedback.

### Challenges and solutions

- **Floating Origin System & Networking Compatibility**: Maintaining synchronization in multiplayer while shifting the world origin was complex due to positional drift and desynchronization of visual components.
  - _Solution_: Built a unified origin-shift manager that updated key systems (Mirror transforms, particle systems, rigidbodies, camera targets) while compensating for shift deltas. Also introduced buffer zones to reduce jitter in networked objects and smoothed transitions between shifted zones.
- **Async World Streaming**: Ensuring seamless asset loading during gameplay without noticeable hitches or delays.
  - _Solution_: Combined proximity checks with UniTask-based async loading queues and preload buffers, enabling responsive streaming while keeping memory usage efficient.
