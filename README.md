# Projeto: Análise dos Dados da Polícia Rodoviária Federal de Acidentes nas Rodovias e Posicionamento de Radares

## Entendimento do Negócio

O contexto rodoviário brasileiro, vasto e dinâmico, é marcado por desafios inerentes à segurança viária. Nesse cenário, a Polícia Rodoviária Federal (PRF) desempenha um papel essencial na garantia da ordem e na promoção da segurança nas rodovias federais do país.

### Papel da Polícia Rodoviária Federal (PRF):
A PRF, instituição vinculada ao Ministério da Justiça e Segurança Pública, é responsável pela fiscalização, patrulhamento e policiamento ostensivo nas rodovias federais brasileiras. Seu propósito principal é assegurar a integridade dos usuários das estradas, prevenir acidentes e zelar pela ordem pública em um ambiente rodoviário desafiador.

### Implementação de Radares como Medida de Segurança:
Os radares, dispositivos eletrônicos de monitoramento de velocidade e comportamento veicular, representam uma ferramenta crucial na abordagem preventiva da PRF. Estrategicamente posicionados, esses equipamentos visam não apenas coibir excessos de velocidade, mas também promover uma cultura de respeito às normas de trânsito, contribuindo para a redução de acidentes e suas consequências.

## Conjunto de Dados

### Dados dos acidentes da PRF nas Rodovias 
Os dados de acidentes de trânsito utilizados neste estudo foram coletados no site da Policia Rodoviária Federal em [Dados Abertos da PRF](https://www.gov.br/prf/pt-br/acesso-a-informacao/dados-abertos/dados-abertos-da-prf)
e abrangem o período de janeiro de 2021 a julho de 2023.

### Dados Radares nas Rodovias Federais
Os dados de radares de trânsito nas rodovias federais do Brasil forma coletados em  "Dados.gov.br" do governo federal [Dados Radares](https://dados.gov.br/dados/conjuntos-dados/radar) com atualizaçõ em dezembro de 2023.

## Tecnologias Utilizadas
- Ambiente de Desenvolvimento: Google Colab
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

Na fase de entendimento dos dados, o objetivo é adquirir uma compreensão abrangente do conjunto de dados em questão. Isso inclui identificar suas fontes, entender a estrutura dos dados, examinar as características e os tipos de variáveis presentes e compreender o contexto em que os dados foram coletados. Durante essa etapa, foram incluídos metadados detalhados que descrevem a origem e a composição dos dados, fornecendo informações adicionais para orientar as análises subsequentes. Esta etapa é crucial para orientar as análises subsequentes e garantir que os dados sejam interpretados corretamente.

## Preparação dos Dados

A preparação dos dados envolve o processo de limpeza, transformação e organização dos dados de forma a torná-los adequados para análise. Nesta etapa foram realizados tratamento de valores nulos, modificação de formato de variáveis para garantir consistência nos tipos de dados, padronização de colunas para facilitar a análise e ajustes em colunas para refletir informações mais precisas.

Uma preparação eficaz dos dados é fundamental para garantir a qualidade e a confiabilidade das análises posteriores, pois ajuda a minimizar viéses e inconsistências nos dados, permitindo uma interpretação mais precisa dos resultados.

## Análise Exploratória

A análise exploratória visa investigar os padrões, relações e tendências presentes nos dados. Por meio de técnicas estatísticas e visualizações, busca-se identificar insights relevantes, padrões emergentes e potenciais correlações entre as variáveis.

Durante a análise exploratória, foram realizadas diversas análises, incluindo a distribuição geográfica dos acidentes em um mapa do Brasil, a frequência dos acidentes por rodovia, a avaliação da gravidade dos acidentes e a identificação de áreas de alto risco. Além disso, foi realizada uma análise das proximidades dos acidentes em relação à localização dos radares, permitindo identificar possíveis relações entre a presença de radares e a incidência de acidentes.

Também foi conduzida uma análise temporal dos acidentes para compreender as tendências ao longo do tempo e identificar variações significativas em diferentes períodos.

Essa etapa permitiu uma compreensão mais profunda dos dados, fornecendo insights valiosos para a formulação de hipóteses e a tomada de decisões informadas sobre medidas de segurança viária e políticas de prevenção de acidentes.

## Conclusão e Recomendações

Após uma análise abrangente dos dados relacionados aos acidentes nas rodovias e à presença de radares, fica evidente a necessidade de medidas urgentes para melhorar a segurança viária. Os resultados revelam uma lacuna significativa na infraestrutura de monitoramento, com trechos críticos carecendo de sistemas de radar. Isso ressalta a importância de expandir a cobertura de radares em áreas de alta incidência de acidentes.

Além disso, observa-se uma estabilidade preocupante nos índices de acidentes ao longo do tempo, sem uma diminuição significativa nos números de vítimas. Essa tendência reforça a urgência de implementar medidas eficazes para reduzir a incidência de acidentes nas rodovias.

Diante dessas constatações, propõe-se uma série de medidas para melhorar a segurança viária. Isso inclui a instalação estratégica de radares em áreas com alta concentração de acidentes, a avaliação de locais críticos para identificar padrões de ocorrência, a melhoria da sinalização e conscientização dos motoristas, e o estabelecimento de um sistema contínuo de monitoramento e análise de dados.

Essas propostas visam não apenas controlar a velocidade e desencorajar comportamentos imprudentes, mas também promover uma cultura de segurança nas estradas. É fundamental que as autoridades responsáveis e os órgãos de trânsito atuem de forma proativa na implementação dessas medidas, visando à redução dos acidentes e à preservação de vidas nas rodovias.

## Licença

Este projeto está licenciado sob os termos da [Licença MIT](https://github.com/Suelymessias/Projeto_Analise_PRF/blob/main/LICENSE)

## Contato

Para mais informações ou colaborações, entre em contato através do [e-mail](suelymesssias@gmail.com) 
Você também pode me encontrar no [LinkedIn](https://www.linkedin.com/in/suely-c-messias-analytics/)


