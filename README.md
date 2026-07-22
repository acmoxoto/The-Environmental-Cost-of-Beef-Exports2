# Dados socioambientais da Amazônia Legal

Repositório para organização de bases relacionadas à Amazônia Legal, com foco em exportações de carne, queimadas e cobertura e uso da terra.

## Arquivos

- `data/EXP_ANUAL_carne(2).xlsx`: dados anuais de exportação de carne.
- `data/historico_regiao_amazonia_legal queimadas(2).xlsx`: histórico de queimadas na Amazônia Legal.
- `data/TABELA-GERAL-MAPBIOMAS-COL8.0-AMAZONIA_LEGAL-1(2).xlsx`: tabela geral do MapBiomas, Coleção 8.0, para a Amazônia Legal.
- `scripts/inspecionar_planilhas.py`: lista planilhas, dimensões, colunas e primeiras linhas.
- `docs/metadados_arquivos.json`: metadados básicos extraídos das pastas de trabalho.

## Estrutura

```text
repositorio_amazonia_dados/
├── data/
├── docs/
├── scripts/
├── .gitignore
├── README.md
└── requirements.txt
```

## Uso local

```bash
python -m venv .venv
```

No Windows:

```bash
.venv\Scripts\activate
```

No Linux ou macOS:

```bash
source .venv/bin/activate
```

Depois:

```bash
pip install -r requirements.txt
python scripts/inspecionar_planilhas.py
```

## Publicação no GitHub

1. Crie um repositório vazio no GitHub.
2. Extraia este pacote.
3. Abra o terminal dentro da pasta `repositorio_amazonia_dados`.
4. Execute:

```bash
git init
git add .
git commit -m "Adiciona bases socioambientais da Amazônia Legal"
git branch -M main
git remote add origin URL_DO_REPOSITORIO
git push -u origin main
```

## Cuidados acadêmicos

Antes da divulgação pública, confira a fonte, a autoria, a licença, a metodologia, o período de cobertura, as unidades, os códigos geográficos e as regras de citação de cada base.

Os arquivos foram preservados em seu formato original. Este repositório não atribui licença aos dados de terceiros.
