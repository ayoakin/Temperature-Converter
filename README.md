# TemperatureConverter

const kelvin = 300;

//the value of kelvin is constant

//Celsius = kelvin -273

const celsius = kelvin - 273;

//Fanrenhit = Celsius*(9/5)+32

let fahrenheit = celsius * (9 / 5) + 32;

//round off fahrenheit to whole number

fahrenheit = Math.floor(fahrenheit);

console.log(`The temperature is ${fahrenheit} degrees Fahrenheit`);

let newton = celsius * (33 / 100);

newton = Math.floor(newton);

console.log(`The temperature is ${newton} degrees Newton`);

console.log(`The temperature is ${celsius} degrees Celsius`);
