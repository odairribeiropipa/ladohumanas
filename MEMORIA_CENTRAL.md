# Memória Central do Projeto Lado Humanas

Este arquivo guarda o contexto duradouro do projeto. Ele existe para que humanos, Codex e Claude possam continuar o trabalho com coerência, sem depender apenas da memória da conversa atual.

A memória central não é um diário de tudo que aconteceu. Para histórico de mudanças, use `LOG_DE_EVOLUCAO.md`. Aqui devem ficar preferências estáveis, decisões canônicas, contexto de obras, padrões de voz, cuidados recorrentes e perguntas importantes ainda em aberto.

## Como usar

Antes de criar, revisar ou reorganizar material relevante, leia:

1. `INSTRUCOES_LADO_HUMANAS.md`
2. `MEMORIA_CENTRAL.md`
3. `LOG_DE_EVOLUCAO.md`, quando precisar entender mudanças recentes

Atualize esta memória quando surgir algo que deva orientar trabalhos futuros, como:

- preferência firme de estilo, tom, forma ou organização;
- decisão sobre identidade de obra, personagem, tema, título ou estrutura;
- informação recorrente que outra IA precisa saber;
- restrição importante;
- pergunta em aberto que depende de decisão humana;
- relação entre arquivos, projetos ou versões.

Não use este arquivo para:

- registrar cada pequena alteração;
- guardar senhas, chaves, tokens ou dados sensíveis;
- substituir o Git;
- substituir o log de evolução;
- fixar como verdade algo que ainda é só hipótese.

## Estado geral do projeto

- Nome do projeto: Lado Humanas.
- Natureza: acervo criativo e intelectual com livros, músicas, roteiros, artes, ideias, notas e materiais em desenvolvimento.
- Pastas principais atuais:
  - `LIVROS`
  - `MUSICAS`
  - `ROTEIROS`
- Agentes previstos: Codex e Claude, ambos operando a partir das mesmas instruções centrais.
- Estado técnico registrado em 2026-05-20 08:34 -03:00: Git local inicializado na branch `main`, com commit inicial `7ad7ea7`.
- Estado GitHub registrado em 2026-05-20 08:37 -03:00: GitHub App conectado à conta `arthurcmribeiro`; GitHub CLI (`gh`) instalado, mas ainda não autenticado no Windows; repositório remoto ainda não criado/configurado.

## Preferências editoriais estáveis

- O tom deve unir profundidade intelectual e linguagem natural.
- A referência estética é a elegância de um imortal da Academia Brasileira de Letras, mas sem pedantismo.
- O público geral deve conseguir compreender o texto sem sentir que está diante de jargão acadêmico.
- A autoria humana deve ser preservada; a IA deve lapidar, organizar e expandir sem apagar a voz original.
- Clareza, cadência, precisão e beleza importam juntas.
- Reescritas devem evitar aparência genérica de texto produzido por IA.

## Regras operacionais estáveis

- Não apagar arquivos sem pedido explícito.
- Não substituir obra inteira sem preservar versão anterior.
- Não criar conteúdo duplicado se já houver material parecido.
- Antes de criar algo novo, verificar se existe conteúdo relacionado.
- Mudanças relevantes devem ser registradas em `LOG_DE_EVOLUCAO.md`.
- Memórias novas devem ser registradas aqui apenas quando forem úteis para continuidade futura.
- Quando houver dúvida entre alterar e preservar, preservar.

## Relação entre memória, log e Git

- `MEMORIA_CENTRAL.md`: guarda contexto duradouro e decisões que orientam o futuro.
- `LOG_DE_EVOLUCAO.md`: guarda o histórico narrado das mudanças, com data, motivo, impacto e reversão.
- Git/GitHub: quando forem ativados, guardarão o histórico técnico por commits, branches, tags e pull requests.
- Git local: ativo desde 2026-05-20, branch `main`, primeiro commit `7ad7ea7`.
- GitHub remoto: pendente de autenticação do `gh` ou criação manual de repositório remoto.

## Projetos e áreas

### Livros

- Pasta: `LIVROS`.
- Uso previsto: livros, capítulos, contos, ensaios, prefácios, sinopses, planos de obra e pesquisas literárias.
- Memórias específicas: ainda não registradas.

### Músicas

- Pasta: `MUSICAS`.
- Uso previsto: letras, temas, versos soltos, melodias descritas, conceitos de álbum, nomes de faixa e direção estética.
- Memórias específicas: ainda não registradas.

### Roteiros

- Pasta: `ROTEIROS`.
- Uso previsto: cinema, teatro, vídeos, cenas, diálogos, estruturas narrativas, personagens e argumentos.
- Memórias específicas: ainda não registradas.

## Decisões canônicas

- O projeto terá uma instrução comum para todos os agentes: `INSTRUCOES_LADO_HUMANAS.md`.
- Codex terá instruções específicas em `AGENTS.md`.
- Claude terá instruções específicas em `CLAUDE.md`.
- A memória central será concentrada neste arquivo para evitar versões paralelas e contraditórias.

## Perguntas em aberto

- Haverá um repositório remoto no GitHub?
- Os materiais terão uma organização por obra, por gênero, por data ou por estágio de desenvolvimento?
- O projeto terá um padrão de versionamento por branches, tags ou pastas de versões?

## Modelo para novas memórias

```md
### 2026-05-20 — Título curto da memória

- Origem: humano, Codex, Claude ou arquivo específico.
- Status: confirmado, provisório ou pergunta em aberto.
- Área: geral, livros, músicas, roteiros ou outra.
- Memória:
  Descreva o fato, preferência ou decisão de forma objetiva.
- Implicação prática:
  Explique como isso deve orientar trabalhos futuros.
- Arquivos relacionados:
  - `caminho/do/arquivo.md`
```

## Novas memórias

Use esta seção para acrescentar memórias futuras que ainda não se encaixem nas áreas acima. Quando uma memória se tornar estrutural, mova-a para a seção adequada.
