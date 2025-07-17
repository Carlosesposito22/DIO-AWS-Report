# RELATÓRIO DE IMPLANTAÇÃO DE SERVICOS AWS

Data: 16 de julho de 2025

Empresa: Abstergo Industries

Responsável: Carlos Eduardo Espósito

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Carlos Eduardo Espósito. O objetivo do projeto foi elencar 3 serviços da AWS, com a finalidade de realizar diminuicoes de custos imediatos.

## Descrição do Projeto
O Projeto foi dividido em 3 etapas, com foco na adoção de serviços escaláveis da AWS que eliminem a necessidade de investimentos infraestrutura física.

Fase 1: Plataforma de Processamento Adaptável e Econômica
- *NOME DA SOLUÇÃO:* Amazon Elastic Compute Cloud (EC2).
- *OBJETIVO PRINCIPAL:* Oferecer capacidade de computação virtual altamente adaptável a situação e com custo otimizado.
- *DESCRIÇÃO DO CENÁRIO DE USO:* Para hospedar os sistemas cruciais da distribuidora, empregamos o EC2, combinado com sua funcionalidade de Auto Scaling. Isso permite um ajuste dinâmico da capacidade computacional de acordo com as flutuações da demanda. A utilização de Instâncias Spot (Oportunas), que proporcionam até 90% de economia comparadas aos preços sob demanda, resultou em uma redução drástica dos gastos com infraestrutura de servidores.

Fase 2: Armazenamento Resiliente e de Custo Acessível
- *NOME DA SOLUÇÃO:* Amazon Simple Storage Service (S3).
- *OBJETIVO PRINCIPAL:* Prover um serviço de armazenamento de dados com elevada durabilidade, baixo custo e modular.
- *DESCRIÇÃO DO CENÁRIO DE USO:* Substituímos os servidores de arquivos locais por coleções de armazenamento no Amazon S3, com controle de versionamento. Documentos fiscais, imagens de produtos e registros de transações agora são armazenados de forma segura, beneficiando-se da extrema durabilidade e um custo muito mais vantajoso em comparação com a hospedagem em centros de dados tradicionais.

Fase 3: Automação Reativa de Processos (Serverless)
- *NOME DA SOLUÇÃO:* AWS Lambda.
- *OBJETIVO PRINCIPAL:* Execução de código sem a necessidade de gerenciar ou provisionar servidores (abordagem Serverless).
- *DESCRIÇÃO DO CENÁRIO DE USO:* Otimizamos tarefas repetitivas e essenciais, como a emissão de alertas de baixo estoque, a geração de relatórios financeiros detalhados, através de funções Lambda. Essas funções são ativadas apenas quando necessário, ou seja, sob demanda. Como não há cobrança por tempo ocioso, o uso do Lambda elimina o desperdício de recursos e, simultaneamente, reduz o tempo dedicado ao desenvolvimento e à manutenção dos sistemas, aumentando a eficiência operacional.

## Conclusão
A integração dessas soluções AWS na Abstergo Industries trará uma série de vantagens estratégicas:
- Otimização Financeira: Projeção de economias significativas nos custos com servidores e armazenamento (potencialmente até 60%), pela transição de infraestrutura legada para modelos de nuvem escaláveis.
- Produtividade Aprimorada: Automação de fluxos de trabalho que antes eram manuais, resultando em menor tempo e custo operacional.
- Capacidade Adaptativa: Resposta eficaz a variações de demanda, com alta disponibilidade e escalabilidade automática dos recursos.
