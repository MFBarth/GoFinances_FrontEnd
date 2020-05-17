<h3 align="center">
  Desafio: Fundamentos ReactJS
</h3>

## Sobre o desafio

Nesse desafio, foi criado uma aplicação React que permite incluir e importar, além disso é gerado um balanço com o valor de soma de entradas, retiradas e total de crédito dos dados dos repositórios criados na API feita no desafio anterior utilizando Node.js, segue link para o desafio anterior: *https://github.com/MFBarth/Desafio_Database_upload_NodeJs*.

**Observação**: Este desafio está utilizando o gerenciador de pacotes **yarn**, sendo assim para instalar todas as dependências é necessário dar o comando `yarn` no terminal, além disso é nescessário que a API (criado no desafio anterior) esteja sendo executado no caminho *http://localhost:3333*, para que a aplicação consiga listar, incluir e deleletar dados dos respositórios.

### Layout da aplicação

Essa aplicação possui o layout apresentado na imagem abaixo. (Layout fornecido pela Rockeseat).

<img alt="GoFinances" src="/src/assets/goFinances.png"/>


### Funcionalidades da aplicação


- **`Listar as transações da sua API`**: Na página `Dashboard` é exibido uma listagem através de uma tabela, com o campo `title`, `value`, `type` e `category` de todas as transações que estão cadastradas na  API.

- **`Exibir o balance da sua API`**: Na página `Dashboard`, é exibido o balance que é retornado do  backend, contendo o total geral, junto ao total de entradas e saídas.

- **`Importar arquivos CSV`**: Na página `Import`, é possível fazer o envio de um arquivo no formato `csv` para o  backend, que irá fazer a importação das transações para o seu banco de dados. O arquivo csv deve seguir o seguinte [modelo](https://github.com/MFBarth/Desafio_Database_upload_NodeJs/tree/master/src/assets/file.csv).
