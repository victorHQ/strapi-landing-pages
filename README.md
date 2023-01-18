<h1 align="center">
  <img alt="Strapi Icon" title="Strapi" src="https://user-images.githubusercontent.com/34111368/213310820-9fcd13ef-3026-4dc1-a611-d620ed6fc35d.png" width="220px" />
</h1>
<p align="center">Strapi v4 API - Landing-Pages</p>

<p align="center">
 <a href="#tecnologias">Tecnologias</a> • 
 <a href="#project">Projeto</a> • 
 <a href="#install">Instalação</a> • 
 <a href="#license">Licença</a>
</p>

<h2 id="tecnologias" align="center">
  Tecnologias :computer: 
</h2>

<p align="center">
  <img src="https://img.shields.io/badge/strapi-2F2E8B?style=for-the-badge&logo=strapi&logoColor=ffffff"/>
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=ffffff"/>
</p>

<h2 id="project" align="center">
  Projeto :technologist:
</h2>
<p align="center">
  O projeto foi feito com o intuito de reforçar os meus estudos e testar as minhas capacidades. Utilizei o Strapi + React para construir e gerir a api, bem como, o <a href="https://cloudinary.com/">Cloudinary</a> para hospedar as imagens que serão lidas no front-end e o <a href="https://www.elephantsql.com/">ElephantSQL</a> para gerenciar o banco de dados postgreSQL, onde serão salvos os dados criados no strapi.
</p>

<h2 id="install" align="center">
  Instalação :rocket:
</h2>
<p align="center">
  Nota: O Strapi necessita de uma arquivo .env na raiz do projeto, segue a estrutura e chaves que é preciso criar. Projeto conta com arquivos de configuração para o heroku.
  
  <table border="1" align="center">
    <tr align="center">
      <td><strong>Variaveis</strong></td>
      <td><strong>Valor</strong></td>
    </tr>
    <tr align="center">
        <td>HOST</td>
        <td title="Ip do Host">0.0.0.0</td>
    </tr>
    <tr align="center">
        <td>PORT</td>
        <td title="Porta do host">1337</td>
    </tr>
    <tr align="center">
        <td>APP_KEYS</td>
        <td title="Chaves de aplicativo">Números e letras</td>
    </tr>
    <tr align="center">
        <td>API_TOKEN_SALT</td>
        <td title="Token da API">Números e letras</td>
    </tr>
    <tr align="center">
        <td>ADMIN_JWT_SECRET</td>
        <td title="Chave secreta JWT">Números e letras</td>
    </tr>
    <tr align="center">
        <td>DATABASE_HOST</td>
        <td title="Ip do banco de dados">IP do BD</td>
    </tr>
    <tr align="center">
        <td>DATABASE_NAME</td>
        <td title="Nome da base de dados">Nome do BD</td>
    </tr>
        <tr align="center">
        <td>DATABASE_USERNAME</td>
        <td title="Nome do usuário da base de dados">Nome do user do BD</td>
    </tr>
        <tr align="center">
        <td>DATABASE_PASSWORD</td>
        <td title="Senha da base de dados">Senha do BD</td>
    </tr>
        <tr align="center">
        <td>DATABASE_SSL</td>
        <td title="SSL da base de dados">true ou false</td>
    </tr>
        <tr align="center">
        <td>CLOUDINARY_NAME</td>
        <td title="Nome do cloudinary em dashboard">Nome do Cloud</td>
    </tr>
        <tr align="center">
        <td>CLOUDINARY_KEY</td>
        <td title="Chave do cloudinary em dashboard">Key do Cloud</td>
    </tr>
        <tr align="center">
        <td>CLOUDINARY_SECRET</td>
        <td title="Chave secreta do cloudinary em dashboard">Key Secret do Cloud</td>
    </tr>
        <tr align="center">
        <td>JWT_SECRET</td>
        <td title="Chave JWT">Números e letras</td>
    </tr>
  </table>
  
  <div align="center">
    <a href=".env.example">Exemplo de .env(renomear depois de preencher)</a>
  </div>
  
  <h3 align="left">Passo a Passo</h3>
  <ol>
    <li>Instale o Node com o NPM pelo link: https://nodejs.org/en/download/</li>
    <li>Depois baixe os arquivos do projeto e excute o terminal dentro da pasta onde contém os arquivos.</li>
    <li>Agora execute os comandos no terminal:</li>
    <ul>
      <li title="Instala as dependencias">npm install</li>
      <li title="Inicia a API do Strapi">npm run develop</li>
    </ul>
  </ol>
</p>

<h2 id="license" align="center">
  Licença 📝
</h2>
<p align="center">
  Esse projeto está sob a licença MIT. Veja o arquivo <a href="LICENSE"> LICENSE </a> para mais detalhes.<br><br>
  <a href="LICENSE" target="_blank"><img src="https://img.shields.io/static/v1?label=license&message=mit&color=green&style=for-the-badge&logo="/></a>   
</p>

