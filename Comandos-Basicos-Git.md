## Guia de Comandos Básicos do Git

- git --version (Verifica a versão atual do Git

- git config -–list (Lista as configurações do Git, se estiver dentro do repositório, lista mais itens)

- git config -–global user.name "Meu Nome"  (Define o nome de usuário para o Git)
- git config -–global user.email "email@dominio.com" (Define o e-mail de usuário para o Git (tem de ser o cadastrado no GitHub)
- git config -–global core.editor vim (Define o editor de texto padrão para abrir automaticamente arquivos informados pelo Git)
- git init » (Inicializa um repositório Git dentro da pasta)
- git status (Vê o estado atual do projeto)
- git add arquivo.txt (Adiciona o arquivo arquivo.txt ao projeto)

### Opções do Parâmetros add

- git add . (usado para adicionar arquivos novos e modificados mas não os deletados)
- git add * (usado para adicionar arquivos novos e modificados do diretório atual)
- git add -A (Adiciona todos arquivos que foram modificados, mesmo que: --all)
- git add *.txt (Adiciona todos os arquivos '.txt' que foram modificados)
- git commit -m "Minhas mudanças efetuadas"  (Armazena as mudanças efetuadas e descreve o que foi alterado)
- git log (Mostra todas as mudanças que já foram efetuadas: commit, autor e data)
- git push -u origin master (Envia todos os arquivos modificados e “commitados” para o repositório no github)

### Definições do  "git push -u origin master"

- -u   (faz com que o Git armazene esse comando e da próxima vez basta utilizarmos git push)

- origin- (diz que o repositório no github possui o mesmo nome do projeto/diretório que você está enviando)

- master - (o nome da branch (indicador)

  

  ### Continuação dos comandos Git

- git pull origin master (Verifica as mudanças efetuadas por outros colaboradores do projeto)

- git reset arquivo.txt (Remove um arquivo do projeto)

- git checkout – arquivo.txt (Desfaz a última alteração feita num arquivo)

- git rm "*.txt" (Remove 1 ou mais arquivos utilizando “curinga”)

- git clone https://github.com/user/project.git  (Copia um projeto pro seu PC a partir do repositório GitHub)

- git diff HEAD (Verifica as partes dos arquivos alterados no último commit)

- info git (Obtém a Documentação do git)

- man git (Obtém o Manual do git)