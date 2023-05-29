# JavaScript-learning
JavaScript: Kelvin Weather
//Kelvin Weather eg1
const kelvin = 273;
// comberting kelvin to celsius ; Celsius by subtracting 273
const celsius = kelvin - 273;
// this will calculate the fahrenheit
let fahrenheit = celsius * (9 / 5) + 32;
// roundup by using math.floor
fahrenheit = Math.floor(fahrenheit);
// we use string interpolation to replace TEMPERATURE
console.log(`The temperature is ${fahrenheit} degrees Fahrenheit.`);

// Convert to Newton
let newton = celsius * (33 / 100);
// Round down
newton = Math.floor(newton);

console.log(`The temperature is ${newton} degrees Newton.`);



//Dog Years  Eg2
//This Var is my age
const myAge = 100;
// variable for age
let earlyYears = 2;
earlyYears *= 10.5;
let laterYears = myAge - 2;
laterYears *= 4;
console.log(earlyYears);
console.log(laterYears);

let myAgeInDogYears = laterYears + earlyYears;
let myName = "katwoman".toLowerCase();
console.log(`My name is ${myName}. I am ${myAgeInDogYears} years old in dog years.`);

//convert any human age to dog years
//const x = humanyears;
//let 8 humanyears = 45 dog years;
//let 22 humanyears = 101 dog years;

//x *= 10;
