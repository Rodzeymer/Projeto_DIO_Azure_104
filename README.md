# Projeto_DIO_Azure_104
Projeto para curso de Azure AZ 104

Primeiramente vamos separar o que é Certificação e Certificado. Apesar de parecer serem sinônimos, Certificação é mais dificil e valioso que Certificado. Certificado atesta que a pessoa acompanhou o evento. Certificação passa por uma avaliação, muitas vezes extensa e detalhada, em que se atesta que o profissional sabe usar a ferramenta se grnades dificuldades.

A certificação AZ-104 - Microsoft Azure Administrator Associate é uma credencial oficial da Microsoft que valida as habilidades necessárias para gerenciar, configurar, proteger e administrar serviços na nuvem Microsoft Azure.

Para que serve a certificação AZ-104?
Valida competências técnicas para administrar serviços do Azure, como identidades, governança, armazenamento, computação, redes virtuais e monitoramento.
Prepara o profissional para implementar e gerenciar a infraestrutura de nuvem de uma organização, trabalhando em conjunto com equipes de segurança, desenvolvimento e DevOps.
Reconhecida globalmente, abre portas para oportunidades de emprego e crescimento na área de cloud computing.
Primeiro, sobre o Azure Entra ID, sistema de autenticação e segurança da Microsoft, que garante proteção aos recursos e acesso às ferramentas da Microsoft, como o Office 360e o próprio Azure.

O Entra ID permite gerênciar as credenciais dos usuários, desde o acesso básico que é gratuito, e usuários P1 e P2, que possuem maior nível de acesso e podem gerenciar grupos de usuários, permitindo gerir os acessos individuais dos usuários somente aos recursos necesários para cada login.

Após acessar a plataforma do Azure é possível fazer suas configurações de várias maneiras, pela área de trabalho disponibilizada pela plataforma, por CLI (Command-Line Interface), pelo ARM (Azure Resource Management).

A plataforma Azure, sendo uma PaaS (Plataform as a Service), disponibiliza muitas aplicações diferentes, começando pelas redes virtuais, que são redes virtuais com acesso a gateways, balanceadores de carga e outros serviços para proteger os acessos e permitir acessos específicos. As redes podem ser localizadas geograficamente para impedir acessos indevidos, com ou sem conexão com outras redes virtuais da mesma administração.

Um serviço de destaque é o de armazenamento, em que se utiliza a solução de BLOBs (Binary Large Objects) em que os dados, estruturados ou não, em nuvem, com possibilidade de configurar níveis de acesso para cada usuário e o tipo de armazenamento conforme frequencia de uso, entre dados quentes (Acesso frequente), dados frios (Pouco acesso) e arquivados, (Nenhum acesso). Com ferramentas de disponibilidade e de recuperação, em que os dados nos servidores Azure pode ter cópias redundantes, backups agendados, cujos discos físicos podem estar dispostos em racks ou até locais físicos diferentes, garantindo uma maior disponibilidade e segurança a falhas físicas e lógicas.

E é isso, um bom resumo do que visto na DIO preparando para a AZ-104, até o momento!

Aqui estão 50 dicas úteis para usar o Microsoft Azure de forma eficiente e otimizada, baseadas nas melhores práticas, recursos e estratégias recomendadas para usuários iniciantes e avançados:

Configuração Inicial e Gestão de Recursos
Avalie as necessidades do seu negócio antes de escolher os serviços do Azure para garantir que atendam às suas demandas específica.
Use o Azure Resource Manager (ARM) para organizar e gerenciar recursos de forma estruturada e eficiente.
Agrupe recursos relacionados em Grupos de Recursos para facilitar o gerenciamento e automação.
Utilize Tags (etiquetas) para categorizar recursos por ambiente, proprietário ou custo, facilitando a identificação e análise de despesas.
Configure backups regulares com Azure Backup para garantir a segurança dos dados.
Implemente estratégias de recuperação de desastres usando Azure Site Recovery.

Otimização de Custos

