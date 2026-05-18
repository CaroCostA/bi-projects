# 📊 Portfólio — Análise de Dados & Business Intelligence

> Projetos desenvolvidos com foco em análise de KPIs, experimentação (A/B Testing), storytelling com dados e visualização — alinhados às práticas de squads de crescimento em empresas de tecnologia.

---

## 🗂️ Projetos

### 01 · Dashboard de KPIs de Delivery
**Ferramentas:** Looker Studio · Google Sheets  
**Contexto:** Dashboard executivo com KPIs operacionais de uma plataforma de delivery — GMV, pedidos, NPS, taxa de cancelamento e ROI de cupons — com filtros interativos por cidade, canal e período.  
**Destaques:**
- Campos calculados: ROI de cupom, % usuários recorrentes, taxa de sucesso
- Correlação identificada: tempo de entrega < 36min → NPS +4 pontos acima da média
- Oportunidade mapeada: categoria Japonês tem ROI de cupom 2,3x maior que Fast Food

🔗 [Ver Dashboard](https://datastudio.google.com/reporting/c6034863-760e-4c03-bb0c-5fe3d92dbf19)

---

### 02 · Análise de Teste A/B — Impacto de Cupom Progressivo no GMV
**Ferramentas:** SQL (BigQuery) · Estatística  
**Contexto:** Análise completa de experimento controlado comparando modelo de cupom flat (controle) vs cupom progressivo (variante) em 100.000 usuários por 4 semanas.  
**Destaques:**
- Cálculo de uplift, z-score e significância estatística (95%)
- Segmentação por tipo de usuário: novo, recorrente, em risco
- Análise temporal para detectar efeito de novidade
- Recomendação de rollout gradual com KPI de guarda

📂 [Ver SQL](./projeto2_teste_ab.sql)

---

### 03 · Análise de Cohort — Retenção de Usuários
**Ferramentas:** Python · Pandas · Matplotlib  
**Contexto:** Análise de retenção por cohort de aquisição — identifica em qual semana os usuários têm maior churn e qual canal de aquisição retém melhor.  
**Destaques:**
- Heatmap de retenção por cohort semanal
- Canal orgânico retém 2x mais que canal pago no D30
- Identificação do "momento aha": 3º pedido = +60% de probabilidade de retenção

📂 [Ver Notebook](./projeto3_cohort_retencao.ipynb)

---

### 04 · Portfólio Web
**Ferramentas:** HTML · CSS · GitHub Pages  
**Contexto:** Este portfólio — desenvolvido e hospedado no GitHub Pages.

---

## 🛠️ Stack

| Categoria | Ferramentas |
|---|---|
| Consulta & Transformação | SQL (BigQuery, PostgreSQL) |
| Visualização | Looker Studio, Power BI, Tableau |
| Análise | Python (Pandas, NumPy, Matplotlib) |
| Experimentação | A/B Testing, Estatística (z-test, t-test) |
| Versionamento | Git, GitHub |

---

## 📬 Contato

**[Seu Nome]**  
[linkedin.com/in/seuperfil](https://linkedin.com)  
[seuemail@gmail.com](mailto:seuemail@gmail.com)
