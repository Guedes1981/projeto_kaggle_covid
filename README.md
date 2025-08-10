# COVID-19 com PostgreSQL: da limpeza SQL ao storytelling analítico

Pipeline SQL (PostgreSQL/pgAdmin) aplicado ao dataset COVID-19 do Kaggle, com tabelas de staging, limpeza/padronização e geração de métricas analíticas (CSVs) usadas em gráficos e insights.

## 📊 Destaques
- **Brasil — pico MM7 (casos):** 77 129 na semana de 2021-06-23.
- **Brasil — pico MM7 (mortes):** 3 124 na semana de 2021-04-09.
- **Ranking per capita — casos:** posição 49/220 (≈ 107 944).
- **Ranking per capita — mortes:** posição 13/220 (≈ 2 461).
- **Timing do 1º pico pós-100 casos:** mediana 119 dias (P25 76, P75 165) em 219 países.

## 📂 Estrutura do repositório

## 🚀 Como reproduzir
1. PostgreSQL ≥ 13 (pgAdmin).
2. Criar schema/tabelas `*_stg` e executar o script completo (Passos 1–7).
3. Exportar os CSVs para `data/processed/`.
4. Rodar o notebook (Kaggle ou local) para gerar gráficos e insights.

## 📈 Gráficos sugeridos
- Séries temporais com **MM7** (casos e mortes) — Brasil.
- **Rankings per capita** (casos/mortes por milhão).
- **Mapa de calor** por continente (evolução semanal).
- **Picos** (linhas de referência e anotações).
- **Comparativo** Brasil × vizinhos × média continental.

## ⚠️ Limitações
- Subnotificação e diferenças de testagem/registro por país.
- Atrasos e revisões (*backfills*) nas séries.
- Métricas per capita dependem da qualidade da coluna de população.

## 📚 Créditos
- Dados: Kaggle — COVID-19 Data.
- Autor: Murilo Guedes.
- Licença do código: MIT.

