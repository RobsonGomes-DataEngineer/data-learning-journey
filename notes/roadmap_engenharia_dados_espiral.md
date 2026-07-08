# ROADMAP — ENGENHARIA DE DADOS
### Objetivo final: atuar como Engenheiro de Dados no mercado alemão

---

## POR QUE ESSA VERSÃO É DIFERENTE DA ANTERIOR

| Problema do roadmap original | Ajuste feito aqui |
|---|---|
| 1 tecnologia isolada por semana | Espiral: Bash + Python + SQL + Docs andam juntos desde a semana 1, aprofundando a cada ciclo |
| 46h/semana por 24 meses | 22h tecnologia + 3h inglês + 2h alemão (ajustável) = ~27h/semana sustentável |
| Só engenharia de dados, sem generalismo de TI | Camada "Canivete Suíço" mensal: redes, troubleshooting, Linux geral, segurança básica |
| Sem Markdown como ferramenta | Markdown é usado desde a semana 1 para documentar, não é tópico isolado |
| SQL Server *e* PostgreSQL (duplicado) | Fica só PostgreSQL (gratuito, mais usado fora do ecossistema 100% Microsoft) |
| SAP obrigatório (mês inteiro) | Vira módulo eletivo curto, só se você mirar vaga que pede especificamente |
| Todo microprojeto 100% definido | Metade dos projetos tem tema aberto — você decide o escopo |
| Alemão intenso desde o dia 1 | Alemão leve nos primeiros 6 meses, intensifica na reta final |
| Sem matemática, lógica formal, algoritmos ou Excel | Trilha paralela dedicada, tratando você como leigo total em cada uma — nada é "considerado óbvio" |

**Duração estimada:** ~20 meses, com 22h/semana de tecnologia (dentro da sua faixa de 20-25h).

---

## FILOSOFIA DA ESPIRAL

Cada ciclo (4 semanas) não "fecha" uma tecnologia — ele revisita todas as camadas com profundidade crescente, sempre dentro do **mesmo projeto pessoal em evolução contínua**. Você não terá 24 projetos desconectados; terá 3-4 projetos que crescem com você, mais desafios pontuais de generalismo.

**Estrutura de cada semana (regra fixa):**
- Você aprende um conceito novo (curta, pontual — nunca um curso completo de uma vez)
- Aplica no seu projeto em andamento, no mesmo dia ou no dia seguinte
- Documenta em Markdown o que fez e por quê (isso também é o seu portfólio sendo construído em tempo real)

---

## CARGA HORÁRIA SEMANAL (~24h/semana — dentro da sua faixa de 20-25h)

- **9h** — Núcleo espiral (Python + SQL + Bash + Docs, sempre entrelaçados)
- **4h** — Matemática + Lógica de Programação + Algoritmos (trilha própria, ver seção abaixo)
- **2h** — Excel (trilha própria, ver seção abaixo)
- **3h** — Camada Canivete Suíço (generalismo de TI)
- **3h** — Projeto pessoal em evolução / troubleshooting livre
- **2h** — Inglês instrumental (constante do mês 1 ao fim)
- **1h** — Alemão (meses 1-6: leve/sobrevivência; meses 7-14: moderado; meses 15-20: intenso — aumenta às custas de outras horas na reta final, ver Bloco 3)

> Nos meses 17-20, a carga de alemão sobe (5-6h/semana). Nessa fase, o núcleo espiral e o Canivete Suíço já estão consolidados, então essas horas migram naturalmente para o idioma sem estourar o total semanal.

---

## TRILHA PARALELA: MATEMÁTICA, LÓGICA DE PROGRAMAÇÃO, ALGORITMOS E EXCEL (do zero absoluto)

Essa trilha roda em paralelo ao núcleo espiral, mês a mês, e assume que você nunca teve contato sério com nenhum dos quatro temas. Nada aqui pressupõe "isso você já deve saber".

