# Santander-Code-Girls-2025-4

## Infraestrutura Automatizada com AWS CloudFormation

A infraestrutura automatizada tem como objetivo criar e gerenciar recursos de tecnologia de forma padronizada e reproduzível, eliminando a necessidade de configurações manuais.  
Na AWS, essa automação é alcançada por meio do CloudFormation, um serviço que permite definir toda a infraestrutura como código (IaC — Infrastructure as Code).

Com o CloudFormation, é possível descrever os recursos desejados — como instâncias EC2, volumes EBS, redes VPC, bancos de dados RDS, e outros serviços da AWS — em um modelo (template) escrito em YAML ou JSON.  
A partir desse modelo, a AWS provisiona automaticamente todos os componentes na ordem correta, aplicando dependências, permissões e configurações de forma consistente.

Entre os principais benefícios estão:
- Automação: criação, atualização e exclusão de recursos de forma automática e previsível;  
- Padronização: todos os ambientes (desenvolvimento, testes e produção) seguem a mesma estrutura;  
- Controle de versão: os modelos podem ser versionados em repositórios Git, facilitando auditoria e colaboração;  
- Escalabilidade e repetibilidade: possibilita recriar ambientes completos com rapidez e sem erro humano.

Em resumo, o AWS CloudFormation é uma ferramenta essencial para quem busca adotar práticas modernas de DevOps e infraestrutura como código, tornando o gerenciamento da nuvem mais eficiente, seguro e sustentável.
