<div align="center">
  <h1>Olá, sou o Breno 👋</h1>
  <p>Estudante e desenvolvedor júnior de software focado em utilitários de sistema nativos para Windows, automações em Python e produtos indie.</p>

  <p>
    <a href="https://usb-screamer.vercel.app" target="_blank">
      <img src="https://img.shields.io/badge/Projeto-UsbScreamer-10B981?style=for-the-badge&logo=windows&logoColor=white" alt="UsbScreamer" />
    </a>
    <img src="https://img.shields.io/badge/Python-3.13-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python 3.13" />
    <img src="https://img.shields.io/badge/OS-Windows-0078D6?style=for-the-badge&logo=windows11&logoColor=white" alt="Windows" />
  </p>
</div>

---

### 🚀 Projeto em Destaque

**[UsbScreamer](https://usb-screamer.vercel.app)** — Utilitário desktop cômico e minimalista para Windows que reage sonoramente à conexão e desconexão de dispositivos USB.
- **Engenharia de Baixo Nível:** Polling via Windows API (`ctypes`) sem reter handles de volume (mantendo a ejeção segura nativa).
- **Interface & Sistema:** Integração direta com a bandeja do sistema (`pystray`), reprodução assíncrona local (`winsound`) e persistência via chaves no Registro do Windows (`winreg`).
- **Distribuição:** Pipeline de compilação automatizado com PyInstaller e empacotamento em instalador nativo via Inno Setup (execução no espaço de usuário sem elevação de privilégios/UAC).

---

### 🛠️ Stack & Tecnologias

- **Linguagens & Runtime:** Python 3.13
- **Desktop & Win32:** Windows API (Ctypes), PyInstaller, Inno Setup
- **Web & Deploy:** Tailwind CSS, Vercel, Git & GitHub

---

### 📫 Conecte-se Comigo

- 🌐 **Site:** [usb-screamer.vercel.app](https://usb-screamer.vercel.app)
