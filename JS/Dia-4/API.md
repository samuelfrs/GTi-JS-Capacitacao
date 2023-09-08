# API e tratamento de dados json

Quando estamos trabalhando em um projeto, como o de um sistema, que temos muitas informações indo e vindo, costuma-se trabalhar com uma
API, que é a sigla para "Application Programming Interface" (Interface de Programação de Aplicativos, em português). É um conjunto de 
regras e protocolos que permite que diferentes softwares se comuniquem entre si. Em termos simples, uma API define como componentes de 
software devem interagir.

O arquivo json funciona como se fosse o dicionário utilizado entre a linguagem do Front-end e a linguagem do Back-end para se comuni-
carem entre sí quanto às informações do banco de dados.

Vamos buscar entender como podemos chamar uma API no nosso código, e após isso, vamos tentar exibir alguma informação dela na tela
pela primeira vez.

Antes, quero explicar o que é Promise(Promessa), then e catch

1) **Promessa:** Uma Promessa (Promise) em JavaScript é um objeto que representa a eventual conclusão (ou falha) de uma operação assíncrona. Ela é usada para lidar com tarefas assíncronas de forma mais limpa e eficaz, tornando o código mais legível e fácil de manter. As Promessas são especialmente úteis quando se trabalha com operações como solicitações de rede (por exemplo, solicitações HTTP), leitura/gravação de arquivos e qualquer outra tarefa que possa levar algum tempo para ser concluída.
2) **then:** O método then é usado para definir o que deve acontecer quando uma Promessa é resolvida com sucesso, ou seja, quando a tarefa assíncrona é concluída com sucesso e produz um valor.
3) **catch:** O método catch é usado para lidar com erros que ocorrem durante a execução de uma Promessa. É uma maneira mais concisa de lidar com erros do que passar a segunda função para o método then.

**Método fetch:**

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/a9acf7b8-5003-4191-b9e6-ec0a504ec6ea)

Vamos buscar entender cada linha e informação presente no código:

linha 1: utilizamos a função fetch para realizar uma soliticação HTTP na url informada no seu parâmetro. Então nos é retornado uma 
resposta, chamada **Response** ou **res**.

linha 2: utilizamos o método then que ao pé da letra significa "então" para pegarmos essa resposta **(que chamaremos de res a partir 
daqui)** para fazermos uma validação. O res, vem com algumas coisas, vamos ver:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/04c9afc7-53f8-47bb-aead-8d82426c8363)

Coloque esse console.log(res) nesse exato local e veja no console o que aparece:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/0c4f1e41-e9d3-4ac6-b744-58a1c3faa981)

Esse ok serve como o parâmetro de validação do resgate das informações da API nesse caso. na ocasião ele tem o valor de true, ou seja,
a requisição foi um sucesso. Tente colocar na url do fetch algo como users/100000 no final. Você verá que retornará um **ok: false**
Então vamos continuar **(Lembre-se de apagar o console.log(res), pois quando informo as linhas estou me baseando na da primeira
imagem)**:

linha 3: nessa linha realizamos a validação do resgate dos dados que falei acima, utilizamos a condicional if para validarmos se os
dados estão corretos. essa linha pode parecer confusa porque você não viu o if sendo utilizado dessa maneira no módulo anterior. Mas
vamos entender o que acontece:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/5821f59e-8201-4d73-947c-adbd85f87a6c)

Nessa imagem temos uma validação parecida com o que ocorre na requisição. Nela temos uma variável booleana X que possui o valor de true
e abaixo temos uma condicional estranha a princípio, mas saiba que as condicionais se lêem da seguinte forma:

**if(condição verdadeira){**

faça o que estiver aqui

**}**

**else{**

faça o que estiver aqui

**}**

Vamos voltar ao entendimento do código:

linha 4: Como a validação foi avaliada como verdadeira, entramos no if e vemos que na linha 4 temos um **return res.json()**, isso
serve para transformarmos a resposta da requisição em um arquivo JSON, que pode ser entendido pelo front e back end e lido por nós,
humanos. Vale citar que a resposta dessa operação é uma **data** que será usada mais para frente

linha 6 e 7: Agora caso a requisição não ocorra com sucesso, essa linha servirá para exibir no console a mensagem error, que indicará 
que algo não correu com sucesso.

linha 10: Aqui temos outro método then. Aqui utilizaremos a resposta da lnha 4 (**data**) para exibirmos o que quisermos do conteúdo
da API, nesse caso eu coloquei data.data porque quero apenas as informações dos usuários.

linha 11: aqui temos o método catch, que é algo novo. Ele é usado para o código saber o que fazer quando lidar com erros que ocorrem 
durante a execução de uma promessa. Então pegamos a possível resposta de erro que é **err** e exibimos no console.

E ao rodarmos o código, teremos no console o seguinte:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/dcff71d7-59be-461d-adfd-93d245cceafd)

Isso é os dados da API de usuários, utilizaremos eles mais a frente para exibirmos no backend, então não apague esse código do
seu script.js

## Finalização

Bem pessoal, esse módulo foi meio massivo porque realmente Consumo de API é algo muito importante no nosso contexto atual. Busquem
se aprimorar bastante no entendimento do que foi passado aqui e testem com outras API's. Se divirtam e nos vemos na próxima :D
