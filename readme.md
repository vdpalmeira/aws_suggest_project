# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS
Data: 14 de janeiro de 2025
Empresa: Abstergo Industries
Responsável: Victor Dias Palmeira

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizada por Victor Dias Palmeira. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos, considerando a migração de uma infraestrutura on-premises cara para a nuvem. A Abstergo Industries, como uma empresa farmacêutica, enfrenta desafios específicos relacionados à conformidade regulatória, segurança de dados e necessidade de alta escalabilidade para pesquisa e desenvolvimento.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1
Nome da ferramenta: Amazon EC2 (Instâncias R5)
Foco da ferramenta: Computação em nuvem
Descrição de caso de uso: Implementação de instâncias R5, otimizadas para memória, para hospedar aplicações de análise de dados e simulações farmacêuticas, permitindo escalabilidade e redução de custos com infraestrutura física. A migração de servidores on-premises para EC2 pode reduzir os custos de computação em até 63%. Essas instâncias são ideais para cargas de trabalho intensivas em memória, como modelagem molecular e análise de grandes volumes de dados clínicos.
### Etapa 2
Nome da ferramenta: Amazon S3 (S3 Standard e S3 Glacier)
Foco da ferramenta: Armazenamento de dados
Descrição de caso de uso: Utilização de Amazon S3 Standard para armazenamento de dados acessados diariamente, como resultados de testes clínicos e dados de pesquisa em andamento, garantindo alta durabilidade e acessibilidade com custos reduzidos. Para armazenamento de longo prazo de dados clínicos e de pesquisa, será utilizado o Amazon S3 Glacier, que oferece uma solução de baixo custo para arquivamento de dados. A migração de armazenamento on-premises para S3 pode reduzir os custos de armazenamento em até 66%. O S3 também facilita a conformidade com regulamentações como FDA, EMA e HIPAA, essenciais para a indústria farmacêutica.
### Etapa 3
Nome da ferramenta: AWS Lambda
Foco da ferramenta: Computação sem servidor
Descrição de caso de uso: Implementação de funções Lambda para processamento de dados em tempo real, como análise de resultados de testes clínicos, eliminando a necessidade de gerenciamento de servidores e reduzindo custos operacionais. A utilização de Lambda permite pagar apenas pelo tempo de execução do código, otimizando ainda mais os custos. Isso é particularmente útil para tarefas de processamento de dados que variam em volume e frequência, como a análise de dados de ensaios clínicos.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a redução de custos operacionais, aumento da eficiência e da produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos
[AWS Blog - Moving from on premises to the cloud with AWS delivers significant cost savings](https://aws.amazon.com/pt/blogs/aws-insights/moving-from-on-premises-to-the-cloud-with-aws-delivers-significant-cost-savings-report-finds/)

[Documentação do Amazon S3](https://docs.aws.amazon.com/pt_br/s3/?id=docs_gateway)

[Documentação do Amazon EC2](https://docs.aws.amazon.com/pt_br/AWSEC2/latest/UserGuide/concepts.html)

[Documentação do AWS Lambda](https://docs.aws.amazon.com/pt_br/lambda/)

## Assinatura do Responsável pelo Projeto:
Victor Dias Palmeira