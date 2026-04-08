# 📘 Caderno Temático: Renda Fixa para Iniciantes

> Como usar IA para aprender a investir?
> Este repositório documenta minha jornada de estudo sobre Renda Fixa utilizando NotebookLM, engenharia de prompts e fontes oficiais como Tesouro Direto, Banco Central e CVM.


## 🎯 Contexto e Objetivos

### Contexto
Este projeto foi desenvolvido como parte do curso de 
Inteligência Artificial da DIO, com o objetivo de explorar 
o uso do NotebookLM como ferramenta de aprendizagem ativa. 

O tema escolhido foi **Renda Fixa para Iniciantes**, por ser 
um assunto de grande relevância para a educação financeira 
dos brasileiros e por contar com amplo material aberto e 
confiável disponível para estudo.

### Objetivos de Estudo
Ao final deste caderno temático, espero ser capaz de:

- ✅ Compreender o conceito de renda fixa e seus principais produtos
- ✅ Diferenciar os tipos de investimentos: Tesouro Direto, CDB, LCI e LCA
- ✅ Entender os conceitos de liquidez, rentabilidade e risco
- ✅ Identificar qual produto é mais adequado para cada perfil e objetivo
- ✅ Utilizar a IA como ferramenta de estudo de forma crítica e eficiente


## 📚 Curadoria de Fontes

As fontes foram selecionadas com base em três critérios:
credibilidade institucional, linguagem acessível para iniciantes
e cobertura complementar dos conteúdos sobre Renda Fixa.

