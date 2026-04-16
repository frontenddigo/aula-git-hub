Feito para aprender o git-bash
<p>
O Git Bash é um emulador de terminal para Windows que permite usar comandos Bash (Linux) e Git no mesmo ambiente. Os principais comandos incluem cd (navegar), ls (listar arquivos), git init (iniciar repositório), git add (preparar arquivos), git commit (salvar alterações) e git push (enviar para repositório remoto). 
</p>
<p>Aqui estão os comandos essenciais divididos por categoria:
1. Navegação e Manipulação de Arquivos (Bash) 
pwd: Mostra o diretório atual.
ls / ls -la: Lista arquivos e pastas (o -la mostra ocultos e detalhes).
cd <pasta>: Muda para a pasta indicada (ex: cd documentos).
cd ..: Volta para a pasta anterior.
mkdir <pasta>: Cria uma nova pasta.
touch <arquivo>: Cria um novo arquivo vazio.
rm <arquivo>: Remove um arquivo.
clear: Limpa a tela do terminal. 
</p>
<p>
2. Configuração Inicial do Git 
git config --global user.name "Seu Nome": Define seu nome para commits.
git config --global user.email "seuemail@exemplo.com": Define seu e-mail.
git config --list: Lista todas as configurações. 
</p>
 <p>
3. Gerenciamento de Repositórios
git init: Inicia um novo repositório Git na pasta atual.
git clone <url>: Clona um repositório existente.
git status: Verifica o estado dos arquivos (quais foram modificados, adicionados).
git diff: Mostra a diferença entre os arquivos modificados e o último commit. 
</p>
4. Commits e Ramificações
git add <arquivo>: Adiciona um arquivo específico para a área de preparação (staging).
git add .: Adiciona todos os arquivos modificados/novos da pasta atual.
git commit -m "mensagem": Salva as alterações com uma mensagem explicativa.
git branch: Lista, cria ou exclui branches.
git checkout -b <nome-da-branch>: Cria e muda para uma nova branch.
git merge <branch>: Incorpora as alterações da branch especificada na branch atual. 
<p>
5. Repositório Remoto (GitHub/GitLab)
git remote add origin <url>: Conecta seu repositório local a um remoto.
git push -u origin <branch>: Envia seus commits locais para o repositório remoto.
git pull: Busca e incorpora as alterações do repositório remoto. 
</p>
Atalhos Úteis no Git Bash
Tab: Autocompleta nomes de arquivos e pastas.
Ctrl + C: Cancela o comando atual em execução.
Ctrl + L: Limpa a tela (semelhante ao comando clear).
Ctrl + R: Pesquisa no histórico de comandos.
Botão direito do mouse: Cola o texto na área de transferência.
<p>
Comandos: …ou crie um novo repositório na linha de comando
echo "# qul" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/frontenddigo/*nome-da-pasta*.git 
git push -u origin main
</p>
 <p>
...ou enviar um repositório existente pela linha de comando
git remote add origin https://github.com/frontenddigo/*nome-da-pasta*.git
git branch -M main
git push -u origin main
 </p>
