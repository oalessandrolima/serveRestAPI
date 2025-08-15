# serveRestAPI

Teste de API Rest do manual a CI/CD

## O que é

Este repositório foi criado para o bootcamp de Teste de API Rest

## Tecnologias utilizadas

- Postman
- Node version v20.12.1
- Newman version 6.2.1
- newman-reporter-htmlextra version 1.23.1


## Documentações

- Doc da API: [Consulte Swagger](https://serverest.dev/#/)


## Como instalar o ambiente

- Primeiro: instale o node em seu computador [baixe aqui](https://nodejs.org/en/download)
- Segundo: realize a instalação do newman de forma global [baixe aqui a dependência](https://www.npmjs.com/package/newman)
```
npm install -g newman
```
- Terceiro: realize a instalação da dependência dos relatórios (opcional) [newman-reporter-htmlextra](https://www.npmjs.com/package/newman-reporter-htmlextra)
```
npm install -g newman-reporter-htmlextra
```

## Como rodar os testes

### Pelo Postman web ou desktop

- Importe a collection e o environment
- Execute os testes de forma manual ou automatizada

### Pelo Newman

- Abra o seu console de preferência
- Execute a seguinte linha de comando para executar os testes
  ```
  newman run /path/to/collection.json -r cli
  ```
- Execute os testes com relatório
  ```
  newman run /path/to/collection.json -r cli,html,htmlextra,csv
  ```
  
### Report

Se você optou por rodar os testes com o report htmlextra, você gerou um arquivo HTML com o resultado dos testes e para verificar as validações você pode abrir a pasta **newman** que foi criada no local em que os arquivos de collection e environment se encontram.


## Entre em contato

Email: alessandrorodrigues270@gmail.com

LinkedIn: https://www.linkedin.com/in/alessandro-lima-305203108/
