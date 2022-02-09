# Projeto Trybe
Código feito no desafio prático da trybe

## Calculadora adição e subtração
Neste desafio, você deve implementar a função calculadoraAdicaoSubtracao, que:
- recebe 3 argumentos: sendo os dois primeiros números inteiros, **numero** e **outroNumero**, e o terceiro **operacao**, sendo uma string "+" ou "-";
- retorna um valor dependendo da operação:
   - se **operação** é "+", então retorna a soma do **numero** com o **outroNumero**.
   - se **operação** é "-", então retorna a subtração do **numero** com o **outroNumero**.
   - se **opração** não é nenhuma das operações esperadas, então retorna o valor **0**.


### Solução
function calculadoraAdicaoSubtracao(numero, outroNumero, operacao){

if(operacao == "+"){

   return numero + outroNumero;
   
}else if(operacao == "-"){

   return numero - outroNumero;
   
}else{

   return 0;
   
}

}


## Vezes que uma letra aparece
Neste desafio, você deve implementar a função vezesLetraAparece, que:
- recebe 2 parâmetros: **frase**, que deve ser uma string;
- retorne o número de vezes que **letra** aparece na **frase**;


### Solução 
function vezesLetrasAparece(frase, letra){

var letrasIguais = 0;

for(var indice = 0; indice <= frase.length -1; indice++){

    if(frase[indice] == letra){
    
       letrasIguais++;
    }else{
    
       continue;
    }
    
    return letrasIguais;
}

}
