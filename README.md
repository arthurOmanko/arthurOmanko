﻿# HoneySelect VRmod with LRE & IBL

This mod is for integrating existing VirtualReality HoneySelect mod (VRmod) with Linear Rendering Experiment (LRE) and Image Based Lighting (IBL)
and adding some improvements.
The main way to use this mod have already been referred on the site of existing each mod.
If User wants to know about each mod in detail, please see them.

- VRmod
https://github.com/Eusth/HoneySelectVR
- LRE & IBL
https://joan6694.bitbucket.io/
- IPA
https://github.com/Eusth/IPA


## [Installation]
1. Extract the zip file into your HoneySelect directory.
2. Run (HoneySelect|StudioNEO)_(64|32)_for_VR_with_IBL
3. Enjoy!

**Caution** 
- This mod might rewrite some existing files and cause some bugs depending on User's environment.
  Please back up Game root folder before installing necessarily.
- This mod has no internet connections at all. If User encounters any Firewall problem by this mod, please dont allow any connections.
  The provider does not know why this happens yet.
- This mod will often have heavy loads on memory especially, so User might get freezed or encounter PC crashes on VR execution. 
  In the case, User can decrease the number of post-processing effects or also have no effects (ApplyShaders = false).
  Please be careful to avoid any probelm caused by the case.
- Chara texture will get weird on Title, (enabling/disabling) self shadow, switching (seated/standing) mode, applying shader (as long as known as of now).
  The provider doesnt know about this reason very sorry. If User encounters this problem, initialize scene or chara.
  Until quitting Application , it will not happen twice. 


## [Requirements]
- Game updated with the last patch and DLC installed
- Installed and set up SteamVR
- HSExtSave plugin


## [Mod Settings]
- VRmod:  
  -- ${GameFolder}\vr_settings_for_IBL.xml   --- each VR setting  
  -- ${GameFolder}\vr_for_IBL.log   --- Log on VR execution
- IBL:      
  -- ${GameFolder}\Plugins\HSIBL\Presets_for_VR   --- IBL Preset for VR
- LRE:      
  -- ${GameFolder}\UserData\GraphicSetting\Config_for_VR.xml   --- LRE default for VR


## Modes & Controls

HoneySelectVR comes in two *modes*:

| Mode        | Description         |
| ----------- | ------------------- |
| Seated      | *Default mode.* This mode lets you play the game with a mouse, keyboard, or gamepad.<br />The controls are essentially the same as in the main game. The screen is presented on a big monitor in front of you. |
| Standing    | As soon as tracked controllers are registered by the game, it switches into *standing mode*, also called *room scale mode*. In this mode, you can freely move around and use your Vive or Touch controllers to stuff. |

### Common Mode
On both Seated and Standing Mode, same shortcuts would be used.

#### Keyboard Shortcuts

