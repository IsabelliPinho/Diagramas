# Diagramas conceitual e lógico
 Aluno
Atributos:
nome_aluno
endereco_aluno
cidade_aluno
-Indentificador:
mat:matricula (alunos)

 # Disciplina:
nome_disc
carga_hor
-Indentificador:
cod_disc:codigo da disciplina (disciplinas)

# Turmas:
fk_cod_prof
fk_cod_disc
ano
horario
nota
-Indentificador:
cod_turma: codigo da turma (turma)

# Professores:
nome_prof
endereco_prof
cidade_prof
-Indentificador:
cod_prof:codigo do professor (professores)

# historico:
fk_mat
fk_cod_disc
fk_cod_turma
fk_cod_prof
fk_ano
fk_not
frequencia
