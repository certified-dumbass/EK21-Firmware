EK21Firmware fix
A Windows app for configuring the older EPOMAKER EK21 as a macropad. Assign actions to its keys and switch between profiles for gaming, music, or everyday use.
Features
Feature	What it does
Media controls	Play, pause, or skip to the next or previous track.
Apps and games	Launch a selected app or game with a single key.
Websites	Open a saved URL in your browser.
Power settings	Assign Windows power actions to a key.
Microphone	Control your microphone using the available microphone actions.
Profiles	Save multiple layouts on your PC and switch between them in the app.
Automatic startup	Turn startup at Windows sign-in on or off from the app.


RGB controls are unavailable.
Compatibility
- Windows
- EPOMAKER EK21 with USB ID 320F:5055, VIA protocol 9, and a 4×12 matrix
- A USB connection for configuring the macropad
Check your USB ID before writing a keymap to the device. EK21Firmware fix configures the existing firmware through VIA and requires no firmware flashing.
Getting started
1. Extract the release package to a folder you plan to keep.
2. Connect your EK21 via USB.
3. Launch Control Center using the included Start-EK21-Control-Center.bat file.
4. Choose a profile and assign actions to your keys.
5. Click Save changes. Control Center saves the profile on your PC and can write supported key and media assignments to the EK21. The status message shows whether the changes were also read back from the device.
Starting with Windows
Open the app settings and turn on automatic startup. Windows will launch Control Center through the included batch file when you sign in. Turn the option off to stop future automatic launches.

Keep Control Center running for PC-side actions such as launching apps and games, opening websites, and running Windows power or microphone actions.
What works with Control Center closed?
Standard key assignments, media keys, and the existing volume knob can work directly through the EK21. Control Center backs up the keymap before writing changes and reads it back afterward. Whether a newly written mapping survives a full power cycle on this hardware revision still needs to be verified.
Reporting issues
Open a GitHub issue with your USB ID, Windows version, steps to reproduce the problem, and any error messages
