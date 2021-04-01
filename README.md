<h1 align="center">UnityUIPlayables</h1>

A set of tracks and clips for controlling the Unity UI (uGUI) with Timeline.

<p align="center">
  <img width=700 src="https://user-images.githubusercontent.com/47441314/113313016-cf9afe80-9345-11eb-9aa9-422c53b5a3f8.gif" alt="Demo">
</p>

## Features

#### Control Unity UI (uGUI)
Unity UI Playables allows you to control any uGUI components and its parameters with Timeline.

<p align="center">
  <img width=700 src="https://user-images.githubusercontent.com/47441314/113312392-34098e00-9345-11eb-9ec4-614caffe09a0.png" alt="Control Unity UI">
</p>

#### Easings and Animation Curve
You can easily set up animations using the easing function.  
If you want to create complex animations, you can also use Animation Curves.

<p align="center">
  <img width=500 src="https://user-images.githubusercontent.com/47441314/113312417-3a980580-9345-11eb-815b-96baf0f10189.png" alt="Easings and Animation Curve">
</p>

#### Blending
All clips and all parameters are blendable.

<p align="center">
  <img width=700 src="https://user-images.githubusercontent.com/47441314/113312482-4c79a880-9345-11eb-8e19-c6c85d2e1338.png" alt="Blending">
</p>

## Usage

#### Install
Open Packages/manifest.json and add the following to the dependencies block.

```json
{
    "dependencies": {
        "com.harumak.unityuiplayables": "https://github.com/Haruma-K/UnityUIPlayables.git?path=/Assets/UnityUIPlayables"
    }
}
```

#### Create Tracks and Clips
Press the add track button in Timeline and select the track below UnityUIPlayables.

<p align="center">
  <img width=500 src="https://user-images.githubusercontent.com/47441314/113312977-c6aa2d00-9345-11eb-99f5-cd46b718c708.png" alt="Create Tracks and Clips">
</p>

Next, add the corresponding clip to the track.  
The parameters can be controlled from the clip's inspector.

## Controllable Parameters
|Component Name|Parameter Name|
|-|-|
|<b>RectTransform</b>|Anchored Position<br>Size Delta<br>Local Rotation<br>Local Scale|
|<b>Graphic</b>|Color|
|<b>Image</b>|Color<br>Fill Amount|
|<b>RawImage</b>|Color<br>UV Rect|
|<b>Text</b>|Color<br>Font Size<br>Line Spacing|
|<b>Text (Text Mesh Pro)</b>|Font Size<br>Color<br>Gradient (Top Left / Top Right / Bottom Left / Bottom Right)<br>Spacing (Character / Line / Word / Paragraph)<br>Face Color (Only at Runtime)<br>Outline Color (Only at Runtime)<br>Outline Width (Only at Runtime)|
|<b>Slider</b>|Value|
|<b>Canvas Group</b>|Alpha|