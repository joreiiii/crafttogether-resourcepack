# CraftTogether Resource Pack

Server-mandated resource pack for the CraftTogether Minecraft server.

Based on the "Anti Xray Pack" (Full, for 26.1.x) from Modrinth:
https://modrinth.com/resourcepack/anti-xray-pack

Changes from upstream:
- `pack.mcmeta` description set to "CraftTogether Resources"
- `pack.png` replaced with the server's own icon (plugins/MiniMOTD/icons/Server-Icon.png)
- All glass blockstates and models removed (glass, tinted glass, stained glass and panes), so glass renders as vanilla
- All bed blockstates and the bed block model removed (all 16 colors), so beds render as vanilla
- All sign and hanging sign blockstates and models removed (incl. wall variants), so signs render as vanilla
- All leaves blockstates and models removed (incl. azalea leaves and the `block/leaves` parent), so leaves render as vanilla

The original zip (before the glass, bed, sign and leaves removals) is kept as `CraftTogether-Resources.zip.old`.

Original file sha1: `b496f061938712d616889b74876e6cf9ee3f003d`
