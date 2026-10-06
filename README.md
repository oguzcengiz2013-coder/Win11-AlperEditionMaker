# Win11-AlperEditionMaker

Win11-AlperEditionMaker is a tool for creating customized Windows 11 installation ISOs from your own Windows 11 installation media.

It automates common ISO customization tasks and makes it easier to build a personalized Windows 11 installer without manually editing every file.

## Download

Release packages are distributed with names such as:

`Win11-AlperEdition-v1.zip`

Extract the ZIP before running the Maker.

## Features

- Modify a Windows 11 ISO automatically
- Add custom files and folders
- Add `$OEM$` content
- Add SetupComplete and first-logon scripts
- Apply registry tweaks
- Add themes, wallpapers, icons, and other customizations
- Support for manually provided drivers
- Optional Windows 11 hardware requirement compatibility tweaks
- Rebuild the modified installation media into a new ISO

## Requirements

- Windows 11
- Administrator privileges
- A legitimate Windows 11 ISO
- Enough free disk space for extracting and rebuilding the ISO

## Usage

1. Download the latest `Win11-AlperEdition-v*.zip` release.
2. Extract the ZIP to a folder.
3. Obtain a legitimate Windows 11 ISO.
4. Run Win11-AlperEditionMaker as Administrator.
5. Select or provide your Windows 11 ISO.
6. Configure the desired modifications.
7. Build the customized ISO.

## Driver Support

Drivers are **not bundled** with Win11-AlperEditionMaker.

If you want to include additional drivers, manually place the required driver files in the appropriate driver folder before building the ISO.

If you do not need custom drivers, you can leave the driver folder unchanged.

## Unsupported Hardware

Win11-AlperEditionMaker may include optional registry and Setup compatibility tweaks intended for installing Windows 11 on unsupported hardware.

These tweaks may affect checks such as:

- TPM
- Secure Boot
- CPU compatibility

These tweaks do **not** bypass Windows activation or licensing.

Installing Windows 11 on unsupported hardware may result in compatibility issues or differences in support and update availability.

## Notes

- Behavior may vary between different Windows 11 builds.
- Some customization options may behave differently depending on the source ISO.
- Testing the generated ISO in a virtual machine before installing it on important hardware is recommended.
- Always keep a backup of your original Windows 11 ISO.

## Important

This repository and its release ZIP files do **not** include or distribute Microsoft Windows or Windows installation media.

They do not include:

- Windows ISO files
- `install.wim`
- `boot.wim`
- Windows product keys
- Activation tools
- KMS tools
- Cracks
- Activation bypasses
- Pre-activated Windows installations

Users must provide their own legitimate Windows 11 installation media.

## Disclaimer

Win11-AlperEditionMaker is an independent project and is not affiliated with, sponsored by, or endorsed by Microsoft Corporation.

Microsoft, Windows, and Windows 11 are trademarks of Microsoft Corporation.

Users are responsible for ensuring that their use of Windows and any third-party files complies with the applicable licenses and terms.

## License

The license included with this repository applies only to the original Win11-AlperEditionMaker code and files.

It does not grant any rights to Microsoft Windows or other third-party software.
