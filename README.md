# 💻 my-vscode-configs
  
Repositório atualizado regularmente com minhas configurações da IDE VS Code.

</br>

![pré visualizacao do layout](/assets/preview.png)

</br>

## ❗ Leia com atenção</span>
  
  - Estas configurações foram testadas apenas no sistema operacional Windows. Em breve (sem estimativa), estarei postando atualizações para Linux.
  - Ao configurar seu VS Code utilizando estas configurações a maior parte de seus comandos será via teclado e não via interface.
  - A extensão <code>Apc Customize UI++</code> está em fase experimental.
  - No macOS pode ser necessária a permissão para o APC Customize UI++ editar o VSCode.
  ```bash
    sudo chown -R $(whoami) "/Applications/Visual Studio Code.app/Contents/Resources/app/out"
  ```

## Comandos

<details>
<summary>Windows</summary>

- <kbd>Ctrl</kbd> + <kbd>Q</kbd> (Menu lateral esquerdo)
- <kbd>Ctrl</kbd> + <kbd>P</kbd> (Ir até os arquivos)
- <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>Q</kbd> (Mostrar todos os comandos)
- <kbd>Ctrl</kbd> + <kbd>`</kbd> (Abrir o terminal)

</details>

<details>
<summary>MacOS</summary>

- <kbd>Ctrl</kbd> + <kbd>Q</kbd> (Menu lateral esquerdo)
- <kbd>⌘</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd> (Ir até os arquivos)
- <kbd>Ctrl</kbd> + <kbd>`</kbd> (Abrir o terminal)
  
</details>

</br>

## 🛠️ Configuração

Siga o passo a passo:

- Instale o [VS Code](https://code.visualstudio.com)
- Instale as seguintes extensões no VS Code:
  - [Apc Customize UI++](https://marketplace.visualstudio.com/items?itemName=drcika.apc-extension)
  - [Min Theme](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.min-theme)
  - [Symbols](https://marketplace.visualstudio.com/items?itemName=miguelsolorio.symbols)
- Instale as seguintes fontes em seu computador:
  - [JetBrains Mono](https://www.jetbrains.com/pt-br/lp/mono/)
  - [Inter](https://fonts.google.com/specimen/Inter)
- Abra o seu VS Code
- Use o comando:
  - Windows: <kbd>Ctrl</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>
  - MacOS: <kbd>⌘</kbd> + <kbd>Shift</kbd> + <kbd>P</kbd>.
- Pesquise por ``Preferences: Open settings (JSON)``
- Copie e cole o conteúdo do arquivo:
  - Windows: `windows-settings.json`.
  - MacOS: `mac-settings.json`.

</br>

## Sujestões de extensões

Dê uma olhada nessas extensões e veja se são uteis para a sua produtividade:

- [Dotenv](https://marketplace.visualstudio.com/items?itemName=dotenv.dotenv-vscode)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [LiveServer](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- [Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
- [Regex Previewer](https://marketplace.visualstudio.com/items?itemName=chrmarti.regex)
- [Rest Client](https://marketplace.visualstudio.com/items?itemName=humao.rest-client)
- [SQLite](https://marketplace.visualstudio.com/items?itemName=alexcvzz.vscode-sqlite)
- [WSL](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl)
- [Codeium](https://marketplace.visualstudio.com/items?itemName=Codeium.codeium)
