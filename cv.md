## rsschool-cv
***
# Yana Dyachok
#### Front End developer
***
![my photo](./assets/img/cv-img.jpg "my photo") 
### Contacts
***
* [Address](https://www.google.com/maps/place/%D1%83%D0%BB.+%D0%97%D0%B0%D0%BC%D0%BE%D1%81%D1%82%D1%8F%D0%BD%D1%81%D0%BA%D0%B0%D1%8F,+%D0%92%D0%B8%D0%BD%D0%BD%D0%B8%D1%86%D0%B0,+%D0%92%D0%B8%D0%BD%D0%BD%D0%B8%D1%86%D0%BA%D0%B0%D1%8F+%D0%BE%D0%B1%D0%BB%D0%B0%D1%81%D1%82%D1%8C,+21000/@49.2409224,28.4909036,17z/data=!3m1!4b1!4m6!3m5!1s0x472d5b4186629121:0x745e0ac3cf07d224!8m2!3d49.2409189!4d28.4930923!16s%2Fg%2F1vyxh564)
* [Phone](tel:+380992924988)
* [E-mail](mailto:annetart1994@gmail.com)
* [LinkedIn](https://www.linkedin.com/in/yana-dyachok-06a384253/)
* [GitHub](https://github.com/Yana-Dyachok)
* [Codewars](https://www.codewars.com/users/Yana-Dyachok)
* [Discord](https://discord.com/users/yana-dyachok#6659)
* [Telegram](https://t.me/yana_ins)
### About myself:
***
I'm a doctor by education. I started studying programming in 2021, because I really like it, it’s very interesting, I love the latest technologies and constant development I want to succeed in my future profession, because it’s much better to develop in the field that you like. In my free time, I work out and watch movies
### Skills
***
* HTML
* CSS 
* JavaScript
* C++ (OOP)
* Figma(for web development)
* Git & GitHub
* Editors:  VSCode, Visual Studio.
### Code examples
***
Write an algorithm that will identify valid IPv4 addresses in dot-decimal format. IPs should be considered valid if they consist of four octets, with values between 0 and 255, inclusive.(from  codewars)
***
```
              function isValidIP(str) {
                        let reg = /[A-z]/;
                        let array = str.split(".").filter((element) => {
                          for (let index = 0; index < element.length+1; index++) {
                            if (element[0] === "0" && element.length >= 2) element = "\n";
                          }
                          return (
                            element >= 0 &&
                            element <= 255 &&
                            !(element === "") &&
                            !element.includes("\n") &&
                            !element.includes(" ") &&
                            !element.match(reg)
                          );
                        });
                        return array.length !== 4 ? false : true;
                      }
               const adress = "0.229.017.134";
               console.log(isValidIP(adress)); 
 ```
 ***
Complete the function powerOfTwo that determines if a given non-negative integer is a power of two.You may assume the input is always valid.Beware of certain edge cases - for example, 1 is a power of 2 since 2^0 = 1 and 0 is not a power of 2.(from  codewars)
***
```
              function powerOfTwo(n){
                          let s=0
                          if(n===2)return true
                          while(n!==2){
                            n=Math.sqrt(n)
                          }
                          if(n===2) return true
                          if(n<2)return false
                        }
                        console.log(powerOfTwo(4096))
 ```
 ***
### Education
***
* [National Pirogov Memorial Medical University(2011-2017)](https://www.vnmu.edu.ua/)
   + Faculty: Medical №1.
* [IT-Step Academy (2021-2022)](https://vinnitsa.itstep.org/)
* [JavaScript/Front-end. Stage 0 (2022-2023)](https://rs.school/js-stage0/) in [RS School](https://rs.school/)

### Experience
***
   I did several projects when I was in [RS School](https://rs.school/) (Stage 0)
   + [CV](https://yana-dyachok-cv-rs-school.netlify.app/)
   + [plants](https://yana-dyachok.github.io/plants/)
   + [momentum](https://yana-dyachok.github.io/momentum/src/index.html)

### English
***
  * EPAM - test result: Pre-Intermediate( A2)
  * [Project 12](https://p12.com.ua/) - test result: Intermediate( B1)