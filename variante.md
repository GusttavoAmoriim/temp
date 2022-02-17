criando uma ramificação da branch principal "main"

1 - git checkout -b "nome da branch": criando a ramificação da linha principal. o checkout sai da branch principal "main" e entra na nova.
2 - git add . : manda todos os arquivos para área de standy
	git status: se o arquivo estiver verde, ele está pronto pra ser comitado. New file é se for adicionado um novo arquivo para comitar. Modified é um arquivo que sofreu alteração e ja tinha sido comitado antes.
3  - git commit -m "nome do commit"
 não precisa do git remote pois a conexão já foi criada no primeiro commit
4 - git push origin "nome da nova branch sem aspas"


----------------------------
para voltar pra branch main, "git checkout main" e para ir para branch criada "git checkout nome_da_branch". veja que não tem o -b

estando na na branch main, o comando git merge "nome da branch" unifica as duas branch. confirme com "git push origin main"