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

**Semana 2: Intermediário de Python - Explicação dos Conceitos e Exemplos**

**Dia 8: Compreensões de Lista e Dicionário**

- **Compreensões de Lista e Dicionário**: São maneiras concisas e elegantes de criar listas ou dicionários sem precisar usar loops extensos ou funções. Elas são amplamente utilizadas em Python por sua eficiência e legibilidade.

    - **Exemplo de Compreensão de Lista**:
        ```python
        # Criar uma lista dos quadrados dos números de 0 a 9.
        quadrados = [x**2 for x in range(10)]
        print(quadrados)  # Saída: [0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
        ```
      
    - **Exemplo de Compreensão de Dicionário**:
        ```python
        # Criar um dicionário com números e seus quadrados.
        quadrados_dict = {x: x**2 for x in (2, 3, 4)}
        print(quadrados_dict)  # Saída: {2: 4, 3: 9, 4: 16}
        ```

**Dia 9: Manipulação de Strings**

- **Métodos de string**: Em Python, strings são objetos e, como tal, possuem métodos que permitem a sua manipulação. Esses métodos ajudam a realizar tarefas como alterar a capitalização, dividir a string em partes e substituir substrings.

    - **Exemplo**:
        ```python
        frase = "aprendendo python"
        
        # Transformar a string em maiúsculas.
        print(frase.upper())  # Saída: "APRENDENDO PYTHON"
        
        # Dividir a string em palavras.
        palavras = frase.split()
        print(palavras)  # Saída: ['aprendendo', 'python']
        ```

**Dia 10: Classes e Objetos**

- **Classes e Objetos**: Em programação orientada a objetos, a classe é como um blueprint para criar objetos. Os objetos têm atributos (características) e métodos (ações). A classe define os atributos e métodos que seus objetos terão.

    - **Exemplo**:
        ```python
        class Carro:
            def __init__(self, marca, modelo):
                self.marca = marca
                self.modelo = modelo
                
            def exibir_informacoes(self):
                print(f"Marca: {self.marca}, Modelo: {self.modelo}")

        # Criando um objeto da classe Carro.
        meu_carro = Carro("Toyota", "Corolla")
        meu_carro.exibir_informacoes()  # Saída: Marca: Toyota, Modelo: Corolla
        ```

**Dia 11: Tratamento de Exceções**

- **Tratamento de Exceções**: No desenvolvimento de software, é comum encontrar erros. Em Python, erros detectados durante a execução são chamados de exceções e podem ser tratados usando blocos `try` e `except`.

    - **Exemplo**:
        ```python
        try:
            resultado = 10 / 0  # Isso causará uma exceção.
        except ZeroDivisionError:
            print("Não é possível dividir por zero!")
        ```

**Dia 12: Introdução a Bibliotecas**

- Bibliotecas são conjuntos de módulos que oferecem funcionalidades prontas para serem usadas, evitando que os desenvolvedores recriem código comumente usado. Em Python, as bibliotecas podem ser padrões (já incluídas com o Python) ou externas (instaladas via pip).

    - **Exemplo**:
        ```python
        # Usando a biblioteca padrão "datetime" para obter a data atual.
        import datetime
        hoje = datetime.date.today()
        print(hoje)  # Saída: a data de hoje no formato AAAA-MM-DD
        ```

Estes conceitos formam o núcleo intermediário de Python e são cruciais para tópicos mais avançados e para o uso efetivo de frameworks como o FastAPI.


**Semana 2: Intermediário de Python - Exercícios com Exemplos**

**Dia 8: Compreensões de Lista e Dicionário**

1. **Exercício:** Crie uma lista que contenha o dobro de cada número de 1 a 10 usando compreensão de lista.
    - **Exemplo:**
      ```python
      dobrados = [x*2 for x in range(1, 11)]
      print(dobrados)  # Saída: [2, 4, 6, 8, 10, 12, 14, 16, 18, 20]
      ```

