Projects created withing Delta Reality

In this repository im going to showcase projectes i have worked on inside the Delta Reality firm. Also For each project there will be a description on the core features, technologys and hardware used.
_____________________________________________________________

**Client: Europa Park Germany - PHOTOBOOTH**

Hardware: Nuc, 55' Touch monitor, Orbbec Femto bolt camera

Description: A photobooth app that uses Orbbec Femto bolt camera for user detection and user cutout. The app is made out of few stages where the user can pick a language out of the 3 selected languages, select a background, take the picture and send the picture to its email. Also the user needs to agree to the GDPR that is inside the app, we use a certain algoritam to check if the email is written correctly. The email that is sending the picture is stored inside the .json file. The protocol for sending the email is SMTP and the email is send with a preloaded subject and description that can be changed inside the .json file.
For the languages we use the i2 localization package. From this is a photobooth template project was created for every other future photobooth app.

![EuropaParkIdle](https://github.com/user-attachments/assets/e5603f3b-a544-4af7-aa34-cdf46e7df020)

![EuropaParkLang_select](https://github.com/user-attachments/assets/92d4044f-e630-4dff-96e2-8ad11a4805bc)

![EuropaParkBG_select](https://github.com/user-attachments/assets/2071fae6-cd4c-462a-b538-9eb223da9984)

![Europa-Photobooth_2024-03-26-10-50-25](https://github.com/user-attachments/assets/4557b481-04ea-456d-a8a0-b46b95fdcece)

![EuropaParkSendToEmail](https://github.com/user-attachments/assets/47ad0f69-fda0-406e-ba7d-530e5b9197eb)

_____________________________________________________

**Client: Museum of Knin**

**Project: Interactive book**

Hardware: Andriod box, Infrared Camera, projector

Description: We use a real book with printed markers. To detect the markers we use the Vuforia Engine. The app uses two langauges, so there are two videos for each marker, one made in croatian and the other in english. To change the langauge we use real buttons that are connected to the android box. When the camera detects a marker it starts with the video projection, if the language is changed while the video is playing it will just switch the video from cro to eng or the other way around and continue the video from the same frame it was stoped. The videos are played using AVPro plugin. From this app we created a Interactive book template project that is used for every other future interactive book project.

![Interactive book1](https://github.com/user-attachments/assets/131cbad1-ef0c-45f3-b043-4a2881f64ad3)

![Interactive book2](https://github.com/user-attachments/assets/efb4928c-ad43-4730-a007-50b3780bfeea)

![Interactive book4](https://github.com/user-attachments/assets/877bf24e-db21-4678-b85a-52caaabef2a8)

Video can be viewed here: https://drive.google.com/file/d/1_6tt-m7uKKhkISn7lb-ACMGB4CQT0aqD/view?usp=drive_link

**Project: 360 VR**

Hardware: PicoG2

Description: The app is made out of two stages, the main menu stage where by using the head gaze pointer you can select if the subtitles will be loaded or not, and if you want to experience the 360VR on Croatian or English. The 2D animations are created by using DoTween, the gaze i used as a raycast, and we use the Canvas in the 3D space. Depending on the language selected the video will be loaded. The video is stored inside the Android persistant data path. The Subtitles are loaded from the exel sheet and the speed of the moving subtitles depends on the video duration. There are invisible boxes on each side of the hot air baloon to detect where the user is looking so that we can show the subtitles on the correct side. The projection of the video is on a 3D sphere, and to play the video we use AVPro plugin.

![Knin 360 VR](https://github.com/user-attachments/assets/9cf9f93a-06cc-46d9-8298-cf048a4997e4)

![Knin 360 VR2](https://github.com/user-attachments/assets/6807b688-6979-4e1c-abad-bcb7937ffce4)

![Knin 360 VR3](https://github.com/user-attachments/assets/f81860c5-1a1c-4a01-90b9-ddbc87dbf016)

Video can be viewed here: https://drive.google.com/file/d/1gplcIPQUki2ZbLijr6D5wW1ebIkQa5Cr/view?usp=drive_link

_______________________________________________

**Museum of Kruja**

**Project: Interactive Wall - AR**

Hardware: Android tablet

Description: AR app that uses Vuforia Engine for marker detection and video snapping. The video snapping was extra calibrated so we can get the fully correct position of the video playing over the marker. We needed to overlap a video taht is playing in 3D space with a video that will be played in 2D space, to get this effect we make a smooth transition from the 3D world space into the 2D overlay space. After the 2D overlay video finishes there is a state to scan the marker again. The subtitles are loaded via script so every subtitle is saved inside a exel sheet and loaded at the time when needed. For video handling i use AVPro plugin.

![krujawall1](https://github.com/user-attachments/assets/c3482c87-581b-4627-97f8-e3fda050fbb6)
![krujawall2](https://github.com/user-attachments/assets/4083fa7b-a5e3-4fbe-8cda-57b8dc27c5f8)
![krujawall3](https://github.com/user-attachments/assets/38dec019-e437-4c9e-bfda-ce7a8f5dee43)
![krujawall4](https://github.com/user-attachments/assets/2a927953-f98b-47b8-9fd2-eb00af2ca6d8)
![krujawall5](https://github.com/user-attachments/assets/50588f8e-2358-446c-a5d1-664681329ffd)

Video of the app can be viewed here:
https://drive.google.com/file/d/1ebzC_kql0EKSrFLBbgDCa1i4y3OwszBZ/view?usp=drive_link
https://drive.google.com/file/d/10kPVu7IPMu816wFTj0JbIFGDpoHLHMQv/view?usp=drive_link

**Project Virtual Dressing Room**

Hardware: PC, Kinect Camera

Description: By using the kinect camera i have implemented the hand gesture detection such as left and right hand raise, left and right hand swipe. Also user detection for the costumes to fit on the user. The app uses i2 localization for language inside the app, kinect depth information for correcly fitting the costume, and dynamic costume scaling for each user. To get the fluid costume effect we use a cloth simulation package combined with our physics logic. After a costume is selected you can take a picture and then a QR code will appear where the picture is stored. The picture is stored on their server. The logic for uploading is that the program checks a folder where the images are saved. When a picture inside the folder is detected the picture will be send to the server and afterward it will be deleted from the folder.

![VDR](https://github.com/user-attachments/assets/41a2c69f-034d-4812-9ab7-a8f606f65636)
![VDR2](https://github.com/user-attachments/assets/f97f7b6a-d268-4785-baad-153aaf98298c)

Video of the app can be viewed here: https://drive.google.com/file/d/1Rmgn_EHeOhd_96bASG5uYSHP8j2ZTeUE/view?usp=drive_link

1
