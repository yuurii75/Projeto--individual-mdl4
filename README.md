# Projeto-individual mdl4

#A Resilia está pensando em lançar um novo sistema de acompanhamento e para isso precisa de ajuda para modelar um banco de dados que vai armazenar seus cursos, turmas e alunos.


1 - Existem outras entidades além dessas três?

R: Sim, será necessário mais entidades para completar o modelo, além de Cursos, Alunos e Turmas, adicionei Professores.


2 - Quais são os principais campos e tipos?

R: Os principais campos são ID, NOME, EMAIL e N_MATRICULA. Os tipos são eles respectivamente INT e VARCHAR.


3 - Como essas entidades são relacionadas?

Alunos matriculam-se em Cursos

Cursos geram Turmas 

Turmas  possuem Alunos

Turmas contem Professores

#Extras
Script com o código na pasta SQLScript.
