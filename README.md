Projects created withing Delta Reality

In this repository im going to showcase projectes i have worked on inside the Delta Reality firm. Also For each project there will be a description on the core features, technologys and hardware used.
_____________________________________________________________

**Client: Europa Park Germany - PHOTOBOOTH**

Hardware: Nuc, 55' Touch monitor, Orbbec Femto bolt camera

Description: A photobooth app that uses Orbbec Femto bolt camera for user detection and user cutout. The app is made out of few stages where the user can pick a language out of the 3 selected languages, select a background, take the picture and send the picture to its email. Also the user needs to agree to the GDPR that is inside the app, we use a certain algoritam to check if the email is written correctly. The email that is sending the picture is stored inside the .json file. The protocol for sending the email is SMTP and the email is send with a preloaded subject and description that can be changed inside the .json file.
For the languages we use the i2 localization package. From this is a photobooth template project was created for every other future photobooth app.

<img src = "https://github.com/user-attachments/assets/e5603f3b-a544-4af7-aa34-cdf46e7df020" alt = "EuropaParkIdle" height = "500px" align = "center">
<br></br>

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

Description: By using the kinect camera i have implemented the hand gesture detection such as left and right hand raise, left and right hand swipe. Also user detection for the costumes to fit on the user. The app uses i2 localization for language inside the app, kinect depth information for correcly fitting the costume, and dynamic costume scaling for each user. To get the fluid costume effect we use a cloth simulation package combined with our physics logic. After a costume is selected you can take a picture and then a QR code will appear where the picture is stored. The picture is stored on their server. The logic for uploading is that the program checks a folder where the images are saved. When a picture inside the folder is detected the picture will be send to the server and afterward it will be deleted from the folder. The backgrounds of the screenshot can be regulated and changed withing the .json file(if its an image background or a blurred background). If the background is an image, there is a image folder where the client can load its images and the images will be at random loaded for each screenshot.

![VDR](https://github.com/user-attachments/assets/41a2c69f-034d-4812-9ab7-a8f606f65636)
![VDR2](https://github.com/user-attachments/assets/f97f7b6a-d268-4785-baad-153aaf98298c)

Screenshots from the app(there can be different backgrounds):

![KrujaVDR_2024-05-29-10-46-50](https://github.com/user-attachments/assets/569909b4-53c4-4574-b137-edeb63a7bd2d)
![KrujaVDR_2024-05-29-10-47-31](https://github.com/user-attachments/assets/5b2211cd-7a6d-49dd-82b3-707ec8b425b2)
![Uploading KrujaVDR_2023-11-06-09-23-57.png…]()

Video of the app can be viewed here: https://drive.google.com/file/d/1Rmgn_EHeOhd_96bASG5uYSHP8j2ZTeUE/view?usp=drive_link

______________________________________________________________

**Client: Croatian museum of sports**

**Project: Video galley**

Hardware: Nuc, Touch monitor
  
Description: For the video player i use the AVPro plugin. The video controls are custom si that we can use some features that are not integrated inside the plugin. The import of the videos needed to be easy to do so i have created a simple way for the clients to load their videos, by writting the name and description video inside an exel sheet with a unique Key string. That key string is used for the video name and the video thumbnail. All of the video thumbnails and videos are stored inside the Streaming Assets folder. 

![hsm-videogaleri](https://github.com/user-attachments/assets/2339311e-33bf-42c8-bbdf-e99e8d785da8)
![hsm-videogaleri2](https://github.com/user-attachments/assets/9b010bd3-5521-4a78-8105-c44a3afe18ae)
![hsm-videogaleri3](https://github.com/user-attachments/assets/1b7ee014-5b66-4f0a-8779-11d628396e4a)
![hsm-videogaleri4](https://github.com/user-attachments/assets/9c63c3f2-4c8d-4f5e-b905-671f01f0b40e)

Video of the app can be viewed here: https://drive.google.com/file/d/1J0meqXI9T2M6TiDta63DcWqWSK6b303O/view?usp=drive_link

____________________________________________________

**Client: Museum of Lipik**

**Project: Photographic work**

hardware: PC, DSLR camera, Projector, Touch monitor

Description: By using the DSLR camera as a web came and implementing mediapipe i have gotten a cutout of the users face. Getting the face point indexes of the user, im dynamic creating a mesh of the users face and with an extra camera in the sceen im getting the mesh position and creating a 2D alpha mask out of it. With this alpha mask i can blit the two textures (alpha mask and the camera feed) so that i can isolate the users surroundings and get only the users face. Now with some calculation i can get the users face inside the correct box no mather if the user stands infront of the camera of somewhere left/right. The costumes are created as prefabs and are saved hierachly inside scriptable objects. There are scriptable objects for the gender and the gender data holds the references to their costume data. The costume data holds the reference to the costume image thumbnail and the costume prefab. The flow of the app goes that on enter state of each screen a hologram appears on the Display 2 and talks about the history of photography. After the hologram finishes the app is interactable. After a costume is picked a screenshot state is up next where the user can take a screenhot of himself. There is a sepia shader material that is applyed on the final image. Aftweward the user can give the image a name and by submiting it the image is send via local server to the museums info table where the image can be printed out.

![Lipik1](https://github.com/user-attachments/assets/082b4751-acc0-4ecb-a5f2-8b72fba73431)
![Lipik2](https://github.com/user-attachments/assets/478783a1-6449-4b1f-b167-34ef6bd28925)
![Lipik3](https://github.com/user-attachments/assets/64546491-117d-4ddd-aac0-245a3dd62b4e)
![Lipik4](https://github.com/user-attachments/assets/eca2ff0a-cd18-468a-8f4f-8ffb7c816d04)
![Lipik5](https://github.com/user-attachments/assets/77b726e4-5f67-4cd6-9e3b-f1ec8b52b1df)
![Lipik6](https://github.com/user-attachments/assets/d4145d6b-9525-41fc-b6e1-33f67f56b523)

Final pictures:
![woman2](https://github.com/user-attachments/assets/6a4992cb-7d6b-48e6-ae2c-e0370b4692eb)
![woman3](https://github.com/user-attachments/assets/7f85a4ef-3f7c-427a-8c0d-5a006bd9c3ae)
![boy1](https://github.com/user-attachments/assets/8db3fc31-7dc6-413d-832a-20ef1a898c4d)
![F-kid1](https://github.com/user-attachments/assets/0fe88e8c-f01f-4809-bf0b-16aee315b628)
![F-kid2](https://github.com/user-attachments/assets/708c310d-cf5a-4a2a-b445-3bc44152b3e6)
![man3](https://github.com/user-attachments/assets/caec5411-b4c5-4177-bb80-9e33599461e4)

Full video of the app can be viewed here: https://drive.google.com/file/d/1XrbJmzYFgbCMTrrAovk3YQgmW0NfdtDd/view?usp=drive_link
___________________________________________________________________

Full flow of the all can ve viewed here:

https://drive.google.com/file/d/1qQMbKocsZt_tBHwy8UAblgq4c-Cz5c-H/view?usp=drive_link
https://drive.google.com/file/d/1E_xcVihBcvidTFz72rPi5agoDl2EO7r0/view?usp=drive_link
