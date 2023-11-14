<div align="center">

# Local Mirror Detection

[![Generic badge](https://img.shields.io/github/downloads/VRLabs/Local-Mirror-Detection/total?label=Downloads)](https://github.com/VRLabs/Local-Mirror-Detection/releases/latest)
[![Generic badge](https://img.shields.io/badge/License-MIT-informational.svg)](https://github.com/VRLabs/Local-Mirror-Detection/blob/main/LICENSE)
[![Generic badge](https://img.shields.io/badge/Unity-2019.4.31f1-lightblue.svg)](https://unity3d.com/unity/whats-new/2019.4.31)
[![Generic badge](https://img.shields.io/badge/SDK-AvatarSDK3-lightblue.svg)](https://vrchat.com/home/download)

[![Generic badge](https://img.shields.io/discord/706913824607043605?color=%237289da&label=DISCORD&logo=Discord&style=for-the-badge)](https://discord.vrlabs.dev/)
[![Generic badge](https://img.shields.io/endpoint.svg?url=https%3A%2F%2Fshieldsio-patreon.vercel.app%2Fapi%3Fusername%3Dvrlabs%26type%3Dpatrons&style=for-the-badge)](https://patreon.vrlabs.dev/)

Sets an "IsMirror" parameter to true on your mirror clone

![VRChat_2023-10-25_20-51-13 163_3840x2160](https://github.com/VRLabs/Local-Mirror-Detection/assets/76777936/2e9e5f00-6b90-40f6-9c8e-44b7be6dd610)

### ⬇️ [Download Latest Version](https://github.com/VRLabs/Local-Mirror-Detection/releases/latest)

<!-- 
### 📦 [Add to VRChat Creator Companion]() -->

</div>

---

## How it works

* The mirror clone initialized after the local clone by copying the local clone in its current state.
* By changing the value of a parameter before the mirror clone initializes, we can desync the two clones in the FX Controller.

## Install guide

https://github.com/VRLabs/Local-Mirror-Detection/assets/76777936/f225e58d-5863-4e29-ae00-87bf8f4bfde5

* Merge the Animator Controller ``Mirror Detection FX`` to your own FX Controller, using the [Avatars 3.0 Manager](https://github.com/VRLabs/Avatars-3.0-Manager) tool.

## How to use

* The ``IsMirror`` parameter is a float. The value will be 1.0 on the mirror clone and -1.0 on your local clone.
  * You can use this float to play animations for only your mirror clone
  * Note that you can not animate GameObject state and transform on your mirror clone

## Performance stats

```c++
FX Animator Layers: 1
```

## Contributors

[Dreadrith](https://github.com/Dreadrith)

## License

Local Mirror Detection is available as-is under MIT. For more information see [LICENSE](https://github.com/VRLabs/Local-Mirror-Detection/blob/main/LICENSE).

​

<div align="center">

[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/VRLabs.png" width="50" height="50">](https://vrlabs.dev "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Discord.png" width="50" height="50">](https://discord.vrlabs.dev/ "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Patreon.png" width="50" height="50">](https://patreon.vrlabs.dev/ "VRLabs")
<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Empty.png" width="10">
[<img src="https://github.com/VRLabs/Resources/raw/main/Icons/Twitter.png" width="50" height="50">](https://twitter.com/vrlabsdev "VRLabs")

</div>

