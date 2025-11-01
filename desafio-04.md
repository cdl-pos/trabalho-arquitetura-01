# 🏥 Desafio — Sistema de Faturamento Hospitalar

Um hospital precisa de um módulo para calcular o valor total de uma internação, considerando diárias, procedimentos e convênios.

---

## 🧩 Regras de Negócio

Cada internação deve conter:
- Quantidade de diárias
- Valor da diária
- Lista de procedimentos realizados:
  - nome
  - valor
- Tipo de convênio:
  - Particular
  - Plano básico
  - Plano premium

Regras:
- **Convênio particular**: paga o valor total.
- **Convênio básico**: cobre **70% dos custos totais**.
- **Convênio premium**: cobre **90% dos custos totais**.
- O sistema deve permitir **inclusão futura de novos planos** com regras específicas.

---

## 🧠 Requisitos

- Deve retornar o **valor total pago pelo paciente** e o **valor coberto pelo convênio**.
- Implementar utilizando princípios **SOLID** e padrões como **Strategy**.
- **Testes unitários** obrigatórios (PHPUnit ou similar).
- Uso de **arquitetura limpa/hexagonal** será considerado um diferencial.

---

