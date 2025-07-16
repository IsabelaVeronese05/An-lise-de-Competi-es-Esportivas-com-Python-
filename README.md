# 📊 Análise de Competições Esportivas com Python 

Este projeto tem como objetivo explorar, limpar e visualizar dados históricos de competições esportivas organizadas por diferentes federações, com base no arquivo `meets.csv`. Os dados incluem informações como data, local, federação, país e nome de cada evento.

---

## 🎯 Objetivos

- Limpar dados com inconsistências (valores nulos, formatos errados)
- Realizar análise exploratória com gráficos
- Entender padrões temporais e geográficos
- Visualizar as federações mais ativas e os países/estados com mais eventos

---

## 📂 Estrutura da Base de Dados

A base `meets.csv` contém **8482 registros** com as seguintes colunas:

| Coluna        | Descrição                                 |
|---------------|--------------------------------------------|
| `MeetID`      | Identificador único do evento              |
| `MeetPath`    | Caminho relativo da URL do evento          |
| `Federation`  | Federação organizadora                     |
| `Date`        | Data do evento (posteriormente convertida) |
| `MeetCountry` | País onde o evento foi realizado           |
| `MeetState`   | Estado (apenas EUA)                        |
| `MeetTown`    | Cidade do evento                           |
| `MeetName`    | Nome oficial da competição                 |

---

## 🛠 Tecnologias Utilizadas

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn


---

## 📊 Análises Realizadas

- ✅ Limpeza e padronização de dados
- ✅ Conversão da coluna de data (`Date`) para datetime
- ✅ Criação das colunas `Year` e `Month`
- ✅ Verificação de valores ausentes
- ✅ Análises gráficas:
  - Eventos por **ano**
  - Eventos por **país**
  - Federações mais ativas
  - Eventos por **estado** nos EUA
  - Evolução temporal mês a mês

---

## 📈 Exemplos de Gráficos

| Tipo | Descrição |
|------|-----------|
| 📅 Eventos por Ano | Volume de competições ao longo do tempo |
| 🌍 Distribuição por País | Quais países concentram mais eventos |
| 🏋️ Top Federações | As federações mais ativas |
| ⏳ Tendência Temporal | Eventos organizados por mês/ano |

