# Markdown
- [Cheat Sheet MarkDown](https://www.markdownguide.org/cheat-sheet/)
- [Editor MarkDown online](https://dillinger.io/)
- The Markdown Guide by **Matt Cone** (libro sobre Markdown)
- Markdown se puede utilizar para crear sitios web

# Terminal
- 💾 Terminal: Programa que proporciona una interfaz de línea de comandos
- 🐚 Shell: Programa que interpreta los comandos.
- ✍ Prompt: Mensajes que se ve en la línea de comandos, indicando que está a la espera de órdenes.
- Diferencias entre SO:
  - *Windows:* 💾 PowerShell, 🐚 PowerShell, ✍ >
  - *Linux:* 💾 Gnome Terminal, 🐚 Bash, ✍ >
  - *macOS:* 💾 Terminal, 🐚 Z Shell, ✍ %
- Los *alias* se utilizan para "renombrar" comandos de la terminal
  - Ejemplo: alias findd="ls ~/ | grep $1"
    - alias abreviatura="comando_que_ejecuta_la_abreviatura"
    - Con $ indicamos que necesita una variable
- echo *$SHELL* nos indica que tipo de terminal tenemos según:
  - Carpeta /bin/zsh --> Z Shell
  - Carpeta /bin/bash --> Bash
- Para guardar los *alias* se hace en los archivos, están en el directorio de inicio del usuario:
  - Z Shell --> .zshrc
  - Bash --> .bashrc