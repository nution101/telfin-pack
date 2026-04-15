# Bash Server — Better Looks

Prism Launcher modpack that adds shaders + performance mods to vanilla Minecraft,
pre-configured for the **Bash Minecraft server** (`mc.telfin.io`).

## Download

**Direct download (share this link with players):**
<https://github.com/nution101/telfin-pack/releases/download/v1.1.0/Bash-BetterLooks-1.1.0.mrpack>

- **Repo:** <https://github.com/nution101/telfin-pack>
- **Latest release:** [v1.1.0](https://github.com/nution101/telfin-pack/releases/tag/v1.1.0)

## Install (players)

1. **Copy the download URL above.**
2. In **Prism Launcher** (https://prismlauncher.org):
   - **Add Instance → Import → From URL**, paste the link, OR
   - Download the `.mrpack` file and drag-and-drop it onto Prism.
3. **Launch the new instance.** Shaders are already on, `mc.telfin.io` is already in your multiplayer list — just click Join.

Using the **Modrinth App** (https://modrinth.com/app) works too: drag-and-drop the `.mrpack` onto the app window.

## What's in it

Matches server version **Minecraft 1.21.11 (Fabric)**.

- [Fabric API](https://modrinth.com/mod/fabric-api) — required for the other mods
- [Iris Shaders](https://modrinth.com/mod/iris) — shader support
- [Sodium](https://modrinth.com/mod/sodium) — performance overhaul (also required for Iris)
- [Simple Voice Chat](https://modrinth.com/mod/simple-voice-chat) — matches the server's voice chat plugin
- [YetAnotherConfigLib (YACL)](https://modrinth.com/mod/yacl) — shared config UI lib
- [Fps Overlay](https://modrinth.com/mod/fps-overlay) — on-screen FPS display
- [Complementary Reimagined](https://modrinth.com/shader/complementary-reimagined) — shader pack, pre-enabled

**Not bundled (CurseForge-only, add manually if you want them):**
Controllable + Framework (MrCrayfish). These are only on CurseForge, which Modrinth
packs can't reference directly. After importing the pack, open the instance in Prism →
**Mods tab → Download Mods → search CurseForge** to add them in ~30 seconds.

Overrides bundled in the pack:

- `servers.dat` — `mc.telfin.io` pre-added as "Bash Server"
- `config/iris.properties` — Complementary selected + shaders enabled
- `options.txt` — fabulous graphics, render distance 12

## Notes

- Vanilla clients can still join the server — this pack is optional, just for visuals.
- When the server updates past 1.21.11, this pack needs a refresh (new mod versions).
- The pack is client-side only. No server-side mods are added or required.
