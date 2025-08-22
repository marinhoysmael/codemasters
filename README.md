### 1. Sistema de Controle de Biblioteca Escolar
**Descrição:** Sistema para cadastro, empréstimo e devolução de livros.

**Requisitos Funcionais:**
1. Cadastro de livros com título, autor, ISBN e quantidade.
2. Cadastro de alunos.
3. Registro de empréstimos e devoluções.
4. Consulta de livros disponíveis.

**Requisitos Não Funcionais:**
- Interface responsiva.
- API REST segura com autenticação JWT.

**Histórias de Usuário:**
- **Como bibliotecário**, quero cadastrar novos livros **para que** estejam disponíveis para empréstimo.
  - **Critérios de Aceite:** Cadastro com campos obrigatórios; confirmação visual; validação de ISBN.

**Etapas/Sprints:**
- Sprint 1: CRUD de livros e alunos.
- Sprint 2: Empréstimos e devoluções.
- Sprint 3: Autenticação e relatórios.
