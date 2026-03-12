# Plano 1 — Estatística para Data Science (pesado)
## Conteúdo da pós + prática aplicada em Python/ML
## Formato 100% compatível com GitLab/GitHub

**Objetivo:** dominar a base estatística da pós em Data Science e Estatística Aplicada, com aplicação prática em Python e conexão com Machine Learning.  
**Carga sugerida:** **3h por dia**, **6 dias por semana**, por **6 semanas**.  
**Domingo:** revisão leve, organização de notas e recuperação de atraso.  
**Ferramenta prática:** **Python** no **Google Colab** ou Jupyter.

---

# Como usar este arquivo

- As **tabelas** são usadas só para visão geral semanal.
- As **tarefas diárias** ficam fora da tabela, com **checkbox real**.
- Cada aula tem:
  - conteúdo programático
  - referência de livro com **página exata** quando disponível
  - material online
  - atividade prática em Python

---

# Bibliografia principal

## Base de teoria
- **Morettin & Bussab — Estatística Básica, 9ª edição**
- **Sheldon Ross — Probabilidade, 8ª edição**
- **Bolfarine & Bussab — Elementos de Amostragem, 1ª edição, 4ª impressão**
- **Sueli Aparecida Mingoti — Análise de Dados Através de Métodos de Estatística Multivariada, 1ª edição**

## Base complementar aplicada
- **Data Science para Negócios, 1ª edição**
- **Mãos à Obra: Aprendizado de Máquina com Scikit-Learn, Keras e TensorFlow, 2ª edição**

## Materiais externos úteis
- **UECE / eduCAPES — Estatística e Probabilidade**  
  https://educapes.capes.gov.br/handle/capes/432207
- **UNIVESP — videoaulas de Estatística**  
  https://www.youtube.com/results?search_query=univesp+estatistica
- **Google Colab**  
  https://colab.research.google.com/
- **SciPy**  
  https://docs.scipy.org/doc/scipy/
- **statsmodels**  
  https://www.statsmodels.org/
- **scikit-learn**  
  https://scikit-learn.org/
- **lifelines**  
  https://lifelines.readthedocs.io/
- **Kaggle Datasets**  
  https://www.kaggle.com/datasets
- **IBGE SIDRA**  
  https://sidra.ibge.gov.br/
- **Repositório da Cibele Russo**  
  https://github.com/cibelerusso/AnaliseMultivariadaEAprendizadoNaoSupervisionado

---

# Estrutura do plano

## Bloco A — Fundamentos estatísticos
- estatística descritiva
- probabilidade
- inferência
- testes de hipóteses

## Bloco B — Inferência aplicada
- duas populações
- aderência e associação
- ANOVA
- amostragem

## Bloco C — Modelagem e multivariada
- regressão
- dados categóricos
- PCA
- cluster
- discriminante

## Bloco D — Tópicos avançados da pós
- sobrevivência
- séries temporais
- longitudinais
- metodologia científica

---

# Visão geral por semana

| Semana | Foco principal | Objetivo | Livros-base |
|---|---|---|---|
| 1 | Estatística descritiva e análise bidimensional | dominar resumo de dados e visualização | Morettin; UECE |
| 2 | Probabilidade e variáveis aleatórias | construir base matemática para inferência | Ross; Morettin |
| 3 | Inferência estatística e testes | entender estimação, IC e testes | Morettin |
| 4 | Amostragem, aderência, associação e ANOVA | cobrir parte central da pós | Bolfarine; Morettin |
| 5 | Regressão, dados categóricos e multivariada | ligar estatística com ML | Morettin; Mingoti; Hands-On |
| 6 | Sobrevivência, séries temporais, longitudinais e fechamento | fechar lacunas e consolidar | materiais específicos + prática |

---

# Semana 1 — Estatística descritiva e análise bidimensional

## Resumo da semana

