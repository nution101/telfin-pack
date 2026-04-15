# Bash Server — Better Looks

Prism Launcher modpack that adds shaders + performance mods to vanilla Minecraft,
pre-configured for the **Bash Minecraft server** (`mc.telfin.io`).

## What's in it

Matches server version **Minecraft 1.21.11 (Fabric)**.

- [Fabric API](https://modrinth.com/mod/fabric-api) — required for the other mods
- [Iris Shaders](https://modrinth.com/mod/iris) — shader support
- [Sodium](https://modrinth.com/mod/sodium) — performance overhaul (also required for Iris)
- [Complementary Reimagined](https://modrinth.com/shader/complementary-reimagined) — shader pack, pre-enabled

Overrides bundled in the pack:

- `servers.dat` — `mc.telfin.io` pre-added as "Bash Server"
- `config/iris.properties` — Complementary selected + shaders enabled
- `options.txt` — fabulous graphics, render distance 12

## Install

Using **Prism Launcher** (https://prismlauncher.org):

1. Download `Bash-BetterLooks-1.0.0.mrpack` from the latest release.
2. In Prism: **Add Instance → Import → From File → pick the `.mrpack`**.
3. Launch the new instance. Server is already in your multiplayer list. Shaders are on. Play.

Using the **Modrinth App** (https://modrinth.com/app):
drag-and-drop the `.mrpack` onto the app window.

## Notes

- Vanilla clients can still join the server — this pack is optional, just for visuals.
- When the server updates past 1.21.11, this pack needs a refresh (new mod versions).
- The pack is client-side only. No server-side mods are added or required.
