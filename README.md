# Pass.in
[![NPM License](https://img.shields.io/npm/l/origin)](https://github.com/lucascesca/web-service-project/blob/main/LICENSE)

# Sobre o Projeto

O pass.in é uma aplicação de gestão de participantes em eventos presenciais que permite ao organizador cadastar um evento e abrir uma página de inscrição para este. Essa aplicação também fornece aos participantes um meio de emissão de credencial para o check-in no dia do evento.

## Requisitos 
### Funcionais
- O organizador deve poder cadastrar um novo evento;
- O organizador deve poder visualizar dados de um evento;
- O organizador deve poder visualizar a lista de participantes;
- O participante deve poder se inscrever em um evento;
- O participante deve poder visualizar seu crachá de inscrição;
- O participante deve poder realizar check-in no evento;

### Não-funcionais

- O check-in no evento será realizado através de um QRCode;

## Regras de Negócio

- O participante só pode se inscrever em um evento uma única vez;
- O participante só pode se inscrever em eventos com vagas disponíveis;
- O participante só pode realizar check-in em um evento uma única vez;

## Modelo Físico do Banco de Dados
![Modelo conceitual](https://github.com/lucascesca/assets/blob/main/Captura%20de%20tela%202024-04-04%20230237.png)

# Tecnologias Usadas

- Java
- Spring Boot
- JPA/Hibernate
- Maven
- HyperSQL

# Como executar o projeto

Pré-resquisitos: Java 17 e Maven

```bash
# clonar repositório
git clone https://github.com/lucascesca/pass-in

# entrar na pasta do projeto
cd pass-in

# executar o projeto
mvnw spring-boot:run
```

# Autor
Lucas Couto Cesca
 
https://www.linkedin.com/in/lucas-couto-cesca-53a691209/
