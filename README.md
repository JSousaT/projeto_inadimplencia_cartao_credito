📊 Data Science em Cartões de Crédito — Previsão, Segmentação e Gestão de Inadimplência

Este projeto demonstra uma abordagem prática de Data Science aplicada com dados de crédito. O objetivo é transformar dados brutos em diagnósticos acionáveis, identificar clientes de maior risco de inadimplência e simular o impacto de soluções concretas, tudo voltado para apoiar a tomada de decisão.


👩‍💻 Sobre mim:
Atuo há anos no departamento financeiro, com análise de indicadores, BI, automação de processos e apoio à decisão em ambientes de negócio. Sou formada em Gestão de TI e Banco de Dados, especializada em Data Science, Big Data e BI.

Nos últimos meses, venho ampliando minha atuação para Data Science, desenvolvendo projetos práticos e focados em gerar valor real, como este caso, que integra análise preditiva, visualização inteligente e recomendações para área de crédito. Meu objetivo é criar soluções que facilitem a vida das pessoas, tragam eficiência operacional e apoiem estratégias de negócio baseadas em dados.


🔎 Descrição do Caso:
A partir de dados públicos do UCI Credit Card Dataset, realizei todo o ciclo analítico:

ETL e EDA: limpeza, transformação e análise exploratória dos dados dos clientes de cartão.

Diagnóstico de Risco: identificação dos perfis de maior risco de inadimplência, cruzando dados financeiros e demográficos.

Machine Learning: construção de modelos de classificação (Regressão Logística, Floresta Aleatória, XGBoost, LightGBM) para prever inadimplência.

Explicabilidade: análise dos principais fatores de risco, usando Feature Importance e SHAP para interpretar as decisões dos modelos.

Simulações e Segmentação: classificação automática dos clientes em faixas de risco (baixo, médio, alto) e simulação do impacto de ações de negócio.

Dashboards em Power BI: visualização interativa dos resultados e recomendações.

Geração de insights e recomendações acionáveis, conectando análise e ação.

✨ Principais Destaques

Diagnóstico visual e acionável: segmentação dos clientes e principais fatores de risco em dashboards práticos.

Integração de técnicas modernas: EDA, feature engineering, ML, explicabilidade e BI em fluxo único e reprodutível.

Simulação de cenários e sugestões de ação: respostas diretas sobre como priorizar contato, renegociar limites e agir de forma proativa.

Automação de relatórios e visualizações, facilitando o uso para área de crédito e gestão.

Estrutura modular e clara, fácil reaproveitamento em outros contextos.


🚀 Como este projeto pode ajudar empresas

* Identifica rapidamente clientes e segmentos de maior risco, direcionando ações onde o retorno é maior.
* Simula o impacto potencial de políticas de crédito e ações proativas.
* Gera análises e visualizações prontas para uso em Power BI, facilitando o trabalho do time financeiro e de crédito.
* Facilita integração entre áreas, tornando recomendações acionáveis e alinhadas ao objetivo do negócio.
* Apoia a redução da inadimplência, retenção de clientes e potencialização de receitas.


📂 Estrutura do Projeto

├── data/                            # Base de dados pública (tratada e original)
├── export/                          # Resultados, predições, explicabilidade (para Power BI)
├── img/                             # Gráficos, prints dos dashboards e outputs
├── PowerBI/                         # Dashboard .pbix pronto para uso
├── 01_EDA_e_Preprocessamento.ipynb  # ETL, EDA e feature engineering
├── 02_Modelagem_ML.ipynb            # Modelagem, comparação e exportação dos melhores modelos
├── 03_Explicabilidade_e_Exportacao.ipynb  # Explicabilidade e outputs para Power BI
└── README.md

🔗 Como rodar o projeto

* Clone este repositório
* Instale as dependências (requirements.txt)
* Coloque as basespública na pasta /data
* Execute os notebooks na ordem indicada (01, 02, 03)
* Importe os arquivos da pasta /export no Power BI, usando o dashboard pronto em /PowerBI
* Explore os dashboards interativos e veja recomendações geradas automaticamente


📊 Power BI

O painel interativo construído no Power BI pode ser acessado e explorado no arquivo:
`/PowerBI/painel_inadimplencia_credito.pbix`

**Dica:** Caso não possua Power BI instalado, utilize a [versão gratuita do Power BI Desktop](https://powerbi.microsoft.com/pt-br/desktop/) para abrir e visualizar o painel.


📈 Resultados e visualizações
A seguir, exemplos dos principais resultados, sempre acompanhados de explicação do significado:

🟪 Matriz de Confusão — Predição de Inadimplência
Como interpretar: Cada célula mostra o número de clientes classificados corretamente ou não pelo modelo (acertos e erros para “Inadimplente” e “Não Inadimplente”).

🟦 Principais Fatores de Risco
Como interpretar: Limite de crédito, proporção paga dos últimos meses e idade aparecem como fatores mais relevantes para inadimplência, segundo o modelo.

🟩 Segmentação Visual — Perfil de Risco
Como interpretar: Visualização dos clientes por faixa etária, limite de crédito, sexo, escolaridade e estado civil, destacando onde o risco está mais concentrado.

🟧 Checklist Visual — Ações Sugeridas
Como interpretar: Para cada faixa de risco, recomendações práticas: revisar limite, contato proativo, renegociação etc.

🛠️ Principais Recomendações

* Aja proativamente sobre clientes de alto risco (probabilidade >80%)
* Revise limites e condições para esse grupo, priorizando renegociação
* Use segmentação para personalizar ações (idade, perfil, limite)
* Automatize monitoramento contínuo com os outputs do modelo


📝 Observações finais
Este projeto é um case prático de portfólio, demonstrando como Data Science pode apoiar o setor financeiro na prevenção à inadimplência, segmentação de risco e aumento da eficiência operacional.
Toda a lógica está documentada, fácil de adaptar para bancos, fintechs e financeiras.
Dados usados são públicos (UCI Credit Card Dataset), prontos para compartilhar, sem restrição.


📫 Contato
• LinkedIn: https://www.linkedin.com/in/jaquelinesousat/