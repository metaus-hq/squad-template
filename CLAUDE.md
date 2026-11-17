# [Nome do projeto]

## Objetivo
[Uma frase sobre o que o projeto resolve.]

## Stack e comandos
- Stack: [linguagens e frameworks]
- Instalar: [comando]
- Rodar: [comando]
- Testes: [comando]
- Lint/format: [comando]

## Convenções
- Commits no padrão Conventional Commits (feat:, fix:, docs:, test:, refactor:)
- Uma branch por tarefa: feat/<assunto> ou fix/<assunto>
- Nunca commitar direto na main; todo trabalho entra por Pull Request
- Nunca ler, editar ou commitar arquivos .env ou segredos

## Fluxo do squad
1. planner: transforma a demanda em tarefas com critérios de aceite e PARA para aprovação do Mateus.
2. dev: implementa só o que foi aprovado, em uma branch.
3. tester: escreve e roda os testes.
4. reviewer: revisa (somente leitura) e reporta problemas.
5. Abrir PR e aguardar aprovação humana. O merge é sempre do Mateus.

## Quando parar e perguntar
- Requisito ambíguo ou decisão de arquitetura nova
- Mudança que afete banco de dados, autenticação ou dependências
- Qualquer ação destrutiva (apagar arquivos, reescrever histórico)

## Decisões de arquitetura
Registre em docs/decisions/ (um arquivo por decisão, usando 0000-modelo-adr.md).