| Dia | Tema | Referência principal |
|---|---|---|
| 1 | Tipos de variáveis e distribuições de frequência | Morettin cap. 2 |
| 2 | Gráficos estatísticos | Morettin cap. 2 |
| 3 | Medidas de posição e dispersão | Morettin cap. 3 |
| 4 | Quantis, boxplot, outliers | Morettin cap. 3 |
| 5 | Análise bidimensional | Morettin cap. 4 |
| 6 | Revisão + prática aplicada | Morettin + Python |

## Dia 1 — Tipos de variáveis e distribuições de frequência

**Conteúdo programático**
- tipos de variáveis
- qualitativa, quantitativa, discreta e contínua
- distribuição de frequência
- tabela de frequência

**Referências**
- **Morettin & Bussab**: Cap. 2 — **2.1 Tipos de Variáveis (p. 11)**; **2.2 Distribuições de Frequências (p. 11)**
- **UECE / eduCAPES**: capítulos de população, amostra e frequência
- https://educapes.capes.gov.br/handle/capes/432207

**Atividades**
- [ ] Ler Morettin p. 11–15
- [ ] Ler apoio UECE sobre variáveis e frequência
- [ ] Criar resumo de 10 linhas sobre tipos de variáveis
- [ ] No Colab, carregar `iris` ou `penguins`
- [ ] Classificar cada variável do dataset
- [ ] Montar ao menos 2 tabelas de frequência em Python

## Dia 2 — Gráficos estatísticos

**Conteúdo programático**
- gráficos para variáveis qualitativas
- gráficos para variáveis quantitativas
- histograma
- gráfico de barras
- gráfico de dispersão inicial

**Referências**
- **Morettin & Bussab**: **2.3 Gráficos (p. 15)**; **2.3.1 Variáveis Qualitativas (p. 18)**; **2.3.2 Variáveis Quantitativas (p. 19)**; **2.4 Ramo-e-Folhas (p. 23)**
- **UNIVESP**: estatística descritiva
- https://www.youtube.com/results?search_query=univesp+estatistica+descritiva

**Atividades**
- [ ] Ler Morettin p. 15–23
- [ ] Assistir 1 aula da UNIVESP de estatística descritiva
- [ ] Gerar gráfico de barras para variável categórica
- [ ] Gerar histograma para variável numérica
- [ ] Gerar gráfico ramo-e-folhas manualmente para um exemplo pequeno
- [ ] Escrever quando cada gráfico deve ser usado

## Dia 3 — Medidas de posição e dispersão

**Conteúdo programático**
- média
- mediana
- moda
- variância
- desvio-padrão

**Referências**
- **Morettin & Bussab**: **3.1 Medidas de Posição (p. 39)**; **3.2 Medidas de Dispersão (p. 41)**
- **UECE / eduCAPES**: medidas de posição e dispersão

**Atividades**
- [ ] Ler Morettin p. 39–45
- [ ] Resolver 6 exercícios manuais
- [ ] Calcular média, mediana, moda, variância e desvio-padrão em Python
- [ ] Inserir um outlier artificial no dataset
- [ ] Comparar a sensibilidade da média e da mediana
- [ ] Registrar a conclusão em 5 linhas

## Dia 4 — Quantis, boxplot e outliers

**Conteúdo programático**
- quartis
- quantis
- boxplot
- assimetria
- outliers

**Referências**
- **Morettin & Bussab**: **3.3 Quantis Empíricos (p. 45)**; **3.4 Box Plots (p. 51)**; **3.5 Gráficos de Simetria (p. 55)**; **3.6 Transformações (p. 56)**
- **UECE / eduCAPES**
- https://colab.research.google.com/

**Atividades**
- [ ] Ler Morettin p. 45–58
- [ ] Fazer um boxplot em Python
- [ ] Identificar outliers
- [ ] Verificar assimetria de uma variável
- [ ] Fazer uma transformação simples (log, se couber)
- [ ] Escrever o que mudou após a transformação

## Dia 5 — Análise bidimensional

**Conteúdo programático**
- associação entre variáveis
- correlação
- associação entre variáveis qualitativas
- associação entre variáveis quantitativas

