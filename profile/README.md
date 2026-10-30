# avnServices

Desenvolvimento do **Ayccer ERP**.

## Fluxo de trabalho

Todo trabalho parte de uma **task** (issue) no projeto da organização. Nenhum código vai direto para a `main`: tudo entra por Pull Request, revisado por outra pessoa do time.

### 1. Nome da branch

Padrão: `feature/<número da task>`

| Exemplo | Task |
|---|---|
| `feature/42` | #42 |
| `feature/108` | #108 |

Para correções de bug, use `fix/<número da task>` (ex.: `fix/57`).

### 2. Pull Request

- **Título**: nome da task, seguido do número. Ex.: `Cadastro de clientes (#42)`
- **Descrição**: sempre inclua `Closes #42`, para o PR ficar ligado à task e fechá-la no merge.
- **Revisão**: o PR só é mergeado depois da aprovação de outra pessoa, nunca do próprio autor.

### 3. Checklist antes de abrir o PR

- [ ] A branch segue o padrão `feature/<número da task>`
- [ ] O título e o `Closes #N` estão preenchidos
- [ ] O código compila e os testes passam
- [ ] Não há senhas, tokens ou dados sensíveis no código