<h1 align="center">
	<img src="./github/assets/ceres.png"  alt="Logo"  width="240"><br><br>
    Projeto Ceres
</h1>

<div align="center">
    <a href="https://www.typescriptlang.org/">
        <img src="https://img.shields.io/static/v1?label=Linguagem&message=Typescript&color=blue&style=for-the-badge&logo=Typescript" alt="Linguagem: Typescript">
    </a>
    <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript">
        <img src="https://img.shields.io/static/v1?label=Linguagem&message=Javascript&color=yellow&style=for-the-badge&logo=JavaScript" alt="Linguagem: Javascript">
    </a>
    <a href="https://www.java.com/">
		<img  src="https://img.shields.io/static/v1?label=Linguagem&message=Java&color=red&style=for-the-badge&logo=openjdk"  alt="Linguagem: Java">
	</a>
	<a href="https://spring.io/projects/spring-boot">
		<img src="https://img.shields.io/badge/Spring-6DB33F?label=Framework&style=for-the-badge&logo=spring&logoColor=green"  alt="Linguagem: Springboot">
    </a>
    <a href="https://react.dev/">
		<img src="https://img.shields.io/badge/React-20232A?label=Biblioteca&color=blue&style=for-the-badge&logo=react&logoColor=61DAFB"  alt="Biblioteca: React">
    </a>
     <a href="https://www.mysql.com/">
		<img src="https://img.shields.io/badge/MySQL-005C84?label=Banco de Dados&color=darkgray&style=for-the-badge&logo=mysql&logoColor=white"  alt="Banco de Dados: Mysql">
    </a>
</div>

<h2 align="center">Sumário</h2>

<p align="center">
    <a href="#sobre">Sobre</a> •
    <a href="#objetivos">Objetivos</a> •
    <a href="#banco-de-dados">Banco De Dados</a> •
    <a href="#contribuições">Contribuições</a> •
    <a href="#membros">Membros</a> •
    <a href="#licença">Licença</a>
</p>

## 📌Sobre

<div>
    <p align="center">
    <em>
        Um aplicativo voltado para distribuição e aumento de visibilidade de produtores locais e produtos para agricultores. Preços descentralizados do mercado padrão (idealmente menores) voltados para a população vulnerável das cidades.
        <br><br>
    </em>
    </p>
</div>

## 🎯Objetivos

<div>
    <p align="center">
    <em>
        Estimular a agricultura local, o estímulo para agriculturas orgânicas, evitar o desperdício de alimentos e garantir a qualidade dos mercados de commodities de alimentos.
        <br><br>
    </em>
    </p>
</div>

## 🗃Banco de Dados

### Tabela: tb_produtos

|        Atributo        |                               Descrição e motivo da escolha                                | Chave |
| :--------------------: | :----------------------------------------------------------------------------------------: | :---: |
|       id BIGINT        |             Identificador único de cada produto para registro de cada produto.             | PK AI |
|   nome VARCHAR(255)    |             Nome do produto, para identificar e descrever o produto anunciado.             |  NN   |
|  preco DECIMAL(10,2)   |                  Preço do produto para identificar o seu valor agregado.                   |  NN   |
|     quantidade INT     |                 Quantidade de produtos disponíveis para gestão do estoque.                 |  NN   |
| descricao VARCHAR(255) | Nome da descrição para determinar quais são os detalhes do produto que está sendo vendido. |  NN   |
|  imagem VARCHAR(255)   |         Url para carregar a imagem do produto e identificar o produto visualmente.         |  NN   |
|  categorias_id BIGINT  |                       Foreign key para conectar a tabela categorias.                       |  FK   |
|   usuarios_id BIGINT   |                        Foreign key para conectar a tabela usuários.                        |  FK   |

### Tabela: tb_usuarios

|       Atributo        |                      Descrição e motivo da escolha                      | Chave |
| :-------------------: | :---------------------------------------------------------------------: | :---: |
|       id BIGINT       |        Identificador do usuário para registro de cada produtor.         | PK AI |
|   nome VARCHAR(255)   |           Registro do nome e identificar o nome do produtor.            |  NN   |
|  email VARCHAR(255)   | Para atribuir o email e possibilitar o acesso do produtor a plataforma. |  NN   |
|  senha VARCHAR(255)   | Para criar uma senha e possibilitar o acesso do produtor a plataforma.  |  NN   |
|   foto VARCHAR(255)   |          Para identificar e visualizarmos a foto do produtor.           |  NN   |
| telefone VARCHAR(255) |            Para podermos ligar para o usuário caso precise.             |  NN   |
|   tipo VARCHAR(255)   |              Para podermos diferenciar o tipo de usuário.               |  NN   |

