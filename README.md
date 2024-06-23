
![Logo](https://media.licdn.com/dms/image/D4D12AQEmC2CSTK0unw/article-cover_image-shrink_600_2000/0/1691964348159?e=2147483647&v=beta&t=UA2DD5lAEDP28NHD9BRZIoriUAdwNxY8P465qku8lNY)

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 22 de junho de 2024  
**Empresa:** Abstergo Industries  
**Responsável:** José Maurício Lopes Neto

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por **José Maurício Lopes Neto**. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

### Etapa 1:
- **Nome da ferramenta:** Amazon EC2 (Elastic Compute Cloud)
- **Foco da ferramenta:** Escalabilidade e Otimização de Custos de Computação
- **Descrição de caso de uso:**
  O Amazon EC2 foi implementado para oferecer capacidade de computação escalável e flexível. A empresa utilizou Instâncias Reservadas para obter descontos significativos em comparação com instâncias sob demanda e Spot Instances para tarefas que podem ser interrompidas, economizando até 90% em custos de computação. Além disso, a funcionalidade de Auto Scaling foi configurada para ajustar automaticamente o número de instâncias de acordo com a demanda, evitando custos com capacidade ociosa.

### Etapa 2:
- **Nome da ferramenta:** Amazon S3 (Simple Storage Service)
- **Foco da ferramenta:** Armazenamento Escalável e Econômico
- **Descrição de caso de uso:**
  O Amazon S3 foi utilizado para armazenar grandes volumes de dados de forma segura e econômica. A empresa adotou diferentes classes de armazenamento, como S3 Standard para dados frequentemente acessados e S3 Glacier para arquivamento de dados, reduzindo custos de armazenamento. Políticas de ciclo de vida foram configuradas para mover automaticamente dados entre classes de armazenamento com base na frequência de acesso, otimizando ainda mais os custos.

### Etapa 3:
- **Nome da ferramenta:** Amazon RDS (Relational Database Service)
- **Foco da ferramenta:** Gestão de Banco de Dados Eficiente e Econômica
- **Descrição de caso de uso:**
  O Amazon RDS foi implementado para gerenciar bancos de dados relacionais de forma eficiente. A empresa utilizou Instâncias Reservadas para bancos de dados críticos, economizando até 69% em comparação com instâncias sob demanda. A funcionalidade de escalabilidade automática foi configurada para ajustar a capacidade do banco de dados conforme a demanda, evitando custos com capacidade excessiva. Read Replicas foram usadas para distribuir a carga de leitura, melhorando o desempenho sem necessidade de instâncias adicionais do banco de dados principal.

## Conclusão
A implementação de ferramentas na empresa **Abstergo Industries** tem como esperado uma redução significativa de custos operacionais, aumento da eficiência e melhoria na produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos
Documentação de cada um dos serviços:
- Documentação do Amazon Elastic Compute Cloud: [https://docs.aws.amazon.com/pt_br/ec2/](https://docs.aws.amazon.com/pt_br/ec2/)
- Documentação do Amazon Simple Storage Service: [https://docs.aws.amazon.com/pt_br/s3/](https://docs.aws.amazon.com/pt_br/s3/)
- Documentação do Amazon RDS: [https://docs.aws.amazon.com/pt_br/rds/](https://docs.aws.amazon.com/pt_br/rds/)

## Assinatura do Responsável pelo Projeto:
**José Maurício Lopes Neto**

---

*Este projeto prático faz parte do curso de formação **"AWS Cloud Practitioner Certification"** da dio.me. Ele tem como objetivo aplicar na prática os conhecimentos adquiridos durante o curso, focando na implementação de serviços AWS para otimizar custos e aumentar a eficiência operacional de uma empresa real.*

## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mauriciioneto/)


