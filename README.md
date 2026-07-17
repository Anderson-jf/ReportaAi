# Plataforma ReportaAi 🏙️🦟

A **Plataforma ReportaAi** é um ecossistema integrado de GovTech focado em Cidades Inteligentes e Vigilância em Saúde. O sistema foi projetado para otimizar a identificação de anomalias urbanas (como buracos na pavimentação e descarte incorreto de entulhos). Atua como uma ferramenta de mapeamento epidemiológico, identificando potenciais focos de fossa cheia, entulho, vazamento... e etc.

---

## 🚀 Minha Atuação e Entregas no Ecossistema

O desenvolvimento do projeto foi baseado na metodologia ágil Scrum. Minhas contribuições concentraram-se na engenharia de interface e na arquitetura de resiliência dos módulos cliente:

### 📱 1. Aplicativo Mobile do Cidadão (`app-reportAi-frontend`)
Desenvolvimento da interface em **React Native (Expo)** focada no conceito de "cidadão como sensor voluntário".
- **Arquitetura Visual e Roteamento:** Construção de fluxo de navegação responsiva utilizando Expo Router.
- **Padrão Offline-First:** Implementação de persistência local assíncrona para permitir o registro de denúncias mesmo em áreas com sombra de conectividade, sincronizando os dados automaticamente em segundo plano após o reestabelecimento da rede.
- **Mecanismo Anti-Fraude (EXIF):** Integração de rotina forense para extrair programmaticamente os metadados nativos da foto (coordenadas GPS e timestamp originais da captura) para impedir uploads de imagens baixadas da internet ou antigas.
- **Segurança & LGPD:** Tela estruturada de Onboarding com termo de consentimento explícito para o tratamento de dados de geolocalização em total conformidade com a LGPD.

### 💻 2. Painel de Gestão Web (`zeladoria-web-dashboard`)
Co-desenvolvimento do MVP de administração voltado para o poder público municipal.
- **Dashboard Georreferenciado:** Integração com a Google Maps API para plotagem de Pins de ocorrências capturadas através de listeners em tempo real.
- **Otimização de Desempenho (Clustering):** Lógica para agrupamento inteligente de pins geográficos próximos, evitando lentidão ou travamento do navegador.

---

## ⚙️ Stack Tecnológica do Ecossistema

- **Mobile:** React Native (Expo Router)
- **Web Dashboard:** React.js integrados com Google Maps API
- **Backend & Banco de Dados:** Firebase (Authentication para sessões, Firestore para banco NoSQL escalonável e Storage para armazenamento binário)
- **Inteligência Artificial:** Modelo YOLOv8 treinado via Roboflow e processado em nuvem (Google Colab) com foco em detecção passiva veicular.

---

## 🛠️ Status Atual do Projeto & Honestidade Acadêmica

Como parte do rigor metodológico da Prova de Conceito (PoC), o ecossistema apresenta o seguinte status de integração:
- **Módulo Mobile & Web:** 100% integrados e funcionais através da infraestrutura Cloud do Firebase.
- **Módulo IoT (IA na Borda):** O modelo YOLOv8 foi treinado e validado em ambiente de script offline executando de forma isolada. O processamento de vídeo em tempo real (15-30 FPS) e o envio da telemetria de rede (Heartbeats) permanecem documentados no backlog técnico como propostas para trabalhos futuros de expansão comercial da plataforma.

---

## 👥 Corpo Técnico e Institucional
- **Equipe de Engenharia:** José Anderson, João Gabriel, Júlio César, Kauê Adriano
- **Orientação e Coordenação:** Prof. Andouglas Júnior
- **Instituição:** Instituto Federal de Educação, Ciência e Tecnologia do Rio Grande do Norte (IFRN) - Campus Currais Novos
