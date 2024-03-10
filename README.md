# calculadoraKM_L.emJS

 function calculadoraKM_L(){ 
    let consumoMedio = (prompt("informe o consumo medio?:"));
    let precoLitro = (prompt("informe o preço do litro?:"));
    let distancia = (prompt("informe a distancia em KM?:"));
    let litrosNecessario = distancia / consumoMedio ;
     let precoTotal = litrosNecessario * precoLitro;
     alert("o preço total para essa viagem é: R$"+ precoTotal);
     console.log(precoTotal);
 }