**Referências**
- **Morettin & Bussab**: **Cap. 4 — Introdução (p. 73)**; **4.3 Associação entre Variáveis Qualitativas (p. 78)**; **4.4 Medidas de Associação entre Variáveis Qualitativas (p. 81)**; **4.5 Associação entre Variáveis Quantitativas (p. 85)**; **4.6 Associação entre Variáveis Qualitativas e Quantitativas (p. 92)**
- https://www.youtube.com/results?search_query=univesp+correlacao+estatistica

**Atividades**
- [ ] Ler Morettin p. 73–97
- [ ] Fazer 2 scatterplots em Python
- [ ] Calcular correlação de Pearson
- [ ] Montar uma tabela de contingência simples
- [ ] Interpretar associação entre duas variáveis categóricas
- [ ] Escrever um mini-relatório com 1 gráfico

## Dia 6 — Revisão aplicada da semana

**Referências**
- Morettin cap. 2, 3 e 4
- Python: pandas, matplotlib, seaborn

**Atividades**
- [ ] Revisar resumos da semana
- [ ] Repetir os 3 gráficos mais importantes
- [ ] Criar um notebook `semana01_descritiva.ipynb`
- [ ] Fazer análise exploratória curta em um dataset do Kaggle ou IBGE
- [ ] Subir notebook no GitLab/GitHub
- [ ] Listar dúvidas pendentes

---

# Semana 2 — Probabilidade e variáveis aleatórias

## Resumo da semana

| Dia | Tema | Referência principal |
|---|---|---|
| 7 | Combinatória e axiomas | Ross caps. 1 e 2 |
| 8 | Probabilidade condicional e Bayes | Ross cap. 3 |
| 9 | Variáveis discretas | Ross cap. 4 |
| 10 | Variáveis contínuas | Ross cap. 5 |
| 11 | Esperança, covariância e TLC | Ross caps. 7 e 8 |
| 12 | Revisão e simulação | Ross cap. 10 |

## Dia 7 — Combinatória, espaço amostral e axiomas

**Referências**
- **Ross**: **Cap. 1 — Análise combinatória (p. 15–24)**; **Cap. 2 — Espaço amostral e eventos (p. 39)**; **Axiomas da probabilidade (p. 44)**

**Atividades**
- [ ] Ler Ross p. 15–24
- [ ] Ler Ross p. 39–52
- [ ] Resolver 8 exercícios de contagem
- [ ] Resolver 4 exercícios de probabilidade básica
- [ ] Fazer um resumo dos símbolos e operações com eventos

## Dia 8 — Probabilidade condicional, independência e Bayes

**Referências**
- **Ross**: **3.2 Probabilidades condicionais (p. 81)**; **3.3 Fórmula de Bayes (p. 89)**; **3.4 Eventos independentes (p. 106)**
- **Data Science para Negócios**: **Cap. 9 — Teorema de Bayes (p. 236)**; **Naive Bayes (p. 239)**

**Atividades**
- [ ] Ler Ross p. 81–121
- [ ] Ler DS para Negócios p. 236–241
- [ ] Resolver 6 exercícios de Bayes
- [ ] Escrever um exemplo real de probabilidade condicional
- [ ] Implementar um exemplo simples de Bayes em Python

## Dia 9 — Variáveis aleatórias discretas

**Referências**
- **Ross**: **4.1 Variáveis aleatórias (p. 151)**; **4.2 Discretas (p. 157)**; **4.3 Valor esperado (p. 160)**; **4.5 Variância (p. 168)**; **4.6 Binomial e Bernoulli (p. 170)**; **4.7 Poisson (p. 181)**; **4.8 Geométrica/Hipergeométrica (p. 195, 200)**
- **Morettin**: **6.6.2 Bernoulli (p. 153)**; **6.6.3 Binomial (p. 157)**; **6.6.5 Poisson (p. 164)**

