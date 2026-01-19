# 📘 Comandos Git

## 📌 Comandos básicos
- `git init` → Inicializa um novo repositório Git.
- `git clone <url>` → Clona um repositório remoto para sua máquina.
- `git status` → Mostra o estado atual do repositório (arquivos modificados, staged, etc).
- `git add <Nome do Arquivo> ou git add <.> ` → Adiciona arquivos ao **staging area**.
- `git commit -m "mensagem"` → Cria um commit com uma mensagem descritiva.
- `git log <--oneline>` → Exibe o histórico de commits <!--oneline> exibe de forma resumida .
- `git diff` → Mostra diferenças entre versões de arquivos.

---

## 🌐 Trabalhando com repositórios remotos
- `git remote add origin <url>` → Conecta o repositório local a um remoto.
- `git push origin <branch>` → Envia commits para o repositório remoto.
- `git pull origin <branch>` → Atualiza o repositório local com mudanças do remoto.
- `git fetch` → Baixa alterações do remoto sem mesclar automaticamente.

---

## 🌿 Branches
- `git branch` → Lista branches existentes.
- `git branch <nome>` → Cria uma nova branch.
- `git checkout <branch>` → Troca para outra branch.
- `git checkout -b <branch>` → Cria e já muda para a nova branch.
- `git merge <branch>` → Mescla uma branch na atual.
- `git rebase <branch>` → Reaplica commits sobre outra branch.

---

## 🔄 Controle de versões
- `git reset <arquivo>` → Remove arquivo do staging area.
- `git reset --hard <commit>` → Volta o repositório para um commit específico (descarta alterações).
- `git revert <commit>` → Cria um novo commit que desfaz mudanças de um commit anterior.
- `git stash` → Guarda temporariamente alterações não commitadas.
- `git stash pop` → Recupera alterações guardadas.

---

## 🛠️ Outros úteis
# 📘 Comandos Git

## 📌 Comandos básicos
- `git init` → Inicializa um novo repositório Git.
- `git clone <url>` → Clona um repositório remoto para sua máquina.
- `git status` → Mostra o estado atual do repositório (arquivos modificados, staged, etc).
- `git add <arquivo>` → Adiciona arquivos ao **staging area**.
- `git commit -m "mensagem"` → Cria um commit com uma mensagem descritiva.
- `git log` → Exibe o histórico de commits.
- `git diff` → Mostra diferenças entre versões de arquivos.

---

## 🌐 Trabalhando com repositórios remotos
- `git remote add origin <url>` → Conecta o repositório local a um remoto.
- `git push origin <branch>` → Envia commits para o repositório remoto.
- `git pull origin <branch>` → Atualiza o repositório local com mudanças do remoto.
- `git fetch` → Baixa alterações do remoto sem mesclar automaticamente.

---

## 🌿 Branches
- `git branch` → Lista branches existentes.
- `git branch <nome>` → Cria uma nova branch.
- `git checkout <branch>` → Troca para outra branch.
- `git checkout -b <branch>` → Cria e já muda para a nova branch.
- `git merge <branch>` → Mescla uma branch na atual.
- `git rebase <branch>` → Reaplica commits sobre outra branch.

---

## 🔄 Controle de versões
- `git reset <arquivo>` → Remove arquivo do staging area.
- `git reset --hard <commit>` → Volta o repositório para um commit específico (descarta alterações).
- `git revert <commit>` → Cria um novo commit que desfaz mudanças de um commit anterior.
- `git stash` → Guarda temporariamente alterações não commitadas.
- `git stash pop` → Recupera alterações guardadas.

---

## 🛠️ Outros úteis
- `git tag <nome>` → Cria uma tag (marcação de versão).
- `git show <commit>` → Mostra detalhes de um commit.
- `git blame <arquivo>` → Mostra quem alterou cada linha de um arquivo.
- `git config --global user.name "Seu Nome"` → Configura o nome do usuário.
- `git config --global user.email "seu@em`