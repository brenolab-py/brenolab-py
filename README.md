<div align="center">
  <h1>Olá, me chamam de Breno 👋</h1>

  ---

### 💡 Filosofia & Aprendizado

* 🧠 **Autodidata:** Aprendizado na prática, movido principalmente pela curiosidade e pela vontade de entender como as coisas funcionam. Venho explorando Python para resolver problemas reais, automatizar pequenas rotinas e, ocasionalmente, criar soluções para problemas que eu mesmo inventei.

* 🐍 **Python além dos scripts:** Explorando o desenvolvimento de aplicações desktop para Windows, incluindo interfaces gráficas, integração com a Win32 API e aplicações leves. Ainda estou aprendendo, então cada projeto costuma ensinar tanto sobre programação quanto sobre o motivo de certas coisas simplesmente... não funcionarem.

---

### 🚀 Projeto em Destaque

**[UsbScreamer](https://github.com/brenolab-py/UsbScreamer)** — Utilitário desktop cômico e minimalista para Windows que toca um som ao conectar ou remover unidades removíveis (pendrives). Código aberto (MIT). [Página do projeto](https://usb-screamer.vercel.app)

- **Baixo nível:** Detecção por polling com a Windows API (`ctypes`: `GetLogicalDrives` + `GetDriveTypeW`), sem reter handles, então a ejeção segura do Windows continua funcionando.
- **Interface e sistema:** Bandeja do sistema (`pystray`), áudio assíncrono (`winsound`), instância única (mutex Win32) e inicialização com o Windows via `HKCU\...\Run` (`winreg`), sem admin.
- **Build e distribuição:** Build automatizado com PyInstaller (`--onedir`) e instalador Inno Setup que instala em `%LocalAppData%`, sem UAC.

---

### 🛠️ Stack & Ferramentas

- **Linguagem:** Python 3.13
- **Engenharia Windows:** Windows API (ctypes), PyInstaller, Inno Setup 7
- **Web, deploy e vendas:** Tailwind CSS, Vercel, Git & GitHub, plataforma de checkout digital

---

### 📫 Conecte-se Comigo

- 🌐 **Projeto atual:** [usb-screamer.vercel.app](https://usb-screamer.vercel.app)
- 💻 **Código-fonte:** [github.com/brenolab-py/UsbScreamer](https://github.com/brenolab-py/UsbScreamer)
- 🎬 **TikTok:** [@___brenos](https://www.tiktok.com/@___brenos) *(bastidores, projetos, demonstrações)*
