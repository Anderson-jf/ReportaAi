# ReportaAi

Sistema Full Stack desenvolvido para auxiliar a população no registro de ocorrências urbanas e apoiar órgãos públicos no gerenciamento dessas informações através de uma plataforma web e um aplicativo móvel.

O projeto integra um aplicativo desenvolvido em React Native, um painel administrativo Web e serviços do Firebase para armazenamento, autenticação e sincronização de dados.

---

## Demonstração

📱 Aplicativo Mobile

🌐 Painel Administrativo

*(adicione os links quando disponíveis)*

---

# Funcionalidades

## Aplicativo Mobile

- Cadastro de usuários
- Registro de ocorrências
- Captura de imagens
- Captura de localização
- Funcionamento Offline-First
- Sincronização automática após reconexão
- Histórico de ocorrências

---

## Painel Administrativo

- Visualização de ocorrências
- Mapa interativo
- Gerenciamento das ocorrências
- Atualização de status
- Dashboard administrativo

---

## Inteligência Artificial

O projeto inclui estudos para utilização do modelo YOLOv8 na identificação automática de ocorrências urbanas a partir de imagens.

Atualmente o treinamento do modelo foi realizado separadamente como Prova de Conceito (PoC), sem integração direta ao fluxo principal da aplicação.

---

# Minha contribuição

Atuei principalmente no desenvolvimento do aplicativo móvel.

Entre as funcionalidades implementadas estão:

- Desenvolvimento das telas em React Native
- Navegação utilizando Expo Router
- Arquitetura Offline-First
- Persistência local
- Sincronização automática
- Captura de metadados EXIF
- Integração com Firebase
- Implementação do fluxo de autenticação

Também participei do desenvolvimento do painel administrativo, contribuindo para funcionalidades relacionadas ao gerenciamento das ocorrências.

---

# Stack

## Mobile

- React Native
- Expo
- Expo Router

## Web

- React
- Google Maps API

## Backend

- Firebase Authentication
- Firebase Firestore
- Firebase Storage

## Inteligência Artificial

- YOLOv8
- Roboflow
- Google Colab

---

# Arquitetura

```
React Native
        │
Firebase Authentication
        │
Firebase Firestore
        │
Firebase Storage
        │
Painel Web
```

---

# Conceitos aplicados

- Mobile Development
- Offline-First
- Firebase
- Firestore
- Geolocalização
- EXIF Metadata
- API Integration
- React Native
- Expo Router
- Google Maps API
- NoSQL
- Scrum

---

# Como executar

## Mobile

```bash
git clone ...

npm install

npx expo start
```

---

# Estrutura

```
app/

components/

services/

hooks/

assets/

firebase/
```

---

# Aprendizados

Durante o desenvolvimento foram aplicados conceitos relacionados a:

- Desenvolvimento Mobile
- Arquitetura Offline-First
- Persistência local
- Sincronização de dados
- Firebase
- Geolocalização
- Captura de imagens
- Integração com APIs
- Trabalho colaborativo utilizando Scrum

---

# Equipe

- José Anderson
- João Gabriel
- Júlio César
- Kauê Adriano

**Orientação**

Prof. Andouglas Júnior

Instituto Federal do Rio Grande do Norte (IFRN)
