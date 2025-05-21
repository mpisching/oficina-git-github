# oficina-git-github
Oficina promovida aos professores

## Projeto git-github

adicionando um diagrama de classes...

```mermaid
classDiagram
Turma "1" --> "*" Aluno
Turma "1" --> "1..2" Professor
Comunidade <|-- Aluno
Comunidade <|-- Professor
Comunidade --> "1" Endereco

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

class Comunidade {
    - nome: String
    - email: String
    - contato: String
}

class Endereco {
    - cep: String
}