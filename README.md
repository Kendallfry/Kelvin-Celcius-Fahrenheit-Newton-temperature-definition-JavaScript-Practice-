# Kelvin-Celcius-Fahrenheit-Newton-temperature-definition-JavaScript-Practice.
This is code I created while practicing defining variables and using string interpolation in Javascript. 

#Coding below

// This code creates a variable that stores the value for degrees in Kelvin
const kelvin = 25;
// This code defines the cariable celsius which is a representation in degrees that has a value that is 273 less than Kelvin
const celsius = kelvin - 273;
// This code is what defines the value for fahrenheit.
let fahrenheit = celsius*(9/5) + 32;
// This code re-defines fahrenheit and round it to a whole number once it is converted from celsius
fahrenheit = Math.floor(fahrenheit);
// This code checks the program on the console.
console.log(`The temperature is ${fahrenheit}.`);
// This code defines Newton 
let newton = celsius*(33/100);
// This code re-defines newton and round it to a whole number once it is converted from celsius
newton = Math.floor(newton);
// This code checkes the program with the addition of the newton variable. 
console.log(`The temperature is ${newton}.`);
