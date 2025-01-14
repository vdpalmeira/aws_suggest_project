# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA
Data: 14 de janeiro de 2025
Empresa: Abstergo Industries
Responsável: Victor Dias Palmeira

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Victor Dias Palmeira. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto com os serviços da AWS, com a finalidade de aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

# Medida 1: Implementação de AWS Identity and Access Management (IAM)
Descrição de caso de uso: Utilização do AWS IAM para gerenciar o acesso aos recursos da AWS de forma segura. Isso inclui a criação de políticas de acesso detalhadas, a implementação de autenticação multifator (MFA) para usuários e a definição de permissões baseadas em funções. Essa medida garante que apenas usuários autorizados possam acessar dados sensíveis e recursos críticos, atendendo aos requisitos de conformidade da indústria farmacêutica.
# Medida 2: Criptografia de Dados com AWS Key Management Service (KMS)
Descrição de caso de uso: Implementação do AWS KMS para criptografar dados em repouso e em trânsito. Isso inclui a criptografia de dados armazenados no Amazon S3, Amazon RDS e outras bases de dados, bem como a criptografia de dados transmitidos entre serviços. A utilização do KMS garante que os dados sensíveis, como informações de pacientes e resultados de testes clínicos, estejam protegidos contra acessos não autorizados, atendendo às regulamentações de segurança de dados.
# Medida 3: Monitoramento e Auditoria com AWS CloudTrail e AWS Config
Descrição de caso de uso: Implementação do AWS CloudTrail e AWS Config para monitorar e auditar todas as atividades e configurações dos recursos da AWS. O CloudTrail registra todas as chamadas de API, fornecendo um histórico detalhado das ações realizadas na conta AWS, enquanto o AWS Config monitora e avalia as configurações dos recursos em tempo real. Essas ferramentas permitem a detecção de atividades suspeitas e a garantia de conformidade contínua com as políticas de segurança da empresa.

## Conclusão
A implementação de medidas de segurança na empresa Abstergo Industries tem como esperado a proteção dos dados sensíveis, a garantia de conformidade com regulamentações de segurança e a redução de riscos de segurança. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais a segurança dos processos da empresa.

## Anexos
[AWS Blog - Moving from on premises to the cloud with AWS delivers significant cost savings](https://aws.amazon.com/pt/blogs/aws-insights/moving-from-on-premises-to-the-cloud-with-aws-delivers-significant-cost-savings-report-finds/)

[Documentação do AWS IAM](https://docs.aws.amazon.com/pt_br/iam/)

[Documentação do AWS KMS](https://docs.aws.amazon.com/pt_br/kms/)

[Documentação do AWS CloudTrail](https://docs.aws.amazon.com/pt_br/cloudtrail/?id=docs_gateway)

[Documentação do AWS Config](https://docs.aws.amazon.com/pt_br/config/?icmpid=docs_homepage_mgmtgov)

## Assinatura do Responsável pelo Projeto:
Victor Dias Palmeira