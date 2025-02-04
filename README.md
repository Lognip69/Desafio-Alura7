function Imc(Peso, Altura){
    let imC = Peso / (Altura * 2)
    return imC.toFixed(2) //<--- Esse parametro reduz as casas decimais com base no numero passado nos ()
}
let Peso = prompt('Quanto você pesa?')
let Altura = prompt('Quanto você tem de altura?')
let IImc = Imc(Peso, Altura)
console.log(`Pesando ${Peso} e com ${Altura} de altura e`)
if (IImc < 18.5){
    console.log(`Com o imc de ${IImc} vccê está em Magresa Extrema`)
} else if (IImc >= 18.5 && IImc <= 24.9){
    console.log(`Com ${IImc} vccê está com imc Normal`)
} else if (IImc > 24.9 && IImc <= 30){
    console.log(`Com o imc de ${IImc} vccê está com Sobrepeso`)
} else{
    console.log(`Com o imc de ${IImc} vccê está Obeso`)
}
//------------------------------------------------------------------------------------------------

function fatorial(numero){
}
fatorial(4)


function valorDolar(dolar){
    let valor = dolar * 4.80
    return valor
}
valorDolar(32)

function calculoAreaPerimetro(altura, base){
    let perimetro = 2 * (base + altura)
    let area = base * altura
    console.log(perimetro) 
    console.log(area)
}
calculoAreaPerimetro(10, 5)

function calculoAreaCirculo(raio){ 
    area = 3.14 * raio**2 //<--- serve pra calcular a exponencial
    console.log(area)
}
calculoAreaCirculo(5)

function tabuada(numero){
    contador = 10
    while (contador > 0){
        let tabu = numero * contador
        console.log(`${numero} X ${contador} = ${tabu}`)
        contador--
    }
}
tabuada(10)
