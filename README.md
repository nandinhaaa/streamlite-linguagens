
# 📊 Análise das Principais Linguagens de Programação

Este projeto é uma aplicação interativa desenvolvida com **Streamlit** que realiza a raspagem de dados das linguagens de programação mais populares a partir do site [Statistics Times](https://statisticstimes.com/tech/top-computer-languages.php), e apresenta os resultados de forma visual através de **tabelas e gráficos**.

## 🚀 Funcionalidades

* 🔍 **Raspagem de dados** em tempo real usando `requests` + `BeautifulSoup`.
* 📑 Exibição dos dados em tabela interativa.
* 📈 Gráfico de linha com a evolução das linguagens.
* 📊 Gráfico de barras para comparação.
* 🥧 Gráfico de pizza destacando o **Top 3 linguagens**.
* ⚡ Interface simples e intuitiva feita com **Streamlit**.

---

## 🛠️ Tecnologias Utilizadas

* [Python 3](https://www.python.org/)
* [Pandas](https://pandas.pydata.org/)
* [Requests](https://docs.python-requests.org/)
* [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/)
* [Matplotlib](https://matplotlib.org/)
* [Streamlit](https://streamlit.io/)

---

## 📥 Como Rodar o Projeto

### 1. Clone o repositório

```bash
git clone https://github.com/nandinhaaa/streamlite-linguagens.git
cd streamlite-linguagens
```

### 2. Crie e ative um ambiente virtual (opcional, mas recomendado)

```bash
python -m venv venv
source venv/bin/activate   # Linux/Mac
venv\Scripts\activate      # Windows
```

### 3. Instale as dependências

```bash
pip install -r requirements.txt
```

*(Caso o `requirements.txt` não esteja presente, instale manualmente:)*

```bash
pip install requests beautifulsoup4 pandas matplotlib streamlit
```

### 4. Execute a aplicação

```bash
streamlit run app.py
```

O projeto rodará em: **[http://localhost:8501](http://localhost:8501)**

---

## 📸 Exemplos de Visualização

* **Tabela de Dados**
* **Gráfico de Linha**
* **Gráfico de Barras**
* **Top 3 - Gráfico de Pizza**

*(adicione aqui prints da aplicação para deixar o README mais atrativo!)*

---

## 📂 Estrutura do Projeto

```
streamlite-linguagens/
│── app.py              # Código principal da aplicação
│── requirements.txt    # Dependências do projeto
│── README.md           # Documentação
│── .devcontainer/      # Configuração para Codespaces
```

---

## 💡 Melhorias Futuras

* [ ] Adicionar filtros por ano/mês (caso disponível na fonte).
* [ ] Exportar dados para CSV/Excel.
* [ ] Adicionar mais gráficos interativos (Plotly/Altair).

---

## 👩‍💻 Autora

Feito com ❤️ por [@nandinhaaa](https://github.com/nandinhaaa)

---
