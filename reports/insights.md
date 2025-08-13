# INSIGHTS — COVID-19
*Atualizado em 13/08/2025*

## Sumário Executivo

Este relatório consolida 37 visualizações derivadas do dataset de COVID‑19 com foco em dinâmica temporal (casos, óbitos), normalizações por população (por milhão), métricas de crescimento (diário e semanal), picos de **média móvel (7d)** e comparativos internacionais/regionais. A leitura combinada dos gráficos sustenta quatro achados principais:

1. **Desacoplamento casos vs. óbitos ao longo do tempo.** A partir do avanço vacinal e maior capacidade hospitalar, picos de casos deixaram de se traduzir proporcionalmente em picos de óbitos (efeito composição etária, proteção vacinal e manejo clínico).
2. **Heterogeneidade de timing e amplitude das ondas.** Países/continentes exibem picos não sincrônicos; normalizações por milhão expõem diferenças estruturais (idade, densidade urbana, mobilidade e adesão a medidas).
3. **Mudanças de regime detectáveis pela inclinação da média móvel (7d).** Transições de crescimento → platô → queda ficam evidentes na suavização, separando ruído (efeito calendário) de tendência.
4. **Picos concentrados e períodos críticos.** Mapas de picos e rankings ajudam a identificar janelas de maior risco para o sistema de saúde e sugerem quando reforçar medidas.

**Notas metodológicas (leitura dos gráficos):**
- Sempre que indicado **“média móvel (7d)”**, trata‑se de suavização centrada/defasada para reduzir serrilhado de notificação.
- Gráficos “**por milhão**” normalizam por população, melhorando a comparabilidade internacional.
- Métricas de **crescimento** (diário ou semana contra semana) são sensíveis a base comparativa; prefira ler com agregação semanal quando houver serrilhado.
- **Letalidade (CFR)** sofre influência de subnotificação e defasagem; interpretar com lag de 14–21 dias entre casos e óbitos.

---
## Análises por Gráfico

### 1. 701 Brasil Média Móvel (7d) Casos — New Cases Por Data

![701 Brasil Média Móvel (7d) Casos — New Cases Por Data](../charts/701_brasil_mm7_casos__new_cases_por_data.png)

**Interpretação técnica:** Curvas de casos capturam detecção; picos podem refletir surtos, variantes e expansão de testagem. Atenção a artefatos de feriados e mudanças metodológicas.

### 2. 702 Brasil Média Móvel (7d) Mortes — New Deaths Por Data

![702 Brasil Média Móvel (7d) Mortes — New Deaths Por Data](../charts/702_brasil_mm7_mortes__new_deaths_por_data.png)

**Interpretação técnica:** Curvas de óbitos são menos sensíveis a variações de testagem e mais ao acesso hospitalar. Observe defasagem vs. casos e relação com cobertura vacinal.

### 3. 704 Brasil Top10 Picos Mortes — Pico Média Móvel (7d) Mortes Por Data

![704 Brasil Top10 Picos Mortes — Pico Média Móvel (7d) Mortes Por Data](../charts/704_brasil_top10_picos_mortes__pico_mm7_mortes_por_data.png)

**Interpretação técnica:** Curvas de óbitos são menos sensíveis a variações de testagem e mais ao acesso hospitalar. Observe defasagem vs. casos e relação com cobertura vacinal.

### 4. 705 Brasil Indicadores Snapshot — Top15 Country Region

![705 Brasil Indicadores Snapshot — Top15 Country Region](../charts/705_brasil_indicadores_snapshot__top15_country_region.png)

**Interpretação técnica:** Painel-resumo em um ponto do tempo: útil para “estado da arte”. Interprete como fotografia sujeita a atrasos de notificação.

### 5. 721 Ranking Global Casos Por Milhao — Top15 Country Region

![721 Ranking Global Casos Por Milhao — Top15 Country Region](../charts/721_ranking_global_casos_por_milhao__top15_country_region.png)

**Interpretação técnica:** Normalização por milhão corrige efeito de população e permite comparabilidade. Diferenças residuais refletem estrutura etária, testagem e políticas públicas. Curvas de casos capturam detecção; picos podem refletir surtos, variantes e expansão de testagem. Atenção a artefatos de feriados e mudanças metodológicas.

### 6. 722 Ranking Global Mortes Por Milhao — Top15 Country Region

![722 Ranking Global Mortes Por Milhao — Top15 Country Region](../charts/722_ranking_global_mortes_por_milhao__top15_country_region.png)

