# How to Update: MultiMC

If you had installed [FO on MultiMC with automatic updates](../install/multimc.md#automatic-updates), you just need to run the existing versions. If you get a popup saying that **This modpack uses new versions of the following...**, then click on the **Update** button.

However, if you had installed [FO on MultiMC without automatic updates](../install/multimc.md#easy-installation), or if you're updating to a new version of Minecraft, keep on reading.

1. Follow the [FO installation instructions for MultiMC](../install/multimc.md) again. This will create a new instance
2. In **MultiMC**, click on the new version, then click on **Minecraft Folder**
3. Click on the previous version as well, then click on **Minecraft Folder**
4. Move the following files and folders from the previous version (_step 3_) to the new version (_step 2_):
   * `saves`: Your local worlds
   * `resourcepacks`: Your resource packs, if any. If you're asked to replace files, do not!
   * `shaders`: Your shaders, if any
   * `screenshots`: Your screenshots, if any
   * `server.dat`: Your multiplayer servers, if any
   * `options.txt`: Your custom options and keybinds, if any. If you want the [recommended FO settings](../../info/options.md), do not copy it
5. Once you've moved them, launch the new instance. Minecraft should open up
6. If you can see the newly installed version in the bottom-right corner, you can delete the previous version
