# JavaScript-learning-
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
