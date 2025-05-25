# Análise de Evasão de Clientes (Churn) - Telecom X BR

## Descrição do Projeto

Este projeto realiza uma análise completa do dataset de clientes da Telecom X BR com o objetivo de identificar os fatores que levam à evasão (Churn) e propor estratégias de retenção. Através de etapas de Extração, Tratamento e Análise Exploratória de Dados, visando compreender o perfil dos clientes que cancelam seus serviços.

## Dados

Os dados utilizados neste projeto foram importados da API Telecom X

📌 Link da API:
- **Dados de Clientes:**
🔗https://github.com/ingridcristh/challenge2-data-science/blob/main/TelecomX_Data.json
- **Dicionário de Dados:**
🔗https://github.com/ingridcristh/challenge2-data-science/tree/main

## Tecnologias e Bibliotecas Utilizadas

- Python
- Pandas (para manipulação e análise de dados)
- NumPy (para operações numéricas)
- Matplotlib (para visualização de dados)
- Seaborn (para visualização de dados estatísticos)
- Requests (para extração de dados via URL)

## Como Visualizar e Executar o Projeto

O projeto está contido em um notebook Colab.

1. **Acessar o Notebook:** Clique no link abaixo para visualizar o notebook diretamente no GitHub:
🔗https://colab.research.google.com/drive/18IvbbDuEsiDhCDt3Iti1oHZorIB5RJ5G?usp=sharing

3. **Executar no Google Colab:**
   - Abra o link do notebook no GitHub.
   - Clique no ícone "Open in Colab" (Abrir no Colab) que geralmente aparece no topo da visualização do notebook no GitHub.
   - Execute as células sequencialmente para replicar a análise.

## Estrutura do Repositório

- "CHALLENGE_TELECOM.ipynb": O notebook principal contendo todo o código e relatório.
- `TelecomX_Data.json`: Arquivo de dados original.
- `TelecomX_dicionario.md`: Dicionário de dados.
- `README.md`: Este arquivo.

## Conclusões Principais

- A análise exploratória e de correlação revelou padrões significativos relacionados à evasão de clientes:

- ⏳Tempo de Permanência é Crítico: Clientes com menor tempo de permanência (tenure) são significativamente mais propensos a evadir. A retenção nos primeiros meses é fundamental.<br>
- 📑Tipo de Contrato: Clientes com contratos mensais apresentam uma taxa de evasão muito maior em comparação com aqueles com contratos de um ou dois anos.
- 💰Método de Pagamento e Conveniência: Métodos de pagamento menos convenientes, como cheque eletrônico, estão associados a uma maior taxa de evasão. Pagamentos automáticos (transferência bancária, cartão de crédito) indicam maior estabilidade e menor churn.
- 🖇Serviços Adicionais Agem Como Retentores: Clientes que assinam serviços adicionais, especialmente os relacionados à segurança (OnlineSecurity, OnlineBackup, DeviceProtection) e suporte (TechSupport), tendem a ter uma taxa de evasão consideravelmente menor. O número total de serviços adicionais também está negativamente correlacionado com o Churn.<br>

## Recomendações Chave

- [Liste 2-3 recomendações principais do seu relatório, ex: Focar na retenção de novos clientes e promover contratos mais longos.]
- [Outra recomendação chave, ex: Incentivar a adesão a servços adicionais de segurança.]

## Autor

- Juliane Borges
- GitHub:https://github.com/JULIANNEBBORGES/CHALLENGE_TELECOM_X_BR
- LinkedIn: https://www.linkedin.com/in/julianebb



