# Treinando uma IA de Aprendizagem: Explore o Poder do NotebookLM

## Contexto e Objetivo

Atualmente estou finalizando o primeiro curso do Bootcamp Bradesco - GenAI, Dados & Cyber, que aborda os fundamentos da IA Generativa. Assim, a fim de entender na prática o que aprendi, criei um caderno temático no assistente de IA da Google NotebookLM.

Com base nisso, meu principal objetivo para este projeto é compreender a Engenharia de Prompt sob as ópticas das áreas da IA, Ciência de Dados, Cibersegurança, Administração (em geral) e Direito Digital e Proteção de Dados de modo que eu possa aplicá-la em contextos acadêmicos e profissionais, restringindo o estudo a fontes técnicas específicas, tais como revistas acadêmicas e livros.

---

## Curadoria de fontes

- https://jrnm.ojsbr.com/juridica/article/view/6012/5518
- https://aclanthology.org/2024.legal-1.3.pdf
- https://www.cambridge.org/core/journals/cambridge-forum-on-ai-law-and-governance/article/reimagining-corporate-governance-in-the-ai-era-law-legitimacy-and-algorithmic-power/FAC9AF8DC700C6F143242842A6B0F702
- https://arxiv.org/pdf/2402.07927

---

# Engenharia de Prompt e "Cicatrizes"

## Prompt-0: *Buscador de links dos assuntos correlatados*

### Framework do Prompt

- Persona
- Contexto e objetivo
- Tarefa
- Restrições de pesquisa

### Prompt

> "Atue como um profissionais das áreas da IA, Ciência de Dados, Cibersegurança, Administração (em geral) e Direito Digital e Proteção de Dados. Estou realizando um pesquisa sobre Engenharia de Prompt sob as ópticas das áreas que evidenciei anteriormente neste prompt de modo que eu possa aplicá-la em contextos coorporativos e acadêmicos (dentro da área da Ciência da Computação). Pesquise os principais links que atinjam meu objetivo com esse estudo. Esses links devem se restringir a revistas acadêmicas e livros renomados"

### Anotação

Esqueci de especificar a quantidade de links, porém a IA sugeriu uma boa base para o começo. Embora a IA tenha compreendido minha situação geográfica, também esqueci de restringir as pesquisas das áreas de Direito Digital e Proteção de Dados ao contexto jurídico brasileiro.

---

## Prompt-1: *Resumo geral*

### Framework

- Persona
- Contexto
- Tarefa
- Formato de saída

### Prompt

> "Atue como profissionais das áreas da IA, Ciência de Dados, Cibersegurança, Administração (em geral) e Direito Digital e Proteção de Dados, porém, hegemonicamente, como um estudante do segundo semestre de Ciência da Computação. Compreendendo o cenário atual da IA nas empresas, faça um resumo sobre todos os assuntos abordados em suas fontes de modo que um estudante de ciência da computação e entusiasta em tecnologia, que almeja iniciar sua trajetória como profissional da área, possa tirar proveito. Sobre o formato de saída, produza parágrafos de explicação que contenham 300 caracteres e tópicos para citar exemplos"

### Resposta

A LGPD no Brasil estabelece o equilíbrio entre a inovação da IA e a proteção dos direitos fundamentais dos cidadãos.

Para nós, futuros profissionais, é vital entender o impacto das decisões automatizadas e os desafios de propriedade intelectual nos dados para treinamento.

Exemplos:

- Direito do titular à explicação sobre como um algoritmo tomou uma decisão.
- Conflitos entre direitos autorais de criadores e o uso de dados para treinar modelos.
- A cibersegurança agora enfrenta o risco de injeção de prompt, onde instruções maliciosas manipulam o comportamento do modelo.
- Sistemas robustos utilizam pipelines multiagentes para filtrar ataques adversariais, garantindo que a saída final seja segura e auditável para as empresas.

Exemplos:

- Uso de um "Agente Guarda" que verifica violações de política antes de exibir a resposta.
- Ataques que utilizam codificação em Base64 para ocultar comandos maliciosos dos filtros.
- Na prática de programação, a Engenharia de Prompts usa técnicas como Chain-of-Thought (CoT) para resolver problemas lógicos complexos.
- Estratégias estruturadas ajudam LLMs a gerar código Python mais eficiente, reduzindo alucinações e melhorando a qualidade do software produzido.

Exemplos:

- Estratégia "Least-to-Most" para decompor um problema grande em subproblemas menores.
- Uso de pseudocódigo e validação lógica intermediária para aumentar o acerto em concursos.
- As empresas demandam uma Governança Corporativa que gerencie riscos como o viés de automação e a opacidade algorítmica.
- A documentação rigorosa de prompts e versões de modelos é indispensável para garantir a transparência e a responsabilidade ética nas decisões de negócio.

Exemplos:

