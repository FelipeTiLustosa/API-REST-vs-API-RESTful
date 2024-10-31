## API-REST VS API-RESTful

1. **API REST**:
   - Uma **API REST** (ou API no estilo REST) é uma API que tenta seguir os princípios REST.
   - No entanto, ela **não necessariamente** segue todas as regras ou princípios REST de maneira rigorosa. Ou seja, pode ser uma API que usa alguns verbos HTTP e URLs, mas sem se preocupar tanto com a organização e a padronização total dos recursos.
Vamos simplificar!

"REST" (Representational State Transfer) é um **estilo de arquitetura** ou conjunto de regras que torna uma API mais **organizada e fácil de entender**.

#### Imagine uma API REST como um cardápio em um restaurante:

1. **URLs como Endereços**: Cada prato no cardápio tem um nome; nas APIs REST, esses "endereços" (URLs) levam a diferentes tipos de informações ou ações. Por exemplo:
   - `/usuarios` pode trazer todos os usuários.
   - `/usuarios/1` traz um usuário específico.

2. **Métodos Simples**: A API REST usa **verbos simples**:
   - **GET** para ler dados (como olhar o cardápio).
   - **POST** para criar algo (como fazer um pedido).
   - **PUT** para atualizar algo.
   - **DELETE** para excluir.

3. **Formatos Comuns**: REST geralmente troca informações em um formato padrão, como **JSON** (uma maneira fácil de enviar e ler dados).

2. **API RESTful**:
   - Já uma **API RESTful** é uma API que segue **todas** as regras e princípios REST de maneira completa.
   - Isso significa que ela adota todos os padrões REST, como o uso correto de verbos HTTP (GET, POST, PUT, DELETE), organização de URLs, tratamento de erros adequado, e representa cada recurso (como "usuários" ou "produtos") de forma clara e consistente.

Então, enquanto a **API REST** pode usar alguns conceitos REST, a **API RESTful** adota esses princípios de forma completa e cuidadosa.

### O que é o Padrão REST?

O **padrão REST** (Representational State Transfer) é um conjunto de regras e convenções para construir APIs que sejam:

1. **Baseadas em Recursos**:
   - REST organiza informações como "recursos", onde cada recurso tem uma representação única.
   - Exemplo: Um recurso "usuários" tem uma URL específica, como `/usuarios`.

2. **Utilização de Verbos HTTP**:
   - **GET**: Ler dados.
   - **POST**: Criar dados.
   - **PUT/PATCH**: Atualizar dados.
   - **DELETE**: Excluir dados.

3. **Estateless (Sem Estado)**:
   - Cada requisição é independente; o servidor não precisa lembrar do que aconteceu em requisições anteriores.

4. **URL como Identificador de Recursos**:
   - As URLs identificam os recursos e devem ser organizadas de forma lógica e simples.

5. **Formatos Padronizados de Dados**:
   - REST usa formatos como **JSON** ou **XML** para que o cliente e o servidor troquem informações de forma consistente.

Essas práticas tornam as APIs RESTful bem estruturadas, fáceis de entender e simples de integrar com diversos sistemas.