| # | Título | Instituição | Link | Justificativa |
|---|--------|------------|------|---------------|
| 1 | Guia do Investidor | Tesouro Direto | [PDF](https://github.com/poliato2015-max/imagens/blob/main/projeto_notebooklm_investir_renda_fixa_guia_do_investidor_tesouro_direto_oficial.pdf?raw=true) | Fonte oficial com foco prático nos tipos de títulos públicos disponíveis |
| 2 | Caderno de Educação Financeira | Banco Central do Brasil | [PDF](https://github.com/poliato2015-max/imagens/blob/main/projeto_notebooklm_investir_renda_fixa_caderno_cidadania_financeira_banco_central.pdf?raw=true) | Base conceitual sobre juros, poupança e gestão financeira pessoal |
| 3 | Livro TOP - Mercado de Valores Mobiliários | CVM / ANBIMA | [PDF](https://github.com/poliato2015-max/imagens/blob/main/projeto_notebooklm_investir_renda_fixa_livro_top_mercado_de_valores_mobiliarios_brasileiro_cvm_ambima.pdf?raw=true) | Visão técnica e abrangente do sistema financeiro brasileiro |
| 4 | Vantagens e Desvantagens da Renda Fixa | B3 |[PDF](https://github.com/poliato2015-max/imagens/blob/main/projeto_notebooklm_investir_renda_fixa_vantagens_desvantagens_renda_fixa_b3.pdf?raw=true) | Comparativo direto entre os principais produtos de renda fixa do mercado |

> Observação: Os PDFs foram hospedados no GitHub para garantir acesso público, já que algumas fontes originais exigem autenticação.



## 🧪 Engenharia de Prompts

### Bloco 1 - Conceitos Fundamentais

#### 🔹 Prompt 1A
> "Atue como um educador financeiro. O que é 
> renda fixa e quais são os principais produtos 
> disponíveis para um investidor iniciante no 
> Brasil? Use apenas as informações presentes 
> nas fontes disponíveis."

**Resultado:** Resposta técnica e abrangente, 
cobrindo Tesouro Direto (Selic, Prefixado, IPCA+), 
CDB, LCI, LCA, Poupança e Fundos DI, com 
explicações sobre FGC, liquidez e tributação.

#### 🔹 Prompt 1B — Variação
> "Atue como um educador financeiro. Explique 
> o conceito de renda fixa como se eu nunca 
> tivesse investido antes. Use exemplos do 
> cotidiano para facilitar o entendimento e 
> baseie-se apenas nas fontes disponíveis."

**Resultado:** Resposta altamente didática com 
analogia do imóvel/aluguel e exemplo prático 
do computador de R$1.000. Mais acessível para 
públicos sem experiência financeira.

---

#### 🔍 Cicatriz - Comparativo 1A vs 1B

**Observação:** A mudança de "explique os 
produtos" para "explique como se eu nunca 
tivesse investido" transformou completamente 
o tom da resposta. O Prompt 1B gerou analogias 
espontâneas e uma narrativa mais envolvente, 
sem perder precisão técnica.

**Aprendizado:** Contextualizar o nível do 
público-alvo no prompt é tão importante quanto 
o conteúdo da pergunta em si. Para fins 
didáticos, o 1B se mostrou superior.

---

### Bloco 2 - Comparativo de Produtos

#### 🔹 Prompt 2A
> "Atue como um educador financeiro. Quais são 
> as diferenças entre Tesouro Selic, CDB e LCI 
> para quem está começando a investir? Use apenas 
> as informações presentes nas fontes disponíveis."

**Resultado:** Gerou espontaneamente uma tabela 
comparativa com 5 critérios (liquidez, risco, 
rentabilidade, tributação e valor mínimo), além 
de pontos de atenção sobre reserva de emergência, 
vantagem fiscal da LCI e custos operacionais.

#### 🔹 Prompt 2B - Variação
> "Atue como um educador financeiro. Compare 
> Tesouro Selic, CDB e LCI considerando: liquidez, 
> risco, rentabilidade e valor mínimo. Apresente 
> em formato de tabela e baseie-se apenas nas 
> fontes disponíveis."

**Resultado:** Gerou tabela com os mesmos 5 
critérios do 2A (incluindo tributação mesmo sem 
solicitação) e adicionou análise numerada mais 
aprofundada, com destaque para o comparativo 
de rentabilidade líquida entre LCI e CDB.

---

#### 🔍 Cicatriz - Comparativo 2A vs 2B

**Observação:** Mesmo sem solicitar formato de 
tabela no 2A, a IA o gerou espontaneamente ao 
perceber que o contexto era comparativo. O 2B, 
ao especificar os critérios, gerou uma análise 
mais estruturada e aprofundada.

**Aprendizado:** Especificar critérios no prompt 
não apenas organiza a resposta — eleva a qualidade 
da análise. O 2B trouxe o insight sobre 
rentabilidade líquida LCI vs CDB, ausente no 2A, 
demonstrando que prompts mais detalhados extraem 
respostas mais ricas.

### Bloco 3 - Aplicação Prática

---

#### 🔹 Prompt 3A
> "Atue como um educador financeiro. Tenho R$1.000 
> para investir pela primeira vez e quero segurança. 
> Com base nas fontes disponíveis, quais produtos 
> de renda fixa seriam mais adequados para este 
> perfil e por quê?"

**Resultado:** Indicou Tesouro Selic, CDB com 
liquidez diária e Poupança como opções para 
perfil conservador. Trouxe seção inédita 
explicando por que Tesouro Prefixado, IPCA+ 
e LCI foram descartados para este perfil — 
demonstrando raciocínio crítico da IA.

---

#### 🔹 Prompt 3B - Variação
> "Atue como um educador financeiro. Qual a 
> diferença entre investir para reserva de 
> emergência versus investir para um objetivo 
> de longo prazo em renda fixa? Quais produtos 
> são mais indicados para cada situação? 
> Baseie-se apenas nas fontes disponíveis."

**Resultado:** Entregou o conteúdo mais completo 
do caderno - distinguiu claramente os dois 
objetivos, indicou produtos específicos para 
cada caso e gerou tabela comparativa espontânea. 
Trouxe alerta crítico sobre riscos do resgate 
antecipado em títulos de longo prazo.

---

#### 🔍 Cicatriz - Comparativo 3A vs 3B

**Observação:** O 3A respondeu bem para um 
cenário específico (R$1.000, perfil conservador). 
O 3B elevou o nível ao abordar a estratégia por 
objetivo, gerando o conteúdo mais rico do caderno.

**Aprendizado:** Prompts baseados em 
**estratégia e objetivo** extraem respostas 
mais profundas do que prompts baseados em 
**cenário e valor**. Para fins educacionais, 
contextualizar o "para quê" do investimento 
é mais poderoso do que contextualizar o "quanto".

### Bloco 4 — Riscos e Cuidados

---

#### 🔹 Prompt 4A
> "Atue como um educador financeiro. Quais são 
> os principais riscos da renda fixa que um 
> investidor iniciante precisa conhecer antes 
> de aplicar seu dinheiro? Baseie-se apenas 
> nas fontes disponíveis."

**Resultado:** Estruturou os 4 pilares de risco 
da renda fixa: Crédito, Mercado, Liquidez e 
Concentração. Destaque para o conceito de 
"marcação a mercado" e o alerta sobre reserva 
de emergência em títulos sem liquidez diária.

---

#### 🔹 Prompt 4B - Variação
> "Atue como um educador financeiro. O que é 
> o FGC e como ele protege o investidor de 
> renda fixa? Quais produtos são cobertos 
> por ele e quais não são? Baseie-se apenas 
> nas fontes disponíveis."

**Resultado:** Explicou o FGC de forma completa, 
listou produtos cobertos (Poupança, CDB, LCI, LCA) 
e não cobertos (Tesouro Direto e Fundos), com 
destaque para o conceito inédito de segregação 
patrimonial dos fundos de investimento.

---

#### 🔍 Cicatriz - Comparativo 4A vs 4B

**Observação:** O 4A mapeou o panorama completo 
de riscos. O 4B aprofundou especificamente o 
Risco de Crédito, trazendo informação ausente 
no 4A: a segregação patrimonial dos fundos 
como mecanismo de proteção alternativo ao FGC.

---

### Bloco 5 — Descoberta: Produtos Avançados de Renda Fixa

#### 🔹 Prompt 5A
> "Atue como um educador financeiro. O que são 
> LC (Letra de Câmbio), LF (Letra Financeira), 
> Debêntures, CRI e CRA como produtos de renda 
> fixa? Baseie-se apenas nas fontes disponíveis."

**Resultado obtido:** O NotebookLM detalhou 
todos os 5 produtos com precisão:
- **LC:** Emitida por financeiras para captar 
  recursos destinados a financiamentos. 
  Coberta pelo FGC.
- **LF:** Chamada de "debênture dos bancos", 
  valor mínimo de R$150.000,00, prazo mínimo 
  de 24 meses, sem liquidez antecipada.
- **Debêntures:** Títulos emitidos por empresas 
  S/A. O investidor torna-se credor, não sócio. 
  Podem ser simples ou conversíveis em ações.
- **CRI:** Lastreado em créditos imobiliários, 
  emitido por securitizadoras. Sem cobertura FGC.
- **CRA:** Lastreado em recebíveis do agronegócio. 
  Sem cobertura FGC.

**Destaque da resposta:** A IA trouxe 
espontaneamente uma distinção crítica sobre 
cobertura do FGC:

| Produto | Cobertura FGC |
|---------|--------------|
| LC | ✅ Coberto até R$250 mil |
| CDB | ✅ Coberto até R$250 mil |
| LCI / LCA | ✅ Coberto até R$250 mil |
| LF | ❌ Não coberto |
| Debêntures | ❌ Não coberto |
| CRI / CRA | ❌ Não coberto |

---

#### 🔍 Cicatriz — Escopo das Fontes vs. Mercado Real

**Contexto:** Ao acessar uma corretora de 
investimentos, identifiquei produtos de renda 
fixa não abordados nos prompts anteriores: 
LC, LF, Debêntures, CRI e CRA.

**Hipótese inicial:** Imaginei que as fontes 
não cobriam esses produtos, já que não 
apareceram espontaneamente nas respostas 
dos Blocos 1 a 4.

**O que gerou a hipótese:** O prompt anterior 
sobre LC e LF foi corrigido após perceber que 
a versão inicial havia omitido esses dois 
produtos sem justificativa — demonstrando 
que a revisão crítica dos próprios prompts 
é parte essencial da engenharia de prompts.

**Resultado:** O NotebookLM respondeu com 
riqueza de detalhes — todos os produtos 
estavam nas fontes e foram explicados 
com precisão.

**Causa real identificada:** Os prompts 
anteriores foram formulados de forma genérica 
("principais produtos para iniciantes"), 
levando a IA a priorizar naturalmente os 
produtos mais populares e acessíveis. Os 
produtos avançados existiam nas fontes mas 
não foram evocados por falta de pergunta 
específica.

**Aprendizado:** A IA não entrega tudo 
espontaneamente - ela responde ao que é 
perguntado. Prompts genéricos revelam o 
panorama geral; prompts específicos revelam 
profundidade. Explorar ativamente o conteúdo 
das fontes é responsabilidade do estudante, 
não da IA. A revisão crítica dos próprios 
prompts - como a correção que incluiu LC e LF 
- é tão importante quanto a elaboração 
inicial deles.

**Aprendizado:** Prompts focados em um único 
conceito geram mais profundidade do que prompts 
abrangentes. A estratégia ideal é usar um prompt 
panorâmico (4A) para mapear o tema e prompts 
específicos (4B) para aprofundar os pontos críticos.
