# Projeto de Dashboard Financeiro – Bulltrend

Este projeto foi realizado como parte do curso da Alura, com o desafio de simular o trabalho de um **analista de dados** em uma consultoria financeira especializada no mercado de ações brasileira, chamada **Bulltrend**.

O objetivo foi desenvolver um **relatório interativo** que auxiliasse o time de consultoria a analisar estrategicamente os ativos das carteiras de seus clientes, combinando duas importantes correntes de análise de ativos: **análise fundamentalista** e **análise gráfica**.

---

## Base de Dados

Trabalhamos com duas bases de dados complementares:

- **Cotações**:  
  Geradas no período de 01/08/2022 a 01/08/2023, utilizando a biblioteca `yfinance`, que coleta dados de cotações de ativos listados na bolsa de valores brasileira e mundial a partir do site **Yahoo Finance**.

- **Indicadores fundamentalistas**:  
  Obtidos através da biblioteca `fundamentus`, que extrai dados diretamente do site **Fundamentus**, consolidando indicadores financeiros de ativos brasileiros.

---

## Ferramentas e Técnicas Utilizadas

Para alcançar o resultado, utilizamos **Python** e **Power BI**, realizando a extração, transformação e carga de dados (ETL) e culminando na criação de um **dashboard completo**. Durante o projeto, foram aprofundados os seguintes conhecimentos:

- Extração de dados financeiros de ativos utilizando APIs com a linguagem Python;
- Configuração de um ambiente virtual para integração entre Python e Power BI;
- Realização de processos de ETL diretamente no Power BI, integrando Python para manipulação avançada de dados;
- Criação de visualizações impactantes, tanto nativas do Power BI quanto geradas por scripts Python.

---

## Insights e Perguntas de Negócio

Com o dashboard finalizado, é possível responder a perguntas estratégicas, como:

1. **Quais foram os valores mínimo e máximo registrados pelos ativos entre 01/08/2022 e 01/08/2023?**  
2. **Qual era o valor de mercado e o valor intrínseco dos ativos em 01/08/2023?**  
3. **Como se comportaram os principais indicadores financeiros (P/L, P/VP, DY e ROE) durante o período?**  
4. **Quais foram as receitas líquidas e os lucros líquidos acumulados nos últimos 3 meses (maio-julho de 2023) e nos 12 meses (agosto de 2022 a julho de 2023)?**  
5. **Como o setor de cada ativo (ex.: Bebidas para ABEV3) impactou seu desempenho financeiro durante o intervalo?**

---

## Conclusão

Este projeto foi uma excelente oportunidade para simular o papel de um analista de dados, integrando ferramentas poderosas como **Python** e **Power BI** para transformar dados brutos em insights valiosos e direcionar tomadas de decisão estratégicas.

---

## Pré-requisitos para Reproduzir o Projeto

- **Bibliotecas Python**:  
  - `yfinance`  
  - `fundamentus`

- **Ferramentas Utilizadas**:  
  - Python 3.10+  
  - Power BI  

### Como executar:

1. Instale as bibliotecas necessárias utilizando `pip install yfinance fundamentus`.
2. Configure o ambiente virtual com Python integrado ao Power BI.
3. Execute os scripts para gerar as bases de dados de cotações e indicadores.
4. Importe os dados para o Power BI e crie as visualizações conforme o projeto.

---

### Contato

Se você tiver dúvidas ou quiser saber mais sobre este projeto, fique à vontade para entrar em contato!
**Meu LinkedIn**: [Carolyne Soares](https://www.linkedin.com/in/carolyne-soares)




