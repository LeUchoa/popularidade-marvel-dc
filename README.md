# 📊 Popularidade de Personagens (Marvel vs DC) – Brasil

Este projeto investiga a popularidade de personagens da **Marvel** e da **DC Comics** no Brasil, inspirado na metodologia da pesquisa da USDish, mas adaptado ao nosso contexto.  
O objetivo é responder três perguntas principais:

1. Qual é o **herói mais popular** no Brasil?  
2. Qual é o **vilão mais popular** no Brasil?  
3. Entre **Marvel e DC**, qual editora é mais popular no país?  

O resultado final será uma **página web** com os dados e a reportagem, hospedada no GitHub Pages, além da documentação completa do processo neste repositório.

---

## 🔹 Motivação

Sou fã de quadrinhos desde sempre, com uma queda maior pela Marvel, mas sempre gostei da rivalidade com a DC.  
A ideia deste projeto surgiu após assistir a um vídeo do canal **Ei Nerd**, onde o Peter comentava a pesquisa da USDish sobre popularidade de heróis nos EUA e levantava a dúvida de como seria no Brasil.  
Além de responder a essa questão, um dos objetivos pessoais é também compartilhar os resultados com a comunidade nerd brasileira — quem sabe até chegar ao Peter do Ei Nerd 🎯.

---

## 🔹 Metodologia

- **Fontes de dados**:  
  - Google Keyword Planner → validação de relevância mínima.  
  - Google Trends → comparação de popularidade relativa.  

- **Configurações no Trends**:  
  - Localidade: Brasil  
  - Período: **01/01/2024 a 31/12/2024**  
  - Categoria: todas  
  - Tipo de busca: pesquisa na web  
  - Critério: **termo de pesquisa** (para garantir comparabilidade)  

- **Métrica consolidada**: cálculo da média dos índices semanais/mensais exportados do Trends.  

---

## 🔹 Escopo da Análise

1. Ranking de super-heróis (Brasil, ano de 2024).  
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

## 📚 Inspirações

- [Marvel vs. DC: Quem prevalece no seu estado? (USDish)](https://www.usdish.com/news/blog/marvel-vs-dc-your-states-favorite-comics)  
- [Marvel vs DC: qual companhia é mais popular? (Canaltech)](https://canaltech.com.br/entretenimento/marvel-vs-dc-qual-companhia-e-mais-popular-pesquisa-responde-a-essa-pergunta-183758/)  
- [OFICIAL - DC É MELHOR QUE MARVEL (Ei Nerd, YouTube)](https://youtu.be/bSuNck0P6T0?si=03TyLVHHKO3DoBYX)  

---

✍️ **Autor**: Leandro ([@LeUchoa](https://github.com/LeUchoa))  
📅 **Ano**: 2025