**Atividades**
- [ ] Ler Ross p. 151–205
- [ ] Resolver exercícios de binomial e Poisson
- [ ] Simular Bernoulli, binomial e Poisson em Python
- [ ] Comparar média e variância simuladas com as fórmulas
- [ ] Fazer 1 quadro-resumo das distribuições discretas

## Dia 10 — Variáveis aleatórias contínuas

**Referências**
- **Ross**: **Cap. 5 — Introdução (p. 231)**; **Uniforme (p. 240)**; **Normal (p. 244)**; **Exponencial (p. 256)**; **Gama (p. 263)**; **Weibull (p. 265)**
- **Morettin**: **7.4.1 Uniforme (p. 186)**; **7.4.2 Normal (p. 188)**; **7.4.3 Exponencial (p. 193)**

**Atividades**
- [ ] Ler Ross p. 231–267
- [ ] Resolver 5 exercícios de normal e exponencial
- [ ] Padronizar uma variável normal
- [ ] Gerar amostras contínuas em Python
- [ ] Plotar densidades teóricas e histogramas simulados

## Dia 11 — Esperança, covariância, correlação e TLC

**Referências**
- **Ross**: **Cap. 7 — Covariância e correlação (p. 384)**; **Cap. 8 — Teorema do limite central (p. 463)**; **lei fraca (p. 459)**

**Atividades**
- [ ] Ler Ross p. 384–390 e p. 459–472
- [ ] Simular médias amostrais em Python
- [ ] Mostrar o TLC com histogramas
- [ ] Calcular covariância e correlação em um dataset
- [ ] Escrever a intuição do TLC com suas palavras

## Dia 12 — Revisão e simulação

**Referências**
- **Ross**: **Cap. 10 — Simulação (p. 517)**; **transformação inversa (p. 520)**; **rejeição (p. 521)**

**Atividades**
- [ ] Revisar resumos da semana
- [ ] Resolver 6 exercícios mistos
- [ ] Simular distribuições discretas em Python
- [ ] Simular distribuições contínuas em Python
- [ ] Organizar notebook `semana02_probabilidade.ipynb`

---

# Semana 3 — Inferência estatística

## Resumo da semana

| Dia | Tema | Referência principal |
|---|---|---|
| 13 | Introdução à inferência e amostragem | Morettin cap. 10 |
| 14 | Distribuições amostrais | Morettin cap. 10 |
| 15 | Estimação e IC | Morettin cap. 11 |
| 16 | Testes de hipóteses | Morettin cap. 12 |
| 17 | Duas populações | Morettin cap. 13 |
| 18 | Revisão prática | Morettin + Python |

## Dia 13 — Introdução à inferência

**Referências**
- **Morettin**: **Cap. 10 — Introdução à inferência (p. 273)**; **População e Amostra (p. 276)**; **Problemas de Inferência (p. 278)**; **Amostragem Aleatória Simples (p. 284)**

**Atividades**
- [ ] Ler Morettin p. 273–289
- [ ] Escrever diferença entre parâmetro e estatística
- [ ] Escrever diferença entre população e amostra
- [ ] Criar 3 exemplos de problemas de inferência

## Dia 14 — Distribuições amostrais e tamanho de amostra

**Referências**
- **Morettin**: **Distribuição amostral da média (p. 293)**; **da soma (p. 295)**; **de proporção (p. 301)**; **Tamanho de amostra (p. 305)**
- **Ross**: **TLC (p. 463)**

**Atividades**
- [ ] Ler Morettin p. 293–305
- [ ] Simular distribuição amostral em Python
- [ ] Comparar n pequeno e n grande
- [ ] Fazer 4 exercícios de tamanho de amostra

## Dia 15 — Estimação e intervalos de confiança

**Referências**
- **Morettin**: **Cap. 11 — Estimação (p. 308)**; **Propriedades de estimadores (p. 310)**; **Máxima verossimilhança (p. 323)**; **Intervalos de Confiança (p. 329)**; **Erro padrão (p. 334)**

