# Funções e Funções assíncronas

* Funções em JavaScript:

Funções são blocos de código reutilizável que realizam tarefas específicas. São definidas usando a palavra-chave "function" seguida de 
um nome e parâmetros (opcional).Podem retornar valores usando a palavra-chave "return".

Veja um exemplo de função em javascript: 

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/50fa8561-6643-4d94-bad0-8b999c63e2a7)

Saída no console:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/ae3fd848-c03d-4c3f-8382-45200e1b0774)

* Funções Assíncronas em JavaScript:

Funções assíncronas permitem que tarefas demoradas sejam executadas sem bloquear a execução do código. São definidas com a 
palavra-chave "async" antes da palavra-chave "function". Dentro de funções assíncronas, podemos usar a palavra-chave "await" 
para esperar que promessas sejam resolvidas antes de continuar a execução. São úteis para lidar com operações demoradas, como 
solicitações de rede ou acesso a bancos de dados.

vamos ver um exemplo de aplicação de uma função assíncrona:

![image](https://github.com/samuelfrs/GTi-JS-Capacitacao/assets/81939929/5ce66320-ad39-420d-b31c-346b661049db)

Vamos supor que estamos fazendo uma requisição à alguma API, isso pode ser um processo demorado, então utilizamos essa funcionalidade para realizar isso.

# Principais diferenças

1) **Fluxo de Execução:** Funções síncronas executam sequencialmente, enquanto funções assíncronas podem continuar a executar outras tarefas enquanto aguardam operações assíncronas.
2) **Promessas:** Funções assíncronas frequentemente usam promessas para representar operações assíncronas, permitindo melhor controle sobre o fluxo de execução.
3) **Await:** O uso de "await" é exclusivo das funções assíncronas e permite esperar a conclusão de uma promessa antes de continuar a execução.
4) **Callbacks vs. Async/Await:** Funções assíncronas simplificam o tratamento de código assíncrono em comparação com o uso de callbacks aninhados.

## Finalização

Em resumo, funções em JavaScript são blocos de código reutilizáveis que executam tarefas específicas, enquanto funções assíncronas são usadas para lidar com operações demoradas de forma eficiente, permitindo que o código continue a ser executado de forma assíncrona usando promessas e "await".

Por hoje agora é isso. No próximo módulo iremos aprender a interagir com o HTML utilizando o DOM e após isso vocês estarão aptos a realizarem o desafio proposto aqui na capacitação. Boa sorte :)
