* PhillHogland: WIXBUG:4592 - Register named process, in another user's context with Restart Manager.  If Access Denied, continue install rather than fail.

* BobArnson: **BREAKING CHANGE** Changed bundle version to Major.Minor.0.BuildNumber. This allows us to publish updates as Major.Minor.(GreaterThanZero).BuildNumber. MSI product version numbers remain Major.Minor.BuildNumber so major upgrades continue to work. This bundle will not upgrade from build v3.10.1124.0. If you've installed v3.10.1124.0, you must uninstall before installing a later bundle.

* BMurri: WIXBUG:3750 - Add LaunchWorkingFolder to wixstdba to facilitate processes that require a different working folder.

* SeanHall: WIXBUG:4609 - Fix incorrect use of BVariantCopy by creating the new method BVariantSetValue.

* SeanHall: WIXBUG:4608 - Fix bug in mbapreq where it wouldn't reload the bootstrapper if there was a mix of installed and uninstalled prerequisites.

## WixBuild: Version 3.10.1124.0

* SeanHall: WIXBUG:4598 - Fix thmutil documentation.  Also backport some thmutil features/fixes from wix4.

* BobArnson: WIXBUG:4580 - Check bit mask appropriately for Burn system variables.

* SamuelS: WIXFEAT:4543 - Allow Pyro to exclude empty patch transforms.

* HeathS: WIXBUG:4542 - Pad package sequence number log file names for proper sorting

* HeathS: Add logging for hash verification and registration issues.

* HeathS: Redefine Exit\* macros as variadic macros

* SeanHall: WIXFEAT:4505 - WixHttpExtension for URL reservations.

* BobArnson: WIXBUG:4569 - Add SWAPRUN for CD(!) and NET back to the Burn stub.

* BobArnson: Add support for registering Votive into Visual Studio 2015 Preview.

* BobArnson: WiX v3.10

## WixBuild: Version 3.10.0.0