**Atividades**
- [ ] Ler Morettin p. 308–334
- [ ] Fazer 5 exercícios de estimadores
- [ ] Construir IC para média em Python
- [ ] Construir IC para proporção em Python
- [ ] Explicar corretamente o significado de um IC

## Dia 16 — Testes de hipóteses

**Referências**
- **Morettin**: **Cap. 12 — Testes de Hipóteses (p. 344)**; **Procedimento geral (p. 353)**; **Teste para média com variância conhecida (p. 353)**; **Teste para proporção (p. 355)**; **Valor-p (p. 362)**; **Teste para variância (p. 365)**

**Atividades**
- [ ] Ler Morettin p. 344–372
- [ ] Resolver 6 exercícios manuais
- [ ] Fazer teste z/t em Python
- [ ] Fazer teste para proporção em Python
- [ ] Escrever hipótese nula e alternativa em 3 exemplos

## Dia 17 — Inferência para duas populações

**Referências**
- **Morettin**: **Cap. 13 — Introdução (p. 376)**; **Comparação das variâncias (p. 380)**; **Amostras independentes (p. 383)**; **Amostras dependentes (p. 397)**

**Atividades**
- [ ] Ler Morettin p. 376–399
- [ ] Fazer 4 exercícios de comparação de médias
- [ ] Fazer teste para duas amostras independentes em Python
- [ ] Fazer teste pareado em Python
- [ ] Resumir quando usar cada caso

## Dia 18 — Revisão inferencial

**Atividades**
- [ ] Revisar todos os resumos da semana
- [ ] Refazer 4 exercícios sem consulta
- [ ] Criar notebook `semana03_inferencia.ipynb`
- [ ] Resolver um mini caso completo em Python
- [ ] Registrar dúvidas pendentes

---

# Semana 4 — Amostragem, aderência, associação e ANOVA

## Resumo da semana

| Dia | Tema | Referência principal |
|---|---|---|
| 19 | Fundamentos de amostragem | Bolfarine caps. 1 e 2 |
| 20 | AAS e amostragem estratificada | Bolfarine caps. 3 e 4 |
| 21 | Aderência e independência | Morettin cap. 14 |
| 22 | ANOVA | Morettin cap. 15 |
| 23 | Complemento aplicado a negócio | DS p/ Negócios |
| 24 | Revisão e prática | Bolfarine + Morettin |

## Dia 19 — Fundamentos de amostragem

**Referências**
- **Bolfarine & Bussab**: **1.3.3 Variáveis e atributos (p. 5)**; **1.5.3 Planejamento e seleção da amostra (p. 15)**; **1.5.4 Tipos básicos de amostras (p. 16)**; **1.5.5 Classificação de amostras probabilísticas (p. 19)**; **1.5.6 Estimadores e erros amostrais (p. 20)**; **1.5.7 Tamanho da amostra (p. 21)**; **1.5.8 Censo ou amostragem (p. 22)**
- **Bolfarine**: **2.1 População (p. 29)**; **2.2 Amostras (p. 31)**; **2.3 Planejamento amostral (p. 34)**

**Atividades**
- [ ] Ler Bolfarine p. 15–34
- [ ] Fazer resumo dos tipos de amostragem
- [ ] Diferenciar censo e amostragem
- [ ] Montar um exemplo prático de desenho amostral

## Dia 20 — AAS, estratificada e sistemática

**Referências**
- **Bolfarine**: **Cap. 3 — Amostragem aleatória simples (p. 57)**; **3.2.5 Tamanho da amostra (p. 68)**; **3.3.5 Tamanho da amostra sem reposição (p. 79)**; **Cap. 4 — Amostragem estratificada (p. 93)**; **4.3 Alocação proporcional (p. 102)**; **4.3.3 Neyman (p. 104)**; **4.5 Tamanho da amostra (p. 110)**; **7.8 Amostragem sistemática (p. 171)**

**Atividades**
- [ ] Ler Bolfarine p. 57–79 e 93–112
- [ ] Fazer exemplo de AAS em Python
- [ ] Fazer exemplo de amostragem estratificada em Python
- [ ] Comparar alocação proporcional e Neyman
- [ ] Fazer exemplo de amostragem sistemática

