# planejamento-demanda-analise
Análise de Planejamento de Demanda: Simulação e Otimização com Dados de Vendas

# 📦 Análise de Planejamento de Demanda

Este projeto simula e analisa dados de vendas e estoque para apoiar decisões de planejamento de demanda em um cenário B2B, inspirado em boas práticas de BI e Ciência de Dados aplicadas ao setor de varejo.

## 🎯 Objetivo
Ajudar a área de Planejamento de Demanda a:
- Identificar padrões de vendas
- Antecipar rupturas de estoque
- Definir níveis ótimos de segurança
- Otimizar o abastecimento com base em previsões e sazonalidade

## 🧰 Ferramentas e Tecnologias
- **Python (Pandas, Matplotlib, Seaborn)**
- **SQL (simulado em SQLite)**
- **Power BI (dashboard interativo)**
- **DBT + Airflow (conceitual no pipeline)**
- **GCP (simulação de uso via BigQuery e Cloud Storage)**

## 🧪 Pipeline de Análise

1. **Extração:** Dados de vendas simulados via SQL
2. **Transformação:** Limpeza, agregações e cálculo de indicadores
3. **Visualização:** Power BI e gráficos Python
4. **Insights:** Regras para tomada de decisão

## 📊 Indicadores Calculados
- Ruptura (%) = (Demanda - Estoque) / Demanda
- Lead Time médio (dias)
- Cobertura de estoque (dias)
- Demanda média por SKU
- Vendas por canal (B2B vs B2C)

## 🖥️ Dashboard
![Dashboard Preview](./imagens/preview_dashboard.png)

## 🚀 Como Executar

```bash
git clone https://github.com/seuusuario/planejamento-demanda-analise.git
cd planejamento-demanda-analise
pip install -r requirements.txt
jupyter notebook notebooks/analise_planejamento_demanda.ipynb
