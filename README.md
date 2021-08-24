# Site de uma loja feita usando VTEX

## Sobre
Este site foi feito com base no desafio do treinamento hiring coders 2021, que é patrocinado pela VTEX. O desafio era fazer um site seguindo o passo a passo dado por eles. O objetivo foi praticar o que foi ensinado por eles.

Ferramentas usadas: VTEX e React.


## Instalação
Você vai precisar ter instalado em sua máquina:

[GIT](https://git-scm.com)

[Node.js](https://nodejs.org/en/). 

[VTEX](https://developers.vtex.com/vtex-developer-docs/docs/vtex-io-documentation-vtex-io-cli-install)

E também de um editor de código, de preferência o [VSCode](https://code.visualstudio.com/)

### Passos
- Crie uma pasta, que englobará duas pastas necessárias;
- Navegue até esta pasta no terminal;
- Clone este projeto, projeto-loja-vtex, use o terminal, com o comando <code>git clone https://github.com/Braz99/projeto-loja-vtex.git</code>;
- Depois clone <code>git clone https://github.com/Braz99/menufooter.git</code>
- Depois abra a pasta menufooter no terminal usando o comando <code> cd caminho da pasta</code>
- Com a pasta selecionada é hora de instalar todas as dependências do projeto com o comando <code>yarn install</code> na pasta footer menu(raiz), e na pasta de react.
- Para executar a aplicação em modo de desenvolvimento use o comando <code>vtex link</code> tanto na pasta do projeto-loja-vtex quanto na do footer menu, usando dois terminais, um para cada.
 
 ## Estruturação do projeto
 - A pasta menufooter é o footer estilizado feito em react, que contém o link para os desafios, link para a loja e o link para o whatsapp;
 - A __pasta projeto-loja-vtex__ contém a loja com as imagens e estilos, e segue o padrão do tema minimum-boilerplate-theme da vtex;
 - Dentro do projeto-loja-vtex na pasta store, há a __pasta blocks__, onde se encontra todos os blocos usados, e há também o arquivo __routes.jsonc__ que define as rotas;
 - Na pasta __assets__ ficam as imagens usadas;
 - Na pasta styles contém os estilos, tanto eles individualizados por blocos, __pasta css__, quanto geral, pasta configs, __style.json__

## Licença 
License MIT

## Autor 
Fabrício Brazil