2. **Exercício:** Usando compreensão de dicionário, crie um dicionário onde as chaves são números de 1 a 5 e os valores são o quadrado das chaves.
    - **Exemplo:**
      ```python
      quadrados = {x: x**2 for x in range(1, 6)}
      print(quadrados)  # Saída: {1: 1, 2: 4, 3: 9, 4: 16, 5: 25}
      ```

**Dia 9: Manipulação de Strings**

1. **Exercício:** Dada a string "Python é divertido!", converta-a para maiúsculas e, em seguida, separe-a em palavras.
    - **Exemplo:**
      ```python
      frase = "Python é divertido!"
      frase_maiuscula = frase.upper()
      palavras = frase_maiuscula.split()
      print(palavras)  # Saída: ['PYTHON', 'É', 'DIVERTIDO!']
      ```

**Dia 10: Classes e Objetos**

1. **Exercício:** Crie uma classe chamada "Cachorro" que tenha um método para "latir". Crie um objeto dessa classe e faça-o "latir".
    - **Exemplo:**
      ```python
      class Cachorro:
          def latir(self):
              print("Au au!")
              
      rex = Cachorro()
      rex.latir()  # Saída: Au au!
      ```

**Dia 11: Tratamento de Exceções**

1. **Exercício:** Escreva um programa que peça ao usuário para digitar um número e, em seguida, imprima o inverso desse número. Se o usuário digitar zero, capture a exceção e imprima uma mensagem amigável.
    - **Exemplo:**
      ```python
      try:
          numero = float(input("Digite um número: "))
          inverso = 1 / numero
          print(f"O inverso de {numero} é {inverso}")
      except ZeroDivisionError:
          print("Não é possível encontrar o inverso de zero!")
      ```

**Dia 12: Introdução a Bibliotecas**

1. **Exercício:** Utilize a biblioteca `datetime` para calcular quantos dias faltam para o seu próximo aniversário.
    - **Exemplo:**
      ```python
      import datetime
      hoje = datetime.date.today()
      aniversario = datetime.date(hoje.year, 12, 31)  # Substitua 12 e 31 pela sua data de aniversário
      if aniversario < hoje:
          aniversario = aniversario.replace(year=hoje.year + 1)
      delta = aniversario - hoje
      print(f"Faltam {delta.days} dias para o meu próximo aniversário!")
      ```

Estes exercícios ajudarão a solidificar seu entendimento dos conceitos intermediários de Python. Ao resolvê-los, você estará mais preparado para tópicos mais avançados e para trabalhar com frameworks como o FastAPI.

**Semana 3: Avançado de Python e Introdução ao FastAPI - Explicação dos Conceitos e Exemplos**

**Dia 13: Iteradores e Geradores**

- **Iteradores e Geradores** são mecanismos para iterar sobre sequências de dados sem necessariamente armazenar toda a sequência na memória de uma vez. Um iterador é um objeto que permite a iteração (ou seja, você pode percorrê-lo com um loop `for`). Um gerador é um tipo especial de iterador que é definido usando uma função e não um conjunto de dados armazenado.

    - **Exemplo de Gerador**:
        ```python
        def contagem_regressiva(n):
            while n > 0:
                yield n
                n -= 1

        for num in contagem_regressiva(5):
            print(num)
        ```
        A saída desse código seria a contagem regressiva de 5 a 1.

**Dia 14: Decoradores**

- **Decoradores** são uma ferramenta poderosa em Python que permite modificar ou estender o comportamento de funções ou métodos sem alterar seu código fonte. Eles são representados por `@nome_do_decorador` acima da definição de uma função.

    - **Exemplo**:
        ```python
        def meu_decorador(func):
            def wrapper():
                print("Algo está acontecendo antes da função ser chamada.")
                func()
                print("Algo está acontecendo após a função ser chamada.")
            return wrapper

        @meu_decorador
        def diz_ola():
            print("Olá!")

        diz_ola()
        ```
        Isso imprimirá as mensagens antes e depois de "Olá!".

