# 📘 Caderno Temático: Renda Fixa para Iniciantes

> Como usar IA para aprender a investir? Este 
> repositório documenta minha jornada de estudo 
> sobre Renda Fixa usando NotebookLM, engenharia 
> de prompts e fontes oficiais como Tesouro Direto, 
> Banco Central e CVM.

---

## 🎯 Contexto e Objetivos

### Contexto
Este projeto foi desenvolvido como parte do curso
de Inteligência Artificial da DIO, com o objetivo
de explorar o uso do NotebookLM como ferramenta
de aprendizagem ativa.

O tema escolhido foi **Renda Fixa para Iniciantes**,
por ser um assunto de grande relevância para a
educação financeira dos brasileiros e por contar
com amplo material aberto e confiável disponível
para estudo.

### Objetivos de Estudo
Ao final deste caderno temático, espero ser capaz de:

- ✅ Compreender o conceito de renda fixa e seus principais produtos
- ✅ Diferenciar os tipos de investimentos: Tesouro Direto, CDB, LCI e LCA
- ✅ Entender os conceitos de liquidez, rentabilidade e risco
- ✅ Identificar qual produto é mais adequado para cada perfil e objetivo
- ✅ Utilizar a IA como ferramenta de estudo de forma crítica e eficiente

---

## 📚 Curadoria de Fontes

As fontes foram selecionadas com base em três critérios:
credibilidade institucional, linguagem acessível para
iniciantes e cobertura complementar dos conteúdos
sobre Renda Fixa.

