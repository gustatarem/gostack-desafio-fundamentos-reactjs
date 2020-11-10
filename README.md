
<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios-new.png" />

<h3 align="center">
  Desafio 07: GoFinances Web
</h3>

## :rocket: Sobre o desafio

Esse projeto é uma continuação da aplicação de gestão de transações, desenvolvida com React.js utilizando rotas e envio de arquivos por formulário.

Essa aplicação se conecta ao backend do [Desafio 06](https://github.com/gustatarem/gostack-typeorm-upload) e exibe as transações criadas e permitir a importação de um arquivo CSV para gerar novos registros no banco de dados.

## :trophy: Funcionalidades da aplicação

- **`Listar as transações da API`**: A página `Dashboard` exibe uma listagem através de uma tabela, com o campo `title`, `value`, `type` e `category` de todas as transações que estão cadastradas na sua API.

- **`Exibir o balance da API`**: A página `Dashboard` exibe o balance que é retornado do  backend, contendo o total geral, junto ao total de entradas e saídas.

- **`Importar arquivos CSV`**: Na página `Import`, você pode realizar o envio de um arquivo no formato `csv` para o backend, que irá fazer a importação das transações para o o banco de dados. O arquivo csv deve seguir o seguinte [modelo](https://github.com/Rocketseat/bootcamp-gostack-desafios/blob/master/desafio-database-upload/assets/file.csv).

## :computer: Instruções de instalação e teste

Clone o repositório usando o `git` ou faça o download no formato zip. 
Antes de tudo, certifique-se de que você tem um gerenciador de pacotes (como o yarn) e o `Node.js` instalados em sua máquina.

Após baixar o projeto, abra uma aba do terminal e execute os seguintes comandos:

```Bash
# ../pasta-de-destino
$ cd gostack-desafio-fundamentos-reactjs
# ../pasta-de-destino/gostack-desafio-fundamentos-reactjs
$ yarn
```

Para iniciar a aplicação no localhost (porta 3000):

```Bash
# ../pasta-de-destino/gostack-desafio-fundamentos-reactjs
$ yarn start
```

Para rodar os testes da aplicação:

```Bash
# ../pasta-de-destino/gostack-desafio-fundamentos-reactjs
$ yarn test
```