**Dia 15: Introdução ao FastAPI**

- **FastAPI** é um framework moderno e rápido para construir APIs com Python. Ele é baseado em padrões abertos, como JSON Schema, OAuth 2.0 e OpenAPI.

    - **Exemplo básico com FastAPI**:
        ```python
        from fastapi import FastAPI

        app = FastAPI()

        @app.get("/")
        def leia_raiz():
            return {"Olá": "Mundo"}
        ```
        Ao executar este código, um servidor será iniciado, e acessando o endereço padrão (`http://127.0.0.1:8000/`), verá o retorno `{"Olá": "Mundo"}`.

**Dia 16: Dependências em FastAPI**

- No FastAPI, as **dependências** permitem que você reutilize o código de maneira eficaz, injetando funções de dependência em rotas, dependências de outros, etc. Isso é útil para autenticação, verificação de permissões, e muito mais.

    - **Exemplo**:
        ```python
        from fastapi import FastAPI, Depends

        app = FastAPI()

        def get_nome(nome: str = "Mundo"):
            return nome

        @app.get("/ola")
        def leia_nome(nome: Depends(get_nome)):
            return {"Olá": nome}
        ```

**Dia 17: Path Parameters e Query Parameters em FastAPI**

- **Path Parameters** são usados para capturar valores diretamente da URL, enquanto **Query Parameters** são normalmente usados para filtrar resultados.

    - **Exemplo**:
        ```python
        from fastapi import FastAPI

        app = FastAPI()

        @app.get("/items/{item_id}")
        def leia_item(item_id: int, q: str = None):
            return {"item_id": item_id, "q": q}
        ```

Ao abordar estes conceitos e praticá-los, você construirá um sólido entendimento das características avançadas de Python e das bases do FastAPI.

**Semana 3: Avançado de Python e Introdução ao FastAPI - Exercícios com Exemplos**

**Dia 13: Iteradores e Geradores**

1. **Exercício:** Crie um gerador que produza os primeiros n números da sequência de Fibonacci.
    - **Exemplo**:
      ```python
      def fibonacci(n):
          a, b = 0, 1
          for _ in range(n):
              yield a
              a, b = b, a + b

      for num in fibonacci(5):
          print(num)
      ```
      Saída: 0, 1, 1, 2, 3

**Dia 14: Decoradores**

1. **Exercício:** Crie um decorador que registre o tempo de execução de uma função.
    - **Exemplo**:
      ```python
      import time

      def cronometrar(func):
          def wrapper(*args, **kwargs):
              inicio = time.time()
              resultado = func(*args, **kwargs)
              fim = time.time()
              print(f"{func.__name__} executou em {fim - inicio} segundos")
              return resultado
          return wrapper

      @cronometrar
      def pausa():
          time.sleep(2)

      pausa()
      ```
      Saída aproximada: `pausa executou em 2.000114917755127 segundos`

**Dia 15: Introdução ao FastAPI**

1. **Exercício:** Usando FastAPI, crie uma API simples que retorne uma mensagem de saudação com o nome do usuário passado como parâmetro.
    - **Exemplo**:
      ```python
      from fastapi import FastAPI

      app = FastAPI()

      @app.get("/ola/{nome}")
      def saudacao(nome: str):
          return {"mensagem": f"Olá, {nome}!"}
      ```

**Dia 16: Dependências em FastAPI**

1. **Exercício:** Crie uma dependência que verifique se o usuário é "admin" e, em seguida, uma rota que utilize essa dependência para retornar um conteúdo secreto.
    - **Exemplo**:
      ```python
      from fastapi import FastAPI, Depends, HTTPException

      app = FastAPI()

      def is_admin(user: str):
          if user != "admin":
              raise HTTPException(status_code=401, detail="Não autorizado")
          return user

      @app.get("/secreto")
      def get_secreto(user: str = Depends(is_admin)):
          return {"mensagem": "Conteúdo secreto!"}
      ```

