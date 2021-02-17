---
marp: true
title: Como git pode salvar seu bacon!
description: Palestra sobre git e como pode salvar seu dia!
theme: Uncover
paginate: true
_paginate: false
header: ''
footer: ''
---

![bg right 60%](https://icongr.am/octicons/mark-github.svg)

# <!--fit--> Como git pode salvar seu bacon!

---

<!-- backgroundColor: #123 -->
<!-- color: white -->
# AGENDA

- ### O que é GIT
- ### Conceitos
- ### Comandos iniciais
- ### Melhores práticas
- ### Rebase vs Merge vs Squash
- ### Stash and Amend é o seu melhor amigo

![bg right 60%](assets/agenda.png)

---
<!-- header: o que e git -->

# O QUE É GIT

![bg left 200%](assets/computer-system.jpeg)
![bg left 200%](assets/software-dev.jpeg)

- Sistema de computador criado pelo criador do linux em 2005
- Usado por desenvolvedores para poder salvar, rastrear, gerenciar codigo e facilitar o trabalho em equipe.
---
<!-- header: git conceitos -->

# CONCEITOS 

- ## Sistema distribuido de controle de versao
- ## Rastreamento / historico
- ## Snapshot (Commit)
- ## Reverta a qualquer momento

![bg right 88%](assets/dvc.png)

---
<!-- header: comandos iniciais -->
# COMANDOS INICIAIS

- ## git init
- ## git add `nome-do-arquivo` ou `.`
- ## git status
- ## git commit `-m "mensagem de commit"`

![bg left 110%](assets/conceitos.png)

---
<!-- header: comandos inicias -->

- ## git push
- ## git pull
- ## git clone `nome do repositorio`

![bg right 110%](assets/conceitos.png)

---
<!-- header: alem do basico -->
# MELHORES PRÁTICAS

- ### git branch `nome-da-ramificacao` / `-d nome-da-ramificacao`    
- ### git checkout `nome-da-ramificacao` / `-b nova-ramificacao`
- ### git diff
- ### git merge "feature"
- ### git rebase "master"

![bg right 75%](assets/merge-rebase.png)

---
![bg 90%](assets/rebase-vs-merge.png)

---
<!-- header: alem do basico -->

# <!--fit--> `git stash` and `amend` is your friend

- ## git stash / save "mensagem"
- ## git stash list (like git status)
- ## git stash clear / drop "stash-id"
- ## git stash pop / apply "stash-id"
- ## git commit --amend --no-edit

---
<!-- header: demo -->

![bg](assets/demo.jpg)

---
<!-- header: thanks! -->
# Muito Obrigado!!!

Guilherme Epifanio

