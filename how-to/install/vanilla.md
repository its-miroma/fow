# How To Install: [Minecraft Launcher (vanilla)](<https://www.minecraft.net/en-us/download>)

The Minecraft Launcher, also known as the vanilla launcher, is a very basic launcher that lacks many features. Because of this the process to install FO is more difficult. Consider using [another supported launcher](./index.md) for easier installation and for automatic updates.

{% hint style="success" %}
We're planning to introduce a simpler installer for the Minecraft Launcher. You may track its progress in [issue #110 on GitHub](<https://github.com/Fabulously-Optimized/fabulously-optimized/issues/110>)
{% endhint %}

[FO uses Fabric](/about/fabric.md), so you will need to install its loader.

1. On macOS and Linux, download and install [Java](<https://download.fo/java>)
2. Download the [Fabric Installer](<https://fabricmc.net/use>)
3. Run the Fabric Installer
4. Select `version 0.16.5` of the Fabric Loader
5. Click on **Install**. You have now installed the Fabric Loader
6. Open the **Minecraft Launcher**
7. Click on **Installations**. You should find a new Fabric installation
8. Click on the folder icon 📂 next to the Fabric installation
9. In your **browser**, open the [FO vanilla downloader](<https://download.fo/vanilla>)
10. If you do not want the latest version, select the version you want from the dropdown. If you're looking for even older versions, read the [legacy instructions](#legacy-instructions)
11. Click on the download button ⬇️. This should download a `zip` file
12. If you get a prompt about popup windows or multiple downloads, please allow them
13. Extract the `zip` file. [What does the `zip` file contain?](#what-does-the-zip-file-contain)
14. Copy all folders from the extracted `zip` file to the `.minecraft` folder that you opened in _step 8_. [Why do I need to copy everything over?](#why-do-i-need-to-copy-everything-over)
15. If you're asked to replace files, replace them
16. If you want the [recommended FO settings](/info/options.md), delete `options.txt`. This will reset your vanilla options (resource packs, language, keybinds...) but you can reapply them later
17. Go back to the **Minecraft Launcher**
18. Launch the Fabric installation from _step 7_. Minecraft should start up
19. If you can see `Fabulously Optimized` in the bottom-right corner, you're done!

## What does the `zip` file contain?

The `zip` file contains the following:

- `config/`: Configuration files that adjust the mods for the best experience
- `mods/`: The mods that are included in FO
- `resourcepacks/`: Small resource packs for the best experience. [What do the resource packs do?](/info/resource-packs/index.md)
- `Copy all 3 folders!`: A dummy files that reminds you to, well, copy all 3 folders!

If you've downloaded the MultiMC `zip` file, you'll find a slightly different folder structure:

- `Fabulously Optimized x.y.z/`: A folder containing the MultiMC instance
  - `minecraft/`: The main folder of the modpack, which contains exactly what was mentioned above
  - `instance.cfg`: A manifest file describing name, icon, type and notes for the instance
  - `mmc-pack.json`: A manifest file describing the version of Minecraft, Fabric and of other dependencies
  - `pack.png`: An icon for the instance

The MultiMC `zip` file used to be hosted on CurseForge - legacy versions are still there - but since FO 6.0.0 it is obtained through the website (see instructions above).

## Why do I need to copy everything over?

FO consists of mods, configuration and resource packs, and all three are necessary. [What does the pack contain?](/info/index.md)

Copying the `mods` folder only may result in the following issues:

- In some versions the game will not launch at all
- Some of your resource packs will be broken
- Some features, such as zoom, will not work as shown
- New unexpected keybinds will appear
- Confusing mod buttons or popups will appear
- Confusing descriptions in the mod list
- There won't be any FO version number in the title screen

If you have mistakenly forgotten to copy the other folders, do the following:

1. Follow _steps 6-8_ from the instructions above to open the installation's folder.
2. Locate and delete the `mods` folder
3. If you had modified your settings in-game, move both `config/` and `options.txt` to a different location
4. Follow _steps 9-15_ from the instructions above
5. If you had backed up your settings in _step 3_ and you don't want the [recommended FO settings](/info/options.md), move yours back
6. Follow _steps 17-19_ from the instructions above

## Legacy instructions

Legacy instructions for FO 4.6.1/Minecraft 1.19.3 and older

1. Install the appropriate version of Java:
   - Minecraft 1.19-1.19.3: [Java 17](<https://download.fo/java17>)
   - Minecraft 1.17-1.18.2: [Java 17](<https://download.fo/java17>) <!-- TODO: Are you sure? -->
   - Minecraft 1.16.5: [Java 8](<https://download.fo/java8>)
2. Install the appropriate version of the [Fabric Loader](<https://fabricmc.net/use>)
   - Minecraft 1.19-1.19.3: `version 0.14.24`
   - Minecraft 1.17-1.18.2: `version 0.14.12`
   - Minecraft 1.16.5: `version 0.13.3`
3. Open the **Minecraft Launcher**
4. Click on **Installations**. You should find a new Fabric installation
5. Click on the folder icon 📂 next to the Fabric installation
6. In your **browser**, open the [**Files section**](<https://www.curseforge.com/minecraft/modpacks/fabulously-optimized/files?showAlphaFiles=show>) on CurseForge
7. Click on the appropriate version of FO
8. Click on **Additional files**. You should find a **MultiMC version**
9. Click on `⋮` → `Download file`
10. Extract the `zip` file. If you see less than 10 mods in it, you have downloaded the wrong version
11. Go to `Fabulously Optimized x.x.x` > `minecraft`. You should find a `zip` file in there
12. Extract the `zip` file
13. Copy all folders from the `zip`'s `minecraft` folder to the `.minecraft` folder that you opened in _step 5_
14. If you're asked to replace files, replace them
15. If you want the [recommended FO settings](/info/options.md), delete `options.txt`. This will reset your vanilla options (resource packs, language, keybinds...) but you can reapply them later
16. Go back to the **Minecraft Launcher**
17. Launch the Fabric installation from _step 4_. Minecraft should start up
16. If you can see `Fabulously Optimized` in the bottom-right corner, you're done!
