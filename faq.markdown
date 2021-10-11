---
layout: default
title: FAQ
nav_order: 7
---

# [](#header-1)FAQ

### [](#header-3)1. Windows shows me a warning message when I run the Remote Face installer. Is it safe to install Remote Face on my computer?

![](assets/img/faq_1.png)

It is safe to run the installer downloaded from Remote Face’s official [website](https://remoteface.ai/). You may additionally check if the installer is signed with the correct itSeez3D certificate by clicking the “Show more details” -> “Show information about the publisher’s certificate”.

### [](#header-3)2. What conferencing applications do you support?

On Windows, Remote Face works with Zoom, Microsoft Teams, Skype, and Google Meet. On Mac, it supports Zoom and Google Meet.

### [](#header-3)3. Does Remote Face send my images somewhere?

No, avatars are generated locally on your computer without sending your images outside. It only will be sent if you choose a QR code as a way to transfer the selfie from your smartphone to the computer where Remote Face is installed.

### [](#header-3)4. What are the system requirements for Remote Face?

PC:
*   Windows 7 and higher	
*   CPU with AVX support
*   GPU and driver with support for OpenGL 3.3 or higher

Mac:

*   macOS 10.13 and higher
*   CPU with AVX support
*   GPU with Metal support



### [](#header-3)5. Why does my avatar move the lips when other people speak?

Remote Face uses lip-sync technology for lips animation: it consumes the microphone input of your computer to synchronize the avatar's mouth with your speech. If you use audio speakers in a conference, the microphone picks up the voices of other meeting participants even if you are silent at the moment. There are two ways to avoid the problem mentioned above: 1. Use headphones so that the microphone doesn’t pick up the other people's voices 2. Temporarily disable the lip-sync by clicking on the microphone icon in the settings menu. 

On Windows it is accessible from tray:

![](assets/img/faq_2.png)

![](assets/img/faq_3.png)

On Mac it is accessible from Status Bar:

![](assets/img/mac/faq_2.png)

![](assets/img/mac/faq_3.png)

### [](#header-3)6. Do I have to have a webcam to use Remote Face?

No, you only need a webcam if you want to synchronize the pose of your avatar with your current pose (i.e. head tracking).

### [](#header-3)7. Head tracking is not stable

Remote Face uses a camera connected to your computer to track the position of your head and sync with the position of your avatar. It is crucial to have a camera located right in front of you. The lighting is also very important: make sure that you do not have bright lights (for example windows) behind you if you want head tracking to be more stable.