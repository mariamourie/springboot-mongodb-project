# Projeto de API Restful

# Sobre o projeto

Esse projeto foi proposto no curso "Programação Orientada a Objetos com Java" da plataforma Udemy, ministrado pelo professor Nélio Alves. O projeto foi estruturado conforme as camadas lógicas e o modelo de domínio. Com esse projeto, foi possível compreender as principais diferenças entre o paradigma orientado a documentos e o relacional. Uma implementação das operações de CRUD foi feita no projeto com as entidades do modelo de domínio.

## Funcionalidades

Na camada de serviço, é possível realizar as seguintes operações relacionadas ao usuário:

- Buscar todos os usuários
- Buscar usuário por id
- Inserir um novo usuário
- Remover um usuário
- Atualizar dados de um usuário

Já com a entidade Post, é possível realizar as seguintes operações na camada de serviço:

- Buscar um post por id
- Buscar post por título
- Buscar post por texto, data mínima ou data máxima

## Modelo do domínio
![Modelo do domínio](./src/assets/Modelo%20de%20domínio.png)

## Instância do domínio
![Instância do domínio](./src/assets/Instância%20do%20domínio.png)

## Camadas lógicas
![Camadas lógicas](./src/assets/Camadas%20Lógicas.png)

# Tecnologias utilizadas

[![Tecnologias do projeto](https://skillicons.dev/icons?i=java,spring,hibernate,mongodb&theme=light)](https://skillicons.dev)

# Ferramentas utilizadas

[![Ferramentas utilizadas no projeto](https://skillicons.dev/icons?i=eclipse,postman,maven,git&theme=light)](https://skillicons.dev)

# Como executar o projeto

Pré-requisitos: Java 

```bash
# clonar repositório
git clone https://github.com/mariamourie/springboot-mongodb-project.git

# entrar na pasta da aplicação
cd src/main/java/com/mariamourie/workshopmongo

# executar o projeto
./mvnw spring-boot:run
```

# Autor

Maria Eduarda Leitão da Cruz

https://www.linkedin.com/in/maria-eduarda-cruz