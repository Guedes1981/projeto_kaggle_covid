# 📊 Projeto COVID-19 — Análise SQL + Python

Este projeto apresenta **insights visuais e estatísticos** sobre a pandemia de COVID-19, a partir de consultas SQL (PostgreSQL) aplicadas a dados originais do Kaggle, exportando **34 tabelas derivadas (CSV)** para análise e visualização com Python.

## 📁 Estrutura do projeto

```
projeto_kaggle_covid/
  ├── data/
  │   ├── raw/            # Dados originais do Kaggle
  │   └── processed/      # 34 CSVs processados
  ├── notebooks/
  │   └── covid_insights_publish.ipynb  # Notebook oficial de análise
  ├── charts/             # Gráficos gerados automaticamente
  ├── reports/
  │   └── INSIGHTS.md     # Storytelling com índice de gráficos
  ├── requirements.txt    # Dependências Python
  └── README.md           # Este arquivo
```

## 🗂 Dataset original

- Fonte: [COVID-19 Dataset — Kaggle](https://www.kaggle.com/)
- **Observação:** os dados originais (pasta `data/raw/`) não são versionados no GitHub devido ao tamanho/licença.

## 🚀 Como reproduzir localmente

### 1️⃣ Clonar o repositório
```bash
git clone <URL_DO_SEU_REPO>.git
cd projeto_kaggle_covid
```

### 2️⃣ Criar e ativar ambiente virtual
**Windows (PowerShell):**
```powershell
py -m venv .venv
.venv\Scripts\Activate.ps1
```

**Mac/Linux (bash/zsh):**
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 3️⃣ Instalar dependências
```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### 4️⃣ Executar o notebook
- Abra `notebooks/covid_insights_publish.ipynb` no VS Code ou Jupyter.
- Selecione o **kernel** do ambiente virtual `.venv`.
- Execute todas as células (**Run All**).

**Resultados esperados:**
- PNGs gerados em `charts/`
- Arquivo `reports/INSIGHTS.md` atualizado
- Gráficos exibidos inline no notebook

## 📈 Exemplos de gráficos

*(Abaixo, insira exemplos reais da pasta `charts/`)*

![Exemplo 1](charts/exemplo1.png)
![Exemplo 2](charts/exemplo2.png)

## 📜 Storytelling

O arquivo [`reports/INSIGHTS.md`](reports/INSIGHTS.md) contém:
- Índice de gráficos
- Links para cada visualização
- Observações gerais sobre os resultados

## 🛠 Tecnologias utilizadas
- **SQL** (PostgreSQL) — consultas e agregações
- **Python** 3.x
  - pandas
  - matplotlib
  - numpy
- **Jupyter Notebook**
- **VS Code**

## 🌐 Publicação no Kaggle
Este notebook foi adaptado para rodar diretamente no **Kaggle Notebooks**, bastando:
- Criar um novo Kernel no Kaggle
- Fazer upload de `covid_insights_publish.ipynb`
- Adicionar como *Input Dataset* a pasta `data/processed`

## 📄 Licença
Este projeto está licenciado sob a licença MIT — veja o arquivo LICENSE para mais detalhes.
