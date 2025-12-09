CESAR SCHOOL & NTT DATA

Cadeira: Projetos — Grupo 3 Água e Esgoto
👨‍🎓 Equipe

Bruno Sottomayor Martin

Bruno José Cavalcanti

Igor Kauã

Vinicius da Cruz

Matheus Connolly

Gabriel Leal

📊 Projeto COMPEDATA

A Compedata é uma solução orientada à análise de dados que tem como objetivo transformar informações brutas em insights valiosos para gestão pública. A partir de dados reais de corte de água, 
consumo e localidades, o projeto identifica padrões, recorrências e comportamentos que podem indicar áreas críticas, tendências preocupantes ou oportunidades de melhoria nos serviços de abastecimento.

Com essas análises, buscamos entregar à prefeitura e órgãos governamentais uma visão clara e fundamentada sobre onde e por que certos problemas estão acontecendo. A partir disso,
gestores podem agir de forma mais estratégica — seja planejando ações preventivas, otimizando recursos, priorizando regiões vulneráveis ou melhorando a comunicação com a população.

A Compedata nasce, portanto, como uma ponte entre dados e decisões, contribuindo para uma gestão pública mais eficiente, inteligente e orientada por evidências.

🏗️ Arquitetura do Pipeline

A solução segue a estrutura clássica Medallion Architecture:

🥉 Bronze

Ingestão das planilhas originais (.csv).

Nenhum tratamento aplicado.

🥈 Silver

Limpeza e padronização das colunas.

Conversão de datas.

Criação de atributos derivados (ano, mês, status, etc.).

🥇 Gold

Tabelas analíticas para dashboards, incluindo:

Cortes por bairro

Cortes por mês

Cortes por ano

Status dos cortes

Ranking Top 10 bairros

📊 Dashboards

Foram geradas visualizações profissionais no Databricks utilizando Plotly, como:

Comparativo anual de cortes efetuados e pendentes

Top 10 bairros com maior número de cortes

Meses com maiores ocorrências por ano

Análises de distribuição e tendências

🎯 Objetivo Final

Fornecer uma visão clara e estruturada sobre o comportamento dos cortes de água ao longo do tempo, identificando padrões, sazonalidade e regiões com maior ocorrência.
