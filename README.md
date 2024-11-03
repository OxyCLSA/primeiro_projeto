# Projeto de Site de Vendas

Este é um projeto de um site de vendas desenvolvido utilizando diversas tecnologias modernas para o backend e frontend.

## Tecnologias Utilizadas

- **Java**: Linguagem de programação principal.
- **Spring Framework**: Utilizado para a construção do backend.
- **Maven**: Ferramenta de automação de compilação e gerenciamento de dependências.
- **JPA (Java Persistence API)**: Utilizado para a persistência de dados.
- **Hibernate**: Implementação do JPA.
- **PostgreSQL**: Banco de dados relacional.
- **Frontend**: Tecnologias e frameworks utilizados para a interface do usuário.

## Estrutura do Projeto

- `src/main/java`: Código fonte do backend.
- `src/main/resources`: Arquivos de configuração e recursos.
- `src/main/webapp`: Arquivos do frontend (HTML, CSS, JavaScript).

## Configuração do Ambiente

1. **Clone o repositório**:
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```

2. **Navegue até o diretório do projeto**:
    ```bash
    cd seu-repositorio
    ```

3. **Compile o projeto utilizando Maven**:
    ```bash
    mvn clean install
    ```

4. **Configure o banco de dados PostgreSQL**:
    - Crie um banco de dados chamado `vendas`.
    - Atualize as configurações de conexão no arquivo `application.properties`.

5. **Execute a aplicação**:
    ```bash
    mvn spring-boot:run
    ```

## Contribuição

Sinta-se à vontade para contribuir com o projeto. Para isso, siga os passos abaixo:

1. Faça um fork do projeto.
2. Crie uma nova branch (`git checkout -b feature/nova-feature`).
3. Faça commit das suas alterações (`git commit -m 'Adiciona nova feature'`).
4. Faça push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo LICENSE para mais detalhes.
