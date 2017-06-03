# Ti.VoiceRecorderVisualizer

This is  an Axway Titanium module for realizing of an audio recorder visualizer. It expose the [Visualizer](https://github.com/tyorikan/voice-recording-visualizer) of [Takayuki Yorikane](Takayuki Yorikane) 


## Constants

- [x] RENDERTYPE_BAR
- [x] RENDERTYPE_FADE
- [x] RENDERTYPE_PIXEL
- [x] RENDERRANGE_TOP
- [x] RENDERRANGE_BOTTOM
- [x] RENDERRANGE_BOTH

## Permissions
This module needs AUDIO_RECORDING permissions. You need runtime permissions in devices ≧ Marshmellow!! 

## Usage

```javascript

var Visualizer = require("ti.voicerecordervisualizer")
var RenderView = Visualizer.createRenderView({
	color : "red",
	range : Visualizer.RENDERANGE_BOTTOM,
	types : [Visualizer.RENDERTYPE_BAR,Visualizer.RENDERTYPE_FADE],
	columns : 10
})
RenderView.start();

```


