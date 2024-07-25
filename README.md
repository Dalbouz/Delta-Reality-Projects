Projects created withing Delta Reality

In this repository im going to showcase projectes i have worked on inside the Delta Reality firm. Also For each project there will be a description on the core features, technologys and hardware used. Every project i published and can be seen inside the museums. 
_____________________________________________________________

**Client: Europa Park Germany - PHOTOBOOTH**

Hardware: Nuc, 55' Touch monitor, Orbbec Femto bolt camera

Description: A photobooth app that uses Orbbec Femto bolt camera for user detection and user cutout. The app is made out of few stages where the user can pick a language out of the 3 selected languages, select a background, take the picture and send the picture to its email. Also the user needs to agree to the GDPR that is inside the app, we use a certain algoritam to check if the email is written correctly. The email that is sending the picture is stored inside the .json file. The protocol for sending the email is SMTP and the email is send with a preloaded subject and description that can be changed inside the .json file.
For the languages we use the i2 localization package. From this is a photobooth template project was created for every other future photobooth app.

<div align = "center">
<img src = "https://github.com/user-attachments/assets/e5603f3b-a544-4af7-aa34-cdf46e7df020" alt = "EuropaParkIdle" width = "700px" align = "center">
<br></br>
<img src  = "https://github.com/user-attachments/assets/92d4044f-e630-4dff-96e2-8ad11a4805bc" width = "700px">
<br></br>
<img src = "https://github.com/user-attachments/assets/2071fae6-cd4c-462a-b538-9eb223da9984" width = "700px">
<br></br>
<img src = "https://github.com/user-attachments/assets/4557b481-04ea-456d-a8a0-b46b95fdcece" width = "700px">
<br></br>
<img src = " https://github.com/user-attachments/assets/47ad0f69-fda0-406e-ba7d-530e5b9197eb" width ="700px">
</div>

_____________________________________________________

**Client: Museum of Knin**

**Project: Interactive book**

Hardware: Andriod box, Infrared Camera, projector

Description: We use a real book with printed markers. To detect the markers we use the Vuforia Engine. The app uses two langauges, so there are two videos for each marker, one made in croatian and the other in english. To change the langauge we use real buttons that are connected to the android box. When the camera detects a marker it starts with the video projection, if the language is changed while the video is playing it will just switch the video from cro to eng or the other way around and continue the video from the same frame it was stoped. The videos are played using AVPro plugin. From this app we created a Interactive book template project that is used for every other future interactive book project.
<br></br>
<div align = "center">
<img src = "https://github.com/user-attachments/assets/131cbad1-ef0c-45f3-b043-4a2881f64ad3" width = "700px">
<br></br>
<img src = "https://github.com/user-attachments/assets/efb4928c-ad43-4730-a007-50b3780bfeea" width = "700px">
<br></br>
<img src = "https://github.com/user-attachments/assets/877bf24e-db21-4678-b85a-52caaabef2a8" width = "700px">
</div>
<br></br>
Video can be viewed here: https://drive.google.com/file/d/1_6tt-m7uKKhkISn7lb-ACMGB4CQT0aqD/view?usp=drive_link
<br></br>
<b>Project: 360 VR</b>

Hardware: PicoG2

Description: The app is made out of two stages, the main menu stage where by using the head gaze pointer you can select if the subtitles will be loaded or not, and if you want to experience the 360VR on Croatian or English. The 2D animations are created by using DoTween, the gaze i used as a raycast, and we use the Canvas in the 3D space. Depending on the language selected the video will be loaded. The video is stored inside the Android persistant data path. The Subtitles are loaded from the exel sheet and the speed of the moving subtitles depends on the video duration. There are invisible boxes on each side of the hot air baloon to detect where the user is looking so that we can show the subtitles on the correct side. The projection of the video is on a 3D sphere, and to play the video we use AVPro plugin.
<br></br>
<div align = "center">
<img src = "https://github.com/user-attachments/assets/9cf9f93a-06cc-46d9-8298-cf048a4997e4" width = "700px">
<br></br>
<img src = "https://github.com/user-attachments/assets/6807b688-6979-4e1c-abad-bcb7937ffce4" width = "700px">
<br></br>
<img src = "https://github.com/user-attachments/assets/f81860c5-1a1c-4a01-90b9-ddbc87dbf016" width = "700px">
</div>
<br></br>
Video can be viewed here: https://drive.google.com/file/d/1gplcIPQUki2ZbLijr6D5wW1ebIkQa5Cr/view?usp=drive_link

