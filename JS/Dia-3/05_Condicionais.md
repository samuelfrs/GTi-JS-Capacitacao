# Condicionais

Vamos começar a entrar mais nos conceitos de programação, partindo das condicionais. Vocês já viram elas em cadeiras de programação,
mas resumidamente temos **if**, **else** e **else if**.
* if: SE...
* else: SE NÃO...
* else if: "SE NÃO SE"...

Vamos por em prática cada um:

* if:

Vemos que aqui eu fiz uma validação de um dado X, lendo o código temos:
Se x for maior ou igual à 5, ele dirá no console o a string atrelada ao true, se não, ele dirá a string atrelada ao false
![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/6fa017a1-02b7-4108-974c-5324bd3b0b2f)

Saída no console:

Veja que ele ignorou completamente o **else**, tendo em vista que a condição era verdadeira
![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/7e1ba27c-c36c-4e5c-b395-490989102727)

* else:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/9bd20be2-2a8f-4e24-a2d7-4efea640a581)

Saída no console:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/31b26961-810a-47b4-8657-5c9dca35cc3c)

* else if:

Aqui temos uma situação peculiar, o else if é um outro if, só que atrelado a condicional no if anterior, vamos analisar:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/56725d93-60f4-4c23-8870-1344e7b2ad91)

Saída no console:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/efc74295-8a97-4d11-8d5a-a3ffdd94a2b9)

O poder das condicionais são absurdos, você pode fazer várias coisas com elas, desde validações de dados à jogos simples.

## Shorthands

Shorthands condicionais, também conhecidos como operadores ternários, são construções em JavaScript que permitem que você avalie uma expressão condicional de forma concisa e retorne um valor com base nessa condição. Eles são frequentemente usados para atribuir valores com base em uma condição em uma única linha de código. Segue a seguinte sintaxe: **condição ? true:false**. Vamos aplicar em um código para entender:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/f0073c60-bfeb-4fe5-9031-c6a0edf19793)

Ele exibirá isso no console:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/99d0455b-fe57-44b1-afcb-69cc9f2ecbdc)

experimente trocar o valor de x para false, e veja o console.




## Finalização

Por esse módulo é apenas isso, condicionais são de fácil aplicação, mas busque fazer outros tipos de validações, como por exemplo, verificações de condições booleanas para saber se um certo usuário tem permissão de acessar um painel (Faça apenas a lógica simples)
