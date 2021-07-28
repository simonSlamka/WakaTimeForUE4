# WakaTimeForUE4

![plugin version](https://img.shields.io/badge/version-1.2.0-blue) ![Unreal Engine version](https://img.shields.io/badge/Unreal%20Engine%20version-4.26-blue) ![Platform support](https://img.shields.io/badge/Platform_support-Windows-blue)

---

### Setting up the plugin
1. Download WakatimeForUE4.zip from the releases
2. Extract the plugin into your editor plugins folder (Commonly C:\Program Files\Epic Games\UE_4.xx\Engine\Plugins)  
   2.1. Your folder structure should be ...\Engine\Plugins\WakaTimeForUE4\
   2.2. Within this folder resides WakaTimeForUE4.uplugin and other files
3. Run the engine
4. If you already used wakatime elsewhere, your api key gets loaded. If not, you get prompted by a window.

### Notice
This is my first ever project in C++, so it is definitely not perfect.  
If you have any suggestions how to improve it, or any bug reports, please, use the "Issues" tab.

### Troubleshooting
Q: **The Wakatime icon in my editor is pink, what is wrong?**  
A: Your plugin folder is most likely named something like `WakaTimeForUE4-1.2.0`. Rename it to just `WakaTimeForUE4` and it will be fine.

Q: **The plugin failed to build.**  
A: Branches other than `release` are development branches, so they might contain code that does not compile. If this happens on the `release` branch (or any version tag), make sure you have all dependencies required for building C++ code. You usually install all of them when installing Visual Studio and checking both C++ and .NET.

Q: **I have regenerated my api key, how do I change it in the editor?**  
A: There is a WakaTime icon in the main toolbar. When you click this icon, you can change the api key. Just remember to hit save!

---
## Contributors
I'd like to thank all of these people for what they did. They helped me to get this plugin to the stage where it is right now.

<a href="https://github.com/ghost">
    <img src="https://github.com/ghost.png" width="64" height="64" alt="ghost" title="A person who helped us solve many warnings regarding macros.">
</a>

<a href="https://github.com/simonSlamka">
    <img src="https://github.com/simonSlamka.png" width="64" height="64" alt="simonSlamka" title="simonSlamka - Helped me and motivated me to finish the version 1.2.0">
</a>

