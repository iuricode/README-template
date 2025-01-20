<p align="center">
  <img src="/icon.png" width="140px" alt="logo" />
</p>

<h1 align="center">Nome do Projeto</h1>
<p align="center">Uma breve descrição do projeto, explicando sua funcionalidade principal de forma clara e objetiva.</p>

<h3 align="center">
  <!-- <a href="https://github.com/usuário/nome-do-projeto/actions/workflows/release.yml" target="_blank">
    <img alt="Build" src="https://github.com/usuário/nome-do-projeto/actions/workflows/release.yml/badge.svg" />
  </a> -->

  <!-- Versão -->
  <a href="https://github.com/usuário/nome-do-projeto/releases">
    <img alt="releases url" src="https://img.shields.io/github/v/release/usuário/nome-do-projeto?style=for-the-badge&labelColor=1C1E26&color=FF79C6">
  </a>  
  
 <!-- Licença -->
  <a href="./LICENSE" target="_blank">
    <img alt="License: MIT" src="https://img.shields.io/badge/license%20-MIT-1C1E26?style=for-the-badge&labelColor=1C1E26&color=FF79C6">
  </a>

 <!-- Twitter -->
  <a href="https://twitter.com/usuário" target="_blank">
    <img alt="Twitter: usuário" src="https://img.shields.io/twitter/follow/usuário.svg?style=for-the-badge&labelColor=1C1E26&color=FF79C6&logo=twitter" />
  </a>
</h3>

<br />

# Funcionalidades

- 👨‍🚀 Atalhos rápidos
- ⚙️ Altamente configurável
- 💅 Temas e temas personalizados
- 🚀 Multi-plataforma (Windows, Mac, Linux)
- 🌎 Idiomas e idiomas personalizados (i18n)

<img src=".github/preview.png" alt="Exemplo de visualização rodando o aplicativo mostrando Diego Fernandes feliz na tela do aplicativo com o Visual Studio Code aberto ao fundo">

# Instalação

