# EcoEscola — proposta de backend

Proposta de sistema para análise de desperdício energético em escolas. A branch contém somente documentação; as funcionalidades descritas no planejamento não estão implementadas neste repositório.

## Tecnologias

- Documentação Markdown

## Funcionalidades e utilização

Leia a proposta abaixo. Não há backend, dependências ou comando de execução disponível nesta branch.

## Como executar

```bash
git clone https://github.com/EuGeanCarlos/eco-escola-energy-ai.git
cd eco-escola-energy-ai
```

Leia a proposta abaixo. Não há backend, dependências ou comando de execução disponível nesta branch.

## Demonstração e publicação

Execução local. Nenhuma demonstração nova foi confirmada nesta etapa.

GitHub Pages hospeda arquivos estáticos e não executa Java, Node.js, PHP ou Python. As dependências de servidor deste projeto devem ser executadas em ambiente apropriado.

## Estrutura versionada

```text
README.md
```

## Status

Protótipo / projeto de estudo em desenvolvimento. A descrição acima distingue o que está implementado das dependências ou etapas pendentes.

## Autor e créditos

**Gean Carlos** — estudante de Engenharia de Computação, UEMA.

[GitHub](https://github.com/EuGeanCarlos)

Licenças, autoria compartilhada e atribuições existentes no código e nos materiais originais permanecem aplicáveis.

---

## Documentação original e contexto

O material original a seguir preserva contexto, créditos e planejamento. Para execução e limitações atuais, considere as seções de auditoria acima.

# eco-escola-energy-ai
Back-end em Java com IA para identificar desperdício energético em escolas públicas.

# 🌱 EcoEscola — IA para Identificar Desperdício Energético em Escolas Públicas

O **EcoEscola** é um sistema inteligente desenvolvido em **Java + Spring Boot** que analisa o consumo energético de salas e equipamentos em escolas públicas.  
Seu objetivo é **detectar desperdícios**, gerar **alertas automáticos** e produzir **relatórios inteligentes** utilizando IA.

Este projeto une **back-end**, **simulação de dados**, **detecção inteligente** e **impacto socioambiental real**.

---

## ✨ Objetivo do Projeto

Ajudar escolas a reduzir:
- consumo desnecessário de energia  
- gastos mensais  
- impacto ambiental  

Tudo isso **sem necessidade de sensores reais**, usando dados simulados e lógica inteligente.

---

## 🧠 Como a IA funciona

O sistema usa duas camadas de inteligência:

### 1) **IA Local (sua lógica em Java)**
Algoritmos que detectam:
- uso fora do horário escolar  
- picos anômalos de consumo  
- equipamentos ineficientes  
- padrões de desperdício  

### 2) **IA Generativa (opcional)**
Modelos externos para:
- gerar relatórios explicativos  
- sugerir ações corretivas  
- traduzir os alertas técnicos para linguagem simples  

---

## 🔧 Tecnologias Utilizadas

**Back-end**
- Java 17+  
- Spring Boot 3  
- Spring Web  
- Spring Data JPA  
- Lombok  
- Validation  
- PostgreSQL  

**IA**
- Módulo de detecção criado em Java  
- Integração opcional com modelos generativos (OpenAI, Gemini, etc.)  

**Simulação**
- Gerador interno de consumo horário  
- Criação automática de picos e anomalias  

**Front-End**
- HTML  
- JavaScript  
- Chart.js  

---

## 🏗 Estrutura da Arquitetura

Front-End
↓

API REST (Java/Spring)

↓
Services (Lógica)

↓
IA Local → IA Generativa

↓
Banco de Dados (PostgreSQL)


Simulador → Registros → IA → Alertas → Dashboard

---

## 📁 Estrutura do Projeto

src/main/java/com/ecoescola/energy
├── controller
├── service
├── repository
├── model
├── dto
├── ia # Motor de IA local
├── simulator # Gerador de consumo
└── EcoEscolaApplication.java

src/main/resources
└── application.properties


---

## 🚀 Funcionalidades

- Cadastro de salas  
- Cadastro de equipamentos  
- Registro/simulação de consumo  
- Detecção automática de desperdício  
- Geração de alertas  
- Relatórios inteligentes (IA generativa)  
- Dashboard simples com gráficos  

---

## 🧪 Simulação de Consumo

O projeto não depende de medidores físicos.  
Um simulador interno gera:

- consumo por hora  
- picos aleatórios  
- falhas simuladas  
- padrões típicos de escolas  

Permite demonstrar IA + lógica sem depender de hardware.

---

## 🌍 Impacto Socioambiental

O projeto busca:
- reduzir desperdício de energia  
- reduzir custos em escolas públicas  
- diminuir emissões relacionadas  
- incentivar educação sobre sustentabilidade  
- democratizar o uso de IA no setor público  

---

## 🧭 Roadmap

- [x] Estrutura inicial do projeto  
- [ ] Criar entidades Sala e Equipamento  
- [ ] Criar simulador de consumo  
- [ ] Implementar motor de IA local  
- [ ] Registrar e armazenar alertas  
- [ ] Criar rotas REST  
- [ ] Desenvolver dashboard  
- [ ] Integração com IA generativa  
- [ ] Publicar versão demonstrativa  

---

## 🤝 Contribuições

Sinta-se livre para contribuir com melhorias, ideias, relatórios de bug ou testes.

---

## 📜 Licença

Este projeto é distribuído sob a licença MIT.

---

## ✉ Contato

Criado por **Gean Carlos**  
Especialização em **Back-End e Inteligência Artificial**.




## Validação desta auditoria — 14/10/2026

Sem publicação nova confirmada. Análise dos arquivos versionados concluída. Documentação preparada; execução local necessária.