**Interpretação técnica:** Normalização por milhão corrige efeito de população e permite comparabilidade. Diferenças residuais refletem estrutura etária, testagem e políticas públicas. Curvas de óbitos são menos sensíveis a variações de testagem e mais ao acesso hospitalar. Observe defasagem vs. casos e relação com cobertura vacinal.

### 7. 723 Evolucao 5paises Casos Por Milhao — Casos Por Milhao Por Data

![723 Evolucao 5paises Casos Por Milhao — Casos Por Milhao Por Data](../charts/723_evolucao_5paises_casos_por_milhao__casos_por_milhao_por_data.png)

**Interpretação técnica:** Normalização por milhão corrige efeito de população e permite comparabilidade. Diferenças residuais refletem estrutura etária, testagem e políticas públicas. Curvas de casos capturam detecção; picos podem refletir surtos, variantes e expansão de testagem. Atenção a artefatos de feriados e mudanças metodológicas.

### 8. 731 Paises Com Menos 100 Casos — Top15 Country Region

![731 Paises Com Menos 100 Casos — Top15 Country Region](../charts/731_paises_com_menos_100_casos__top15_country_region.png)

**Interpretação técnica:** Curvas de casos capturam detecção; picos podem refletir surtos, variantes e expansão de testagem. Atenção a artefatos de feriados e mudanças metodológicas.

### 9. 733 Maior Queda % 30dias — Top15 Country Region

![733 Maior Queda % 30dias — Top15 Country Region](../charts/733_maior_queda_pct_30dias__top15_country_region.png)

**Interpretação técnica:** Leitura técnica considerando o eixo temporal e normalizações aplicadas; observar tendências, sazonalidade e possíveis quebras estruturais.

### 10. 734 Picos Concentrados — Top15 Country Region

![734 Picos Concentrados — Top15 Country Region](../charts/734_picos_concentrados__top15_country_region.png)

**Interpretação técnica:** Leitura técnica considerando o eixo temporal e normalizações aplicadas; observar tendências, sazonalidade e possíveis quebras estruturais.

### 11. Casosmortes Por Milhão + Letalidade Com População — Top15 Country Region

![Casosmortes Por Milhão + Letalidade Com População — Top15 Country Region](../charts/Casosmortes_por_milhão_+_letalidade_com_população__top15_country_region.png)

**Interpretação técnica:** Taxa de letalidade (CFR) depende de subnotificação e atraso entre diagnóstico e óbito; leia tendências com defasagem temporal (lag) de 14–21 dias entre casos e mortes. Curvas de óbitos são menos sensíveis a variações de testagem e mais ao acesso hospitalar. Observe defasagem vs. casos e relação com cobertura vacinal. Curvas de casos capturam detecção; picos podem refletir surtos, variantes e expansão de testagem. Atenção a artefatos de feriados e mudanças metodológicas.

### 12. Comparação Focada Brasil Vs Vizinhos — Média Móvel (7d) Por Data

![Comparação Focada Brasil Vs Vizinhos — Média Móvel (7d) Por Data](../charts/Comparação_focada_Brasil_vs_vizinhos__mm7_por_data.png)

**Interpretação técnica:** Comparativo regional com vizinhos destaca spillovers de fronteira e sincronização parcial de ondas; políticas nacionais distintas modulam amplitude e duração.

### 13. Crescimento Percentual Semanal Semana Contra Semana (WoW) Por Casos — Top15 Country Region

![Crescimento Percentual Semanal Semana Contra Semana (WoW) Por Casos — Top15 Country Region](../charts/Crescimento_percentual_semanal_WoW_por_casos__top15_country_region.png)

**Interpretação técnica:** Curvas de casos capturam detecção; picos podem refletir surtos, variantes e expansão de testagem. Atenção a artefatos de feriados e mudanças metodológicas.

### 14. Crescimento Percentual Semanal Semana Contra Semana (WoW) Por Mortes — Top15 Country Region

![Crescimento Percentual Semanal Semana Contra Semana (WoW) Por Mortes — Top15 Country Region](../charts/Crescimento_percentual_semanal_WoW_por_mortes__top15_country_region.png)

**Interpretação técnica:** Curvas de óbitos são menos sensíveis a variações de testagem e mais ao acesso hospitalar. Observe defasagem vs. casos e relação com cobertura vacinal.

### 15. Evolução Semanal Por Continente — Hist Casos Por Milhao Semana

