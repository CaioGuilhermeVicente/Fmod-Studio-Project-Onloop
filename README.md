# FMOD Studio Project Template

Este repositório serve como **template** para criação de novos projetos do **FMOD Studio** utilizando Git. Ele já inclui os arquivos de configuração necessários para versionamento dentro do fluxo (`.gitignore` e `.gitattributes`).

## Como criar um novo projeto

### 1. Criar um repositório a partir do template

1. Acesse este repositório no GitHub.
2. Clique em **Use this template** → **Create a new repository**.
3. Escolha a organização ou conta onde ele será criado.
4. Defina o nome do novo repositório.
5. Clique em **Create repository**.

### 2. Criar um projeto FMOD Studio

1. Abra o **FMOD Studio**.
2. Selecione **New Project**.
3. Salve o projeto, escolhendo a pasta onde ficará armazenado localmente.
4. Defina o nome do projeto e finalize a criação.

### 3. Vincular o projeto local ao repositório

Abra um terminal na pasta do projeto e execute:

```bash
git init
git remote add origin [LINK DO REPOSITORIO]
git fetch origin
git checkout -b main
git pull origin main --allow-unrelated-histories
```

Então faça o commit inicial do projeto:

```bash
git add .
git commit -m "Initial project"
git push -u origin main
```
