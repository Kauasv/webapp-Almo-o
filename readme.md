# 🍽️ Sistema de Pedidos de Almoço

## 📋 Objetivo
Este projeto foi desenvolvido para atender à demanda de reunir os pedidos de almoço de forma mais prática antes de serem enviados para o restaurante.

## 🔄 Fluxo do Sistema

1. **Solicitante** → Disponibiliza o cardápio para os demais funcionários
2. **Funcionários** → Realizam o preenchimento do cardápio, selecionando o que desejam
3. **Solicitante** → Copia ou gera um arquivo Excel para enviar ao restaurante

---

## 🏗️ Estrutura do Projeto

| Item | Detalhes |
|------|----------|
| **Banco de Dados** | Firebase Firestore |
| **Front-end** | HTML, CSS, JavaScript |
| **Hosting** | Firebase Hosting |
| **URL do Hosting** | [https://almoco-empresa-7a582.web.app](https://almoco-empresa-7a582.web.app) |

---

## ⚙️ Configuração do Firebase

```javascript
// Importar os módulos necessários
import { initializeApp } from "firebase/app";
import { getAnalytics } from "firebase/analytics";

// Configuração do Firebase
const firebaseConfig = {
  apiKey: "AIzaSyBrfXYmD0DwHD1Lk2Zf9c_Dvc3KrCiAD9A",
  authDomain: "almoco-empresa-7a582.firebaseapp.com",
  projectId: "almoco-empresa-7a582",
  storageBucket: "almoco-empresa-7a582.firebasestorage.app",
  messagingSenderId: "646365633884",
  appId: "1:646365633884:web:acd39ed091832d9ebdb599",
  measurementId: "G-BKJH0N2E6N"
};

// Inicializar Firebase
const app = initializeApp(firebaseConfig);
const analytics = getAnalytics(app);
```

---

## 📦 Instalação

```bash
npm install firebase
```

---

## ℹ️ Informações do Projeto

| Campo | Informação |
|-------|------------|
| **Desenvolvedor** | Kauã Silva Valadares |
| **Cliente** | Hidraup Soluções |
| **Data** | Junho de 2026 |