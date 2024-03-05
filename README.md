# JS-exercises---Rocketseat
Exercícios de JS do curso da Rocketseat - (JS exercises from the Rocketseat course)

// 1. Declare uma variável de nome weight 


/*let weight
const weight
var weight
// 2. Que tipo de dado é a variável acima? 
undefined
console.log(typeof weight)
*/


/* 
    3. Declare uma variável e atribua valores para cada um dos dados 
    * name: String 
    * age: Number (integer)
    * stars: Number (float)
    * isSubscribed: boolean 
*/

/*
let name = "Vincius"
let age = 16
let stars = 15.9
let isSubscribed = true 

*/

/* 
    4. A variável student abaixo é de que tipo de dados? 

    4.1 Atribua a ela as mesmas propriedades e valores

    4.2 Mostre no console a seguinte mensagem: 

    <name> de idade <age> pesa <weight> kg.

    Atenção substitua <name> <age> e <weight> pelos valores de cada propriedade do objeto   
*/

/*
let student = {

    name: "Vincius",
    age: 16,
    weight: 64.9,
    isSubscribed: true  

    console.log('${student.name} de idade ${student.age} pesa ${student.weight} kg.')
}
*/


/* 
    5. Declare uma variável do tipo Array, de nome 
    students e atribua a ela nenhum valor, ou seja, 
    somente o Array vaizo
*/

let students = []

/* 
    6. Reatribua valor para a variável acima, colocando 
    dentro dela o objeto student da questão 4. (Não 
    copiar e colar o objeto, mas usar o objeto criado
    e inserir ele no Array) 
*/

/* 



*/

/*
students = [
    student
]

console.log(students)
*/


/*

    7. coloque no console o valor da posição zero do Array acima

*/

// console.log(students[0])

/* 
    8. Crie um novo student e coloque na posição 1 do Array students
*/

/*
const Vinicius = {
    name: "Vinicius",
    age: 23,
    weight: 74.8, 
    isSubscribed: true,
}

students = [
    student, 
    Vinicius
]

// ou students[1] = Vinicius

console.log(students)

*/

/*
    9. Sem rodar o código responda qual é a resposta do 
    código abaixo e por que? Após sua resposta, rode o 
    código e veja se você acertou.

    console.log(a)
    var a = 1 
*/

// vai imprimir no console.log um undefined pois a variavel (a) ainda não está criada quando foi alí, só que ela vai sofrer um hoisting(elevação), então ela vai subir o var e o var somente declarado, torna-se undefined. Vai chegar como undefined e só depois recebe o 1. 
