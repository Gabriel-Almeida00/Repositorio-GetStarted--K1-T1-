Comandos Básicos
git init: Inicia um novo repositório Git em um diretório existente.
git clone <URL>: Clona um repositório Git existente para o seu computador.
git add <arquivo>: Adiciona um arquivo específico para a área de preparação (staging area).
git add . ou git add --all: Adiciona todos os arquivos alterados para a área de preparação.
git commit -m "mensagem": Realiza um commit dos arquivos na área de preparação com uma mensagem descritiva.
git status: Mostra o estado atual do repositório, incluindo arquivos modificados, adicionados ou removidos.
git log: Exibe o histórico de commits do repositório.
git pull: Puxa as alterações do repositório remoto para o branch atual.
git push: Envia os commits locais para o repositório remoto.
Comandos de Branching
git branch: Lista todos os branches no repositório e destaca o branch atual.
git branch <nome_do_branch>: Cria um novo branch com o nome especificado.
git checkout <nome_do_branch>: Muda para o branch especificado.
git merge <nome_do_branch>: Combina o branch atual com o branch especificado.
Comandos de Remoção e Renomeação
git rm <arquivo>: Remove um arquivo do repositório e prepara a remoção para o próximo commit.
git mv <antigo_nome> <novo_nome>: Renomeia um arquivo no repositório e prepara a mudança para o próximo commit.
Comandos para Trabalhar com o Repositório Remoto
git remote -v: Exibe os repositórios remotos configurados e suas URLs.
git remote add <nome> <URL>: Adiciona um repositório remoto com o nome especificado e a URL fornecida.
git remote remove <nome>: Remove um repositório remoto com o nome especificado.
git fetch: Obtém as alterações do repositório remoto, mas não as mescla com o branch local.
git branch -r: Lista os branches remotos.
git push <nome_do_remote> <nome_do_branch>: Envia o branch local especificado para o repositório remoto especificado.
Links para Estudo
Documentação oficial do Git: https://git-scm.com/doc
Livro Pro Git (gratuito e disponível em vários idiomas): https://git-scm.com/book
Git - Guia Prático: https://rogerdudler.github.io/git-guide/index.pt_BR.html
Git Cheatsheet (folha de referência rápida): https://github.github.com/training-kit/downloads/pt_BR/github-git-cheat-sheet/
Curso de Git e GitHub do GitHub Learning Lab: https://lab.github.com/githubtraining/introduction-to-github