## Sintaxe básica: variáveis, tipos de dados, operadores.

Nesse módulo você aprenderá a sintaxe básica do JS. Vamos começar setando um projeto inicial. Vamos também misturar um pouco de HTML com JS a partir daqui.

1) Seguindo os passos do início, crie uma pasta nova e abra ela no Vscode.
2) Crie nela um arquivo chamado index.html e outro chamado script.js como na figura abaixo

no index.html escreva um exclamação e aperte enter na sugestão que o vscode der, ficará assim:
![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/3e722df3-6322-42d0-9edc-d8043513e630)

3) Vincule o arquivo js com o html da seguinte forma: no final da tag body no arquivo html, coloque uma tag script com o src(caminho) sendo o arquivo js. Veja na imagem:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/79844469-e834-4af6-8cd7-5c1bbbaf2e7a)

Agora seu arquivo js está vinculado com o html. vamos começar a brincadeira.

## Variáveis

Nas várias linguagens de programação, cada uma leva seus tipos de dados, algumas tem 5, outras 6 e por aí vai, mas nosso bom e velho JS possui apenas 3 tipos de variáveis, que são:

* var
* let
* const

Vamos explicar no que consiste cada uma:
1) var: é uma variável mutável, que será "ouvida" e conhecida no código todo. Isso ficará mais claro no futuro
2) let: também é uma variável mutável, mas a diferença é que ela sera ouvida e conhecida apenas no escopo em que se encontra, como um loop for por exemplo. Você entenderá melhor no futuro
3) const: é uma variável não mutável, ela é **constante**. Então o que for definido na sua inicialização, deverá ser aquilo até o final.

## Dados

* Number(Número)
* String(Texto)
* Boolean(Booleano)
* Undefined(Indefinido)
* Null(Nulo)
* Object(Objeto)
* Array(Array)
* Symbol(Símbolo)
* BigInt(int com mais bytes)

Você pode já conhecer algum ou todos, mas com o tempo iremos nos habituar a cada um ou pelo menos à grande maioria deles. Vamos então à um exemplo prático.

## Praticando

No seu arquivo html, ligue a extensão **Live server** clicando nela, no index.html

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/525ef698-f39c-4b23-9a98-5a95a753f347)

Após isso, será aberto no seu navegador uma página no localhost:3000. Isso é a extensão do liveserver, atualizando em tempo real as mudanças que ocorrem no código da página que você está trabalhando, mas como iremos mexer com javascript agora, algo não tão visual, iremos trabalhar no console. Então aperte f12 no seu teclado e vá em console. Ou clique com o direito na página e clique em inspecionar elemento, abrirá a mesma janela e você deve ir em console.

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/b3c2ed14-e659-4f7e-85de-40060d66f5c3)

Após isso, vá no seu arquivo JS e escreva o seguinte:

**Console.log é um comando para exibir alguma coisa no console, painel que estamos analisando no momento.**
![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/9b5abf4e-f612-4820-890d-677f3f9fe027)

Após isso será possível ver no console, o tipo de variável que é x, no caso undefined, por conta de não termos atribuido nenhum valor à ela. Vamos brincar mais um pouco, então faça como na imagem:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/61696e17-fac7-4209-8b28-612d111bc170)

Perceba que no console será exibido alguns dos tipos de dados que vimos anteriormente, perceba também que tanto int quanto float são reconhecidos como Number

## Operadores

Vamos para o próximo tópico que são os **operadores**. Eles se dividem em algumas categorias, que são:

* Operadores Aritméticos:
1) Adição (+)
2) Subtração (-)
3) Multiplicação (*)
4) Divisão (/)
5) Módulo (%)

* Operadores de Atribuição
1) Atribuição (=)
2) Atribuição de Adição (+=)
3) Atribuição de Subtração (-=)
4) Atribuição de Multiplicação (*=)
5) Atribuição de Divisão (/=)
6) Atribuição de Módulo (%=)

* Operadores de Comparação
1) Igual a (==)
2) Diferente de (!=) **Esse operador tem um ponto especial no **!** que consiste em uma negação, será explicada melhor mais para frente**
3) Estritamente igual a (===)
4) Estritamente diferente de (!==)
5) Maior que (>)
6) Menor que (<)
7) Maior ou igual a (>=)
8) Menor ou igual a (<=)

* Operadores Lógicos
1) E lógico (&&) o E é usado para validação de 2 ou mais condições, e só retornará True caso todas as condições sejam satisfeitas

2) OU lógico (||) o OU também é usado para validação de 2 ou mais condições e retornará True caso ao menos uma das x condições sejam satisfeitas

3) Negação lógica (!) a Negação verificará a condição e retornará o oposto do que deveria ser retornado, a visualização dele é mais complicada mas com o tempo você pega o jeito.c

* Outros Operadores **usados menos (com excessão do ternário), porém é importante saber da existência.**
1) Operadore ternário (?) **é uma condicional resumida**
2) typeof
3) instanceof
4) in
5) delete
6) new
7) Incremento (++)
8) Decremento (--)

Agora que temos conhecimento sobre os tópicos abordados nesse módulo, vamos fazer alguns testes:

* Operadores Aritméticos:

Uma explicação sobre o operador **Módulo**: Ele consiste no resto da divisão do x pelo y, no caso o resto da divisão de 10 por 10, como dá um número inteiro, ele retorna zero. Teste utilizando em uma divisão que não dê inteiro, como  10/3 por exemplo.

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/c9fcea49-90b3-4d11-a60b-05a04c70dcfb)

Essa deve ser a saída no console:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/7ed161b2-19cc-497c-b024-420eda6774cc)


* Operadores de Atribuição:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/31dc717a-62cf-46fc-96fe-f52a2c9bdd90)

Saída no terminal(**Observe que na operação do Módulo, a saída foi o resto da divisão, que no caso é 1**):

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/1fa00e5c-a97b-4056-8e6b-a5885df8b783)

* Operadores de Comparação:

A saída no console dos operadores de Comparação são resultados booleanos (True e false).

A respeito dos operadores **Estritamente igual e Estritamente diferente** é importante citar que são usados mais para validações do jeito do print. x e xstring têm 10 como valor, só que x é um **Number** e xstring é uma **String**, então acabam não sendo Estritamente iguais

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/ae24e9e9-1141-4166-b853-9a9690418140)

A saída no console deve ser:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/34a494fa-93b3-428e-bca4-ea824decf696)

* Operadores Lógicos:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/3ca4945e-1d9e-45a8-862a-a78c290c0b86)

Saída no console:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/0624d0d9-a97d-4326-aa46-80dbb6eb928a)


# Finalização

Acabamos por aqui. Eu fiz questão de em alguns momentos utilizar algumas coisas que talvez vocês não tenham pensado, como o uso do typeof para a validação do OU lógico. Isso foi com o intuito de vocês verem que esses operadores podem ser utilizados de diversas formas e nas mais variadas situações. Mas enfim, por hoje é só, futuramente teremos alguns exercícios, mas enquanto não temos, sintam-se à vontade para botar em prática o que vimos até aqui da forma que acharem melhor e lembrem-se: **Qualquer dúvida não hesitem em me chamar para sanar.** Bons estudos :D





