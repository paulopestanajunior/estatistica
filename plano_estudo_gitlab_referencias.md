# Plano completo de estudos de Estatística para Data Science

## Livros adicionais incorporados

Além dos livros já considerados, este plano também pode usar:

- **Hands-On Machine Learning with Scikit-Learn, Keras & Transformers** — como apoio prático em Python para regressão, classificação, clusterização, redução de dimensionalidade e avaliação de modelos.
- **Data Science para Negócios** — como apoio conceitual para interpretação, tomada de decisão, modelagem aplicada e leitura de problemas reais com dados.

**Regra do plano:** toda aula deve ter pelo menos **uma referência de livro** e/ou **um material online** para facilitar consulta rápida e revisão.
## Formato 100% compatível com GitLab

**Início:** 16/03/2026  
**Carga diária:** 3h por dia  
**Ferramenta prática:** Python (Google Colab)  
**Objetivo:** aprender os conceitos estatísticos da pós o mais rápido possível, com foco em teoria + prática.

> **Importante sobre referências:**
> - Para os **seus livros físicos**, usei **capítulos e tópicos**, não página exata, porque a paginação muda conforme a edição.
> - Para **PDFs e materiais online**, usei **links diretos** e, quando viável, **páginas/seções estáveis**.

---

# Visão geral por semana

| Semana | Período | Tópico principal | Foco principal | Referência base da semana |
|---|---|---|---|---|
| 1 | 16/03 a 21/03 | Estatística descritiva | Variáveis, tabelas, gráficos, medidas-resumo, outliers | Morettin & Bussab; UECE/eduCAPES |
| 2 | 23/03 a 28/03 | Probabilidade e distribuições | Construir base para inferência | Sheldon Ross; Morettin & Bussab |
| 3 | 30/03 a 04/04 | Inferência estatística | IC, testes de hipóteses, ANOVA | Morettin & Bussab |
| 4 | 06/04 a 11/04 | Amostragem e não paramétricos | Seleção de amostras e testes sem normalidade | Bolfarine & Bussab |
| 5 | 13/04 a 18/04 | Regressão linear e multivariada | Modelagem linear, PCA, clusterização | Morettin; livro de multivariada; repo da Cibele Russo |
| 6 | 20/04 a 25/04 | Dados categóricos, logística e sobrevivência | Qui-quadrado, logística, Kaplan-Meier, Cox | Materiais específicos + Python |
| 7 | 27/04 a 02/05 | Séries temporais, longitudinais e metodologia | ARIMA, efeitos aleatórios e projeto final | Morettin & Toloi; materiais metodológicos |

---

# Semana 1 — Estatística descritiva

## Resumo da semana

| Dia | Conteúdo programático do dia | Referência principal |
|---|---|---|
| 16/03 | População, amostra, variáveis e escalas | Morettin (cap. introdutórios); UECE cap. 2 |
| 17/03 | Frequências, tabelas e gráficos | Morettin (estatística descritiva); UECE caps. 3 a 5 |
| 18/03 | Média, mediana e moda | Morettin (medidas-resumo); UECE cap. 6 |
| 19/03 | Variância, desvio-padrão, quartis e boxplot | Morettin (dispersão); UECE cap. 7 |
| 20/03 | Outliers, visualização e análise bidimensional | Morettin; UNIVESP |
| 21/03 | Revisão da semana | seus resumos + exercícios |

## 16/03 — População, amostra, variáveis e escalas

**Conteúdo programático**
- conceito de população
- conceito de amostra
- parâmetro e estatística
- variáveis qualitativas e quantitativas
- variáveis discretas e contínuas
- escalas nominal, ordinal, intervalar e de razão