**Dia 17: Path Parameters e Query Parameters em FastAPI**

1. **Exercício:** Crie uma rota que aceite um ID de item como parâmetro de caminho e uma string de consulta `q` como parâmetro de consulta. Retorne ambos.
    - **Exemplo**:
      ```python
      from fastapi import FastAPI

      app = FastAPI()

      @app.get("/items/{item_id}")
      def get_item(item_id: int, q: str = None):
          return {"item_id": item_id, "q": q}
      ```

Esses exercícios visam proporcionar uma prática abrangente dos conceitos avançados de Python e da introdução ao FastAPI, preparando-o para tópicos ainda mais avançados na próxima semana.

**Semana 4: Avançado em FastAPI e Tópicos Finais - Explicação dos Conceitos e Exemplos**

**Dia 18: Modelos Pydantic em FastAPI**

- **Pydantic** é uma biblioteca de análise de dados e validação usando anotações Python. Em FastAPI, Pydantic é usado para definir o formato dos dados que você espera receber e enviar.

    - **Exemplo**:
        ```python
        from fastapi import FastAPI
        from pydantic import BaseModel

        app = FastAPI()

        class Item(BaseModel):
            name: str
            price: float

        @app.post("/items/")
        def create_item(item: Item):
            return {"name": item.name, "price": item.price}
        ```

**Dia 19: Requisições Assíncronas em FastAPI**

- FastAPI permite criar rotas **assíncronas** usando a palavra-chave `async`. Isso torna possível executar operações IO-bound (como operações de banco de dados) de forma mais eficiente.

    - **Exemplo**:
        ```python
        from fastapi import FastAPI

        app = FastAPI()

        @app.get("/async-endpoint")
        async def read_items():
            # Imagine uma operação assíncrona aqui
            return {"message": "Executado de forma assíncrona!"}
        ```

**Dia 20: Autenticação e Autorização em FastAPI**

- A autenticação e autorização são componentes essenciais para muitas APIs. FastAPI tem várias ferramentas e integrações para sistemas de autenticação, como OAuth2 e senhas.

    - **Exemplo**:
        ```python
        from fastapi import FastAPI, Depends, HTTPException
        from fastapi.security import HTTPBasic, HTTPBasicCredentials

        app = FastAPI()
        security = HTTPBasic()

        def get_current_username(credentials: HTTPBasicCredentials = Depends(security)):
            if credentials.username != "alice":
                raise HTTPException(status_code=400, detail="Usuário não autorizado!")
            return credentials.username

        @app.get("/users/me")
        def read_current_user(username: str = Depends(get_current_username)):
            return {"username": username}
        ```

**Dia 21: Testes em FastAPI**

- Testar sua API garante que ela funcione como esperado. FastAPI se integra facilmente com a biblioteca `pytest` para permitir testes eficientes.

    - **Exemplo**:
        ```python
        from fastapi.testclient import TestClient

        client = TestClient(app)

        def test_read_main():
            response = client.get("/")
            assert response.status_code == 200
            assert response.json() == {"message": "Hello World"}
        ```

**Dia 22: Bancos de Dados e ORM em FastAPI**

- Um ORM (Object-Relational Mapping) é uma ferramenta que permite interagir com bancos de dados usando a sintaxe de programação orientada a objetos. Um exemplo popular é o SQLAlchemy.

    - **Exemplo**:
        ```python
        from fastapi import FastAPI
        from sqlalchemy import create_engine
        from sqlalchemy.ext.declarative import declarative_base
        from sqlalchemy.orm import sessionmaker

        DATABASE_URL = "sqlite:///./test.db"
        engine = create_engine(DATABASE_URL)
        SessionLocal = sessionmaker(bind=engine)
        Base = declarative_base()

        # Aqui iriamos definir nossos modelos e rotas para interagir com o banco de dados.
        ```

