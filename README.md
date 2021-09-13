var peso = 110
if (peso > 100){
    console.log('Erro! O peso da peça não pode ser maior do que 100g')
}
else {
    console.log ('Cadastro permitido!')
} 

const caixa = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11]
if (caixa < 10){
    console.log("Erro! Quantidade de peças superior a 10. Não há capacidade suficiente")
}
else{
    console.log("Cadastro aprovado")
}



const peças = ['p1', 'peça2', 'peça003']

if (peças.length >=3){
    console.log('Peça aprovada')
}
console.log ('Quantidade de caracteres')

for (let index = 0; index < peças.length; index ++){
    const atual = peças[index];
    if (atual.length < 3){
        console.log(atual + ' : a peça possui nome inferior a 3 caracteres e não pode ser cadastrada.')
    }else {
        console.log (atual + ' : a peça pode ser cadastrada.')
    }
}
