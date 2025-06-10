# 🚗 Análise de Veículos Elétricos Registrados nos EUA

Este projeto tem como objetivo explorar e visualizar dados públicos sobre veículos elétricos registrados em diferentes estados dos Estados Unidos. A análise foi realizada com Python (usando bibliotecas como pandas, matplotlib, seaborn e folium) e alguns gráficos foram posteriormente exportados e otimizados no Tableau para visualização interativa.

## 📁 Fonte de Dados

O dataset utilizado contém informações detalhadas sobre cada veículo, incluindo:

- VIN (parcial)
- Localização: Cidade, Estado, Código Postal, Distrito Legislativo
- Ano do Modelo, Marca e Modelo
- Tipo de Veículo Elétrico
- Autonomia elétrica (`Electric Range`)
- Valor de mercado sugerido (`Base MSRP`)
- Elegibilidade para programas de combustível alternativo (CAFV)
- Localização geográfica (`Vehicle Location`) no formato WKT (`POINT (longitude latitude)`)

---

## 🔍 Etapas do Projeto

1. **Leitura e pré-processamento do arquivo CSV**
   - Conversão de colunas
   - Tratamento de dados nulos
   - Extração da latitude e longitude a partir do campo WKT

2. **Criação de Visualizações com Python**
   - Gráfico de barras das **10 marcas com mais veículos elétricos**
   - Distribuição por **ano do modelo**
   - Distribuição por **tipo de veículo elétrico**
   - Gráfico das **10 cidades com mais registros**
   - Histograma da **autonomia elétrica**
   - Mapa interativo com **marcadores dos veículos** (folium)

3. **Exportação de dados para o Tableau**
   - Alguns gráficos foram recriados no Tableau para permitir uma navegação mais fluida, interativa e profissional.

---

## 🛠 Tecnologias Utilizadas

- Python 3.11
- Jupyter Notebook (.ipynb)
- pandas
- matplotlib
- seaborn
- folium
- Tableau Public (para visualização interativa)

---

## 🌐 Visualização Interativa

🔗 [Tableau](https://public.tableau.com/views/EvAnalysisWashingtonState-GabrielHBrigatto/Dashboard?:language=pt-BR&:increment_view_count=no&:embed=y&:sid=&:redirect=auth&:embed_code_version=3&:loadOrderID=0&:display_count=y&publish=yes&:origin=viz_share_link)

---

## 📌 Conclusões

A análise permitiu identificar as marcas mais populares de veículos elétricos, os estados e cidades com maior concentração, além de entender a variação da autonomia e os tipos mais comuns. O uso de mapas e visualizações ajudou a comunicar melhor os insights.

---
