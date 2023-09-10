# Array

Um array é uma estrutura de dados que permite armazenar uma coleção de valores em uma única variável. Esses valores podem ser de qualquer tipo de dado, como números, strings, objetos, funções e até mesmo outros arrays. Os arrays em JavaScript são conhecidos por serem flexíveis e dinâmicos, o que significa que você pode adicionar, remover e modificar elementos facilmente durante a execução do programa. 

## Como se cria um array?

Você pode criar um array em JavaScript de várias maneiras. Aqui estão alguns exemplos:

1) Notação de colchetes:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/39ee40f4-7b30-415d-b390-31d31425a082)

2) Usando o construtor Array():

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/d1fa0eaf-7850-499c-9c3d-77475f5023fe)

Veja no seu console como é a saída de cada array criado das duas formas, será a mesma coisa.

## Acessando elementos específicos de um array

Você pode acessar os elementos de um array usando um índice baseado em zero. Por exemplo, para acessar o primeiro elemento de um array, você usaria array[0], e para o segundo elemento, array[1], e assim por diante.

Vamos montar um código que exibirá na tela apenas os itens de um array de números que são pares. Vamos utilizar conhecimentos de módulos anteriores, então se você não entendeu algo, sugiro que volte e reveja melhor, ou pergunte a alguém da diretoria de projetos.

Código:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/3ae79c1b-50f6-412b-9b66-20e8cfb81a01)

Saída no console:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/7c1a2c3d-11aa-4b7a-bc14-d53d5030e1c7)

Vamos entender cada linha:

linha 1): Aqui nós declaramos o array **numeros** com 10 itens dentro, de 1 a 10.

linha 3): Aqui faremos um laço de repetição para ele percorrer por todo o array, vamos aos parâmetros utilizados em cada parte. partimos do i = 0, indo até o **numeros.length** que é um método de array para retornar o tamanho do mesmo, ou seja, nesse caso é 10. Depois realizamos um incremento de 1 na variável i a cada ciclo rodado no for.

linha 4): Aqui, a cada ciclo for realizamos uma validação se o número da vez é par ou não com a condição do resto da divisão por 2 de i ser igual a zero. Isso significaria que o número é par.

linha 5): Retornamos no console o número.

Nós realizamos provavelmente um código que TALVEZ você não entenda o motivo agora, mas isso em projetos é muito útil, porque as vezes queremos exibir alguns certos itens de um array que atendem a algumas condições específicas.

## Mais outros métodos do array

Assim como o resto do JS, o array é muito vasto e sua utilidade é imensa, então vamos conhecer alguns dos métodos mais úteis dos arrays:

* .push

Esse método serve para adicionar algum item novo ao final do array, veja: 

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/bf4ea75b-dfb3-4f40-b97a-d3c5ebb22a49)

Saída no console:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/83481b7d-644f-4f38-bf89-23c6fa90dd3e)

* .pop

Esse método remove o último item do array:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/13264a1b-a98f-4519-9ffc-8bc2d23011cb)

Console:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/8de4cb8a-d48c-4f3b-85ae-6434b8be1733)

* .shift

O método shift remove o primeiro elemento de um array e retorna esse elemento removido. Ele também modifica o array original, fazendo com que todos os elementos subsequentes se movam uma posição para a frente. Se o array estiver vazio, o método shift retornará undefined. Veja:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/5b951580-7abb-4dd0-a3b1-a1354cd16806)

Console:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/86e79652-badf-48f7-8edb-eae0fada3e91)

* .unshift

O método unshift adiciona um ou mais elementos ao início de um array e retorna o novo comprimento do array. Ele também modifica o array original. Veja:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/f6ee146f-1520-4802-91f4-7ba63d8ff75f)

Console:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/2395f563-5db2-4371-b606-53d0e3747bb1)

* .lenght

Esse método foi utilizado no começo do módulo para realizar o código de retornar se é par. mas ele resumidamente serve para informar o tamanho de um array. Veja:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/3314e4b5-b872-47cd-a6b3-d0cd08659f0a)

Console:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/16589120-7910-44f7-976d-e405f3fc1874)

* .map

O método map é uma função de alta ordem em JavaScript que é usada em arrays para criar um novo array com base em uma transformação aplicada a cada elemento do array original. O novo array resultante terá o mesmo comprimento do array original, mas cada elemento será o resultado da aplicação de uma função a um elemento correspondente do array original. O método map não modifica o array original, ele cria um novo array com os resultados da transformação. Veja um exemplo:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/b9ec2259-7a72-4792-9e70-83ee6bd188cb)

Saída no console:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/934c46fc-f501-4eff-89fe-5f38f47ae1c6)


* .filter

O método filter é outra função de alta ordem em JavaScript que é usada em arrays para criar um novo array contendo todos os elementos do array original que atendem a um critério específico. Ele não modifica o array original, mas cria um novo array com os elementos filtrados. O resultado é um subconjunto do array original contendo apenas os elementos que satisfazem a condição definida. Veja um exemplo:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/80e2444e-0ed9-4f4e-8d34-5fc3aa531fd2)

Perceba que isso é outro método de fazer o primeiro código desse módulo. Existem infinitas formas de chegar no mesmo resultado com programação.

Saída no console:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/49baa3ae-b7d6-4281-b4df-fb34b42ece2b)

* .forEach

O método forEach é útil quando você precisa realizar uma operação específica em cada elemento de um array, mas não precisa criar um novo array ou modificar o array original. Pode ser usado para várias tarefas, como exibir elementos em uma interface de usuário, calcular estatísticas simples ou realizar outras operações personalizadas em cada item da coleção. Veja:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/bba8c127-52d8-41f8-bf8f-e216872df351)

Saída no console:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/cf0e98c5-4c27-4dd7-ba48-c2ee0d413302)

## Finalização

Por hoje é só, vocês aprenderam os métodos mais importantes dos Arrays, então pratiquem e vejam por si só o que podem fazer com isso. Nos vemos na próxima :D






