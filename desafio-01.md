# 🏫 Desafio 01 — Sistema de Notas e Aprovação (Escola)

> Um sistema de gestão escolar precisa calcular a média final e a situação dos alunos em diferentes disciplinas, considerando as notas das provas e trabalhos.

Regras de negócio:
- Cada disciplina deve conter:
- nome da disciplina
- peso da prova
- peso do trabalho

Cada aluno deve ter:
- nome
- notas (prova e trabalho) para cada disciplina

A média final da disciplina deve ser calculada pela fórmula:
```
Média = (nota_prova * peso_prova + nota_trabalho * peso_trabalho) / (peso_prova + peso_trabalho)
```

A situação final deve ser:
- Aprovado se média ≥ 7
- Recuperação se 5 ≤ média < 7
- Reprovado se média < 5

### Requisitos:

- Retornar a situação final de cada aluno e a média em cada disciplina.
- Implementação orientada a objetos.
- Deve permitir a inclusão de novas regras de aprovação (ex: bônus por frequência).

Arquitetura limpa é diferencial.
