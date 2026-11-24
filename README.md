<div align="center">

# `// Banco de Dados Escolar — Projeto de Estudo SQL`

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.herokuapp.com?font=Silkscreen&weight=400&size=14&duration=2600&pause=900&color=FF007F&center=true&vCenter=true&width=720&lines=GESTAO-ESCOLAR-SQL+//+MODELAGEM+DE+BANCO+DE+DADOS;ESQUEMA+RELACIONAL+%7C+NORMALIZACAO+%7C+SQL+%7C+MYSQL;ALUNOS+%7C+CURSOS+%7C+TURMAS+%7C+MATRICULAS" alt="Typing SVG" />
</a>

</div>

<br/>

```bash
CodeByWesley@gestao-escolar-sql:~$ cat schema_overview.log
> PROJETO:   Banco de Dados Escolar (Projeto de Estudo SQL)
> DOMÍNIO:   Esquema de banco de dados relacional para um sistema de gestão escolar
> FOCO:      Modelagem relacional, integridade referencial, normalização
>            e escrita de scripts SQL para criação de esquemas e consultas.
```

---

### `// 01. ENTIDADES DO ESQUEMA RELACIONAL`

| Entidade | Tabela / Escopo | Descrição na Modelagem |
| :--- | :--- | :--- |
| **Alunos** | `Students` | Cadastro centralizado dos estudantes matriculados na instituição[cite: 7]. |
| **Cursos** | `Courses` | Catálogo de cursos e grades oferecidas pelo sistema escolar[cite: 7]. |
| **Turmas** | `Classes` | Organização de turmas vinculadas aos respectivos cursos[cite: 7]. |
| **Matrículas** | `Enrollments` | Tabela associativa que relaciona alunos às turmas/cursos, garantindo integridade referencial[cite: 7]. |

---

### `// 02. CONCEITOS & BOAS PRATICAS APLICADAS`

* **`▸ Modelagem Conceitual e Lógica:`** Definição clara de entidades, atributos, cardinalidades e relacionamentos (`1:N` e `N:N` resolvido via `Enrollments`).
* **`▸ Integridade Referencial:`** Uso de chaves primárias (`PRIMARY KEY`) e chaves estrangeiras (`FOREIGN KEY`) para assegurar consistência entre alunos, cursos, turmas e matrículas[cite: 7].
* **`▸ Scripts DDL & DML:`** Estruturação limpa de criação de tabelas (`CREATE TABLE`) e consultas relacionais (`SELECT`, `JOIN`).

---

### `// 03. STACK & ESTRUTURA DO REPOSITORIO`

<p align="center">
  <img src="https://img.shields.io/badge/SQL-090514?style=for-the-badge&logo=microsoftsqlserver&logoColor=00F3FF" height="28"/>
  <img src="https://img.shields.io/badge/MYSQL-090514?style=for-the-badge&logo=mysql&logoColor=FF007F" height="28"/>
  <img src="https://img.shields.io/badge/MODELAGEM_RELACIONAL-090514?style=for-the-badge&logo=databricks&logoColor=00F3FF" height="28"/>
</p>

```text
gestao-escolar-sql/
├── database/    # Diretório com scripts e artefatos do banco de dados
├── schema.sql   # Script principal com a definição das tabelas e relacionamentos
└── README.md    # Documentação do esquema relacional e objetivos de estudo
```

---

<div align="center">

`CodeByWesley@gestao-escolar-sql
