# Automação de Relatórios com Python e Pandas

Projeto de automação desenvolvido em Python para otimizar o fechamento e envio de relatórios comerciais a partir de bases de dados volumosas.

## 📌 Sobre o Projeto
O script realiza a leitura e o processamento de uma planilha com mais de 100 mil registros de vendas, calcula os principais indicadores de desempenho (KPIs) por unidade e integra-se à API do Microsoft Outlook para estruturar o relatório final em formato executivo, pronto para envio à liderança.

## 📊 Indicadores Consolidados
- **Faturamento:** Valor monetário total vendido por unidade/loja.
- **Quantidade:** Volume total de peças comercializadas por unidade.
- **Ticket Médio:** Razão entre faturamento e quantidade vendida por loja.

## 🛠️ Tecnologias e Bibliotecas
- **Python 3**
- **Pandas:** Manipulação, filtragem, agrupamento (`groupby`) e cálculo dos dados.
- **pywin32:** Comunicação com o sistema operacional Windows e interface MAPI do Microsoft Outlook.
- **HTML/CSS:** Formatação visual das tabelas com máscara de moeda (R$).
- **Microsoft Excel:** Fonte de dados de entrada.

