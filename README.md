# Teste Prático para Vaga de Estágio em Desenvolvimento de Software

## _Leia atentamente!_

Este teste prático tem como objetivo avaliar a familiaridade do candidato com as tarefas de desenvolvimento de software. As proposições **não são, necessariamente, eliminatórias**, mas servem para entender o nível de conhecimento e a capacidade de resolução de problemas do candidato.

**Regras Gerais:**
- É permitido consultar a internet durante o teste.
- É permitido o uso de assistentes de IA (como ChatGPT, Copilot, etc.).
  - **IMPORTANTE**: Caso utilize assistentes de IA, **copie e cole os prompts** utilizados para gerar as respostas.
- O candidato pode utilizar a linguagem de programação de sua preferência.
- O teste está dividido em três etapas, cada uma com foco em uma área específica.
- Escolha a linguagem que você tem mais familiaridade para resolver os desafios.
- Todas as aplicações devem ser executáveis e testáveis pelo terminal (__console application__) ou em um ambiente web (__web application__).
  
**Linguagens disponíveis\*:**
- Python 3.12
- JavaScript (Node/Bun)
- TypeScript (Bun)
- Java 17
- C# 12 (dotnet 8)
- Dart 3.7.0

**IDE Recomendada:**
- Visual Studio Code

*Se a linguagem de sua preferência não estiver listada, entre em contato para verificar a possibilidade de utilizá-la.

---

### Duração prevista: __1 hora e 30 minutos__

---

## Etapa inicial: Faça um clone deste repositório
##
```bash
git clone https://github.com/rodrigoraraujo/internship-practical-test.git
```

## Etapa 1: Avaliação de Lógica de Programação

Nesta etapa, o objetivo é avaliar a capacidade do candidato em resolver problemas de lógica e algoritmos.

### Desafio 1: Soma de Números Pares
Escreva um programa que receba uma lista de números inteiros e retorne a soma de todos os números pares presentes na lista.

**Exemplo:**
- Entrada: `[1, 2, 3, 4, 5, 6]`
- Saída: `12` (2 + 4 + 6)

### Desafio 2: Fatorial
Escreva uma função que calcule o fatorial de um número inteiro não negativo.

**Exemplo:**
- Entrada: `5`
- Saída: `120` (5! = 5 * 4 * 3 * 2 * 1)

### Desafio 3: Palíndromo
Escreva uma função que verifique se uma string é um palíndromo (ou seja, se ela é a mesma quando lida de trás para frente).

**Exemplo:**
- Entrada: `"arara"`
- Saída: `true`

---

## Etapa 2: Conhecimento em Linguagem de Programação

Nesta etapa, o objetivo é avaliar o conhecimento do candidato em uma linguagem de programação específica (à sua escolha).

### Tarefa 1: Manipulação de Arrays
Escreva um programa que:
1. Crie um array com 5 elementos:
    - `["a", "b", "c", "d", "e"]`
    - **Dica:** Utilize a estrutura de dados de sua linguagem de programação.
2. Adicione um novo elemento ao final do array.
3. Remova o primeiro elemento do array.
4. Inverta a ordem dos elementos do array.
5. Imprima o array resultante.

### Tarefa 2: Funções e Escopo
Escreva uma função que receba dois números como parâmetros e retorne a soma deles. Em seguida, crie uma variável global e uma variável local dentro da função para demonstrar o entendimento de escopo.

### Tarefa 3: Tratamento de Erros
Escreva um programa que tente dividir dois números. Caso ocorra uma divisão por zero, capture o erro e exiba uma mensagem amigável ao usuário.

---

## Etapa 3: Conhecimento do Ambiente Web

Nesta etapa, o objetivo é avaliar o conhecimento do candidato em desenvolvimento web, incluindo HTML, CSS, JavaScript e interação com APIs.

### Tarefa 1: Criar uma Página Web
Crie uma página HTML simples que contenha:
- Um título (`<h1>`).
- Um parágrafo (`<p>`).
- Um botão que, ao ser clicado, exiba um alerta com a mensagem "Olá, Mundo!".

### Tarefa 2: Consumir uma API
Utilize JavaScript para consumir uma API pública (por exemplo, [JSONPlaceholder](https://jsonplaceholder.typicode.com/)) e exibir os dados retornados em uma lista na página.

**Exemplo:**
- Consuma a rota `https://jsonplaceholder.typicode.com/users` e exiba os seguintes dados do usuário em uma lista (`<ul>`):
- Nome (`name`)
- E-mail (`email`)
- Telefone (`phone`)
- Endereço (`address`) com a cidade (`city`) e o CEP (`zipcode`)

### Tarefa 3: Estilização com CSS
Adicione estilos CSS à página criada na Tarefa 1 para:
- Centralizar o conteúdo na página.
- Alterar a cor de fundo do corpo da página.
- Estilizar o botão com bordas arredondadas e uma cor de fundo diferente.

---

## Instruções Finais

1. Organize seu código em pastas e arquivos separados para cada etapa.
2. Envie o código final compactado em um arquivo `[SEU NOME COMPLETO].zip`.
3. Caso tenha utilizado assistentes de IA, inclua um arquivo `prompts.txt` com os prompts utilizados.

### **Boa sorte!**