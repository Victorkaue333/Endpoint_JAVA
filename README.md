# 🚀 Endpoint JAVA - API RESTful com Spring Boot

API RESTful desenvolvida com Spring Boot 3.5.7 e Java 17, demonstrando a criação de endpoints modulares e boas práticas de desenvolvimento back-end.

## 📋 Sobre o Projeto

Este projeto é uma API REST construída com Spring Boot, estruturada em módulos de controllers para facilitar a organização e escalabilidade. Atualmente, implementa endpoints de teste e validação, servindo como base para aplicações mais complexas.

## 🛠️ Tecnologias Utilizadas

- **Java 17** - Linguagem de programação
- **Spring Boot 3.5.7** - Framework principal
- **Spring Web** - Criação de APIs REST
- **Lombok** - Redução de código boilerplate
- **Maven** - Gerenciamento de dependências
- **Spring Boot Test** - Testes automatizados

## 📁 Estrutura do Projeto

```
Endpoint_JAVA/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/testemod00/i1emotional00/
│   │   │       ├── I1emotional00Application.java
│   │   │       ├── controllerMol1/
│   │   │       │   └── ControllerModulo.java
│   │   │       ├── controllerMol2/
│   │   │       │   └── ControllerModuloTwo.java
│   │   │       └── controllerMol3/
│   │   │           └── ControllerModuloThree.java
│   │   └── resources/
│   │       └── application.properties
│   └── test/
│       └── java/
├── pom.xml
└── README.md
```

## 🚀 Como Executar

### Pré-requisitos

- Java 17 ou superior
- Maven 3.6 ou superior

### Passos para Execução

1. **Clone o repositório**
   ```bash
   git clone https://github.com/Victorkaue333/Endpoint_JAVA.git
   cd Endpoint_JAVA
   ```

2. **Compile o projeto**
   ```bash
   mvnw clean install
   ```

3. **Execute a aplicação**
   ```bash
   mvnw spring-boot:run
   ```

4. **A aplicação estará disponível em:**
   ```
   http://localhost:8080
   ```

## 📡 Endpoints Disponíveis

### Módulo 1

#### GET `/api/v1/ping`
Endpoint de teste para verificar se a API está funcionando.

**Resposta:**
```json
{
  "message": "Kauê"
}
```

**Exemplo de requisição:**
```bash
curl http://localhost:8080/api/v1/ping
```

## 🔧 Configurações

As configurações da aplicação estão localizadas em `src/main/resources/application.properties`:

```properties
spring.application.name=i1emotional00
server.port=8080
```

## 🧪 Executar Testes

```bash
mvnw test
```

## 📦 Build para Produção

Para gerar o arquivo JAR executável:

```bash
mvnw clean package
```

O arquivo `.jar` será gerado em `target/i1emotional00-0.0.1-SNAPSHOT.jar`

Para executar o JAR:

```bash
java -jar target/i1emotional00-0.0.1-SNAPSHOT.jar
```

## 🔄 Próximos Passos

- [ ] Implementar endpoints nos módulos 2 e 3
- [ ] Adicionar camada de serviços
- [ ] Integrar banco de dados
- [ ] Implementar autenticação e autorização
- [ ] Adicionar documentação Swagger/OpenAPI
- [ ] Implementar tratamento global de exceções
- [ ] Adicionar validações de entrada
- [ ] Configurar perfis de ambiente (dev, prod)

## 👤 Autor

**Victor Kaue**

- GitHub: [@Victorkaue333](https://github.com/Victorkaue333)

## 📄 Licença

Este projeto está sob a licença MIT.

---

⭐ Se este projeto foi útil para você, considere dar uma estrela no repositório!
Endpoint utilizado para validação de módulos feitos com o front em Flutter e o back em Java
