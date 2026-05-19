# Análise Exploratória de Dados — Produtividade de Funcionários

Repositório destinado ao trabalho/prova de **Fundamentos em Ciência de Dados**, com foco em análise exploratória de dados usando Python.

## Objetivo

Investigar, de forma exploratória, quais características dos funcionários estão associadas a níveis mais altos ou mais baixos de produtividade.

A variável `Produtividade` é transformada em uma variável binária:

- **Alta produtividade**: funcionários com produtividade acima da mediana;
- **Baixa produtividade**: funcionários com produtividade abaixo ou igual à mediana.

## Base de dados

A base utilizada é `DadoseDecisoes.csv`, disponibilizada no enunciado da atividade.

As variáveis analisadas incluem informações demográficas, profissionais e de produtividade dos funcionários, como idade, gênero, departamento, salário, horas trabalhadas, satisfação, tempo de empresa, cursos realizados e regime de home office.

## Análises realizadas

O notebook contém:

1. Carregamento e inspeção inicial da base;
2. Classificação dos funcionários em produtividade alta ou baixa;
3. Identificação dos tipos estatísticos das variáveis;
4. Tabelas de frequência para variáveis qualitativas;
5. Medidas descritivas para variáveis quantitativas;
6. Histogramas, boxplots, gráficos de barras e gráficos de dispersão;
7. Tabelas resumo comparando produtividade binária com as demais variáveis;
8. Discussão exploratória das associações observadas;
9. Limitações da análise e possíveis análises confirmatórias.

## Como executar no Google Colab

1. Abra o arquivo `notebooks/analise_exploratoria_dados_produtividade.ipynb` no Google Colab.
2. Faça upload do arquivo `data/DadoseDecisoes.csv` ou ajuste o caminho do arquivo no notebook.
3. Execute as células em ordem.

## Como executar localmente

Crie um ambiente virtual e instale as dependências:

```bash
python -m venv .venv
source .venv/bin/activate  # Linux/Mac
# .venv\Scripts\activate   # Windows

pip install -r requirements.txt
```

Depois, abra o notebook:

```bash
jupyter notebook notebooks/analise_exploratoria_dados_produtividade.ipynb
```

## Principais ferramentas utilizadas

- Python
- pandas
- matplotlib
- seaborn
- numpy
- Jupyter Notebook / Google Colab

## Observação metodológica

As conclusões apresentadas são de natureza **exploratória**. Portanto, associações observadas nos gráficos e tabelas não devem ser interpretadas como evidência causal nem como significância estatística. Para uma etapa confirmatória, seriam necessárias análises estatísticas adicionais adequadas ao tipo das variáveis e ao objetivo da investigação.