### Tabela: tb_categorias

|        Atributo        |                               Descrição e motivo da escolha                               | Chave |
| :--------------------: | :---------------------------------------------------------------------------------------: | :---: |
|       Id BIGINT        |          Identificador único de cada categoria para registro de cada categoria.           | PK AI |
|   nome VARCHAR(255)    | Nome da categoria para identificar o nome da categoria em que o produto está relacionado. |  NN   |
| descricao VARCHAR(255) |                                  Descrição da categoria                                   |  NN   |

## 🤝Contribuições:

### Documentação:

```
git clone https://github.com/ceres03/docs.git
```

### Frontend:

```
git clone https://github.com/ceres03/frontend.git
```

### Backend:

```
git clone https://github.com/ceres03/backend.git
```

## Métodos API

https://drive.google.com/file/d/1jG756zsE9iijPAONx_oVKrkNAn4PsGKi/view?usp=sharing

## ❤Membros

<div>
    <p align="center">
        <a href="https://github.com/ceres03/docs/graphs/contributors">Documentação</a> •
        <a href="https://github.com/ceres03/backend/graphs/contributors">Backend</a> •
        <a href="https://github.com/ceres03/frontend/graphs/contributors">Frontend</a>
    </p>
</div>

<div align="center">

|                                                                                       <a href="https://github.com/carolinerinaldo">Caroline</a>                                                                                        |                                                                                       <a href="https://github.com/Guhfrontend">Gustavo</a>                                                                                       |                                                                                      <a href="https://github.com/jovesposito">João</a>                                                                                       |                                                                                       <a href="https://github.com/Juliohf">Júlio</a>                                                                                       |
| :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| <a href="https://github.com/carolinerinaldo"><img src="https://avatars.githubusercontent.com/u/152224702?v=4" title="Caroline" alt="Caroline" width="100" height="100" style="border-radius:100%!important;display:inline-block"/></a> | <a href="https://github.com/Guhfrontend"><img src="https://avatars.githubusercontent.com/u/138324368?v=4" title="Gustavo" alt="Gustavo" width="100" height="100" style="border-radius:100%!important;display:inline-block"/></a> | <a href="https://github.com/jovesposito"><img src="https://avatars.githubusercontent.com/u/156468842?v=4" title="João"  alt="João" width="100" height="100" style="border-radius:100%!important;display:inline-block" /></a> | <a href="https://github.com/Juliohf"><img src="https://avatars.githubusercontent.com/u/108244681?v=4" title="Júlio"  alt="Júlio" width="100" height="100" style="border-radius:100%!important;display:inline-block" /></a> |

|                                                                                      <a href="https://github.com/sarassaura">Sarah</a>                                                                                       |                                                                                      <a href="https://github.com/Rojinhas">Ruth</a>                                                                                      |                                                                                        <a href="https://github.com/ouxnq">Vinícius</a>                                                                                        |
| :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| <a href="https://github.com/sarassaura"><img src="https://avatars.githubusercontent.com/u/141577271?v=4" title="Sarah" alt="Sarah" width="100" height="100" style="border-radius:100%!important;display:inline-block" /></a> | <a href="https://github.com/Rojinhas"><img src="https://avatars.githubusercontent.com/u/170153622?v=4" title="Ruth" alt="Ruth" width="100" height="100" style="border-radius:100%!important;display:inline-block" /></a> | <a href="https://github.com/ouxnq"><img src="https://avatars.githubusercontent.com/u/97247768?v=4" title="Vinícius"  alt="Vinícius" width="100" height="100" style="border-radius:100%!important;display:inline-block" /></a> |

</div>

## 📝Licença

Organização ©ceres, 2024. Todos os direitos reservados.

Esse projeto usa a licença [MIT](https://github.com/ceres03/docs/blob/main/LICENSE).
