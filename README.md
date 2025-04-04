# README.md

### ʚ Projeto de Treinamento Git & GitHub ɞ

> Este repositório faz parte do treinamento prático de uso do Git e GitHub em equipe. O objetivo é entender melhor como clonar repositórios, trabalhar com branches e realizar merge requests.
> 

### ⇲ Objetivo do Trabalho

> O trabalho consiste em simular um fluxo de desenvolvimento colaborativo, onde cada membro do grupo realizará uma tarefa específica dentro do repositório.
> 

---

## ✦ Etapas do Trabalho

- Clonar o Repo

```bash
git clone https://github.com/SEU_USUARIO/ProjetoEngSoft.git
cd ProjetoEngSoft
git pull origin main
```

- Realizar Modificações
    - Membro 1: Criar um README.md.
    - **Membro 2:** Editar o README.md, adicionando detalhes .
    - **Membro 3:** Criar um arquivo CONTRIB.md, com informações sobre contribuição.

- Após realizar a modificação, cada um deve rodar:

```bash
git add .
git commit -m "Descrição da modificação"
git push origin main
```

---

### ➤  Trabalhar com Branches

1. O **líder** cria a branch dev:
    
    ```bash
    git checkout -b dev
    git push origin dev
    
    ```
    
2. Cada membro cria sua própria branch a partir da dev:
    
    ```bash
    git checkout dev
    git pull origin dev
    git checkout -b feature/nome-da-funcionalidade
    ```
    
3. Após modificar os arquivos, enviar as mudanças:
    
    ```bash
    git add .
    git commit -m "Descrição da funcionalidade"
    git push origin feature/nome-da-funcionalidade
    ```
    

---

### ➤  Criar Pull Requests e Mesclar

- No **GitHub**, cada membro abre um **Pull Request** da sua branch feature/nome-da-funcionalidade para a dev.
- Após revisão e aprovação, fazer o merge na dev.
- O líder pode mesclar a dev na main quando tudo estiver finalizado.
