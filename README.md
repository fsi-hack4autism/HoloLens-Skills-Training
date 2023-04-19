# HoloLens-Skills-Training

## Virtual Machine setup
 * Make sure the machine installed is Windows 10
 * Download and install Visual Studio 2022 with "Game Development with Unity" module

## Dev environment setup

### Setup Unity Hub
 * Configure your Visual Studio environment by installing the following modules while installing Visual Studio
   * "Game Development with Unity"
   * "UWP Development" - make sure all C++ modules and Windows SDK modules (11 and 10) are selected
 * Once installed, launch Unity Hub from a nenwly created desktop icon
 * Make sure you have the latest version (v3.4.2)
 * On relaunching, you will get prompted for installing Unity Editor - go ahead and install it (this might take up to 3 hours)

### Creating Unity Hub project
 * On launching after the install
 * If Universal Windows Platform is nto installed, you will need to install it
   * Launch Unity Hub, open File -> Build Settings -> UWP. This will prompt you to install UWP. Note, you may have to restart Unity to see corretion options
 * Reference - https://learn.microsoft.com/en-us/training/modules/learn-mrtk-tutorials/1-3-exercise-configure-unity-for-windows-mixed-reality
 
## Install Windows SDK
 * Download and install from https://developer.microsoft.com/en-us/windows/downloads/windows-sdk/
 * Ensure that UWP modules are selected while installing

### Import the MRTK Unity foundation package
 * Reference - https://learn.microsoft.com/en-us/training/modules/learn-mrtk-tutorials/1-5-exercise-configure-resources?tabs=openxr
 
## References
 * https://learn.microsoft.com/en-us/windows/mixed-reality/develop/unity/unity-development-overview