**Referências do dia**
- **Morettin & Bussab**: capítulos iniciais de estatística descritiva e apresentação dos tipos de variáveis
- **UECE / eduCAPES**: capítulo 2 — População e Amostra; trecho de variáveis e escalas
- PDF texto: http://localhost:8451/https://educapes.capes.gov.br/bitstream/capes/718539/5/Estatistica-LIVRO.pdf
- Link público: https://educapes.capes.gov.br/handle/capes/432207

**Atividades**
- [ ] Ler teoria base sobre população, amostra e variáveis
- [ ] Fazer mapa mental dos tipos de variáveis
- [ ] Abrir um notebook no Google Colab
- [ ] Carregar um dataset simples em Python (`iris` ou `tips`)
- [ ] Classificar cada variável como qualitativa, discreta ou contínua
- [ ] Escrever um resumo de 5 a 10 linhas

## 17/03 — Frequências, tabelas e gráficos

**Conteúdo programático**
- frequência absoluta
- frequência relativa
- frequência acumulada
- tabelas de distribuição
- gráfico de barras
- histograma
- gráfico de setores

**Referências do dia**
- **Morettin & Bussab**: parte de tabelas, distribuições de frequência e gráficos
- **UECE / eduCAPES**: capítulo 3 — Gráficos Estatísticos; capítulo 4 — Tabelas e Séries Estatísticas; capítulo 5 — Distribuição de frequência
- UNIVESP: aulas de estatística descritiva
- https://www.youtube.com/results?search_query=univesp+estatistica+descritiva

**Atividades**
- [ ] Estudar teoria de frequências e tabelas
- [ ] Montar tabela de frequência para variável categórica
- [ ] Montar tabela de frequência para variável numérica
- [ ] Criar gráfico de barras em Python
- [ ] Criar histograma em Python
- [ ] Anotar quando usar cada gráfico

## 18/03 — Média, mediana e moda

**Conteúdo programático**
- medidas de tendência central
- média aritmética
- mediana
- moda
- efeito de valores extremos

**Referências do dia**
- **Morettin & Bussab**: parte de medidas de tendência central
- **UECE / eduCAPES**: capítulo 6 — Medidas de Posição
- Link público: https://educapes.capes.gov.br/handle/capes/432207

**Atividades**
- [ ] Estudar definição e interpretação de média, mediana e moda
- [ ] Resolver 5 exercícios manuais
- [ ] Calcular média, mediana e moda em Python
- [ ] Inserir um outlier artificial no dataset
- [ ] Comparar o efeito do outlier na média e na mediana
- [ ] Registrar a conclusão

## 19/03 — Variância, desvio-padrão, quartis e boxplot

**Conteúdo programático**
- amplitude
- variância
- desvio-padrão
- coeficiente de variação
- quartis
- boxplot

**Referências do dia**
- **Morettin & Bussab**: parte de medidas de dispersão e separatrizes
- **UECE / eduCAPES**: capítulo 7 — Medidas de Dispersão
- Complemento visual: boxplot e interpretação no material do curso

**Atividades**
- [ ] Ler teoria de medidas de dispersão
- [ ] Resolver exercícios de variância e desvio-padrão
- [ ] Calcular quartis em Python
- [ ] Gerar boxplot em Python
- [ ] Identificar possíveis outliers
- [ ] Explicar o que cada parte do boxplot representa

## 20/03 — Outliers, visualização e análise bidimensional

**Conteúdo programático**
- identificação de outliers
- visualização de distribuições
- relação entre duas variáveis
- gráfico de dispersão
- noção inicial de correlação

**Referências do dia**
- **Morettin & Bussab**: estatística descritiva bidimensional
- UNIVESP: correlação e gráficos de dispersão
- https://www.youtube.com/results?search_query=univesp+correlacao+estatistica

**Atividades**
- [ ] Ler teoria sobre outliers e análise bidimensional
- [ ] Fazer scatterplot entre duas variáveis numéricas
- [ ] Calcular correlação em Python
- [ ] Interpretar se a correlação parece fraca, moderada ou forte
- [ ] Escrever um mini-relatório com gráfico e interpretação