Ao compreender e praticar estes conceitos, você estará bem equipado com uma compreensão robusta do FastAPI e de como desenvolver aplicações web modernas e eficientes com Python.

**Semana 4: Avançado em FastAPI e Tópicos Finais - Exercícios com Exemplos**

**Dia 18: Modelos Pydantic em FastAPI**

1. **Exercício:** Crie uma API que aceite dados de um livro usando modelos Pydantic e retorne os mesmos dados.
    - **Exemplo**:
      ```python
      from fastapi import FastAPI
      from pydantic import BaseModel

      app = FastAPI()

      class Book(BaseModel):
          title: str
          author: str
          year: int

      @app.post("/book/")
      def create_book(book: Book):
          return {"title": book.title, "author": book.author, "year": book.year}
      ```

**Dia 19: Requisições Assíncronas em FastAPI**

1. **Exercício:** Crie um endpoint assíncrono que simule uma operação de longa duração usando `await` e retorne uma mensagem após a conclusão.
    - **Exemplo**:
      ```python
      import asyncio
      from fastapi import FastAPI

      app = FastAPI()

      @app.get("/long-task")
      async def long_task():
          await asyncio.sleep(3)
          return {"message": "Tarefa concluída!"}
      ```

**Dia 20: Autenticação e Autorização em FastAPI**

1. **Exercício:** Implemente uma autenticação básica HTTP que aceite um nome de usuário e senha definidos por você. Se a autenticação for bem-sucedida, retorne as credenciais.
    - **Exemplo**:
      ```python
      from fastapi import FastAPI, Depends, HTTPException
      from fastapi.security import HTTPBasic, HTTPBasicCredentials

      app = FastAPI()
      security = HTTPBasic()

      def verify_credentials(credentials: HTTPBasicCredentials = Depends(security)):
          if credentials.username != "user123" or credentials.password != "pass123":
              raise HTTPException(status_code=401, detail="Credenciais inválidas!")
          return credentials

      @app.get("/secure-endpoint")
      def secure(username: str = Depends(verify_credentials)):
          return {"username": username.username}
      ```

**Dia 21: Testes em FastAPI**

1. **Exercício:** Escreva um teste para um endpoint que retorna a mensagem "Hello Tests!".
    - **Exemplo**:
      ```python
      from fastapi.testclient import TestClient
      from fastapi import FastAPI

      app = FastAPI()

      @app.get("/test-endpoint")
      def get_message():
          return {"message": "Hello Tests!"}

      client = TestClient(app)

      def test_hello_tests():
          response = client.get("/test-endpoint")
          assert response.status_code == 200
          assert response.json() == {"message": "Hello Tests!"}
      ```

**Dia 22: Bancos de Dados e ORM em FastAPI**

1. **Exercício:** Utilizando SQLAlchemy, defina um modelo para um `User` com `id`, `username`, e `email`. Em seguida, crie um endpoint que aceite dados do usuário e os armazene no banco de dados.
    - **Exemplo**:
      ```python
      from fastapi import FastAPI
      from pydantic import BaseModel
      from sqlalchemy import Column, Integer, String, create_engine
      from sqlalchemy.ext.declarative import declarative_base
      from sqlalchemy.orm import sessionmaker

      DATABASE_URL = "sqlite:///./test.db"
      engine = create_engine(DATABASE_URL)
      SessionLocal = sessionmaker(bind=engine)
      Base = declarative_base()

      class User(Base):
          __tablename__ = "users"
          id = Column(Integer, primary_key=True, index=True)
          username = Column(String, index=True, unique=True)
          email = Column(String, unique=True, index=True)

      Base.metadata.create_all(bind=engine)

      app = FastAPI()

      class UserCreate(BaseModel):
          username: str
          email: str

      @app.post("/users/")
      def create_user(user: UserCreate):
          db_user = User(username=user.username, email=user.email)
          db = SessionLocal()
          db.add(db_user)
          db.commit()
          db.refresh(db_user)
          db.close()
          return {"id": db_user.id, "username": db_user.username, "email": db_user.email}
      ```

