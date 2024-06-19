   
## Alexandr Chalyshev ##
==================================================================
-------------------     ----------------------------
1. 📧                       I.C.WienerOnly@gmail.com
2. 📱                  +375(29)895-27-94
3. 🌇                       Belarus, Vitebsk
-------------------     ----------------------------

# Profile #
In these courses, I set myself the goal and task of getting acquainted with the profession of "JS/Front-end developer" for a change in professional activity

Education
---------

2006-2010 
:   **Technical operation of 
telecommunications systems and networks**; 
BELARUSIAN STATE ACADEMY OF COMMUNICATION 
(Vitebsk)

2010-2014
:   **Information Technology and Management Engineer**; 
BELARUSIAN STATE UNIVERSITY OF INFORMATICS AND RADIOELECTRONICS (Minsk)

Experience
----------
1.  First task:
 Write a function that accepts an array of 10 integers (between 0 and 9), that returns a string of those numbers in the form of a phone number.
* solution:
```
function createPhoneNumber(numbers){
 let numberForm="(xxx) xxx-xxxx";
  for(let i=0; i<numberForm.length; i++){
    numberForm=numberForm.replace("x", numbers[i]);}
  return numberForm;}
```
[codewars example](https://www.codewars.com/kata/525f50e3b73515a6db000b83/train/javascript "example of a solution on the site")

----------
2. Second task:
Given n, take the sum of the digits of n. If that value has more than one digit, continue reducing in this way until a single-digit number is produced. The input will be a non-negative integer.
* solution:
```
function digitalRoot(n) {
let sum=0;
x=String(n);
for(let i=0; i<x.length; i++){sum+=Number(x[i]);}
 if (sum>9) {sum=digitalRoot(sum);} 
 return (sum)
```
[codewars example](https://www.codewars.com/kata/541c8630095125aba6000c00/train/javascript "example of a solution on the site")

----------------------------------------
|Place of work|
|:---------:|
| Republican Unitary Enterprise "Beltelecom"|
* Languages:
     * English (Intermediate)
     * Russian 
     * Belarussian
* skills
    * HTML (Junior)
    * CSS (Junior)
    * Java Script (Junior)
    
    
