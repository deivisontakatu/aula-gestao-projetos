# 📊 EAP — Estrutura Analítica do Projeto

---

## 📌 Identificação

| Campo | Informação |
|---|---|
| **Projeto** | [Nome do projeto] |
| **Gerente do projeto** | [Nome] |
| **Data** | [DD/MM/AAAA] |
| **Versão** | [1.0] |

---

## 🧩 Estrutura Analítica do Projeto

```text
PROJETO
│
├── 1. [ENTREGA / FASE]
│   ├── 1.1 [Pacote de trabalho]
│   ├── 1.2 [Pacote de trabalho]
│   └── 1.3 [Pacote de trabalho]
│
├── 2. [ENTREGA / FASE]
│   ├── 2.1 [Pacote de trabalho]
│   ├── 2.2 [Pacote de trabalho]
│   └── 2.3 [Pacote de trabalho]
│
├── 3. [ENTREGA / FASE]
│   ├── 3.1 [Pacote de trabalho]
│   ├── 3.2 [Pacote de trabalho]
│   └── 3.3 [Pacote de trabalho]
│
└── 4. [ENTREGA / FASE]
    ├── 4.1 [Pacote de trabalho]
    ├── 4.2 [Pacote de trabalho]
    └── 4.3 [Pacote de trabalho]
```

---

## 📋 Dicionário da EAP

| Código | Elemento | Descrição |
|---|---|---|
| 1.0 | [Entrega / Fase] | [Descrição] |
| 1.1 | [Pacote de trabalho] | [Descrição] |
| 1.2 | [Pacote de trabalho] | [Descrição] |
| 1.3 | [Pacote de trabalho] | [Descrição] |
| 2.0 | [Entrega / Fase] | [Descrição] |
| 2.1 | [Pacote de trabalho] | [Descrição] |
| 2.2 | [Pacote de trabalho] | [Descrição] |
| 2.3 | [Pacote de trabalho] | [Descrição] |
| 3.0 | [Entrega / Fase] | [Descrição] |
| 3.1 | [Pacote de trabalho] | [Descrição] |
| 3.2 | [Pacote de trabalho] | [Descrição] |
| 3.3 | [Pacote de trabalho] | [Descrição] |
| 4.0 | [Entrega / Fase] | [Descrição] |
| 4.1 | [Pacote de trabalho] | [Descrição] |
| 4.2 | [Pacote de trabalho] | [Descrição] |
| 4.3 | [Pacote de trabalho] | [Descrição] |

---

## 📝 Orientações

A **EAP (Estrutura Analítica do Projeto)** representa uma decomposição hierárquica do escopo do projeto.

Ela organiza o projeto em entregas e componentes menores, facilitando o planejamento, acompanhamento e controle.

### 📌 Estrutura da EAP

- **Projeto:** nível mais alto da estrutura.
- **Entrega / Fase:** principais componentes do projeto.
- **Pacote de trabalho:** menor nível utilizado para planejamento e controle.

### ⚠️ Atenção

A EAP deve representar **o que será entregue pelo projeto**, e não simplesmente uma lista de atividades.

**Evite:**

- ❌ Fazer reunião
- ❌ Programar sistema
- ❌ Fazer testes
- ❌ Enviar e-mail

**Prefira:**

- ✅ Sistema desenvolvido
- ✅ Sistema testado
- ✅ Documentação produzida
- ✅ Sistema implantado

---

## 🔎 Exemplo

Considere um projeto de desenvolvimento de um aplicativo.

```text
DESENVOLVIMENTO DE APLICATIVO
│
├── 1. PLANEJAMENTO
│   ├── 1.1 Requisitos definidos
│   └── 1.2 Plano do projeto
│
├── 2. DESIGN
│   ├── 2.1 Protótipo
│   └── 2.2 Interface
│
├── 3. DESENVOLVIMENTO
│   ├── 3.1 Backend
│   └── 3.2 Frontend
│
├── 4. TESTES
│   ├── 4.1 Testes funcionais
│   └── 4.2 Testes de integração
│
└── 5. IMPLANTAÇÃO
    ├── 5.1 Ambiente configurado
    └── 5.2 Aplicativo publicado
```

---

## 📚 Exemplo de Dicionário

| Código | Elemento | Descrição |
|---|---|---|
| 1.0 | Planejamento | Definição inicial do projeto |
| 1.1 | Requisitos definidos | Levantamento e documentação dos requisitos |
| 1.2 | Plano do projeto | Definição das principais informações de planejamento |
| 2.0 | Design | Definição da solução visual |
| 2.1 | Protótipo | Modelo inicial da aplicação |
| 2.2 | Interface | Interfaces definidas |
| 3.0 | Desenvolvimento | Construção da aplicação |
| 3.1 | Backend | Serviços e regras de negócio |
| 3.2 | Frontend | Interface da aplicação |
| 4.0 | Testes | Verificação da solução |
| 4.1 | Testes funcionais | Validação das funcionalidades |
| 4.2 | Testes de integração | Validação da integração entre componentes |
| 5.0 | Implantação | Disponibilização da aplicação |
| 5.1 | Ambiente configurado | Ambiente preparado para implantação |
| 5.2 | Aplicativo publicado | Aplicação disponibilizada aos usuários |

---

## ✅ Checklist

- [ ] O projeto está representado no nível superior
- [ ] As principais entregas foram identificadas
- [ ] As entregas foram decompostas
- [ ] Os pacotes de trabalho foram definidos
- [ ] Os elementos possuem códigos
- [ ] A EAP representa entregas
- [ ] O escopo completo foi contemplado
- [ ] O dicionário da EAP foi preenchido
- [ ] A estrutura foi revisada pela equipe
