# FutureOfWorkAPI (C# / .NET 8) – Global Solution 2025-2  
API RESTful desenvolvida para o tema **“O Futuro do Trabalho”**, permitindo gerenciar **Cursos** e **Profissionais** e oferecendo uma base sólida para soluções de requalificação profissional dentro do ecossistema tecnológico moderno.

## 👥 Integrantes do Grupo
- **Leonardo Mansur – RM551659**  
- **Gabriel Oliveira – RM98565**  
- **Gabriel Riqueto – RM98685**  

---

## 🎯 Objetivo do Projeto
A aplicação tem como foco simular um ambiente de **capacitação e desenvolvimento profissional**, permitindo:

- Cadastrar e gerenciar **cursos de especialização**  
- Registrar e consultar **profissionais** interessados em requalificação  
- Expor endpoints REST organizados, versionados e documentados  
- Persistir dados utilizando **Entity Framework Core + SQLite**  
- Ilustrar um fluxo simples e completo de uma API profissional em .NET 8  

O projeto foi construído seguindo boas práticas de desenvolvimento, organização em camadas, documentação com Swagger e padrões modernos da plataforma .NET.

---

## 🏗 Arquitetura (Mermaid)
```mermaid
flowchart LR
    Client["Cliente (Swagger / Postman)"] -->|HTTP| Ctrl[Controllers]
    Ctrl --> AppCamada[Aplicação]
    AppCamada --> Db[(SQLite via Entity Framework Core)]