## Dia 21 — Aderência, homogeneidade e independência

**Referências**
- **Morettin**: **Cap. 14 — Testes de Aderência (p. 416)**; **Homogeneidade (p. 417)**; **Independência (p. 424)**; **Teste para coeficiente de correlação (p. 426)**

**Atividades**
- [ ] Ler Morettin p. 416–426
- [ ] Resolver 4 exercícios
- [ ] Fazer teste qui-quadrado de aderência em Python
- [ ] Fazer teste de independência em Python
- [ ] Interpretar tabela de contingência

## Dia 22 — ANOVA e comparações entre médias

**Referências**
- **Morettin**: **Cap. 15 — Mais de duas subpopulações (p. 441)**; **Suposições (p. 445)**; **Estimação do modelo (p. 449)**; **Tabela ANOVA (p. 450)**; **Comparações entre médias (p. 455)**; **Teste de homocedasticidade (p. 456)**

**Atividades**
- [ ] Ler Morettin p. 441–456
- [ ] Resolver 4 exercícios de ANOVA
- [ ] Rodar ANOVA em Python com statsmodels
- [ ] Fazer análise visual por boxplots
- [ ] Registrar interpretação da tabela ANOVA

## Dia 23 — Aplicação orientada a negócio

**Referências**
- **Data Science para Negócios**: **Cap. 2 — tarefas de mineração (p. 19)**; **Compreensão do negócio (p. 27)**; **Compreensão dos dados (p. 28)**; **Preparação dos dados (p. 29)**; **Avaliação (p. 31)**

**Atividades**
- [ ] Ler DS para Negócios p. 19–31
- [ ] Escrever um mini caso de negócio
- [ ] Dizer qual desenho amostral usaria
- [ ] Dizer qual teste estatístico usaria
- [ ] Relacionar estatística com decisão

## Dia 24 — Revisão da semana 4

**Atividades**
- [ ] Revisar resumos
- [ ] Refazer 3 exercícios de amostragem
- [ ] Refazer 2 exercícios de ANOVA/qui-quadrado
- [ ] Organizar notebook `semana04_amostragem_testes.ipynb`
- [ ] Subir tudo ao repositório

---

# Semana 5 — Regressão, dados categóricos e multivariada

## Resumo da semana

| Dia | Tema | Referência principal |
|---|---|---|
| 25 | Regressão linear | Morettin cap. 16 |
| 26 | Regressão aplicada em ML | Hands-On cap. 4 |
| 27 | Regressão logística e dados categóricos | Hands-On + DS Negócios |
| 28 | PCA | Mingoti + Hands-On |
| 29 | Clusterização | Mingoti + repo Cibele Russo |
| 30 | Discriminante e revisão | Mingoti |

## Dia 25 — Regressão linear simples

**Referências**
- **Morettin**: **Cap. 16 — Introdução (p. 462)**; **Método dos parâmetros (p. 465)**; **Avaliação do modelo (p. 468)**; **ANOVA (p. 474)**; **Inferência (p. 475)**; **Intervalos (p. 478)**; **Predição (p. 480)**; **Resíduos (p. 482)**
- **Hands-On**: **Cap. 4 — Regressão linear (p. 90)**

**Atividades**
- [ ] Ler Morettin p. 462–482
- [ ] Ler Hands-On p. 90–97
- [ ] Ajustar regressão linear simples em Python
- [ ] Plotar linha ajustada
- [ ] Analisar resíduos
- [ ] Interpretar coeficientes em linguagem simples

## Dia 26 — Regressão linear regularizada

**Referências**
- **Hands-On**: **Cap. 4 — Gradient Descent (p. 93)**; **Curvas de aprendizado (p. 104)**; **Modelos linearmente regularizados (p. 107)**; **Ridge (p. 107)**; **Lasso (p. 109)**; **Elastic Net (p. 111)**

