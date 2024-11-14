---
icon: sliders
---

# Options

FO uses [Your Options Shall Be Respected](https://modrinth.com/mod/yosbr) to manage settings and to allow updates without losing your settings, but you will not get FO's latest recommendations. You can find [FO's settings file on GitHub](https://github.com/Fabulously-Optimized/fabulously-optimized/tree/main/Packwiz/1.21.1/config).

If you want to start fresh, you can always [reset to FO's recommended settings](../../how-to/reset/). You can also check out [other options you may want to change](other.md).

{% hint style="info" %}
Click on each option to get a description of what it does.
{% endhint %}

<table><thead><tr><th>Option</th><th width="100">Vanilla</th><th width="100">FO</th><th>Reason</th></tr></thead><tbody><tr><td><a data-footnote-ref href="#user-content-fn-1"><code>advancedItemTooltips</code></a></td><td>false</td><td>true</td><td>These are useful for much more than just debugging - if you're using commands, want to know the exact durability value, learning English, etc. Plus, this setting is hidden in the debug menu, so many people might not know about it.</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-2"><code>darkMojangStudiosBackgroun</code></a><code>d</code></td><td>false</td><td>true</td><td>Black background is less intrusive than red, partial Bedrock Edition parity</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-3"><code>enableVsync</code></a></td><td>true</td><td>false</td><td>Disabling VSync by default helps users instantly see the benefits of FO, reduces input lag and increases framerate when using shaders. The benefits of enabling or disabling it vary by system; also note that FO has an option to use Adaptive VSync on some systems.</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-4"><code>guiScale</code></a></td><td>0</td><td>3</td><td>3 is more usable on most screens, 0 (Auto) can get too large on Full HD and larger screens, including most Macs' "Retina" displays</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-5"><code>incompatibleResourcePacks</code></a></td><td>[]</td><td>(varies)</td><td>Mod-provided resource packs that have old manifest version but are known to be compatible. Usually contains just <a href="https://curseforge.com/minecraft/mc-mods/continuity">Continuity</a>'s resource packs, but values may vary by FO version.</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-6"><code>joinedFirstServer</code></a></td><td>false</td><td>true</td><td>I expect my users to already know that Social Interactions can be opened with <code>P</code>; the screen is easily discoverable by the "Player Reporting" button</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-7"><code>maxFps</code></a></td><td>120</td><td>260</td><td>260 means "unlimited", which allows you to see the full FPS that your system is capable of</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-8"><code>onboardAccessibility</code></a></td><td>true</td><td>false</td><td>Minecraft already has an easily accessible accessibility button in the main menu, this screen just creates annoyances for the majority who don't need it. <a href="accessibility.md">Read more about accessibility in FO</a></td></tr><tr><td><a data-footnote-ref href="#user-content-fn-9"><code>operatorItemsTab</code></a></td><td>false</td><td>true</td><td>It is useful and it only appears when you have the permission for it, so it's weird Mojang even made it an option</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-10"><code>resourcePacks</code></a></td><td><code>[]</code></td><td><a data-footnote-ref href="#user-content-fn-11">...</a></td><td>Enabled <a href="resource-packs.md">mod-provided and FO-exclusive resource packs</a> by default</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-12"><code>lang</code></a></td><td>en_us</td><td>(your OS language)</td><td>Enables user's system language by default, for usability, accessibility and discoverability purposes - courtesy of <a href="https://curseforge.com/minecraft/mc-mods/language-reload">Language Reload</a>. Not available for all launchers and operating systems.</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-13"><code>simulationDistance</code></a></td><td>12</td><td>6</td><td>Better performance regardless of the rendering distance you use</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-14"><code>skipMultiplayerWarning</code></a></td><td>false</td><td>true</td><td>I expect my users to already know that the third party servers are not owned or monitored by Mojang Studios or Microsoft.</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-15"><code>telemetryOptInExtra</code></a></td><td>false</td><td>false</td><td>While "minimal" is the default right now anyway, it may not always be the case, hence the enforcement by FO. <a href="telemetry.md">FO disables telemetry</a> anyway, so this is just a fallback.</td></tr><tr><td><a data-footnote-ref href="#user-content-fn-16"><code>tutorialStep</code></a></td><td>movement</td><td>none</td><td>If you know how to install a modpack, you probably don't need those tutorials anymore</td></tr></tbody></table>

[^1]: Enables ["advanced" tooltip info](https://online-tech-tips.com/wp-content/uploads/2021/01/Armor-Tooltips-610x571.png) on items - item ID and durability, and exact color hex code for dyed armor

[^2]: Makes the Mojang Studios splash screen white-on-black instead of white-on-red

[^3]: Toggle [VSync](https://en.wikipedia.org/wiki/Screen_tearing#Vertical_synchronization), a FPS-limiting system

[^4]: Size of the menu and interface elements

[^5]: A list of resource packs that have been forcefully enabled, despite being marked as incompatible

[^6]: Whether to display the hint for [Social Interactions](https://minecraft.wiki/w/Social_Interactions_screen)

[^7]: The maximum framerate

[^8]: Indicates whether the user has not seen the accessibility onboarding screen

[^9]: Shows operator-only items (command blocks, lights, barriers, etc.) in a Creative inventory tab, when you have operator access (`/op`)

[^10]: Adjusts which resource packs are enabled by default

[^11]: `["vanilla","fabric","continuity:glass_pane_culling_fix","continuity:default","file/SodiumTranslations.zip","file/Mod Menu Helper.zip","file/Chat Reporting Helper.zip","file/Fast Better Grass.zip"]`

[^12]: Adjusts the game's language

[^13]: Redstone and mob spawning distance

[^14]: Whether to skip [the legal disclaimer](https://minecraft.wiki/w/File:Multiplayer_disclaimer.png) when opening the multiplayer screen

[^15]: Sets the telemetry (analytics data collection) toggle to "minimal".

[^16]: The next step of [tutorial hints](https://minecraft.wiki/w/Tutorial_hints)
