# 🧬 NeuroInsight: ALS/ELA Clinical & Molecular Dashboard
 
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

## 📝 Descrição do Projeto
O **NeuroInsight** é uma plataforma avançada de análise para pesquisa em Esclerose Lateral Amiotrófica (ELA/ALS). O sistema integra dados clínicos longitudinais com visualizações moleculares tridimensionais (via AlphaFold), permitindo que pesquisadores identifiquem correlações entre mutações genéticas específicas e a progressão fenotípica da doença.

Desenvolvido para oferecer uma visão holística da neurodegeneração, o dashboard processa métricas críticas como a escala **ALSFRS-R** (Revised ALS Functional Rating Scale) e a **Capacidade Vital Forçada (CVF)**, utilizando motores de visualização de alto desempenho para renderizar estruturas proteicas (como TDP-43 e SOD1) diretamente no navegador.

---
![Dashboard NeuroInsight](https://raw.githubusercontent.com/lucide-react/lucide/main/icons/layout-dashboard.svg)
*Figura 1: Interface principal integrando gráficos de tendência clínica e visualizador 3D molecular.*
 
## 🚀 Tecnologias Utilizadas
* **Frontend:** React 19 + TypeScript + Vite
* **Estilização:** Tailwind CSS (Arquitetura Utilitária)
* **Backend & Auth:** Firebase (Google Authentication & Firestore)
* **Visualização Biológica:** 3Dmol.js (Integração dinâmica com AlphaFold Database)
* **Analytics & Gráficos:** Recharts + D3.js
* **Animações:** Framer Motion (Transitions & Micro-interactions)
 
## 📊 Resultados e Funcionalidades
O projeto foi estruturado para garantir precisão científica e suporte à decisão clínica:
* **Visualização Multi-Escalar:** Integração nativa com a API do AlphaFold para carregamento automático de modelos PDB de proteínas associadas à ELA.
* **Monitoramento Crítico:** Sistema de alertas inteligentes para quedas de CVF (abaixo de 50%) ou declínios rápidos na pontuação ALSFRS-R.
* **Motor de Integridade:** Testes de lógica clínica automatizados que validam a consistência dos dados longitudinais dos pacientes.
* **Badges de Status:** Visualização clara do perfil genético (Mutação SOD1, C9orf72, Esporádica) via dashboard unificado.
 
![Gráfico de Performance e Métricas](https://raw.githubusercontent.com/lucide-react/lucide/main/icons/activity.svg)
*Figura 2: Análise métrica do desempenho do modelo e tendências de progressão respiratória.*
 
## 🔧 Como Executar
1. Clone o repositório.
2. Configure as credenciais do Firebase no arquivo de configuração do projeto.
3. Instale as dependências: `npm install`.
4. Execute o servidor de desenvolvimento: `npm run dev`.
 
![Demonstração do Fluxo de Dados](https://raw.githubusercontent.com/lucide-react/lucide/main/icons/database.svg)
*Figura 3: Representação visual do pipeline de dados entre Firestore e o motor de analytics.*
 
---
[Voltar ao início](https://github.com/profdiegocarvalho/portfolio-arthur-correia-carvalho)
