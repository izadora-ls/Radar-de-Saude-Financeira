# Radar-de-Saude-Financeira
Projeto de análise de dados de ponta a ponta usando as demonstrações financeiras públicas de empresas listadas na bolsa.
O fluxo vai do dado bruto ao dashboard: Python → SQL → Excel → Power BI.

🎯 Problema de negócio

Quais empresas de um setor estão financeiramente saudáveis, quais estão se deteriorando e por quê?
Perguntas que o projeto responde:

- Quais empresas têm as melhores e as piores margens dentro do setor?
- A receita está crescendo mais rápido que a dívida?
- Quais empresas tiveram piora nos indicadores por períodos seguidos?
- Como o endividamento se comporta quando os juros sobem?


​📑​ Arquitetura do projeto

Os dados brutos da CVM são tratados em Python com pandas (limpeza, padronização, indicadores e EDA), depois armazenados e modelados em um banco relacional com SQL, que permite consultas analíticas e views. Dali, os dados alimentam o Excel, para validação dos números e resumo executivo, e o Power BI, para a criação do modelo de dados, das medidas em DAX e do dashboard.
