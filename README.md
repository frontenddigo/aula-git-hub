Comandos Básicos de Configuração e Início
git init: Inicializa um novo repositório Git local.
git clone [url]: Clona um repositório remoto para sua máquina local.
git config --global user.name "Seu Nome": Define o nome de usuário para commits.
git config --global user.email "email@exemplo.com": Define o e-mail de usuário para commits.

Comandos de Rotina (Salvar Alterações)
git status: Mostra o estado atual da área de preparação e arquivos modificados.
git add [arquivo]: Adiciona arquivos específicos à área de staging.
git add .: Adiciona todos os arquivos modificados e novos à área de staging.
git commit -m "mensagem": Grava as alterações da staging no histórico com uma mensagem.
git commit --amend: Corrige ou altera a mensagem do último commit.

Comandos de Ramo (Branches)
git branch: Lista as branches locais.
git branch [nome-branch]: Cria uma nova branch.
git checkout [nome-branch]: Alterna para a branch especificada.
git checkout -b [nome-branch]: Cria e alterna para uma nova branch imediatamente.
git merge [nome-branch]: Mescla uma branch com a atual.

Comandos de Repositório Remoto (GitHub/GitLab)
git push origin [branch]: Envia as commits locais para o repositório remoto.
git pull: Atualiza o repositório local com as mudanças do remoto.
git fetch: Baixa as mudanças do repositório remoto sem realizar merge automaticamente.

Comandos de Histórico e Análise
git log: Exibe o histórico de commits.
git diff: Mostra as diferenças entre arquivos que ainda não foram adicionados à staging.
git bisect: Usa pesquisa binária para encontrar commits que introduziram bugs.