**Atividades**
- [ ] Ler Hands-On p. 93–111
- [ ] Comparar regressão linear, ridge e lasso
- [ ] Fazer gráfico de curva de aprendizado
- [ ] Identificar sinais de underfitting e overfitting
- [ ] Registrar qual modelo ficou melhor

## Dia 27 — Regressão logística e dados categóricos

**Referências**
- **Hands-On**: **Regressão Logística (p. 112)**; **Estimando probabilidades (p. 113)**; **Fronteiras de decisão (p. 114)**; **Softmax (p. 117)**
- **Data Science para Negócios**: **Cap. 4 — Regressão logística (p. 97)**; **Cap. 7 — matriz de confusão (p. 189)**; **Cap. 8 — ROC e AUC (p. 214, 219)**
- **Morettin**: **Cap. 14 — independência e associação (p. 424)**

**Atividades**
- [ ] Ler Hands-On p. 112–117
- [ ] Ler DS para Negócios p. 189 e 214–219
- [ ] Ajustar regressão logística em Python
- [ ] Gerar matriz de confusão
- [ ] Calcular ROC/AUC
- [ ] Interpretar probabilidades previstas

## Dia 28 — PCA

**Referências**
- **Mingoti**: **Cap. 3 — PCA Introdução (p. 57)**; **matriz de covariância (p. 58)**; **matriz de correlação (p. 63)**; **critérios para número de componentes (p. 75)**; **representatividade da variância total (p. 83)**
- **Hands-On**: **Cap. 8 — PCA (p. 169)**; **Preservando a variância (p. 169)**; **Componentes principais (p. 170)**; **Taxa de variância explicada (p. 172)**

**Atividades**
- [ ] Ler Mingoti p. 57–86
- [ ] Ler Hands-On p. 169–174
- [ ] Rodar PCA em Python
- [ ] Fazer gráfico de variância explicada
- [ ] Escolher número de componentes
- [ ] Escrever interpretação dos componentes

## Dia 29 — Clusterização

**Referências**
- **Mingoti**: **Cap. 6 — Análise de Agrupamentos (p. 143)**; **distâncias (p. 144–149)**; **técnicas hierárquicas (p. 152)**; **número de clusters (p. 165)**; **k-means (p. 178)**
- **Hands-On**: **Cap. 9 — Clusterização (p. 181)**; **K-Means (p. 184)**; **DBSCAN (p. 196)**; **misturas gaussianas (p. 200)**
- **Repositório da Cibele Russo**
- https://github.com/cibelerusso/AnaliseMultivariadaEAprendizadoNaoSupervisionado

**Atividades**
- [ ] Ler Mingoti p. 143–178
- [ ] Ler Hands-On p. 181–205
- [ ] Explorar 1 exemplo do repo da Cibele Russo
- [ ] Rodar K-Means em Python
- [ ] Rodar clustering hierárquico
- [ ] Comparar ao menos 2 soluções de cluster

## Dia 30 — Discriminante e revisão multivariada

**Referências**
- **Mingoti**: **Cap. 7 — Introdução (p. 197)**; **construção da regra (p. 200)**; **avaliação do ajuste (p. 209)**; **probabilidade global de acerto (p. 213)**; **ANOVA univariada para seleção de variáveis (p. 224)**

**Atividades**
- [ ] Ler Mingoti p. 197–226
- [ ] Resumir diferença entre regressão logística e discriminante
- [ ] Comparar PCA, cluster e discriminante em uma tabela
- [ ] Organizar notebook `semana05_reg_multivariada.ipynb`
- [ ] Revisar dúvidas pendentes

---

# Semana 6 — Sobrevivência, séries temporais, longitudinais e fechamento

## Resumo da semana

| Dia | Tema | Referência principal |
|---|---|---|
| 31 | Séries temporais | apoio externo + Python |
| 32 | Sobrevivência | apoio externo + Python |
| 33 | Longitudinais | apoio externo + Python |
| 34 | Metodologia científica | apoio institucional |
| 35 | Projeto final aplicado | todos |
| 36 | Fechamento e revisão geral | todos |

