# sistema_resilia_mod4
Projeto individual para o módulo 4 do curso WebDev Full Stack - Resilia

# Existem outras entidades além dessas três?

Foram criadas as entidades Professor e Matrícula.

# Quais são os principais campos e tipos?

Principais campos: ID e Nome
Principais tipos: INT e VARCHAR

# Como essas entidades estão relacionadas?

ALUNO  possui relacionamento 1:1 com MATRÍCULA;
MATRÍCULA possui relacionamento 1:N com TURMA;
TURMA possui relacionamento 1:N com PROFESSOR e CURSO.

