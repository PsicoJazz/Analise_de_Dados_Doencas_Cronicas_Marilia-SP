# Análise de Dados de Saúde Pública: Doenças Crônicas em Marília – SP

## 📌 Sobre o projeto

Este projeto tem como objetivo analisar dados públicos de saúde obtidos por meio do **DATASUS**, utilizando técnicas de mineração de dados, pré-processamento e análise estatística para investigar a ocorrência de doenças relacionadas ao código CID-10 I41 no município de Marília, São Paulo.

A análise parte de dados brutos extraídos de bases públicas de saúde, que passam por etapas de tratamento, organização e preparação para possibilitar a exploração dos dados e a identificação de padrões relevantes.

## 🎯 Objetivos

- Realizar a mineração de dados brutos provenientes do DATASUS.
- Aplicar técnicas de pré-processamento e limpeza de dados utilizando Python e Pandas.
- Organizar e estruturar os dados para análise estatística.
- Explorar a distribuição e a frequência dos registros relacionados ao CID investigado.
- Identificar padrões e tendências que contribuam para a compreensão dos dados de saúde do município de Marília – SP.

## 🛠️ Tecnologias utilizadas

- **Python:** linguagem utilizada no processamento e na análise dos dados.
- **Pandas:** manipulação, limpeza, transformação e organização dos dados.
- **numpy:** calculos com arrays.
- **seaborn:** geração de gráficos.
- **Análise estatística:** exploração dos dados e investigação de padrões.
- **DATASUS:** fonte pública dos dados utilizados no estudo.

## 🔎 Metodologia

O desenvolvimento do projeto foi organizado nas seguintes etapas:

### 1. Extração e mineração dos dados

Obtenção de dados brutos provenientes do DATASUS, com seleção dos registros pertinentes ao município de Marília – SP e ao código CID-10 definido para a investigação.

### 2. Pré-processamento dos dados

Utilização da biblioteca Pandas para preparar a base de dados, incluindo procedimentos de organização, verificação de inconsistências, tratamento de valores ausentes e adequação dos dados para as etapas seguintes, conforme a necessidade identificada durante o processamento.

### 3. Análise exploratória e estatística

Aplicação de técnicas estatísticas para examinar os dados, compreender a distribuição dos registros e investigar possíveis padrões relacionados às ocorrências analisadas.

### 4. Interpretação dos resultados

Análise dos resultados obtidos com o objetivo de compreender as características dos registros investigados e explorar informações relevantes para o estudo da saúde pública local.

## 📊 Resultados esperados

A análise busca contribuir para a compreensão dos dados públicos de saúde de Marília – SP, permitindo:

- Conhecer a distribuição dos registros relacionados ao CID investigado.
- Identificar características relevantes presentes na base de dados.
- Explorar padrões estatísticos que possam orientar novas investigações.
- Demonstrar a aplicação prática de técnicas de Ciência de Dados em informações públicas de saúde.

Os resultados e as conclusões devem ser interpretados considerando a cobertura, a qualidade e as limitações da base utilizada.



## ▶️ Como executar

1. Clone o repositório:

```bash
git clone URL_DO_SEU_REPOSITORIO
```

2. Acesse a pasta do projeto:

```bash
cd analise-dados-datasus
```

3. Instale as dependências:

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

4. Execute o notebook Jupyter ou o script Python responsável pelo processamento e pela análise dos dados.

As bibliotecas instaladas devem ser ajustadas às dependências efetivamente utilizadas no projeto.

## 📚 Fonte dos dados

**DATASUS — Departamento de Informação e Informática do Sistema Único de Saúde**

Portal oficial: [https://datasus.saude.gov.br/](https://datasus.saude.gov.br/)

Os dados utilizados são provenientes de bases públicas de saúde. Sua interpretação deve considerar a metodologia de coleta, a disponibilidade dos registros e as possíveis limitações das informações.

## ⚠️ Considerações

Este projeto possui finalidade acadêmica e exploratória, voltada à aplicação de técnicas de mineração, tratamento e análise estatística de dados.

Os resultados não devem ser interpretados isoladamente como evidência de causalidade ou como estimativa definitiva da prevalência de doenças na população. A interpretação depende das características da base, dos critérios de seleção e dos métodos estatísticos empregados.

## 👨‍💻 Autor

**Daniel Martins Ferreira**

Projeto desenvolvido no contexto de estudos em Ciência de Dados, com foco na aplicação de técnicas de análise de dados públicos de saúde.