_______________________________________________

**Client: Museum of Kruja**

**Project: Interactive Wall - AR**

Hardware: Android tablet

Description: AR app that uses Vuforia Engine for marker detection and video snapping. The video snapping was extra calibrated so we can get the fully correct position of the video playing over the marker. We needed to overlap a video taht is playing in 3D space with a video that will be played in 2D space, to get this effect we make a smooth transition from the 3D world space into the 2D overlay space. After the 2D overlay video finishes there is a state to scan the marker again. The subtitles are loaded via script so every subtitle is saved inside a exel sheet and loaded at the time when needed. For video handling i use AVPro plugin.
<br></br>
<div align = "center">
<img src = "https://github.com/user-attachments/assets/c3482c87-581b-4627-97f8-e3fda050fbb6" width = "700px">
  <br></br>
<img src = "https://github.com/user-attachments/assets/4083fa7b-a5e3-4fbe-8cda-57b8dc27c5f8" width = "700px">
  <br></br>

<img src = "https://github.com/user-attachments/assets/38dec019-e437-4c9e-bfda-ce7a8f5dee43" width = "700px">
<br></br>

<img src = "https://github.com/user-attachments/assets/2a927953-f98b-47b8-9fd2-eb00af2ca6d8" width = "700px">
<br></br>

<img src = "https://github.com/user-attachments/assets/50588f8e-2358-446c-a5d1-664681329ffd" width = "700px">
</div>

Video of the app can be viewed here:
https://drive.google.com/file/d/1ebzC_kql0EKSrFLBbgDCa1i4y3OwszBZ/view?usp=drive_link
https://drive.google.com/file/d/10kPVu7IPMu816wFTj0JbIFGDpoHLHMQv/view?usp=drive_link
<br></br>

<b>Project: Virtual Dressing Room</b>

Hardware: PC, Kinect Camera

Description: By using the kinect camera i have implemented the hand gesture detection such as left and right hand raise, left and right hand swipe. Also user detection for the costumes to fit on the user. The app uses i2 localization for language inside the app, kinect depth information for correcly fitting the costume, and dynamic costume scaling for each user. To get the fluid costume effect we use a cloth simulation package combined with our physics logic. After a costume is selected you can take a picture and then a QR code will appear where the picture is stored. The picture is stored on their server. The logic for uploading is that the program checks a folder where the images are saved. When a picture inside the folder is detected the picture will be send to the server and afterward it will be deleted from the folder. The backgrounds of the screenshot can be regulated and changed withing the .json file(if its an image background or a blurred background). If the background is an image, there is a image folder where the client can load its images and the images will be at random loaded for each screenshot.
<br></br>
<div align = "center">
<img src = "https://github.com/user-attachments/assets/41a2c69f-034d-4812-9ab7-a8f606f65636" height = "700px">

<img src = "https://github.com/user-attachments/assets/f97f7b6a-d268-4785-baad-153aaf98298c" height = "700px">
</div>
<br></br>
<div align = "center">
Screenshots from the app(there can be different backgrounds):
<br></br>

<img src = "https://github.com/user-attachments/assets/569909b4-53c4-4574-b137-edeb63a7bd2d" height = "700px">

<img src = "https://github.com/user-attachments/assets/5b2211cd-7a6d-49dd-82b3-707ec8b425b2" height = "700px">
</div>

<br></br>
Video of the app can be viewed here: https://drive.google.com/file/d/1Rmgn_EHeOhd_96bASG5uYSHP8j2ZTeUE/view?usp=drive_link

______________________________________________________________

**Client: Croatian museum of sports**

**Project: Video galley**

Hardware: Nuc, Touch monitor
  
