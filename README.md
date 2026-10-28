# Projeto de Automação para Relatório Executivo Semanal com n8n e IA

### 1️⃣ Descrição do Projeto
Este projeto foi desenvolvido para automatizar a criação e o envio de um briefing executivo semanal para a gestão da agência de marketing digital FlowWorks por meio do n8n[cite: 2]. O fluxo analisa os dados dos projetos e utiliza uma IA para gerar um relatório resumido, enviando a mensagem diretamente no Slack toda a segunda-feira de manhã. 

### 2️⃣ Objetivo
Automatizar a prestação de contas do estado dos projetos, gerando relatórios executivos rápidos para que o gestor saiba o que fazer na semana em apenas 30 segundos de leitura[cite: 2]. O foco é eliminar a visualização de dados crus e destacar apenas o que realmente importa.

### 3️⃣ Funcionalidades
- Processamento de dados de projetos e análise inteligente de estado.
- Identificação automática de projetos com riscos críticos e em alerta.
- Formatação customizada nativa para o Slack utilizando o padrão *mrkdwn* (sem tabelas e com uso moderado de emojis).
- Envio automático do briefing executivo.
- Geração de uma recomendação clara e acionável pela IA sobre a prioridade do dia.

### 4️⃣ Informações analisadas
- Visão geral com o total de projetos ativos e a quantidade em risco.
- Projetos com riscos críticos (ex.: prazos curtos ou baixa percentagem de conclusão).
- Projetos em alerta devido a progresso lento ou prazo próximo.
- Projetos com bom andamento e dentro do prazo.
- Recomendação específica e direcionada, citando o nome do projeto ou cliente.

### 5️⃣ Tecnologias utilizadas
- n8n (Fluxos de automação / Workflows)
- Inteligência Artificial (Modelos LLM)
- Slack (Mensagens e notificações)
- JSON (Estruturação dos dados dos projetos)

### 6️⃣ Benefícios da automação
- Leitura rápida e objetiva, totalmente otimizada para o telemóvel.
- Direcionamento estratégico direto para as prioridades, sem enrolação.
- Redução drástica do trabalho manual de recolha de dados para relatórios.
- Tomada de decisão facilitada por um assistente com tom executivo e direto, simulando um colega experiente que já filtrou as informações.
- Maior controlo sobre o andamento dos clientes e mitigação rápida de atrasos.
