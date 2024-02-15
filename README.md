# Git 101 - Guia Rápido 🚀

Bem-vindo ao mundo do controle de versão com Git! Este guia rápido fornecerá uma visão geral dos comandos essenciais para começar a trabalhar com Git de maneira eficiente.

## 1. Configuração Inicial

Antes de começar, configure suas informações de usuário:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
```

## 2. Inicializando um Repositório

Crie um novo repositório ou clone um existente:

```bash
git init                  # Inicializa um novo repositório local
git clone <URL_do_repo>   # Clona um repositório existente
```

## 3. Adicionando e Comitando

Adicione arquivos ao commit e faça o commit das mudanças:

```bash
git add <nome_do_arquivo>    # Adiciona um arquivo específico
git add .                    # Adiciona todos os arquivos alterados
git commit -m "Mensagem do commit"  # Faz o commit das mudanças
```

## 4. Branching

Gerencie branches para desenvolvimento paralelo:

```bash
git branch                  # Lista branches locais
git branch <nome_branch>    # Cria uma nova branch
git checkout <nome_branch>  # Muda para a branch especificada
git merge <nome_branch>     # Une as mudanças de uma branch à branch atual
```

## 5. Sincronização com Repositório Remoto

Trabalhe colaborativamente sincronizando com um repositório remoto:

```bash
git remote add origin <URL_do_repo>  # Adiciona um repositório remoto
git pull origin <branch>             # Atualiza o repositório local com as mudanças do remoto
git push origin <branch>             # Envia as mudanças locais para o repositório remoto
```

## 6. Lidando com Conflitos

Resolva conflitos durante merges:

```bash
git pull origin <branch>  # Antes de um push, certifique-se de obter as alterações mais recentes
# Resolva conflitos manualmente nos arquivos marcados
git add <arquivos_resolvidos>
git commit -m "Conflitos resolvidos"
git push origin <branch>
```

## 7. Histórico e Informações

Visualize o histórico e obtenha informações sobre o repositório:

```bash
git log                   # Exibe o histórico de commits
git status                # Mostra o status atual do repositório
git diff                  # Exibe as diferenças entre alterações não commitadas
```

Agora você está equipado com os principais comandos do Git! 🎉 Lembre-se de explorar e praticar para se familiarizar ainda mais. Happy coding! 😊