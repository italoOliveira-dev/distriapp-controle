# 🚀 DistriApp Controle

O **DistriApp Controle** é um sistema em desenvolvimento para auxiliar no gerenciamento de processos internos de uma distribuidora, com foco em **clientes, estoque e pedidos**.  

Este projeto também tem como objetivo aplicar **boas práticas de DevOps**, utilizando integração contínua, automação e versionamento organizado desde o início.

---

## 🧩 Stack Tecnológica
- **Backend:** Spring Boot  
- **Frontend:** Angular  
- **Banco de Dados:** PostgreSQL
- **Infra & DevOps:** Docker + GitHub Actions + Git Flow simplificado  

---

## 📂 Estrutura do Repositório

```
    - /distriapp-controle
    ├── backend/ → Projeto Spring Boot
    ├── frontend/ → Projeto Angular
    ├── docs/ → Documentação
    ├── docker/ → Arquivos Docker/Docker Compose
    ├── .github/workflows/ → Workflows de CI/CD
    └── README.md
```


---

## 🔄 Fluxo de Desenvolvimento
- `main` → somente versões estáveis (produção).  
- `develop` → integração das features finalizadas.  
- `feature/*` → desenvolvimento de novas funcionalidades.  
- `hotfix/*` → correções urgentes.  

👉 Nenhum push direto em `main` ou `develop`.  
👉 Todo merge deve ser feito via **Pull Request**.  

---

## 🎯 Objetivo do MVP
A primeira versão deve contemplar:
- [ ] Login e autenticação de usuários  
- [ ] Gestão de clientes (CRUD)  
- [ ] Gestão de produtos/estoque  
- [ ] Gestão de pedidos/vendas  
- [ ] Relatórios básicos (ex.: vendas por período)  

---

## 🤝 Contribuição
Este é um projeto pessoal em desenvolvimento, mas ideias e sugestões são bem-vindas!  

---

## 📌 Status
🚧 Em desenvolvimento (versão inicial / setup do projeto).  

