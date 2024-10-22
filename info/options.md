# Changed Options

{% hint style="info" %}
FO uses [YOSBR]() to manage settings and to allow updates without losing your settings, but you will not get FO's latest recommendations.

If you want to, you can always [get FO's recommended settings](#reset-settings).
{% endhint %}

You can find [FO's settings file on GitHub](https://github.com/Fabulously-Optimized/fabulously-optimized/tree/main/Packwiz/1.21.1/config).

<!-- TODO: description -> hover on option -->

| Option                        | Description | Vanilla | FO | Reason |
| ----------------------------- | ----------- | ------- | -- | ------ |
| `advancedItemTooltips`        | Enables ["advanced" tooltip info](https://www.online-tech-tips.com/wp-content/uploads/2021/01/Armor-Tooltips-610x571.png) on items - item ID and durability, and exact color hex code for dyed armor | false | true | These are useful for much more than just debugging - if you're using commands, want to know the exact durability value, learning English, etc. Plus, this setting is hidden in the debug menu, so many people might not know about it. |
| `darkMojangStudiosBackground` | Makes the Mojang Studios splash screen white-on-black instead of white-on-red | false | true | Black background is less intrusive than red, partial Bedrock Edition parity |
| `enableVsync`                 | Toggle [VSync](https://en.wikipedia.org/wiki/Screen_tearing#Vertical_synchronization), a FPS-limiting system | true | false | Disabling VSync by default helps users instantly see the benefits of FO, reduces input lag and increases framerate when using shaders. The benefits of enabling or disabling it vary by system; also note that FO has an option to use Adaptive VSync on some systems. |
| `guiScale`                    | Size of the menu and interface elements | 0 | 3 | 3 is more usable on most screens, 0 (Auto) can get too large on Full HD and larger screens, including most Macs' "Retina" displays |
| `incompatibleResourcePacks`   | A list of resource packs that have been forcefully enabled, despite being marked as incompatible | \[] | (varies) | Mod-provided resource packs that have old manifest version but are known to be compatible. Usually contains just [Continuity](https://www.curseforge.com/minecraft/mc-mods/continuity)'s resource packs, but values may vary by FO version. |
| `joinedFirstServer`           | Whether to display the hint for [Social Interactions](https://minecraft.wiki/w/Social\_Interactions\_screen) | false | true | I expect my users to already know that Social Interactions can be opened with `P`; the screen is easily discoverable by the "Player Reporting" button |
| `maxFps`                      | The maximum framerate | 120 | 260 | 260 means "unlimited", which allows you to see the full FPS that your system is capable of |
| `onboardAccessibility`        | Indicates whether the user has not seen the accessibility onboarding screen | true | false | Minecraft already has an easily accessible accessibility button in the main menu, this screen just creates annoyances for the majority who don't need it. [Read more about accessibility in FO](accessibility.md) |
| `operatorItemsTab`            | Shows operator-only items (command blocks, lights, barriers, etc.) in a Creative inventory tab, when you have operator access (`/op`) | false | true | It is useful and it only appears when you have the permission for it, so it's weird Mojang even made it an option |
| `resourcePacks`               | Adjusts which resource packs are enabled by default | \[] | `["vanilla","fabric","continuity:glass_pane_culling_fix","continuity:default","file/SodiumTranslations.zip","file/Mod Menu Helper.zip","file/Chat Reporting Helper.zip","file/Fast Better Grass.zip"]` | Enabled [mod-provided and FO-exclusive resource packs](resource-packs/README.md) by default |
| `lang`                        | Adjusts the game's language | en_us | (your OS language) | Enables user's system language by default, for usability, accessibility and discoverability purposes - courtesy of [Language Reload](https://www.curseforge.com/minecraft/mc-mods/language-reload). Not available for all launchers and operating systems. |
| `simulationDistance`          | Redstone and mob spawning distance | 12 | 6 | Better performance regardless of the rendering distance you use |
| `skipMultiplayerWarning`      | Whether to skip [the legal disclaimer](https://minecraft.wiki/w/File:Multiplayer\_disclaimer.png) when opening the multiplayer screen | false | true | I expect my users to already know that the third party servers are not owned or monitored by Mojang Studios or Microsoft. |
| `telemetryOptInExtra`         | Sets the telemetry (analytics data collection) toggle to "minimal". | false | false | While "minimal" is the default right now anyway, it may not always be the case, hence the enforcement by FO. [Debugify](https://curseforge.com/minecraft/mc-mods/debugify) is used to disable it entirely though, so this is also just a fallback. |
| `tutorialStep`                | The next step of [tutorial hints](https://minecraft.wiki/w/Tutorial\_hints) | movement | none | If you know how to install a modpack, you probably don't need those tutorials anymore |

## Reset Settings

1. Open FO's folder from your launcher
   * CurseForge App: right click on the modpack tile → `Open Folder`
   * Modrinth App: right click on the modpack tile → `📂 Open folder`
   * Prism Launcher: right click on the instance → `Folder` → `.minecraft`
   * MultiMC: right click on the instance → `Minecraft Folder`
   * Minecraft Launcher: click `Installations` → hover on the instance → click `📁`
2. If you want to reset mod options, locate and delete the `config` folder
3. If you want to reset vanilla options, locate and delete the `options.txt` file
4. Download your version of [FO from Modrinth](https://modrinth.com/modpack/fabulously-optimized/versions) again
5. Rename the file you've downloaded to `pack.zip`, and extract it
6. Open the `overrides` folder inside of it
7. Move the `configs` folder from _step 6_ to the modpack's folder opened in _step 1_
8. Launch Minecraft from your launcher
9. If you can see the new settings in-game, you're done!
