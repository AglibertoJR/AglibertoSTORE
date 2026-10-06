# AglibertoStore — Workflow de Git e GitHub

## Objetivo

Usar Git não apenas como armazenamento, mas como parte do desenvolvimento profissional.

## Quando fazer commit

Fazer commit quando uma unidade lógica estiver concluída e em estado minimamente estável.

Exemplos:

- nova entidade funcionando;
- novo endpoint funcionando;
- regra de negócio implementada;
- teste adicionado;
- correção de bug isolada;
- refatoração isolada;
- documentação significativa.

Evitar commits vagos como:

- `coisas`
- `alterações`
- `teste`
- `final`

## Convenção recomendada

Usar Conventional Commits quando possível:

```text
feat: nova funcionalidade
fix: correção de bug
refactor: refatoração
 test: testes
docs: documentação
chore: manutenção/configuração
```

## Exemplo

```bash
git add .
git commit -m "feat: create product entity"
git push origin main
```

> O comando exato será ensinado antes do primeiro uso; não presumir domínio de Git.

## Regra de aula

Antes de pedir um commit, explicar:
1. o que mudou;
2. por que a mudança merece um commit;
3. o que o commit deve conter;
4. a mensagem sugerida.

## Checkpoints

Usar tags quando houver versões importantes, por exemplo:

```text
v0.1.0
v0.2.0
v1.0.0
```

## Recuperação de contexto

Quando o projeto estiver em um chat novo, informar:

- último commit;
- branch atual;
- estado do `PROJECT_STATE.md`;
- etapa atual do `ROADMAP.md`.
