# Semana 1 — Primeiro Contato

## Objetivo da semana

Praticar até virar automático: terminal, Git/GitHub, Python (REPL vs script),
Excel básico, e fundamentos de generalismo de TI (processos, IP/porta, Docker).
Como o ambiente (WSL2, VS Code, Python, Docker, PostgreSQL, Git) já estava
configurado, o foco não foi instalação, e sim repetição até fixar.

## O que foi feito

- **Terminal:** `pwd`, `ls`, `cd`, `mkdir`, `touch`, `rm`, `cat`, `cp`, `mv`, `head`,
  redirecionamento com `>`.
- **Git:** fluxo completo `init → status → add → commit → remote add → push`.
- **GitHub:** repositório público criado e conectado via SSH.
- **Python:** diferença prática entre REPL (`python3` interativo) e script (`.py`
  executado com `python3 arquivo.py`).
- **Excel:** células, referências, `=SOMA()`, `=MÉDIA()`, `=SE()` (lógica condicional,
  antecipada da Semana 2).
- **Canivete Suíço:** processos (`htop` vs Gerenciador de Tarefas do Windows),
  conceito de IP/porta, `docker ps` / `docker --version`.
- **Algoritmo sem código:** sequência de passos de uma receita real (aglio e olio),
  identificando dependência de ordem e paralelismo entre processos (água fervendo
  + preparo do alho, sincronizados no ponto certo).
- **Matemática:** revisão de frações, porcentagem e regra de três simples.

## Decisões técnicas e por quê

- **Estrutura do repositório:** optei por um único repositório
  (`data-learning-journey`) para toda a jornada, organizado por bloco/semana,
  em vez de um repositório por projeto. Facilita ver a evolução completa num
  lugar só.
- **Nomenclatura em inglês:** pastas e nomes de repositório em inglês
  (`block-0-foundation`, não `bloco-0-fundacao`), visando o mercado
  internacional/alemão como público-alvo do portfólio.
- **`.gitignore` desde o primeiro commit:** adicionado para excluir arquivos de
  metadado do Windows/WSL (`*:Zone.Identifier`) e artefatos futuros
  (`venv/`, `__pycache__/`) antes que "sujassem" o histórico do Git.
- **Roadmap público:** decidi manter o arquivo de planejamento de estudos
  (`notes/roadmap...md`) público no repositório — reforça a ideia de
  "aprender em público", mostrando método, não só resultado.

## Erros encontrados e resolvidos

- `git add` sem argumento → Git sugeriu `git add .`; usei `git add README.md`
  para ser mais específico.
- Docker não reconhecido no WSL2 (`command not found`) → resolvido ativando
  a WSL Integration nas configurações do Docker Desktop.
- Erros de sintaxe no REPL Python (parêntese não fechado, `#` mal posicionado)
  → corrigidos entendendo a mensagem de erro, não só copiando a correção.