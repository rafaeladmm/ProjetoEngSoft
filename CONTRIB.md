# Contrib.md

### ↪︎ Guia de Contribuição

> Bem-vindo ao repositório do **Projeto de Engenharia de Software**! Este documento explica como contribuir corretamente com o  nosso projeto.
> 

---

### ☑︎ Como Contribuir

- **Clonar o Repositório**
    
    Antes de começar, faça o clone do repositório para sua máquina local:
    

```bash
git clone <https://github.com/SEU_USUARIO/ProjetoEngSoft.git>
cd ProjetoEngSoft
git pull origin main
```

- **Criar uma Nova Branch**
    
    Sempre crie uma **nova branch** para cada funcionalidade ou correção que for fazer:
    

```bash
git checkout dev
git pull origin dev  
git checkout -b feature/nome-da-funcionalidade
```

---

### ☑︎ **Fazer as Modificações**

Edite os arquivos necessários e, após finalizar, adicione suas mudanças:

```bash
git add .
git commit -m "Descrição da modificação realizada"
git push origin feature/nome-da-funcionalidade
```

---

### ☑︎ **Criar um Pull Request**

Após enviar suas alterações, acesse o **GitHub** e:

1. Vá até a aba **Pull Requests**.
2. Clique em **"New Pull Request"**.
3. Escolha a branch de origem (feature/nome-da-funcionalidade) e a branch de destino (dev).
4. Adicione uma descrição e crie o PR.
5. Aguarde a revisão e aprovação.

---

### ☑︎ **Mesclar as Alterações**

Depois que o PR for aprovado, ele será mesclado na branch dev.

Quando todas as contribuições estiverem finalizadas, será feito o merge da dev para a main.

---

### ʚ Boas Práticas ɞ

- Sempre atualize seu repositório antes de iniciar qualquer modificação:

```bash

git pull origin main  
git pull origin dev   
```

- Use mensagens de commit **claras e descritivas**.
- Se houver conflitos, resolva-os localmente antes de enviar um commit.

---

**🔹 Dúvidas?** Entre em contato com os membros do projeto!

https://github.com/rafaeladmm

https://github.com/Janine2110

https://github.com/MiguelVencato
