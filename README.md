# 🛠️ HUB DE FERRAMENTAS CLI

> [!IMPORTANT]
> **Ambiente:** Ubuntu 25.10 (Mobile)
> **Status:** 🟢 Operacional
> **Arquitetura:** aarch64

---

### 🎥 Motor de Extração: yt-dlp
Utilitário de alto desempenho para manipulação e download de fluxos de mídia.

| Recurso | Função |
| :--- | :--- |
| **Integração** | FFmpeg nativo para fusão de áudio/vídeo |
| **Formatação** | Suporte a múltiplos codecs (MP4, MKV, MP3) |
| **Automatização** | Script de download rápido via Alias |

---

### ⚙️ Configuração do Sistema

> [!NOTE]
> Execute os comandos abaixo para garantir a compatibilidade total do ambiente.

```bash
# 1. Instalar dependências essenciais
apt update && apt install python3 ffmpeg -y

# 2. Criar o atalho de execução rápida
echo "alias baixar='python3 ~/Pedro/ferramentas/yt-dlp/yt_dlp/__main__.py'" >> ~/.bashrc
source ~/.bashrc
```

---

### 🚀 Guia de Uso

* **Qualidade Máxima:** `baixar "URL"`
* **Listar Formatos:** `baixar -F "URL"`
* **Extrair MP3:** `baixar -x --audio-format mp3 "URL"`

---
_Repositório técnico para automação de tarefas via linha de comando._
