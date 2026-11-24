# EX No.6.2.DESIGN THE VARIOUS PARTS OF A MECHANICAL COMPONENT AND ASSEMBLE
## DATE: 23.11.2026

## AIM: 
To Design the various parts of a mechanical component and assemble it using a bottom-up approach then convert it into the orthographic view

## REQUIREMENTS: 
1. Autodesk fusion 360
2. Windows 10
3. 4 GB of RAM (integrated graphics recommend 6 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:

## STEP :1 Initial Setup
Open Autodesk Fusion 360 and start a new design.
In the Browser tree, expand Document Settings, click Change Active Units, and set the unit type to millimeters (mm) (matching standard furniture scale for the given dimensions).

<img width="567" height="635" alt="f346ad91-59f0-424d-8b8c-f3c13751cb26" src="https://github.com/user-attachments/assets/7d5828bc-476b-458f-8736-e1864d468956" />

## STEP 2: Creating the Seat Panel & Backrest Slats
Seat: Create a sketch on the top or side face of the seat frame and extrude a solid rectangular seat spanning the full 47 cm width, 55 cm depth, and 6 cm thickness (joining with the side frames).

<img width="754" height="659" alt="d88618c3-e020-4520-a994-1d45c6647d00" src="https://github.com/user-attachments/assets/98511d48-8ed9-462e-b4c1-b3d0273fb7ae" />
<img width="763" height="572" alt="06bf297b-64c4-47a0-a3fc-2c8c5432acee" src="https://github.com/user-attachments/assets/985b13e9-0add-484b-83b9-923c85450a1c" />

## STEP 3:Creating Legs 
Select Create Sketch and choose the YZ Plane (Right/Side view).
Draw the Front Leg as a vertical rectangle of width 6 cm and height 40 cm.
Offset 43 cm to the left along the base and draw the Rear Leg with a width of 6 cm and height 40 cm.

<img width="796" height="778" alt="de5714bd-9c38-4c43-ab95-032a57f66202" src="https://github.com/user-attachments/assets/2a6d982c-4e23-4e3e-a65a-e4c518226458" />
<img width="1280" height="451" alt="119f354f-aaa7-4abf-ac8f-f9458db020c9" src="https://github.com/user-attachments/assets/98a561b5-e0ae-4b10-9261-a5e551abf6a1" />
<img width="1283" height="698" alt="c8b1d4ff-824e-4d65-b4d6-da37d7d38695" src="https://github.com/user-attachments/assets/3ed0fdb6-087f-4be9-8885-efa76835c8ad" />

## STEP 4:Modeling the Side Frame and Inclined Backrest
Above the legs, draw the Seat side profile with a thickness of 6 cm and total depth of 55 cm (6+43+6cm).
From the top of the seat at the rear, sketch the inclined Backrest Post rising to a vertical height of 56 cm (total height 102 cm from the floor), angled backward so the overall horizontal depth from the front leg reaches 64 cm, maintaining a post thickness of 6 cm.
Finish the sketch and use the Extrude tool (E) to extrude the side frame profile by 6 cm (matching the leg thickness).

<img width="793" height="908" alt="4e0dd1ed-c534-42a1-9f2e-33b2afab74dd" src="https://github.com/user-attachments/assets/22d6b848-db2d-4c6e-a83b-2d73125a444b" />
<img width="617" height="626" alt="5028e54f-7869-4143-bacd-38e2ed1cd49d" src="https://github.com/user-attachments/assets/532f19fa-825d-4e8a-b1e6-a173cb747178" />

## STEP 5:Duplicating the Opposite Side Frame
Calculate the total width of the chair from the Front View: 6cm(leftleg)+35cm(innergap)+6cm(rightleg)=47cm.
Construct an Offset Plane at 41 cm (35+6cm) from the inner face of the first side frame, or use Mirror / Move/Copy (M) to place the second identical side frame 35 cm apart (inner-to-inner).

<img width="992" height="839" alt="6399bfa2-1e64-4949-ab10-030001ad1744" src="https://github.com/user-attachments/assets/4d1bcc2a-fdc3-4ebe-bbb8-693b6f43abf2" />
<img width="923" height="823" alt="09d94272-2f78-4bca-b1b3-6583f06dbcf1" src="https://github.com/user-attachments/assets/607a6129-5ea8-4b0f-bee8-f7d9dd6d2e4a" />

## STEP 6:Creating Backrest Slats:
Start a sketch on the front/inner face of the inclined backrest post.
Measure 20 cm up from the top surface of the seat and draw the Lower Slat with a height of 4 cm spanning the 35 cm inner width.
Measure 16 cm above the lower slat and draw the Upper Slat with a height of 4 cm (leaving 12 cm from the top of the upper slat to the top edge of the backrest).
Use Extrude (E) with the Join operation to extrude both slats across the 35 cm span (matching the slat thickness to the backrest post or standard rail thickness).

<img width="1063" height="816" alt="0c3faf5c-b03c-40f8-aba3-5e44e83656ac" src="https://github.com/user-attachments/assets/cb61c05a-3aa6-47ca-b229-45c3559e47bc" />
<img width="1317" height="768" alt="43a410bc-64d0-40e8-9f29-3ec094723a7a" src="https://github.com/user-attachments/assets/b34d2ab2-aaa7-4f1c-a698-e9f302721895" />

## STEP 7: Applying Fillets & Material
Select the Fillet tool (F) and apply a radius of R2 cm to the top-rear edges and R3 cm to the top-front edges of both backrest posts.
Right-click the body in the Browser, select Physical Material, and assign Wood (e.g., Oak or Cherry) to complete the model.

<img width="967" height="827" alt="c3ad7372-e5c7-4034-87b4-4ca77b5a0046" src="https://github.com/user-attachments/assets/1018ad3d-d203-4b7b-9087-802fcd89a8dc" />

### Note: 
If the components do not fit properly into the slots, it can be moved into the slot using the Move option.

## INPUT: 

![image](https://user-images.githubusercontent.com/113594316/199641859-1ebade5e-7bb4-4047-aa4b-89ae1d934ba0.png)

## OUTPUT:

<img width="818" height="707" alt="Screenshot 2026-11-24 003154" src="https://github.com/user-attachments/assets/ad59f422-f9ef-4cf5-9637-f4153d855c99" />
<img width="1022" height="722" alt="Screenshot 2026-11-24 003811" src="https://github.com/user-attachments/assets/454c7548-5a79-4fe0-8c44-f53ddc011a11" />

## RESULT:
Thus, a design of various parts of a mechanical component and assemble it using a bottom-up approach in orthographic view has been done

ILANILA VINNARASI.K.V
26017175
23.11.2026

