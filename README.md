# t05-t05g09_18586_18597
t05-t05g09_18586_18597 created by GitHub Classroom

1. Instalação

Todos os ficheiros que se encontram no main (exceto o T4-Latex) necessitam de ser transferidos em modo .zip.
Pode-se transferir um a um e ao fim zipar todos os ficheiros.
Com os ficheiros em .zip, deve-se carregar o projeto no Overleaf.

2. Exemplo de uso

O layout do projeto, contém índices tanto de figuras, quanto de tabelas e também o índice geral do documento, com fácil entendimento do código e sua estrutura.
A estrutura está divida por capítulos onde facilmente pode-se acrescentar novos capítulos ao documento, marcações de pontos e alterações na cor da fonte.
É necessário ter atenção onde inicia e termina o documento e de acordo com o que se é acrescentado, deve estar entre o \begin{document} e \end{document}

3. Documentação

O projeto baseia-se em um relatório técnico em linguagem LaTeX, onde podemos configurar toda a estrutura pela linguagem fornecida, foi necessário utilizar bibliotecas
para que toda a estrutura entrasse de acordo com o que queríamos e o que era preciso. A nossa estrutura do projeto e envio para o github foi elaborada via gitbash, onde 
editavámos o projeto no Overleaf, descarregavámos e fazíamos upload com a versão atual na pasta main de cada computador.

4. Descrição do Projeto

4.1. Principais comandos utilizados.

Para a utilização do github, optamos por utilizar o git bash pelo SO Windows 11. Abaixo segue-se os principais comandos utilizados para a realização da transferências
de ficheiros para o github.

$ git config --global user.name "Victor"
$ git config --global user.email "a18586@alunos.ipca.pt"
$ git init
$ ssh-keygen -t rsa -C "a18586@alunos.ipca.pt"
$ ssh -T git@github.com
$ git remote add origin git@github.com:LabInf2022-23/t05-t05g09_18586_18597
$ git pull ou push (depende de quem iniciou o projeto)
$ git checkout main
...
Switched to branch 'questao_1'
Your branch is up to date with 'origin/questao_1'. // Onde questao_1 é o nome da branch.
$ git add main.tex
$ git commit -m "ficheiros adicionais"
$ git push origin questao_1
...
$ git checkout main

$ git mergetool

4.2. Divisão do Projeto

O projeto foi-se dividido em 9 issues e 9 branchs (+1 branch main), ou seja, para cada issue, ordenamos uma branch. Contudo a elaboração do projeto foi feita por ambos os membros do grupo em simultâneo, o que facilitou a execução do trabalho.

5. Problemas ao Decorrer do Projeto

Ao decorrer do projeto, encontramos uma situação na qual não estávamos a espera, que na nossa bash mostrava ao realizar o pull a seguinte mensagem:

#Utilizador@T202108702 MINGW64 ~/Desktop/TP_GIT (main|MERGING)
$ git pull
error: Pulling is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: Exiting because of an unresolved conflict.

Ao utilizar o comando:

$ git mergetool

Podemos perceber que nosso erro estava a ser de não adicionar o ficheiro main.tex pela bash, pensando que somente alterar na pasta raiz era suficiente.
Então podemos continuar a elaboração do projeto com os comandos:

$ git checkout main
$ git checkout nome_da_branch

6. Conclusão

A elaboração do TP05 baseado no github, nos proporcionou uma excelente experiência com a plataforma, pois conseguimos executar as ações que nos foram propostas. Mesmo enfrentando alguns problemas de comunicação entre nossos dispositivos e o github, conseguimos passar por cima dos obstáculos, o que a termo pessoal, trouxe-nos mais um ânimo para a continuação do projeto. Conseguimos analisar com este projeto, alguns dos principais conceitos da plataforma git e como ele funciona. Optamos por executar o projeto em git bash, o que para nós tornava mais interessante a execução das tarefas, pois nos proporcionava expandir mais nossos horizontes ao executar as tarefas por comandos. O conhecimento que foi adquirido ao decorrer das aulas e com a elaboração deste projeto, será fortalecido ao longo dos próximos anos, pois ambos sabemos que a plataforma será essencial na nosso percursso acadêmico e profissional. 




