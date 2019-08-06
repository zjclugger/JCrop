# JCrop - Image Cropping Library for Android

This project is base on project uCrop. The url is https://github.com/Yalantis/uCrop

# Changelog
### Version：2.2.3
Added some code for PictureSelector (https://github.com/LuckSiege/PictureSelector) base on uCrop version 2.2.3
It will be referenced in Project PictureSelector.

### Version: 2.2.3

  * Several fixes including [#445](https://github.com/Yalantis/uCrop/issues/445), [#465](https://github.com/Yalantis/uCrop/issues/465) and more!    
  * Material design support 
  * uCrop fragment as child fragment
  * Added Italian language

### Version: 2.2.2

* uCrop fragment added
* bugfix

### Version: 2.2.1

  * Fix including [#285](https://github.com/Yalantis/uCrop/issues/285)

### Version: 2.2

  * Several fixes including [#121](https://github.com/Yalantis/uCrop/issues/121), [#173](https://github.com/Yalantis/uCrop/issues/173), [#184](https://github.com/Yalantis/uCrop/issues/184) and more!
  * New APIs introduced [#149](https://github.com/Yalantis/uCrop/issues/149), [#186](https://github.com/Yalantis/uCrop/issues/186) and [#156](https://github.com/Yalantis/uCrop/issues/156)

### Version: 2.1

  * Fixes issue with EXIF data (images taken on front camera with Samsung devices mostly) [#130](https://github.com/Yalantis/uCrop/issues/130) [#111](https://github.com/Yalantis/uCrop/issues/111)
  * Added API to set custom set of aspect ratio options for user. [#131](https://github.com/Yalantis/uCrop/issues/131)
  * Added API to set all configs via UCrop.Options class. [#126](https://github.com/Yalantis/uCrop/issues/126)
  * Added ABI x86_64 support. [#105](https://github.com/Yalantis/uCrop/issues/105)

### Version: 2.0

  * Native image crop (able to crop high-resolution images, e.g. 16MP & 32MP images on Nexus 5X).
  * WebP compression format is not supported at the moment (choose JPEG or PNG).
  * Now library copies EXIF data to cropped image (size and orientation are updated).
  
### Version: 1.5

  * Introduced "Freestyle" crop (you can resize crop rectangle by dragging it corners) [#32](https://github.com/Yalantis/uCrop/issues/32)
  * Now image & crop view paddings are not associated [#68](https://github.com/Yalantis/uCrop/issues/68)
  * Updated API

### Version: 1.4

  * Introduced http(s) Uri support!
  * Image is cropped in background thread.
  * Showing loader while Bitmap is processed (both loading and cropping).
  * Several bug fixes.
  * Couple new things to configure.
  * Updated minSdkVersion to Android ICS 4.0 (no reason to support couple percents of old phones).

### Version: 1.3

  * Image is loaded in background thread. Better error-handling for image decoding.
  * Improved EXIF data support (rotation and mirror).
  * Small UI updates.
  * Couple new things to configure.
  
  * Sample updated with possibility to choose custom aspect ratio.

### Version: 1.2

  * Updated core logic so an image corrects its position smoothly and obviously.

### Version: 1.1

  * UCrop builder was updated and now UCrop.Options class has even more values to setup.

### Version: 1.0

  * Initial Build

### Let us know!

We’d be really happy if you sent us links to your projects where you use our component. Just send an email to github@yalantis.com And do let us know if you have any questions or suggestion regarding the library. 

#### Apps using uCrop

- [Thirty](https://play.google.com/store/apps/details?id=com.twominds.thirty).
- [Light Smart HD](https://play.google.com/store/apps/details?id=com.SmartCamera.simple).
- [BCReader](https://play.google.com/store/apps/details?id=com.iac.bcreader).
- [Xprezia: Share Your Passion](https://play.google.com/store/apps/details?id=com.xprezzia.cnj).

## License

    Copyright 2017, Yalantis

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
