# Instruções para Desenvolvimento

Este projeto requer a recriação de uma página mobile baseada em um design fornecido no Figma. A pessoa responsável por este teste deve utilizar o arquivo fornecido no projeto para desenvolver a página conforme as especificações do design.

### Figma Design
O design a ser seguido está disponível no Figma no seguinte [link](https://www.figma.com/file/lAAailSNvI7cZQAllaYOgh/Untitled?type=design&node-id=0%3A1&mode=design&t=MXWGaECxZGzFZF24-1)


### Ferramentas Utilizadas

* React: O projeto deve ser desenvolvido utilizando React.
* SCSS: Utilize SCSS para estilização dos componentes.

### Estrutura do Projeto

O projeto está estruturado da seguinte forma:

* `src/`: Diretório contendo o código fonte do projeto.
* `public/`: Diretório contendo arquivos estáticos como imagens. 
* `README.md`: Este arquivo contendo as instruções para desenvolvimento.

## Como Começar

* Extraia este projeto para um diretório local.
* Navegue até o diretório do projeto.
* Instale as dependências do projeto utilizando `npm install`.
* Execute o projeto localmente com `npm start`.

## Desenvolvimento
* Utilize o arquivo fornecido no projeto como referência para criar a página mobile.
* Siga fielmente as especificações de design presentes no Figma.
* Utilize SCSS para estilização dos componentes.
* Mantenha o código limpo e bem organizado, seguindo as melhores práticas de desenvolvimento.

### Slider

Para o componente slider, você poderá utilizar a biblioteca que quiser. Sugerimos a utilização da biblioteca [react-slick](https://react-slick.neostack.com/).

Para a composição do card de produtos no slider, deverá ser utilizado as informações retornantes da função `getProducts` presente no arquivo `/src/utils.js`.

