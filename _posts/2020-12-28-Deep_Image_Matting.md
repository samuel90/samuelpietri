---
layout: single
title:  "Deep Image Matting"
excerpt: "Dive into different solutions for image matting."
date:   2020-12-26 16:28:53 +0100
categories: deep-learning image-matting
classes: wide 
header:
  teaser: "assets/images/002_image_matting/test.png"
  #overlay_image: "assets/images/002_image_matting/test.png"
---

The greenscreen will become obsolete, that's a fact. One way or another new techniques will jump in and will make work of image-matting a much more automated, less time-consuming job. To be fair some alternatives are already been used in Hollywood productions such as the [virtual sets](https://www.insider.com/green-screen-virtual-sets-mandalorian-2020-4) used in the latest Disney series "The Mandalorian". A set of led screens recreate the environment in real time improving the effects of reflections and allowing the actors to move in a much more realistic set are becoming a thing. 
Deep learning techniques are coming up, as well, letting the practice of manually cutting out content over background becoming fully automated, with almost no supervision. Now I'll take a look at a couple of alternatives that I found interesting trying them out with different content and since I've already introduced the Mandalorian I'll use some of its shots to test various techniques.

MODNet

![MODNet_001](/assets/images/002_image_matting/MODNet_001.jpg)

![MODNet_002](/assets/images/002_image_matting/MODNet_002.jpg)

![MODNet_003](/assets/images/002_image_matting/MODNet_003.jpg)

U-2-Net

![U-2-Net_001](/assets/images/002_image_matting/U-2-Net_001.jpg)

![U-2-Net_002](/assets/images/002_image_matting/U-2-Net_002.jpg)

![U-2-Net_003](/assets/images/002_image_matting/U-2-Net_003.jpg)




![Image Matting Test](/assets/images/002_image_matting/Image_Matting_Test.gif)


{% include video id="496647965" provider="vimeo" %}

![MODNet_Errors](/assets/images/002_image_matting/MODNet_Errors.jpg)
![U-2-Net_Errors](/assets/images/002_image_matting/U-2-Net_Errors.jpg)


![MODNet_U-2-Net_001](/assets/images/002_image_matting/MODNet_U-2-Net_001.jpg)
![MODNet_U-2-Net_002](/assets/images/002_image_matting/MODNet_U-2-Net_002.jpg)
![MODNet_U-2-Net_003](/assets/images/002_image_matting/MODNet_U-2-Net_002.jpg)




{% include video id="496656226" provider="vimeo" %}