## Dia 31 — Séries temporais

**Referências**
- **Hands-On**: previsão de série temporal com RNN apenas como leitura leve — **cap. 15, p. 388–393**
- **statsmodels**: https://www.statsmodels.org/
- **Google Colab**

**Atividades**
- [ ] Estudar tendência, sazonalidade e autocorrelação
- [ ] Baixar uma série temporal simples
- [ ] Plotar a série em Python
- [ ] Calcular ACF/PACF
- [ ] Fazer decomposição simples da série
- [ ] Registrar interpretação

## Dia 32 — Análise de sobrevivência

**Referências**
- **lifelines**: https://lifelines.readthedocs.io/
- material introdutório em português da área de saúde / epidemiologia
- apoio conceitual: censura, Kaplan-Meier, logrank, Cox

**Atividades**
- [ ] Estudar conceitos de censura e tempo até evento
- [ ] Rodar Kaplan-Meier em Python
- [ ] Comparar 2 curvas de sobrevivência
- [ ] Aplicar logrank
- [ ] Ler documentação do lifelines

## Dia 33 — Dados longitudinais

**Referências**
- **statsmodels**: modelos mistos
- materiais complementares de universidades abertas
- Python: `statsmodels` MixedLM

**Atividades**
- [ ] Estudar conceito de medidas repetidas
- [ ] Entender diferença entre longitudinal e transversal
- [ ] Ajustar um modelo misto simples em Python
- [ ] Interpretar efeito fixo e aleatório
- [ ] Escrever 5 linhas de conclusão

## Dia 34 — Metodologia científica

**Referências**
- materiais institucionais de metodologia
- **Data Science para Negócios**: formulação de problema e avaliação
- https://educapes.capes.gov.br/handle/capes/432207

**Atividades**
- [ ] Definir tema de mini-projeto
- [ ] Escrever problema de pesquisa
- [ ] Escrever objetivo geral
- [ ] Escrever objetivos específicos
- [ ] Definir quais métodos estatísticos usará

## Dia 35 — Projeto final aplicado

**Sugestão de projeto**
- análise exploratória + inferência + regressão ou cluster
- dataset do Kaggle, IBGE ou dados próprios

**Atividades**
- [ ] Escolher dataset final
- [ ] Fazer EDA completa
- [ ] Aplicar ao menos 1 teste estatístico
- [ ] Aplicar 1 modelo de regressão, classificação ou cluster
- [ ] Interpretar resultados
- [ ] Escrever mini-relatório

## Dia 36 — Revisão geral e fechamento

**Atividades**
- [ ] Revisar todos os resumos
- [ ] Revisar todos os notebooks
- [ ] Separar tópicos fortes e fracos
- [ ] Criar lista “o que revisar depois”
- [ ] Subir versão final no GitLab/GitHub
- [ ] Planejar transição para o Plano 2 (ML + LLM + agentes)

---

# Organização sugerida do repositório

```text
plano-01-estatistica-para-data-science/
├── README.md
├── semana01/
├── semana02/
├── semana03/
├── semana04/
├── semana05/
├── semana06/
├── notebooks/
├── datasets/
└── resumos/
```

---

# Checklist macro do plano

- [ ] Semana 1 concluída
- [ ] Semana 2 concluída
- [ ] Semana 3 concluída
- [ ] Semana 4 concluída
- [ ] Semana 5 concluída
- [ ] Semana 6 concluída
- [ ] Repositório organizado
- [ ] Notebooks revisados
- [ ] Resumos finais consolidados
- [ ] Pronto para iniciar o Plano 2

---

# Observações finais

- Este plano foi montado com foco em **estatística pesada para Data Science**, não só em apertar botão de biblioteca.
- O objetivo é que você entenda:
  - o conceito estatístico
  - a interpretação
  - a aplicação em Python
  - a conexão com Machine Learning
- O **Hands-On** e o **Data Science para Negócios** entram como ponte entre teoria estatística e prática real.
