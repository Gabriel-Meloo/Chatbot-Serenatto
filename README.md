# ☕ Chatbot Serenatto – Assistente Virtual para Loja Online de Cafés Especiais

Este projeto tem como objetivo criar um **chatbot inteligente** para a **Serenatto**, uma loja online especializada em **grãos de cafés especiais brasileiros**. O chatbot atua como um **atendente virtual**, ajudando os clientes a esclarecerem dúvidas sobre os produtos e processos de preparo.

---

## 🎯 Objetivo

Oferecer uma experiência personalizada para os clientes da Serenatto, auxiliando na escolha do café ideal e proporcionando informações úteis sobre os diferentes métodos de preparo.

---

## 🧠 Funcionalidades do Chatbot

- Recomendações personalizadas de grãos com base em preferências do cliente
- Informações sobre:
  - Origem dos cafés
  - Processos de torrefação
  - Métodos de preparo (coado, prensa francesa, espresso, etc.)
- Esclarecimento de dúvidas sobre pedidos e envio
- Atendimento 24h com linguagem natural e amigável

---

## ⚙️ Tecnologias Utilizadas

| Ferramenta         | Finalidade                                         |
|--------------------|----------------------------------------------------|
| **Groq (LLM)**     | Modelo de linguagem para respostas inteligentes    |
| **LlamaIndex**     | Integração entre dados e o LLM                     |
| **Chroma**         | Banco de dados vetorial                           |
| **Gradio**         | Protótipo local e testes com usuários              |
| **HTML/JS Widget** | Embutido do chatbot no site da loja               |
| **Python**         | Backend de processamento e ingestão de dados       |

---

## 🧾 Fonte dos Dados

Os dados utilizados para alimentar o modelo incluíram:

- Descrições dos grãos e suas características (fornecidos via CSV)
- Textos institucionais da marca
- Artigos e postagens do blog sobre preparo e curiosidades do café

Esses documentos foram convertidos em embeddings e armazenados em banco vetorial.

---

## 🌐 Integração no Site

O chatbot foi embutido diretamente na página principal da loja (HTML/JS), garantindo:

- Carregamento leve e rápido
- Interface amigável e responsiva
- Ícone de chat acessível a qualquer momento
