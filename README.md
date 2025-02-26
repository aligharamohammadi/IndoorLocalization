# IndoorLocalization
I have developed a real-time indoor localization system using TOF sensors based on a database. The system currently operates with three anchors and one tag for localization in a T-intersection environment.

 

System Setup:

The middle anchor (Anchor2) serves as the initiator, synchronizing all anchors. It has visibility of both Anchor1 and Anchor3.

The initiator anchor is essential—the system will not function without it. In future expansions, if we acquire more devices, we could place the initiator on the cart instead.

The anchors are installed at a height of 2.1 meters, facing downward, while the tag on the cart is facing upward.

Anchor1 and Anchor3 are positioned 7 meters away from the central point (the middle of the T-intersection).
![image](https://github.com/user-attachments/assets/a4800f1d-dec2-4eca-aad9-73d10e42b835)


Localization:

At least two anchors per corridor ensure continuous localization, while the tag is mounted on the vehicle.

The localization is based on Anchor2 and either Anchor1 or Anchor3, depending on the tag’s position.


![Video](https://github.com/user-attachments/assets/67692708-576c-48a6-8247-06a3090aca3f)


