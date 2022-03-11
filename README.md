function calcAverage (valor1, valor2, valor3){
    return(valor1 + valor2 + valor3)
}
 
let avgDolphins = calcAverage(44,23,0);
let avgKoalas = calcAverage(44,29,78);

// criar função para o vencedor 

function checkWinner (avgKoalas, avgDolphins) {
     if (avgKoalas >= avgDolphins *2) {
         console.log("Os vencedores são os Koalas!!!");
         
     }else if(avgDolphins >= avgKoalas *2){
      console.log ("Os vencedores são os Dolphins!!!"); 
         
     }else {
         console.log ("Houve um empate!!!");
     }
}
checkWinner (avgKoalas, avgDolphins)
