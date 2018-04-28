# Desafio da semana #2

Nesse exercício, você está livre para escolher os nomes para suas variáveis e funções! :smile:

```js
// Crie uma função que receba dois argumentos e retorne a soma dos mesmos.
function soma(x,y){
  return x + y;
}

// Declare uma variável que receba a invocação da função criada acima, passando dois números quaisquer por argumento, e somando `5` ao resultado retornado da função.
var myvar = soma(4,5) + 5;

// Qual o valor atualizado dessa variável?
14

// Declare uma nova variável, sem valor.
var myvarda;

/*
Crie uma função que adicione um valor à variável criada acima, e retorne a string:
    O valor da variável agora é VALOR.
Onde VALOR é o novo valor da variável.
*/
function myvardaVal(){
  return 'O valor da variável é: ' + 20;
}

// Invoque a função criada acima.
myvardaVal();

// Qual o retorno da função? (Use comentários de bloco).
?
*/
'O valor da variável é: 30'
*/

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos;
2. Se qualquer um dos três argumentos não estiverem preenchidos, a função deve retornar a string:
    Preencha todos os valores corretamente!
3. O retorno da função deve ser a multiplicação dos 3 argumentos, somando `2` ao resultado da multiplicação.
*/
function myFunction(x, y, z){
    if(x == null && x == undefined){
        return 'Preencha todos os valores corretamente!';
        };
    
     if(y == null && y == undefined){
            return 'Preencha todos os valores corretamente!';
        };
    
    if(z == null && z == undefined){
            return 'Preencha todos os valores corretamente!';
        };
	return (x * y * z) + 2;
};

// Invoque a função criada acima, passando só dois números como argumento.
myFunction(4,5);

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
"Preencha todos os valores corretamente!"

// Agora invoque novamente a função criada acima, mas passando todos os três argumentos necessários.
myFunction(4,5,4);

// Qual o resultado da invocação acima? (Use comentários para mostrar o valor retornado).
//82

/*
Crie uma função com as seguintes características:
1. A função deve receber 3 argumentos.
2. Se somente um argumento for passado, retorne o valor do argumento.
3. Se dois argumentos forem passados, retorne a soma dos dois argumentos.
4. Se todos os argumentos forem passados, retorne a soma do primeiro com o segundo, e o resultado, dividido pelo terceiro.
5. Se nenhum argumento for passado, retorne o valor booleano `false`.
6. E ainda, se nenhuma das condições acima forem atendidas, retorne `null`.
*/
function myFunctionIsBack(x, y, z){
    if(x != null || x != undefined){
	    if(y != null || y != undefined){
		 
   			 if(z != null || z != undefined){
            return (x + y) / z;
       	
			 };
			
            return x + y;
        };
       
		 return x;
        };
	if(x == null && y == null && z == null){	
    
		return false;
    };
	
return null;
};

// Invoque a função acima utilizando todas as possibilidades (com nenhum argumento, com um, com dois e com três.) Coloque um comentário de linha ao lado da função com o resultado de cada invocação.
myFunctionIsBack(); // false
myFunctionIsBack(4) //4
myFunctionIsBack(4)
myFunctionIsBack(4,6)//10
myFunctionIsBack(4,6,2)//5
```
