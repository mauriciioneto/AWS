# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA
**Data:** 23 de junho de 2024  
**Empresa:** Abstergo Industries  
**Responsável:** José Maurício Lopes Neto


---

### Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por João Silva. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de aumentar a segurança na empresa.

---

### Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

#### Medida 1: Implementação de AWS Identity and Access Management (IAM)
- **Descrição de caso de uso:**
  - O AWS IAM foi implementado para gerenciar o acesso aos serviços e recursos da AWS de forma segura. Foram criadas políticas de acesso baseadas em funções (roles) para garantir que cada funcionário tenha acesso apenas aos recursos necessários para o desempenho de suas funções.
- **Etapas da implementação:**
    1. Auditoria das necessidades de acesso de cada departamento.
    2. Criação de grupos e roles específicas no IAM.
    3. Aplicação de políticas de acesso baseadas em princípios de menor privilégio.
    4. Treinamento dos funcionários sobre boas práticas de segurança de acesso.

#### Medida 2: Configuração de AWS CloudTrail para auditoria e monitoramento
- **Descrição de caso de uso:**
  - O AWS CloudTrail foi configurado para registrar todas as chamadas de API feitas na conta AWS da empresa, proporcionando visibilidade sobre as ações realizadas por usuários, roles, e serviços.
- **Etapas da implementação:**
    1. Habilitação do CloudTrail em todas as regiões usadas pela empresa.
    2. Configuração de logs para serem armazenados em buckets S3 seguros.
    3. Implementação de alertas via Amazon SNS para atividades suspeitas ou anômalas.
    4. Integração com o AWS CloudWatch para análise em tempo real.

#### Medida 3: Implementação de AWS Key Management Service (KMS) para gerenciamento de chaves
- **Descrição de caso de uso:**
  - O AWS KMS foi utilizado para criar e controlar chaves criptográficas usadas para proteger dados armazenados e transmitidos. A criptografia foi aplicada a serviços como S3, EBS, e RDS.
 - **Etapas da implementação:**
    1. Criação de chaves mestras no KMS.
    2. Configuração de políticas de gerenciamento de chaves.
    3. Aplicação de criptografia em volumes EBS e buckets S3.
    4. Configuração de rotinas de rotação de chaves e monitoramento de uso de chaves.

---

### Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado aumento na segurança e na proteção de dados, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

---

### Anexos
- Documentação do AWS Identity and Access Management https://aws.amazon.com/pt/iam/00
- Documentação do AWS CloudTrail https://docs.aws.amazon.com/cloudtrail/
- Documentação do AWS Key Management Service https://docs.aws.amazon.com/kms/

---

## Assinatura do Responsável pelo Projeto:
**José Maurício Lopes Neto**

---

*Este projeto prático faz parte do curso de formação **"AWS Cloud Practitioner Certification"** da dio.me. Ele tem como objetivo aplicar na prática os conhecimentos adquiridos durante o curso, focando na implementação de serviços AWS para otimizar custos e aumentar a eficiência operacional de uma empresa real.*
## 🔗 Links
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mauriciioneto/)