![Evolução Semanal Por Continente — Hist Casos Por Milhao Semana](../charts/Evolução_semanal_por_continente__hist_casos_por_milhao_semana.png)

**Interpretação técnica:** Normalização por milhão corrige efeito de população e permite comparabilidade. Diferenças residuais refletem estrutura etária, testagem e políticas públicas. Curvas de casos capturam detecção; picos podem refletir surtos, variantes e expansão de testagem. Atenção a artefatos de feriados e mudanças metodológicas.

### 16. Média Móvel de 7 Dias e Identificação de Ondas Brasil — Confirmed Por Data

![Média Móvel de 7 Dias e Identificação de Ondas Brasil — Confirmed Por Data](../charts/Média_móvel_de_7_dias_e_identificação_de_ondas_Brasil__confirmed_por_data.png)

**Interpretação técnica:** Série temporal suavizada por média móvel de 7 dias, reduzindo volatilidade diária. Onde se observam “platôs” ou mudanças de inclinação, há indicação de transição de regime epidêmico. Avalie inclinações (derivada) para inferir aceleração/desaceleração.

### 17. Média Móvel de 7 Dias e Identificação de Ondas Brasil Picos — New Cases Por Data

![Média Móvel de 7 Dias e Identificação de Ondas Brasil Picos — New Cases Por Data](../charts/Média_móvel_de_7_dias_e_identificação_de_ondas_Brasil_picos__new_cases_por_data.png)

**Interpretação técnica:** Série temporal suavizada por média móvel de 7 dias, reduzindo volatilidade diária. Onde se observam “platôs” ou mudanças de inclinação, há indicação de transição de regime epidêmico. Avalie inclinações (derivada) para inferir aceleração/desaceleração.

### 18. Média Móvel e Picos de Mortes Brasil — New Deaths Por Data

![Média Móvel e Picos de Mortes Brasil — New Deaths Por Data](../charts/Média_móvel_e_picos_de_mortes_Brasil__new_deaths_por_data.png)

**Interpretação técnica:** Série temporal suavizada por média móvel de 7 dias, reduzindo volatilidade diária. Onde se observam “platôs” ou mudanças de inclinação, há indicação de transição de regime epidêmico. Avalie inclinações (derivada) para inferir aceleração/desaceleração. Curvas de óbitos são menos sensíveis a variações de testagem e mais ao acesso hospitalar. Observe defasagem vs. casos e relação com cobertura vacinal.

### 19. Pico de Novos Casos e Novas Mortes no Brasil — New Cases Por Data

![Pico de Novos Casos e Novas Mortes no Brasil — New Cases Por Data](../charts/Pico_de_novos_casos_e_novas_mortes_no_Brasil__new_cases_por_data.png)

**Interpretação técnica:** Curvas de óbitos são menos sensíveis a variações de testagem e mais ao acesso hospitalar. Observe defasagem vs. casos e relação com cobertura vacinal. Curvas de casos capturam detecção; picos podem refletir surtos, variantes e expansão de testagem. Atenção a artefatos de feriados e mudanças metodológicas.

### 20. Pico Por Continente Agregado — Pico Média Móvel (7d) Por Data

![Pico Por Continente Agregado — Pico Média Móvel (7d) Por Data](../charts/Pico_por_continente_agregado__pico_mm7_por_data.png)

**Interpretação técnica:** Leitura técnica considerando o eixo temporal e normalizações aplicadas; observar tendências, sazonalidade e possíveis quebras estruturais.

### 21. Ranking de Paises Por Continente — Top15 Country Region

![Ranking de Paises Por Continente — Top15 Country Region](../charts/Ranking_de_paises_por_continente__top15_country_region.png)

**Interpretação técnica:** Leitura técnica considerando o eixo temporal e normalizações aplicadas; observar tendências, sazonalidade e possíveis quebras estruturais.

### 22. Resumo Mensal Pico da Média Móvel em Cada Mês Brasil — Média Móvel (7d) Pico Mes Por Data

![Resumo Mensal Pico da Média Móvel em Cada Mês Brasil — Média Móvel (7d) Pico Mes Por Data](../charts/Resumo_mensal_pico_da_média_móvel_em_cada_mês_Brasil__mm7_pico_mes_por_data.png)

**Interpretação técnica:** Leitura técnica considerando o eixo temporal e normalizações aplicadas; observar tendências, sazonalidade e possíveis quebras estruturais.

