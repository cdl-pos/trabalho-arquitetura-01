# 🔧 Desafio — Sistema de Orçamentos de Oficina

> Um sistema de oficina mecânica precisa calcular o custo total de um serviço de manutenção em veículos, considerando peças, mão de obra e possíveis descontos.

---

## 🧩 Regras de Negócio

Cada serviço deve conter:
- **Descrição**
- **Tempo estimado** (em horas)
- **Valor da hora técnica**
- **Peças utilizadas**:
  - nome
  - preço unitário
  - quantidade

O sistema deve calcular:
- Total de peças
- Total de mão de obra
- Valor final com base em possíveis descontos:
  - **Desconto de 5%** se o cliente pagar à vista (PIX)
  - **Desconto de 10%** se o veículo tiver manutenção preventiva (cliente fiel)
  - Descontos **não são cumulativos** (usar o maior)

---

## 🧠 Requisitos

- Deve retornar o **valor final do orçamento** e um **resumo dos itens**.
- O design deve permitir a inclusão de **novas regras de desconto** (ex: cupons, convênios).
- Implementação **orientada a objetos**, utilizando princípios **SOLID** e padrões de projeto.
- Uso de **arquitetura limpa** é um diferencial.

---

