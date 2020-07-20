# getkcal

Estes são os arquivos iniciais do projeto **getkcal** feito por [Mateus Silva](https://github.com/maateusilva) em um dos seus videos aulas.
O projeto tem como objetivo armazenar seu tamanho e peso com o tipo de atividade que você faz, e fazer um cálculo de IMC para saber um média de quantas calorias você deve perder/ganhar para ter uma boa saúde.

## Instalação

Este projeto não precisa de nenhuma depedência para funcionar, porém durante a aula foi utilizado o pacote `serve` para roda-lo no browser através de um servidor node.

Sinta-se a vontade caso queira rodar este projeto direto no seu browser clicando com o botão direito no arquivo `index.html` e, em seguida, selecionando a opção `Abrir Com` e selecionando o navegador de sua preferência.

Você precisará ter o [NodeJS](https://nodejs.org) instalado na sua máquina, e, após isso, clonar este repositório:

```sh
  $ git clone https://github.com/maateusilva/getkcal.git
```

## Executando a aplicação

Para executá-la é muito simples, basta rodar os seguintes comandos:

```sh
  $ cd getkcal/starterkit # para acessar a pasta clonada do git
  $ npm init -y # inicializando o package.json
  $ npm install serve -D # instalando o serve como dependência de desenvolvimento
  $ npx serve . # rodando o servidor node
```
