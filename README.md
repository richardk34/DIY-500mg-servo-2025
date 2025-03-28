# DIY-500mg-servo
500mg Servo for a micro RC model.
Forked from a fork of Charles Maulion's 500mg Servo Project on rcgroups.com

Currently developing a new version of the servo main body to work with my combination of motor and carbon fiber shafts.
Circuit boards are ordered and were soldered.

The plan is to use cycloidal gears derived from watchmaking standards to reduce the amount of friction that standard involute gears result in. 

More about gears:
https://www.numericana.com/answer/gears.htm#horology

https://www.hessmer.org/gears/CycloidalGearBuilder.html

http://www.hessmer.org/blog/2012/01/28/cycloidal-gear-builder/

<img src="https://user-images.githubusercontent.com/89079859/152161802-1aa1f0c0-fab4-48b5-bb16-03e7c73a0f11.png" width="20%" height="20%">
<img src="https://user-images.githubusercontent.com/89079859/152161979-31888126-6917-4d16-af3b-453313ec9731.png" width="20%" height="20%">
<img src="https://user-images.githubusercontent.com/89079859/152162040-724eb967-de27-4da8-be3b-f3f600c5c816.png" width="20%" height="20%">
<img src="https://user-images.githubusercontent.com/89079859/152162102-fd310f43-40ca-4f02-ac1a-36c68ac80686.png" width="20%" height="20%">
<img src="https://user-images.githubusercontent.com/89079859/152110818-6a085f0e-41cf-460b-99db-3cca11ab3b2c.png" width="20%" height="20%">


The electronic board components are as follows:

3 components :
1 atmel attiny1616 / 416 in  20-pin VQFN 3x3 mm
1 hall linear sensor : 49E-sot23 or A1304-sot23
1 cap 
![image](https://user-images.githubusercontent.com/89079859/152124439-74c066f0-c4e9-49b6-afa9-aa392909717a.png)

To program Attiny1616 with one wire UDPI, you need to made UDPI programmer : (use arduino 3.3V)
https://create.arduino.cc/projecthub/john-bradnam/create-your-own-updi-programmer-1e55f1




