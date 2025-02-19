# OBS Assets

This directory houses assets needed for streaming when using [**OBS**](https://obsproject.com/). For guides and helpful tips and tricks, please refer to the [documentation](https://github.com/cloud-platforms-streaming/docs).

## HOWTO install assets so they "just work"

In an attempt to make this as simple as possible, we have built this OBS Scene to be compliant with Mac and Linux. We've tried to make the installation process just as simple. However, we now have a number of different sets of assets. The following is a template installation for the main OpenShift Streaming Scene Collection.

1. Clone this repo into `/opt`
1. In OBS remove any existing **OpenShift Streaming** Scenes from the Scene Collection menu  
(NOTE: you won't do this the first time. Also, if you don't do this OBS will probably crash. Sadly, OBS doesn't automatically pick up Scene changes)
1. In OBS, select Scene Collection -> Import, use the path to the OBS scene `/opt/streaming-tools/obs/openshift_streaming/basic/scenes/OpenShift_Streaming.json`, and click Add.

![Import the OpenShift Streaming Scene](../img/scene-import.png)

Now, repeat the above steps for any other shows you may need to produce, for example "OpenShift Commons" -> "openshift_commons" and "In the Clouds" -> "in_the_clouds".

## What's in the Scene

TODO: Describe Scene and HOWTO use it effectively; sound settings are going to be tough

### Breaks, in stream commercials, etc.

Breaks are often a thing in longer live streams. The a psychological theory that 50 minutes of instruction followed by a ten minute break is a solid way to provide instruction in immersive environments. Twitch is not a fully immersive environment, but breaks are often expected during longer Twitch streams

There is a "[Be Right Back](obs/assets/OpenShift_Twitch_BRB.mp4)" animation for use here if you want to take a break, change the OBS scene to Break.

#### Commercials

Yes, we can run Twitch commercials.
Don't get distracted by those.