## 21/03 — Revisão da semana 1

**Referências do dia**
- seus resumos
- exercícios do Morettin
- notebooks do Colab da semana

**Atividades**
- [ ] Revisar todos os resumos da semana
- [ ] Refazer 3 exercícios sem consultar
- [ ] Revisar os gráficos feitos
- [ ] Conferir se sabe diferenciar variável discreta e contínua
- [ ] Conferir se sabe interpretar média, mediana, desvio-padrão e boxplot
- [ ] Listar dúvidas pendentes

---

# Semana 2 — Probabilidade e distribuições

## Resumo da semana

| Dia | Conteúdo programático do dia | Referência principal |
|---|---|---|
| 23/03 | Experimentos, espaço amostral e eventos | Sheldon Ross, caps. iniciais |
| 24/03 | Regras de probabilidade e Bayes | Sheldon Ross |
| 25/03 | Variáveis aleatórias discretas | Sheldon Ross |
| 26/03 | Variáveis aleatórias contínuas | Sheldon Ross |
| 27/03 | Esperança, variância e distribuições importantes | Ross + Morettin |
| 28/03 | Revisão aplicada | exercícios + Python |

## 23/03 — Experimentos, espaço amostral e eventos

**Conteúdo programático**
- experimento aleatório
- espaço amostral
- eventos simples e compostos
- união, interseção e complemento

**Referências do dia**
- **Sheldon Ross**: capítulos iniciais de experimentos aleatórios e espaço amostral
- **Morettin & Bussab**: introdução à probabilidade

**Atividades**
- [ ] Ler teoria de experimentos aleatórios
- [ ] Resolver exercícios com moedas, dados e cartas
- [ ] Desenhar diagramas de eventos
- [ ] Representar união, interseção e complementar
- [ ] Fazer resumo dos símbolos principais

## 24/03 — Regras de probabilidade e Bayes

**Conteúdo programático**
- axiomas da probabilidade
- probabilidade condicional
- independência
- probabilidade total
- teorema de Bayes

**Referências do dia**
- **Sheldon Ross**: capítulos sobre probabilidade condicional e independência
- **Morettin & Bussab**: probabilidade total e Bayes

**Atividades**
- [ ] Ler teoria de probabilidade condicional
- [ ] Resolver 6 exercícios
- [ ] Separar exemplos de eventos independentes e dependentes
- [ ] Resolver 2 exercícios de Bayes
- [ ] Escrever um exemplo prático de Bayes

## 25/03 — Variáveis aleatórias discretas

**Conteúdo programático**
- variável aleatória discreta
- distribuição Bernoulli
- distribuição Binomial
- distribuição Poisson
- distribuição Geométrica

**Referências do dia**
- **Sheldon Ross**: capítulos de variáveis aleatórias discretas
- **Morettin & Bussab**: distribuições discretas usuais
- SciPy stats: https://docs.scipy.org/doc/scipy/

**Atividades**
- [ ] Estudar definição de variável aleatória discreta
- [ ] Resolver exercícios de binomial
- [ ] Resolver exercícios de Poisson
- [ ] Simular binomial e Poisson em Python
- [ ] Comparar as distribuições em gráficos

## 26/03 — Variáveis aleatórias contínuas

**Conteúdo programático**
- variável aleatória contínua
- função densidade
- distribuição uniforme
- distribuição exponencial
- distribuição normal

**Referências do dia**
- **Sheldon Ross**: capítulos de variáveis aleatórias contínuas
- **Morettin & Bussab**: distribuição normal e contínuas básicas
- SciPy stats: https://docs.scipy.org/doc/scipy/

**Atividades**
- [ ] Estudar densidade e interpretação geométrica
- [ ] Resolver exercícios de normal
- [ ] Fazer padronização z-score
- [ ] Simular distribuição normal em Python
- [ ] Plotar curva normal e interpretar média e desvio-padrão

