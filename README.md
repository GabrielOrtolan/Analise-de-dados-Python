
# Aplicação Prática de Python na Ciência dos Dados – Parte 2

Este repositório contém a solução da atividade prática proposta na disciplina de Ciência dos Dados, ministrada pelo(a) professor(a) **Sergio Ricardo**.

## 📄 Descrição da Atividade

O objetivo da atividade foi explorar as **características financeiras** de um dataset real com informações de clientes de cartão de crédito, realizando análises estatísticas e visuais com a linguagem Python.

A atividade utilizou o dataset `default_of_credit_card_clients__courseware_version_1_21_19.xls` e exigiu a aplicação de conhecimentos em:

- Manipulação de dados com **Pandas**
- Visualização com **Matplotlib**
- Aplicação de funções com `.apply()`
- Máscaras booleanas e transformações **logarítmicas**

---

## 📊 Exercícios Desenvolvidos

1. Criação de listas com os nomes das colunas financeiras.
2. Análise estatística com `.describe()` das faturas.
3. Visualização das faturas com histogramas em layout 2x3.
4. Análise com `.describe()` das colunas de pagamento.
5. Histogramas dos pagamentos com rotação no eixo X.
6. Máscara booleana para identificar valores iguais a zero.
7. Visualização logarítmica dos pagamentos diferentes de zero.

---

## 📁 Arquivos

- `Aplicacao_Pratica_Python_Ciencia_Dados_FINAL.ipynb`: Notebook Jupyter com toda a solução da atividade, incluindo código, gráficos e análises.
- `default_of_credit_card_clients__courseware_version_1_21_19.xls`: Dataset original da atividade.

---

## 🛠️ Requisitos

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 💡 Observações

O gráfico final do exercício 7 segue exatamente o padrão visual solicitado pelo professor, com uso de `log10` apenas nos valores de pagamento diferentes de zero e layout em grade 2x3.

---

## 📚 Referências

- ARVALHO, A. C. P. L. F. de. *Ciência de dados: fundamentos e aplicações.* LTC, 2024.
- SALDANHA, R. F. et al. *Ciência de dados e big data.* Cadernos de Saúde Coletiva, 2021.
- SARKER, I. H. *Data science and analytics: an overview.* SN Computer Science, 2021.
