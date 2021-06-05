## Project 1

<img width="581" alt="p1-folders" src="https://user-images.githubusercontent.com/84175061/120882161-ae939b80-c58a-11eb-80f2-fff6d2bd5939.png">
<img width="593" alt="p1-ping" src="https://user-images.githubusercontent.com/84175061/120882162-af2c3200-c58a-11eb-8eff-b75e1ffcde6c.png">
<img width="587" alt="p1-tree" src="https://user-images.githubusercontent.com/84175061/120882164-afc4c880-c58a-11eb-9da7-f4af5df5f6e0.png">


### p1-date.js
```
/*
    CIT 281 Project 1
    Name: Brianna Wei
*/

let daysOfTheWeek = ["Sunday", "Monday", "Tuesday", "Wednesday", "Thursday", "Friday", "Saturday"];

let currentDate =  new Date();
let numAsDayOfWeek = currentDate.getDay();


for(let i= 0; i <days.length();i++) {
    console.log(daysOfTheWeek[(numAsDayOfWeek + i) % 7];

}

```


### p1-random.js
```
/*
    CIT 281 Project 1
    Name: Brianna Wei
*/

// Returns a random number between min (inclusive) and max (exclusive)
function getRandomInteger(min, max) {
    return Math.floor(Math.random() * (max - min) + min);
}

let letters = ["a", "b", "c", "d", "e", "f", "g", "h", "i", "j", "k", "l", "m", "n", "o", "p", "q", "r", "s", "t", "u", "v", "w", "x", "y", "z"];
let line = ""; 
let randomChar = getRandomInteger(5,25);
for (let i = 0; i < randomChar; i ++) {
    let randomIndex = getRandomInteger(0,25);
    line = line + letters[randomIndex];
}

console.log(line);

```