## 27/03 — Esperança, variância e distribuições importantes

**Conteúdo programático**
- esperança matemática
- variância
- interpretação prática
- escolha de distribuição

**Referências do dia**
- **Sheldon Ross**: esperança e variância
- **Morettin & Bussab**: revisão de distribuições

**Atividades**
- [ ] Calcular esperança e variância em exercícios
- [ ] Fazer tabela-resumo das distribuições
- [ ] Escrever quando usar binomial, Poisson, normal e exponencial
- [ ] Simular exemplos em Python
- [ ] Revisar dúvidas da semana

## 28/03 — Revisão da semana 2

**Referências do dia**
- exercícios do Ross
- exercícios do Morettin
- notebooks do Colab

**Atividades**
- [ ] Refazer exercícios sem consulta
- [ ] Montar formulário-resumo da semana
- [ ] Verificar se consegue escolher a distribuição adequada em exemplos simples
- [ ] Revisar Bayes, binomial e normal
- [ ] Organizar notebook da semana no GitLab

---

# Semana 3 — Inferência estatística

## Resumo da semana

| Dia | Conteúdo programático do dia | Referência principal |
|---|---|---|
| 30/03 | Distribuições amostrais e TLC | Morettin |
| 31/03 | Estimação pontual | Morettin |
| 01/04 | Intervalos de confiança | Morettin |
| 02/04 | Testes de hipóteses (1 amostra) | Morettin |
| 03/04 | Testes de hipóteses (2 amostras) | Morettin |
| 04/04 | ANOVA e qui-quadrado | Morettin |

## 30/03 — Distribuições amostrais e TLC

**Referências do dia**
- **Morettin & Bussab**: capítulos de distribuições amostrais e inferência
- apoio prático em Python: https://docs.scipy.org/doc/scipy/

**Atividades**
- [ ] Ler teoria das distribuições amostrais
- [ ] Entender a intuição do TLC
- [ ] Simular médias amostrais em Python
- [ ] Comparar histograma original e histograma das médias
- [ ] Escrever o que o TLC diz com suas palavras

## 31/03 — Estimação pontual

**Referências do dia**
- **Morettin & Bussab**: estimação pontual

**Atividades**
- [ ] Ler teoria de estimação pontual
- [ ] Resolver exercícios de estimadores
- [ ] Calcular estimativas em um dataset real
- [ ] Comparar estimativas em amostras de tamanhos diferentes
- [ ] Anotar o que muda quando a amostra cresce

## 01/04 — Intervalos de confiança

**Referências do dia**
- **Morettin & Bussab**: intervalo de confiança para médias e proporções
- SciPy: https://docs.scipy.org/doc/scipy/

**Atividades**
- [ ] Ler teoria de intervalos de confiança
- [ ] Resolver exercícios manuais
- [ ] Construir intervalos em Python
- [ ] Interpretar os resultados em linguagem simples
- [ ] Comparar intervalos com amostras pequenas e grandes

## 02/04 — Testes de hipóteses (1 amostra)

**Referências do dia**
- **Morettin & Bussab**: testes de hipóteses para uma amostra
- SciPy: https://docs.scipy.org/doc/scipy/

**Atividades**
- [ ] Ler teoria de testes de hipóteses
- [ ] Resolver exemplos de teste de média
- [ ] Fazer teste z ou t em Python
- [ ] Interpretar p-valor corretamente
- [ ] Escrever a decisão final em frase completa

## 03/04 — Testes de hipóteses (2 amostras)

**Referências do dia**
- **Morettin & Bussab**: comparação entre duas amostras
- SciPy: https://docs.scipy.org/doc/scipy/

**Atividades**
- [ ] Estudar diferença entre amostras independentes e pareadas
- [ ] Resolver exercícios de teste t para duas amostras
- [ ] Fazer um teste pareado em Python
- [ ] Fazer um teste de comparação entre dois grupos
- [ ] Resumir quando usar cada teste

