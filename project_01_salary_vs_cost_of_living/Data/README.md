# Projeto 01 — Salary vs Cost of Living

## Contexto
Salários elevados nem sempre significam melhor qualidade de vida.  
Este projeto tem como objetivo analisar salários médios na área de tecnologia
em diferentes países e ajustá-los pelo custo de vida, buscando estimar
o poder de compra relativo.

A análise foi conduzida com dados reais, utilizando Python, Pandas
e Jupyter Notebook.

---

## Objetivos da Análise
- Comparar salários médios em tecnologia entre países
- Avaliar o impacto do custo de vida sobre o salário nominal
- Estimar o poder de compra relativo por país
- Demonstrar integração de múltiplas fontes de dados

---

## Fontes de Dados
- **Global Tech Salary Dataset** — dados salariais globais na área de tecnologia
- **Cost of Living Index by Country (2024)** — índice de custo de vida por país

Ambos os datasets foram obtidos a partir da plataforma Kaggle.

---

## Metodologia
1. Exploração inicial dos dados salariais
2. Definição de critério mínimo de amostra (≥ 50 registros por país)
3. Cálculo de salários médios por país
4. Padronização dos identificadores de país (códigos ISO)
5. Integração dos dados de salário e custo de vida
6. Cálculo de uma métrica de poder de compra:
   
poder_de_compra = salario_em_USD / indice_de_custo_de_vida

yaml
Copiar código

7. Comparação e interpretação dos resultados

Países com baixo número de observações foram analisados separadamente,
com ressalvas quanto à robustez estatística.

---

## Principais Resultados
- Estados Unidos e Canadá apresentam os maiores salários médios nominais
- Ao ajustar pelo custo de vida, o Canadá apresentou o maior poder de compra médio
- Salários mais altos não garantem necessariamente melhor poder de compra
- Países com menor salário nominal tendem a manter poder de compra inferior,
mesmo com custo de vida mais baixo

---

## Limitações
- A análise considera médias, não a distribuição completa dos salários
- O índice de custo de vida é uma métrica relativa e não representa gastos individuais
- Diferenças regionais dentro de um mesmo país não foram consideradas

---

## Ferramentas Utilizadas
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## Estrutura do Projeto
project_01_salary_vs_cost_of_living/
├── data/
│ ├── Global_Tech_Salary.txt
│ └── Cost_of_Living_Index_by_Country_2024.csv
├── notebooks/
│ └── projeto1_mediasalarial_custodevida.ipynb
└── README.md

yaml
Copiar código

---

## Conclusão
Este projeto demonstra a importância de analisar salários em conjunto com
indicadores econômicos complementares. Ajustar o salário pelo custo de vida
permite uma visão mais realista do poder de compra e reforça que valores
nominais isolados podem ser enganosos.
