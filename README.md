# Delta-Reality-projects
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

Description: We use a real book with printed markers. To detect the markers we use the Vuforia Engine. The app uses two langauges, so there are two videos for each marker, one made in croatian and the other in english. To change the langauge we use real buttons that are connected to the android box. When the camera detects a marker it starts with the video projection, if the language is changed while the video is playing it will just switch the video from cro to eng or the other way around and continue the video from the same frame it was stoped.

![Interactive book1](https://github.com/user-attachments/assets/131cbad1-ef0c-45f3-b043-4a2881f64ad3)

![Interactive book2](https://github.com/user-attachments/assets/efb4928c-ad43-4730-a007-50b3780bfeea)

![Interactive book3](https://github.com/user-attachments/assets/f628cab2-7dfe-4d56-bc13-a619c008b94a)

![Interactive book4](https://github.com/user-attachments/assets/877bf24e-db21-4678-b85a-52caaabef2a8)

Video can be viewed here: https://drive.google.com/file/d/1_6tt-m7uKKhkISn7lb-ACMGB4CQT0aqD/view?usp=drive_link



