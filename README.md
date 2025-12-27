# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 27 de Dezembro de 2025

Empresa: Abstergo Industries

Responsável: Wallace Gabriel da Silva

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Wallace Gabriel da Silva. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1:

- **Amazon EC2 Auto Scaling**
- Foco: Otimização de recursos computacionais
- Descrição de caso de uso: Implementação de escalabilidade automática para os servidores que hospedam o sistema de gestão de estoque da farmácia. Durante horários de pico (manhã e final de tarde), o sistema escala automaticamente para atender a demanda, e reduz a capacidade nos períodos de baixa utilização, gerando economia de até 40% nos custos de infraestrutura.

Etapa 2:

- **Amazon S3 Intelligent-Tiering**
- Foco: Armazenamento inteligente de dados
- Descrição de caso de uso: Migração dos documentos fiscais, notas de entrada/saída e relatórios de vendas para o S3 com camadas de armazenamento inteligente. Documentos acessados frequentemente permanecem em camada de acesso rápido, enquanto arquivos históricos são movidos automaticamente para camadas mais econômicas, reduzindo custos de armazenamento em até 60%.

Etapa 3:

- **Amazon RDS (Instâncias Reservadas)**
- Foco: Redução de custos com banco de dados
- Descrição de caso de uso: Substituição do banco de dados on-premises pelo Amazon RDS com instâncias reservadas por 1 ano. O banco de dados gerencia informações de medicamentos, clientes, fornecedores e vendas. Com a migração, eliminou-se custos de manutenção de hardware e licenciamento, além de obter desconto de até 72% em relação às instâncias sob demanda.

## Conclusão

A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução significativa de custos operacionais, maior disponibilidade dos sistemas, eliminação de gastos com manutenção de infraestrutura física e otimização do uso de recursos de TI*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

- [Manual de configuração do Auto Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html)
- [Política de ciclo de vida do S3](https://docs.aws.amazon.com/AmazonS3/latest/userguide/intelligent-tiering.html)
- [Documentação de migração do banco de dados para RDS](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/Welcome.html)
- [Planilha comparativa de custos (antes e depois)](https://calculator.aws/#/)

Assinatura do Responsável pelo Projeto:

**Wallace Gabriel da Silva**
