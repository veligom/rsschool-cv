***
![Foto](https://scontent-waw1-1.xx.fbcdn.net/v/t39.30808-6/318791443_3001577629987396_7111670642369409944_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=0d5531&_nc_ohc=icOr3QeTR2wAX9Mg_Er&_nc_ht=scontent-waw1-1.xx&oh=00_AfC_vdlrUIyxjDWVzfGkB7dYFop1LwmLEd-MK-_mBtLPQQ&oe=6397D375)
# Yury Niadzvedski
***
### Contact information
![location](https://img.icons8.com/ios-filled/20/null/visit.png) **Location:** Mogilev, Republic of Belarus
![phone](https://img.icons8.com/ios-filled/20/null/apple-phone.png) **Phone:** +375-29-3692398
![mail](https://img.icons8.com/ios-filled/20/null/apple-mail.png) **E-mail:** nedvedskiyuri@gmail.com
![git](https://img.icons8.com/fluency/20/null/github.png) **GitHub:** [@veligom](https://github.com/veligom)
![discord](https://img.icons8.com/ios-glyphs/20/null/discord-logo.png) **Discord:** [Yury Niadzvedski](https://discordapp.com/users/1044452260052205602/)
![facebook](https://img.icons8.com/material-rounded/20/null/facebook.png) **Facebook:** [Y_Ned](https://www.facebook.com/rctata)
![codepen](https://img.icons8.com/ios-filled/20/null/codepen.png) **Codepen:** [veli](https://codepen.io/veligom)
***
### About me
My name is Yuri, I am 36 years old. I work as a freelancer in an educational project for entrepreneurs. I am actively studying programming, inspired by Web development. I like to spend my free time with my parents and friends. I am actively engaged in sports, like to travel and make new acquaintances.  

I am currently actively studying English and the Java Script programming language.  

Every day before going to bed I try to read 25 sheets of fiction. The last book I read was *["The Theory of Castes and roles"](https://www.litres.ru/aleksey-krol/teoriya-kast-i-roley/otzivi/)* by Alex Kroll, I highly recommend it.  

>Never regret anything, because at a certain moment it was exactly what you wanted......
***
### Skills and Proficiency
+ **Basic knowledge of the programming language:**
    + С++
	+ C#
	+ JS
	+ MS SQL SERVER
+ **Graphic Editors:**
    + Adobe Photoshop
	+ CorelDRAW
+ **Other skills:**
    + HTML5/CSS3
	+ UNIX systems
	+ Computer networks
***
### Code example:
**Task:** _Using prompt, request any number from the user and check
it according to the following parameters:\
more/less than 100;\
 even/odd;\
 fractional/non;\
 fractional;\
 positive/negative.  
 
Display the test results on the screen in any available way in approximately the
following format - "The number you entered is less than one hundred, even, positive,
not fractional."_

**Decision #1**:
``` javascript
let res_1, res_2, res_3, res_4;
const userNumber = prompt("Введите любое число:");
if (+userNumber) {
  if (userNumber < 100) {
    res_1 = "меньше ста";
  } else {
    res_1 = "больше ста";
  }
  if (userNumber % 2 == 0) {
    res_2 = "четное";
  } else {
    res_2 = "нечетное";
  }
  if (userNumber > 0) {
    res_3 = "положительное";
  } else {
    res_3 = "отрицательное";
  }
  if (userNumber % 1 == 0) {
    res_4 = "не целое";
  } else {
    res_4 = "дробное";
	} 
	alert(`Вы ввели число ${res_1}, ${res_2}, ${res_3}, ${res_4}!`);
} else {
	alert('К сожалению, Вы ввели не число, попробуйте ещё раз!');
}
```
**Decision #2**:
``` javascript
let res_1, res_2, res_3, res_4;
const userNumber = prompt("Введите любое число:");
(+userNumber) || userNumber && alert("Пожалуйста, введите число!");
res_1 =
  (userNumber > 100 && "больше ста") ||
  (userNumber < 100 && "меньше ста") ||
  (userNumber == 100 && "равно 100");
res_2 =
  (userNumber > 0 && "положительное") || (userNumber < 0 && "отрицательное");
res_3 =(userNumber % 1 == 0 && "целое") || (userNumber % 1 !== 0 && "дробное");
res_4 =
  (userNumber % 2 == 0 && "четное") || (userNumber % 2 !== 0 && "нечетное");

alert(`Введенное Вами число ${res_1}, ${res_2}, ${res_3}, ${res_4}`);
```
***