Description: For the video player i use the AVPro plugin. The video controls are custom si that we can use some features that are not integrated inside the plugin. The import of the videos needed to be easy to do so i have created a simple way for the clients to load their videos, by writting the name and description video inside an exel sheet with a unique Key string. That key string is used for the video name and the video thumbnail. All of the video thumbnails and videos are stored inside the Streaming Assets folder. 
<br></br>
<div align = "center">
<img src = "https://github.com/user-attachments/assets/2339311e-33bf-42c8-bbdf-e99e8d785da8" height = "700px">
<img src = "https://github.com/user-attachments/assets/9b010bd3-5521-4a78-8105-c44a3afe18ae" height = "700px">
<img src = "https://github.com/user-attachments/assets/1b7ee014-5b66-4f0a-8779-11d628396e4a" height = "700px">
<img src = "https://github.com/user-attachments/assets/9c63c3f2-4c8d-4f5e-b905-671f01f0b40e" height = "700px">
  <br></br>
</div>

Video of the app can be viewed here: https://drive.google.com/file/d/1J0meqXI9T2M6TiDta63DcWqWSK6b303O/view?usp=drive_link

____________________________________________________

**Client: Museum of Lipik**

**Project: Photographic work**

hardware: PC, DSLR camera, Projector, Touch monitor

Description: By using the DSLR camera as a web came and implementing mediapipe i have gotten a cutout of the users face. Getting the face point indexes of the user, im dynamic creating a mesh of the users face and with an extra camera in the sceen im getting the mesh position and creating a 2D alpha mask out of it. With this alpha mask i can blit the two textures (alpha mask and the camera feed) so that i can isolate the users surroundings and get only the users face. Now with some calculation i can get the users face inside the correct box no mather if the user stands infront of the camera of somewhere left/right. The costumes are created as prefabs and are saved hierachly inside scriptable objects. There are scriptable objects for the gender and the gender data holds the references to their costume data. The costume data holds the reference to the costume image thumbnail and the costume prefab. The flow of the app goes that on enter state of each screen a hologram appears on the Display 2 and talks about the history of photography. After the hologram finishes the app is interactable. After a costume is picked a screenshot state is up next where the user can take a screenhot of himself. There is a sepia shader material that is applyed on the final image. Aftweward the user can give the image a name and by submiting it the image is send via local server to the museums info table where the image can be printed out.
<br></br>
<div align = "center">
<img src = "https://github.com/user-attachments/assets/082b4751-acc0-4ecb-a5f2-8b72fba73431" height = "700px">
<img src = "https://github.com/user-attachments/assets/478783a1-6449-4b1f-b167-34ef6bd28925" height = "700px">
<img src = "https://github.com/user-attachments/assets/64546491-117d-4ddd-aac0-245a3dd62b4e" height = "700px">
<img src = "https://github.com/user-attachments/assets/eca2ff0a-cd18-468a-8f4f-8ffb7c816d04" height = "700px">
<img src = "https://github.com/user-attachments/assets/77b726e4-5f67-4cd6-9e3b-f1ec8b52b1df" height = "700px">
<img src = "https://github.com/user-attachments/assets/d4145d6b-9525-41fc-b6e1-33f67f56b523" height = "700px">
</div>
<br></br>
<div align = "center">
Final pictures:
<br></br>

<img src = "https://github.com/user-attachments/assets/6a4992cb-7d6b-48e6-ae2c-e0370b4692eb" height = "700px">
<img src = "https://github.com/user-attachments/assets/7f85a4ef-3f7c-427a-8c0d-5a006bd9c3ae" height = "700px">
<img src = "https://github.com/user-attachments/assets/8db3fc31-7dc6-413d-832a-20ef1a898c4d" height = "700px">
<img src = "https://github.com/user-attachments/assets/0fe88e8c-f01f-4809-bf0b-16aee315b628" height = "700px">
<img src = "https://github.com/user-attachments/assets/708c310d-cf5a-4a2a-b445-3bc44152b3e6" height = "700px">
<img src = "https://github.com/user-attachments/assets/caec5411-b4c5-4177-bb80-9e33599461e4" height = "700px">
</div>
<br></br>
Full video of the app can be viewed here: https://drive.google.com/file/d/1XrbJmzYFgbCMTrrAovk3YQgmW0NfdtDd/view?usp=drive_link

________________________________________________________________________________________________________

<b>Client: Museum of natural history Zagreb</b>
<br></br>
<b>Project: Spectar electromagnetic waves</b>
<br></br>
Hardware: Nuc, 3x Planar monitors 55', external touch sensor
<br></br>
Description: multi touch informative application for exploring different minerals under different spectrum. Draggin the image through different spectrum's the image will shift to a different view deppending on the current spectrum it is in. The Info POI popups are created with scriptable objects and can be dinamicly changed, you can load different texts or images into a list and they will be shown in that order. Every image handles himself and checks the current position of the screen.
<div align ="center">
<img src = "https://github.com/user-attachments/assets/c6b1746b-7d6d-420e-807f-858f8b820286" width = "700px">
  <br></br>
