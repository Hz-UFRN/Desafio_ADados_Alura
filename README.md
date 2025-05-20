# Desafio_Alura Store - Análise de Desempenho das Lojas

## Propósito

Este projeto tem como objetivo analisar o desempenho de quatro lojas do grupo Alura Store, utilizando dados históricos de vendas, avaliações de clientes, custos de frete e sazonalidade. A análise permite identificar qual loja apresenta o pior desempenho integrado e, portanto, deve ser vendida, além de sugerir melhorias estratégicas para as lojas que permanecerão ativas.

---

## Estrutura do Projeto

```
├── AluraStoreBr.ipynb        # Notebook principal com toda a análise, gráficos e relatório final.
├── data/
│   ├── loja1.csv             # Dados da Loja 1
│   ├── loja2.csv             # Dados da Loja 2
│   ├── loja3.csv             # Dados da Loja 3
│   └── loja4.csv             # Dados da Loja 4
├── README.md                 # Este arquivo de documentação
```

**Descrição dos arquivos:**
- **AluraStoreBr.ipynb**: Notebook Jupyter com códigos, visualizações e o relatório executivo.
- **data/**: Pasta contendo arquivos .csv com os dados brutos de cada loja.
- **README.md**: Instruções, contexto e exemplos de resultados.

---

## Exemplos de Gráficos e Insights

### 1. Faturamento Total por Loja
![Exemplo de gráfico de barras](docs/exemplo_faturamento.png)

### 2. Faturamento Mensal (Sazonalidade)
![Exemplo de gráfico de linha](docs/exemplo_sazonalidade.png)

### 3. Distribuição das Avaliações dos Clientes
![Exemplo de boxplot](docs/exemplo_boxplot.png)

### 4. Participação das Categorias mais Vendidas
![Exemplo de gráfico de pizza](docs/exemplo_pizza.png)

**Principais insights obtidos:**
- Identificação da loja com desempenho mais fraco considerando faturamento, avaliações, frete e sazonalidade.
- Observação de padrões sazonais: lojas excessivamente dependentes de poucos meses de pico são mais arriscadas.
- Sugestões precisas para melhorar avaliações, reduzir custos logísticos e diversificar o mix de produtos nas lojas mantidas.

---

## Como Executar o Notebook

1. **Clone este repositório:**
   ```bash
   git clone https://github.com/seu-usuario/alura-store.git
   cd alura-store
   ```

2. **Instale as dependências necessárias:**
   Recomenda-se o uso de um ambiente virtual. Instale as bibliotecas principais via pip:
   ```bash
   pip install pandas matplotlib scikit-learn jupyter
   ```

3. **Abra o notebook Jupyter:**
   ```bash
   jupyter notebook AluraStoreBr.ipynb
   ```
   > **Obs.:** Certifique-se de que os arquivos de dados `.csv` estejam na pasta `data/` como indicado.

4. **Execute as células do notebook:**
   Siga a ordem das células para processar os dados, visualizar os gráficos e ler o relatório final interativo.

---

## Contato

Dúvidas, sugestões ou melhorias? Fique à vontade para abrir uma issue ou pull request neste repositório!