### Matemática — do zero
- **Bloco 0 (semanas 1-6):** Revisão de aritmética que a escola normalmente deixa enferrujar — frações, porcentagem, regra de três simples. Objetivo único: você nunca travar numa conta básica no meio de um problema de programação.
- **Bloco 1 (meses 2-5):** Álgebra básica (o que é uma variável, uma equação, como isolar um valor) — e o paralelo explícito com variáveis em programação, que parecem a mesma coisa mas não são. Depois, estatística descritiva do zero: média, mediana, moda, desvio padrão — sempre calculada primeiro na mão, depois conferida no Pandas.
- **Bloco 2 (meses 6-13):** Lógica proposicional do zero (o que é uma proposição, tabelas verdade, E/OU/NÃO) — isso destrava a escrita de condições SQL e Python complexas sem "tentativa e erro". Estatística aplicada básica (correlação, distribuição) ligada aos dashboards que você já está construindo.
- **Bloco 3 (meses 14-20):** Matemática de negócio (cálculos por trás de KPIs industriais como o OEE) — nesse ponto você já tem base suficiente pra isso ser aplicação, não teoria nova.

### Lógica de Programação — do zero (separada da sintaxe)
- **Bloco 0:** Antes de qualquer linha de Python, você resolve problemas no papel: fluxogramas simples, pseudocódigo. A ideia é treinar "quebrar um problema em passos pequenos" sem a sintaxe atrapalhando.
- **Bloco 1:** Tradução consciente de fluxogramas/pseudocódigo para código real — você aprende a ver a lógica por trás da sintaxe, não decorar comandos.

### Algoritmos — do básico ao avançado
- **Bloco 0-1:** Noção intuitiva de eficiência, sem termos técnicos ainda — por exemplo, por que procurar um nome numa lista desorganizada é mais lento que numa lista organizada. Isso é sentido na prática antes de virar teoria.
- **Bloco 1-2:** Busca linear e busca binária, algoritmos de ordenação simples (bubble sort, insertion sort) implementados por você na mão — depois comparados com as funções prontas do Python, pra entender por que elas existem.
- **Bloco 2:** Complexidade de algoritmos formalizada (notação Big-O, mas explicada com exemplos concretos do que você já implementou, nunca abstrato puro). Estruturas de dados fundamentais (pilha, fila) explicadas com analogias do dia a dia antes da implementação.
- **Bloco 3:** Algoritmos mais avançados sob demanda (recursão aplicada, noções de grafos) — consolidados na prática intensiva de SQL/Python do mês 19, que deixa de ser "primeira vez vendo isso" e vira revisão.

### Excel — do zero absoluto
- **Bloco 0:** Interface, células, referências, fórmulas básicas (SOMA, MÉDIA, SE) — tratado como se você nunca tivesse aberto o programa.
- **Bloco 1:** Tabelas dinâmicas, PROCV/PROCX, formatação condicional — sempre aplicados no mesmo dataset que você já está tratando em Pandas, fazendo o paralelo direto "isso no Excel é isso no Pandas".
- **Bloco 2:** Power Query (ETL dentro do próprio Excel) — ponte natural pro que você já faz em pipelines Python, e uma das habilidades mais pedidas em vaga júnior de dados, mesmo quando a vaga é "mais avançada" no resto.
- **Bloco 3:** Excel para apresentação executiva (gráficos, dashboards simples) — em paralelo ao que você já constrói no Power BI, pra entender quando um substitui o outro no mundo real.

---

# BLOCO 0 — FUNDAÇÃO CANIVETE SUÍÇO (Semanas 1-6)

Diferente do roadmap anterior, aqui você não "aprende Bash" e depois "aprende Python" — tudo entra junto, em doses pequenas, desde a semana 1. Cada semana segue a mesma distribuição de ~24h (ver seção de carga horária acima), só muda o conteúdo específico.

**Regra de ouro do Bloco 0:** nenhuma semana assume que você já sabe algo. Se um item parecer básico demais, é proposital — a base tem que ser automática antes de você acelerar.

---

### SEMANA 1 — Primeiro contato com o terminal e com você mesmo

> Como você já tem WSL2, VS Code, Python, Docker, PostgreSQL, Git configurados e conta no GitHub, essa semana muda de "instalar" para "praticar até virar automático" — o tempo que seria gasto em setup vira repetição e fixação.

**Núcleo espiral (9h)**
- [ ] Comandos `pwd`, `ls`, `cd`, `mkdir`, `touch`, `rm` — repetir até digitar sem pensar (não vale copiar/colar, é memória muscular)
- [ ] Confirmar `git config --list` (nome/email já configurados) e revisar o fluxo `git init` → `git status` → `git add` → `git commit` num repositório de teste, criado e apagado só pra treinar
- [ ] VS Code: configurar o terminal integrado, atalhos básicos, extensão de preview de Markdown (se ainda não tiver)
- [ ] Escrever seu primeiro `README.md` de verdade (apresentação pessoal, em português)
- [ ] Python: rodar um script simples direto do terminal integrado do VS Code (não só REPL) — confirmar que o ambiente está redondo

