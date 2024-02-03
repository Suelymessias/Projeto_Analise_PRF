# Projeto: Análise dos Dados da Polícia Rodoviária Federal de Acidentes nas Rodovias e Posicionamento de Radares

## Entendimento do Negócio

O contexto rodoviário brasileiro, vasto e dinâmico, é marcado por desafios inerentes à segurança viária. Nesse cenário, a Polícia Rodoviária Federal (PRF) desempenha um papel essencial na garantia da ordem e na promoção da segurança nas rodovias federais do país.

### Papel da Polícia Rodoviária Federal (PRF):
A PRF, instituição vinculada ao Ministério da Justiça e Segurança Pública, é responsável pela fiscalização, patrulhamento e policiamento ostensivo nas rodovias federais brasileiras. Seu propósito principal é assegurar a integridade dos usuários das estradas, prevenir acidentes e zelar pela ordem pública em um ambiente rodoviário desafiador.

### Implementação de Radares como Medida de Segurança:
Os radares, dispositivos eletrônicos de monitoramento de velocidade e comportamento veicular, representam uma ferramenta crucial na abordagem preventiva da PRF. Estrategicamente posicionados, esses equipamentos visam não apenas coibir excessos de velocidade, mas também promover uma cultura de respeito às normas de trânsito, contribuindo para a redução de acidentes e suas consequências.

## Conjunto de Dados

### Dados dos acidentes da PRF nas Rodovias 
Os dados de acidentes de trânsito utilizados neste estudo foram coletados no site da Policia Rodoviária Federal em [Dados Abertos da PRF]( https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-da-prf)
e abrangem o período de janeiro de 2021 a julho de 2023.

### Dados Radares nas Rodovias Federais
Os dados de radares de trânsito nas rodovias federais do Brasil forma coletados em  "Dados.gov.br" do governo federal [Dados Radares](https://dados.gov.br/dados/conjuntos-dados/radar) com atualizaçõ em dezembro de 2023.

## Tecnologias Utilizadas
- **Ambiente de Desenvolvimento: Google Colab**
- Linguagem de Programação: Python

### Bibliotecas Python:
- NumPy: Para computação numérica e operações matemáticas eficientes.
- Pandas: Para manipulação e análise de dados.
- Matplotlib: Para visualização de dados estática em gráficos e plots.
- Seaborn: Para visualização de dados estatísticos e aprimoramento estético dos gráficos.
- Folium: Para visualização de dados geoespaciais e criação de mapas interativos.
- GeoPandas: Para análise e manipulação de dados geoespaciais no formato de dataframes.

## Objetivo da Análise

Este projeto tem como objetivo analisar as causas dos acidentes nas rodovias do Brasil e se há relação com o posicionamento dos radares.

- Analisar a eficácia dos radares e o impacto dos radares na redução de acidentes.

- Identificar rodovias com maior concentração de acidentes e avaliar a presença de radares nesses locais.

- Avaliar a gravidade dos acidentes ocorridos em diferentes trechos das rodovias.

- Conduzir uma análise estatística para determinar a correlação entre a presença de radares e a diminuição na frequência de acidentes.

- Conduzir uma analise temporal nos anos abordados.

- Considerar não apenas os aspectos de segurança, mas também as implicações econômicas decorrentes dos acidentes.

## Entendimento dos Daods

Na fase de entendimento dos dados, o objetivo é adquirir uma compreensão abrangente do conjunto de dados em questão. Isso inclui identificar suas fontes, entender a estrutura dos dados, examinar as características e os tipos de variáveis presentes e compreender o contexto em que os dados foram coletados. Esta etapa é crucial para orientar as análises subsequentes e garantir que os dados sejam interpretados corretamente.
