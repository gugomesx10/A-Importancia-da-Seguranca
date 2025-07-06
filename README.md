# Redução dos Custos em Farmácias com AWS

## RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 06/07/2025  
**Empresa:** FarmaVida LTDA  (inventado por mim)
**Responsável:** Gustavo Gomes Martins

---

## Introdução

Este relatório apresenta o processo de implementação de serviços em nuvem na empresa **FarmaVida LTDA**, realizado por **Gustavo Gomes Martins**.  
O objetivo do projeto foi:

- *Elencar 3 serviços da AWS aplicados à realidade da empresa*  
- *Realizar a diminuição de custos imediatos com infraestrutura local*

---

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos.  
A seguir, serão descritas as etapas do projeto:

### Etapa 1
- **Nome da ferramenta:** Amazon S3  
- **Foco da ferramenta:** Armazenamento seguro e escalável de documentos e relatórios de vendas.  
- **Descrição de caso de uso:** A empresa armazenava arquivos localmente, gerando risco de perda de dados. Com o Amazon S3, todos os documentos passaram a ser versionados e acessíveis via navegador, com custos reduzidos por acesso esporádico (uso de classes IA e Intelligent-Tiering).

---

### Etapa 2
- **Nome da ferramenta:** Amazon RDS  
- **Foco da ferramenta:** Banco de dados gerenciado para controle de estoque e pedidos.  
- **Descrição de caso de uso:** A base de dados local era instável e exigia manutenção manual. Com o RDS, foi possível automatizar backups, aumentar a disponibilidade e reduzir custos com suporte técnico e infraestrutura física.

---

### Etapa 3
- **Nome da ferramenta:** AWS Lambda  
- **Foco da ferramenta:** Processamento automático de tarefas rotineiras e disparo de notificações.  
- **Descrição de caso de uso:** Antes, a farmácia usava scripts manuais para gerar relatórios semanais. Agora, funções Lambda automatizam esse processo, acionando notificações por e-mail e armazenando os relatórios no S3 automaticamente.

---

## Conclusão

A migração parcial para a nuvem com foco em armazenamento, banco de dados e automações resultou em **redução de custos operacionais**, **melhoria na segurança dos dados** e **escalabilidade para futuras integrações**.  
O projeto mostrou que a **adoção de soluções AWS pode ser aplicada de forma acessível e estratégica**, mesmo para empresas de pequeno e médio porte no setor farmacêutico.

---

