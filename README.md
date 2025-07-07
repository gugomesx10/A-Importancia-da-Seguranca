# Relatório de Implementação de Medidas de Segurança

**Data:** 06/07/2025  
**Empresa:** Farmácia Vida+  
**Responsável:** Gustavo Gomes Martins

## 📌 Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa **Farmácia Vida+**, realizado por **Gustavo Gomes Martins**.  
O objetivo do projeto foi elencar **3 medidas de segurança** utilizando serviços da AWS, com a finalidade de aumentar a proteção dos sistemas e dados sensíveis da empresa.

## 🔐 Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em três medidas de segurança. A seguir, são descritas as etapas da implementação:

### ✅ Medida 1: Amazon GuardDuty

**Caso de uso:**  
Serviço utilizado para detectar comportamentos suspeitos e atividades maliciosas, como varreduras de porta, chamadas de API não autorizadas ou comunicação com IPs maliciosos.  
Foi implementado em todas as contas da farmácia para fornecer detecção inteligente de ameaças de forma contínua e automatizada.

---

### ✅ Medida 2: AWS IAM com MFA obrigatório

**Caso de uso:**  
O controle de identidade e acesso (IAM) foi reforçado com a exigência de autenticação multifator (MFA) para todos os usuários privilegiados.  
Essa medida foi essencial para reduzir o risco de acessos não autorizados a recursos sensíveis da infraestrutura.

---

### ✅ Medida 3: AWS Macie

**Caso de uso:**  
AWS Macie foi implementado para identificar dados confidenciais, como CPF, dados de pagamento e informações de clientes, armazenados em buckets S3.  
A partir dos resultados, foram aplicadas políticas de criptografia e controle de acesso aos dados mais sensíveis.

---

## ✅ Conclusão

Com a implementação dessas ferramentas, a Farmácia Vida+ elevou significativamente o nível de segurança da sua infraestrutura em nuvem, garantindo conformidade com boas práticas e reduzindo vulnerabilidades críticas.

