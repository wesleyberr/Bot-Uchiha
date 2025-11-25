# 🔴⚫ Uchiha-Bot 👾

<div align="center">

![Uchiha Bot](https://media.giphy.com/media/l0HlGy9x8FZo0XO1i/giphy.gif)

### 🎨 **Meu Bot simples e leve para o WhatsApp!** 🤖

[![JavaScript](https://img.shields.io/badge/JavaScript-ES6%2B-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://www.whatsapp.com)
[![Node.js](https://img.shields.io/badge/Node.js-v14%2B-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![Baileys](https://img.shields.io/badge/Baileys-API-FF6B6B?style=for-the-badge&logo=npm)](https://github.com/adiwajshing/Baileys)
[![MIT License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

---

### 🔴 **"O clã Uchiha é conhecido por suas poderosas habilidades e forte ligação."** ⚫

</div>

---

## 👋 Bem-vindo ao Uchiha-Bot

Um **Bot poderoso e leve para WhatsApp** com a temática inspirada no lendário clã Uchiha! 🔥

Este projeto incorpora a rica história e o design espetacular do clã Uchiha em um bot interativo moderno, oferecendo funcionalidades dinâmicas com uma interface temática profissional.

---

## 🎨 Temática Uchiha

| Elemento | Descrição |
|----------|-----------|
| **🔴 Cor Primária** | Vermelho Profundo - Poder e Determinação |
| **⚫ Cor Secundária** | Preto - Mistério e Força |
| **⚪ Acentos** | Branco - Equilíbrio e Pureza |
| **🌀 Símbolo** | Sharingan - Visão e Percepção |
| **💫 Tema** | Poder, Lealdade e Excelência |

---

## ⚙️ Requisitos / Prerequisites

Antes de começar, certifique-se de que você possui:

```
✅ Node.js v14.0.0 ou superior
✅ npm v6.0.0 ou superior (ou yarn v1.22.0+)
✅ Conta do WhatsApp ativa
✅ Git instalado no seu sistema
✅ Conexão com a internet
```

---

## 📥 Instalação / Installation

### 📍 Passo 1: Clone o repositório

```bash
git clone https://github.com/verzinonlyyuhhh/Bot-Uchiha.git
cd Bot-Uchiha
```

### 📍 Passo 2: Instale as dependências

```bash
npm install
# ou
yarn install
```

### 📍 Passo 3: Configure o arquivo de ambiente

```bash
cp .env.example .env
# Edite o arquivo .env com suas configurações
```

### 📍 Passo 4: Inicie o Bot

```bash
npm start
# ou
node index.js
```

Escaneie o **QR Code** com seu WhatsApp para autenticar! 📱

---

## 🚀 Como Usar / Usage

### 🎮 Iniciando o Bot

```bash
npm start
```

O bot iniciará e exibirá um QR Code. Escaneie com seu WhatsApp!

### 💬 Enviando Comandos

Envie mensagens para o bot começando com `!`:

```
!menu          → Mostra o menu principal
!help          → Exibe a lista de comandos disponíveis
!status        → Verifica o status do bot
!admin         → Acessa menu de administrador
!about         → Informações sobre o Uchiha-Bot
```

### 🎯 Exemplos Práticos

```
Você: !menu
Bot: 🔴⚫ BEM-VINDO AO UCHIHA-BOT! ⚫🔴
     Escolha uma opção:
     1️⃣ Comandos
     2️⃣ Informações
     3️⃣ Admin

Você: !help
Bot: 📋 LISTA DE COMANDOS:
     • !menu - Menu principal
     • !help - Ajuda
     • !status - Status
     ...
```

---

## 🛠️ Tecnologias / Technologies

<div align="center">

| Tecnologia | Descrição | Versão |
|------------|-----------|--------|
| ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) | Linguagem Principal | ES6+ |
| ![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white) | Runtime | v14+ |
| ![Baileys](https://img.shields.io/badge/Baileys-FF6B6B?logo=npm) | WhatsApp API | Latest |
| ![Express](https://img.shields.io/badge/Express.js-000000?logo=express) | Framework Web | v4+ |
| ![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white) | Database | v3+ |

</div>

**Dependências Principais:**
- `@adiwajshing/baileys` - Automação WhatsApp Web
- `express` - Framework web
- `axios` - Cliente HTTP
- `dotenv` - Variáveis de ambiente
- `qrcode-terminal` - Exibir QR Code no terminal

---

## 📁 Estrutura do Projeto / Project Structure

```
Uchiha-Bot/
│
├── 📄 index.js                 # 🔴 Arquivo principal de inicialização
├── 📄 menu.js                  # 🔴 Menu principal do bot
├── 📄 submenu.js               # 🔴 Submenus adicionais
├── 📄 conf.js                  # ⚙️ Arquivo de configuração
│
├── 📦 package.json             # 📋 Dependências do projeto
├── 📄 .env.example             # 🔐 Template de variáveis de ambiente
├── 📄 .gitignore               # 🚫 Arquivos ignorados
│
├── 📁 src/                     # 💾 Código-fonte modularizado
│   ├── 📁 commands/            # 📝 Comandos do bot
│   ├── 📁 config/              # ⚙️ Configurações
│   └── 📁 utils/               # 🔧 Funções utilitárias
│
├── 📁 modules/                 # 🧩 Módulos de funcionalidades
│   └── 📄 adm.js               # 👑 Módulo de administração
│
├── 📁 auth_info_baileys/       # 🔐 Dados de autenticação (auto-gerado)
│
├── 📁 Implementação/           # 📚 Documentação de implementação
│
├── 📄 README.md                # 📖 Este arquivo
├── 📄 INSTALLATION.md          # 📋 Guia detalhado de instalação
├── 📄 LICENSE                  # ⚖️ Licença MIT
│
└── 🎨 **TEMA UCHIHA APLICADO**
    └── 🔴⚫ Cores e design inspirados no clã Uchiha
```

### 📌 Descrição dos Arquivos Principais:

| Arquivo | Descrição |
|---------|-----------|
| `index.js` | Inicializa o bot e conecta ao WhatsApp via Baileys |
| `menu.js` | Define menus interativos com temática Uchiha |
| `submenu.js` | Submenus adicionais e secundários |
| `conf.js` | Configurações globais e constantes do bot |
| `modules/adm.js` | Funções exclusivas de administrador |

---

## 🗺️ Roadmap / Futuro Desenvolvimento

### ✅ Feito
- [x] ✔️ Autenticação com Baileys
- [x] ✔️ Sistema de menus interativos
- [x] ✔️ Módulo de administração
- [x] ✔️ Temática Uchiha aplicada

### 🔄 Em Desenvolvimento
- [ ] 🔨 Sistema de banco de dados completo
- [ ] 🔨 Mais comandos interativos
- [ ] 🔨 Sistema de permissões por usuário
- [ ] 🔨 Respostas automáticas inteligentes

### 🎯 Próximos
- [ ] 🚀 Integração com APIs externas
- [ ] 🚀 Dashboard web de controle
- [ ] 🚀 Sistema de plugins
- [ ] 🚀 Suporte a múltiplos números
- [ ] 🚀 Registros detalhados (logs)
- [ ] 🚀 Backup automático de dados
- [ ] 🚀 Sistema de reputação de usuários

---

## 🤝 Contribuindo / Contributing

Sinta-se à vontade para contribuir com o projeto! Nós acolhemos sugestões que respeitem o legado Uchiha!

### Como Contribuir:

```bash
# 1. Faça um Fork do projeto
# 2. Crie uma branch para sua feature
git checkout -b feature/MinhaFeature

# 3. Faça commit das mudanças
git commit -m 'Adiciona MinhaFeature com temática Uchiha'

# 4. Push para a branch
git push origin feature/MinhaFeature

# 5. Abra um Pull Request
```

---

## 🐛 Suporte e Contato / Support & Contact

### 📢 Reportar Bugs

Se encontrar um bug ou problema:

1. Abra uma [**Issue no GitHub**](https://github.com/verzinonlyyuhhh/Bot-Uchiha/issues)
2. Descreva o problema em detalhes
3. Inclua os passos para reproduzir

### 💬 Entre em Contato

<div align="center">

| Plataforma | Link |
|-----------|------|
| 📱 **WhatsApp** | [+244948963368](https://wa.me/244948963368?text=Olá%20Rúben%21%20Vim%20do%20GitHub%20%3A%29) |
| 👥 **Facebook** | [Rúben Silver](https://www.facebook.com/profile.php?id=61551471087846) |
| 📸 **Instagram** | [@ruben_siilver](https://www.instagram.com/ruben_siilver?igsh=MWRpZjVwaXJwZ21kNQ==) |
| ✈️ **Telegram** | [@uchiha_all](https://t.me/uchiha_all) |
| 🐙 **GitHub** | [@verzinonlyyuhhh](https://github.com/verzinonlyyuhhh) |

</div>

---

## 👨🏽‍💻 Desenvolvedor / Author

<div align="center">

![Developer](https://media.giphy.com/media/M9gbBFeQn0dIE/giphy.gif)

### **𝐑ú𝐛𝐞𝐧 𝐒𝐢𝐥𝐯𝐞𝐫 👨🏽‍💻**

Desenvolvedor apaixonado por JavaScript e automação de bots!

**GitHub:** [@verzinonlyyuhhh](https://github.com/verzinonlyyuhhh)

> *"O caminho do verdadeiro poder não é conquistado pela força, mas pela dedicação e perseverança."* - Inspirado no Clã Uchiha

</div>

---

## 📜 Licença / License

Este projeto está sob a licença **MIT** - veja o arquivo [LICENSE](LICENSE) para detalhes completos.

```
MIT License

Copyright (c) 2025 Rúben Silver

Permissão é concedida, gratuitamente, a qualquer pessoa que obtenha uma cópia
deste software e seus arquivos de documentação associados ("Software"), para 
lidar no Software sem restrição, incluindo, sem limitação, os direitos de usar, 
copiar, modificar, mesclar, publicar, distribuir, sublicenciar e/ou vender cópias
do Software.
```

---

## 🎨 Galeria de Capturas

```
╔════════════════════════════════════════╗
║   🔴⚫ UCHIHA-BOT ATIVO 🔴⚫          ║
║                                        ║
║  Status: ✅ Conectado ao WhatsApp     ║
║  Usuário: Rúben Silver 👨🏽‍💻          ║
║  Tema: 🔴 Uchiha Clan ⚫              ║
║  Versão: 1.0.0                        ║
║  Modo: 🎮 Interativo                  ║
║                                        ║
╚════════════════════════════════════════╝
```

---

## ⭐ Apoie o Projeto

Se gostou do **Uchiha-Bot**, deixe uma ⭐ estrela no repositório!

```
🌟 Sua estrela motiva o desenvolvimento! 🌟
```

---

<div align="center">

### 🔴⚫ **「 Uchiha-Bot: Poder através da Automação 」** ⚫🔴

![Sharingan](https://media.giphy.com/media/5VKbvrjB8Alo7qIMAD/giphy.gif)

**Última Atualização:** 2025-11-25 19:45:00 UTC

**Desenvolvido com 💜 por Rúben Silver**

---

*O Clã Uchiha vive em cada linha de código deste bot!* 🔥

</div>
