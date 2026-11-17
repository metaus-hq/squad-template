# squad-template

Modelo base da **metaus-hq** para projetos com um squad de agentes
[Claude Code](https://code.claude.com), com fluxo **issue → PR** e aprovação humana
em cada etapa.

## O que vem pronto
- `CLAUDE.md`: contexto, convenções e regras do squad
- `.claude/agents/`: planner, dev, tester e reviewer
- `.claude/settings.json`: permissões básicas (bloqueia `.env` e force push)
- `.github/`: modelo de PR e CODEOWNERS
- `docs/decisions/`: modelo de registro de decisões (ADR)

## Como usar
1. Clique em **Use this template** (ou use `gh repo create ... --template`).
2. Preencha o `CLAUDE.md` com objetivo, stack e comandos do projeto.
3. Troque o usuário no `.github/CODEOWNERS`.
4. Abra no VS Code e peça ao `planner` o plano da primeira tarefa.

## Fluxo
planner (plano) → aprovação humana → dev → tester → reviewer → Pull Request → merge humano.
