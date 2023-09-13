![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/a348d1c7-1a9f-4308-914a-572ace3f53b5)# Export e Import

Em JavaScript, import e export são palavras-chave usadas para trabalhar com módulos, que são uma maneira de organizar e reutilizar código em um programa JavaScript. Os módulos ajudam a dividir o código em partes menores e mais gerenciáveis, tornando-o mais modular e fácil de manter.

Vamos suport uma situação: Estamos em um projeto em código puro, apenas HTML, CSS e JS. E nele, temos algumas várias funções que precisaremos usar. Tudo em um arquivo só, fica poluído e muita informação que as vezes torna-se desnecessária, então nós fazemos um arquivo a parte, apenas para as funções e o importamos no arquivo principal, vamos ver um exemplo:

Primeiramente, crie um outro arquivo na sua pasta, o nome não importa muito, mas nesse módulo, criarei o arquivo com o nome de **funcs.js**, veja:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/32215ba3-6e9c-43ad-a94f-227609677480)

Após isso, vá no seu index.html e faça uma alteração no script importado lá, adicione uma propriedade **type="module"**. Veja abaixo:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/cc615622-ff07-4a60-8293-bd3cda8f8f31)

Agora vamos trabalhar.

1) **Exportação de Valores:** Você pode exportar valores (funções, variáveis, objetos) de um módulo para que eles possam ser usados em outros módulos. Para fazer isso, você utiliza a palavra-chave export seguida do que deseja exportar. Por exemplo:

Vá no arquivo funcs.js e faça o seguinte:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/43f4a039-a92c-4e9b-b129-7e56bed2d424)

Não se preocupe com a função existente ali, a fiz apenas para mostrar que o export/import funciona para valores e funções, o próximo módulo é ensinando sobre elas.

Na imagem, perceba que existe o comando **export** e **export default**, na realidade, apenas o export bastaria, mas vamo utilizar o default para podermos verificar algo mais a frente. O export serve para informar ao código que você deseja exportar aquele elemento para fora daquele arquivo.

Após isso, vá para seu script.js e realize o import da variavel e da função da seguinte maneira:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/9044fa8b-8ccb-4caa-8c12-6afd79bde565)

Perceba que variável foi importada entre chaves. Vamos entender a diferença:

**export:** Com o export, você pode exportar várias funcionalidades de um módulo, nomeadas ou não, que podem ser importadas em outros módulos usando chaves {} para especificar quais funcionalidades você deseja importar.

**export default:** Com o export default, você exporta uma única funcionalidade (ou valor) como a exportação padrão do módulo. Você pode ter apenas uma exportação padrão por módulo. Ao importar, você pode dar a ela o nome que preferir.

Vamos rodar o código para ver o que nos é devolvido no console:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/700956f1-df88-4254-a974-291e26b5f084)

Perceba que a função foi executada, sem estar declarada no arquivo js principal, e a variável exibida sem também estar declarada lá, apenas importada.

## Finalização

Isso não funciona apenas para arquivos locais ou criadas por você no seu computador. Também é possível importar funções, bibliotecas e funcionalidades que outras pessoa fizeram e deixaram livres para uso. Essa funcionalidade do JS é bastante útil, principalmente quando estamos trabalhando com frameworks mais complexos, como o REACT.

Por hoje é só, vamos para o próximo módulo :)