- Adoção de comitês especializados (AITO) para supervisionar o uso ético de tecnologias.
- Necessidade de registrar a versão exata do modelo (ex: GPT-4 0125) para fins de auditoria.
- Estudar IA exige entender técnicas como RAG e otimização por prompts, que conectam modelos a dados externos e melhoram o desempenho em tarefas específicas.
- Como alunos de computação, devemos focar na automação de fluxos de trabalho e na criação de sistemas que sejam explicáveis.

Exemplos:

- Uso de Retrieval Augmented Generation (RAG) para atualizar o conhecimento do modelo.
- Implementação de "IA Explicável" (XAI) para fornecer justificativas compreensíveis ao usuário.

### Anotações

Consegui ter uma base rasa, mas sólida, do conteúdo. Porém, eles estão muito distintos. Vou tentar sintetizá-los num prompt adicional.

---

## Prompt adicional (Prompt-1.5)

### Prompt

> "Produza uma síntese de todos esses assuntos abordados em 200 palavras"

### Resposta

A convergência entre Inteligência Artificial (IA) e a LGPD no Brasil estabelece desafios críticos de privacidade, exigindo transparência algorítmica e o direito à explicação em decisões automatizadas.

Esse cenário jurídico abrange também a propriedade intelectual, questionando a legalidade do uso de dados protegidos no treinamento e na geração de conteúdos por modelos de linguagem.

Paralelamente, a governança corporativa enfrenta o dilema entre inovação e responsabilidade, demandando que diretores supervisionem riscos de opacidade e o "viés de automação" para manter a legitimidade institucional.

No campo técnico, a cibersegurança evolui com pipelines de defesa multiagentes e frameworks adversariais projetados para detectar e mitigar ataques de injeção de prompt e tentativas de jailbreaking.

A performance desses sistemas é otimizada pela Engenharia de Prompts, utilizando técnicas como Chain-of-Thought (CoT), RAG e Tree-of-Thoughts para aprimorar o raciocínio lógico e reduzir alucinações.

Na educação, essas estratégias potencializam o ensino de programação Python e a engenharia de atributos.

Contudo, a pesquisa na área exige novas diretrizes de transparência e reporte para garantir a reprodutibilidade científica e a conformidade administrativa.

Em síntese, a maturidade da IA depende de uma integração interdisciplinar entre segurança, ética e rigor jurídico.

### Anotação

Embora ele não tenha unido tudo num único tópico, ele reconheceu suas principais distinções por meio de categorias: Gestão e Direito e Campo Técnico.

---

## Prompt-1.9

### Prompt

> "Elenque os principais tópicos a serem estudados e quais as recomendações dos autores dos artigos"

### Resposta

### 1. Regulação Jurídica e Privacidade (Foco em LGPD)

**Tópicos de estudo:**

- Intersecção entre a LGPD e sistemas de IA.
- Direito à explicação em decisões automatizadas.
- Problema da "caixa-preta" algorítmica.
- Autodeterminação informativa no Big Data.

**Recomendações dos autores:**

- Realizar Avaliações de Impacto à Proteção de Dados (AIPD) específicas para IA.
- Adotar os princípios de privacy by design e security by design.
- Investir na capacitação técnica e jurídica de Encarregados de Dados (DPOs).

### 2. Cibersegurança e Segurança de Modelos

**Tópicos de estudo:**

- Ataques de injeção de prompt.
- Jailbreaking.
- Vulnerabilidades em LLMs.
- Frameworks de avaliação de segurança.

**Recomendações dos autores:**

- Implementar pipelines de defesa multiagentes.
- Utilizar avaliações quantitativas de segurança.
- Manter monitoramento contínuo e logs de interação.

### 3. Engenharia de Prompts e Raciocínio Lógico

**Tópicos de estudo:**

- Chain-of-Thought (CoT).
- Retrieval Augmented Generation (RAG).
- Tree-of-Thoughts.
- Self-Refine.

**Recomendações dos autores:**

- Utilizar prompts conversacionais multi-etapas.
- Adaptar estratégias de prompt ao nível de dificuldade do problema.
- Integrar verificadores simbólicos para reduzir erros.

### 4. Governança Corporativa e Ética

**Tópicos de estudo:**

- Deveres fiduciários dos diretores frente à IA.
- Paradoxo da transparência.
- Viés de automação.

**Recomendações dos autores:**

- Criar Comitês de Supervisão de IA e Tecnologia.
- Evitar delegação cega a sistemas automatizados.
- Reportar o uso de IA em relatórios corporativos.

### 5. Documentação e Rigor em Pesquisa/Desenvolvimento

**Tópicos de estudo:**

- Reprodutibilidade de experimentos com LLMs.
- Documentação de prompts.
- Direitos de propriedade intelectual.

**Recomendações dos autores:**

