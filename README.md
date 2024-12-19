In Discord, on a server far far away.......  

# Duh-Duh-Duh-Dun-DunDaDuh-Dun-DunDaDuh-Dun-Dun-Dun-Dun-DunDaDuh-DaDunDaDuh!!!!  
.  
.  
.  
.  
After a long wait, I've finally done it.  

These are the PCBs you're looking for.   

Introducing Jangofet, Bobafet, Sintasfet, & Ailynfet.  

It's an image heavy readme, so buckle up.  

Jangofet is a Flex cable that works on either v1 or v2.   
Now this might be expensive to have made, But you'll only need one cable, not 2.  
All holes are .3mm to help with keeping the price down. Also have some on order now to make sure they fit the v1 properly.   
I have a feeling you may have to cut the copper on the left which can be done without worry as it's all looped. You can cut both of the | and the cable will still function.  
I've also added a pad so you can cut the cable and attach it using wires.  
 
![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/jangofet/jango-3D-top.png)  
![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/jangofet/jangotop.png)  
![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/jangofet/jangobottom.png)  

Assembled boards can be ordered for around $175 for 5 panels of them which have 18 cables each so you get 90 cables total, so like $1.95 a cable. The final price depends on the cost of parts.   
Also you can have them save the framework and stencil for $5 a month and it will make future orders cheaper. Together theyre about $100 of the initial cost.  
So without them it's about $75 for 5 panels which makes the final per cable cost about $0.84 per cable.   
Uses 2x [IRFHS8342PbF](https://www.infineon.com/dgdl/irfhs8342pbf.pdf?fileId=5546d462533600a401535623992e1f5f).  

------------------------------------------------------------------------------------------------------------  

Because of the cost of flexible pcbs and having them assembled for you(if you don’t want to hand assemble), I have also created Bobafet; a little 10mmX10mm pcb to achieve the same task.  
Each board is technically 2 boards, JLCPCB wont assemble anything under 10x10mm so it's partially drilled in half so it still only counts as one.  

![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/bobafet/bobafet-3D-top.png)  
![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/bobafet/bobafettop.png)   
![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/bobafet/bobafetbottom.png)  

If you order just the paneled not assembled you can get 250 of them for under $10. That's the smallest order you can have made at JLC, 5 panels.  
5 panels with each panel having 25 boards which are then turned into 2 boards making a total of 250 boards.  
Assembled boards can be ordered for around $94 for 250 of them, so like $0.38 a board. The final price depends on the cost of parts. 
These prices are about the same for Sintasfet. For Ailynfet it works out to $0.72 per board as you only get 125 boards total.  
Should order these and the other boards no thicker than .6mm thick.  
Uses 2x [IRFHS8342PbF](https://www.infineon.com/dgdl/irfhs8342pbf.pdf?fileId=5546d462533600a401535623992e1f5f)  

------------------------------------------------------------------------------------------------------------  

Because mosfets can be pricey and so can getting pcbs made, I have also created Sintasfet; a little 10mmX10mm pcb to achieve the same task.  
It's desinged for the PDFN3x3 footprint and for mosfets strong enough to be used alone like the [TM80N03DF](https://www.lcsc.com/datasheet/lcsc_datasheet_2411121145_Tritech-MOS-TM80N03DF_C7463225.pdf).  
Each board is technically 2 boards, JLCPCB wont assemble anything under 10x10mm so it is partially drilled in half so it still only counts as one.  
Going off the specs this mosfet should work solo, I have some of the mosfet on their way to me now to personally test. So don't order yet.  

![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/sintasfet/sintasfet-3D-top.png)  
![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/sintasfet/sintasfettop.png)   
![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/sintasfet/sintasfetbottom.png)  

------------------------------------------------------------------------------------------------------------  

Because of the cost of flexible pcbs and having them assembled for you(if you don’t want to hand assemble), & so you can use a different mosfet. I have also created Ailynfet; a little 10mmX10mm pcb to achieve the same task.  
The min board size Jlcpcb will assemble is 10x10 so you may have to file it down a little.   
I have also kept the holes all the same size on the larger end, so it’s cheaper to manufacture.   
Ailynfet can be used with 2 mosfets.   
The footprint is for the [TPN8R903NL](https://toshiba.semicon-storage.com/info/TPN8R903NL_datasheet_en_20140218.pdf?did=14026&prodName=TPN8R903NL).  
PDFN3x3 footprint mosfets should fit also as the footprints are almost identical.  
With all four of the boards I kept cost in mind while designing them.   


![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/ailynfet/ailynfet-3D-top.png)  
![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/ailynfet/ailynfettop.png)   
![image](https://github.com/pbanj/Fet-1/raw/refs/heads/main/ailynfet/ailynfetbottom.png)  


I've included all the files, not just the Gerbers. It isn't really open if all you give is the Gerbers.  



My license is, just give credit which is as simple as leaving the QR code as it links to this repo. I didn't do this to make money, I did this for the community and to see if i could.  
Thanks to stashboy for taking measurements for me because my calipers were dead.  


Now with all the cool stuff out of the way here comes the dumb stuff. Ordering prototypes is fairly expensive.  
The pcbs themselves are not too expensive, but the parts add up quick.  
So if you'd like to help with current/future projects here is my [paypal](https://paypal.me/pbanj) this will help get pcbs done faster.  

# Donators  
Want to thank  

[Lazer1026](https://github.com/Lazr1026)  
[Emerekt](https://github.com/Emerekt-git) 


#Disclaimer
Important: This is for educational purposes only.

Neither I nor the contributors are not responsible for any misuse or damage caused by this project.  
Use at your own risk and only on systems you own or have explicit permission to test.