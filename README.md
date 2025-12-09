#  CESAR School & NTTDATA  
## 📊 Projeto COMPEDATA  

---

##  Integrantes do Grupo  
| Nome | GitHub |
|------|--------|
| **Bruno Sottomayor Martin** | @brunosm26 |
| **Bruno José Cavalcanti** | @brunodf081 |
| **Igor Kauã** | @igorrizzin |
| **Vinicius da Cruz** | — |
| **Matheus Connolly** | @Connolly-devops |
| **Gabriel Leal** | — |

---

# Introdução ao Projeto

A **Compedata** é uma solução orientada à análise de dados, criada com o objetivo de transformar informações brutas em **insights valiosos para a gestão pública**.  
Utilizando dados reais de **corte de água**, **consumo** e **localidades**, a solução identifica padrões, recorrências e comportamentos que podem indicar:

- áreas críticas,  
- regiões vulneráveis,  
- tendências preocupantes,  
- oportunidades de melhoria na operação e fornecimento.

A partir desses diagnósticos, a prefeitura e órgãos governamentais passam a ter uma visão clara e fundamentada sobre **onde** e **por que** os problemas estão acontecendo. Isso permite:

- ações preventivas,  
- otimização de recursos,  
- priorização de regiões críticas,  
- comunicação mais eficiente com a população.

A Compedata nasce, portanto, como uma ponte entre **dados e decisões**, contribuindo para uma gestão pública **mais inteligente, eficiente e orientada por evidências**.

---

# 🛠️ Arquitetura da Solução

A solução segue a arquitetura **Medallion (Bronze → Silver → Gold)**:

### 🥉 Bronze  
Coleta e armazenamento dos dados brutos (planilhas de corte de água e consumo).

### 🥈 Silver  
Padronização, limpeza, enriquecimento e preparação dos dados.

### 🥇 Gold  
Criação de tabelas analíticas e indicadores usados em dashboards e relatórios.

---

# 📊 Dashboards Criados

Os dashboards foram desenvolvidos no Databricks usando tabelas Gold, com visualizações para:

- Cortes por bairro  
- Cortes por mês  
- Ranking Top 10  
- Análises por status (efetuado vs pendente)  
- Comparação por ano  

Essas visualizações permitem que gestores identifiquem rapidamente **onde estão os maiores problemas** e **qual deve ser a priorização das ações**.

---

#  Tecnologias Utilizadas
- Databricks  
- PySpark  
- Delta Lake  
- Plotly  
- GitHub  

---

#  Estrutura do Repositório
aguas_esgoto_ntt/
├── bronze/
├── silver/
├── gold/
├── notebooks/
└── README.md

yaml
Copiar código

---


Este projeto foi desenvolvido para a cadeira de **Projetos – CESAR School**, em parceria com a **NTT Data**.
