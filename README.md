<div align="center">

# Materiais da trilha

**Bases de dados e guias usados nas aulas da Trilha de Formação em Desenvolvimento de Soluções com IA.**

![Semana 4](https://img.shields.io/badge/semana%204-Git%2C%20GitHub%20e%20dados-0b6bb8?style=for-the-badge)

</div>

---

## O que tem aqui

| Pasta | Conteúdo |
|---|---|
| [`semana-04/`](semana-04) | Base de solicitações para as aulas de Pandas |

As atividades, os vídeos e a entrega das respostas ficam na **Plataforma Projetar**, no menu **Trilha**. Este repositório guarda só os arquivos que as aulas usam.

## Como usar uma base no Colab

Não precisa baixar nada: o Pandas lê o arquivo direto daqui.

```python
import pandas as pd

url = "https://raw.githubusercontent.com/Projetar-Solucoes/materiais-trilha/main/semana-04/solicitacoes_semana4.csv"
df = pd.read_csv(url)
df.head()
```

## Sobre os dados

Todas as bases são **fictícias**: nomes, setores e solicitações foram gerados para a aula e não correspondem a pessoas reais. Algumas bases vêm com problemas de propósito (linhas repetidas, campos vazios, textos escritos de jeitos diferentes), porque dados de verdade também vêm assim — e arrumar isso faz parte do trabalho.

**Não altere os arquivos daqui.** Faça a limpeza no seu código, no seu próprio repositório.
