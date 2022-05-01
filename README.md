# Local Mirror Detection
  
[![Generic badge](https://img.shields.io/badge/Unity-2019.4.31f1-informational.svg)](https://unity3d.com/unity/whats-new/2019.4.31)
[![Generic badge](https://img.shields.io/badge/SDK-AvatarSDK3-informational.svg)](https://vrchat.com/home/download)
[![Generic badge](https://img.shields.io/badge/License-MIT-informational.svg)](https://github.com/VRLabs/Local-Mirror-Detection/blob/main/LICENSE)
[![Generic badge](https://img.shields.io/github/downloads/VRLabs/Local-Mirror-Detection/total?label=Downloads)](https://github.com/VRLabs/Local-Mirror-Detection/releases/latest)

Set an "IsMirror" parameter to animate conditionally with the local mirror.

## How it works

The mirror-copy FX layer initializes after the host avatar's FX layer, which can be exploited to set a parameter value for each side.

## Install guide

Merge the FX controller to your own FX controller, using the [Avatars 3.0 Manager](https://github.com/VRLabs/Avatars-3.0-Manager) tool.

## How to use

The "IsMirror" parameter is a float. The value will be 1.0 inside the local mirror, and -1.0 outside of it.

## Credit

[Dreadrith](https://github.com/Dreadrith)

## Downloads

You can grab the latest version of Local Mirror Detection in [Releases](https://github.com/VRLabs/Local-Mirror-Detection/releases/latest).

## License

Local Mirror Detection is available as-is under MIT. For more information see [LICENSE](https://github.com/VRLabs/Local-Mirror-Detection/blob/main/LICENSE).

## Contact us

If you need help, our support channel is on [Discord](https://discord.vrlabs.dev).