Keys      | Effect
----      | ------
<kbd>Ctrl</kbd>+<kbd>C</kbd>, <kbd>Ctrl</kbd>+<kbd>C</kbd> | Change to *standing mode*.
<kbd>Ctrl</kbd>+<kbd>C</kbd>, <kbd>Ctrl</kbd>+<kbd>V</kbd> | Enable (very experimental) third person camera. [Was used for this video](https://www.youtube.com/watch?v=0klN6gd1ybM).
<kbd>Alt</kbd>+<kbd>S</kbd> | Save settings (IPD, screen position, etc.).
<kbd>Alt</kbd>+<kbd>L</kbd> | Load settings (last saved state).
<kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>L</kbd> | Reset settings to the initial state.
<kbd>Ctrl</kbd>+<kbd>F5</kbd> | Apply shaders (only for the brave)
<kbd>Alt</kbd>+<kbd>NumPad +</kbd> <br /> <kbd>Alt</kbd>+<kbd>NumPad –</kbd> | Increase / decrease player scale
<kbd>Ctrl</kbd>+<kbd>F12</kbd> | Capture on VR.
<kbd>Ctrl</kbd>+<kbd>Q</kbd> | Toggle fixing of Field of View for Camera (on IBL item). If want full functions of lens on IBL, unfix by toggle. 
<kbd>NumPad +</kbd> <br /> <kbd>NumPad –</kbd> | Move GUI up / down.
<kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>NumPad +</kbd> <br /> <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>NumPad –</kbd> | Move GUI left / right
<kbd>Ctrl</kbd>+<kbd>NumPad +</kbd> <br /> <kbd>Ctrl</kbd>+<kbd>NumPad –</kbd> | Increase / decrease GUI size.
<kbd>Shift</kbd>+<kbd>NumPad +</kbd> <br /> <kbd>Shift</kbd>+<kbd>NumPad –</kbd> | Increase / decrease GUI distance
<kbd>Shift</kbd>+<kbd>Ctrl</kbd>+<kbd>C</kbd> | Most GUI Default texture gets changed from transparent into opaque to improve UI/UX usability 
<kbd>Shift</kbd>+<kbd>UpArrow</kbd> <br /> <kbd>Shift</kbd>+<kbd>DownArrow</kbd> | Increse / decrease the size of Buttons on GUI. (To avoid disapperance of Buttons depending on the resolution of screen)

### Seated Mode

As stated earlier, the controls are basically the same as in the main game with the exception of a few VR-related shortcuts. You are presented with a screen in front of your that replaces your monitor and can be configured via the settings or via shortcuts (see below).

#### Keyboard Shortcuts

Keys      | Effect
----      | ------
<kbd>F4</kbd> | Switch GUI projection mode (flat, curved, spherical).
<kbd>F7</kbd> | Toggle camera lock (enabled by default). This prevents the camera to *tilt* because such movements are known to cause cyber sickness.
<kbd>F12</kbd> | Recenter

### Standing Mode

The *standing mode* is where things start to get interesting. This mode is pretty much disconnected from the usual game in that it comes with its very own controls -- although you can still use your mouse and your keyboard.

#### Keyboard Shortcuts

Keys      | Effect
----      | ------


## Tools

These tools are mainly meant to be used in *standing mode* but some of them are also available in *seated mode*. By default, your left hand will start with the *menu tool* and your right hand will start with the *warp tool*. In order to change them on either hand, press the *menu button* on your Vive controller. [See here an overview of buttons](https://forums.unrealengine.com/attachment.php?attachmentid=87367&d=1460020388).

**You can get in-game help any time by holding the menu button!**

### Menu Tool (seated / standing)

<img src="https://github.com/Eusth/PlayClubVR/raw/master/Manual/menu_tool.png">

With the *menu tool* you can interact with the user interface of the game. There are, in fact, two ways you can control the mouse: a two-handed way that makes use of a laser pointer, and a one-handed way that lets you use your trackpad like a ... touchpad!

#### Laser pointer

<img src="https://github.com/Eusth/PlayClubVR/raw/master/Manual/laser_pointer.jpg">

To use the laser pointer, simply point the *other controller* at the menu screen. A laser pointer will appear and you can easily interact with the UI. To make a click, press the trigger button.

#### Trackpad

To use the trackpad, slide with your thumb over the trackpad and the mouse cursor will move accordingly. To make a click, press the trackpad.

#### Attaching, Detaching and Resizing the Menu

<img src="https://github.com/Eusth/PlayClubVR/raw/master/Manual/scale.jpg">

It's possible to detach and resize the menu you're holding at any point in the game.

Simply press the grip button to "let go" of the menu screen -- the screen will then stay put where you left it. You can even use other tools and still interact with the screen using the *laser pointer* mechanism.

Furthermore, it's possible to *resize* the screen. In order to do that, point both your controllers at a screen, press the trigger button, and move the controllers apart. It's also possible to move the screen around like this.

Lastly, to take control of the screen again, press the grip button once more.

### Warp Tool (standing)

<img src="https://github.com/Eusth/PlayClubVR/raw/master/Manual/warp_tool.png">

The *warp tool* is only available in room scale mode and allows you to jump around in the scene.

#### Warping

In order to warp, touch the trackpad, choose your position and press. While touching the trackpad you are able to see:

1. Where you will warp to
2. Your play area
3. A HMD that further shows where your head will be

You can also *rotate* your play area while touching the trackpad by drawing circles with your thumb.

<img src="https://github.com/Eusth/PlayClubVR/raw/master/Manual/warp.jpg">

#### Changing Scale and Height

It's also possible to change scale and height with this tool, although it's a bit cumbersome at the moment. To do this, hold the trackpad *pressed* before warping. You can now change your future height by moving the Vive controller up and down and your scale by moving back and forth. Note that you can only change one of those two each time.

By pressing the *grip button* you can reset the scale and height.

## Settings & Tweaks

Settings can be changed in the file *vr_settings.xml*, which is generated the first time you start the game. Use `RenderScale` to tweak the resolution, **not** the internal resolution dialog, as that one will currently only change the resolution of the GUI.

Tag      | Default | Effect | Mode
----     | ------  | ------ | ----
`<Distance>` | 0.1 | Sets the distance between the camera and the GUI at `[0,0,0]`. | Seated
`<Angle>` | 170 | Sets the width of the arc the GUI takes up.  | Seated
`<IPDScale>` | 0.83 | Sets the scale of the camera. The higher, the more gigantic the player is. | Seated / Standing
`<OffsetY>` | 0 | Sets the vertical offset of the GUI in meters. | Seated
`<Rotation>` | 0 | Sets by how many degrees the GUI is rotated (around the y / up axis) | Seated
`<Rumble>` | True | Sets whether or not rumble is activated. | Seated / Standing
`<RenderScale>` | 1 | Sets the render scale of the renderer. Increase for better quality but less performance, decrease for more performance but poor quality. | Seated / Standing
`<MirrorScreen>` | False | Sets whether or not the view should be mirrored in the game window. | Seated / Standing
`<ApplyShaders>` | true | Sets whether or not post-processing shaders should automatically be applied to the camera. | Seated / Standing
`<NearClip>` | 0.01 | Within this distance, seen chara gets transparent. | Seated / Standing
`<PitchLock> | false | whether or not can rotate on all axises | Seated


## Building HoneySelectVR

HoneySelectVR depends on the [VRGIN](https://github.com/Eusth/VRGIN) library which is included as a submodule. It is therefore important that when you clone the project, you clone it recursively.

```
git clone --recursive https://github.com/Eusth/HoneySelectVR.git
cd HoneySelectVR
```

After cloning the repo and setting up the submodule, you should be able to compile the project by simply opening the *.sln file and building.

Note that there is a build configuration called "Install" that will extract your Honey Select Trial install directory from the registry and copy the files where they belong. 
