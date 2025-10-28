# 📊 Popularidade de Personagens (Marvel vs DC) – Brasil

Este projeto investiga a popularidade de personagens da **Marvel** e da **DC Comics** no Brasil, inspirado na metodologia da pesquisa da USDish, mas adaptado ao nosso contexto.  
O objetivo é responder três perguntas principais:

1. Qual é o **herói mais popular** no Brasil?  
2. Qual é o **vilão mais popular** no Brasil?  
3. Entre **Marvel e DC**, qual editora é mais popular no país?  

O resultado final será uma **página web** com os dados e a reportagem, hospedada no GitHub Pages, além da documentação completa do processo neste repositório.

---

## 🔹 Metodologia

- **Fontes de dados**:  
  - Google Keyword Planner → validação de relevância mínima.  
  - Google Trends → comparação de popularidade relativa.  

- **Configurações no Trends**:  
  - Localidade: Brasil  
  - Período: últimos 12 meses  
  - Categoria: todas  
  - Tipo de busca: pesquisa na web  
  - Critério: **termo de pesquisa** (para garantir comparabilidade)  

- **Métrica consolidada**: cálculo da média dos índices semanais/mensais exportados do Trends.  

---

## 🔹 Escopo da Análise

1. Ranking de super-heróis (Brasil, últimos 12 meses).  
2. Ranking de vilões (mesma metodologia).  
3. Comparação direta Marvel vs DC.  
4. Visualizações:  
   - Mapas por estado (herói/vilão vencedor).  
   - Mapas por estado (editora vencedora).  
   - Gráficos de barras/linhas (ranking consolidado e evolução temporal).  

---

## 🔹 Estrutura do Repositório

```plaintext
📁 popularidade-marvel-dc
│
├── 📁 data_raw/              # Dados brutos exportados (CSV do Trends, Keyword Planner)
├── 📁 data_processed/        # Dados tratados (médias, rankings consolidados)
├── 📁 notebooks/             # Notebooks (Jupyter/Colab) com análises passo a passo
├── 📁 scripts/               # Scripts Python/R (opcional, se migrar além do Excel)
├── 📁 visuals/               # Mapas, gráficos e ícones usados no relatório
├── 📁 docs/                  # Documentação extra (metodologia detalhada, apêndices)
└── README.md                 # Guia principal do projeto

---

## 🔹 Próximos Passos

- [ ] Definir lista final de personagens (heróis e vilões).  
- [ ] Rodar Keyword Planner para validar relevância.  
- [ ] Rodar Google Trends e exportar CSVs.  
- [ ] Calcular médias e consolidar rankings.  
- [ ] Comparar Marvel vs DC diretamente no Trends.  
- [ ] Criar mapas e gráficos.  
- [ ] Montar página web com resultados.  
- [ ] Divulgar o projeto (meta: chegar até o canal **Ei Nerd** 🎯).  

---

✍️ **Autor**: Leandro ([@LeUchoa](https://github.com/LeUchoa))  
📅 **Ano**: 2025
