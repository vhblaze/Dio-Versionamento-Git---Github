# 🚀 Guia Rápido: Dio Versionamento com Git e GitHub

## 📌 O que é Git?
O **Git** é um sistema de controle de versão distribuído que permite gerenciar o histórico de alterações em arquivos e colaborar com outros desenvolvedores.

### 🔹 Comandos Básicos do Git

| Comando | Descrição |
|---------|-----------|
| `git init` | Inicializa um repositório Git |
| `git clone <URL>` | Clona um repositório remoto |
| `git status` | Mostra o status dos arquivos no repositório |
| `git add <arquivo>` | Adiciona um arquivo para ser commitado |
| `git commit -m "mensagem"` | Registra as mudanças no repositório |
| `git log` | Exibe o histórico de commits |
| `git branch` | Lista as branches disponíveis |
| `git checkout <branch>` | Troca para uma branch específica |
| `git merge <branch>` | Mescla uma branch com a atual |
| `git pull` | Atualiza o repositório local com o remoto |
| `git push` | Envia alterações do repositório local para o remoto |

---

## 📌 O que é GitHub?
O **GitHub** é uma plataforma baseada em nuvem que permite armazenar e gerenciar repositórios Git, facilitando a colaboração entre desenvolvedores.

### 🔹 Como Trabalhar com GitHub
1. **Criar um repositório no GitHub**
2. **Clonar o repositório** para o seu computador
3. **Fazer alterações e commits**
4. **Enviar as mudanças para o GitHub** com `git push`
5. **Criar branches e pull requests** para contribuir em projetos colaborativos

---

## 📌 Fluxo de Trabalho no GitHub
1️⃣ **Criar ou clonar um repositório**
```bash
 git clone https://github.com/usuario/repo.git
```
2️⃣ **Criar uma nova branch** (opcional, para novas funcionalidades)
```bash
 git checkout -b nova-feature
```
3️⃣ **Adicionar e confirmar alterações**
```bash
 git add .
 git commit -m "Adicionando nova funcionalidade"
```
4️⃣ **Enviar para o GitHub**
```bash
 git push origin nova-feature
```
5️⃣ **Abrir um Pull Request** no GitHub para mesclar a branch com a `main`

---

## 📌 Resumo Visual do Fluxo Git/GitHub
```plaintext
1️⃣ git init | git clone <URL>
2️⃣ git branch -b minha-feature
3️⃣ git add . | git commit -m "Mensagem"
4️⃣ git push origin minha-feature
5️⃣ Criar Pull Request no GitHub
6️⃣ git merge minha-feature (se aprovado)
```

---
