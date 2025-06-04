# Projeto Mercadinho Online ![Project Status](https://img.shields.io/badge/status-em%20desenvolvimento-yellow)

![Created](https://img.shields.io/badge/criado_em-maio_2025-blue)
![Last Commit](https://img.shields.io/github/last-commit/pomptrash/projeto-mercadinho-online)

![React](https://img.shields.io/badge/React-20232a?logo=react&logoColor=61dafb) 
![Bootstrap](https://img.shields.io/badge/Bootstrap-563d7c?logo=bootstrap&logoColor=white) 
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) 
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?logo=mysql&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=white)



## Introdução

Como forma de praticar todo o conteúdo visto durante o meu segundo semestre de Análise e Desenvolvimento de Sistemas, resolvi criar esse projeto que consiste na junção de todas as matérias: 

- **Análise e modelagem de sistemas** *(levantar requisitos e criar os diagramas UML: de caso de uso e de classe)*,
- **Banco de dados** *(modelar o banco de dados de forma conceitual, lógica e física, utilizando MySQL)*,
- **Desenvolvimento de aplicações para a web** *(criar o mapa de site e wireframe do site)*,
- **Front-End frameworks** (será utilizado react.js + bootstrap.css)
- **POO** (aplicar a programação orientada a objetos para facilitar a estrutura do código)

## Objetivo

O projeto tem como objetivo disponibilizar, de forma online, os produtos de um mercado para que os clientes não precisem ir pessoalmente para fazer as compras, ou possam comprar online e ir até o mercado somente para resgatar a compra. O usuário vai poder acessar o site do mercado, escolher suas compras, adicionar no carrinho e efetivar o pagamento. Posteriormente, escolhe a forma que deseja receber as compras: Entrega a domicílio ou resgatar presencialmente no mercado. 

Nesse primeiro momento, os produtos serão todos genéricos, portanto, não haverão marcas diferentes e também não haverá sistema de estoque. Também não haverá sistema de Login. O histórico de compras será armazenado através do Local Storage.

---

A matéria de Back-End será iniciada somente no terceiro semestre da faculdade, mas adiantei um pouco do conteúdo de forma autodidata. Aprendi conceitos como rotas, métodos HTTP, endpoints, consumo e criação de APIs, etc. Durante o desenvolvimento desse projeto, pretendo aprimorar ainda mais meu conhecimento em Back-End. Será usado Python com Flask. Pretendo implementar a arquitetura MVC, organizando o Back-End em Models, Controllers e Views.

O método de gestão de projetos utilizado durante a criação desse projeto será uma mistura de **Scrum** *(Histórias de usuário, Backlog do produto e Backlog da Sprint, etc)* com **Metodologia tradicional** **em Cascata** (Especificação de requisitos funcionais/ não funcionais e documentação com a criação de diagramas UML). 

### Primeira fase: Levantamento de requisitos
Na primeira fase, definimos os requisitos que serão implementados no nosso sistema.

1. [Especificação de Requisitos Funcionais](docs/Requisitos/EspecificaçãoDeRequisitosFuncionais.md "Especificação de Requisitos Funcionais")
2. [Histórias de Usuário](docs/Requisitos/HistoriaDeUsuario.md "Histórias de Usuário")
3. [Backlog do produto](docs/Requisitos/BacklogProduto.md "Backlog do Produto")

### Segunda fase: Modelagem
Na segunda fase: criamos os Diagramas UML, modelamos o Banco de Dados de forma Conceitual, Lógica e Física e criamos os Wireframes.

1. [Diagramas UML - Caso de Uso e Classe](./docs/Modelagem/Diagramas-UML/diagramas-documentados.md "Documentação Diagramas UML")
2. [Modelagem Banco De Dados](./docs/Modelagem/Modelagem-Banco-De-Dados/modelagem-banco-de-dados-mercadinho-online.md "Documentação Modelagem do Banco De Dados")
3. [Mapa de Site e Wireframes](./docs/Prototipos/prototipagem.md "Documentação Mapa de Site e Wireframes")