Introdução ao R

Repositório para aula de Git da disciplina **Introdução ao R**

Este repositório contém materiais e instruções para a aula de Git. Siga o passo a passo abaixo para configurar seu ambiente e conectar seu RStudio ao GitHub.

## Passo a passo para configuração do Git e SSH

### 1. Configure seu nome e e-mail no Git

Substitua `"nome"` e `seuemail@email.com` pelos seus dados reais. Copie e cole os comandos abaixo no terminal do RStudio:

```sh
git config --global user.name "nome"
git config --global user.email seuemail@email.com
```

---

### 2. Gere uma chave SSH para acessar o GitHub

Coloque o seu e-mail no comando abaixo e cole no terminal do RStudio para gerar a chave de acesso:

```sh
ssh-keygen -t ed25519 -C "seuemail@exemplo.com"
```

---

### 3. Visualize a sua chave pública

Use o comando abaixo para ver o conteúdo da sua chave pública:

```sh
cat ~/.ssh/id_ed25519.pub
```

---

### 4. Adicione sua chave SSH ao GitHub

1. Copie o texto retornado pelo comando acima.
2. Acesse [https://github.com/settings/ssh/new](https://github.com/settings/ssh/new) (com sua conta do GitHub logada).
3. Cole a chave no campo indicado e salve.

---

Pronto! Seu ambiente estará configurado para usar o Git e o GitHub junto com o RStudio.

---
