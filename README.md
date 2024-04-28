# identity-card-scanner
A tensorflow js project with a YOLO model trained to recognize french identity cards and each segments composing it.
<br>
<br>
It's a non-optimized proof of concept of an app that can scan french identity cards in a continuous video stream.
<br>
We can simply add conditions that when several classes are detected, it saves the images, parse the extracted informations on it and triggers some automations like :
- Authenfication of users on a website
<br>
- Compare name and faces to those in law enforcement databases
<br>
- Allow entrance to a secured building to specific people
<br>
- Autorize payments through id verification
<br>
<br>
It can recognize the ROI (the identity card) + 12 additional classes including portrait image, MRZ, etc..
<br>
It can run on any devices (computers, mobiles, tablets..) as it is hosted on a web-app and uses tensorflow js.

<br>
<br>

<div align="left">
         <a href="https://www.youtube.com/shorts/iB--z3T2SwY">
                  <img src="https://github.com/RaghaniSebastien/identity-card-scanner/assets/73033350/eba7d984-b4e0-4f78-ae24-3ca7a54fe720" width="450";/>
         </a>
</div>



