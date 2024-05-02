# RadioFieldAR_tinySA-ULTRA

## UPDATE 2024.5.3
- Fixed an issue where it wouldn't work with some language settings.
- Display method can be selected from FOG or sphere
- Added button to save measurement data to file

## Description

You can see the radio strength in AR(Augmented Reality).

This software is using the tinySA-ULTRA as measurement device.

I am grateful to be able to purchase a spectrum analyzer at a reasonable price.

This is free software, please use it at your own risk.

If you are not familiar with tinySA, please refer to the following

https://www.tinysa.org/wiki/

There is the movie introducing this app.

https://youtu.be/J-cCwv5PNz8

![e2](https://user-images.githubusercontent.com/83148498/218468387-55c822a3-e418-4faf-ac73-3389c2c15cbd.png)

## Required environment

![1](https://user-images.githubusercontent.com/83148498/218467041-c7820c92-1248-4685-b66c-b35bec0bfba0.png)

### A android smartphone that supports ARCORE.

You can check this web site.

https://developers.google.com/ar/devices

I confirmed to work this app the following devices.

SONY SOV38

SHARP AQUOS sense6

### tinySA ULTRA

There are two versions of tinySA, Normal and Ultra.

I have used the tinySA Ultra. So I'm not sure if it works with normal tinySA.

But the command seems to be the same on both devices. I think it will work.
  
### OTG USB cable

There are many kinds of things. I have used this one.
  
https://www.amazon.co.jp/gp/product/B08LH1K2HF

### An antenna with printed picture for tracking

Plese use this one. The size should be around 50mm*50mm.

https://nomad-saving.com/wp-content/uploads/2016/03/NASA5-1-768x512.jpg

## How to install

#### Install RadioFieldAR
I'm sorry this app can't be installed from the google play store.

You can install using APK file on this page.

Please refer to these web site for details.

https://www.lifewire.com/install-apk-on-android-4177185

JAPANESE

https://www.teradas.net/archives/6078/

## How to use
First, you start the app. You need to give permission for camera and device.

![permission](https://user-images.githubusercontent.com/83148498/218463506-ff26891c-4e5b-405b-b222-2ced271432e8.png)

After a while, the camera screen will appear.

![start](https://user-images.githubusercontent.com/83148498/218464237-f14fa3cc-c659-4a06-a4ca-34d0c209f5de.png)

It is necessary to aim the camera slowly around the measurement object for the app recognize the surrounding environment.

[important]
ARCore requires visual information from the camera to build an environmental understanding. 
Rapid device movement can cause the camera image to become blurry, reducing ARCore's ability to track and detect features.
During brief periods of movement, ARCore relies on IMU data to estimate the device pose. When movement stops, visual tracking resumes.
Avoid extended periods of rapid movement, which can cause ARCore to lose tracking and prevent detection of features.

https://developers.google.com/ar/develop/runtime

Basically you need to set several setting to tinySA. This app is only getting peek marker data from it.

Measurement speed depends on tinySA settings.

![tinySA](https://user-images.githubusercontent.com/83148498/218465991-3579383c-a6ac-4fd7-9f6b-f363d9a33b1d.png)

The size and grid value can be changed on the app.

![az_recorder_20230213_220722](https://user-images.githubusercontent.com/83148498/218466847-d2b76954-b4ac-4f5b-962f-e7f4a5a82c43.jpg)

The play button is used for start and stop.
The cross mark is for clear the measurement result.

![drawing](https://user-images.githubusercontent.com/83148498/218464841-ea6ea2df-8b84-4449-87ef-0fff30d08487.png)

![button](https://user-images.githubusercontent.com/83148498/218465331-0788177a-1caa-452e-9743-9f0cc0f46654.png)

Let's try it!!