**Matemática / Lógica / Algoritmos (4h)**
- [ ] Revisão de frações e porcentagem — resolver ~15 exercícios básicos
- [ ] Regra de três simples aplicada (ex: conversão de unidades) — 10 exercícios
- [ ] O que é um "algoritmo" na vida real, sem código nenhum (ex: os passos de fazer um café, escritos como uma receita numerada)

**Excel (2h)**
- [ ] Abrir o Excel/Google Sheets como se fosse a primeira vez — células, linhas, colunas, referências (A1, B2)
- [ ] Fórmulas básicas: `=SOMA()`, `=MÉDIA()`

**Canivete Suíço (3h)**
- [ ] O que é um processo (abrir o gerenciador de tarefas do Windows e o `htop`/`top` dentro do WSL2, comparar os dois)
- [ ] O que é um IP e uma porta — conceito, sem prática ainda
- [ ] Já que você tem Docker instalado: rodar `docker ps` e `docker --version` só pra confirmar que está tudo ativo (sem subir contêiner ainda — isso vem no Bloco 2, mas vale já saber que funciona)

**Projeto pessoal (3h)**
- [ ] Criar o repositório `meu-primeiro-canivete` no GitHub (via terminal, com `git remote add` e `git push`, já que você já tem SSH/conta configurados)
- [ ] Nenhum código ainda — só estrutura de pastas criada via terminal

**Inglês (2h)**
- [ ] Vocabulário de comandos: *create, add, move, delete*
- [ ] Praticar ler a documentação oficial do Git (mesmo sem entender tudo)

**Alemão (1h)**
- [ ] Alfabeto, fonética, saudações (*Hallo, Guten Morgen, Tschüss*)

**Entregável da semana:** repositório no GitHub criado e já com `push` feito (não só local), primeiro commit, README com sua apresentação.

---

### SEMANA 2 — Lógica sem sintaxe + primeiras variáveis

**Núcleo espiral (9h)**
- [ ] Python: variáveis, tipos (`str`, `int`, `float`, `bool`)
- [ ] `input()` e `print()` — programa que pergunta seu nome e responde
- [ ] Bash: `mv`, `cp`, `cat`, `head` — praticar em arquivos de teste
- [ ] Git: segundo e terceiro commit, com mensagens descritivas

**Matemática / Lógica / Algoritmos (4h)**
- [ ] Comparar explicitamente: variável em matemática (x, y) vs. variável em programação — o que muda
- [ ] Desenhar no papel um fluxograma de "fazer um café" (lógica antes de qualquer código)
- [ ] Reescrever esse fluxograma como pseudocódigo (texto estruturado, ainda sem sintaxe real)

**Excel (2h)**
- [ ] Fórmula `=SE()` — sua primeira lógica condicional, antes mesmo de ver `if` em Python
- [ ] Tipos de dado no Excel (texto, número, data) e formatação de célula

**Canivete Suíço (3h)**
- [ ] Estrutura de diretórios do Linux (`/home`, `/etc`, `/var`) — o que cada um significa, de forma geral
- [ ] O que é uma variável de ambiente (conceito) — ver o `$PATH` no seu terminal

**Projeto pessoal (3h)**
- [ ] Script Python: recebe o nome do usuário via `input()` e imprime uma saudação personalizada
- [ ] Commitar esse script no repositório

**Inglês (2h)**
- [ ] Vocabulário de posse e localização (*Where is..., This is my...*)

**Alemão (1h)**
- [ ] Gênero dos substantivos (*der/die/das*) com objetos do dia a dia

**Entregável da semana:** script Python funcional e versionado + fluxograma (pode ser uma foto do papel, anexada ao repositório).

---

### SEMANA 3 — Decisões e primeiros dados

**Núcleo espiral (9h)**
- [ ] Python: `if`/`elif`/`else`, operadores de comparação
- [ ] Instalar o DB Browser for SQLite, entender o que é uma tabela
- [ ] SQL: `SELECT`, `WHERE` — suas primeiras queries

