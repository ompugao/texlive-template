# Texlive template

## setup

1. run `git clone https://github.com/ompugao/texlive-template.git`
2. Open this folder with VS Code
3. Add [Remote Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack) VS Code Extention
4. Press `><` icon (it should be at the left bottom) and execute `Rebuild Container`
5. Wait for a while until VS Code opens this workspace.
6. Open a terminal and execute `latexmk sample.tex`
7. Done

## build

```bash
latexmk sample.tex
```
then you will find `sample.pdf`.
