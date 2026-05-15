sorry for the spealling mistakes i make 




day 1 the start 4/29/2026
time tracked - 1.30h

soooooooooooo firstly ts was honestly annoying bro omg i wanted to makea a macropad so i decided sure lemme make one how hard could it be i only used easyeda before and i dont feel like learning kicad so i just rolled with it i first had to see the qmk docs to know what i was dealing with then i choose a mcu i decided to go with the pico cus its easy yk lots of docs then i opened the docs for it went to the wiring diagram and hell began
i placed the chip in easyeda and i edited the footprint to make it look a lil nice easy to work with ik i am a dumbahh

so i started by adding all the capcitors linking them to gnd and honsetly idk what was i doing i kept looking between the docs and drc to figure out what to do i added caps to the ivodd pins all of em then i decided to add the usb c which gave me lotss of toruble dude i first started routing it with my skills learnt from the usb hub hehehehe i connected them to the usb of the pico i added a shield but when i saw it if elt it looekd ugly asf so i deleted everyting and tried making it look pretty but i felt like it wont work so i had to redo everything again painn and now the usb c is done i think here is the schamaatics so far 
looks so messy ik ik ![alt text](image.png)



day 2 finsihed the mcu schematics 4/29/2026
time tracked - 1h

yippe i finished it i added alot of things firstly the 
voltage regulatour ![alt text](image-1.png)


crystal
![alt text](image-2.png)


debug for debugging duh
![alt text](image-3.png)

boot switch for switching duhh
 ![alt text](image-4.png)


 reset button for reseting duhhh 
 ![alt text](image-5.png)


 flash for what say it with me for flashing duhhhhh
  ![alt text](image-6.png)

  then those lil baby cute leds 
  ![alt text](image-7.png)

i just saw the docs kept following it not really much trouble and now were done yay 

day 3 started working on the switches 5/9/2026
time tracked - 1.3

okay so i decied to finally get back to this 
i first started by get a switch shaft then i edited the footprint cus it was lowk pmo and made it looks better i kinda failed

then i aslo go my switch and edited the footprint it still pmo so i edited the footprint much more
then i connected it to some capcitors and made the rows and coulmns then i connected it to the mcu and then i got a rotary encoder and did the same changed hte footprint and connected it ![alt text](image-8.png)

day 4 YAYAYAY I FINISHED THE SCHEMATICS 5/9/2026
time tracked - 1.3
what mostly i did was just add leds i finished the encoders and wired them up
i also finsihed the leds
i also added an rgb led for feedback so i started changing the footprint cus it was very ugly and me gag tbh but i made it look cool i am so awsome  and i finished wiring everyting putting it togther and here the finle schematics 
![alt text](image-9.png)
![alt text](image-10.png)



day 5 and 6
time tracked = 2h
hello there dear reviewer
sososoos i did alot of things well not alot kinda one but like kinda alot at the same time after i finished the schematics it was time for the great pcb so the first part was like 2 days ago and i was super sick and tired so i might not rember what i did but all i remember is me making the pcb outline adding the switches and the switch caps i think and there was a problem with the switch caps so i had to redo the footprint all over again and then i placed the board and wired the caps for it 
and part 2 is where i finsihed itnot alot happened just placing the parts going back and fourtgh i also made the schematics look a bit nicer and i noticed an issue with the switches that the 3d model was off so i had to re do all the switches but i finally got it and now its finished looks pretty ![alt text](image-11.png)

day 7
time tracked 2.6h 

started the pain of the routing so this is the hardest part routing so i had really really small place to work with 
but before routing i had to add some desgin rules so i did that changed everything and changed the vias to be easy and cheap for manifacturing and after i did that for some reason it said the lines r too thick so i had to redo all the desgin rules and restore them to deful but for also some unkown reason it stil said i cant untill i discoverd i need to change the width of the connection and re did all my desgin rules so after that i started the poor old routing which is not much but i had tooo little space so i was stuggling so much u dont even know but i manged then i had the worst thing possiable the flash pins there was so lill space so i just sat there for like what half an hour trying to wiggle it and crreating as much space as possiable for vias to go on the top layer and i finally did it so after that i went to connect the rows and cols of switches was pretty easy and then i got to routing the encoders i got pretty bored tbh so i just did 1 and said done for the day so prolly gonna contuine later ![](image-12.png)
here is progress 