**Matemática / Lógica / Algoritmos (4h)**
- [ ] Tabelas verdade intuitivas: E, OU, NÃO — com exemplos do cotidiano, antes de qualquer código
- [ ] Exercícios simples de lógica proposicional (nível iniciante)

**Excel (2h)**
- [ ] Ordenação e filtros de dados
- [ ] Introdução a gráficos simples (coluna, pizza)

**Canivete Suíço (3h)**
- [ ] Pegar um erro real seu (de qualquer semana anterior) e dissecar a mensagem linha por linha
- [ ] Técnica de pesquisa eficaz: isolar a parte relevante do erro, buscar em inglês

**Projeto pessoal (3h)**
- [ ] Expandir o script da semana 2: agora ele valida a idade do usuário e responde com lógica condicional

**Inglês (2h)**
- [ ] Vocabulário de condição (*If..., then...*)

**Alemão (1h)**
- [ ] Apresentação de terceiros, frases simples

**Entregável da semana:** script com lógica condicional funcionando + 5 queries SQL básicas testadas.

---

### SEMANA 4 — Repetição e o primeiro script que conecta tudo

**Núcleo espiral (9h)**
- [ ] Python: `for`, `while`, iteração em listas
- [ ] Bash: redirecionamento (`>`, `>>`), pipes (`|`)
- [ ] SQL: `ORDER BY`, `LIMIT`

**Matemática / Lógica / Algoritmos (4h)**
- [ ] Noção intuitiva de eficiência (sem termo técnico ainda): por que procurar algo numa lista pequena é mais rápido que numa lista enorme
- [ ] Exercício no papel: percorrer uma lista "na mão", item por item, antes de fazer isso em código

**Excel (2h)**
- [ ] `PROCV` — primeira função de busca (compare mentalmente com um `for` procurando algo numa lista)

**Canivete Suíço (3h)**
- [ ] Permissões de arquivo (`chmod`) — o que significa 755, 644 na prática
- [ ] Diferença entre `sudo` e usuário comum

**Projeto pessoal (3h)**
- [ ] Script Python com loop que lê uma lista de itens de um CSV pequeno e imprime um resumo
- [ ] Conectar esse script a um script Bash que o chama automaticamente

**Inglês (2h)**
- [ ] Vocabulário de repetição (*Again, Until, Next, Break*)

**Alemão (1h)**
- [ ] Dias da semana, meses, números até 100

**Entregável da semana:** pipeline mínimo funcionando — Bash chama Python, que processa um CSV.

---

### SEMANA 5 — Funções, chaves SSH e consolidação técnica

**Núcleo espiral (9h)**
- [ ] Python: funções (`def`), parâmetros, `return`
- [ ] Refatorar os scripts das semanas 2-4 usando funções
- [ ] SQL: revisão de tudo visto até aqui, sem conceito novo — só prática

**Matemática / Lógica / Algoritmos (4h)**
- [ ] Implementar busca linear "na mão" em Python (percorrer lista item a item procurando um valor)
- [ ] Comparar com o operador nativo `in` do Python — por que ele existe, o que economiza

**Excel (2h)**
- [ ] Formatação condicional
- [ ] Revisão de tudo visto (`SOMA`, `MÉDIA`, `SE`, `PROCV`) aplicada num dataset pequeno seu

**Canivete Suíço (3h)**
- [ ] Gerar seu par de chaves SSH (mesmo sem usar ainda) — entender o conceito de chave pública/privada
- [ ] Boas práticas básicas de senha e segurança de conta

**Projeto pessoal (3h)**
- [ ] Refatoração: transformar os scripts soltos das semanas 1-4 num projeto único, organizado, com funções reaproveitáveis

**Inglês (2h)**
- [ ] Vocabulário de causa e efeito (*This function returns..., Because of...*)

**Alemão (1h)**
- [ ] Verbos básicos no presente (*machen, arbeiten, haben, sein*)

**Entregável da semana:** projeto refatorado com funções, sem código duplicado.

---

### SEMANA 6 — Consolidação total do Bloco 0

**Núcleo espiral (9h)**
- [ ] Nenhum conceito novo — só resolver bugs reais no seu próprio projeto
- [ ] Revisão cruzada: Python + SQL + Bash trabalhando juntos no mesmo projeto

