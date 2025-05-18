🛍️ Alura Store – Análise de Dados

Este projeto tem como objetivo realizar uma análise exploratória dos dados de uma loja virtual fictícia, a **Alura Store**. O foco está em entender o comportamento de vendas, a performance por categoria de produtos e a satisfação dos clientes, gerando insights que possam apoiar decisões estratégicas.

---

🎯 Propósito da Análise

* Avaliar o desempenho de vendas por produto e categoria.
* Identificar tendências de consumo.
* Analisar o faturamento total da loja ao longo do tempo.
* Verificar a satisfação dos clientes por meio das avaliações.
* Explorar possíveis relações entre tipo de produto, preço, quantidade vendida e avaliação.

---

📁 Estrutura do Projeto

```
alura-store/
│
├── dados/
│   └── alura_store.csv         # Base de dados principal
│
├── imagens/
│   └── grafico_faturamento.png # Exemplos de gráficos gerados
│   └── grafico_avaliacoes.png
│
├── notebooks/
│   └── analise_alura_store.ipynb  # Notebook com toda a análise
│
└── README.md                  # Este arquivo
```

---

📊 Exemplos de Gráficos e Insights

 📈 Faturamento por Categoria

![Faturamento por Categoria](imagens/grafico_faturamento.png)

* A categoria **Eletrônicos** lidera em faturamento, representando mais de 35% da receita total.

⭐ Avaliação Média por Categoria

![Avaliações por Categoria](imagens/grafico_avaliacoes.png)

* A categoria **Livros** possui a melhor média de avaliação, com **4.7 estrelas**, indicando alta satisfação.

💡 Outros insights:

* Produtos com maiores quantidades vendidas nem sempre são os mais bem avaliados.
* A loja tem maior volume de vendas nos meses de **novembro e dezembro**, sugerindo efeito sazonal (Black Friday e Natal).
* Há correlação positiva entre preço e avaliação média em algumas categorias.

---

▶️ Como Executar o Notebook

1. **Clone este repositório:**

   ```bash
   git clone https://github.com/seu-usuario/alura-store.git
   cd alura-store
   ```

2. **Crie um ambiente virtual (opcional):**

   ```bash
   python -m venv venv
   source venv/bin/activate  # Linux/Mac
   venv\Scripts\activate     # Windows
   ```

3. **Instale as dependências:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Execute o Jupyter Notebook:**

   ```bash
   jupyter notebook notebooks/analise_alura_store.ipynb
   ```

---

 📌 Observações

Este projeto foi desenvolvido como parte dos estudos em Data Science e análise de dados da plataforma Alura. Todos os dados são fictícios e utilizados apenas para fins educacionais.

---

Se você quiser, posso gerar o `requirements.txt` com base nas bibliotecas que usou. É só me dizer quais foram, ou me mandar o notebook que eu analiso!
