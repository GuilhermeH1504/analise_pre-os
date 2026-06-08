# Projeto PS5 Price Scraper

Este projeto reúne scrapers em Python para coletar preços de PS5 na Amazon Brasil e no Mercado Livre, consolidar os resultados e manter um histórico simples de preços.

## Arquivos principais

- `analise.ipynb` — notebook de análise de dados e visualização
- `main.py` — script principal que executa os scrapers e salva resultados consolidados
- `mercado.py` — scraper do Mercado Livre usando Playwright
- `dados.py` — funções de limpeza, normalização e gravação de dados
- `automacao.py` — scraper da Amazon usando Playwright
- `ps5_consolidado.json` / `ps5_consolidado.csv` — saída consolidada gerada pelo `main.py`
- `historico_precos.csv` — histórico acumulado de preços

## Como usar

1. Instale as dependências:

```bash
python -m pip install -r requirements.txt
python -m playwright install
```

2. Execute o script principal:

```bash
python main.py
```

3. Os resultados serão salvos em:

- `ps5_consolidado.json`
- `ps5_consolidado.csv`
- `historico_precos.csv`

