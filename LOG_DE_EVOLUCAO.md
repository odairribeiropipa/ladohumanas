# Log de Evolução do Projeto Lado Humanas

Este arquivo registra mudanças relevantes feitas no projeto para que qualquer pessoa, Codex ou Claude consiga entender o que foi alterado, quando, por quem, por qual motivo e como reverter se necessário.

Ele não substitui o Git. Ele complementa o histórico técnico com contexto editorial, criativo e estratégico.

## Como usar

Crie um novo registro sempre que houver mudança relevante, especialmente quando envolver:

- criação, revisão ou reorganização de arquivos;
- alteração de tom, estrutura, conceito, título, personagem, narrativa ou direção estética;
- criação de versões alternativas;
- decisões editoriais importantes;
- commits, branches, tags ou publicações no GitHub;
- reversões, restaurações ou correções de mudanças anteriores.

Mudanças pequenas e puramente mecânicas podem ser agrupadas em um único registro.

## Modelo de registro

```md
## 2026-05-20 08:19 -03:00 — Título curto da mudança

- Agente: Codex, Claude ou humano.
- Tipo: criação, revisão, organização, versão, correção, reversão, Git/GitHub ou decisão editorial.
- Arquivos afetados:
  - `caminho/do/arquivo.md`
- Resumo:
  Explique em poucas linhas o que mudou.
- Motivo:
  Explique por que a mudança foi feita.
- Impacto editorial:
  Indique efeito em tom, estrutura, leitura, continuidade, autoria ou organização.
- Git/GitHub:
  Branch: `nome-da-branch` ou `não aplicável`.
  Commit: `hash` ou `ainda não commitado`.
  Pull request: `link` ou `não aplicável`.
- Como reverter:
  Explique o caminho de reversão. Exemplo: restaurar versão anterior, desfazer commit, recuperar arquivo alternativo ou consultar o diff.
- Observações para o próximo agente:
  Diga o que outra IA precisa saber antes de continuar.
```

## Registros

## 2026-05-20 08:19 -03:00 — Criação do sistema de instruções e log

- Agente: Codex.
- Tipo: criação, organização e decisão editorial.
- Arquivos afetados:
  - `INSTRUCOES_LADO_HUMANAS.md`
  - `AGENTS.md`
  - `CLAUDE.md`
  - `LOG_DE_EVOLUCAO.md`
- Resumo:
  Foram criadas instruções comuns para o projeto Lado Humanas, instruções específicas para Codex e Claude, e este log de evolução para registrar mudanças relevantes.
- Motivo:
  Estabelecer uma forma coerente de trabalho entre agentes diferentes, preservando autoria, evitando sobreposição de conteúdo e facilitando reversões futuras.
- Impacto editorial:
  O projeto passou a ter uma constituição editorial comum e um mecanismo de memória operacional para acompanhar decisões, mudanças e versões.
- Git/GitHub:
  Branch: `não aplicável`.
  Commit: `ainda não commitado`.
  Pull request: `não aplicável`.
  Observação: a pasta ainda não é um repositório Git no momento deste registro.
- Como reverter:
  Remover os arquivos criados neste registro ou restaurar versões anteriores caso o projeto já tenha sido colocado sob Git posteriormente.
- Observações para o próximo agente:
  Antes de criar ou alterar conteúdo relevante, leia `INSTRUCOES_LADO_HUMANAS.md` e registre a mudança neste arquivo. Se o Git for inicializado depois, acrescente branch, hash de commit e links de pull request quando existirem.

## 2026-05-20 08:23 -03:00 — Criação da memória central

- Agente: Codex.
- Tipo: criação, organização e decisão operacional.
- Arquivos afetados:
  - `MEMORIA_CENTRAL.md`
  - `INSTRUCOES_LADO_HUMANAS.md`
  - `AGENTS.md`
  - `CLAUDE.md`
  - `LOG_DE_EVOLUCAO.md`
- Resumo:
  Foi criado um arquivo centralizado para memórias duradouras do projeto, separando contexto estável de histórico de mudanças. As instruções de Codex e Claude foram ajustadas para consultar e atualizar essa memória quando necessário.
- Motivo:
  Permitir que agentes diferentes compreendam preferências, decisões canônicas, perguntas em aberto e contexto estrutural sem depender apenas da conversa atual.
