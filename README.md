# 🛠️ Modelo Conceitual – Sistema de Oficina Mecânica

Este repositório apresenta o modelo conceitual de um banco de dados para um sistema de oficina mecânica, incluindo clientes, veículos, ordens de serviço, mecânicos, peças e mão de obra utilizadas nos atendimentos.

## 📘 Descrição Geral

O objetivo do modelo é organizar as principais informações envolvidas no funcionamento de uma oficina, permitindo:

- Registrar clientes e seus veículos

- Criar ordens de serviço

- Controlar equipes de mecânicos

- Registrar peças utilizadas

- Registrar tipos de mão de obra aplicada

O design busca evitar dados duplicados e manter relacionamentos claros entre as entidades.

## 🗂️ Principais Entidades

- Cliente – informações básicas do cliente.

- Veículos – veículos associados ao cliente.

- Ordem_servico – dados da ordem de serviço (datas, valor, status, equipe responsável).

- Mecanicos – dados individuais dos mecânicos.

- Equipe_mecanicos – equipes que executam as ordens de serviço.

- Tabela_pecas – catálogo de peças da oficina.

- Tabela_mao_de_obra – tipos de serviços e valores de mão de obra.

## 🔗 Relacionamentos Importantes

- Um cliente pode ter vários veículos.

- Uma ordem de serviço pertence a um veículo e a um cliente.

- Uma equipe pode ter vários mecânicos.

- Uma ordem de serviço pode usar várias peças e vários tipos de mão de obra.
