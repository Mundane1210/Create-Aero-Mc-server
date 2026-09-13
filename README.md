# Create-Aero-Mc-server
Mods for the create aeronautics server. Included basic mods list, readme for installation for both minecraft and cracked tlauncher version, and extra shaderpack if you want it asw.

I RECOMMEND DOWNLOADING AND USING TLAUNCHER IF YOU CAN CUZ IT WILL BE EASIER TO SET UP MODS AND SHIT
-TLAUNCHER IS A PIRATED COMPLETLEY SAFE VERSION OF MC THAT JUST MAKES SHIT 10X EASIER TO USE. BUT IF YOU DONT FEEL LIKE IT ITS FINE IT SHOULD ALL STILL WORK ANYWAYS
you can download tlauncher here: https://tlauncher.org/



copy paste all ts in to your chat or claude to get a personal tailored set up guide if you cant figure it out or you run into some error.



# Create Aeronautics Server — Setup Guide

**Minecraft Version:** 1.21.1
**Mod Loader:** NeoForge 21.1.250

---

## 1. Installing the Modpack Zip

You'll need the `mods.zip` file shared by the server owner, plus a NeoForge 1.21.1 (build 21.1.250) client set up. Follow the section below that matches your launcher.

### 1.1 Basic (Official Minecraft Launcher)

1. Install NeoForge on your PC:
   - Go to [neoforged.net](https://neoforged.net) and download the installer.
   - Run it, select **"Install Client"**, and choose version **21.1.250**.
   - This creates a new profile in your official Minecraft Launcher.
2. Open the official Minecraft Launcher, select the new **NeoForge 1.21.1** profile from the dropdown, and click Play once to let it generate the folder structure. Close the game after it reaches the main menu.
3. Open your `.minecraft` folder:
   - Windows: `%appdata%\.minecraft`
   - Mac: `~/Library/Application Support/minecraft`
4. Inside `.minecraft`, find (or create) a folder named `mods`.
5. Extract the mods.zip file I provided and drag **all the .jar files** directly into the `mods` folder (not inside a subfolder — the jars need to sit loose at the top level).
6. Launch the game using the NeoForge 1.21.1 profile.
7. Go to **Multiplayer > Add Server**, paste in the server address, and connect.





### 1.2 TLauncher

1. Open TLauncher and create a new modded profile:
   - Click **"Create a mod-pack"** (or similar option depending on your TLauncher version).
   - **Loader type:** NeoForge
   - **Game version:** 1.21.1
   - **Loader version:** 21.1.250
   - Give it a name (e.g. "Create Aeronautics Server") and click **Create**.
2. Open the profile's folder:
   - Go back into the profile settings and click **"Open the mod-pack folder"**.
3. Inside that folder, find (or create) a folder named `mods`.
4. Extract the `mods.zip` file and drag **all the .jar files** directly into that `mods` folder.
5. Save the profile settings, then select the profile from TLauncher's dropdown and click **Play**.
6. Go to **Multiplayer > Add Server**, paste in the server address, and connect.

> **Note:** Every player, regardless of launcher, needs the exact same mods.zip contents. Mismatched mod lists will cause a "Failed to connect" or "Incompatible client" error.

---





## 2. Installing Shaders

Shaders are **optional** and **client-side only** — they don't need to match between players, so everyone can pick their own settings.

We recommend **Complementary Reimagined** as the shader pack — it looks great while staying lighter on performance than heavier options like Complementary Unbound, which matters since we're already running a large modpack.

### 2.1 Basic (Official Minecraft Launcher)

1. Download **Complementary Reimagined** from [Modrinth](https://modrinth.com) — make sure the shader pack .zip stays zipped, don't extract it.
2. In your `.minecraft` folder, find (or create) a folder named `shaderpacks`.
3. Drop the shader pack .zip file directly into `shaderpacks`.
4. Launch the game, go to **Options > Video Settings**, and click **Shaders**.
5. Select **Complementary Reimagined** from the list and click **Done**. The first load may briefly freeze while shaders compile — this is normal.

#### Settings for lower-end PCs

If you experience low FPS or stuttering:

- Open **Shader Options** from the Shaders menu.
- Set **Performance Profile** to **Medium** or **Low**.
- Lower **Shadow Distance** (try 64–96 blocks instead of the default).
- Disable **Reflections** and **Volumetric Clouds/Fog** if enabled.
- Reduce **Render Distance** in normal Video Settings (8–10 chunks) to further ease the load, since we're already running a heavy modpack on top of shaders.






### 2.2 TLauncher

1. Download **Complementary Reimagined** from [Modrinth](https://modrinth.com) — keep it zipped.
2. Open your TLauncher profile's mod-pack folder (same place your `mods` folder is).
3. Find (or create) a folder named `shaderpacks`.
4. Drop the shader pack .zip file directly into `shaderpacks`.
5. Launch the game with your NeoForge profile, go to **Options > Video Settings**, and click **Shaders**.
6. Select **Complementary Reimagined** and click **Done**.

#### Settings for lower-end PCs

Same as above:

- Open **Shader Options**.
- Set **Performance Profile** to **Medium** or **Low**.
- Lower **Shadow Distance** to around 64–96 blocks.
- Disable **Reflections** and **Volumetric Clouds/Fog**.
- Lower normal **Render Distance** to 8–10 chunks in Video Settings.

---

## Troubleshooting

- **"Incompatible client" error:** Your NeoForge build doesn't match the server. Double-check it's exactly **21.1.250**.
- **"Failed to verify username":** You need to be on a cracked/offline-enabled server — this should already be configured, but if it recurs, let the server owner know.
- **Mods missing or crash on join:** Re-check that every file from `mods.zip` made it into your `mods` folder, with nothing left zipped or in a subfolder.

copy paste all ts in to your chat or claude to get a personal tailored set up guide if you cant figure it out or you run into some error
