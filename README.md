# Square Era Database - Room 4: Cyber City

Persistent world modifications, player profiles, and session state for Square Era 3D Voxel Sandbox Room 4.

## Room Overview
- Room ID: 4
- Room Name: Cyber City
- Game Mode: CREATIVE
- Description: Futuristic Cyberpunk Nexus with Obsidian towers, Amethyst crystal conduits, and neon glow.
- Server Repository: [yasamarium/square-era-server-room4](https://github.com/yasamarium/square-era-server-room4)

## Schema & Files
- `data/world.json`: JSON map of persistent chunk modifications `[ ["x,y,z", blockId], ... ]`.
- `data/players.json`: Registered player profiles and session records.
- `data/chat.json`: Persistent in-room chat history.
- `data/sessions.json`: 5-hour runner cycle timestamps and synchronization checkpoints.

Zero external databases required. Backed 100% by GitHub Git persistence.
