# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 02/2026	

Empresa: Abstergo Industries	

Responsável: Luciano Furtado 

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Luciano Furtado. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos especí­ficos. A seguir, serão descritas as etapas do projeto:

## Etapa 1: 
- Nome da ferramenta: AWS S3 com Intelligent-Tiering.
- Foco da ferramenta: Armazenamento de objetos escalável com gestão automática de custos.
- Descrição de caso de uso: diariamente o sistema gera arquivos, como XMLs de notas fiscais, fotos de receitas médicas e backups de segurança. Em vez de investir em storage físico, você envia esses dados para o Amazon S3. Ao ativar o Intelligent-Tiering, a AWS utiliza IA para identificar arquivos que não são acessados há 30 dias (como uma receita médica de um mês atrás) e os move automaticamente para camadas de arquivamento mais baratas. Isso reduz o custo de armazenamento de dados históricos sem interromper o acesso caso precise recuperá-los.

## Etapa 2: 
- Nome da ferramenta: AWS Aurora Serverless.
- Foco da ferramenta: Banco de dados relacional (SQL) que escala a capacidade instantaneamente.
- Descrição de caso de uso: Para manter o estoque sincronizados, o banco de dados precisa estar sempre disponível. O Amazon Aurora Serverless é ideal para negócios de movimento moderado, ajustando sua capacidade de processamento em tempo real conforme a demanda. Isso evita o pagamento por uma infraestrutura "grande demais" para os momentos de calmaria, otimizando o custo total de propriedade da base de dados.

## Etapa 3: 
- Nome da ferramenta: AWS Lambda.
- Foco da ferramenta: Processamento de código Serverless (sem servidor) pago por uso.
- Descrição de caso de uso: As vendas on-line e presenciais possuem picos distintos. Em vez de manter um servidor ligado 24/7 para processar os pedidos, você utiliza o AWS Lambda. O código do seu sistema próprio só é executado quando um evento ocorre, ou seja, uma compra é realizada. O custo é elaborado a partir da execução, eliminando o custo de ociosidade de servidores físicos ou máquinas virtuais.

## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado melhorar a perfomance e reduzir custos com infraestrutura, processamento e armazenamento de dados. Com isso aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilizaçãoo das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

Assinatura do Responsável pelo Projeto:

Luciano Furtado
