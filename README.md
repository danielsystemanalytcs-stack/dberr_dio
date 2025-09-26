# 🚀 Modelo de Dados para E-commerce (PJ/PF, Pagamentos e Entrega)

Este repositório contém o **Modelo Relacional de Banco de Dados** projetado para um sistema de e-commerce, com foco na gestão de clientes (Pessoa Jurídica e Física), múltiplas formas de pagamento e rastreamento de entregas.

---

## 🎯 Objetivo do Modelo

O principal objetivo deste modelo é estruturar as informações críticas de um sistema de vendas online, garantindo:

1.  **Segregação Cliente PJ e PF:** Uma conta pode ser **exclusivamente PJ ou PF**.
2.  **Flexibilidade de Pagamento:** Possibilidade de cadastrar **múltiplas formas de pagamento** por conta.
3.  **Rastreabilidade de Entregas:** Gestão completa do status da entrega e do **código de rastreio**.

---

## 🏗️ Estrutura do Modelo Relacional

O modelo é composto por quatro entidades principais: `CONTA`, `PAGAMENTO`, `PEDIDO` e `ENTREGA`.

### Diagrama (Visão Geral)