<img src = "https://github.com/user-attachments/assets/c29beb1f-ea49-407f-9962-26d1c4120056" width = "700px">
  <br></br>
<img src = "https://github.com/user-attachments/assets/39426acb-9490-40ae-846f-f7b1bdbe8ef5" width = "700px">
  <br></br>
<img src = "https://github.com/user-attachments/assets/49e60fa0-ed5d-4c8c-85b8-723370352a55" width = "700px">

</div>
<br></br>
Full flow of the all can ve viewed here:

https://drive.google.com/file/d/1qQMbKocsZt_tBHwy8UAblgq4c-Cz5c-H/view?usp=drive_link
https://drive.google.com/file/d/1E_xcVihBcvidTFz72rPi5agoDl2EO7r0/view?usp=drive_link

______________________________________________________________________________

<b>Client: Etnographic museum of Požega</b>
<br></br>
<b>Project: Lerman's travels</b>
<br></br>
Hardware:Nuc, Touch monitor
<br></br>
Description: Educational 2D minigame where you explore Africa as the main character Lerman. There are 4 maps to travel to, all the maps are made as prefab variants and can be easly extended and changed. YOur playes can also wonder and hit bounds where it will inform you that your on the wrong path. The main path is created with bezier curves, and the bounds are also created around the area where the player can go. When the payers pivot hits the bounds it will inform you that your on the wrong path. There is also The main points where the player need to get to go to the next map. Everything is created as prefabs so you can fill the map/level prefab with all the needed features and they will work together, they are all independed from one another. When hitting the end point a letter will fly in and start the typing of the real letters that Lerman sended at that time. 
<div align = "center">
<img src = "https://github.com/user-attachments/assets/f31cf4c9-e4a9-40d9-bb21-553549f1cc09" width = "700px">
<br></br>
<img src = "https://github.com/user-attachments/assets/c6226a2e-8a42-4e1f-b8f2-637d990e4823" width = "700px">
<br></br>
<img src = "https://github.com/user-attachments/assets/b1fbaa19-72fa-4c55-a4e4-b29fc848a81c" width = "700px">
<br></br>
<img src = "https://github.com/user-attachments/assets/a75174cb-0708-4779-a8c3-041dd7f80ff1" width = "700px">
<br></br>
<img src = "https://github.com/user-attachments/assets/7d9fc9fa-021b-440c-bf18-f370fb6514ba" width = "700px">
<br></br>
<img src = "https://github.com/user-attachments/assets/14f6f582-21f4-444e-b4a0-0a989b0f64c5" width = "700px">
<br></br>
<img src = "https://github.com/user-attachments/assets/a9f00614-a657-435e-ba6f-47be63dca6ad" width = "700px">
<br></br>
<img src = "https://github.com/user-attachments/assets/bcd9dba5-b733-4e28-b7fc-2960e224be8a" width = "700px">
</div>
<br></br>
Full app flow can be viewed here: https://drive.google.com/file/d/1AebM8795vAkrZbgKJqI5VjhxEScpFtzf/view?usp=drive_link

____________________________________________________________

<b>Client:Pitch for Unesco</b>
<br></br>
Hardware: Oculus Quest 3 Pro
<br></br>
Description: MR app where we use are real world door, sync it with the 3D world in unity and create the effect that you can walk through the real door into a fantasy world. On the other side we use a 360 sphere to project a 360 image. For this effect we use the portal plugin. Using the controller for the anchor point in the real world we can correcly point where the door is and sync the opening of the door also. With the other controller you can preset the offset and main setups before usage.

<div align = "center">
<img src = "https://github.com/user-attachments/assets/880c7cd8-2fa2-4b09-b101-ae37b7dbc043" width = "700px">
  <br></br>

<img src = "https://github.com/user-attachments/assets/322672bf-bbb1-45ec-a42e-35c26dbcdf6a" width = "700px">
<br></br>
<img src = "https://github.com/user-attachments/assets/407df4f8-f985-4e3c-a84f-8059ada9146b" width = "700px">
</div>
<br></br>
Full app flow can be viewed here: https://drive.google.com/file/d/13u39FCARuu4GHLR8pmt4tJLlL8QgvdaD/view?usp=drive_link