- [Baixar](https://github.com/usuário/nome-do-projeto/releases)

⚠️ **Para MacOS**, mova o aplicativo extraído para a pasta **Aplicativos**, abra seu terminal e execute o seguinte comando para assinar o aplicativo
```bash
codesign --force --deep --sign - /Applications/Nome\ Do\ Projeto.app
```
Aguarde até o comando terminar, depois abra o aplicativo e permita as permissões da câmera que serão solicitadas. 🚀

# Uso e configurações

Após rodar pela primeira vez, você pode acessar as configurações do aplicativo através do **menu de bandeja** e clicar em `Configurações` para alterar atalhos padrão, tamanho da câmera, zoom, formas, temas, idiomas etc.

## Atalhos padrão

> ⚠️ **Para usuários de Linux/Windows:** se você já está usando o Nome do Projeto, provavelmente precisará atualizar os atalhos manualmente. Para isso, abra as configurações da câmera em `menu de bandeja` > `Configurações` e atualize com os novos atalhos padrão ou outros que você preferir, e o sistema operacional permitir, ou simplesmente selecione `Resetar Configurações`.

<table>
  <thead>
    <tr>
      <th>MacOS</th>
      <th>Linux / Windows</th>
      <th>Função</th>
      <th>Janela precisa estar focada</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><kbd>+</kbd> / <kbd>-</kbd></td>
      <td><kbd>+</kbd> / <kbd>-</kbd></td>
      <td>Zoom in/out</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td><kbd>/</kbd></td>
      <td><kbd>/</kbd></td>
      <td>Inverter horizontal</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td><kbd>o</kbd></td>
      <td><kbd>o</kbd></td>
      <td>Alternar formas <a href="#usando-formas-personalizadas">personalizadas</a></td>
      <td>Sim</td>
    </tr>
    <tr>
      <td><kbd>r</kbd></td>
      <td><kbd>r</kbd></td>
      <td>Resetar zoom</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td><kbd>Backspace</kbd></td>
      <td><kbd>Backspace</kbd></td>
      <td>Alternar câmera</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td><kbd>Espaço</kbd></td>
      <td><kbd>Espaço</kbd></td>
      <td>Alternar tamanho da janela (pequeno/grande)</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td><kbd>Command</kbd> + <kbd>,</kbd></td>
      <td><kbd>Ctrl</kbd> + <kbd>,</kbd></td>
      <td>Abrir o arquivo de configurações</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td><kbd>Setas para cima</kbd> / <kbd>Baixo</kbd> / <kbd>Esquerda</kbd> / <kbd>Direita</kbd></td>
      <td><kbd>Setas para cima</kbd> / <kbd>Baixo</kbd> / <kbd>Esquerda</kbd> / <kbd>Direita</kbd></td>
      <td>Ajustar deslocamento do vídeo</td>
      <td>Sim</td>
    </tr>
    <tr>
      <td><kbd>Command</kbd> + <kbd>Shift</kbd> + <kbd>Alt</kbd> + <kbd>Cima</kbd></td>
      <td><kbd>Shift</kbd> + <kbd>Alt</kbd> + <kbd>Cima</kbd></td>
      <td>Mover câmera para a borda superior da tela</td>
      <td>Não</td>
    </tr>
    <tr>
      <td><kbd>Command</kbd> + <kbd>Shift</kbd> + <kbd>Alt</kbd> + <kbd>Baixo</kbd></td>
      <td><kbd>Shift</kbd> + <kbd>Alt</kbd> + <kbd>Baixo</kbd></td>
      <td>Mover câmera para a borda inferior da tela</td>
      <td>Não</td>
    </tr>
    <tr>
      <td><kbd>Command</kbd> + <kbd>Shift</kbd> + <kbd>Alt</kbd> + <kbd>Direita</kbd></td>
      <td><kbd>Shift</kbd> + <kbd>Alt</kbd> + <kbd>Direita</kbd></td>
      <td>Mover câmera para a borda direita da tela</td>
      <td>Não</td>
    </tr>
    <tr>
      <td><kbd>Command</kbd> + <kbd>Shift</kbd> + <kbd>Alt</kbd> + <kbd>1</kbd></td>
      <td><kbd>Shift</kbd> + <kbd>Alt</kbd> + <kbd>1</kbd></td>
      <td>Alternar tamanho da câmera (pequeno/grande)</td>
      <td>Não</td>
    </tr>
    <tr>
      <td><kbd>Command</kbd> + <kbd>Shift</kbd> + <kbd>Alt</kbd> + <kbd>3</kbd></td>
      <td><kbd>Shift</kbd> + <kbd>Alt</kbd> + <kbd>2</kbd></td>
      <td>Alternar visibilidade da câmera (mostrar/ocultar)</td>
      <td>Não</td>
    </tr>
  </tbody>
</table>

## Ajustando a borda

Abra as configurações da câmera no `menu de bandeja` > `Configurações`, então procure pela propriedade `"themeOverrides"` e altere a propriedade `"borderWith"` para `"0"` caso queira **remover a borda**. Ou você pode deixá-la mais grossa alterando o valor para `"10px"`, por exemplo.

## Usando formas personalizadas

Você pode usar formas personalizadas utilizando a propriedade CSS [`clip-path`](https://developer.mozilla.org/en-US/docs/Web/CSS/clip-path). Você pode usar uma ferramenta como [Clippy](https://bennettfeely.com/clippy/) para experimentar diferentes formas que você pode criar com o `clip-path`.

### Como adicionar/remover formas

Abra as configurações da câmera no `menu de bandeja` > `Configurações` e na propriedade `"shapes"`, coloque o valor do `clip-path` em CSS conforme desejar.

<details>
  <summary>Veja um exemplo de imagem</summary>
  <img src="https://i.imgur.com/EfTwfr6.png">
</details>

## Alterando o tamanho

Abra as configurações da câmera no `menu de bandeja` > `Configurações` e altere as propriedades de largura e altura de `"screen.initial"` e/ou `"screen.large"` conforme desejar.

<details>
  <summary>Veja um exemplo de imagem</summary>
  <img src="https://i.imgur.com/D53cdtr.png">
</details>

# Contribuindo

Clone o repositório, abra a pasta do projeto e instale as dependências com:

```sh
yarn
```

Execute o projeto com:

```sh
yarn dev
```

# Autor

👤 **Nome do Autor**

- Twitter: [@usuario](https://twitter.com/usuario)
- Github: [@usuario](https://github.com/usuario)
- LinkedIn: [@usuario](https://linkedin.com/in/usuario)

## Mostre seu apoio

Dê uma estrela se este projeto te ajudou!
