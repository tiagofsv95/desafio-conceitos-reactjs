<img alt="GoStack" src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png" />

<h3 align="center">
  Desafio 03: Conceitos do ReactJS
</h3>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/rocketseat/bootcamp-gostack-desafios?color=%2304D361">

  <a href="https://www.linkedin.com/in/tiago-felipe-sanches-vieira-457764139/r">
    <img alt="Made by Tiago Felipe" src="https://img.shields.io/badge/made%20by-Tiago%20Felipe-%2304D361">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361">
</p>

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## :rocket: Sobre o desafio

Nesse desafio, foi proposto continuar desenvolvendo a aplicação que irá armazenar repositórios, que você já foi desenvolvido no [desafio](https://github.com/tiagofsv95/desafio-conceitos-node) utilizando o Node.js.

Para executar o projeto e necessario ter o repositorio citado acima clonado e rodando, pois **é o backend desta aplicação**. Depois basta dar um `git clone https://github.com/tiagofsv95/desafio-conceitos-reactjs.git` no seu console e depois `yarn` para instalar as dependencias. Depois de instalar todas as dependencias basta executar `yarn start`.

## Ferramentas utilizadas na aplicação

-**react**;

-**axios**;

### Funcionalidades da aplicação

- **`Listar os repositórios da sua API`**: Deve ser capaz de criar uma lista com o campo **title** de todos os repositórios que estão cadastrados na sua API.

- **`Adicionar um repositório a sua API`**: Deve ser capaz de adicionar um novo item na sua API através de um botão com o texto **Adicionar** e, após a criação, deve ser capaz de exibir o nome dele após o cadastro.

- **`Remover um repositório da sua API`**: Para cada item da sua lista, deve possuir um botão com o texto **Remover** que, ao clicar, irá chamar uma função para remover esse item da lista do seu frontend e da sua API.

### Específicação dos testes

Para esse desafio tem os seguintes testes:

- **`should be able to add new repository`**: Para que esse teste passe, sua aplicação deve permitir que um repositório seja adicionado ao seu backend e listado no seu frontend dentro de uma `LI`.

- **`should be able to remove repository`**: Para que esse teste passe, sua aplicação deve permitir que ao clicar no botão de remover que vai estar dentro da `LI` do repositório adicionado, o item seja removido da listagem.

![Desafio Demo](demo/demo.gif)

## :memo: Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

Feito com ❤️ by Tiago Felipe
