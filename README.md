# Ritmo Life Tracker

> **EN:** A mobile-first personal tracker that brings daily habits, goals, body metrics, expenses and reminders into a single offline web app.

**Ritmo** é um app pessoal para o celular que reúne num só lugar tudo o que eu precisava acompanhar no dia a dia: água, sono, refeições, treinos, estudos, rotina de bem-estar, gastos, remédio e compromissos.

## 🎯 O problema

Minha rotina estava espalhada em vários aplicativos: um para água, outro para gastos, outro para treino, anotações soltas para estudos. Nenhum conversava com o outro e eu não conseguia enxergar a semana como um todo.

## ✅ A solução

Um único app, leve, que abre direto no navegador do celular e não precisa de conta, servidor nem internet depois de carregado.

### Funcionalidades

| Aba | O que tem |
|---|---|
| **Hoje** | Água com anel de progresso, sono, refeições com horário, treino e exercícios, devocional e remédio do dia |
| **Metas** | Metas de água, sono, estudo e treino, com sequência de dias seguidos e progresso dos últimos 7 dias |
| **Gastos** | Registro por categoria, gastos do dia e relatório do mês com gráfico de barras |
| **Corpo** | Peso e medidas, com histórico e variação desde o primeiro registro |
| **Mais** | Estudos (feito e pendente), calendário de adesão ao remédio, agenda de lembretes e exportação de relatórios |

Outros detalhes:

- **Tira de rituais** no topo: cada ícone mostra se aquele hábito foi feito no dia e leva direto para a seção correspondente
- **Navegação entre dias** para preencher ou revisar datas anteriores
- **Relatórios semanal e mensal** prontos para imprimir ou salvar em PDF
- **Compatível com dados antigos**: novos campos são mesclados aos registros já salvos, então atualizar o app nunca apaga o histórico

## 🛠️ Tecnologias

- **HTML5**, **CSS3** e **JavaScript** puros, em um único arquivo e sem dependências
- **localStorage** para guardar os dados no próprio aparelho
- **CSS conic-gradient** para o anel de progresso da água
- **Google Fonts** (Fraunces e Inter)

## 🧭 Processo

O app foi construído e evoluído em várias rodadas a partir do uso real: primeiro o registro diário, depois metas com sequências, medidas corporais, devocional e relatórios exportáveis. A navegação foi reorganizada em cinco abas quando o número de funções cresceu. Uma função de registro por voz chegou a ser testada e foi retirada por não fazer diferença no uso do dia a dia.

Cada versão foi testada simulando o uso completo do app, inclusive com dados salvos no formato antigo, para garantir que nenhuma atualização apagasse registros.

## ▶️ Como usar

Baixe o arquivo `index.html` e abra no navegador do celular ou do computador. Os dados ficam salvos no próprio navegador.

> Como os dados ficam só no aparelho, limpar os dados do navegador apaga o histórico. Use a exportação de relatório para guardar um resumo.

## 🔮 Próximos passos

- Exportar e importar backup dos dados em JSON
- Transformar em PWA para instalar na tela inicial do celular
- Gráficos de evolução de sono e água ao longo do mês

---

Feito por [Giovana Heusi](https://github.com/giovanaheusi)