- Registrar versão exata do modelo.
- Documentar parâmetros utilizados.
- Disponibilizar prompts completos ou templates estruturados.

---

## Conclusão

Resumidamente, compreendi as principais discussões e aplicabilidades da Engenharia de Prompt no setor de Desenvolvimento de Sistemas, integrando múltiplas áreas de conhecimento. Dessa forma, são relevantes para o meu desenvolvimento como um profissional ético, responsável e atualizado.

---

## Prompt-2: *Aprofundamento para trabalhar como um Jovem Aprendiz na vaga de Auxiliar de Administrativo de TI (Suporte Técnico)*

### Framework

- Contexto
- Persona
- Tarefa
- Formato
- Exemplo

### Prompt

> "Agora, traga a aplicabilidade desses estudos para um emprego de Jovem Aprendiz para a vaga de Auxiliar de Administrativo de TI (Suporte Técnico). Atue como um profissional de Administrativo de TI. Com base nas fontes, responda como essas discussões jurídicas, pedagógicas e técnicas ajudam no desenvolvimento de um bom profissional dessa área. Pensando que trata-se de um Jovem Aprendiz que acabou de ingressar nesse setor. Em relação ao formato, redija um resumo de aproximadamente 1500 caracteres e, logo após, escreva suas aplicabilidades para cada função que o auxiliar terá que fazer. Em relação às funções do auxiliar, escreva da seguinte forma: função: descrição aplicabilidade."

### Funções

- Apoio às rotinas administrativas do setor de TI.
- Controle e organização de equipamentos e documentos.
- Lançamento e conferência de informações.
- Atendimento de chamados e suporte básico aos usuários.
- Acompanhamento de solicitações internas.

### Resposta

Para um Jovem Aprendiz na TI, a integração desses estudos transforma o suporte técnico de uma função meramente operacional em um papel estratégico.

O entendimento da LGPD não é apenas uma obrigação jurídica; é uma diretriz de segurança essencial para o manejo de dados sensíveis e equipamentos da empresa.

Ao dominar a Engenharia de Prompts, como as técnicas Chain-of-Thought e Self-Refine, o auxiliar ganha agilidade para solucionar chamados complexos e gerar scripts em Python mais precisos para automatizar tarefas repetitivas.

Além disso, a ciência sobre ataques de injeção de prompt e vulnerabilidades em modelos de linguagem alerta o profissional iniciante para a necessidade crítica de filtrar informações antes de alimentá-las em sistemas corporativos.

O conhecimento pedagógico extraído dos estudos sobre LLMs ensina a decompor problemas técnicos grandes em etapas menores e lógicas, facilitando o acompanhamento de solicitações.

A governança corporativa reforça que a tecnologia deve estar sob supervisão, combatendo o viés de automação e priorizando a transparência.

Profissionalizar-se exige rigor documental, registrando versões e parâmetros de ferramentas utilizadas, garantindo auditabilidade e conformidade.

---

### Aplicabilidades

**Apoio às rotinas administrativas do setor de TI**

Aplicabilidade: Utilizar diretrizes de documentação de ferramentas, registrando versões e configurações para garantir processos transparentes e auditáveis.

**Controle e organização de equipamentos e documentos**

Aplicabilidade: Aplicar princípios de security by design e LGPD para garantir proteção de dados durante manutenção, descarte e armazenamento.

**Lançamento e conferência de informações**

Aplicabilidade: Utilizar técnicas de verificação lógica e refinamento iterativo para reduzir erros em dados inseridos.

**Atendimento de chamados e suporte básico aos usuários**

Aplicabilidade: Aplicar raciocínio estruturado para decompor problemas e utilizar bases de conhecimento internas para encontrar soluções.

**Acompanhamento de solicitações internas**

Aplicabilidade: Evitar dependência excessiva de automações, mantendo análise humana para garantir decisões transparentes.

---

## Prompt-3: *Verificação de entendimento*

### Framework

- Persona
- Tarefa
- Formato

### Prompt

> "Atue como um tutor universitário. Responda a seguinte pergunta: Eu posso resumir que as aplicabilidades da Engenharia de Prompt nessa profissão, em suma, atuam como um 'agilizador' dos processos de cada tarefa? Seja objetivo, transparente e conciso em sua resposta."

### Resposta

Sim, mas com ressalvas fundamentais.

Embora a Engenharia de Prompt atue como um agilizador, defini-la apenas como tal simplifica sua função técnica e estratégica.

1. **Aceleração via decomposição:** permite dividir tarefas complexas em etapas menores e lógicas.

2. **Extensão de capacidade:** amplia a utilização dos modelos de linguagem em diferentes fluxos de trabalho.

3. **Interface de controle e precisão:** melhora a qualidade e segurança das respostas geradas.

4. **Redução de riscos:** evita problemas relacionados a alucinações, viés de automação e ataques de segurança.

