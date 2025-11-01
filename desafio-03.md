# 🍽️ Desafio — Sistema de Pedidos de Restaurante

Um restaurante precisa de um módulo para calcular o valor total de um pedido, considerando taxas de serviço, delivery e promoções.

---

## 🧩 Regras de Negócio

Cada pedido deve conter:
- Lista de pratos:
  - nome
  - preço unitário
  - quantidade
- Tipo de pedido: **consumo no local** ou **delivery**
- Cupom promocional (opcional)

Regras:
- **Taxa de serviço (10%)** se for consumo no local.
- **Taxa de entrega (R$ 8,00)** se for delivery.
- Se houver cupom promocional:
  - `DESCONTA10`: 10% de desconto no valor total.
  - `FRETEGRATIS`: remove a taxa de entrega.
  - Outros cupons podem ser adicionados futuramente.

---

## 🧠 Requisitos

- Deve retornar o **valor total** e um **resumo das taxas aplicadas**.
- Implementação **extensível** a novos tipos de taxa (ex: taxa de embalagem, taxa de conveniência).
- Implementação **orientada a objetos**, utilizando princípios **SOLID** e **design patterns**.
- **Arquitetura limpa** e separação de camadas serão diferenciais.

---

