<div align="right">Language:
<a title="Английский" href="./README.md">:us:</a>
<a title="Українська" href="./README-ua.md">🇺🇦</a>
<a title="Русский" href="./README-ru.md">:ru:</a>
</div>

# GallerAI: Search your gallery by image contents using arificial intelligence in your Android device!

[Application on Google Play](https://play.google.com/store/apps/details?id=com.algr.gallerai)

**Please report bugs and leave your feedback and ideas here as issues.**

Please read the notes below before filing bugs.

## GallerAI
GallerAI application scans your images for objects and people and allows you to search by image contents in about 1k categories (e.g. 'food', 'animal', 'car', 'bottle', person names etc.).

Application does NOT send any images or your private data to remote servers and does all processing locally on your device.

## Important notes (please read):
Application is quite resource/battery intensive during initial image scan phase.

It might take a couple of hours, depending on images count and CPU performance.

As Android operating system may limit resources for background processes, you need to change few settings for this application, so scan could continue when your device is idle. After scan is completed, you can change these settings back.
To do it, open GallerAI application's android settings and:

- Allow GallerAI application autorun
- Change GallerAI battery consumption policy to unlimited

<img src="https://github.com/grolex18/GallerAI/blob/master/images/settings.png" width="300">

Also connect charger, if battery level is low (scan won't start if battery level is low to avoid full discharge)

## Useful tips:
- Person selector will be available after first scan process will be fully completed.
- By default, search shows images ordered by relevance, but you can sort it by date using button to the right of years filters.
- You can search by multiple terms, separating them by comma (e.g. "Alex,food")
- Search may show only more relevant images if you increase value in "Settings/Confidence threshold"
- Application groups faces depending on "Settings/Face recognition/Face similaroty threshold" setting, so decrease it, if it merges multiple people in single group and increase it, if it splits same person into too many groups.
  Though, you might give them same name, so search returns all of them anyway. This could be useful also when photos in e.g. sunglasses are splitted out.
- You can limit folders that app will scan in your device by changing "Settings/Choose folders to scan"

This is the initial version of my first Android application that turned out to be useful for me, so decided to publish it.

Have fun with it!

And I appreciate all kind of your feedback, bug reports and improvement ideas.

You can also vote for features listed below.

## TODO list:
- Improve search categories and neural net models
- Improve persons clusterization algorithms for better splitting persons
- Search by emotions, age
- Search by text on images
- Search by country/city based on geo location data
- More features in the embedded image viewer
- Themes and colors customization
- *Your feature*

## Credits:
TensorFlow - https://github.com/tensorflow/tensorflow

Facenet - https://github.com/davidsandberg/facenet

Dlib port for Android - for https://github.com/tzutalin/dlib-android

Protostuff - https://github.com/protostuff/protostuff

Glide - https://github.com/bumptech/glide

Fresco - https://github.com/facebook/fresco

FrescoImageViewer - https://github.com/stfalcon-studio/FrescoImageViewer

Better-apk-expansion - https://github.com/bolein/better-apk-expansion

FilePicker - https://github.com/Angads25/android-filepicker
