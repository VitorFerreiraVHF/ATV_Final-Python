# Análise de Vendas 2024 - Estudo de Caso

Este projeto é um **dashboard interativo** criado como parte de um estudo acadêmico, desenvolvido para a disciplina ministrada pelo professor **Maurício Júnior**. O objetivo principal é utilizar **Python** e bibliotecas modernas para analisar dados de vendas e criar visualizações dinâmicas que auxiliem na tomada de decisões em um contexto logístico.

---

## 🛠 Tecnologias Utilizadas

- **[Python](https://www.python.org/)**: Linguagem de programação principal utilizada no desenvolvimento.
- **[Dash](https://dash.plotly.com/)**: Framework para criação de dashboards web interativos.
- **[Plotly](https://plotly.com/python/)**: Biblioteca para geração de gráficos dinâmicos e interativos.
- **[Pandas](https://pandas.pydata.org/)**: Biblioteca para manipulação e análise de dados.
- **[Dash Bootstrap Components](https://dash-bootstrap-components.opensource.faculty.ai/)**: Conjunto de componentes estilizados com Bootstrap para melhorar o layout e a experiência do usuário.
- **[GitHub](https://github.com/)**: Plataforma para versionamento e hospedagem do código-fonte e da base de dados.

---

## 📊 Funcionalidades do Dashboard

1. **KPIs (Indicadores-Chave de Desempenho)**:
   - Total de Vendas
   - Total de Ordens de Compra
   - Total de Clientes
   - Total de Lojas Ativas

2. **Filtros Interativos**:
   - Dropdown para selecionar lojas específicas e filtrar os dados exibidos nos gráficos.

3. **Visualizações Gráficas**:
   - **Gráfico de Linhas**: Evolução das vendas ao longo do tempo.
   - **Gráfico de Barras**: Total de vendas por loja.
   - **Gráfico de Pizza**: Proporção de vendas por SKU.
   - **Gráfico de Dispersão**: Relação entre ordens de compra e quantidade vendida.
   - **Histograma**: Distribuição das quantidades vendidas.
   - **Tabela Dinâmica**: Resumo de vendas por loja.

---

## 📂 Estrutura do Projeto

- `Analise-Vendas2024.py`: Arquivo principal do código Python que executa o dashboard.
- `vendas.csv`: Base de dados utilizada, hospedada no GitHub e acessada via URL.
- `README.md`: Documentação explicando o projeto e as tecnologias utilizadas.

---

## ⚙️ Pré-requisitos para Execução

Certifique-se de ter o **Python 3.7+** instalado e as seguintes bibliotecas instaladas:

```bash
pip install dash dash-bootstrap-components pandas plotly
