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

### 3. [Plataforma de Pizzaria Full-Stack — Forno & Massa (PWA)](https://github.com/wallacextreme/pizzaria-platform)
* **Stack**: Next.js 15, React 19, TypeScript, Supabase (Auth, RLS, Realtime), PWA (`sw.js` + Manifest), Tailwind CSS, Vitest (**152 testes**).
* **Engenharia**: Painel administrativo com Kanban em tempo real via Supabase Realtime, Row Level Security e RBAC, cálculos em centavos inteiros no servidor, compressão WebP via Canvas API, PWA instalável e **Modo Demo Sandbox (`/demo`)** sem login para recrutadores.
* **Demo Sandbox Online**: [https://wallacextreme.github.io/pizzaria-platform/demo/](https://wallacextreme.github.io/pizzaria-platform/demo/)

### 4. [EtiquetaPro — Gerador de Etiquetas PWA](https://github.com/wallacextreme/etiquetapro)
* **Stack**: JavaScript Vanilla, PWA, Service Worker, Cache Storage API, CSS Paged Media.
* **Engenharia**: Motor de diagramação e impressão física milimétrica (`mm`) para 21 gabaritos Pimaco homologados (A4 e Carta), fila dinâmica de impressão, funcionamento 100% offline e instalação nativa PWA sem frameworks pesados.
* **Demo Online**: [https://wallacextreme.github.io/etiquetapro/](https://wallacextreme.github.io/etiquetapro/)

### 5. [Controle de Entregas Friburgo v5.1.0 (SaaS Pro Logística PWA)](https://github.com/wallacextreme/controle-entregas-friburgo)
* **Stack**: JavaScript ES6+, IndexedDB v3 (Outbox Offline), ISO 18004 QR Code, WebP Canvas POD, PWA, Playwright E2E.
* **Engenharia**: Roteirização por 4 corredores reais de Nova Friburgo (29 bairros com SLA e taxa sugerida), Despacho em Lote + Google Maps multi-paradas + QR Code offline, Comprovante POD WebP, bloqueio de Logística Reversa no acerto de caixa, Thumb-Zone Mobile + Modo Alto Contraste Solar e testes E2E Playwright.
* **Demo Recrutadores (`?demo=1`)**: [https://wallacextreme.github.io/controle-entregas-friburgo/?demo=1](https://wallacextreme.github.io/controle-entregas-friburgo/?demo=1)

### 6. [OmniDesk — Acesso Remoto P2P Zero-Trust](https://github.com/wallacextreme/omnidesk)
* **Stack**: Tauri v2 (Rust Win32 GDI & Lock-Free `SendInput`), WebRTC P2P Full HD 4:4:4, WSS Cloud Signaling, PBKDF2-SHA256, PWA.
* **Engenharia**: Acesso remoto de ultra-baixa latência 60 FPS com autenticaçãoZero-Trust (600.000 iterações PBKDF2), proteção anti-hijacking, ACL com Panic Button e transferência de arquivos SHA-256. Auditado ISO/IEC 25010:2023 e ISO 9001:2026.
* **PWA Live**: [https://omnidesk-remote.web.app](https://omnidesk-remote.web.app)

### 7. [EscalaPro CLT v2.0 — Gestão de Escalas PWA](https://github.com/wallacextreme/escalapro-clt)
* **Stack**: React 19, TypeScript 5.7, Vite 6, IndexedDB (Dexie), SheetJS (`xlsx`), Tauri v2, Vitest & Playwright E2E.
* **Engenharia**: Offline-First PWA com 6 motores de conformidade trabalhista CLT / EC 141/2026, exportação Excel e testes automatizados unitários e E2E.
* **Demo Online**: [https://wallacextreme.github.io/escalapro-clt/](https://wallacextreme.github.io/escalapro-clt/)

### 8. [DEFCON: Frontline — Tactical 3D Tower Defense PWA](https://github.com/wallacextreme/defcon-frontline)
* **Stack**: Three.js 0.187 (WebGL 3D), Vite 7, Save v3, PWA Offline-First.
* **Demo Online**: [https://wallacextreme.github.io/defcon-frontline/](https://wallacextreme.github.io/defcon-frontline/)

### 9. [Cinzas do Éter v1.0.0 — JRPG 16-Bit Original](https://github.com/wallacextreme/cinzas-do-eter)
* **Stack**: Phaser 3, TypeScript 6.0 Strict, Vite 8.2, Vitest (**370 testes**).
* **Engenharia**: Arquitetura 2D orientada a eventos (`EventBus` + FSM), interiores HD-2D/SNES, mapa-mundi completo e simulação Monte Carlo de combate.
* **Demo Online**: [https://wallacextreme.github.io/cinzas-do-eter/](https://wallacextreme.github.io/cinzas-do-eter/)

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

---
## ☕ Apoie este Projeto

Se este projeto ou código foi útil para você, considere apoiar o meu trabalho com uma doação espontânea de qualquer valor. Sua contribuição ajuda a manter o desenvolvimento de novas ferramentas e soluções open-source!

<details>
<summary><strong>💠 Clique aqui para exibir os dados do PIX (Doação Voluntária)</strong></summary>

<br>

- **Chave PIX (ALEATORIA):** `91afe4f0-a466-4423-9d9c-d6a0ffea9b3e`
- **Banco:** C6 Bank
- **Titular:** Wallace de Paulo Soares

> *Nota Legal: Contribuição 100% voluntária e espontânea de apoio ao desenvolvedor (Art. 538 do Código Civil).*
</details>
