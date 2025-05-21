# oficina-git-github
Oficina promovida aos professores

## Projeto git-github

```mermaid
classDiagram
Turma "1" <-- "*" Aluno
Turma "1" <-- "1..2" Professor

class Aluno {
    - matricula: int
    - nome: String
    - contato: String
}

class Professor {
    - siape: String
    - nome: String
    - titulacao: String
}

class Turma {
    - ano: int
}