## 04/04 — ANOVA e qui-quadrado

**Referências do dia**
- **Morettin & Bussab**: ANOVA de um fator e testes qui-quadrado
- statsmodels: https://www.statsmodels.org/
- SciPy: https://docs.scipy.org/doc/scipy/

**Atividades**
- [ ] Ler teoria de ANOVA
- [ ] Resolver um exercício manual de ANOVA
- [ ] Rodar uma ANOVA simples em Python
- [ ] Rodar teste qui-quadrado em Python
- [ ] Interpretar em linguagem simples o resultado dos testes

---

# Semana 4 — Amostragem e não paramétricos

## Resumo da semana

| Dia | Conteúdo programático do dia | Referência principal |
|---|---|---|
| 06/04 | Amostragem aleatória simples e sistemática | Bolfarine & Bussab |
| 07/04 | Amostragem estratificada e por conglomerados | Bolfarine & Bussab |
| 08/04 | Testes não paramétricos para pares | material complementar |
| 09/04 | Testes não paramétricos para independentes | material complementar |
| 10/04 | Aderência, homogeneidade e independência | Morettin |
| 11/04 | Revisão | exercícios + Python |

## 06/04 — Amostragem aleatória simples e sistemática

**Referências do dia**
- **Bolfarine & Bussab**: capítulos iniciais de amostragem aleatória simples e sistemática
- complemento conceitual: slides UFJF de amostragem

**Atividades**
- [ ] Ler teoria no Bolfarine & Bussab
- [ ] Fazer resumo dos tipos de amostragem
- [ ] Sortear amostra aleatória simples em Python
- [ ] Sortear amostra sistemática em Python
- [ ] Comparar as duas abordagens

## 07/04 — Amostragem estratificada e por conglomerados

**Referências do dia**
- **Bolfarine & Bussab**: capítulos de amostragem estratificada e conglomerados
- slides UFJF de amostragem

**Atividades**
- [ ] Ler teoria de estratos e conglomerados
- [ ] Montar um exemplo prático de estratificação
- [ ] Fazer amostragem estratificada em Python
- [ ] Anotar vantagens e limitações
- [ ] Revisar quando cada tipo faz sentido

## 08/04 — Não paramétricos para amostras pareadas

**Referências do dia**
- material complementar de testes não paramétricos
- SciPy stats: https://docs.scipy.org/doc/scipy/

**Atividades**
- [ ] Estudar teoria dos testes pareados não paramétricos
- [ ] Resolver exercícios conceituais
- [ ] Aplicar Wilcoxon em Python
- [ ] Comparar com a ideia do teste t pareado
- [ ] Resumir quando usar

## 09/04 — Não paramétricos para amostras independentes

**Referências do dia**
- material complementar de testes não paramétricos
- SciPy stats: https://docs.scipy.org/doc/scipy/

**Atividades**
- [ ] Ler teoria de Mann-Whitney e Kruskal-Wallis
- [ ] Resolver exercícios
- [ ] Aplicar ambos em Python
- [ ] Interpretar hipótese nula de cada um
- [ ] Fazer tabela comparativa dos testes

## 10/04 — Aderência, homogeneidade e independência

**Referências do dia**
- **Morettin & Bussab**: qui-quadrado para aderência e independência
- SciPy stats: https://docs.scipy.org/doc/scipy/

**Atividades**
- [ ] Revisar teoria de qui-quadrado
- [ ] Fazer um exemplo de aderência
- [ ] Fazer um exemplo de independência
- [ ] Rodar os testes em Python
- [ ] Interpretar as conclusões

## 11/04 — Revisão da semana 4

**Referências do dia**
- resumos da semana
- exercícios do Bolfarine
- notebooks Python

**Atividades**
- [ ] Revisar todos os tipos de amostragem
- [ ] Revisar todos os testes não paramétricos vistos
- [ ] Refazer 3 exercícios sem consulta
- [ ] Atualizar resumos no GitLab
- [ ] Registrar dúvidas ainda abertas

