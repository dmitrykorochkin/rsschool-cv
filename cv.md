## Dmitry Korochkin

### My Contact info: 
* **E-mail:** abramslost@gmail.com
* **Github:** [dmitrykorochkin](https://github.com/dmitrykorochkin)
* **Telegram:** [Kunica28](@Kunica28)

### About Me 

Hello, I am 32 years old, I work as a system administrator, for a long time learning web development was my hobby, now I want to become a good web developer.

### Skills 
* HTML
* CSS(SASS, BEM)
* Git/GitHub
* JavaScript (online school education)
* Figma, Photoshop

### Code example: 
```
const numberGame = function() {

    const number = Math.floor(Math.random() * 100) + 1;
    const inNumber = function(num) {
        return !isNaN(parseFloat(num)) && isFinite(num);
    }

    const bigNumber = function() {
        const numberPrompt = prompt("Угадай число от 0 до 100");
         if (numberPrompt === null) {
             alert('Игра окончена');
             return;
         }

         if (inNumber(numberPrompt)) {
             const userNumber  = +numberPrompt;
 
             if (userNumber > number) {
                 
                 alert('Загадочное число меньше');
                 bigNumber();
 
             } else if (userNumber < number) {
                 alert('Загадочное число больше');
                 bigNumber();
             } else {
                 if (confirm('Вы угадали: Сыграем еще?')) {
                     bigNumber();
                 } else {
                     alert('Игра окончена');
                     return;
                 }
             }
 
         } else {
             alert('Введите число');
             bigNumber();
         }
       
     }; 
 
     bigNumber();
};
numberGame();
```

### Education and corses 
* Nizhny Novgorod State Technical University. R.E. Alekseeva
* Online web development school "GLO Academy"


### Languages 
* Russian - native speaker
* Englich - A1 
