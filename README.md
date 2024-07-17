# Sistema Voll Med

## Descrição do Projeto

O projeto desenvolvido é um sistema para uma clínica médica fictícia chamada Voll Med. O objetivo é criar um aplicativo que permita cadastrar, listar, atualizar e excluir informações de médicos, pacientes e consultas, construindo assim um CRUD completo para gerenciar os dados da clínica.

## Tecnologias Utilizadas

- **Spring Boot 3**: Utilizado como framework principal para construir a API Rest. O Spring Boot é uma ferramenta poderosa que facilita o desenvolvimento de aplicações web em Java.
- **MySQL**: Banco de dados relacional escolhido pela sua popularidade e robustez.
- **Flyway**: Utilizado para gerenciar as migrações do banco de dados, garantindo controle de versão e consistência.
- **JPA (Java Persistence API)**: Camada de persistência implementada utilizando o Hibernate como a implementação da JPA.
- **Lombok**: Ferramenta utilizada para tornar o código mais conciso, gerando automaticamente métodos como getters, setters, toString, entre outros.
- **Maven**: Gerenciador de dependências do projeto e ferramenta para gerar o build da aplicação.
- **Insomnia**: Ferramenta utilizada para testar a API, permitindo simular requisições HTTP.

## Funcionalidades

- **Cadastro de Médicos**: Permite adicionar novos médicos ao sistema.
- **Listagem de Médicos**: Exibe uma lista com todos os médicos cadastrados.
- **Atualização de Médicos**: Permite atualizar as informações de médicos existentes.
- **Exclusão de Médicos**: Permite excluir médicos do sistema.
- **Cadastro de Pacientes**: Permite adicionar novos pacientes ao sistema.
- **Listagem de Pacientes**: Exibe uma lista com todos os pacientes cadastrados.
- **Atualização de Pacientes**: Permite atualizar as informações de pacientes existentes.
- **Exclusão de Pacientes**: Permite excluir pacientes do sistema.
- **Cadastro de Consultas**: Permite agendar novas consultas.
- **Listagem de Consultas**: Exibe uma lista com todas as consultas agendadas.
- **Atualização de Consultas**: Permite atualizar as informações de consultas agendadas.
- **Exclusão de Consultas**: Permite cancelar consultas agendadas.

## Estrutura do Projeto

O projeto está organizado em camadas seguindo o padrão MVC (Model-View-Controller) para garantir uma separação clara das responsabilidades e facilitar a manutenção do código.

1. **Model**: Contém as classes que representam as entidades do sistema.
2. **Repository**: Interface responsável pela comunicação com o banco de dados.
3. **Service**: Contém a lógica de negócio.
4. **Controller**: Responsável por receber as requisições e retornar as respostas apropriadas.


