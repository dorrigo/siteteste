# 📊 Projeto Fictício: Análise de Dados de Vendas (2024)  

Um exemplo de postagem em Markdown para GitHub Pages, com formatação avançada.  

---

## 🔍 Objetivo do Projeto  
Simular uma análise de dados de vendas usando:  
- **Python** (Pandas, Matplotlib)  
- **Jupyter Notebook**  
- **Dados fictícios** (gerados aleatoriamente)  

---

## 📌 Tópicos Principais  

### 1. Dados Utilizados  
| Categoria        | Fonte                     | Período       |  
|------------------|---------------------------|---------------|  
| Vendas Online    | API FakeStore             | Jan-Mar 2024  |  
| Vendas Físicas   | Planilha CSV (gerada)     | Jan-Mar 2024  |  
| Clientes         | Banco de Dados SQLite     | 2023-2024     |  

### 2. Métricas Analisadas  
- 📈 **Faturamento por Mês**  
- 🛒 **Produtos Mais Vendidos**  
- 🌍 **Regiões com Maior Volume**  

### 3. Resultados  
```python
import pandas as pd
print("Top 5 Produtos:")
print(df.groupby('produto')['vendas'].sum().nlargest(5))
```
![Imagem Teste](/assets/images/teste.jpg)
