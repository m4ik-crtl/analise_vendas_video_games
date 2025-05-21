# 🎮 Análise de Vendas de Vídeo Games

Este projeto tem como objetivo **analisar dados de vendas de jogos de vídeo game**, com foco em identificar **fatores que influenciam o sucesso de um jogo** em diferentes plataformas e gêneros. A análise considera avaliações de usuários e críticas, ano de lançamento, gênero e desempenho regional.

## 📊 Objetivos

- Analisar o comportamento do mercado de games após 2013.
- Identificar padrões de vendas por plataforma, gênero e região.
- Verificar a relação entre as notas de usuários/críticos e o sucesso de um jogo.
- Realizar testes de hipóteses estatísticas para comparar médias entre grupos.

## 🧪 Metodologia

1. **Importação e limpeza dos dados**
   - Substituição de valores ausentes por `'Unknown'` para evitar o descarte indevido de informações.
   - Conversão de tipos e padronização de nomes.

2. **Filtro temporal**
   - Apenas jogos lançados a partir de **2013** foram considerados, conforme critério de atualidade da análise.

3. **Análise exploratória**
   - Visualização da distribuição de jogos por plataforma e ano.
   - Identificação das plataformas e gêneros mais populares.
   - Avaliação de correlações entre notas e vendas.

4. **Testes de hipótese**
   - Comparação das médias de avaliações dos usuários entre plataformas (ex: XOne vs PC).
   - Comparação das médias de avaliações entre gêneros (ex: Action vs Sports).
   - Avaliação da igualdade de variâncias antes do teste T (`ttest_ind` com ajuste de `equal_var`).

## 📈 Tecnologias utilizadas

- Python
- Bibliotecas: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`

## 📌 Principais descobertas

- Algumas plataformas e gêneros se destacam em vendas, mas não necessariamente em avaliações.
- As médias de avaliação entre plataformas e gêneros apresentam diferenças estatísticas em certos casos.
- A crítica especializada e a avaliação do público nem sempre seguem a mesma tendência.

## 🗂️ Estrutura

- `analise de vendas de video games.ipynb` — Notebook com todo o código e análise comentada.

## ✅ Status

✔️ Projeto finalizado com feedbacks do revisor incorporados, incluindo:
- Tratamento de valores ausentes.
- Filtro por ano de lançamento ≥ 2013.
- Aplicação rigorosa dos testes de hipótese com verificação de variância.

## 🙋‍♂️ Autor

Maikon Silva  
---

