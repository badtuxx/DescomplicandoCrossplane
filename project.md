# Descomplicando o Crossplane com AWS

## O Projeto

Criar em live toda a documentação necessária para criar uma network completa na AWS utilizando o Crossplane.
O deploy do ambiente deverá ser utilizando as melhores práticas de infra-as-code e GitOps.

### Ferramentas e tecnologias utilizadas

- AWS (VPC, Subnets, Route Tables, Internet Gateway, Security Groups, EC2, NAT Gateway, etc)
- Crossplane
- ArgoCD ou FluxCD
- Helm (talvez)

### Pré-requisitos

Caso queira reproduzir em seu ambiente, você precisará de:

- Conta na AWS
- Conta no GitHub
- AWS CLI instalado e configurado
- kubectl
- Cluster Kubernetes (pode ser local)


### A nossa rede

A nossa rede será composta inicialmente por:

- 1 VPC
- 2 AZs
- 4 Subnets (2 públicas e 2 privadas)
- 1 Internet Gateway
- 2 NAT Gateway
- 2 Route Tables (1 para as subnets públicas e 1 para as subnets privadas)
