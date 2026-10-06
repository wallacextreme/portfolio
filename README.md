# Portfólio Profissional — Wallace Soares

[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub_Pages-2563eb?style=for-the-badge&logo=github&logoColor=white)](https://wallacextreme.github.io/portfolio/)
[![Formação](https://img.shields.io/badge/Graduado-Estácio_de_Sá-059669?style=for-the-badge&logo=academia&logoColor=white)](https://consultadiploma.estacio.br/diploma/163.163.80fed31e1b42)
[![Licença](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Ativo-success?style=for-the-badge)](#)

Portfólio profissional de **Wallace de Paula Soares** ([@wallacextreme](https://github.com/wallacextreme)), **Graduado em Análise e Desenvolvimento de Sistemas** pela **Universidade Estácio de Sá**. Apresenta projetos reais de nível de produção, competências técnicas e arquiteturais nas áreas de **Desenvolvimento Full Stack**, **Sistemas Offline-First**, **Progressive Web Apps (PWA)**, **Desktop (Tauri)** e **Game Development (Phaser 3)**.

---

## 🎓 Formação Acadêmica & Credenciais

* **Curso Superior de Tecnologia em Análise e Desenvolvimento de Sistemas** (Grau: Tecnólogo)  
  * **Instituição**: Universidade Estácio de Sá  
  * **Ano de Conclusão**: 2023 (Colação de Grau: 14/07/2023)  
  * **Código de Validação**: `163.163.80fed31e1b42`  
  * **Validação Oficial**: [Validar Diploma no Portal da Estácio](https://consultadiploma.estacio.br/diploma/163.163.80fed31e1b42)
  * **Currículo Completo**: Consulte o [CURRICULO.md](CURRICULO.md) ou a versão para impressão/PDF em [curriculo.html](curriculo.html).

---

## 🌐 Acesso Online

O portfólio está disponível publicamente com duas experiências visuais complementares:

* **Versão Principal (Moderna / Clean)**: [https://wallacextreme.github.io/portfolio/](https://wallacextreme.github.io/portfolio/)
  * *Design*: Minimalista, corporativo, acessível e com alternador de tema claro/escuro com persistência.
* **Versão Temática (Cyberpunk / Solo Leveling)**: [https://wallacextreme.github.io/portfolio/sololeveling.html](https://wallacextreme.github.io/portfolio/sololeveling.html)
  * *Design*: Estética gamer futurista, HUD com efeito scanline CRT sonoro via Web Audio API e fontes Orbitron & Exo 2.

---

## 🚀 Projetos em Destaque

### 1. [FiscalFlow — Gestão & Auditoria Fiscal Eletrônica](https://github.com/wallacextreme/FiscalFlow)
* **Stack**: Tauri 2 (Rust), TypeScript (Strict Mode), SQLite 3 local, WebAssembly (`sql.js`), Tailwind CSS, Vitest (126 testes).
* **Engenharia**: Ecossistema corporativo 100% Offline-First para gestão, auditoria e escrituração contábil de documentos fiscais (NF-e v4.00, NFC-e, NFS-e Padrão Nacional/ABRASF, CT-e e SPED Fiscal EFD ICMS/IPI). Validação do dígito verificador da Chave de Acesso via Módulo 11 da SEFAZ, desduplicação exata com hash SHA-256 e integridade referencial em banco relacional SQLite local.
* **Governança & Qualidade ISO**: Avaliado sob a norma **ISO/IEC 25010:2023** (9 características de qualidade de produto, scorecard executivo e safety fiscal) e alinhado aos processos do SGQ **ISO 9001:2026** (5 procedimentos operacionais, cultura da qualidade e foco climático).
* **Demo Online**: [https://wallacextreme.github.io/FiscalFlow/](https://wallacextreme.github.io/FiscalFlow/)

### 2. [Catálogo Técnico & Cross-Reference de Palhetas Automotivas](https://github.com/wallacextreme/catalogo-palhetas)
* **Stack**: Preact, TypeScript (Strict Mode), Tailwind CSS v4, PWA Offline-First, Tauri v2 (Desktop Windows), IndexedDB (Dexie.js), SQLite local, 29 testes automatizados (100% aprovados).
* **Engenharia**: Sistema profissional para consulta técnica, rastreabilidade oficial e equivalência cruzada (cross-reference) multi-catálogo de palhetas automotivas (DYNA 2025, CINOY 2023 e VETOR 2025). Exclusividade absoluta para veículos de linha leve (exclusão estrita de caminhões e linha pesada), desduplicação de aplicações redundantes em fichas unificadas, motor de busca com tokenização e busca booleana por medidas/posições, e arquitetura 100% offline-ready com cache total de base de dados.
* **Demo Online**: [https://wallacextreme.github.io/catalogo-palhetas/](https://wallacextreme.github.io/catalogo-palhetas/)

### 3. [Plataforma de Pizzaria Full-Stack](https://github.com/wallacextreme/pizzaria-platform)
* **Stack**: Next.js 15, React 19, TypeScript, Supabase, PostgreSQL com RLS granular, Tailwind CSS, Vitest.
* **Engenharia**: Painel administrativo com Kanban em tempo real via Supabase Realtime, segurança com Row Level Security e RBAC, regras de negócio e cálculos de moeda em centavos inteiros no backend, pipeline client-side de compressão Canvas para WebP e suíte de testes com Vitest.

### 4. [EtiquetaPro — Gerador de Etiquetas PWA](https://github.com/wallacextreme/etiquetapro)
* **Stack**: JavaScript Vanilla, PWA, Service Worker, Cache Storage API, CSS Paged Media.
* **Engenharia**: Motor de diagramação e impressão física milimétrica (`mm`) para 21 gabaritos Pimaco homologados (A4 e Carta), fila dinâmica de impressão, funcionamento 100% offline e instalação nativa PWA sem frameworks pesados.
* **Demo Online**: [https://wallacextreme.github.io/etiquetapro/](https://wallacextreme.github.io/etiquetapro/)

### 5. [Controle de Entregas — Autopeças (PWA Logística)](https://github.com/wallacextreme/controle-entregas-friburgo)
* **Stack**: JavaScript Vanilla ES6+, IndexedDB v2, PWA, Service Worker, CSS Paged Media.
* **Engenharia**: Arquitetura em camadas desacoplada (UI, Services, Repositories, DB) em arquivo único sem dependências externas. Quadro Kanban de 5 colunas com drag & drop nativo, visão mobile-first para motoboys com Waze/Maps/WhatsApp, módulo financeiro de acerto diário com saldo líquido, valores em centavos inteiros (eliminação do IEEE 754 float), máquina de estados estrita com 8 estados, prevenção de troco fantasma, serialização por mutex assíncrono e suíte de 136 testes automatizados.
* **Demo Online**: [https://wallacextreme.github.io/controle-entregas-friburgo/](https://wallacextreme.github.io/controle-entregas-friburgo/)

### 6. Controle de Pagamentos & ERP PRO
* **Stack**: Offline-First, Tauri (Desktop Windows .msi e .exe), IndexedDB, SQLite, Tailwind CSS, PWA.
* **Engenharia**: Arquitetura transacional local sem dependência de internet, rotinas de backup e restauração JSON, exportação CSV e distribuição desktop nativa para Windows.

### 7. Cinzas do Éter — JRPG 16-Bit
* **Stack**: Phaser 3, TypeScript, Vite, Bun, Vitest, Game Architecture.
* **Engenharia**: Arquitetura modular de jogos 2D com desacoplamento de entidades (Player Entity, Map Manager por camadas, Dialogue System dinâmico) e testes automatizados.

### 8. [Arcane Lore — Portal RPG](https://github.com/wallacextreme/Arcane-Lore)
* **Stack**: HTML5 Semântico, CSS3 Flexbox/Gradients, Bootstrap 5.3.0.
* **Engenharia**: Portal temático com telas de autenticação estilizadas e design responsivo cross-device.

---

## 🛠️ Tecnologias & Stack Oficial

* **Frontend**: TypeScript, JavaScript ES6+, React, Next.js, HTML5 Semântico, CSS3, Tailwind CSS, Bootstrap 5.
* **PWA & Armazenamento**: Service Workers, Cache Storage API, Web App Manifest, IndexedDB, SQLite.
* **Backend & Cloud**: Node.js, Express.js, PHP, Supabase (Auth, RLS, Storage, Realtime), Firebase, REST APIs.
* **Desktop & Games**: Tauri (.exe / .msi), Phaser 3 (2D Game Architecture), Bun, Vite.
* **Qualidade & Metodologia**: Vitest, Jest, Git & GitHub, Clean Architecture, Princípios SOLID, Desenvolvimento Assistido por IA.

---

## 📬 Canais & Contato Profissional

* **GitHub**: [@wallacextreme](https://github.com/wallacextreme)
* **LinkedIn**: [linkedin.com/in/wallacextreme](https://linkedin.com/in/wallacextreme)
* **E-mail**: [wallacextreme@hotmail.com](mailto:wallacextreme@hotmail.com)
* **X (Twitter)**: [@Wallace99341593](https://x.com/Wallace99341593)
* **TecnoService NF | IT Support & Services**: [@tecnoservicenf](https://www.instagram.com/tecnoservicenf) *(Empreendimento próprio em suporte técnico, montagem de estações de trabalho e infraestrutura de TI)*
* **Localização**: Rio de Janeiro - RJ, Brasil (Disponível para atuação Remota / Híbrida)

