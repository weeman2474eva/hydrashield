# HYDRA SHIELD

Panel-managed OpenVPN client for Android TV, Fire TV, Android boxes and mobile.

This project is a GPLv2 derivative of [OpenVPN for Android](https://github.com/schwabe/ics-openvpn) by Arne Schwabe. The build workflow checks out the exact upstream source revision and applies the HYDRA SHIELD interface. See `SOURCE_NOTICE.md`.

## Build

Open **Actions**, select **Build HYDRA SHIELD APK**, and run the workflow. The completed universal APK is available as the `HYDRA-SHIELD-APK` artifact.

## Features

- Secure panel URL, username and password login
- Panel-enforced expiry and device limits
- Panel-managed OpenVPN UDP/TCP locations
- Simple remote-friendly Connect workflow
- No IPTV or external launcher functions

The repository must be public before distributing the APK to comply with the GPL source-availability requirement.