- Impacto editorial:
  O projeto ganhou uma camada de continuidade mais estável, capaz de preservar intenção, voz e decisões de longo prazo entre sessões e entre IAs.
- Git/GitHub:
  Branch: `não aplicável`.
  Commit: `ainda não commitado`.
  Pull request: `não aplicável`.
  Observação: a pasta ainda não é um repositório Git no momento deste registro.
- Como reverter:
  Remover `MEMORIA_CENTRAL.md` e desfazer as referências adicionadas em `INSTRUCOES_LADO_HUMANAS.md`, `AGENTS.md`, `CLAUDE.md` e `LOG_DE_EVOLUCAO.md`.
- Observações para o próximo agente:
  Use `MEMORIA_CENTRAL.md` para contexto duradouro e `LOG_DE_EVOLUCAO.md` para histórico de mudanças. Não duplique tudo nos dois arquivos; registre em cada um apenas o que pertence à sua função.

## 2026-05-20 08:34 -03:00 — Inicialização do Git local

- Agente: Codex.
- Tipo: Git/GitHub, organização e versionamento.
- Arquivos afetados:
  - `.gitignore`
  - `AGENTS.md`
  - `CLAUDE.md`
  - `INSTRUCOES_LADO_HUMANAS.md`
  - `LOG_DE_EVOLUCAO.md`
  - `MEMORIA_CENTRAL.md`
- Resumo:
  O projeto foi inicializado como repositório Git local na branch `main`. Foi criado um `.gitignore` para evitar versionamento de estado local de editores e arquivos temporários. Os arquivos-base de governança editorial foram incluídos no primeiro commit.
- Motivo:
  Permitir versionamento técnico, reversão de mudanças e leitura clara do histórico por humanos, Codex e Claude.
- Impacto editorial:
  O projeto passa a ter uma base reversível e auditável para mudanças futuras, reduzindo o risco de perda ou sobreposição de conteúdo.
- Git/GitHub:
  Branch: `main`.
  Commit inicial: `7ad7ea7`.
  Pull request: `não aplicável`.
  Observação: repositório remoto no GitHub ainda não configurado neste registro.
- Como reverter:
  Para desfazer o commit inicial, usar Git para restaurar o estado anterior ou remover o repositório local se ainda não houver conteúdo novo dependente dele. Como o commit `7ad7ea7` contém a base de governança, qualquer reversão deve preservar cópias dos arquivos caso eles ainda sejam úteis.
- Observações para o próximo agente:
  A pasta `.obsidian` foi deixada fora do versionamento por ser estado local do editor. Se o usuário quiser versionar configurações do Obsidian, revise `.gitignore` antes de adicionar esses arquivos.

## 2026-05-20 08:37 -03:00 — Verificação do GitHub remoto

- Agente: Codex.
- Tipo: Git/GitHub e decisão operacional.
- Arquivos afetados:
  - `MEMORIA_CENTRAL.md`
  - `LOG_DE_EVOLUCAO.md`
- Resumo:
  Foi verificado que o GitHub App está conectado à conta `arthurcmribeiro` e que o GitHub CLI (`gh`) está instalado no Windows. Porém, o `gh` ainda não está autenticado em nenhum host GitHub, e não foi encontrado repositório remoto instalado com nome relacionado a `lado-humanas`.
- Motivo:
  Preparar a publicação futura do repositório local no GitHub sem fingir que o remoto já existe.
- Impacto editorial:
  O projeto já possui versionamento local reversível, mas ainda não tem backup remoto nem histórico compartilhado no GitHub.
- Git/GitHub:
  Branch local: `main`.
  Commit local atual antes deste registro: `d0c738e`.
  Repositório remoto: `ainda não configurado`.
  Pull request: `não aplicável`.
- Como reverter:
  Este registro pode ser revertido removendo as linhas adicionadas em `MEMORIA_CENTRAL.md` e esta entrada do log. Não há impacto sobre o conteúdo criativo.
- Observações para o próximo agente:
  Para publicar no GitHub, autenticar o GitHub CLI com `gh auth login` ou criar manualmente um repositório privado no GitHub e adicionar o remote `origin`.
