# Boas vindas ao repositório do projeto de Aggregations!

# Sobre o projeto

Neste projeto o desafio era utilizar métodos complexos de buscas no banco de dados MongoDB e criar pipelines


# Habilidades
Neste projeto fui capaz de:
- Executar buscas complexas no banco mongoDB
- Usar os operadores de aggregation para fazer uma pipeline

# Quer testar o projeto?

- Baixe o projeto: git clone

- Entre no diretório do projeto e instale as dependências: cd mongodb-aggregations && npm install

- Siga as instruções para restaurar o banco de dados e rode as queries no seu terminal

## Instruções para restaurar o banco de dados `aggregations`

1. Abra o terminal e conecte-se à sua instância local do **MongoDB**. Se você receber uma mensagem de erro com uma mensagem como ***Connection refused***, tente reiniciar sua instância ([veja como fazer isso aqui](https://course.betrybe.com/back-end/mongodb/introduction/#conectando)).

2. Agora que você tem certeza de que a sua instância está no ar e que você está conectado a ela, digite `exit`. Você voltará ao terminal para iniciar a importação dos dados.

3. Na raiz do diretório do projeto, execute o seguinte comando que fará a restauração da base de dados `aggregations`:
    ```sh
    DBNAME=aggregations ./scripts/resetdb.sh assets
    ```

  * A execução desse script criará um banco de dados chamado `aggregations` e importará todas as suas coleções.

⚠️ Como tanto esse script quanto o script de execução local dos testes (mostrado na [seção seguinte](#implementações-técnicas)), **restauram a base de dados `aggregations`**, se atente a salvar seu progresso nos arquivos de desafio! ⚠️

---
