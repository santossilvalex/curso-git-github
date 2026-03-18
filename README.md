\#Curso TMW Git \& GitHub 2026



Curso produzido por Téo Calvo, ensinando conceitos básicos no qual são utilizados no dia a dia do uso de Git \& GitHub.

Focado em ensinar no versionamento de códigos e repositórios remotos com GitHub.



O curso além dos conceitos básicos, também da acesso ao aprendizado de como trabalhar com GitFlow e VSCode.

Confira o que foi aprendido no curso.

## Fluxo de trabalho Git local

01. git checkout -b <nova-branch>
02. cria ou atualiza arquivos
03. git status
05. git add *arquivos*
06. git status
07. git commit -m "minha mensagem"
08. git checkout main
09. git merge nova_branch

## Fluxo de trabalho GitHub <> Local (projeto próprio ou da sua empresa)
01. git clone <endereco do projeto>
02. git checkout -b <nova_branch>
03. alterações de arquivos
04. git status
05. git add *arquivos*
06. git status
07. git commit -m "nova mensagem"
08. git push origin <nova_branch>
09. abrir Pull request no GitHub para main
10. excluir <nova_branch> origin
11. git checkout main
12. git branch -D <nova_branch>

## Fluxo de trabalho GitHub <> Local (projetos open-source)
01. Fork do projeto para seu próprio github
02. git clone <endereco do projeto fork>
03. git checkout -b <nova_branch>
04. alterações de arquivos
05. git status
06. git add *arquivos*
07. git status
08. git commit -m "nova mensagem"
09. git push origin <nova_branch>
10. abrir Pull request no GitHub da branch fork para a main do projeto original
11. excluir <nova_branch> origin
12. git checkout main
13. git branch -D <nova_branch>

----

## Padrões de nomeclaturas no git

docs: apenas mudanças de documentação;
feat: uma nova funcionalidade;
fix: a correção de um bug;
perf: mudança de código focada em melhorar performance;
refactor: mudança de código que não adiciona uma funcionalidade e também não corrigi um bug;
style: mudanças no código que não afetam seu significado (espaço em branco, formatação, ponto e vírgula, etc);
test: adicionar ou corrigir testes.

----


Curso finalizado no dia - 18/03/26