__________________________________________________________________________

<b>Client: Museum of Halubarski Zvoncari</b>
  <br></br>
  
<b>Project: Paljenje Pusta</b>

Hardware: Nuc, Touch monitor, infinity rotary connected with arduino
<br></br>
Description: Every name is saved inside the .json file and can be changed or removed, puppet parts are saved as prefabs and loaded as such for fully costumization of the puppet. When the puppet is created we take a screenshot of the puppet and flatten it into one texture. Then apply the burnout shader on it. The Screenshoted puppet is saved and send to the local server on the info table of the museum. All of the puppets are saved in one folder and loaded into the gallery state where you can view the created puppets by year.

<div align = "center">
<img src = "https://github.com/user-attachments/assets/78e55ce0-555f-4619-9291-0b990c860651" width = "700px">
  <br></br>
<img src = "https://github.com/user-attachments/assets/af4b3ce0-cca2-43c0-b493-3498a1247dac" width = "700px">
  <br></br>
<img src = "https://github.com/user-attachments/assets/a3eaecac-84d3-4b8b-9b41-27a18dabfac1" width = "700px">
  <br></br>
<img src = "https://github.com/user-attachments/assets/281aab15-5834-4b0b-a5b6-8664d33ce73e" width = "700px">
  <br></br>
<img src = "https://github.com/user-attachments/assets/a8d24bde-3bce-49e1-9784-744071166a00" width = "700px">
  <br></br>
<img src = "https://github.com/user-attachments/assets/a0102f2d-391f-48c1-807d-32589d458946" width = "700px">
  <br></br>
<img src = "https://github.com/user-attachments/assets/e4c9346d-b854-47ed-b566-3f4dd3af4e6f" width = "700px">
  <br></br>
<img src = "https://github.com/user-attachments/assets/4c719ef0-9cde-451e-b2ce-15417d5a66c4" width = "700px">
  <br></br>
<img src = "https://github.com/user-attachments/assets/396e0035-43c8-4afa-ad63-a7a420017d06" width = "700px">
</div>
<br></br>
Full app flow can be viewed here: https://drive.google.com/file/d/15H0XBq1R-ytet4ytec0n7YLH-OhHCKlT/view?usp=drive_link
<br></br>
<b>Project: Tanac</b>

Hardware: Nuc, Kinect
<br></br>
Description: By using the Azure Kinect SDK for implementing the user detection and user gestures such as hand raise and hand swipe we can control the app. Its made out of few states, where one of the states is a video recording state. The user can dance and get comments from the few commentators. The video is recorded using the AVPro plugin. In a random frame the app takes the screenshot that is used later as the thumbnail of the video inside the gallery state and also the same picture is send to the info table of the museum where the picture can be printed out. We also add a time mark on the thumbnail when the screenshot is created. Videos are saved inside a folder withing the persistant data path with a id, and the thumbnail is saved inside another folder with the same id as the video id so that we can connect the corrent thumbnail with the corrent video.
<div align = "center">
<img src = "https://github.com/user-attachments/assets/5de88236-737e-4a57-8ea5-c9f0f3121523" height = "700px">
<img src = "https://github.com/user-attachments/assets/83cd156e-b292-4ea6-b8d5-f293d1745f7d" height = "700px">
<img src = "https://github.com/user-attachments/assets/c51e0f3f-d74c-4535-b92c-53698348ba79" height = "700px">
<img src = "https://github.com/user-attachments/assets/2bdb9bf1-c9f5-4567-8703-27983cfc8899" height = "700px">
<img src = "https://github.com/user-attachments/assets/52ba4e23-c603-4849-9784-b303460ec163" height = "700px">
<img src = "https://github.com/user-attachments/assets/7de31aec-db0a-436c-b405-7d997df7905f" height = "700px">

</div>
<br></br>
Full app flow can be viewed here:
https://drive.google.com/file/d/1tVDYwkJxhREezuNE_I_2Alx3AaH0Clq5/view?usp=drive_link
<br></br>
https://drive.google.com/file/d/1tgfQ8F--JR63M6xqLFv0UB0kvfXtNOuL/view?usp=drive_link
