function nomeCompleto(nome,sobreNome) {
    
return "O nome comoleto é: " + nome + " " + sobreNome;

}

nomeCompleto ("Alef", "Barbosa");

function media(num1, num2, num3) {

    return `A média geral é: ${( num1 + num2 + num3) / 3}`; 
}

function media2 (num1, num2){
        return "A média é:" + (num1+num2)/2;    
}

let mediaSam = media2(12,45);

let mediaBlu = media(2,3,5);

let mediaJu = media(6,6,12);

console.log(mediaJu, mediaSam, mediaBlu);