**Matemática / Lógica / Algoritmos (4h)**
- [ ] Revisão geral com exercícios mistos (aritmética + lógica + fluxogramas)

**Excel (2h)**
- [ ] Desafio: replicar o resultado do seu script Python inteiramente no Excel, comparando os dois caminhos

**Canivete Suíço (3h)**
- [ ] Revisão de permissões, processos e chaves SSH — sem conceito novo, só fixação

**Projeto pessoal (3h)**
- [ ] Fechar a "semente" do Bloco 0: projeto funcional, documentado, com README completo

**Inglês (2h)**
- [ ] Reescrever o README inteiro em inglês

**Alemão (1h)**
- [ ] Revisão geral do vocabulário acumulado nas 5 semanas anteriores

**Marco final do Bloco 0:** um README "de verdade" — documentando decisões técnicas, não só o que o projeto faz. Esse é o primeiro artefato real do seu portfólio, e ele nasceu construído por você, sem gabarito.

---

# BLOCO 1 — ESPIRAL DE DADOS LOCAL (Meses 2-5)

Cada mês = 1 ciclo. Todo ciclo reaproveita e expande o projeto anterior.

### Mês 2 — Ciclo: Estruturas e Arquivos
- **Núcleo:** Funções com retorno, módulos Python; SQL com JOIN e GROUP BY; Bash com `grep`/`sed` básicos.
- **Canivete suíço:** Fundamentos de rede — o que é IP, DNS, porta, requisição HTTP (conceito, sem código ainda). Isso evita o "medo" de qualquer coisa relacionada a conectividade mais adiante.
- **Inglês:** vocabulário de erro e debug conversacional.
- **Projeto (semi-aberto):** você escolhe um conjunto de dados real (Kaggle, dados públicos do seu interesse) e constrói um pipeline local simples: ler → limpar → salvar em SQLite → 3 queries de negócio.

### Mês 3 — Tratamento de Exceções e APIs
- **Núcleo:** try/except em Python; subqueries em SQL; consumo de API pública com `requests`.
- **Canivete suíço:** Ler documentação técnica de verdade (não tutorial) — praticar em uma API pública real. Entender códigos de status HTTP (200, 404, 500) — isso é generalista, útil em qualquer área de TI, não só dados.
- **Projeto evolui:** adiciona uma fonte de API ao pipeline existente (agora você tem 2 fontes de dados diferentes se cruzando).

### Mês 4 — Ambientes e Automação
- **Núcleo:** venv e requirements.txt; SQLAlchemy conectando Python ao banco; `cron` para agendar.
- **Canivete suíço:** Isolamento de ambiente como conceito geral (por que isolar dependências evita "funciona na minha máquina"). Introdução a variáveis de ambiente e por que segredos (senhas, chaves) nunca vão no código.
- **Projeto evolui:** pipeline roda sozinho, agendado, sem você precisar executar manualmente.

### Mês 5 — Pandas e Consolidação do Bloco
- **Núcleo:** Pandas (limpeza, transformação, agregações); revisão de SQL com CTEs.
- **Canivete suíço:** Noções de performance geral (por que um script fica lento, o que é usar muita memória) — conceito, não otimização avançada ainda.
- **Marco do bloco:** projeto integrador **aberto** — você define sozinho um pipeline pequeno do zero, sem checklist, usando tudo que aprendeu até aqui. Só o critério de sucesso é dado: "dados brutos → dados limpos → 3 respostas de negócio documentadas".

---

# BLOCO 2 — PRODUÇÃO, WAREHOUSE E CLOUD (Meses 6-13)

Aqui entra Docker, PostgreSQL, modelagem dimensional, dbt, cloud (Azure) e Power BI — sempre revisitando Python/SQL/Bash do bloco anterior, nunca isolados.

### Mês 6 — Docker e PostgreSQL
- Docker básico, Docker Compose, migração do SQLite para PostgreSQL.
- **Canivete suíço:** conteinerização como conceito geral de infraestrutura (por que isolar aplicações, não só bancos de dados) — isso é usado em qualquer trilha de TI, não só dados.
- Alemão sobe para 3h/semana a partir daqui.

> Nota: como você já tem Docker e PostgreSQL instalados, esse mês foca menos em setup e mais direto em Docker Compose (orquestrar múltiplos serviços) e na migração de verdade do seu projeto do SQLite para o Postgres — o tempo que seria gasto instalando vira prática de modelagem e queries reais.

