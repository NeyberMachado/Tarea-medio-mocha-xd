-- 'Declaracion de variable'

let minombre = "neyber"; console.log("mi nombre es :", minombre);
const fechaDenacimiento = "2004-07-10"; console.log("mi fecha de nacimientos:", fechaDenacimiento);
const añoatual = "2025-27-9"; console.log("año atual:", añoatual);
let conts 'Ejercicio 2: Operadores y Condicionales'


'operadores y condicionales'

let edad = Number(prompt('Cuántos años tienes'));
if (edad >= 20) {
  console.log('Eres mayor de edad.');
} else {
  console.log('Eres menor de edad.');
}

'manipulacion de strings'

let nombre = prompt('Cuál es tu nombre');
let apellido = prompt('Cuál es tu apellido');
let nombreCompleto = ${nombre} ${apellido}.toUpperCase();
console.log(nombreCompleto);

'bucle for basico 10'

for (let i = 1; i <= 10; i++) {
  console.log(i);
}

'condicionales anidados'

let nota = Number(prompt("¿Cuál es tu nota? (0-10)"));
if (nota >= 0 && nota < 50) {
  console.log("Suspenso");
} else if (nota >= 50 && nota < 70) {
  console.log("Aprobado");
} else if (nota >= 70 && nota < 90) {
  console.log("Notable");
} else if (nota >= 90 && nota <= 100) {
  console.log("Sobresaliente");
} else {
  console.log("Nota no válida");
}
