Aprenda de forma 100% prática como construir uma infraestrutura de Kubernetes escalável e segura usando Terraform na AWS

### Seção 1: Introdução
- ~~Introdução ao Treinamento~~
- ~~Criação da Conta AWS~~
- ~~Configuração do AWS CLI~~

### Seção 2: AWS Mão na Massa
- ~~Arquitetura do Projeto~~
- ~~VPC~~
- ~~Subnets (Privada e Pública)~~
- ~~Tags mas Subnets para AWS Load Balancer Controller~~
- ~~Internet Gateway e Route Table~~
- ~~Auto Assign Public IP~~
- ~~Bastion Host para confirmar~~
- ~~NAT Gateway e Route Table~~
- ~~Cluster IAM role~~
- ~~Criação do Cluster EKS~~
- ~~Node IAM Role~~
- ~~Managed Node Group~~
- ~~OICD Provider~~
- ~~Deploy AWS Load Balancer Controller~~
- ~~Clean up: Limpando Tudo~~

### Seção 3: Introdução ao Terraform e Início do Projeto
- ~~Arquitetura do Terraform~~
- ~~Instalação do Terraform~~
- ~~Terraform Workflow~~
- ~~Setup do Repositório no Github~~
- ~~Providers~~
- Primeiro Recurso VPC
- Terraform State
- Migrando o backend do tfstate
- $ terraform fmt
- Pre-commit hooks para Terraform
- $ terraform validate
- $ terraform console
- $ terraform destroy
- Subnets
- terraform.tfvars (valores para variáveis)
- Region dinâmica e tags para ALB
- Desacoplando tags usando locals
- Private Subnets
- Variable "project_name"
- Internet Gateway e Route Table
- NAT Gateway & EIP
- Private Route Tables