<div align="center">
  <h1>Olá, sou o Breno 👋</h1>
  <p><strong>Entusiasta Python & Autodidata</strong></p>
  <p>Construindo utilitários enxutos para Windows, automações práticas e transformando ideias de software em produtos reais.</p>

  <p>
    <a href="https://usb-screamer.vercel.app" target="_blank">
      <img src="https://img.shields.io/badge/Live_Project-UsbScreamer-10B981?style=for-the-badge&logo=windows&logoColor=white" alt="UsbScreamer" />
    </a>
    <a href="https://github.com/brenolab-py/UsbScreamer" target="_blank">
      <img src="https://img.shields.io/badge/C%C3%B3digo--fonte-MIT-181717?style=for-the-badge&logo=github&logoColor=white" alt="Código-fonte (MIT)" />
    </a>
    <img src="https://img.shields.io/badge/Python-3.13-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python 3.13" />
    <img src="https://img.shields.io/badge/OS-Windows-0078D6?style=for-the-badge&logo=windows11&logoColor=white" alt="Windows" />
    <a href="https://www.tiktok.com/@___brenos" target="_blank">
      <img src="https://img.shields.io/badge/TikTok-@___brenos-000000?style=for-the-badge&logo=tiktok&logoColor=white" alt="TikTok" />
    </a>
  </p>
</div>

---

### 💡 Filosofia & Aprendizado

- 🧠 **Autodidata:** Evolução contínua orientada à resolução de problemas práticos, automação de rotinas e exploração de como o sistema operacional funciona por baixo dos panos.
- 🐍 **Python além dos scripts:** Aplicações desktop nativas, leves e integradas à Win32 API.

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
