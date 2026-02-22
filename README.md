# Cuddly Doodle — Mods & Media

This repository contains a harmless Bedrock add-on skeleton and a small website that plays and lets you download songs.

What I added:
- `index.html` — site with instructions, a simple song player, and links to the Bedrock add-on skeleton.
- `bedrock-addon/` — a skeleton manifest and README to get started with Minecraft Bedrock add-ons.
- `assets/songs/songs.json` — a sample song list used by the player.

How to use the Bedrock skeleton
1. Open the `bedrock-addon/` folder.
2. Add any resource/behavior files you want (textures, models, etc.).
3. Zip the folder contents and rename the `.zip` extension to `.mcpack`.
4. Open the `.mcpack` file on a device running Minecraft Bedrock to import the pack.

Song player
- Update `assets/songs/songs.json` to add or replace song entries. Each entry should have `title`, `artist`, `url`, and `filename` fields.
- Songs can be hosted in the repository under `assets/songs/` or externally; the player will use the provided `url` field.

Next steps you might ask me to do:
- Add a sample resource or texture into `bedrock-addon/`.
- Bundle a ready-to-download `.mcpack` (I can prepare instructions and a script to zip locally).
- Add an admin UI to upload songs to `assets/songs/` (requires server support).
# cuddly-doodle