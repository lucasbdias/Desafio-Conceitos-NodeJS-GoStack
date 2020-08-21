<h1 align="center">
    <img src="https://rocketseat-cdn.s3-sa-east-1.amazonaws.com/bootcamp-header.png" alt="Gostack" width="200px" />
</h1>

<h2 align="center">Desafio 1: conceitos de NodeJS</h2>
<p align="center">Primeiro desafio do Bootcamp GoStack</p>

<p align="center">
    <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/rocketseat/bootcamp-gostack-desafio-01?color=%2304D361">
    <img alt="javascript" src="https://img.shields.io/badge/Javascript-100%25-yellow" /> 
    <img alt="node" src="https://img.shields.io/badge/node-v12.18.3-brightgreen" />
    <img alt="License" src="https://img.shields.io/badge/license-MIT-%2304D361" />
</p>

<p align="center">
    <a href="#sobre">Sobre o desafio</a>
</p>

<h2 id="sobre">🚀 Sobre o desafio</h2>
<p>Criação de uma aplicação para armazenar projetos e suas tecnologias e o mesmo podendo receber likes do zero utilizando Express.</p>
<h3>Rotas: </h3>
    <ul>
        <li>
            <strong>POST /projects :</strong>
            <p style="display: inline"> A rota recebe title, url, techs e likes dentro do corpo e cadastra um novo projeto dentro de um array no seguinte formato: { id: "a17a0dba-ba69-40f8-8750-38ef4e49a3a2", title: 'Novo projeto', url: 'https://github.com/lucasbdias/Desafio-Conceitos-ReactJS-GoStack' , techs: ['nodejs', 'react'] , likes: 0 };</p>
        </li>
        <li>
            <strong>GET /projects :</strong>
            <p style="display: inline"> Rota que lista todos projetos e suas tarefas; </p>
        </li>
        <li>
            <strong>PUT /projects/:id :</strong>
            <p style="display: inline"> A rota que altera o título do projeto com o id presente nos parâmetros da rota; </p>
        </li>
        <li>
            <strong>DELETE /projects/:id :</strong>
            <p style="display: inline"> A rota deleta o projeto com o id presente nos parâmetros da rota; </p>
        </li>
        <li>
            <strong>POST /projects/:id/like :</strong>
            <p style="display: inline"> A rota aumentaa o número de likes do repositório específico escolhido através do id presente nos parâmetros da rota, a cada chamada dessa rota, o número de likes é aumentado em 1. </p>
        </li>
    </ul>

<h3>Middlewares:</h3>
<ul>
    <li>
        <strong>Verificação de id :</strong>
        <p style="display: inline"> Validação de existência do ID do repositório. Em caso de não existir, retorna um erro com status 400. </p>
    </li>
</ul>
