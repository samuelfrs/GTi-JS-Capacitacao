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
* Array(Matriz)
* Symbol(Símbolo)
* BigInt(BigInteiro)

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




