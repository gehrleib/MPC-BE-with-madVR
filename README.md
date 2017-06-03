# MPC-BE with madVR - Better than VLC

### DOWNLOAD & INSTALL

* [MPC-BE](https://sourceforge.net/projects/mpcbe/files/MPC-BE/Release%20builds/) [[Nightly](http://sourceforge.net/projects/mpcbe/files/MPC-BE/Nightly%20Builds%20%28from%20svn%20trunk%29/)] [[Screenshot](http://i.imgur.com/CMdKukD.png)] - *Media Player with Seekbar preview*
* [LAV Filters](http://github.com/Nevcairiel/LAVFilters/releases) - *Codecs that support most formats and can use your graphics card to decode the video*
* [madVR](http://forum.doom9.org/showthread.php?t=146228) [[Mirror](http://www.videohelp.com/tools/madVR)] - *Video upscaler* 
  * Extract to a folder you won't delete (perhaps madVR folder inside MPC-BE install directory) and run install.bat
* Run the registry files to import optimized settings, this prioritizes which codecs to use etc.

Start **MPC-BE**, press the **O** button on your keyboard to enter **Options**. Select **Formats** from the Tree Menu to the left, then press the **Video** button under Association to associate video files with **MPC-BE** and click the **Apply** button to save settings. ([Screenshot](http://i.imgur.com/nV1Gme7.png))

### HARDWARE ACCELERATION

If you wish to playback video using the graphics card instead of the processor, see this [guide](http://i.imgur.com/ZDgzVJd.png).

* **AMD:** DXVA2 (copy-back)
* **INTEL:** Intel® QuickSync
* **NVIDIA:** NVIDIA CUVID

### TIPS

* Turn off **NVIDIA Share** by following this [guide](http://i.imgur.com/ypmqMeh.png) to avoid stuttering issues.


### HOTKEYS

* **Fullscreen:** F (or Left Mouse Button Double Click)
* **Open File:** Q
* **Go To:** G
* **Cycle Audio / Subtitle:** A / S
* **Display Subtitle:** D
* **Options:** O
* **File Properties:** P
* **Zoom 50% / 100% / 200% / Auto Fit:** 1 / 2 / 3 / 4
* **Exit:** ESC

### UNINSTALL

APPS:

* Run **uninstall.bat** in the folder you unpacked **madVR.zip** and remove its contents
* Uninstall **LAV Filters** and **MPC-BE**

REGISTRY:

* Press **WIN + R** on your keyboard
* Type **regedit** and press **OK**
* Navigate to the following folders, **right-click** on them, and select **Remove**:
  * *HKEY_CURRENT_USER\Software\MPC-BE*
  * *HKEY_CURRENT_USER\Software\LAV*
  * *HKEY_CURRENT_USER\Software\madshi*