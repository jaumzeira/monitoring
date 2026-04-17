# monitoring
📊 Monitoring Analyst Challenge - Cloudwalk

Este repositório contém a resolução técnica para o desafio de monitoramento. O projeto evolui de uma análise exploratória via SQL para a construção de uma arquitetura de observabilidade em tempo real.

🚀 Estrutura do Projeto

/desafio-1: Focado em análise de dados, filtros de negócio e consultas SQL para identificação de padrões de transações.

/desafio-2: Implementação de um pipeline de monitoramento contínuo:

Ingestão: Scripts Python para processamento de arquivos CSV e persistência em banco de dados relacional.

Inteligência: Queries SQL utilizando Window Functions para cálculo de Z-Score dinâmico (desvio padrão).

Observabilidade: Dashboard no Grafana para detecção visual de anomalias.

Alertas: Template de notificação ativa integrado via Webhook para o Discord.


🛠️ Tecnologias e Ferramentas

Linguagens: Python, SQL (SQLite).

Inteligência Artificial: Gemini Pro (utilizado intensivamente para suporte à arquitetura, lógica estatística e automação).

Visualização: Grafana (Dashboards e Alerting).

Comunicação: Discord Webhooks.


🧠 Aprendizados e Diferenciais


O maior valor deste desafio não foi apenas o código, mas o processo de resolução:

Curva de Aprendizado: Foi meu primeiro contato prático com o Grafana, exigindo uma imersão rápida em conceitos de observabilidade e métricas de saúde de operação.

Estatística Aplicada: Substituí limites fixos por uma lógica de Z-Score > 3.0, permitindo que o sistema se adapte ao volume de transações de forma inteligente, evitando falsos positivos.

Uso de IA: Este projeto testou os limites da tecnologia. Pela primeira vez, a complexidade técnica e a profundidade das consultas me levaram a atingir o limite de uso do Gemini Pro, demonstrando um fluxo de trabalho de alta intensidade e colaboração homem-máquina.


📄 Apresentação Completa

Para uma visão estratégica das decisões de arquitetura e prints dos resultados (Grafana/Discord), acesse o arquivo: Monitoring analyst test.pdf.
