# Agora Media Source Windows

*其他语言版本： [简体中文](README.zh.md)*

The Agora Media Source Windows Sample App is an open-source demo that will help you get video chat integrated directly into your Windows applications using the Agora Video SDK.

With this sample app, you can:

- Join / leave channel
- Mute / unmute audio
- Enable / disable video
- Change camera
- Send message to channel
- Setup resolution, frame rate and bit rate
- Enable encryption
- Enable / disable black and white filter
- Enable / disable external video & audio stream capturing and audio stream playing

This demo is written in **C++**

A tutorial demo can be found here: [Agora-Windows-Tutorial-1to1](https://github.com/AgoraIO/Agora-Windows-Tutorial-1to1)

Agora Video SDK supports iOS / Android / Windows / macOS etc. You can find demos of these platform here:

- [AgoraVideoSource-Android](https://github.com/AgoraIO/Agora-Video-Source-Android)
- [AgoraVideoSource-iOS](https://github.com/AgoraIO/Agora-Video-Source-iOS)


## Running the App
First, create a developer account at [Agora.io](https://dashboard.agora.io/signin/), and obtain an App ID. define the APP_ID with your App ID.

```
#define APP_ID _T("Your App ID")
```

Next, download the **Agora Video SDK** from [Agora.io SDK](https://www.agora.io/en/blog/download/). Unzip the downloaded SDK package and copy the **sdk** to the "AgoraMediaSource" folder in project(the old one may be over written).

Finally, Open AgoraMediaSource.sln, build the solution and run.

## Developer Environment Requirements
* VC2013 or higher
* WIN7 or higher

## Connect Us

- You can find full API document at [Document Center](https://docs.agora.io/en/)
- You can fire bugs about this demo at [issue](https://github.com/AgoraIO/Agora-Media-Source-Windows/issues)

## License

The MIT License (MIT).
