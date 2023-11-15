# Parking-control-API 🚘

#### Este projeto compreende o desenvolvimento de uma API destinada ao gerenciamento de vagas em um condomínio fictício. Importante destacar que o projeto ainda não atingiu sua versão final, permitindo a incorporação de diversas melhorias na estrutura, na lógica e a adição de novas funcionalidades.

## Índice 📑

- Funcionalidade
- Tecnologias utilizadas
- Futuras melhorias

## Funcionalidades 📲

O projeto foi construído em torno da arquitetura de software REST e o padrão CRUD, logo possui as seguintes funcionalidade;

->(Post) Criação de uma vaga (Parking Spot), contendo os seguintes dados;

- id
- Número da vaga
- placa do carro associado a vaga
- marca do carro 
- modelo do carro
- cor do carro
- data de registro
- Nome do dono
- Apartamento
- Bloco

->(GET) Um método para localizar uma vaga expecifica pelo seu id, ou listar todos as vagas salvas no banco de dados.

->(PUT) Um método para editar os dados de uma vaga salva no banco de dados.

->(DELET) Um método para deletar uma vaga salva no banco de dados.

## Tecnologias utilizadas 🛠️

![JAVA](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)![SPRING](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)![POSTGRESQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)![INTELIJ](https://img.shields.io/badge/IntelliJ_IDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)

#### Java v21 
#### SpringBoot v3.1.5 
#### Maven 
#### PgAdmin 4 
#### Intellij community 2023.2 
#### Apidog

## Futuras melhorias 🚀
Separação mais clara e objetiva das reponsabilidades de cada classe, afim de se obter um baixo aclopamento e facilidade nas modificações e manutenções. 

Criação de classes para regras de negócio, validações, filtros e tratamento de erros.

Crição de uma interfece gráfica para tornar o projeto mais amigável e funcional.
