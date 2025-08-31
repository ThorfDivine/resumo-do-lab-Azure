# resumo-do-lab-Azure

Guia Prático de Microsoft Azure

Este repositório reúne resumos, anotações e dicas sobre o uso da Microsoft Azure, com foco na criação de instâncias de banco de dados e máquinas virtuais, servindo como material de apoio para estudos e futuras implementações.

1. Conceitos Fundamentais

Nuvem Pública, Privada e Híbrida:

Pública: recursos totalmente gerenciados por provedores como Azure, AWS ou Google Cloud.

Privada: infraestrutura exclusiva da empresa, maior controle, mas mais custo e manutenção.

Híbrida: combina nuvem pública e privada, oferecendo flexibilidade e escalabilidade.

Modelos de Serviço:

IaaS (Infrastructure as a Service): permite criar máquinas virtuais, redes e storage sob demanda.

PaaS (Platform as a Service): fornece ambiente pronto para desenvolvimento, sem se preocupar com infraestrutura.

SaaS (Software as a Service): aplicações prontas, como Office 365 ou Dynamics 365.

CapEx vs OpEx:

CapEx (Capital Expenditure): investimento em infraestrutura própria, alto custo inicial.

OpEx (Operational Expenditure): pagamento baseado no uso, reduz riscos e aumenta flexibilidade.

2. Criação de Máquinas Virtuais na Azure

Escolha da região: influencia latência, disponibilidade e custo.

Tipo de imagem: Windows Server, Ubuntu, Debian, entre outros.

Tamanho da VM: define CPU, memória e armazenamento.

Rede e segurança: configuração de portas, grupos de segurança e firewalls.

Escalabilidade: integração com balanceadores de carga, storage e backups automáticos.

Dicas:

Sempre revisar limites de uso gratuitos antes de criar a VM.

Use tags para organizar recursos no portal Azure.

Teste conexões com RDP/SSH antes de instalar aplicações.

3. Criação de Instâncias de Banco de Dados na Azure

Tipos de serviços: Azure SQL Database, MySQL, PostgreSQL.

Configuração básica: escolha de versão, tamanho e escalabilidade.

Segurança: firewall, autenticação, backup automático e criptografia.

Monitoramento: métricas de desempenho e alertas configuráveis no portal Azure.

Dicas:

Prefira escalabilidade automática para suportar picos de acesso.

Sempre configure backup e ponto de restauração.

Teste queries e conexões antes de colocar em produção.

4. Boas Práticas Gerais

Planeje a arquitetura antes de criar recursos.

Use nomes claros e padronizados para VMs, bancos e redes.

Habilite logs e monitoramento para auditoria e manutenção.

Documente todas as configurações no próprio repositório, servindo de referência para projetos futuros.

Explore integrações com Azure DevOps e outros serviços para automatizar deploy e backups.

5. Finalidade e Aplicações

Aprender a criar e gerenciar recursos na Azure não é apenas uma questão técnica. Esse conhecimento permite:

Reduzir custos e complexidade de infraestrutura.

Garantir alta disponibilidade e segurança para aplicações e dados.

Desenvolver habilidades fundamentais para projetos em nuvem, DevOps e soluções corporativas.

Este repositório serve como guia rápido e material de estudo, consolidando conceitos teóricos e práticas recomendadas para quem deseja avançar no universo da computação em nuvem com a Microsoft Azure.
