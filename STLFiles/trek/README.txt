                   .:                     :,                                          
,:::::::: ::`      :::                   :::                                          
,:::::::: ::`      :::                   :::                                          
.,,:::,,, ::`.:,   ... .. .:,     .:. ..`... ..`   ..   .:,    .. ::  .::,     .:,`   
   ,::    :::::::  ::, :::::::  `:::::::.,:: :::  ::: .::::::  ::::: ::::::  .::::::  
   ,::    :::::::: ::, :::::::: ::::::::.,:: :::  ::: :::,:::, ::::: ::::::, :::::::: 
   ,::    :::  ::: ::, :::  :::`::.  :::.,::  ::,`::`:::   ::: :::  `::,`   :::   ::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  :::::: ::::::::: ::`   :::::: ::::::::: 
   ,::    ::.  ::: ::, ::`  :::.::    ::.,::  .::::: ::::::::: ::`    ::::::::::::::: 
   ,::    ::.  ::: ::, ::`  ::: ::: `:::.,::   ::::  :::`  ,,, ::`  .::  :::.::.  ,,, 
   ,::    ::.  ::: ::, ::`  ::: ::::::::.,::   ::::   :::::::` ::`   ::::::: :::::::. 
   ,::    ::.  ::: ::, ::`  :::  :::::::`,::    ::.    :::::`  ::`   ::::::   :::::.  
                                ::,  ,::                               ``             
                                ::::::::                                              
                                 ::::::                                               
                                  `,,`


http://www.thingiverse.com/thing:2425427
Star Trek Badges by Wabbler is licensed under the Creative Commons - Attribution - Non-Commercial license.
http://creativecommons.org/licenses/by-nc/3.0/

# Summary

I'm just a star trek fan and tried to create this badges by myself. I was useing some pictures and photos that I found in the internet, to model these. Use the following magnetes to attach the badges on your shirt:

4 disc magnets 4 x 1 mm for each badge
https://www.amazon.de/Unbekannt-100-Neodym-Micromagnete-Zylinder/dp/B00CLPZYF8/ref=sr_1_3?s=officeproduct&ie=UTF8&qid=1502533505&sr=1-3&keywords=magnet+4x1

and

1 sew-in magnets for the shirt
https://www.amazon.de/Scheibenmagnete-Einn%C3%A4hen-quadratischer-PVC-H%C3%BClle-Haftkraft/dp/B072PRHJBL/ref=sr_1_1?s=kitchen&ie=UTF8&qid=1502533698&sr=1-1&keywords=magnete+zum+einn%C3%A4hen

To integrate the disc magnets to your print, generate the g-code and check the first layer level that close the holes for the magnets. Open the g-code file with text editor and search for the first Z"layer level". Write one line before the text: "M600 E0 L0 ;" and save the file.

If you use for example a resolution of 0.1 mm, the first closing layer will be 1.4 mm. Look for the first Z1.4 in the g-code and write one line thereover M600 E0 L0 ; (don't forget the dot comma). The command M600 stands for filament change pause. It should look like:

G1 X123.204 Y103.192 F7200.000 ;
M600 E0 L0 ;
G1 Z1.400 F7200.000 ;

If the last layer befor closing the holes is finished, the printer pause. Now, put the magnets into the holes and watch out to have identical pole direction of all magnets! Keep also in mind the pole of the counter magnet on your shirt.

If you push a button to continue the print, be aware the printer extrude some filament before printing. Get sure that no filament stuck on the extruder.

After printing, you can prime and paint the badges.

 I'm printing with a prusa Mk2 and had no problems with the magnets on the print bed.
 Be aware to not use magnets on your chest if you have a pacemaker! You can instead print the normal model (without magnets) and use a double-sided tape.

# Print Settings

Printer Brand: Prusa
Printer: Prusa Mk2
Supports: No

# Custom Section

![Alt text](https://cdn.thingiverse.com/assets/f5/13/92/5e/a0/2019-02-04_00.46.50.jpg)

![Alt text](https://cdn.thingiverse.com/assets/6c/88/87/48/ef/2019-02-04_00.43.35.jpg)