# CRUD Pessoas - Monolito

Aplicação monolítica Spring Boot. Frontend e backend integrados.

## Stack
- Java 17
- Spring Boot 3.2.0
- Spring MVC + JPA
- Thymeleaf
- H2 Database
- Bootstrap

## Estrutura
```
src/main/
├── java/br/com/xico/cadpessoas/
├── resources/
│   ├── templates/        # Views Thymeleaf
│   ├── static/          # CSS/JS/Imagens
│   └── application.properties
```

## Funcionalidades
- CRUD completo pessoas
- Interface web integrada
- Validação formulários
- Persistência H2

## Execução
```bash
./mvnw spring-boot:run
```

Acesso: http://localhost:8080

## Migração 2025.2
- Spring Boot 2.6.4 → 3.2.0
- Java 8 → 17
- javax.persistence → jakarta.persistence