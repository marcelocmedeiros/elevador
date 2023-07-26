# Elevador

<p align="center">
<img src="./imagens/Apresentacao.png" alt="Tela incial" width="400px"></img>
<img src="./imagens/Movimentacao.gif" alt="Aplicação funcionando" width="421px"></img>
</p>



## 🤔 O que é este projeto
Este projeto é uma página feita com HTML, CSS e Javascript que contém sete botões de indicação de andares do “T” até 6º andar. Quando clicado o elevador vai para seu respectivo andar. Ainda possui um mostrador ao lado que informa literalmente qual o andar o elevador se encontra. Este foi o primeiro projeto do curso Formação DEV.

## 🖥️ Como rodar este projeto
Para rodar o projeto basta dar dois cliques no arquivo *index.html* uma vez que a pasta do projeto esteja aberta no sistema de arquivos do seu sistema operacional.

Alternativamente você também pode utilizar a extensão [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) da IDE Visual Studio Code para rodar o projeto.

## 🕹️ Como usar este projeto
Uma vez que a aplicação esteja rodando, você pode clicar nos círculos que representam os andares que são mostrados no topo da página para subir e descer o elevador do edifício conforme desejar. Para mostrar o respectivo andar existe um mostrador retangular ao lado dos círculos que representam os andares.

## ⚙️ Tecnologias usadas no projeto
- ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=plastic&logo=html5&logoColor=white)
- ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=plastic&logo=css3&logoColor=white)
- ![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=plastic&logo=javascript&logoColor=F7DF1)

## 🗒️ Features do projeto
<!-- caracteristicas do projeto resumidas mas não é necessaria-->
- 7 botões que representam os andares para subir e descer o elevador e também alterar o mostrador  ao lado.
- O mostrador indica o andar onde o elevador se encontra parado.


## 🗂️ Como este projeto está organizado
<!-- dar uma ideais geral nãoprecisa ser detalhista -->
Na pasta raiz do projeto existem três arquivos de código:
- index.html -> contém o html da aplicação
- Pasta CSS -> contém o arquivo "style.css" que faz estilos da aplicação
- Pasta js -> contém dois arquivos "rua.js" e "predio.js", códigos javascript da aplicação

## 👩‍💻 Como este projeto foi implementado
<!-- Aqui pode ser usado uma linguagem, mas técnica e não escrever demais-->
Este projeto foi implementado com HTML, CSS e JavaScript.

Na pasta javascript especificamente no arquivo “rua.js” usei uma função para construir as faixas da rua obtendo a quantidade das faixas pelo querySelectorAll e criando cada faixa pelo createElement.

Já no arquivo “predio.js” se concentrou toda a construção do prédio, pavimentos e elevador, como também a movimentação do elevador. Para criação de cada andar, térreo e elevador usei o createElement criando uma “div” que representa cada elemento.

A movimentação do elevador se dá capturando o clique do botão do mouse pelo "onclick" nos respectivos botões é disparado um evento que irá movimentar o elevador conforme andar escolhido e por conseguinte mostrar seu ponto final no mostrador.

## ⭐ Dependências principais
<!-- API's importantes-->
Não existe dependências no projeto.

## 🆘 Precisa de ajuda?
Você pode me contatar através desses contatos:

[![Linkedin](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marcelocmdev/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](marcelocmdev@gmail.com)
[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white)](https://www.instagram.com/marcellocmedeiros/)
[![whatsapp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://api.whatsapp.com/send?phone=5583999666768)


-------
<p align="center">Feito com 🧑‍💻 por Marcelo</p>
