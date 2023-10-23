**Plano de Estudo para Python e FastAPI - 1 mês**

**Semana 1: Básicos de Python**

*Dia 1: Introdução ao Python*
- Conceito: O que é Python?
- Exercício: Instale Python e configure o ambiente de desenvolvimento.

*Dia 2: Tipos de dados e Variáveis*
- Conceito: Inteiros, Strings, Listas, Dicionários, Tuplas, e Conjuntos.
- Exercício: Crie variáveis de cada tipo e faça operações básicas com elas.

*Dia 3: Controle de Fluxo*
- Conceito: if, elif, else, loops (for e while).
- Exercício: Escreva um programa que calcule o fatorial de um número.

*Dia 4: Funções e Módulos*
- Conceito: Definindo funções, parâmetros, retornos e importando módulos.
- Exercício: Crie uma função que retorne o maior elemento de uma lista.

*Dia 5: Manipulação de arquivos*
- Conceito: Leitura e escrita de arquivos.
- Exercício: Crie um programa que leia um arquivo e conte quantas vezes uma palavra específica aparece.

*Dia 6 e 7: Revisão e Prática*
- Repasse os conceitos aprendidos.
- Exercício: Crie um programa que gerencie uma lista de tarefas, permitindo adicionar e remover itens.

---

**Semana 2: Intermediário de Python**

*Dia 8: Compreensões de Lista e Dicionário*
- Conceito: Sintaxe e uso.
- Exercício: Crie listas e dicionários usando compreensões.

*Dia 9: Manipulação de Strings*
- Conceito: Métodos de string.
- Exercício: Crie um programa que inverta a ordem das palavras em uma frase.

*Dia 10: Classes e Objetos*
- Conceito: OOP em Python.
- Exercício: Desenvolva uma classe para representar um retângulo e calcular sua área.

*Dia 11: Tratamento de Exceções*
- Conceito: try, except, finally.
- Exercício: Escreva um programa que solicite ao usuário dois números e realize a divisão, tratando erros.

*Dia 12: Introdução a Bibliotecas*
- Conceito: Usando pip, instalação de bibliotecas.
- Exercício: Instale e experimente uma biblioteca de sua escolha.

*Dia 13 e 14: Revisão e Projeto Prático*
- Repasse os conceitos.
- Exercício: Crie um programa de calculadora que suporte adição, subtração, multiplicação e divisão, usando orientação a objetos.

---

**Semana 3: Introdução ao FastAPI**

*Dia 15: O que é FastAPI?*
- Conceito: Introdução e vantagens.
- Exercício: Instale FastAPI e crie um projeto inicial.

*Dia 16: Rotas e Parâmetros*
- Conceito: Definição de rotas, parâmetros de caminho e query.
- Exercício: Crie uma API que retorne informações sobre produtos baseados em parâmetros de pesquisa.

*Dia 17: Modelos Pydantic*
- Conceito: Uso de modelos Pydantic para validação e serialização.
- Exercício: Adicione modelos Pydantic ao projeto do dia anterior.

*Dia 18: Banco de Dados e FastAPI*
- Conceito: Integração com bancos de dados.
- Exercício: Integre um banco de dados SQLite ao seu projeto e crie rotas para CRUD.

*Dia 19: Autenticação e Segurança*
- Conceito: Autenticação básica e JWT.
- Exercício: Implemente autenticação na sua API.

*Dia 20 e 21: Revisão e Ampliação do Projeto*
- Revise conceitos.
- Exercício: Adicione mais recursos à sua API, como upload de imagens, categorização, etc.

---

**Semana 4: Avançado em FastAPI e Finalização**

*Dia 22: Testes em FastAPI*
- Conceito: Escrevendo e executando testes.
- Exercício: Escreva testes para todas as rotas da sua API.

*Dia 23: Documentação com FastAPI*
- Conceito: Utilizando a documentação automática.
- Exercício: Personalize a documentação da sua API e explore os endpoints.

*Dia 24: Middleware e Dependências*
- Conceito: O que são e como usar.
- Exercício: Adicione um middleware para log e uma dependência para verificação de usuário.

*Dia 25: Asynchronous e FastAPI*
- Conceito: Programação assíncrona.
- Exercício: Converta algumas rotas da sua API para serem assíncronas.

*Dia 26 e 27: Projeto Final*
- Consolide seu aprendizado.
- Exercício: Crie uma nova API ou aprimore sua API existente com tudo que aprendeu.

*Dia 28: Revisão e Feedback*
- Repasse todos os conceitos.
- Peça feedback sobre sua API a colegas ou mentores.

---

Este é um plano intensivo, e a profundidade com a qual você explora cada tópico pode variar conforme sua familiaridade anterior com a programação. Dedique tempo para praticar e revisar, e ajuste o plano conforme necessário. Boa sorte!

**Semana 1: Básicos de Python - Explicação dos Conceitos**

**Dia 1: Introdução ao Python**

- **O que é Python?**
    - Python é uma linguagem de programação interpretada, de alto nível e de propósito geral. É conhecida por sua legibilidade e facilidade de uso, permitindo que programadores expressem conceitos em menos linhas de código do que em outras linguagens, como C++ ou Java. Foi criada por Guido van Rossum no final dos anos 1980.

