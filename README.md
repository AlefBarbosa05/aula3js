function calcularMediaGolfinhos(num1, num2, num3) {

    return `A média geral dos golfinhos é: ${( num1 + num2 + num3) / 3}`; 
}

function calcularMediaCoalas(num4, num5, num6){

    return `A média geral dos coalas é: ${( num4 + num5 + num6) / 3}`; 
}
 
let mediaGolfinhos = calcularMediaGolfinhos (10,10,10);

let mediaCoalas = calcularMediaCoalas(12,12,6);

console.log(mediaGolfinhos, mediaCoalas);

