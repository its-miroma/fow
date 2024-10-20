# Unsupported

FO is a Fabric modpack for Minecraft: Java Edition. Because of this, it does not support the following platforms:

## Bedrock Edition

FO is a modpack for Minecraft: Java Edition, so it does not support Bedrock at all.

However, one of [FO's principles](principles.md) is focusing on parity with Bedrock Edition if possible.

## Other Modpacks

FO does not officially support nor recommend being installed with other modpacks, because that may cause conflicts.

You may want to [add custom mods](../how-to/add-mods/) instead.

{% hint style="info" %}
If you still want to do it on your responsibility, you may install the other modpack first, then copy FO's files on it. See the [manual installation instructions](../how-to/install/manual.md).

Note that you will not be able to get help from FO, and probably not from the other modpack either.
{% endhint %}

## Other Loaders

FO is based on [Fabric](principles.md), <!-- TODO: update link --> and does not support other loaders, such as [NeoForge](https://neoforged.net/) or [Quilt](https://quiltmc.org/).

You may try to run FO on Quilt, but this is not officially supported.

FO is tracking the sustainability and popularity of Quilt in [issue #257](https://github.com/Fabulously-Optimized/fabulously-optimized/issues/257). If it proves fruitful, FO may support Quilt in the future.

## Game Clients

FO is not compatible with "game clients", including "PvP clients".

You may want to [add custom mods](../how-to/add-mods/) instead.

## Other Launchers

FO officially supports the [installation on five launchers](../how-to/install/). That does not mean the installation on other launchers is impossible, but FO will not be able to help you in that case.

### ATLauncher

ATLauncher is not suppported because of its confusing and complex interface. However, if that changes, FO may support ATLauncher.

### GDLauncher Carbon

FO may support [GDLauncher Carbon](https://gdlauncher.com/en/blog/curseforge-partnership-announcement) in the future.

### GDLauncher Legacy

GDLauncher Legacy is not supported because it is outdated and it has other technical issues.

Follow these instructions to migrate to [Prism Launcher](https://prismlauncher.org/):

1. Open **GDLauncher Legacy**
2. Right-click on the previously-used instance
3. Click on **Open Folder**
4. Follow the [FO installation instructions for Prism Launcher](../how-to/install/prism-launcher/)
5. In Prism Launcher, click on the **Folder** button on the left
6. Move the following files from the folder you opened in _step 3_ to the folder you opened in _step 5_:
   * `saves`: Your local worlds
   * `resourcepacks`: Your resource packs, if any. If you're asked to replace files, do not!
   * `shaders`: Your shaders, if any
   * `screenshots`: Your screenshots, if any
   * `server.dat`: Your multiplayer servers, if any
   * `options.txt`: Your custom options and keybinds, if any. If you want the [recommended FO settings](../info/options.md), do not copy it
7. Check if the instance in Prism Launcher works
8. Uninstall GDLauncher Legacy

### Pojav Launcher

Pojav Launcher is not supported because of the following drawbacks:

* Long installation process
* High energy usage
* Poor performance

However, FO may support Pojav Launcher in the future.

### PolyMC

{% hint style="danger" %}
PolyMC is compromised! You should switch away immediately!

Follow these instructions to migrate to [Prism Launcher](https://prismlauncher.org/), a safe fork of PolyMC.
{% endhint %}

1. Uninstall PolyMC
2. Install [Prism Launcher](https://prismlauncher.org/)
3. Open **Prism Launcher**. You should get a prompt.
4. Pay attention to what the prompt says. If it says:
   * > It looks like you used PolyMC before. Do you want to migrate your data to the new location of Prism Launcher?
     * Click **Yes** to migrate automatically
   * > Old data from PolyMC was found, but you already have existing data for Prism Launcher. Sadly you will need to migrate yourself. Do you want to be reminded of the pending data migration next time you start Prism Launcher?
     1. Click **No** to close the prompt
     2. Open PolyMC's `instances` directory:
        * Windows: `%APPDATA%/PolyMC/instances`
        * macOS: `~/Library/Application Support/PolyMC/instances`
        * Linux: `~/.local/share/PolyMC/instances`
        * Portable: `PolyMC/instances`
     3. Copy all files and folders from that folder
     4. In Prism Launcher, click on **Folders**
     5. Click on **View Instance Folder**
     6. Paste the files you copied in _step 3_ in the folder you opened in _step 5_
     7. Close and reopen Prism Launcher. You should find all of your instances there
     8. Sign into your accounts and complete Prism Launcher's configuration
5. Follow the [FO installation instructions for Prism Launcher](../how-to/install/prism-launcher/)

### Cracked launchers

FO does not support any launcher that lets you run the game without having purchased it. Choose and use one of the [five launchers supported by FO](../how-to/install/).

{% hint style="success" %}
There is a way to obtain Minecraft for cheaper: You can get a [giftcode from a trusted reseller](https://download.fo/minecraft)!
{% endhint %}

#### TLauncher

{% hint style="danger" %}
TLauncher is malware! You should [reset your entire OS](https://howtogeek.com/202590/stop-trying-to-clean-your-infected-computer-just-nuke-it-and-reinstall-windows).
{% endhint %}
