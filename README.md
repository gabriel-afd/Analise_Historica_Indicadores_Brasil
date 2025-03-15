# 📊 Análise Histórica de Indicadores do Brasil

Este projeto consiste em uma análise de dados realizada em Python a respeito de indicadores socioeconômicos do Brasil no período de 1974 a 2022. Os dados foram obtidos a partir do consumo da API do World Bank no próprio código.

## 📌 Tecnologias Utilizadas
- **Python** 🐍
- **Pandas** 📑 - Manipulação e estruturação dos dados
- **NumPy** 🔢 - Cálculos matemáticos
- **Matplotlib** 📊 - Visualização de dados
- **Seaborn** 🎨 - Gráficos estatísticos
- **Plotly** 📈 - Visualizações interativas
- **API do World Bank** 🌍 - Obtenção dos dados socioeconômicos

## 📋 Etapas do Projeto

### 1️⃣ Importação de Bibliotecas
As bibliotecas essenciais para a análise de dados são importadas:
- `pandas`, `numpy`, `matplotlib.pyplot`, `seaborn`, `plotly.express`

### 2️⃣ Consumo da API do World Bank
- Desenvolvimento de uma função para obter dados da API.
- Armazenamento dos indicadores em um dicionário.
- Conversão dos dados JSON recebidos em um `DataFrame` do Pandas.

### 3️⃣ Tratamento de Dados
- Identificação e remoção de valores nulos.
- Criação de um novo `DataFrame` limpo para análise.

## 📊 Análises Realizadas

📈 **PIB per Capita (1974 – 2022, US$):**
- Evolução crescente até 2011, seguida de queda em 2015 e 2020 devido a crises econômicas e pandemia.

📊 **Crescimento Populacional (1974 – 2022):**
- Crescimento acelerado no século XX, desaceleração no século XXI devido a fatores como educação e condições socioeconômicas.

📉 **Inflação Antes do Plano Real (1980 - 1994):**
- Boxplot indica inflação extremamente alta, com grandes variações nos anos 1985 e 1990.
- Necessário uso de escala logarítmica para capturar a variação.

📊 **Inflação Depois do Plano Real (1995 - 2022):**
- Inflação mais controlada, queda na amplitude das variações.
- Ano de 1995 apresenta grande variabilidade devido à transição econômica.
- Uso de escala linear suficiente para representar os dados.

📈 **Taxa de Inflação Anual – Gráfico de Densidade:**
- Antes do Plano Real: distribuição com cauda longa à direita (hiperinflação).
- Depois do Plano Real: cauda longa à esquerda (inflação controlada e até deflação).
- Mudança na curtose de 0.6125 (mesocúrtica) para 24 (leptocúrtica), indicando maior concentração de valores próximos ao centro.

🔥 **Gráfico Heatmap para Correlação:**
- **Correlação forte positiva:** PIB per capita e expectativa de vida (+0.85).
- **Correlação forte negativa:** Baixa renda e IDH (-0.94).
- **Correlação fraca negativa:** Crescimento econômico e inflação anual.

## 🎯 Conclusão
O projeto demonstra como os indicadores econômicos e sociais do Brasil evoluíram ao longo do tempo e como eventos históricos impactaram os dados. Utilizando técnicas de análise estatística e visualização de dados, foi possível extrair insights importantes sobre a economia brasileira.

🔎 Para mais detalhes, consulte o código-fonte! 🚀

## 🛠 Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/gabriel-afd/Analise_Historica_Indicadores_Brasil.git
   ```
2. Acesse o diretório do projeto:
   ```bash
   cd Analise_Historica_Indicadores_Brasil
   ```
3. Crie um ambiente virtual e instale as dependências:
   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows: venv\Scripts\activate
   pip install -r requirements.txt
   ```
4. Abra o Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Execute o arquivo **Análise_Histórica_Indicadores_Brasil.ipynb**.

## 📬 Contato

Caso tenha dúvidas ou sugestões, sinta-se à vontade para entrar em contato:
📧 **E-mail:** gmedeiros144@gmail.com  
🔗 **LinkedIn:** https://www.linkedin.com/in/gabriel-medeiros-de-mendon%C3%A7a-8a82b7251/ 

💡 Se você gostou deste projeto, não esqueça de dar uma ⭐ no repositório!

---

📢 _"A análise de dados transforma informação em conhecimento!"_

