# Jupyter notebooks para bibliometria
Notebooks usados em conjunto com o parsifal para gerar relatórios bibliométricos

## Pipeline

- Exportar resultados das buscas em bibtex
- Importar para o parsifal
- Remover duplicados (funcionalidade parsifal)
- Exportar xls com todo artigos do parsifal
- Executar o notebook _manipular_dataframes.py.ipynb_ com esse arquivo.
  - Outro arquivo chamado _dataframe_only_useful.xls_ será gerado.
- Executar notebook _gerador_gráficos_métricas.ipynb_ com o novo arquivo.
  - Serão criados arquivos eps com os gráficos.
