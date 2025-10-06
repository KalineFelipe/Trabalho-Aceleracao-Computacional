# Trabalho de Análise de Dados – COVID e Foodpanda

Autor: Kaline de Almeida Felipe
Disciplina: Introdução aos Softwares Estatísticos – 2025.1
Universidade: UFPB – Centro de Ciências Exatas e da Natureza

## Descrição
Este projeto foi desenvolvido como parte da 3 nota da disciplina **Introdução aos Softwares Estatísticos 2025.1** da UFPB.  
Tem como objetivo demonstrar a utilização das bibliotecas **Matplotlib**, **Plotnine** e **Numba** no Python, comparando gráficos e acelerando cálculos numéricos.

O trabalho apresenta análises de dois conjuntos de dados, extraidos do Datasets Kaggle:

1. **Post-COVID Conditions Dataset** – informações sobre condições pós-COVID por país, incluindo sintomas mais frequentes.
2. **Foodpanda Delivery Dataset** – informações sobre pedidos de Foodpanda por cidade, permitindo visualização de tendências de entrega.

---

## Estrutura do Projeto
- `Post-COVID_Conditions.csv`: Conjunto de dados sobre condições pós-COVID.
- `Foodpanda Analysis Dataset.csv`: Conjunto de dados sobre pedidos de Foodpanda.
- `notebook.ipynb`: Notebook contendo todo o código, gráficos e análises.
- `sintomas_pos_covid_plotnine.png`: Exemplo de gráfico gerado com Plotnine.

---

## Tecnologias Utilizadas
- Python 3.x  
- Pandas  
- Matplotlib  
- Plotnine  
- Numba  

---

## Como Executar
Instale as dependências necessárias:
```bash
pip install pandas matplotlib plotnine numba

## Abra o notebook no Jupyter:
jupyter notebook notebook.ipynb

## Execute as células para reproduzir gráficos, análises e testes de desempenho com Numba.

## Exemplos de Análises

Gráficos Matplotlib: Top 10 países com mais casos pós-COVID e total de pedidos por cidade.

Gráficos Plotnine: Sintomas mais frequentes relatados e comparações com cores e temas automáticos.

Numba: Aceleração do cálculo de π (Pi) via método de Monte Carlo, demonstrando ganhos de performance.

## Referências

MCKINNEY, Wes. Python for Data Analysis: Data Wrangling with pandas, NumPy, and Jupyter. 3. ed., Sebastopol: O’Reilly Media, 2022.

MÜLLER, M. Numba Essentials. Birmingham: Packt Publishing, 2015.

YLMAZ, Asel. Post-COVID Conditions Dataset. Kaggle, 2023. Disponível em: link
.

IMRAN, Ayesha. Foodpanda Order and Delivery Trends Dataset. Kaggle, 2023. Disponível em: link
.

Plotnine Documentation

Matplotlib Documentation

