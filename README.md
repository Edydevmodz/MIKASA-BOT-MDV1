# MIKASA-BOT-MDV1

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&pause=1000&color=C41E3A&center=true&vCenter=true&width=500&lines=MIKASA+BOT+MD;WhatsApp+Multi-Device" alt="Typing SVG" />
</p>

<p align="center">
  <b>⚔️ Mikasa BOT — Multi-Device</b><br>
  Bot de WhatsApp poderoso, leve e completo · Baileys SystemZero<br>
  <i>“Se você não consegue se proteger, eu protejo você.”</i>
</p>

<p align="center">
  <a href="https://github.com/Edydevmodz/MIKASA-BOT-MD"><img src="https://img.shields.io/badge/GitHub-MIKASA--BOT--MD-red?style=for-the-badge&logo=github" /></a>
  <img src="https://img.shields.io/badge/Node.js-18%2B-green?style=for-the-badge&logo=node.js" />
  <img src="https://img.shields.io/badge/Baileys-SystemZero-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Platform-Termux%20%7C%20Linux-black?style=for-the-badge" />
</p>

---

## 📌 Sobre

**Mikasa BOT MD** é um bot de WhatsApp multi-device com menus interativos, moderação, downloads, brincadeiras, sistema de dono, proteção de grupos e muito mais.

Desenvolvido por **Edy Dev**.

🔗 Repositório oficial:  
**https://github.com/Edydevmodz/MIKASA-BOT-MDV1**

---

## 🚀 Instalação rápida

### 1) Clonar o repositório

```bash
git clone https://github.com/Edydevmodz/MIKASA-BOT-MD
cd MIKASA-BOT-MDV1
```

### 2) Dependências (Termux)

```bash
pkg update -y
pkg install nodejs git ffmpeg -y
npm install
```

> Se der erro de permissão no armazenamento interno (`EACCES` / symlink):

```bash
npm install --no-bin-links
```

Ou instale/copie o bot para a home do Termux:

```bash
cp -r /storage/emulated/0/Download/MIKASA-BOT-MD ~/MIKASA-BOT-MD
cd ~/MIKASA-BOT-MD
npm install
```

### 3) Configurar

Edite o arquivo:

```text
settings/settings.js
```

Principais campos:

| Campo | Descrição |
|--------|-----------|
| `donoPrincipal` | Número do dono (DDI+DDD, só números) |
| `subDonos` | Números dos sub-donos |
| `prefix` | Prefixo dos comandos (padrão `/`) |
| `geminiApiKey` | Key da IA (opcional) |
| `chanell` | Link do canal |
| `chavePix` | Chave PIX (opcional) |

### 4) Iniciar

```bash
node index.js
```

Escaneie o QR Code **ou** use o código de pareamento que aparecer no terminal.

---

## ⚔️ Comandos principais

| Comando | Função |
|---------|--------|
| `/menu` | Menu principal |
| `/mikasaai` · `/ia` | Inteligência artificial |
| `/ping` | Status do bot |
| `/welcome 1` / `0` | Ativa/desativa boas-vindas |
| `/antilink` · `/antivenda` · `/antiporno` | Moderação |
| `/protocolonamoro` | Proteção de casais |
| `/bypass` | Bypass de links |
| `/denunciar` | Boletim de ocorrência |
| `/menudono` | Menu do dono |

> Use `/menu` no WhatsApp para ver **todos** os menus e comandos.

---

## 🛡️ Recursos

- ✅ Multi-device (Baileys `@systemzero/baileys`)
- ✅ Menus com botões / lista
- ✅ Welcome com foto do membro
- ✅ Anti-link, anti-spam, anti-venda, anti-porno
- ✅ Sistema de advertências (adv / adv2 / adv3)
- ✅ Downloads (YouTube, TikTok, etc.)
- ✅ Brincadeiras e figurinhas
- ✅ Menu dono / sub-dono
- ✅ Proteção de namoro
- ✅ Pareamento por código
- ✅ Leve no Termux

---

## 🔑 Keys permanentes (dono)

Configuradas em `settings/settings.js`:

```text
EDY-KEYPERM-MIKASA
EDY-KEYPERM-MIKASA-SUB
```

---

## 📁 Estrutura

```text
MIKASA-BOT-MD/
├── index.js              # núcleo do bot
├── package.json
├── settings/
│   └── settings.js       # configuração
├── commands/             # todos os comandos
├── lib/                  # bibliotecas internas
├── database/             # dados (JSON)
├── media/                # imagens (menu, welcome)
└── gif/                  # gifs de brincadeiras
```

---

## ⚠️ Avisos

- Não compartilhe sua pasta de sessão (`auth` / sessão do Baileys).
- Use o bot com responsabilidade nos grupos.
- Algumas APIs de download/bypass dependem de serviços externos e podem falhar temporariamente.

---

## 👨‍💻 Créditos

| | |
|--|--|
| **Dev** | Edy Dev |
| **Bot** | Mikasa BOT MD |
| **GitHub** | [Edydevmodz/MIKASA-BOT-MDV1](https://github.com/Edydevmodz/MIKASA-BOT-MDV1) |

---

<p align="center">
  <b>⚔️ Mikasa BOT MD</b><br>
  Feito com disciplina e código por <b>Edy Dev</b>
</p>
