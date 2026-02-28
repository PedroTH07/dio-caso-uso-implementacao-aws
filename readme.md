# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 28/02/2026
Empresa: Abstergo Industries 
Responsável: Pedro Silva Gomes

## Introdução
Este relatário apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Pedro Silva Gomes. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos especí­ficos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon S3 (Simple Storage Service)
- Armazenamento em nuvem escalável e de baixo custo para dados e arquivos da empresa
- A Abstergo Industries atualmente mantém servidores físicos próprios para armazenar catálogos de produtos, notas fiscais, pedidos e histórico de transações com farmácias parceiras. Com o Amazon S3, esses dados seriam migrados para a nuvem, eliminando os custos com manutenção de hardware, energia elétrica e espaço físico dos servidores. O modelo de pagamento pay-as-you-go do S3 garante que a empresa pague apenas pelo espaço efetivamente utilizado, reduzindo drasticamente os gastos fixos de infraestrutura. O principal ganho é a eliminação de custos de hardware e manutenção, com alta disponibilidade e recuperação de dados em caso de falhas.

Etapa 2: 
- Amazon EC2 (Elastic Compute Cloud)
- Computação em nuvem elástica com escalonamento sob demanda para substituir servidores locais
- Atualmente, a Abstergo Industries opera com servidores físicos dimensionados para suportar picos de demanda — como fechamento de pedidos mensais com as farmácias — mesmo que esses picos ocorram por apenas alguns dias no mês. Isso significa pagar por capacidade ociosa durante a maior parte do tempo. Com o Amazon EC2, a empresa pode escalar instâncias de computação automaticamente conforme a demanda, pagando apenas pelas horas de uso efetivo. Utilizando instâncias reservadas ou spot, é possível reduzir os custos de computação em até 70% comparado à infraestrutura física. O principal ganho é a flexibilidade operacional e a eliminação de investimentos em hardware com vida útil limitada.

Etapa 3: 
- Amazon RDS (Relational Database Service)
- Banco de dados gerenciado na nuvem para gestão eficiente dos dados de clientes, pedidos e estoque
- A gestão de um hub de distribuição farmacêutica exige controle preciso de pedidos, clientes (farmácias), estoque e faturamento. Manter bancos de dados locais demanda equipe especializada de DBA, licenças de software onerosas e infraestrutura dedicada. Com o Amazon RDS, toda essa gestão é terceirizada para a AWS, que realiza backups automáticos, aplicação de patches de segurança, alta disponibilidade com Multi-AZ e monitoramento contínuo sem custo adicional de mão de obra especializada. O principal ganho é a redução de custos com licenças de banco de dados, equipe de TI dedicada e downtime operacional, garantindo que os dados de pedidos e clientes estejam sempre disponíveis com segurança.



## Conclusão
A implementação de ferramentas na empresa *Abstergo Industries tem como esperado [benefÃ­cios das ferramentas]*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.


Assinatura do Responsável pelo Projeto:

Pedro Silva Gomes