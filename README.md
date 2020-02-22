<h1 align="center">
  <img alt="Fastfeet" title="Fastfeet" src=".github/logo.png" width="300px" />
</h1>

<h3 align="center">
  Desafio 9: FastFeet, front-end web
</h3>

<h3 align="center">
  :warning: Etapa 3/4 do Desafio Final :warning:
</h3>

<p>Esse desafio faz parte do Desafio Final, que é uma aplicação completa (Back-end, Front-end e Mobile) que é avaliada para emissão do Certificado do Bootcamp GoStack, por isso é fundamental que ele seja feito com muito empenho!</p>

<blockquote align="center">“Mude você e todo o resto mudará naturalmente”!</blockquote>

<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/rocketseat/bootcamp-gostack-desafio-09?color=%2304D361" />

  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%2304D361" />
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361" />

  <a href="https://github.com/Rocketseat/bootcamp-gostack-desafio-09/stargazers">
    <img alt="Stargazers" src="https://img.shields.io/github/stars/rocketseat/bootcamp-gostack-desafio-09?style=social" />
  </a>
</p>

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-entrega">Entrega</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-licença">Licença</a>
</p>

## 🚀 Sobre o desafio

Durante esse desafio vamos construir o front-end da aplicação FastFeet que criamos o back-end durante os desafios dos módulos 02 e 03 de Node.js.

A versão web do projeto FastFeet representa a visão da distribuidora, ou seja, todas funcionalidades presentes na versão web são para administradores. As funcionalidades para o entregador serão dispostas no aplicativo mobile.

### Novas funcionalidades

Antes de iniciar a parte web, **adicione as seguintes funcionalidades no back-end** da aplicação:

1. Permita que a listagem de encomendas seja filtrada pelo nome do produto, recebendo um Query Parameter `?q=Piano` e buscando no banco encomendas com esse filtro (utilize os operadores `Like` ou `iLike`). Caso o parâmetro não seja passado, retorne todas as encomendas;

2. Permita que a listagem de entregadores seja filtrada pelo nome do entregador, recebendo um Query Parameter `?q=John` e buscando no banco entregadores com esse filtro (utilize os operadores `Like` ou `iLike`). Caso o parâmetro não seja passado, retorne todos os entregadores;

3. Permita que a listagem de destinatários seja filtrada pelo nome do destinatário, recebendo um Query Parameter `?q=Ludwig` e buscando no banco destinatários com esse filtro (utilize os operadores `Like` ou `iLike`). Caso o parâmetro não seja passado, retorne todos os destinatários;

### Informações importantes

1. Antes de cancelar encomendas ou deletar qualquer registro do banco crie uma verificação adicinal usando a função `confirm` do JavaScript;
2. Para formatação de datas utilize sempre a biblioteca `date-fns`;
3. No cadastro/edição de encomendas deve ser possível buscar o entregador e o destinatário pelo nome. Utilize o método `async` da biblioteca [React Select](https://react-select.com/home#async). As encomendas devem ser buscadas da API assim que a página carregar e não devem possuir filtro.

### Opcionais

1. Adicione paginação no front-end e back-end para todas listagens;
2. Utilize máscaras para o input de CEP;
3. Crie um filtro para visualizar apenas as entregas com problemas na listagem de encomendas.

## 🎨 Layout

O layout do desafio está em anexo como um arquivo `.xd`.

Caso esteja usando OS X / Windows você pode abrir esse utilizando o Adobe Xd.

Caso contrário, você pode utilizar a seguinte URL para visualizar todas as telas: [Visualizar](https://xd.adobe.com/view/62e829fc-4f10-4ac8-70d2-d39b429d43ee-14d9/grid/)

## 📅 Entrega

Esse desafio **não precisa ser entregue** e não receberá correção. Além disso, o código fonte **não está disponível** por fazer parte do **desafio final**, que será corrigido para **certificação** do bootcamp. Após concluir o desafio, adicionar esse código ao seu Github é uma boa forma de demonstrar seus conhecimentos para oportunidades futuras.

## 📝 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE.md) para mais detalhes.

---

Feito com ♥ by Rocketseat :wave: [Entre na nossa comunidade!](https://discordapp.com/invite/gCRAFhc)
