# Estoque quebrando em silêncio

> Trabalho acadêmico de ADS com aplicação real em base de dados de exemplo do varejo alimentar brasileiro.

[![Status](https://img.shields.io/badge/status-concluído-059669.svg)]()
[![Tecnologias](https://img.shields.io/badge/tech-HTML%20%7C%20CSS%20%7C%20JS%20%7C%20ApexCharts-E07A5F.svg)]()
[![Licença](https://img.shields.io/badge/licença-MIT-8C5A3C.svg)]()

---

## O que é este projeto?

Esta é uma **apresentação interativa** construída como trabalho de faculdade para a disciplina em Análise e Desenvolvimento de Sistemas (ADS). O objetivo não era apenas cumprir uma entrega acadêmica: era mostrar como duas ferramentas simples — desenvolvidas a partir de um problema real observado no dia a dia do varejo alimentar — podem reduzir perdas de estoque e devolver visibilidade para quem opera o negócio.

O projeto foi pensado como uma **landing page narrativa**: rolagem progressiva, dados do setor, mini-emulações das ferramentas e argumentação direta sobre o problema.

---

## O problema

O varejo alimentar brasileiro perde bilhões por ano com produtos que vencem na prateleira. Segundo pesquisas do setor:

| Indicador | Valor | Fonte |
|-----------|-------|-------|
| Perda sobre faturamento | ~1,87% | ABRAS |
| Produto perdido por validade | ~41% das perdas | ABRAS / Abrappe-KPMG |
| Prejuízo anual estimado | até R$ 42,1 bilhões | ABRAPPE/Protiviti |

A causa central não é falta de sistema. É **falta de visibilidade**: ninguém sabe, no momento certo, quais lotes estão perto do vencimento, onde há sobra e onde falta.

---

## As ferramentas

### 🟢 CVL — Controle de Validade por Lote

Sistema de gestão de validade baseado no princípio **FEFO** (*First Expired, First Out*).

**O que faz:**
- Cadastra produtos por **lote** e **data de validade**
- Classifica cada lote em semáforo de risco: vencido, crítico, alerta, OK
- Sugere ações: retirar, transferir, promover, devolver
- Reúne matriz e filiais em uma única tela

🔗 [Ver o CVL em funcionamento](https://jhpng.github.io/CVL/)

---

### 🟡 GAE — Gestão e Análise de Estoque

Ferramenta para transformar planilhas de estoque em lista de ações.

**O que faz:**
- Recebe a planilha do ERP da loja (XLSX/CSV)
- Processa os dados em segundos
- Aponta giro lento, estoque negativo, sobra em filial e produtos sem venda
- Exporta uma lista pronta para decisão

🔗 [Ver o GAE em funcionamento](https://jhpng.github.io/GAE/)

---

## Demonstração ao vivo

A apresentação está publicada via GitHub Pages:

👉 **[Abrir apresentação](https://jhpng.github.io/JHpng-apresentacao-trabalho-final/)**

---

## Tecnologias utilizadas

| Camada | Tecnologia |
|--------|------------|
| Estrutura | HTML5 semântico |
| Estilo | CSS3 puro (variáveis, Grid, Flexbox) |
| Interatividade | JavaScript vanilla |
| Gráficos | ApexCharts |
| Hospedagem | GitHub Pages |

