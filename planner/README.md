# Planner Financeiro Interativo

Arquivo único e offline: **`planner/index.html`**. Abra com dois cliques em qualquer navegador —
não precisa de internet, instalação ou login. Tudo o que você digitar fica salvo no próprio
navegador (localStorage) e pode ser exportado em JSON pelo botão *Exportar dados*.

## De onde vieram os números

O painel não usa exemplos: ele foi calculado a partir de `transacoes_pierre_ultimo_ano.xlsx` —
**1.219 lançamentos entre 27/07/2025 e 26/07/2026**. As transferências internas entre a conta
salário e a conta corrente foram removidas para não inflar a renda.

A estrutura das seções segue o *Planner Financeiro Anual 2026* e a coleção
*Educação Financeira na Prática* (diagnóstico, saia do vermelho, faça seu dinheiro trabalhar,
mentalidade) que estão na raiz do repositório.

### O retrato que saiu do extrato

| Indicador | Valor |
|---|---|
| Entrou em 12 meses | R$ 72.468 |
| Saiu em 12 meses | R$ 120.475 |
| Resultado do período | **−R$ 48.006** |
| Entrada média/mês (jan–jun/26) | R$ 5.635 |
| Saída média/mês (jan–jun/26) | R$ 9.639 |
| Rombo médio mensal | **−R$ 4.003** |
| Parte das saídas no cartão | 30% (R$ 35.827) |

Em 12 dos 13 meses do extrato a saída superou a entrada. Os maiores grupos de gasto por mês são
Transporte (R$ 2.279), Moradia (R$ 1.886) e Compras/lazer (R$ 1.792).

## O que já vem pré-preenchido

- **Orçamento** — a coluna *Previsto* de cada grupo vem com a sua média real dos últimos 6 meses.
- **Contas fixas** — aluguel, financiamento do veículo, seguro auto, internet, energia, água e
  celular, com os valores medianos observados.
- **Assinaturas** — os 8 serviços recorrentes identificados no extrato (R$ 153,10/mês, R$ 1.837/ano).
- **Dívidas** — os parcelamentos que ainda estavam abertos no fim do extrato, com saldo e parcela.
- **Reserva** — a meta já parte do seu custo de vida essencial (R$ 5.322/mês).

Todos esses valores são editáveis: confirme os saldos no app do banco antes de decidir qualquer coisa.

## As nove seções

1. **Painel** — diagnóstico automático, gráfico mês a mês, maiores categorias e a leitura dos números.
2. **Diagnóstico** — ponto de partida, teste da corrida dos ratos, score de 8 áreas, distribuição
   ideal × real e as 3 ações imediatas.
3. **Orçamento** — previsto × aconteceu por mês, com diferença e % da renda guardado.
4. **Contas e assinaturas** — checklist de pagamento e cálculo do que sobra se você cancelar.
5. **Dívidas** — método bola de neve ou avalanche; a ordem e a previsão de quitação se recalculam sozinhas.
6. **Reserva e 10%** — meta de 1, 3 ou 6 meses, prazo para chegar lá e o compromisso dos 10%.
7. **Metas** — quanto guardar por mês para cada sonho, com barra de progresso e mapa do ano.
8. **Semana** — registro diário de entrada e saída, com foco e aprendizado da semana.
9. **Fechamento** — balanço do mês, reflexões e consolidação do ano.

## Backup

O botão *Exportar dados* gera um `.json` com tudo o que você preencheu. Guarde-o de tempos em tempos:
se limpar o navegador ou trocar de computador, o botão *Importar* devolve tudo.
