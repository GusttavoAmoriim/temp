treinando o uso do git e github

PRIMEIRO COMMIT

1 - abra o Git Bush na pasta que está o arquivo
2 - git init: foi inicializado um repositório git vazio.
	ao finalizar o comando vai aparecer entre parenteses (master ou main) o que significa  que você está dentro da branch master, é a linha do tempo principal criado automaticamente.
	uma pasta oculta .git aparece
3 - git add + nome do arquivo.extensão: manda os arquivos da pasta para  área de standy (fica na espera para ir do commit)
	git status: se o arquivo estiver verde, ele está pronto pra ser comitado
4 - git commit -m "nome do commit"
	git status: vai aparecer a mensagem "nothing to commit", até agora está ok. PROSSIGA 
	git branch -M "main": renomea a branch de master para main
5 - no github, vai em repositório e cria um novo.
6 - git remote add origin link_do_repositório.git: criando uma conexão entre o repositório local e o do github.
7 - git push -u origin main: enviando os arquivos para o github. origin é um nome que você deu na etapa 6 para o repositório, e main é o nome da branch.
	Se aparecer o erro "fatal: protocol 'https' not is supported", digite o seguinte comando ''git remote set-url origin + o seu link'' e então após isso dar o comando do push, esse erro pode acontecer devido a caracteres especiais...

dica: para colar textos no git  use a tecla INSERT ou CRRL+SHIFT+V.
	clear, limpa a tela do git