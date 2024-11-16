In Discord, on a server far far away.......  

# Duh-Duh-Duh-Dun-DunDaDuh-Dun-DunDaDuh-Dun-Dun-Dun-Dun-DunDaDuh-DaDunDaDuh!!!!  
.  
.  
.  
.  
After a long wait, I've finally done it.  

These are the PCBs you're looking for.   

Introducing Jangofet, Bobafet, & Ailynfet. 

It's an image heavy readme, so buckle up.  

Jangofet is a Flex cable that works on either v1 or v2  
Now this might be expensive to have made, But you will only need one cable, not 2.  
![image](https://github.com/user-attachments/assets/749e488b-0f25-4feb-9ee1-d746e3be66e3)  
![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/jangofet/jangotop.png)  
![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/jangofet/jangobottom.png)  

Assembled boards can be ordered for around $75 for 25 of them, so like $3 a cable. The final price depends on the cost of parts. 
Uses 2x [IRFHS8342PbF](https://www.infineon.com/dgdl/irfhs8342pbf.pdf?fileId=5546d462533600a401535623992e1f5f) or 2x [NP2016DR-N-G](https://www.lcsc.com/datasheet/lcsc_datasheet_2208231101_NATLINEAR-NP2016DR-N-G_C2991144.pdf)  

------------------------------------------------------------------------------------------------------------

Because of the cost of flexible pcbs and having them assembled for you(if you don’t want to hand assemble), I have also created Bobafet; a little 10mmX10mm pcb to achieve the same task.  
The min board size Jlcpcb will assemble is 10x10 so you may have to file it down a little. I have also kept the holes all the same size on the larger end, so it’s cheaper to manufacture.  

![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/bobafet/bobafet-3D-top.png)  
![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/bobafet/bobafettop.png)   
![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/bobafet/bobafetbottom.png)  

Assembled boards can be ordered for around $20 for 25 of them, so like $0.80 a board. The final price depends on the cost of parts. 
Uses 2x [IRFHS8342PbF](https://www.infineon.com/dgdl/irfhs8342pbf.pdf?fileId=5546d462533600a401535623992e1f5f)  

------------------------------------------------------------------------------------------------------------

Because of the cost of flexible pcbs and having them assembled for you(if you don’t want to hand assemble), & so you can use a different mosfet. I have also created Ailynfet; a little 10mmX10mm pcb to achieve the same task.  
The min board size Jlcpcb will assemble is 10x10 so you may have to file it down a little.  
I have also kept the holes all the same size on the larger end, so it’s cheaper to manufacture.  
Ailynfet can be used with 1 or 2 mosfets.  
The footprint is for [AON6792](https://www.aosmd.com/sites/default/files/res/datasheets/AON6792.pdf), [AON6512](https://www.aosmd.com/sites/default/files/res/datasheets/AON6512.pdf), & the [TPN8R903NL](https://toshiba.semicon-storage.com/info/TPN8R903NL_datasheet_en_20140218.pdf?did=14026&prodName=TPN8R903NL).
The AON6792, and AON6512 are said to work with only 1 mosfet. The TPN8R903NL was said to work but it didn't say if it needed 1 or 2 mosfets. So there are 2 pads and bridge points if need be.  
If using 2 mosfets you need to bridge 2 points, they're marked with lines on the PCB. They're also marked in the pictures.
With all three of the boards I kept cost in mind while designing them.  


![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/ailynfet/ailynfet-3D-top.png)  
![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/ailynfet/ailynfettop.png)   
![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/ailynfet/ailynfetbottom.png)  


I've included all the files, not just the Gerbers. It isn't really open if all you give is the Gerbers.  



My license is, just give credit which is as simple as leaving the QR code as it links to this repo. I didn't do this to make money, I did this for the community.  
Thanks to stashboy for taking measurements for me because my calipers were dead.