### Mês 7 — Modelagem Relacional Avançada
- Normalização, índices, `EXPLAIN ANALYZE`.
- **Canivete suíço:** leitura de logs de sistema (não só de aplicação) — onde ficam, como consultar.

### Mês 8-9 — Modelagem Dimensional (Star Schema)
- Tabelas fato/dimensão, surrogate keys, SCD tipo 1 e 2.
- **Projeto evolui:** o pipeline dos meses anteriores ganha uma camada dimensional de verdade.

### Mês 10 — dbt Core
- Camadas staging/intermediate/marts, testes automatizados (`unique`, `not_null`).
- **Canivete suíço:** versionamento de configuração (não só código) — por que `profiles.yml` e segredos não vão pro Git.

### Mês 11 — Power BI e DAX
- Conexão, modelo visual, medidas DAX essenciais, time intelligence básico.

### Mês 12-13 — Cloud (Azure)
- Blob Storage, Data Lake Gen2 (Bronze/Silver/Gold), Azure SQL, Azure Data Factory.
- **Canivete suíço:** conceitos de cloud que valem pra qualquer provedor (IAM/permissões, custo, região, escalabilidade) — não só "botões do Azure", mas o modelo mental por trás.
- **Marco do bloco:** projeto integrador — pipeline local migrado inteiramente para a nuvem, orquestrado, documentado em inglês.

*(SAP fica como módulo eletivo de 1-2 semanas aqui, só se você já tiver uma vaga específica mirando — não é pré-requisito de entrada.)*

---

# BLOCO 3 — QUALIDADE, GENERALISMO AVANÇADO E PORTFÓLIO (Meses 14-20)

### Mês 14 — Qualidade de Dados
- Great Expectations, logging estruturado em Python.
- **Canivete suíço:** troubleshooting sistemático — método de isolar causa raiz de um problema (não é exclusivo de dados, é postura de qualquer engenheiro).

### Mês 15 — CI/CD
- GitHub Actions, pytest, testes automatizados de dbt em pipeline.
- **Canivete suíço:** fundamentos de segurança de aplicação — por que não commitar segredos, o que é um `.gitignore` bem feito, conceito de superfície de ataque (nível introdutório, não especialista em segurança).

### Mês 16 — Arquitetura e Documentação
- C4 Model, ADRs (Architecture Decision Records) em Markdown.
- Esse mês formaliza uma habilidade que você já vem praticando desde a semana 1: documentar decisões, não só código.

### Mês 17-18 — Projeto Âncora (mercado alemão)
- Dados públicos do Destatis, pipeline completo cloud + dbt + Power BI, com contexto de negócio alemão.
- Alemão sobe para carga mais intensa aqui (5-6h/semana), porque agora você tem vocabulário técnico pra sustentar.

### Mês 19 — Preparação Técnica
- Desafios de SQL/Python (StrataScratch, HackerRank), simulações de entrevista em inglês (modelo STAR), GDPR essencial.
- **Canivete suíço:** noções de escalabilidade e trade-offs de arquitetura (perguntas comuns de entrevista que vão além de "saber a sintaxe").

### Mês 20 — Posicionamento e Candidaturas
- CV europeu, LinkedIn/XING, candidaturas ativas, networking.

---

## O QUE MUDA NA PRÁTICA (resumo)

1. **Nunca mais 1 semana = 1 tecnologia isolada.** Todo ciclo mistura Python + SQL + Bash + Docs desde o início.
2. **Generalismo de TI é currículo, não bônus.** Redes, troubleshooting, segurança básica e leitura de logs aparecem todo mês, em doses pequenas.
3. **Markdown é hábito, não módulo.** Você documenta desde a semana 1, então no mês 16 (Arquitetura/ADR) você só formaliza o que já é costume.
4. **Metade dos projetos tem escopo aberto.** Isso resolve diretamente o problema que você identificou: sentir que o trabalho é seu.
5. **Alemão cresce com sua confiança técnica**, não empurrado desde o zero absoluto ao mesmo tempo que você aprende a programar.
6. **Matemática, lógica, algoritmos e Excel entram como trilha própria, tratando você como leigo total.** Nada pressupõe conhecimento prévio — cada um começa literalmente do zero e evolui em paralelo ao resto.