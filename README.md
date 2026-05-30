# 🎬 Análise de Streaming no Brasil — 2015 a 2024
### Projeto G2 · Tema 21

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?logo=python)
![Streamlit](https://img.shields.io/badge/Streamlit-1.35-red?logo=streamlit)
![Plotly](https://img.shields.io/badge/Plotly-5.22-blueviolet?logo=plotly)
![Pandas](https://img.shields.io/badge/Pandas-2.2-green?logo=pandas)

---

## 📖 Sobre o Projeto

Análise exploratória e dashboard interativo sobre padrões de consumo em plataformas de streaming no Brasil entre **2015 e 2024**, desenvolvido como Projeto G2 · Tema 21.

**Plataformas analisadas:** Netflix · Spotify · Prime Video · Disney+ · YouTube Music

---

## 🗂️ Estrutura do Repositório

```
projeto-streaming/
│
├── app.py                          # Dashboard Streamlit
├── requirements.txt                # Dependências Python
├── README.md                       # Este arquivo
├── index.html                      # GitHub Pages
│
├── dados/
│   └── simulacao_streaming_brasil.csv
│
├── notebooks/
│   └── analise_streaming.ipynb     # Análise no Google Colab
│
├── database/                       # (opcional) SQLite
└── imagens/                        # Prints e assets
```

---

## 🚀 Como Executar Localmente

```bash
# 1. Clone o repositório
git clone https://github.com/SEU_USUARIO/projeto-streaming.git
cd projeto-streaming

# 2. Instale as dependências
pip install -r requirements.txt

# 3. Execute o dashboard
streamlit run app.py
```

---

## 📊 Funcionalidades do Dashboard

- **KPIs**: Total de reproduções, receita, usuários ativos, plataforma líder, conteúdo top, gênero mais consumido
- **Filtros interativos**: Ano, mês, plataforma, categoria, gênero e conteúdo
- **Gráficos**:
  - 📈 Evolução temporal por plataforma
  - 📊 Comparação de audiência e receita entre plataformas
  - 🎭 Distribuição por gênero e categoria
  - 🕐 Heatmap de horários de pico
  - 🔍 Dispersão avaliação × audiência
  - 📈 Crescimento de assinaturas
  - 📋 Tabela dinâmica interativa
- **Conclusão executiva** gerada dinamicamente com base nos filtros

---

## 🔗 Links

| Plataforma | Link |
|---|---|
| 📁 GitHub | [github.com/SEU_USUARIO/projeto-streaming](#) |
| 🌐 GitHub Pages | [SEU_USUARIO.github.io/projeto-streaming](#) |
| 📊 Streamlit App | [projeto-streaming.streamlit.app](#) |

---

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| Python 3.10+ | Linguagem base |
| Pandas | Manipulação de dados |
| Plotly | Gráficos interativos |
| Seaborn / Matplotlib | Visualizações estáticas |
| Streamlit | Dashboard web |
| Jupyter Notebook | Análise exploratória |

---

*Projeto G2 · Tema 21 · Análise de Streaming no Brasil*
