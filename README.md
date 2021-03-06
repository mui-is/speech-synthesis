speech-synthesis
================
This [custom element](http://www.html5rocks.com/en/tutorials/webcomponents/customelements/) (made with [polymer](http://www.polymer-project.org/)) enables you to use easily
the [Web Speech API](https://dvcs.w3.org/hg/speech-api/raw-file/tip/speechapi.html) for speech synthesis (text to speech).

## Installation
Simply use [bower](https://www.npmjs.org/package/bower) for that.

Execute following in your project root.
```shell
bower install mui-is/speech-synthesis
```

## Usage
More detailed information will follow. (Bare with me)

One example:
```html
<link href="path/to/speech-synthesis.html" rel="import">
<speech-synthesis id="ss" text="Hi there! How are you today?" autoSpeak="true"></speech-synthesis>
```

#### Events
* onstart
* onend
* onerror
* onpause
* onresume
* onmark
* onboundary

#### Attributes
* voice
* voiceURI
* volume
* rate
* pitch
* lang
* text
* autoSpeak

#### Current status
E.g. `speaking` tells you if it's currently `speaking` but also you can set `speaking = true` it will start reading.
* pending
* speaking
* paused

#### Methods
* speak()
* pause()
* resume()
* cancel()
* getVoices()


## Current browser support
http://caniuse.com/#search=speechSynthesis

## For more information
https://dvcs.w3.org/hg/speech-api/raw-file/tip/speechapi.html#tts-section
http://updates.html5rocks.com/2014/01/Web-apps-that-talk---Introduction-to-the-Speech-Synthesis-API

http://www.polymer-project.org/

## Donations
Please help me to finance my every cup of tea. Every coin is appreciated.

```
Sick of tea? That’s like being sick of *breathing*! - Uncle Iroh
```

[`197EypPopXtDPFK6rEbCw6XDEaxjTKP58S` -- bitcoin](http://en.wikipedia.org/wiki/Bitcoin)

[`jan.guth@gmail.com` -- paypal](https://www.paypal.com/us/webapps/mpp/home)

[Or just `flattr`  me.](https://flattr.com/submit/auto?user_id=jguth&url=https://github.com/fentas)
