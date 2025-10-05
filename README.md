# Cadastro Pessoas Monolito 2025.2

Aplicação monolítica Spring Boot para gerenciamento de pessoas modernizada para 2025.2.

## Características
- **Arquitetura Monolítica**: Frontend e backend integrados
- **Spring Boot**: Framework Java
- **Thymeleaf**: Template engine para views
- **H2 Database**: Banco em memória
- **Bootstrap**: Framework CSS

## Funcionalidades
- CRUD completo de pessoas
- Interface web integrada
- Validação de formulários
- Persistência em banco H2

## Tecnologias
- Java 17
- Spring Boot 3.2.0
- Spring MVC
- Thymeleaf
- H2 Database
- Bootstrap 4

## Execução
```bash
./mvnw spring-boot:run
```

Acesso: `http://localhost:8080`

## Mudanças da Modernização
- Atualizado Spring Boot de 2.6.4 para 3.2.0
- Atualizado Java de 1.8 para 17
- Migrado imports JPA de javax.persistence para jakarta.persistence
- Mantida compatibilidade total com funcionalidades existentes