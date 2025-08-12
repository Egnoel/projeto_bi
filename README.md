# Projeto BI - Data Warehouse e ETL

Este projeto tem como objetivo a implementação de um Data Warehouse para análise de dados de clientes, vendas, produtos e fornecedores, utilizando processos ETL desenvolvidos em SSIS (SQL Server Integration Services).

## Estrutura do Projeto

- **[`Dataset_Clientes_SSIS.xlsx`](Dataset_Clientes_SSIS.xlsx )**: Base de dados de clientes utilizada para carga inicial.
- **Documento de Requisitos de Projeto.docx**: Documento com os requisitos funcionais e técnicos do projeto.
- **Modelagem/**: Contém arquivos de modelagem do banco OLTP, Stage e DW, incluindo diagramas (.mdj), scripts SQL e imagens.
- **Pacotes/PROJETO_BI/**: Solução SSIS com pacotes ETL para processamento e carga dos dados.
- **Scripts/**: Scripts SQL para modelagem e carga das tabelas do OLTP, Stage e DW.

## Principais Componentes

- **Modelagem OLTP**: Estrutura relacional para armazenamento operacional dos dados.
- **Stage Area**: Área intermediária para tratamento e limpeza dos dados antes da carga no DW.
- **Data Warehouse (DW)**: Estrutura dimensional para análise e geração de relatórios.
- **ETL (SSIS)**: Pacotes para extração, transformação e carga dos dados, incluindo o processamento do cubo de vendas.

## Como Utilizar

1. **Modelagem**: Utilize os arquivos da pasta [`Modelagem`](Modelagem ) para criar as estruturas de banco de dados.
2. **Carga de Dados**: Execute os scripts da pasta [`Scripts`](Scripts ) para inserir os dados iniciais.
3. **ETL**: Abra a solução SSIS em [`Pacotes/PROJETO_BI/PROJETO_BI.sln`](Pacotes/PROJETO_BI/PROJETO_BI.sln ) e execute os pacotes para processar e carregar os dados no DW.
4. **Análise**: Utilize o DW para consultas analíticas e geração de relatórios.

## Requisitos

- SQL Server
- SSIS (SQL Server Data Tools)
- Ferramenta de modelagem (ex: MySQL Workbench, DBDesigner)

## Autor

Projeto desenvolvido por Egnoel Neto para fins acadêmicos e profissionais.

---

Para mais detalhes, consulte o [`Documento de Requisitos de Projeto.docx`](Documento de Requisitos de Projeto.docx ) e os diagramas em [`Modelagem`](Modelagem).