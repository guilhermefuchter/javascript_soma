# javascript_soma

function somarNumeros(numero1, numero2) {
  return numero1 + numero2;
}
const resultado = somarNumeros(5, 3);
console.log(resultado);





function multiplicarNumeros(numero1, numero2) {
  return numero1 * numero2;
}
const resultado = multiplicarNumeros(4, 7);
console.log(resultado);



function dividirNumeros(numero1, numero2) {
  if (numero2 !== 0) {
    return numero1 / numero2;
  } else {
    return "Não é possível dividir por zero.";
  }
}

const resultado1 = dividirNumeros(10, 2);
console.log(resultado1); // Isso imprimirá 5

const resultado2 = dividirNumeros(8, 0);
console.log(resultado2);
