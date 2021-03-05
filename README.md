# LOGICDATA

## CTFs
#### You need to install a Logic analyzer to capture the flag. [Click here](https://www.saleae.com/downloads/) to download

### I. challenge1.logicdata :-

1. Download the Logicdata file from [here](https://github.com/RanitPradhan/LOGICDATA/blob/master/challenge1.logicdata?raw=true)

2. Open the `challenge1.logicdata` file and follow the steps

3. We can see different channels are there but we need only 'Channel 0'

  <img src="https://github.com/RanitPradhan/LOGICDATA/blob/master/images/img_1.jpg">

4. We need to take one annotation here. We can take two different annotations but no need to take for this problem.

  <img src ="https://github.com/RanitPradhan/LOGICDATA/blob/master/images/img_2.jpg">

5. If we zoom in at the first annotation

  <img src ="https://github.com/RanitPradhan/LOGICDATA/blob/master/images/img_3.jpg">
  
7. Looks like a measurement for 1 bit, based on this measure we could get the baud rate(aka bit rate).
   1000000 ÷ 8.66 = 115473.441109
   This number is very close to 115200, a known baud rate. We can setup the bit rate in the Async Serial analyzer.
   
  <img src ="https://github.com/RanitPradhan/LOGICDATA/blob/master/images/img_4.jpg">
  
8. And we get the following:

  <img src ="https://github.com/RanitPradhan/LOGICDATA/blob/master/images/img_5.jpg">

Flag:- ````flag{part_of_a_balanced_breakfast}````
