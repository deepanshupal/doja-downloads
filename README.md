# Downloads

Official downloads for the apps made by [Deepanshu Pal](https://github.com/DeepanshuPal): **Hush**, **Doja** and **Clippy**. All three are free.

This repository only holds release files. Every file is listed below with its SHA-256 checksum, and every release has its notes on the [releases page](https://github.com/DeepanshuPal/downloads/releases).

| App | What it is | Latest | Platforms | Website |
|---|---|---|---|---|
| [**Hush**](#hush) | Push-to-talk dictation. Speech recognition runs on your Mac. Open source (MIT). | 1.1.0 | Mac (Apple silicon) | [hush.software](https://www.hush.software) |
| [**Doja**](#doja) | A tiny pixel cat (and 20 friends) that lives on your Mac's desktop and chats with you. | 1.1.0 | Mac | [doja.pet](https://www.doja.pet) |
| [**Clippy**](#clippy) | The classic paperclip in a Windows 98 window, chatting with an AI model that runs on your computer. | 0.5.0 | Mac, Windows, Linux | [doja.pet/clippy](https://www.doja.pet/clippy) |

## Hush

Hold a key, speak, let go: your words are typed into whatever app you're using.

**Hush 1.1.0** · requires a Mac with Apple silicon (M1 or later) · [release notes](https://github.com/DeepanshuPal/downloads/releases/tag/hush-v1.1.0) · [source code](https://github.com/DeepanshuPal/hush) · [report a problem](https://github.com/DeepanshuPal/hush/issues)

| Platform | File | Size | SHA-256 |
|---|---|---|---|
| Mac (Apple silicon) | [`Hush_1.1.0_aarch64.dmg`](https://github.com/DeepanshuPal/downloads/releases/download/hush-v1.1.0/Hush_1.1.0_aarch64.dmg) | 12.7 MB | `a04a886270ddbca21f4167fdab16e51d2acd1b23d2749804410b6f21476e5855` |

Older versions: [1.0.0](https://github.com/DeepanshuPal/downloads/releases/tag/hush-v1.0.0) · [0.8.0](https://github.com/DeepanshuPal/downloads/releases/tag/hush-v0.8.0) · [0.7.9](https://github.com/DeepanshuPal/downloads/releases/tag/hush-v0.7.9)

<details>
<summary>Speech models (<code>hush-models-v1</code>)</summary>

Hush downloads these by itself when you pick a model in its settings and checks each file against its SHA-256. You don't need to download them by hand.

| File | Size | SHA-256 |
|---|---|---|
| [`breeze-asr-q5_k.bin`](https://github.com/DeepanshuPal/downloads/releases/download/hush-models-v1/breeze-asr-q5_k.bin) | 1.01 GB | `8efbf0ce8a3f50fe332b7617da787fb81354b358c288b008d3bdef8359df64c6` |
| [`ggml-large-v3-q5_0.bin`](https://github.com/DeepanshuPal/downloads/releases/download/hush-models-v1/ggml-large-v3-q5_0.bin) | 1.01 GB | `d75795ecff3f83b5faa89d1900604ad8c780abd5739fae406de19f23ecd98ad1` |
| [`ggml-large-v3-turbo.bin`](https://github.com/DeepanshuPal/downloads/releases/download/hush-models-v1/ggml-large-v3-turbo.bin) | 1.51 GB | `1fc70f774d38eb169993ac391eea357ef47c88757ef72ee5943879b7e8e2bc69` |
| [`ggml-small.bin`](https://github.com/DeepanshuPal/downloads/releases/download/hush-models-v1/ggml-small.bin) | 465 MB | `1be3a9b2063867b937e64e2ec7483364a79917e157fa98c5d94b5c1fffea987b` |
| [`giga-am-v3.int8.onnx`](https://github.com/DeepanshuPal/downloads/releases/download/hush-models-v1/giga-am-v3.int8.onnx) | 214 MB | `2e3fcb7a7b66030336fd10c2fcfb033bd1dc7e1bf238fe5cfd83b1d0cfc9d28e` |
| [`moonshine-base.tar.gz`](https://github.com/DeepanshuPal/downloads/releases/download/hush-models-v1/moonshine-base.tar.gz) | 55.2 MB | `04bf6ab012cfceebd4ac7cf88c1b31d027bbdd3cd704649b692e2e935236b7e8` |
| [`moonshine-medium-streaming-en.tar.gz`](https://github.com/DeepanshuPal/downloads/releases/download/hush-models-v1/moonshine-medium-streaming-en.tar.gz) | 192 MB | `07a66f3bff1c77e75a2f637e5a263928a08baae3c29c4c053fc968a9a9373d13` |
| [`moonshine-small-streaming-en.tar.gz`](https://github.com/DeepanshuPal/downloads/releases/download/hush-models-v1/moonshine-small-streaming-en.tar.gz) | 100 MB | `dbb3e1c1832bd88a4ac712f7449a136cc2c9a18c5fe33a12ed1b7cb1cfe9cdd5` |
| [`moonshine-tiny-streaming-en.tar.gz`](https://github.com/DeepanshuPal/downloads/releases/download/hush-models-v1/moonshine-tiny-streaming-en.tar.gz) | 31.5 MB | `465addcfca9e86117415677dfdc98b21edc53537210333a3ecdb58509a80abaf` |
| [`parakeet-v2-int8.tar.gz`](https://github.com/DeepanshuPal/downloads/releases/download/hush-models-v1/parakeet-v2-int8.tar.gz) | 451 MB | `ac9b9429984dd565b25097337a887bb7f0f8ac393573661c651f0e7d31563991` |
| [`parakeet-v3-int8.tar.gz`](https://github.com/DeepanshuPal/downloads/releases/download/hush-models-v1/parakeet-v3-int8.tar.gz) | 456 MB | `43d37191602727524a7d8c6da0eef11c4ba24320f5b4730f1a2497befc2efa77` |
| [`sense-voice-int8.tar.gz`](https://github.com/DeepanshuPal/downloads/releases/download/hush-models-v1/sense-voice-int8.tar.gz) | 153 MB | `171d611fe5d353a50bbb741b6f3ef42559b1565685684e9aa888ef563ba3e8a4` |
| [`whisper-medium-q4_1.bin`](https://github.com/DeepanshuPal/downloads/releases/download/hush-models-v1/whisper-medium-q4_1.bin) | 469 MB | `79283fc1f9fe12ca3248543fbd54b73292164d8df5a16e095e2bceeaaabddf57` |

</details>

## Doja

Doja walks along the bottom of your screen and on top of your windows, naps, waves, and chats with you using AI that runs on your Mac. Focus timer, gentle reminders, no account.

**Doja 1.1.0** · requires macOS 13.3 or later (Apple silicon or Intel) · [release notes](https://github.com/DeepanshuPal/downloads/releases/tag/doja-v1.1.0) · [doja.pet](https://www.doja.pet)

| Platform | File | Size | SHA-256 |
|---|---|---|---|
| Mac | [`Doja-1.1.0.dmg`](https://github.com/DeepanshuPal/downloads/releases/download/doja-v1.1.0/Doja-1.1.0.dmg) | 11.1 MB | `c11f6061fd11c99e63f5eea2c210ee32dcccc6728dd0527b0ae13f0879a71532` |

## Clippy

The classic Office assistant on your desktop, chatting with a local AI model you download in one click, or your own API key. A fan-made app, not affiliated with, approved by or supported by Microsoft.

**Clippy 0.5.0** · Mac, Windows (x64) and Linux (x64) · [release notes](https://github.com/DeepanshuPal/downloads/releases/tag/clippy-v0.5.0) · [doja.pet/clippy](https://www.doja.pet/clippy)

| Platform | File | Size | SHA-256 |
|---|---|---|---|
| Mac (Apple silicon) | [`Clippy-darwin-arm64-0.5.0.zip`](https://github.com/DeepanshuPal/downloads/releases/download/clippy-v0.5.0/Clippy-darwin-arm64-0.5.0.zip) | 142 MB | `56c198018cec52ccfe0198232103e9396b724b63795a6f98f4206bfaccba99de` |
| Mac (Intel), version 0.4.4 | [`Clippy-darwin-x64-0.4.4.zip`](https://github.com/DeepanshuPal/downloads/releases/download/clippy-v0.4.4/Clippy-darwin-x64-0.4.4.zip) | 138 MB | `e2ed71bfa2841301fe62958793178bb39f58cdb4ae7fec2d2850851e2413f7e0` |
| Windows installer | [`Clippy-0.5.0-setup-x64.exe`](https://github.com/DeepanshuPal/downloads/releases/download/clippy-v0.5.0/Clippy-0.5.0-setup-x64.exe) | 311 MB | `ef268626791f145c6212353a21cda1b15f8f7a4e5bceb4378b1d87c88f1749cc` |
| Windows (zip) | [`Clippy-win32-x64-0.5.0.zip`](https://github.com/DeepanshuPal/downloads/releases/download/clippy-v0.5.0/Clippy-win32-x64-0.5.0.zip) | 317 MB | `1bdc2e8fe34f47caa106022d212de1da1e41fced25b68a8b72a01278648a3b90` |
| Linux (.deb) | [`clippy_0.5.0_amd64.deb`](https://github.com/DeepanshuPal/downloads/releases/download/clippy-v0.5.0/clippy_0.5.0_amd64.deb) | 255 MB | `6beffc5854815e172b82b94dfe411223714a95d426e3f07b2b76489c210e1d81` |
| Linux (.rpm) | [`Clippy-0.5.0-1.x86_64.rpm`](https://github.com/DeepanshuPal/downloads/releases/download/clippy-v0.5.0/Clippy-0.5.0-1.x86_64.rpm) | 265 MB | `fd79b1c7ab245cff1d59a775309c4ec692531141b5a6f0a616d015dbf7737aa0` |

There is no 0.5.0 build for Intel Macs yet; 0.4.4 is the newest one. Older versions: [0.4.4](https://github.com/DeepanshuPal/downloads/releases/tag/clippy-v0.4.4) · [0.4.3](https://github.com/DeepanshuPal/downloads/releases/tag/clippy-v0.4.3)

## Opening an app for the first time

The apps aren't signed with paid Apple or Microsoft certificates, so your computer asks you to confirm once.

- **Mac:** open the DMG or zip and move the app to **Applications**. Open it once; when macOS says it can't be opened, click **Done**, go to **System Settings → Privacy & Security**, scroll down and click **Open Anyway**. Hush also asks for Microphone and Accessibility access during setup. If you update Hush and it waits for permission, remove it under **Accessibility** and add it again.
- **Windows:** if SmartScreen shows "Windows protected your PC", click **More info → Run anyway**.
- **Linux:** install with `sudo apt install ./clippy_0.5.0_amd64.deb` or `sudo dnf install ./Clippy-0.5.0-1.x86_64.rpm`.

## Check your download

Compare the file's SHA-256 with the one in the tables above (GitHub also shows it next to each file on the release page). If they don't match, delete the file and download it again from here.

```sh
# Mac and Linux
shasum -a 256 Hush_1.1.0_aarch64.dmg
```

```powershell
# Windows
Get-FileHash .\Clippy-0.5.0-setup-x64.exe -Algorithm SHA256
```

Only download these apps from this repository or their websites. None of them asks for payment, a licence key or an account.

## How releases are tagged

Each app has its own tag prefix, so one repository can hold all of them:

| Tag | What it is |
|---|---|
| `hush-vX.Y.Z` | Hush app |
| `hush-models-vN` | Speech-model files the Hush app downloads |
| `doja-vX.Y.Z` | Doja for Mac |
| `clippy-vX.Y.Z` | Clippy |

GitHub labels one release "Latest", but here that label doesn't mean the newest version of any particular app. Use the tables above or each app's website. `v1.1.0` is an older name for Doja 1.1.0, kept so existing links keep working.

This repository was called `doja-downloads`; old links redirect here. Hush releases up to 1.1.0 were first published in [hush-downloads](https://github.com/DeepanshuPal/hush-downloads) and Clippy releases up to 0.5.0 in [clippy-downloads](https://github.com/DeepanshuPal/clippy-downloads). Both are archived and stay online, because installed copies of the apps still read them.
