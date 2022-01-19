# Configurando o VS Code para Python

<p align="center">
  <a href="https://wazana.dev">
    <img src="https://www.datocms-assets.com/41512/1642548236-logo.png" height="128">
    <h1 align="center">wazana.dev</h1>
  </a>
</p>

<p align="center">
  <a aria-label="Linkedin wazana.dev" href="https://www.linkedin.com/company/wazana-dev/">
    <img src="https://img.shields.io/badge/wazana--dev-333.svg?style=for-the-badge&logo=linkedin&labelColor=0A66C2">
  </a>
  
  <a aria-label="Instagram wazana.dev" href="https://www.instagram.com/wazana.dev/">
    <img src="https://img.shields.io/badge/@wazana%2Edev-333.svg?style=for-the-badge&logo=instagram&logoColor=white&labelColor=E4405F">
  </a>
  
  <a aria-label="YouTube wazana.dev" href="https://www.youtube.com/channel/UCVE9-HO_GzLtDK4IGKVSYXA">
    <img src="https://img.shields.io/badge/Wazana-333.svg?style=for-the-badge&logo=youtube&logoColor=white&labelColor=FF0000">
  </a>
  
  <a aria-label="Discord wazana.dev" href="https://discord.gg/MF6F4t8eQw">
    <img src="https://img.shields.io/badge/wazana%2Edev-333.svg?style=for-the-badge&logo=discord&logoColor=white&labelColor=5865F2">
  </a>
</p>

**Playlist:** [Programando em Python no VS Code](https://www.wazana.dev/playlist/programando-em-python-no-vs-code).

## Introdução

Neste tutorial vamos utilizar o Python 3 para criar um programa Python simples no Visual Studio Code e com isso poderemos editar, executar e depurar o código por meio dos seguintes passos:

- Escrever, executar e depurar (debug) um script Python.
- Aprender a instalar pacotes criando ambientes virtuais Python.
- Escrever um script Python simples para plotar figuras dentro do VS Code.

### Nível
- [x] - Básico

### Pré-requisitos

O que você precisa para completar o tutorial:

- VS Code
- Extensão Python do VS Code
- Python 3

### Instalação

1. Instale o [VS Code](https://code.visualstudio.com/)

2. Instale a [Extensão Python do VS Code](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

3. Instale o interpretador Python

**Windows**

Instale a partir do site [Python Org](https://www.python.org/downloads/).

Use o botão Download Python que aparece primeiro na página para baixar a versão mais recente.

**macOS**

A instalação através do [Homebrew](https://brew.sh/) é recomendada.

Para instalar o Python usando o Homebrew no macOS use o comando no Terminal:

```
brew install python3
```

### Verifique a instalação Python

Execute o comando abaixo para verificar a versão do Python instalada:

**macOS**

```
python3 --version
```

**Windows**

```
py -3 --version
```

## Ambiente virtual e pacotes

Uma prática recomendada entre os desenvolvedores Python é evitar a instalação de pacotes em um ambiente global.

Em vez disso, utilizaremos um ambiente virtual específico do projeto que contém uma cópia de um interpretador Python global. Depois de ativar esse ambiente, todos os pacotes instalados são isolados de outros ambientes.

### Criação e ativação do ambiente

Para criar um **ambiente virtual** e instalar os pacotes necessários, insira os seguintes comandos conforme apropriado para o seu sistema operacional:

**macOS**

```
python3 -m venv .venv
source .venv/bin/activate
```

**Windows**

```
py -3 -m venv .venv
.venv\scripts\activate
```

Se o comando activate gerar a mensagem "Activate.ps1 is not digitally signed. You cannot run this script on the current system.", execute em seguida:

```
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process
```

### Instalação de pacotes

**macOS**

```
python3 -m pip install matplotlib
```

**Windows**

```
python -m pip install matplotlib
```

## Autor

**Arthur Viana** 

[![Linkedin: arthur-viana](https://img.shields.io/badge/-Arthur%20Viana-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/arthur-viana/)](https://www.linkedin.com/in/arthur-viana/)
[![GitHub Arthur](https://img.shields.io/github/followers/VianaArthur?label=follow&style=social)](https://github.com/VianaArthur)

## Agradecimentos

- Conteúdo feito para [wazana.dev](https://www.wazana.dev/) - Tecnologia direto ao ponto.
