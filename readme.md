# 🌱 BioMonitor — Front-End (Angular)

Interface web do projeto **BioMonitor**, uma plataforma de monitoramento ambiental baseada em sensores IoT, desenvolvida como parte de um projeto full stack completo.

Este repositório contém o **Front-End**, responsável pela visualização dos dados, dashboards, gráficos e interação do usuário com a API RESTful.

---

## 🎯 Objetivo

Fornecer uma interface web moderna e responsiva para:

- Visualizar áreas ambientais monitoradas
- Acompanhar sensores IoT ativos e inativos
- Exibir leituras de temperatura e umidade em tempo real
- Analisar tendências climáticas por área
- Identificar alertas ambientais
- Garantir acesso seguro via autenticação

---

## 🖥️ Tecnologias Utilizadas

- **Angular** (Angular CLI)
- **TypeScript**
- **Tailwind CSS**
- **HTML5 / CSS3**
- **JWT** (autenticação)
- **Consumo de API RESTful**
- **Docker** (integração com ambiente de desenvolvimento)

---

## 🧩 Arquitetura do Front-End

O projeto segue boas práticas de organização Angular, incluindo:

- **Guards** para controle de rotas autenticadas
- **Interceptors** para injeção automática do token JWT
- **Services** para comunicação com a API
- **Models** para tipagem forte dos dados
- **Components** organizados por feature
- **Layout principal reutilizável**
- **Environment configs** para diferentes ambientes

---

## 📊 Funcionalidades

- Dashboard global com indicadores
- Seleção dinâmica de áreas monitoradas
- Gráficos de temperatura e umidade
- Integração total com dados reais do back-end
- Interface responsiva e moderna com Tailwind CSS

---

## 🔗 Integração com o Back-End

O front-end consome uma **API RESTful** desenvolvida em Node.js + TypeScript.

👉 Repositório do Back-End:  
**https://github.com/lucasaraujolp/biomonitor-backend**

---

## 🚀 Como executar o projeto

### Pré-requisitos
- Node.js (LTS)
- Angular CLI

### Instalação
```bash
npm install