---

# Semana 5 — Regressão linear e multivariada

## Resumo da semana

| Dia | Conteúdo programático do dia | Referência principal |
|---|---|---|
| 13/04 | Correlação e regressão linear simples | Morettin |
| 14/04 | Regressão múltipla | Morettin |
| 15/04 | Diagnóstico de regressão | Morettin |
| 16/04 | Transformações e seleção de modelos | Morettin |
| 17/04 | PCA | livro de multivariada + repo da Cibele Russo |
| 18/04 | Clusterização e discriminação | livro de multivariada + repo da Cibele Russo |

## 13/04 — Correlação e regressão linear simples

**Referências do dia**
- **Morettin & Bussab**: correlação e regressão linear simples
- statsmodels: https://www.statsmodels.org/

**Atividades**
- [ ] Estudar teoria da regressão linear simples
- [ ] Fazer scatterplot com linha de ajuste
- [ ] Ajustar regressão simples em Python
- [ ] Interpretar intercepto, inclinação e R²
- [ ] Escrever conclusão em linguagem simples

## 14/04 — Regressão múltipla

**Referências do dia**
- **Morettin & Bussab**: regressão linear múltipla
- statsmodels: https://www.statsmodels.org/

**Atividades**
- [ ] Ler teoria de regressão múltipla
- [ ] Ajustar modelo múltiplo em Python
- [ ] Comparar com regressão simples
- [ ] Verificar variáveis mais relevantes
- [ ] Anotar diferença entre associação e causalidade

## 15/04 — Diagnóstico de regressão

**Referências do dia**
- **Morettin & Bussab**: diagnóstico e pressupostos
- statsmodels: https://www.statsmodels.org/

**Atividades**
- [ ] Estudar pressupostos da regressão
- [ ] Plotar resíduos em Python
- [ ] Verificar normalidade visualmente
- [ ] Identificar pontos influentes
- [ ] Escrever quais problemas apareceram no modelo

## 16/04 — Transformações e seleção de modelos

**Referências do dia**
- **Morettin & Bussab**: transformações e ajuste
- statsmodels: https://www.statsmodels.org/

**Atividades**
- [ ] Estudar quando transformar variáveis
- [ ] Aplicar log em um exemplo
- [ ] Comparar ajuste antes e depois
- [ ] Ler noções de AIC/BIC
- [ ] Registrar aprendizado principal do dia

## 17/04 — PCA

**Referências do dia**
- **Seu livro de multivariada**: capítulo de componentes principais
- **Repositório da Cibele Russo**: aulas, dados e comandos em Python
- https://github.com/cibelerusso/AnaliseMultivariadaEAprendizadoNaoSupervisionado
- scikit-learn: https://scikit-learn.org/

**Atividades**
- [ ] Ler teoria de PCA
- [ ] Ver no repositório da Cibele Russo os materiais de aula
- [ ] Rodar PCA em Python
- [ ] Analisar variância explicada
- [ ] Fazer gráfico das componentes
- [ ] Interpretar o que cada componente parece resumir

## 18/04 — Clusterização e análise discriminante

**Referências do dia**
- **Seu livro de multivariada**: capítulos de agrupamento e discriminação
- **Repositório da Cibele Russo**: aulas, dados e comandos em Python
- https://github.com/cibelerusso/AnaliseMultivariadaEAprendizadoNaoSupervisionado
- scikit-learn: https://scikit-learn.org/

**Atividades**
- [ ] Ler teoria de clusterização
- [ ] Explorar exemplos do repositório da Cibele Russo
- [ ] Rodar k-means em Python
- [ ] Rodar cluster hierárquico em Python
- [ ] Comparar resultados
- [ ] Fazer resumo do que muda entre PCA e clustering

---