### Conclusão

Para um Auxiliar Administrativo de TI, a Engenharia de Prompt funciona como um catalisador de produtividade, mas sua aplicação real está relacionada ao aumento da precisão, controle e conformidade dos processos.

Agilidade sem documentação, validação e governança pode gerar resultados inconsistentes.

# Miniguia de Estudo

## Resumo Estruturado

Este caderno de estudos reúne estudos sobre três áreas fundamentais da Inteligência Artificial.

A primeira aborda a relação entre IA, LGPD e governança corporativa, destacando princípios como transparência algorítmica, direito à explicação, supervisão humana em decisões automatizadas, atuação de comitês especializados (AITO), mitigação do viés de automação e desafios relacionados à propriedade intelectual dos dados de treinamento.

A segunda explora a aplicação da IA em cibersegurança, com foco na prevenção de ataques de prompt injection por meio de pipelines multiagentes, nos quais agentes coordenadores e guardas filtram entradas, validam respostas e aumentam a robustez contra técnicas de ofuscação e jailbreaking.

Por fim, apresenta conceitos de Engenharia de Prompt, enfatizando técnicas como Chain-of-Thought (CoT) e Retrieval-Augmented Generation (RAG) para aprimorar o raciocínio dos modelos, além da importância de documentar versões dos modelos e prompts para garantir a reprodutibilidade de experimentos científicos.

## Glossário de conceitos aprendidos

### Eixo Ético e Jurídico

- **Viés de Automação (Automation Bias):** Tendência cognitiva de confiar excessivamente em sugestões geradas por sistemas automatizados, negligenciando o julgamento humano ou informações contraditórias.

- **IA Explicável (XAI):** Campo da IA focado no desenvolvimento de modelos que fornecem justificativas transparentes para seus resultados, saindo do modelo de "caixa-preta".

- **Autodeterminação Informativa:** Direito do indivíduo de controlar o uso de seus dados pessoais e entender como eles influenciam perfis algorítmicos.

### Eixo de Cibersegurança

- **Injeção de Prompt (Prompt Injection):** Ataque onde instruções maliciosas são inseridas no input do usuário para sobrescrever as diretrizes do sistema e manipular o comportamento do modelo.

- **Pipeline de Defesa Multiagente:** Arquitetura de segurança que utiliza diferentes IAs coordenadas para filtrar ataques e validar respostas em tempo real.

- **Jailbreaking:** Tentativas sofisticadas de burlar os filtros de segurança e protocolos éticos de um modelo de linguagem para forçar saídas proibidas.

- **Ofuscação:** Técnica de esconder comandos maliciosos usando codificação para evitar detecção por filtros de segurança simples.

### Eixo Técnico e Engenharia de Prompt

- **Chain-of-Thought (CoT):** Técnica que induz o modelo a realizar um raciocínio passo a passo, melhorando a precisão em tarefas lógicas e matemáticas.

- **RAG (Retrieval Augmented Generation):** Método que conecta a IA a bases de dados externas em tempo real, reduzindo alucinações e fornecendo informações atualizadas.

## Conjunto de Prompts Reutilizáveis

### Prompt-0: *Buscador de links dos assuntos correlatados*

> Atue como um profissionais das áreas da IA, Ciência de Dados, Cibersegurança, Administração (em geral) e Direito Digital e Proteção de Dados. Estou realizando um pesquisa sobre Engenharia de Prompt sob as ópticas das áreas que evidenciei anteriormente neste prompt de modo que eu possa aplicá-la em contextos coorporativos e acadêmicos (dentro da área da Ciência da Computação). Pesquise os principais links que atinjam meu objetivo com esse estudo. Esses links devem se restringir a revistas acadêmicas e livros renomados.

### Prompt-1: *Resumo geral*

> Atue como profissionais das áreas da IA, Ciência de Dados, Cibersegurança, Administração (em geral) e Direito Digital e Proteção de Dados, porém, hegemonicamente, como um estudante do segundo semestre de Ciência da Computação. Compreendendo o cenário atual da IA nas empresas, faça um resumo sobre todos os assuntos abordados em suas fontes de modo que um estudante de ciência da computação e entusiasta em tecnologia, que almeja iniciar sua trajetória como profissional da área, possa tirar proveito.

### Prompt-2: *Aprofundamento profissional*

> Agora, traga a aplicabilidade desses estudos para um emprego de Jovem Aprendiz para a vaga de Auxiliar de Administrativo de TI (Suporte Técnico). Atue como um profissional de Administrativo de TI. Com base nas fontes, responda como essas discussões jurídicas, pedagógicas e técnicas ajudam no desenvolvimento de um bom profissional dessa área.

### Prompt-3: *Verificação de entendimento*

> Atue como um tutor universitário. Responda a seguinte pergunta: "[pergunta]"