Estes exercícios ajudarão a solidificar sua compreensão sobre os conceitos avançados em FastAPI e a prática de desenvolver aplicações web seguras, eficientes e testáveis.
Claro! O debugging, ou depuração, é uma parte crucial do desenvolvimento. Ajuda a identificar e corrigir erros ou problemas no código. Vou te guiar em como depurar considerando o plano de estudos que traçamos, focando em Python e FastAPI.

### 1. **Python Básico (Semana 1)**

**1.1. Debugging usando `print`**:
  - A forma mais básica de depuração é usando a função `print` para exibir valores de variáveis ou para sinalizar que uma determinada parte do código foi atingida.
  - Exemplo:
    ```python
    def add(a, b):
        print("A:", a)
        print("B:", b)
        return a + b

    add(3, 4)
    ```

**1.2. Usando o built-in debugger (pdb)**:
  - `pdb` é o depurador interativo de Python.
  - Você pode iniciar o pdb adicionando `import pdb; pdb.set_trace()` no código onde deseja iniciar a depuração.
  - Exemplo:
    ```python
    def add(a, b):
        import pdb; pdb.set_trace()
        return a + b

    add(3, 4)
    ```

### 2. **Python Intermediário (Semana 2)**

**2.1. Usando o debugger em funções mais complexas e com list comprehensions**:
  - Você pode colocar pontos de interrupção (breakpoints) em qualquer parte do código, incluindo dentro de comprehensions ou funções lambda.
  - Exemplo:
    ```python
    nums = [1, 2, 3, 4]
    [x*2 for x in nums if (lambda x: (import pdb; pdb.set_trace(), x > 2))[1](x)]
    ```

### 3. **Python Avançado e Introdução ao FastAPI (Semana 3)**

**3.1. Debugging com funções assíncronas**:
  - Quando você trabalha com funções `async`, pode usar `pdb` ou um debugger específico para código assíncrono, como o `aiohttp_pdb`.
  - Exemplo:
    ```python
    import asyncio

    async def fetch_data():
        import pdb; pdb.set_trace()
        await asyncio.sleep(1)
        return "data"

    asyncio.run(fetch_data())
    ```

### 4. **FastAPI Avançado (Semana 4)**

**4.1. Usando `print` ou logging**:
  - Para visualizar os dados recebidos em uma rota ou verificar o fluxo do programa, `print` ou o módulo `logging` podem ser úteis.
  - Exemplo:
    ```python
    from fastapi import FastAPI

    app = FastAPI()

    @app.get("/")
    def read_root():
        print("Root route accessed!")
        return {"Hello": "World"}
    ```

**4.2. Debugging com Uvicorn**:
  - Ao executar sua aplicação FastAPI com Uvicorn, você pode usar o modo `--reload` para reiniciar automaticamente o servidor quando o código for modificado. Além disso, se um erro ocorrer, Uvicorn mostrará um traceback detalhado na página da web.
  - Exemplo para rodar o servidor:
    ```
    uvicorn main:app --reload
    ```

**4.3. Depurando testes**:
  - Quando você escreve testes usando `pytest`, pode usar o flag `-s` para visualizar saídas impressas (`print`) e `--pdb` para iniciar o pdb quando um teste falhar.
  - Exemplo para rodar testes:
    ```
    pytest -s --pdb
    ```

**Dicas Finais**:

- Se você estiver usando um ambiente de desenvolvimento integrado (IDE) como o Visual Studio Code, PyCharm, etc., eles geralmente têm poderosos depuradores embutidos que oferecem ainda mais funcionalidades do que o `pdb` básico.
- Certifique-se de remover ou comentar as linhas de depuração (como `import pdb; pdb.set_trace()`) antes de enviar o código para produção ou repositório.

Com essa orientação de depuração, espero que você se sinta mais confortável para identificar e corrigir erros em seu código à medida que avança em sua jornada de aprendizado!
