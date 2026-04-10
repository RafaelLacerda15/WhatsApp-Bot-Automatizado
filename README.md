# 🤖 WhatsApp Bot Automatizado – Flask + Evolution API

**Bot inteligente para WhatsApp** que automatiza envios em massa, gerencia conversas interativas e rastreia respostas em tempo real.

Projeto desenvolvido como **portfólio de automação backend**, demonstrando habilidades em APIs, webhooks, Docker e integração com serviços de mensageria.

---

### ✨ Recursos Principais

- 📱 **Envio em massa** de mensagens com suporte a texto, áudio e mídia  
- 🎤 **Listas interativas** e fluxos conversacionais inteligentes  
- 🔄 **Rastreamento automático** de conversas e mapeamento de contatos (remote_jid ↔ número)  
- 📊 **Dashboard em tempo real** com estatísticas completas  
- 🗂️ **Logs detalhados** e persistência em banco SQLite  
- 🐳 **Totalmente containerizado** com Docker + Docker Compose  
- 🔌 **Webhooks** para recebimento instantâneo de mensagens  

---

### 🛠️ Tecnologias Utilizadas

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)

**Principais ferramentas:**
- Evolution API (integração oficial com WhatsApp)
- Webhooks + Flask routes
- SQLAlchemy / SQLite
- HTML + CSS + JavaScript (dashboard interativo)

---

### 🚀 Quick Start

#### Com Docker (recomendado)

```bash
# 1. Clone o repositório
git clone https://github.com/RafaelLacerda15/whatsapp-bot-flask-evolution.git
cd whatsapp-bot-flask-evolution

# 2. Configure as variáveis de ambiente
cp .env.example .env

# 3. Inicie os containers
docker-compose up -d

# 4. Acesse
# Dashboard → http://localhost:5000