**Dia 2: Tipos de dados e Variáveis**

- **Inteiros, Strings, Listas, Dicionários, Tuplas e Conjuntos**:
    - **Inteiros (`int`)**: Representam números inteiros, como -3, 0, 42.
    - **Strings (`str`)**: Sequências de caracteres. Exemplo: "Hello, World!".
    - **Listas (`list`)**: Coleções ordenadas e mutáveis de itens. Exemplo: `[1, 2, 3]`.
    - **Dicionários (`dict`)**: Coleções não ordenadas de pares chave-valor. Exemplo: `{"nome": "João", "idade": 30}`.
    - **Tuplas (`tuple`)**: Coleções ordenadas e imutáveis de itens. Exemplo: `(1, 2, 3)`.
    - **Conjuntos (`set`)**: Coleções não ordenadas de itens únicos. Exemplo: `{1, 2, 3}`.

**Dia 3: Controle de Fluxo**

- **if, elif, else**:
    - Usados para tomada de decisões. O código dentro de um bloco `if` é executado se a condição for verdadeira. `elif` (abreviação de "else if") é usado para adicionar condições adicionais. `else` contém o código que será executado se nenhuma das condições anteriores for verdadeira.
- **loops (for e while)**:
    - `for`: Utilizado para iterar sobre uma sequência (lista, tupla, dicionário, conjunto ou string). 
    - `while`: Executa um conjunto de instruções enquanto uma condição for verdadeira.

**Dia 4: Funções e Módulos**

- **Definindo funções, parâmetros, retornos**:
    - As funções permitem agrupar um conjunto de instruções de modo que possam ser reutilizadas. São definidas usando a palavra-chave `def`, seguida pelo nome da função, parâmetros entre parênteses e dois pontos.
- **Importando módulos**:
    - Os módulos são arquivos contendo um conjunto de funções relacionadas. Você pode criar seu próprio módulo ou usar módulos incorporados (por exemplo, `math`, `datetime`). Eles são importados usando a instrução `import`.

**Dia 5: Manipulação de arquivos**

- **Leitura e escrita de arquivos**:
    - Python tem funções para criar, ler, atualizar e deletar arquivos. A função `open()` é usada para abrir um arquivo, e pode ser seguida por métodos como `.read()`, `.write()`, `.close()` entre outros, para manipular o conteúdo do arquivo.

A primeira semana foca na base da linguagem Python, garantindo que você compreenda seus conceitos fundamentais. A partir daqui, você poderá construir sobre essa base e explorar conceitos mais avançados e específicos, como os da biblioteca FastAPI nas semanas subsequentes.

**Semana 1: Básicos de Python - Exercícios com Exemplos**

**Dia 1: Introdução ao Python**

- **Exercício:** Escreva um programa que imprima "Olá, Mundo!" no console.
    - **Exemplo:**
      ```python
      print("Olá, Mundo!")
      ```

**Dia 2: Tipos de dados e Variáveis**

- **Exercício:** Crie variáveis para armazenar seu nome, idade, uma lista de seus hobbies e um dicionário com sua profissão e anos de experiência.
    - **Exemplo:**
      ```python
      nome = "João"
      idade = 30
      hobbies = ["correr", "ler", "cozinhar"]
      profissao_info = {"profissao": "Engenheiro", "anos_de_experiencia": 8}
      ```

**Dia 3: Controle de Fluxo**

- **Exercício:** Dado um número, verifique se ele é positivo, negativo ou zero.
    - **Exemplo:**
      ```python
      numero = 5
      if numero > 0:
          print("Positivo")
      elif numero < 0:
          print("Negativo")
      else:
          print("Zero")
      ```

- **Exercício:** Usando um loop `for`, imprima os números de 1 a 10.
    - **Exemplo:**
      ```python
      for i in range(1, 11):
          print(i)
      ```

**Dia 4: Funções e Módulos**

- **Exercício:** Crie uma função que aceite dois números como argumentos e retorne sua soma.
    - **Exemplo:**
      ```python
      def somar(a, b):
          return a + b
          
      resultado = somar(5, 3)
      print(resultado)  # Saída: 8
      ```

- **Exercício:** Importe o módulo `math` e calcule a raiz quadrada de um número.
    - **Exemplo:**
      ```python
      import math

      numero = 16
      raiz_quadrada = math.sqrt(numero)
      print(raiz_quadrada)  # Saída: 4.0
      ```

**Dia 5: Manipulação de arquivos**

- **Exercício:** Escreva um programa que crie um arquivo chamado "meu_arquivo.txt" e escreva a frase "Aprendendo Python com ChatGPT!" nele. Em seguida, leia o conteúdo do arquivo e imprima-o no console.
    - **Exemplo:**
      ```python
      with open("meu_arquivo.txt", "w") as arquivo:
          arquivo.write("Aprendendo Python com ChatGPT!")

      with open("meu_arquivo.txt", "r") as arquivo:
          conteudo = arquivo.read()
          print(conteudo)  # Saída: Aprendendo Python com ChatGPT!
      ```

Esses exercícios e exemplos abordam os conceitos básicos de Python ensinados na primeira semana. Resolver esses problemas práticos ajudará a consolidar sua compreensão e prepará-lo para tópicos mais avançados nas semanas subsequentes.