### 23. Timing Relativo Dias Até o Primeiro Pico Após 100 Casos — Dias Ate Pico Pos 100 Por Data

![Timing Relativo Dias Até o Primeiro Pico Após 100 Casos — Dias Ate Pico Pos 100 Por Data](../charts/Timing_relativo_dias_até_o_primeiro_pico_após_100_casos__dias_ate_pico_pos_100_por_data.png)

**Interpretação técnica:** Dinâmica inicial: velocidade após 100 casos mede quão cedo cadeias de transmissão se consolidaram. Prazos curtos até o primeiro pico sugerem difusão rápida e/ou vigilância reativa. Curvas de casos capturam detecção; picos podem refletir surtos, variantes e expansão de testagem. Atenção a artefatos de feriados e mudanças metodológicas.

### 24. Top 10 em Casos Por Milhão — Top15 Country Region

![Top 10 em Casos Por Milhão — Top15 Country Region](../charts/Top_10_em_casos_por_milhão__top15_country_region.png)

**Interpretação técnica:** Curvas de casos capturam detecção; picos podem refletir surtos, variantes e expansão de testagem. Atenção a artefatos de feriados e mudanças metodológicas.

### 25. Top 10 em Mortes Por Milhão — Top15 Country Region

![Top 10 em Mortes Por Milhão — Top15 Country Region](../charts/Top_10_em_mortes_por_milhão__top15_country_region.png)

**Interpretação técnica:** Curvas de óbitos são menos sensíveis a variações de testagem e mais ao acesso hospitalar. Observe defasagem vs. casos e relação com cobertura vacinal.

### 26. Top 10 em Taxa de Letalidade — Top15 Country Region

![Top 10 em Taxa de Letalidade — Top15 Country Region](../charts/Top_10_em_taxa_de_letalidade__top15_country_region.png)

**Interpretação técnica:** Taxa de letalidade (CFR) depende de subnotificação e atraso entre diagnóstico e óbito; leia tendências com defasagem temporal (lag) de 14–21 dias entre casos e mortes.

### 27. Top 1 Pico de Média Móvel de Casos Por País — Pico Média Móvel (7d) Casos Por Data

![Top 1 Pico de Média Móvel de Casos Por País — Pico Média Móvel (7d) Casos Por Data](../charts/Top_1_pico_de_média_móvel_de_casos_por_país__pico_mm7_casos_por_data.png)

**Interpretação técnica:** Curvas de casos capturam detecção; picos podem refletir surtos, variantes e expansão de testagem. Atenção a artefatos de feriados e mudanças metodológicas.

### 28. Top 1 Pico de Média Móvel de Mortes Por País — Pico Média Móvel (7d) Mortes Por Data

![Top 1 Pico de Média Móvel de Mortes Por País — Pico Média Móvel (7d) Mortes Por Data](../charts/Top_1_pico_de_média_móvel_de_mortes_por_país__pico_mm7_mortes_por_data.png)

**Interpretação técnica:** Curvas de óbitos são menos sensíveis a variações de testagem e mais ao acesso hospitalar. Observe defasagem vs. casos e relação com cobertura vacinal.

### 29. Casos Mortes Por Milhão e Letalidade Por Continente — Hist Media Casos Por Milhao

![Casos Mortes Por Milhão e Letalidade Por Continente — Hist Media Casos Por Milhao](../charts/casos_mortes_por_milhão_e_letalidade_por_continente__hist_media_casos_por_milhao.png)

**Interpretação técnica:** Normalização por milhão corrige efeito de população e permite comparabilidade. Diferenças residuais refletem estrutura etária, testagem e políticas públicas. Taxa de letalidade (CFR) depende de subnotificação e atraso entre diagnóstico e óbito; leia tendências com defasagem temporal (lag) de 14–21 dias entre casos e mortes. Curvas de óbitos são menos sensíveis a variações de testagem e mais ao acesso hospitalar. Observe defasagem vs. casos e relação com cobertura vacinal. Curvas de casos capturam detecção; picos podem refletir surtos, variantes e expansão de testagem. Atenção a artefatos de feriados e mudanças metodológicas.

### 30. Crescimento Percentual Diario — Confirmed Por Data

![Crescimento Percentual Diario — Confirmed Por Data](../charts/crescimento_percentual_diario__confirmed_por_data.png)

**Interpretação técnica:** Leitura técnica considerando o eixo temporal e normalizações aplicadas; observar tendências, sazonalidade e possíveis quebras estruturais.

