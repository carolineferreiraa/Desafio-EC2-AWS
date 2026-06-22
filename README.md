# Desafio-EC2-AWS
Repositório com objetivo de consolidar meus conhecimentos em gerenciamento de instâncias EC2 na AWS

1- O que é EC2
É uma ferramenta da AWS para criação de máquinas virtuais configuradas remotamente em outro lugar.
Durante a criação da instância, o usuário consegue selecionar uma imagem de máquina da Amazon, que contém o sistema operacional e o software desejado. Com isso, o trabalho de hardware é dispensável para o usuário. Ao selecionar uma instância, você pode escolher a CPU, a memória, a capacidade de rede e muito mais. Essa flexibilidade é o ambiente perfeito para o trabalho escalonável. 

2 - EC2 vs. EC2 S3
EC2 - aluguel de máquinas virtuais
S3 - serviço de armazenamento que salva arquivos como objetos

3- EC2 vs. EC2 ECS/EKS
EC2 - o usuário tem controle total sobre as configurações da máquina virtual
ECS/EKS - serviços como o ECS (Elastic Container Service) e o EKS (Elastic Kubernetes Service) ajudam o usuário a executar aplicativos em contêineres sem gerenciar os detalhes do servidor subjacente. É como ter um sistema de contêineres de remessa pré-organizado, no qual o user simplesmente empacota seu aplicativo em contêineres e deixa a AWS cuidar da logística.

4 - EC2 vs. EC2 Lambda
EC2 - usuário aluga servidores virtuais e os gerencia
Lambda -  é uma plataforma sem servidor que executa seu código em resposta a eventos sem que o user precise se preocupar com os servidores subjacentes. É semelhante a pedir uma refeição que é entregue sob demanda, em vez de alugar uma cozinha completa para prepará-la você mesmo.

5 - EC2 vs. EC2 RDS
EC2  - é um serviço de computação de uso geral para executar qualquer tipo de aplicativo
RDS (Relational Database Service) - é um serviço gerenciado especificamente para bancos de dados.  O RDS cuida da manutenção, dos backups e das atualizações do seu banco de dados para que você possa se concentrar no seu aplicativo, de forma semelhante a ter um restaurante totalmente gerenciado, no qual você se concentra apenas no cardápio e não nas operações diárias da cozinha.

6 - Como iniciar uma nova instância
- Selecionar EC2 no console home
- clicar em Iniciar Instância
- selecione uma AMI
- escolha um tipo de instância
- crie um par de chaves (uma chave pública e uma privada)
- selecionando uma nuvem privada virtual (VPC) e uma sub-rede
- configure a segurança (grupos de segurança)
- revise as configurações
- clique em "Lauch"

  
