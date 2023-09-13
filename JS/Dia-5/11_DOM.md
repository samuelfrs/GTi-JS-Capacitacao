# DOM

O DOM (Document Object Model) é uma representação hierárquica em forma de árvore de um documento HTML ou XML que permite ao JavaScript 
interagir com a estrutura e conteúdo de uma página da web. O DOM é uma parte fundamental da programação web, pois permite que os 
desenvolvedores acessem, manipulem e atualizem elementos HTML, estilos, atributos e eventos em uma página da web.

Como você pode interagir com o DOM usando JavaScript:

1) **Árvore Hierárquica:** O DOM representa uma página da web como uma árvore hierárquica de objetos. O nó raiz é o documento HTML e
os nós subsequentes representam elementos HTML, atributos, texto e outros conteúdos.

2) **Selecionar Elementos:** Você pode selecionar elementos HTML específicos no DOM usando métodos JavaScript, como
document.getElementById(), document.querySelector(), ou document.querySelectorAll().

Vamos ver um exemplo:

No seu index.html, faça uma tag h1 com o id de texto-principal. Desta forma:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/ad8178eb-3e92-4c5a-a20d-041dbc6d803e)


Perceba que não mudou nada visualmente no seu index, então vamos trabalhar nisso.

No seu script, faça o seguinte:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/53d10f79-ac2f-4135-a0d2-f6da6cbe2de1)

Agora veja o seu html, é para ter o seguinte:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/415c41f6-fd16-4dc2-80e2-180b0e9a2b45)

Vamos entender o que foi feito:

1) atribuímos um id a tag **h1** vazia
2) no arquivo js, atribuimos esse id a uma constante utilizando métodos do DOM.
3) inserimos via js, com o método innerText, texto na tag que possui o id "texto-principal".

O mesmo pode ser feito com classes, vamos ver:

Crie mais de 1 parágrafo com a classe "texto-principal":

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/f72b712f-b7c9-40a1-a1b9-1f3d88bf348e)

Veja como deve ficar o HTML:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/08d0ca99-4b5a-42e9-abaa-22cfa1bbe87f)


No js, faça o seguinte:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/c96a07ba-3971-4a59-92be-77ad61532e55)

Atualize a página, e veja que o conteúdo irá mudar, veja:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/eab95ecc-b86f-48a1-b6a2-7aa030ab4aac)

## Outras funcionalidades do DOM:

Vamos ver outras funcionalidades do DOM:

1) **Manipular Elementos:** Uma vez selecionados, você pode manipular elementos do DOM de várias maneiras. Isso inclui a alteração
de conteúdo de texto, modificação de atributos, adição ou remoção de elementos e muito mais.

Aqui estão alguns exemplos:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/e0ae5ae7-8000-44b4-b62f-b39dfb6d9e98)

2) **Manipular Estilos:** Você pode manipular os estilos de um elemento no DOM usando a propriedade style.

Por exemplo:

Texto antes de aplicar o método do DOM:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/2dbab28e-16c6-4e70-a9bb-b7550aadb67d)

Aplicando:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/2222b60a-ac13-4873-8e9d-f352f9565d3f)

Como deve ficar:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/2056ca01-0871-4a6a-84e5-ab7871fa0c02)

3) **Responder a Eventos:** O DOM permite que você responda a eventos do usuário, como cliques, pressionamentos de teclas e
movimentos do mouse. Você pode usar o método addEventListener para associar funções de tratamento de eventos a elementos
específicos.

Exemplo:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/43bc7263-194e-4bf5-803e-e0a37c8fd6b8)

O que deve acontecer, é quando você clicar no elemento, ele irá exibir um alerta do navegador, veja:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/345bb40e-a216-447f-87e9-7a3059271679)

## Finalização

Bem pessoal, Acabamos por aqui, agora vocês irão realizar um pequeno desafio colocando tudo isso em prática para se aperfeiçoarem.
Vejam adiante. Boa sorte :)
