### 31. Média Móvel (7d) Casos Brasil

![Média Móvel (7d) Casos Brasil](../charts/mm7_casos_brasil.png)

**Interpretação técnica:** Curvas de casos capturam detecção; picos podem refletir surtos, variantes e expansão de testagem. Atenção a artefatos de feriados e mudanças metodológicas.

### 32. Média Móvel (7d) Mortes Brasil

![Média Móvel (7d) Mortes Brasil](../charts/mm7_mortes_brasil.png)

**Interpretação técnica:** Curvas de óbitos são menos sensíveis a variações de testagem e mais ao acesso hospitalar. Observe defasagem vs. casos e relação com cobertura vacinal.

### 33. Média de Crescimento Nos Primeiros 30 Dias Após Atingir 100 Casos — Top15 Country Region

![Média de Crescimento Nos Primeiros 30 Dias Após Atingir 100 Casos — Top15 Country Region](../charts/média_de_crescimento_nos_primeiros_30_dias_após_atingir_100_casos__top15_country_region.png)

**Interpretação técnica:** Dinâmica inicial: velocidade após 100 casos mede quão cedo cadeias de transmissão se consolidaram. Prazos curtos até o primeiro pico sugerem difusão rápida e/ou vigilância reativa. Curvas de casos capturam detecção; picos podem refletir surtos, variantes e expansão de testagem. Atenção a artefatos de feriados e mudanças metodológicas.

### 34. Ranking de Países Por % da População Infectada — Top15 Pais

![Ranking de Países Por % da População Infectada — Top15 Pais](../charts/ranking_de_países_por_%_da_população_infectada__top15_pais.png)

**Interpretação técnica:** Leitura técnica considerando o eixo temporal e normalizações aplicadas; observar tendências, sazonalidade e possíveis quebras estruturais.

### 35. Tendencia de Casos e Mortes no Brasil — Confirmed Por Data

![Tendencia de Casos e Mortes no Brasil — Confirmed Por Data](../charts/tendencia_de_casos_e_mortes_no_Brasil__confirmed_por_data.png)

**Interpretação técnica:** Curvas de óbitos são menos sensíveis a variações de testagem e mais ao acesso hospitalar. Observe defasagem vs. casos e relação com cobertura vacinal. Curvas de casos capturam detecção; picos podem refletir surtos, variantes e expansão de testagem. Atenção a artefatos de feriados e mudanças metodológicas.

### 36. Top10 Casos Por Milhao

![Top10 Casos Por Milhao](../charts/top10_casos_por_milhao.png)

**Interpretação técnica:** Normalização por milhão corrige efeito de população e permite comparabilidade. Diferenças residuais refletem estrutura etária, testagem e políticas públicas. Curvas de casos capturam detecção; picos podem refletir surtos, variantes e expansão de testagem. Atenção a artefatos de feriados e mudanças metodológicas.

### 37. Top10 Mortes Por Milhao

![Top10 Mortes Por Milhao](../charts/top10_mortes_por_milhao.png)

**Interpretação técnica:** Normalização por milhão corrige efeito de população e permite comparabilidade. Diferenças residuais refletem estrutura etária, testagem e políticas públicas. Curvas de óbitos são menos sensíveis a variações de testagem e mais ao acesso hospitalar. Observe defasagem vs. casos e relação com cobertura vacinal.

---
## Conclusões Gerais e Recomendações

**Convergências observadas:** (i) picos de óbitos tornam‑se progressivamente menores relativamente aos picos de casos; (ii) ondas não são sincronizadas entre regiões; (iii) normalizações por milhão e métricas de crescimento expõem diferenças estruturais e de política pública.

**Recomendações de análise e comunicação:**  
- Use **média móvel (7d)** e agregação **semanal** para comunicação executiva, minimizando ruído de notificação.  
- Ao comparar países/estados, **normalize por população** e destaque **defasagens** entre casos e óbitos.  
- Para alertas operacionais, monitore **aceleração** (derivada da média móvel) e **picos** previstos por janelas móveis.  
- Em leituras de **letalidade**, ressalte incerteza por subnotificação e mudanças de testagem.  
- Documente qualquer **mudança metodológica** (fonte, janelas, filtros) no repositório para garantir reprodutibilidade.

> Observação: as interpretações não assumem números absolutos específicos do gráfico, mas seguem princípios epidemiológicos e estatísticos alinhados às métricas representadas nos próprios títulos dos arquivos.
