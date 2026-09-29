# Semana 4 · Base de solicitações

`solicitacoes_semana4.csv` — solicitações de uma central de atendimento **fictícia**, abertas entre agosto e setembro de 2026.

```python
import pandas as pd
df = pd.read_csv("https://raw.githubusercontent.com/Projetar-Solucoes/materiais-trilha/main/semana-04/solicitacoes_semana4.csv")
```

## Colunas

| Coluna | O que é | Exemplo |
|---|---|---|
| `protocolo` | Código da solicitação | `2026-0053` |
| `data_abertura` | Quando a solicitação foi aberta | `2026-08-31` |
| `solicitante` | Quem pediu | `Marta Dias` |
| `setor` | Setor de quem pediu | `Comercial` |
| `categoria` | Tipo do pedido | `Acesso` |
| `assunto` | Resumo do pedido | `Senha bloqueada` |
| `prioridade` | Baixa, Média, Alta ou Urgente | `Média` |
| `status` | Aberta, Em andamento, Concluída ou Cancelada | `Concluída` |
| `data_fechamento` | Quando foi concluída (vazio se não terminou) | `2026-09-03` |
| `avaliacao` | Nota de 1 a 5 dada por quem pediu (vazio se não avaliou) | `4` |
| `unidade` | Unidade que atendeu | `Parambu` |

## Atenção

A base tem **problemas de propósito** — encontrar e resolver cada um é o exercício das aulas 3 e 4. Não conte para os colegas onde estão: deixe cada um descobrir.