| # | Título | Instituição | Link | Justificativa |
|---|--------|------------|------|---------------|
| 1 | Guia do Investidor | Tesouro Direto | [PDF](https://github.com/poliato2015-max/imagens/blob/main/projeto_notebooklm_investir_renda_fixa_guia_do_investidor_tesouro_direto_oficial.pdf?raw=true) | Fonte oficial com foco prático nos tipos de títulos públicos disponíveis |
| 2 | Caderno de Educação Financeira | Banco Central do Brasil | [PDF](https://github.com/poliato2015-max/imagens/blob/main/projeto_notebooklm_investir_renda_fixa_caderno_cidadania_financeira_banco_central.pdf?raw=true) | Base conceitual sobre juros, poupança e gestão financeira pessoal |
| 3 | Livro TOP - Mercado de Valores Mobiliários | CVM / ANBIMA | [PDF](https://github.com/poliato2015-max/imagens/blob/main/projeto_notebooklm_investir_renda_fixa_livro_top_mercado_de_valores_mobiliarios_brasileiro_cvm_ambima.pdf?raw=true) | Visão técnica e abrangente do sistema financeiro brasileiro |
| 4 | Vantagens e Desvantagens da Renda Fixa | B3 |[PDF](https://github.com/poliato2015-max/imagens/blob/main/projeto_notebooklm_investir_renda_fixa_vantagens_desvantagens_renda_fixa_b3.pdf?raw=true) | Comparativo direto entre os principais produtos de renda fixa do mercado |

> 💡 Os PDFs foram hospedados neste repositório
> para garantir acesso público, já que algumas
> fontes originais exigem autenticação.

---

## 🧪 Engenharia de Prompts

> Todos os prompts foram testados no NotebookLM
> com a instrução base: **"Atue como um educador
> financeiro... baseie-se apenas nas fontes
> disponíveis."**
>
> Essa escolha de persona foi deliberada — usar
> "educador financeiro" em vez de "consultor de
> investimentos" evita viés de recomendação
> profissional e mantém o foco didático do caderno.

> #### 🔍 Cicatriz — Escolha da Persona
> **Hipótese testada:** Usar "consultor de 
> investimentos" como persona.
>
> **Problema identificado:** Essa persona gera 
> recomendações específicas, assumindo papel 
> regulatório que a IA não deve exercer.
>
> **Solução adotada:** Substituída por "educador 
> financeiro", mantendo didática sem viés de 
> aconselhamento profissional.
>
> **Aprendizado:** A escolha da persona impacta 
> diretamente o escopo e a confiabilidade 
> da resposta da IA.

---

### Bloco 1 — Conceitos Fundamentais

#### 🔹 Prompt 1A
> "Atue como um educador financeiro. O que é
> renda fixa e quais são os principais produtos
> disponíveis para um investidor iniciante no
> Brasil? Use apenas as informações presentes
> nas fontes disponíveis."

**Resultado obtido:** Resposta técnica e abrangente,
cobrindo Tesouro Direto (Selic, Prefixado, IPCA+),
CDB, LCI, LCA, Poupança e Fundos DI, com explicações
sobre FGC, liquidez e tributação.

---

#### 🔹 Prompt 1B — Variação
> "Atue como um educador financeiro. Explique o
> conceito de renda fixa como se eu nunca tivesse
> investido antes. Use exemplos do cotidiano para
> facilitar o entendimento e baseie-se apenas nas
> fontes disponíveis."

**Resultado obtido:** Resposta altamente didática
com analogia do imóvel/aluguel e exemplo prático
do computador de R$1.000. Mais acessível para
públicos sem experiência financeira.

---

#### 🔍 Cicatriz — Comparativo 1A vs 1B
**Observação:** A mudança de "explique os produtos"
para "explique como se eu nunca tivesse investido"
transformou completamente o tom da resposta. O
Prompt 1B gerou analogias espontâneas e uma
narrativa mais envolvente, sem perder precisão técnica.

**Aprendizado:** Contextualizar o nível do
público-alvo no prompt é tão importante quanto
o conteúdo da pergunta em si. Para fins didáticos,
o 1B se mostrou superior.

---

### Bloco 2 — Comparativo de Produtos

#### 🔹 Prompt 2A
> "Atue como um educador financeiro. Quais são as
> diferenças entre Tesouro Selic, CDB e LCI para
> quem está começando a investir? Use apenas as
> informações presentes nas fontes disponíveis."

**Resultado obtido:** Gerou espontaneamente uma
tabela comparativa com 5 critérios (liquidez, risco,
rentabilidade, tributação e valor mínimo), além de
pontos de atenção sobre reserva de emergência,
vantagem fiscal da LCI e custos operacionais.

---

#### 🔹 Prompt 2B — Variação
> "Atue como um educador financeiro. Compare Tesouro
> Selic, CDB e LCI considerando: liquidez, risco,
> rentabilidade e valor mínimo. Apresente em formato
> de tabela e baseie-se apenas nas fontes disponíveis."

**Resultado obtido:** Gerou tabela com os mesmos
5 critérios do 2A (incluindo tributação mesmo sem
solicitação) e adicionou análise numerada mais
aprofundada, com destaque para o comparativo de
rentabilidade líquida entre LCI e CDB.

---

#### 🔍 Cicatriz — Comparativo 2A vs 2B
**Observação:** Mesmo sem solicitar formato de tabela
no 2A, a IA o gerou espontaneamente ao perceber que
o contexto era comparativo. O 2B, ao especificar os
critérios, gerou uma análise mais estruturada
e aprofundada.

**Aprendizado:** Especificar critérios no prompt não
apenas organiza a resposta — eleva a qualidade da
análise. O 2B trouxe o insight sobre rentabilidade
líquida LCI vs CDB, ausente no 2A, demonstrando que
prompts mais detalhados extraem respostas mais ricas.

---

### Bloco 3 — Aplicação Prática

#### 🔹 Prompt 3A
> "Atue como um educador financeiro. Tenho R$1.000
> para investir pela primeira vez e quero segurança.
> Com base nas fontes disponíveis, quais produtos de
> renda fixa seriam mais adequados para este perfil
> e por quê?"

**Resultado obtido:** Indicou Tesouro Selic, CDB com
liquidez diária e Poupança como opções para perfil
conservador. Trouxe seção inédita explicando por que
Tesouro Prefixado, IPCA+ e LCI foram descartados para
este perfil — demonstrando raciocínio crítico da IA.

---

#### 🔹 Prompt 3B — Variação
> "Atue como um educador financeiro. Qual a diferença
> entre investir para reserva de emergência versus
> investir para um objetivo de longo prazo em renda
> fixa? Quais produtos são mais indicados para cada
> situação? Baseie-se apenas nas fontes disponíveis."

**Resultado obtido:** Entregou o conteúdo mais completo
do caderno — distinguiu claramente os dois objetivos,
indicou produtos específicos para cada caso e gerou
tabela comparativa espontânea. Trouxe alerta crítico
sobre riscos do resgate antecipado em títulos
de longo prazo.

---

#### 🔍 Cicatriz — Comparativo 3A vs 3B
**Observação:** O 3A respondeu bem para um cenário
específico (R$1.000, perfil conservador). O 3B elevou
o nível ao abordar a estratégia por objetivo, gerando
o conteúdo mais rico do caderno.

**Aprendizado:** Prompts baseados em estratégia e
objetivo extraem respostas mais profundas do que
prompts baseados em cenário e valor. Para fins
educacionais, contextualizar o "para quê" do
investimento é mais poderoso do que contextualizar
o "quanto".

---

### Bloco 4 — Riscos e Cuidados

#### 🔹 Prompt 4A
> "Atue como um educador financeiro. Quais são os
> principais riscos da renda fixa que um investidor
> iniciante precisa conhecer antes de aplicar seu
> dinheiro? Baseie-se apenas nas fontes disponíveis."

**Resultado obtido:** Estruturou os 4 pilares de risco
da renda fixa: Crédito, Mercado, Liquidez e
Concentração. Destaque para o conceito de "marcação
a mercado" e o alerta sobre reserva de emergência
em títulos sem liquidez diária.

---

#### 🔹 Prompt 4B — Variação
> "Atue como um educador financeiro. O que é o FGC
> e como ele protege o investidor de renda fixa?
> Quais produtos são cobertos por ele e quais não
> são? Baseie-se apenas nas fontes disponíveis."

**Resultado obtido:** Explicou o FGC de forma
completa, listou produtos cobertos (Poupança, CDB,
LCI, LCA) e não cobertos (Tesouro Direto e Fundos),
com destaque para o conceito inédito de segregação
patrimonial dos fundos de investimento.

---

#### 🔍 Cicatriz — Comparativo 4A vs 4B
**Observação:** O 4A mapeou o panorama completo de
riscos. O 4B aprofundou especificamente o Risco de
Crédito, trazendo informação ausente no 4A: a
segregação patrimonial dos fundos como mecanismo
de proteção alternativo ao FGC.

**Aprendizado:** Prompts focados em um único conceito
geram mais profundidade do que prompts abrangentes.
A estratégia ideal é usar um prompt panorâmico (4A)
para mapear o tema e prompts específicos (4B) para
aprofundar os pontos críticos.

---

### Bloco 5 — Descoberta: Produtos Avançados

#### 🔹 Prompt 5A
> "Atue como um educador financeiro. O que são
> LC (Letra de Câmbio), LF (Letra Financeira),
> Debêntures, CRI e CRA como produtos de renda
> fixa? Baseie-se apenas nas fontes disponíveis."

**Resultado obtido:** O NotebookLM detalhou todos
os 5 produtos com precisão:
- **LC:** Emitida por financeiras. Coberta pelo FGC.
- **LF:** "Debênture dos bancos", valor mínimo de
  R$150.000, prazo mínimo de 24 meses, sem
  liquidez antecipada.
- **Debêntures:** Emitidas por empresas S/A.
  Investidor vira credor, não sócio. Podem ser
  simples ou conversíveis em ações.
- **CRI:** Lastreado em créditos imobiliários.
  Sem cobertura FGC.
- **CRA:** Lastreado em recebíveis do agronegócio.
  Sem cobertura FGC.

**Tabela de cobertura FGC:**

| Produto | Cobertura FGC |
|---------|--------------|
| CDB | ✅ Até R$250 mil |
| LCI / LCA | ✅ Até R$250 mil |
| LC | ✅ Até R$250 mil |
| Poupança | ✅ Até R$250 mil |
| LF | ❌ Não coberto |
| Debêntures | ❌ Não coberto |
| CRI / CRA | ❌ Não coberto |
| Tesouro Direto | ❌ Garantia Soberana |

---

#### 🔍 Cicatriz — Escopo das Fontes vs. Mercado Real
**Contexto:** Ao acessar uma corretora, identifiquei
produtos não abordados nos prompts anteriores:
LC, LF, Debêntures, CRI e CRA.

**Hipótese inicial:** Imaginei que as fontes não
cobriam esses produtos, já que não apareceram
espontaneamente nas respostas dos Blocos 1 a 4.

**O que gerou a hipótese:** O prompt foi corrigido
após perceber que a versão inicial havia omitido
LC e LF sem justificativa — demonstrando que a
revisão crítica dos próprios prompts é parte
essencial da engenharia de prompts.

**Resultado:** O NotebookLM respondeu com riqueza
de detalhes — todos os produtos estavam nas fontes.

**Causa real identificada:** Os prompts anteriores
foram formulados de forma genérica, levando a IA
a priorizar produtos mais populares. Os avançados
existiam nas fontes mas não foram evocados por
falta de pergunta específica.

**Aprendizado:** A IA responde ao que é perguntado,
não entrega tudo espontaneamente. Prompts genéricos
revelam o panorama geral; prompts específicos
revelam profundidade. A revisão crítica dos próprios
prompts é tão importante quanto a elaboração
inicial deles.

---

## 📖 Miniguia de Estudo — Renda Fixa para Iniciantes

> Este miniguia foi construído com base nas respostas
> geradas pelo NotebookLM a partir das 4 fontes
> curadas. Serve como referência rápida para revisão
> e aprendizado contínuo.

---

### 📄 Parte 1 — Resumos Estruturados

#### 1.1 O que é Renda Fixa?
Renda fixa é uma modalidade de investimento em que
o investidor conhece, no momento da aplicação, qual
será a regra de rentabilidade. É como "alugar" seu
dinheiro para uma instituição (governo ou banco) por
um período, recebendo juros em troca.

Os rendimentos podem ser:
- **Prefixados:** Taxa definida no início.
- **Pós-fixados:** Atrelados a um indexador (Selic
  ou IPCA).
- **Híbridos:** Taxa fixa + indexador (ex: IPCA+
  5% ao ano).

---

#### 1.2 Principais Produtos para Iniciantes

| Produto | Emissor | Risco | Liquidez | IR | FGC |
|---------|---------|-------|----------|----|-----|
| Tesouro Selic | Governo | Soberano | Diária | Sim | ❌ |
| Tesouro IPCA+ | Governo | Soberano | Vencimento | Sim | ❌ |
| Tesouro Prefixado | Governo | Soberano | Vencimento | Sim | ❌ |
| CDB | Banco | Bancário | Diária/Venc. | Sim | ✅ |
| LCI | Banco | Bancário | Vencimento | Isento | ✅ |
| LCA | Banco | Bancário | Vencimento | Isento | ✅ |
| LC | Financeira | Bancário | Vencimento | Sim | ✅ |
| Poupança | Banco | Bancário | Diária | Isento | ✅ |

---

#### 1.3 Produtos Avançados

| Produto | Emissor | IR | FGC |
|---------|---------|-----|-----|
| LF | Banco | Sim | ❌ |
| Debêntures | Empresa S/A | Sim* | ❌ |
| CRI | Securitizadora | Isento | ❌ |
| CRA | Securitizadora | Isento | ❌ |

> *Debêntures Incentivadas são isentas de IR.

---

#### 1.4 Qual Produto Escolher?

**Para Reserva de Emergência:**
- ✅ Tesouro Selic — melhor opção
- ✅ CDB com liquidez diária
- ✅ Poupança (menor rentabilidade)

**Para Objetivos de Longo Prazo:**
- ✅ Tesouro IPCA+ — proteção do poder de compra
- ✅ Tesouro Prefixado — previsibilidade total
- ✅ LCI / LCA — isenção de IR favorece
  rentabilidade líquida

---

#### 1.5 Os 4 Riscos que Todo Iniciante Deve Conhecer

**1. Risco de Crédito ("Calote")**
Risco de o emissor não pagar o combinado.
Mitigação: Tesouro Direto (risco soberano) ou
FGC para produtos bancários (até R$250 mil).

**2. Risco de Mercado (Oscilação)**
Títulos Prefixado e IPCA+ podem desvalorizar se
resgatados antes do vencimento.
Mitigação: Só invista o que não precisará antes
do vencimento.

**3. Risco de Liquidez (Resgate)**
Alguns produtos só permitem resgate no vencimento.
Mitigação: Nunca coloque a reserva de emergência
em títulos sem liquidez diária.

**4. Risco de Concentração**
Colocar tudo em um único emissor amplifica perdas.
Mitigação: Diversifique entre emissores, respeitando
o limite do FGC de R$250 mil por instituição.

---

### 📖 Parte 2 — Glossário de Conceitos

| Termo | Definição |
|-------|-----------|
| **Renda Fixa** | Investimento com regra de rentabilidade conhecida no momento da aplicação |
| **Prefixado** | Taxa de juros definida no início do investimento |
| **Pós-fixado** | Rentabilidade atrelada a um indexador econômico |
| **Taxa Selic** | Taxa básica de juros da economia brasileira |
| **IPCA** | Índice oficial de inflação do Brasil |
| **CDI** | Taxa de referência do mercado interbancário |
| **Liquidez** | Facilidade de transformar o investimento em dinheiro |
| **Vencimento** | Data em que o emissor devolve o valor investido com juros |
| **FGC** | Fundo Garantidor de Créditos — protege até R$250 mil por CPF/instituição |
| **Risco Soberano** | Risco do Governo Federal — o mais baixo do mercado |
| **Marcação a Mercado** | Atualização diária do preço de um título conforme o mercado |
| **Securitização** | Transformação de dívidas a receber em títulos negociáveis |
| **Debênture** | Título de dívida emitido por empresas S/A |
| **Segregação Patrimonial** | Separação entre patrimônio do fundo e do banco administrador |
| **Suitability** | Teste de perfil de investidor realizado pela corretora |
| **Reserva de Emergência** | Valor para cobrir imprevistos — idealmente 3 a 6 meses de gastos |
| **Juros Compostos** | Juros calculados sobre o valor acumulado |
| **Tabela Regressiva IR** | Alíquota do IR que diminui conforme o tempo de aplicação |

---

### 🔄 Parte 3 — Prompts Reutilizáveis para Revisão

#### 🔹 Revisão Geral
```
Atue como um educador financeiro e faça um
resumo dos principais conceitos de renda fixa
abordados nas fontes, adequado para uma
revisão rápida de 5 minutos.
```

---

#### 🔹 Revisão por Produto
```
Atue como um educador financeiro. Explique
detalhadamente como funciona o [PRODUTO],
seus riscos, vantagens e para qual perfil
de investidor é mais indicado. Baseie-se
apenas nas fontes disponíveis.
```

---

#### 🔹 Simulação de Cenário
```
Atue como um educador financeiro. Tenho
[VALOR] para investir com objetivo de
[OBJETIVO] em um prazo de [PRAZO]. Quais
produtos de renda fixa são mais adequados
para este cenário? Baseie-se apenas nas
fontes disponíveis.
```

---

#### 🔹 Revisão de Riscos
```
Atue como um educador financeiro. Explique
o [RISCO] na renda fixa com um exemplo
prático do cotidiano. Baseie-se apenas
nas fontes disponíveis.
```

---

#### 🔹 Comparativo Personalizado
```
Atue como um educador financeiro. Compare
[PRODUTO A] e [PRODUTO B] considerando
liquidez, risco, rentabilidade e tributação.
Indique qual é mais adequado para um
investidor [PERFIL]. Baseie-se apenas
nas fontes disponíveis.
```

---

#### 🔹 Aprofundamento de Conceito
```
Atue como um educador financeiro. Explique
o conceito de [TERMO] com linguagem simples
e um exemplo prático. Baseie-se apenas
nas fontes disponíveis.
```

## 🏁 Conclusão

Este caderno temático demonstrou como a IA pode
ser utilizada como ferramenta de aprendizagem
ativa, aliando pensamento crítico, curadoria de
fontes e engenharia de prompts para construir
conhecimento sólido sobre Renda Fixa.

Os principais aprendizados sobre o uso da IA
como ferramenta de estudo foram:

- 🎯 A escolha da persona impacta diretamente
  o tom e a qualidade das respostas
- 🎯 Prompts específicos revelam profundidade
  que prompts genéricos deixam ocultos
- 🎯 Contextualizar o público-alvo melhora
  a didática das respostas
- 🎯 A IA responde ao que é perguntado —
  explorar ativamente é responsabilidade
  do estudante
- 🎯 Revisar criticamente os próprios prompts
  é parte essencial do processo

---
*Projeto desenvolvido para o curso de 
Inteligência Artificial da DIO* 🚀