Reduza o tamanho das Máquinas Virtuais (VMs) com recomendações do Azure Advisor para evitar desperdício.
Utilize Máquinas Virtuais Spot para cargas de trabalho tolerantes a interrupções, como testes e processamento em lote, com descontos significativos.
Habilite o dimensionamento automático (auto-scaling) para ajustar recursos conforme a demanda, evitando custos excessivos.
Adote instâncias reservadas para cargas de trabalho previsíveis e economize até 72% em comparação com instâncias sob demanda.
Monitore custos e uso com Azure Cost Management para evitar surpresas e otimizar gastos.
Defina orçamentos e alertas para controlar despesas e receber notificações antecipadas.

Segurança

Implemente autenticação multifator (MFA) para proteger contas e acessos.
Use criptografia de dados em repouso e em trânsito para garantir a confidencialidade das informações.
Configure políticas de segurança com Azure Security Center para identificar e mitigar ameaças.
Mantenha os sistemas atualizados para evitar vulnerabilidades.
Desenvolvimento e Implantação
Utilize Azure DevOps para gerenciar projetos, configurar pipelines CI/CD e colaborar com equipes.
Explore o Azure App Service para criar, implantar e gerenciar aplicativos web e móveis facilmente.
Automatize tarefas repetitivas com Azure Automation e scripts PowerShell para ganhar eficiência.
Use containers e Kubernetes (AKS) para escalabilidade e gerenciamento eficiente de aplicações.
Implemente testes automatizados para garantir qualidade contínua.

Redes e Infraestrutura

Configure redes virtuais (VNet) para isolar e proteger cargas de trabalho.
Use sub-redes e NSGs (Network Security Groups) para controlar o tráfego de entrada e saída.
Conecte VNets com emparelhamento para comunicação segura entre redes.
Implemente VPN Gateway para conexões seguras entre ambientes locais e Azure.

Banco de Dados e Armazenamento

Configure bancos de dados SQL do Azure para gestão eficiente de dados relacionais.
Utilize o modelo sem servidor (serverless) do SQL Azure para ajuste automático de capacidade e cobrança por consumo.
Implemente Azure Cosmos DB para bancos de dados NoSQL altamente escaláveis.
Use Azure Blob Storage para armazenar grandes volumes de dados não estruturados.
Configure políticas de backup e recuperação para bancos de dados.

Monitoramento e Análise

Use Azure Monitor para coletar, analisar e agir sobre dados de desempenho e uso.
Configure dashboards personalizados para acompanhar métricas importantes.
Integre alertas para notificações em tempo real sobre problemas ou anomalias.
Utilize Azure Log Analytics para análise detalhada de logs.
Aproveite o Microsoft Cost Management com Copilot para insights avançados de custo.

Inteligência Artificial e Machine Learning

Explore os Serviços de IA do Azure para adicionar visão computacional, reconhecimento de fala e análise preditiva aos seus aplicativos.
Use Azure Cognitive Services para incorporar funcionalidades inteligentes sem necessidade de conhecimento profundo em IA.
Implemente Azure Machine Learning para criar, treinar e implantar modelos personalizados.

Suporte e Aprendizado

Escolha o plano de suporte adequado para sua necessidade, garantindo acesso rápido a suporte técnico.
Aproveite webinars, vídeos e tutoriais oficiais para aprender e se atualizar constantemente.
Participe de comunidades e fóruns Microsoft Q&A para tirar dúvidas e compartilhar experiências.
Prepare-se para certificações Azure (como AZ-900) para validar seus conhecimentos e ampliar oportunidades.

Boas Práticas Gerais

Automatize a criação e configuração de recursos com templates ARM para consistência e agilidade.
Implemente políticas de governança com Azure Policy para garantir conformidade.
Realize auditorias regulares de segurança e uso para manter o ambiente saudável.
Planeje a escalabilidade desde o início para evitar gargalos futuros.
Documente suas configurações e processos para facilitar manutenção e treinamentos.
Teste ambientes antes de colocar em produção para evitar surpresas.
Utilize ambientes de desenvolvimento e teste isolados para garantir qualidade.
Mantenha-se atualizado com as novidades do Azure para aproveitar novos recursos e melhorias.
Essas dicas abrangem desde a configuração inicial até a otimização, segurança, desenvolvimento, monitoramento e suporte, fornecendo um guia completo para tirar o máximo proveito do Microsoft Azure em diferentes contextos e níveis de experiência.