# Semana 6 — Dados categóricos, logística e sobrevivência

## Resumo da semana

| Dia | Conteúdo programático do dia | Referência principal |
|---|---|---|
| 20/04 | Tabelas de contingência | Morettin |
| 21/04 | Regressão logística binária | material de logística |
| 22/04 | Regressão logística múltipla e multinomial | material de logística |
| 23/04 | Conceitos de sobrevivência e censura | material de sobrevivência |
| 24/04 | Kaplan-Meier e logrank | material de sobrevivência |
| 25/04 | Modelo de Cox e revisão | material de sobrevivência |

## 20/04 — Tabelas de contingência

**Referências do dia**
- **Morettin & Bussab**: tabelas de contingência e qui-quadrado
- SciPy stats: https://docs.scipy.org/doc/scipy/

**Atividades**
- [ ] Montar tabelas de contingência em Python
- [ ] Calcular frequências esperadas
- [ ] Rodar qui-quadrado
- [ ] Rodar Fisher quando apropriado
- [ ] Interpretar odds ratio

## 21/04 — Regressão logística binária

**Referências do dia**
- material introdutório de regressão logística
- statsmodels: https://www.statsmodels.org/
- scikit-learn: https://scikit-learn.org/

**Atividades**
- [ ] Ler teoria de regressão logística binária
- [ ] Ajustar um modelo logístico em Python
- [ ] Interpretar coeficientes
- [ ] Calcular probabilidades previstas
- [ ] Escrever a diferença entre regressão linear e logística

## 22/04 — Regressão logística múltipla e multinomial

**Referências do dia**
- material de regressão logística múltipla e multinomial
- statsmodels e scikit-learn

**Atividades**
- [ ] Ajustar modelo logístico múltiplo
- [ ] Avaliar o ajuste do modelo
- [ ] Testar um exemplo multinomial
- [ ] Comparar saída do modelo
- [ ] Resumir quando usar binária e quando usar multinomial

## 23/04 — Conceitos de sobrevivência e censura

**Referências do dia**
- material introdutório de sobrevivência
- lifelines: https://lifelines.readthedocs.io/

**Atividades**
- [ ] Ler teoria de sobrevivência
- [ ] Entender o conceito de censura
- [ ] Escrever a diferença entre análise clássica e de sobrevivência
- [ ] Ler exemplos aplicados
- [ ] Fazer resumo do vocabulário principal

## 24/04 — Kaplan-Meier e logrank

**Referências do dia**
- material introdutório de Kaplan-Meier
- lifelines: https://lifelines.readthedocs.io/

**Atividades**
- [ ] Rodar Kaplan-Meier em Python
- [ ] Fazer gráfico de sobrevivência
- [ ] Comparar dois grupos
- [ ] Aplicar teste logrank
- [ ] Interpretar os resultados em linguagem simples

## 25/04 — Modelo de Cox e revisão

**Referências do dia**
- material de regressão de Cox
- lifelines: https://lifelines.readthedocs.io/

**Atividades**
- [ ] Ler teoria do modelo de Cox
- [ ] Ajustar modelo de Cox em Python
- [ ] Interpretar hazard ratio
- [ ] Revisar Kaplan-Meier, logrank e Cox
- [ ] Registrar dúvidas

---

# Semana 7 — Séries temporais, longitudinais e metodologia

## Resumo da semana

| Dia | Conteúdo programático do dia | Referência principal |
|---|---|---|
| 27/04 | Fundamentos de séries temporais | Morettin & Toloi |
| 28/04 | Modelos AR e MA | Morettin & Toloi |
| 29/04 | ARIMA e SARIMA | Morettin & Toloi |
| 30/04 | Dados longitudinais e efeitos aleatórios | material complementar |
| 01/05 | Revisão de séries e longitudinais | exercícios + Python |
| 02/05 | Metodologia científica e projeto final | material metodológico |

## 27/04 — Fundamentos de séries temporais

