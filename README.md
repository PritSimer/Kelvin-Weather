# Kelvin-Weather
Codecademy Javascript Beginners Practice Project
const kelvin = 0;//assign the value of 293 to declared variable called kelvin
const celsius = kelvin - 273; // converting kelvin to celsius formula
var fahrenheit = Math.floor(celsius*(9/5)+32); // calculating farenheit and storing into variable called 'fahrenheit' note: it is a var and not const as it can be reassigned. 
It has been declared as let so it can reassigned. Have assigned math.floor to round down the number
const newton = Math.floor(celsius*(33/100));
console.log(`The temperature is ${fahrenheit} degrees fahrenheit and ${newton} degrees newton`);
