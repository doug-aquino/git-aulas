# Guia Completo de Criação de Chave SSH para GitHub

Este documento reúne todos os passos necessários para gerar, configurar e testar uma chave SSH para usar com o GitHub.

---

## 1. Verificar se já existe uma chave

No terminal (Linux/Mac) ou Git Bash (Windows):

bash
ls -al ~/.ssh
## 2. para gerar uma nova chave
* Linux/Mac/Git Bash (Windows):
ssh-keygen -t ed25519 -C "seuemail@exemplo.com"
ou
ssh-keygen -t rsa -b 4096 -C "seuemail@exemplo.com"

• 	Pressione Enter para aceitar o caminho padrão 
• 	Digite uma senha (opcional) ou apenas pressione Enter.

## 3. Adicionar a chave ao agente SSH
* Inicie o agente:
eval "$(ssh-agent -s)"

* Adicione a chave:
ssh-add ~/.ssh/id_ed25519

## 4. Copiar a chave pública
* Mostre o conteúdo da chave pública:
cat ~/.ssh/id_ed25519.pub

## 5. Adicionar no GitHub
* 1. 	Vá em Settings → SSH and GPG keys → New SSH key.
* 2. 	Cole o conteúdo da chave pública.
* 3. 	Dê um nome (ex: "Meu PC").
* 4. 	Salve

## 6. Testar a conexão
 ssh -T git@github.com
 Se aparecer: nome do usuario esta pronto