**Referências do dia**
- **Morettin & Toloi**: capítulos iniciais de séries temporais
- statsmodels: https://www.statsmodels.org/

**Atividades**
- [ ] Ler teoria básica de séries temporais
- [ ] Plotar uma série temporal em Python
- [ ] Identificar tendência e sazonalidade
- [ ] Calcular ACF e PACF
- [ ] Registrar o que foi observado

## 28/04 — Modelos AR e MA

**Referências do dia**
- **Morettin & Toloi**: capítulos de modelos AR e MA
- statsmodels: https://www.statsmodels.org/

**Atividades**
- [ ] Estudar teoria dos modelos AR e MA
- [ ] Simular exemplos em Python
- [ ] Observar ACF e PACF
- [ ] Escrever o que diferencia AR de MA
- [ ] Salvar notebook da aula

## 29/04 — ARIMA e SARIMA

**Referências do dia**
- **Morettin & Toloi**: ARIMA e modelos sazonais
- statsmodels: https://www.statsmodels.org/

**Atividades**
- [ ] Ler teoria de ARIMA
- [ ] Diferenciar uma série em Python
- [ ] Ajustar ARIMA simples
- [ ] Ajustar modelo sazonal se fizer sentido
- [ ] Fazer uma previsão curta
- [ ] Interpretar os resultados

## 30/04 — Dados longitudinais e efeitos aleatórios

**Referências do dia**
- material complementar de modelos mistos
- statsmodels: https://www.statsmodels.org/

**Atividades**
- [ ] Ler teoria de dados longitudinais
- [ ] Entender por que não tratar tudo como independente
- [ ] Ajustar modelo misto simples em Python
- [ ] Interpretar efeitos fixos e aleatórios
- [ ] Anotar aplicações possíveis

## 01/05 — Revisão de séries e longitudinais

**Referências do dia**
- resumos da semana
- notebooks Python

**Atividades**
- [ ] Revisar resumos de séries temporais
- [ ] Revisar resumos de dados longitudinais
- [ ] Refazer 2 exercícios de cada tema
- [ ] Organizar notebooks no GitLab
- [ ] Marcar tópicos em que ainda há dúvida

## 02/05 — Metodologia científica e projeto final

**Referências do dia**
- material de metodologia científica
- guias acadêmicos institucionais

**Atividades**
- [ ] Ler material sobre metodologia científica
- [ ] Escolher um tema pequeno para projeto final
- [ ] Escrever problema de pesquisa
- [ ] Escrever objetivo geral
- [ ] Definir quais métodos estatísticos usaria
- [ ] Montar um mini-esboço de projeto

---

## Como usar os livros extras ao longo do plano

- **Hands-On Machine Learning** entra principalmente em:
  - regressão linear e regressão logística
  - clusterização
  - PCA e redução de dimensionalidade
  - organização prática de experimentos em Python
- **Data Science para Negócios** entra principalmente em:
  - motivação aplicada dos métodos
  - formulação de perguntas de negócio
  - interpretação de resultados
  - ligação entre estatística e decisão

## Regra de referência por aula

Em cada aula do plano, mantenha sempre este padrão:

- **Referência de livro:** pelo menos 1
- **Referência online:** pelo menos 1 quando houver material bom disponível
- **Ferramenta prática:** Python/Colab quando a aula pedir aplicação

# Links úteis

- Google Colab: https://colab.research.google.com/
- Kaggle Datasets: https://www.kaggle.com/datasets
- SciPy: https://docs.scipy.org/doc/scipy/
- statsmodels: https://www.statsmodels.org/
- scikit-learn: https://scikit-learn.org/
- lifelines: https://lifelines.readthedocs.io/
- IBGE SIDRA: https://sidra.ibge.gov.br/
- Repositório da Cibele Russo: https://github.com/cibelerusso/AnaliseMultivariadaEAprendizadoNaoSupervisionado

