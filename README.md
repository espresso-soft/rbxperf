<h1 align="center"><img src="https://raw.githubusercontent.com/pizzaboxer/bloxstrap/main/Bloxstrap/Resources/Icon2022.ico" width="24" alt="Roblox"> FastFlags Presets <img src="https://raw.githubusercontent.com/pizzaboxer/bloxstrap/main/Images/Bloxstrap.png" width="24" alt="Bloxstrap"> </h1>

> [!CAUTION]
> FastFlags are extremely powerful, being that they are intended to only be used by Roblox engineers. While they can be very useful, they can cause issues with stability and functionality if you don't know what you're doing.

#### Version: `2.0.0` `[UPDATE]`
* **V2 Release**
* **Submit an issue if you need help!**
* **Want to add your preset? Fork and make a PR!**

## Bloxstrap How to Use:
1. **Open the [Bloxstrap Menu](https://github.com/pizzaboxer/bloxstrap).**
2. **Navigate to `Fast Flags` >> `Fast Flags Editor` >> `Add New` >>  `Import Json`.**
3. **Paste in the JSON.**
4. **Save and your good to go!**

<img src="/assets/tutorial260.gif" width="750"/>

## Normal Roblox Bootstrapper  How to Use:
###### You can also do Roblox Studio
1. **Navigate to your Roblox Installation directory. Typically found at `%localappdata%\Roblox\Versions\` or `C:\Program Files (x86)\Roblox\Versions`.**
2. **Identify the folder `version-xxxxxxxxxxxxxxxx` ~~containing `RobloxPlayerBeta.exe`~~ You can do this for Roblox Studio too.**
3. **Create a new folder named `ClientSettings`. Inside this folder, place the file `ClientAppSettings.json`.**
4. **Paste the JSON into `ClientAppSettings.json`. (You can utilize ChatGPT to format multiple JSONs for clarity if needed)**
5. **Save and you're good to go!**
###### Do note that after roblox updates you have to do this process again

[Watch a Video Tutorial](https://streamable.com/rk5an6)

<h1 align="center">RBXPERF Presets</h1>

<h4 align="center"><a href="https://github.com/collectivists/rbxflags">View Full List</a><h3>

### V1
###### Very low quality for performance
```json
{
    "FFlagTaskSchedulerLimitTargetFpsTo2402": "False",
    "DFIntTaskSchedulerTargetFps": "9999",
    "FFlagDebugRenderingSetDeterministic": "True",
    "DFFlagDebugRenderForceTechnologyVoxel": "True",
    "FIntRenderShadowIntensity": "0",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
    "DFFlagDisableDPIScale": "True",
    "DFIntDebugFRMQualityLevelOverride": "1",
    "FFlagCommitToGraphicsQualityFix": "True",
    "FFlagFixGraphicsQuality": "True",
    "FFlagGlobalWindRendering": "False",
    "FIntRenderLocalLightUpdatesMax": "8",
    "FIntRenderLocalLightUpdatesMin": "6",
    "FIntRenderLocalLightFadeInMs": "-1",
    "FFlagDisablePostFx": "True",
    "DFFlagDebugPauseVoxelizer": "True",
    "FFlagDebugSkyGray": "True",
    "FFlagFastGPULightCulling3": "True",
    "DFIntMaxFrameBufferSize": "4",
    "FIntTerrainArraySliceSize": "4",
    "DFIntTextureCompositorActiveJobs": "0",
    "FIntDebugTextureManagerSkipMips": "8",
    "FIntFRMMinGrassDistance": "0",
    "FIntFRMMaxGrassDistance": "0",
    "FIntRenderGrassDetailStrands": "0",
    "FIntRenderGrassHeightScaler": "0",
    "FIntRenderShadowmapBias": "-1",
    "FFlagAdServiceEnabled": "False",
    "DFIntAnimationLodFacsDistanceMin": "0",
    "DFIntAnimationLodFacsDistanceMax": "0",
    "DFIntAnimationLodFacsVisibilityDenominator": "0",
    "FFlagEnableInGameMenuChromeABTest2": "False",
    "FFlagEnableReportAbuseMenuRoactABTest2": "False",
    "FFlagEnableInGameMenuChromeABTest3": "False",
    "FFlagUserShowGuiHideToggles": "True",
    "GuiHidingApiSupport2": "True",
    "FIntFullscreenTitleBarTriggerDelayMillis": "3600000"
}
```
### V2
```json
{
    "FFlagTaskSchedulerLimitTargetFpsTo2402": "False",
    "DFIntTaskSchedulerTargetFps": "9999",
    "FFlagRenderFixFog": "True",
    "FFlagDebugCheckRenderThreading": "True",
    "FFlagRenderDebugCheckThreading2": "True",
    "FIntRenderShadowIntensity": "0",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
    "DFFlagDisableDPIScale": "True",
    "FFlagCommitToGraphicsQualityFix": "True",
    "FFlagFixGraphicsQuality": "True",
    "FIntRenderLocalLightUpdatesMax": "6",
    "FIntRenderLocalLightUpdatesMin": "4",
    "FIntRenderLocalLightFadeInMs": "0",
    "FFlagDisablePostFx": "True",
    "FFlagNewLightAttenuation": "True",
    "FFlagDebugForceFSMCPULightCulling": "True",
    "DFIntMaxFrameBufferSize": "6",
    "DFFlagTextureQualityOverrideEnabled": "True",
    "DFIntTextureQualityOverride": "3",
    "FIntFRMMinGrassDistance": "0",
    "FIntFRMMaxGrassDistance": "0",
    "FIntRenderGrassDetailStrands": "0",
    "FIntDebugForceMSAASamples": "0",
    "FFlagGameBasicSettingsFramerateCap5": "False",
    "FFlagUserShowGuiHideToggles": "True",
    "FFlagGuiHidingApiSupport2": "True",
    "FIntFullscreenTitleBarTriggerDelayMillis": "3600000",
    "DFIntTimestepArbiterThresholdCFLThou": "300",
    "FFlagAdServiceEnabled": "False",
    "FFlagDebugDisableTelemetryEphemeralCounter": "True",
    "FFlagDebugDisableTelemetryEphemeralStat": "True",
    "FFlagDebugDisableTelemetryEventIngest": "True",
    "FFlagDebugDisableTelemetryPoint": "True",
    "FFlagDebugDisableTelemetryV2Counter": "True",
    "FFlagDebugDisableTelemetryV2Event": "True",
    "FFlagDebugDisableTelemetryV2Stat": "True",
    "DFIntDefaultTimeoutTimeMs": "10000",
    "FFlagEnableQuickGameLaunch": "True",
    "DFIntAnimationLodFacsDistanceMin": "0",
    "DFIntAnimationLodFacsDistanceMax": "0",
    "DFIntAnimationLodFacsVisibilityDenominator": "0",
    "FFlagHandleAltEnterFullscreenManually": "False",
    "FIntRobloxGuiBlurIntensity": "0",
    "FFlagErrorPromptResizesHeight": "False",
    "FFlagNewCameraControls": "True",
    "DFIntS2PhysicsSenderRate": "10000"
}
```

#### I don't see a difference between these two, Please don't blindly paste Fast Flags that you don't know what they do & Don't buy those "FPS" & "PING" flags.

##### (V1 First SS V2 Second SS)

![image](https://github.com/user-attachments/assets/2a3c90fd-92fc-4231-948f-59559ecdc2e9)
![image](https://github.com/user-attachments/assets/8aea5195-fe3a-4b5e-bb06-8fe1839d2860)

<h1 align="center">Community Presets</h1>

<h4 align="center">We are not accepting performance presets with FastFlags doesn't do anything</h4>

### absolutely kill your game quality with fflags known to me
##### @dynamitebumblemouth
<a href="https://discord.com/users/833240476311486495"> <img src="https://cdn.prod.website-files.com/6257adef93867e50d84d30e2/636e0b5493894cf60b300587_full_logo_white_RGB.svg" width="86">
```json
{
    "FFlagDisablePostFx": "True",
    "FIntDebugTextureManagerSkipMips": "-1",
    "DFIntTextureCompositorActiveJobs": "0",
    "DFIntCSGLevelOfDetailSwitchingDistance": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL12": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL23": "0",
    "DFIntCSGLevelOfDetailSwitchingDistanceL34": "0",
    "DFIntDebugFRMQualityLevelOverride": "1",
    "DFFlagDebugPauseVoxelizer": "True",
    "DFFlagDebugRenderForceTechnologyVoxel": "True",
    "FIntRenderShadowIntensity": "0",
    "FIntRenderShadowmapBias": "1",
    "FIntDebugForceMSAASamples": "-1",
    "FIntFRMMinGrassDistance": "0",
    "DFIntTextureQualityOverride": "1"
}
```

<h1 align="center">Links</h1>

### [Bloxstrap](https://github.com/pizzaboxer/bloxstrap) [Github Repo Link]

<h3 align="center">
  <a href="https://open.spotify.com/track/0ypjMI7vHiDP4sLB1C0Qna">
    <img src="https://i.scdn.co/image/ab67616d0000b273e97df2756c243d8f81cbb0f8" width="256" alt="Listen on Spotify">
  </a>
</h3>

<h3 align="center">Talk - Yeat</h3>

<h1 align="center">
  <a href="https://open.spotify.com/track/0ypjMI7vHiDP4sLB1C0Qna">
    <img src="https://upload.wikimedia.org/wikipedia/commons/2/26/Spotify_logo_with_text.svg" width="100">
  </a>
</h1>

<h4 align="center"><a href="https://discord.gg/nKjV3mGq6R">Bloxstrap</a></h4>

<h4 align="center">COLLECTIVISTS 2024®<sup>eal</sup></h4>

<p align="center"><a href="https://raw.githubusercontent.com/MaximumADHD/Roblox-Client-Tracker/roblox/FVariables.txt">FVariables.txt</a></p>

<p align="center"><a href="https://github.com/MaximumADHD/Roblox-FFlag-Tracker">Roblox FFlag Tracker</a></p>
