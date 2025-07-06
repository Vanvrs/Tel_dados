# Análise de Evasão de Clientes - Telecom X

## 📌 Visão Geral
Este projeto tem como objetivo analisar os dados de clientes da Telecom X para identificar padrões e fatores que contribuem para a evasão de clientes (churn). A análise utiliza Python e suas principais bibliotecas para extrair insights valiosos que ajudarão a empresa a desenvolver estratégias de retenção de clientes.

## 📂 Estrutura do Projeto
O projeto consiste em um script Python que realiza:
1. Extração de dados diretamente da API da Telecom X
2. Transformação dos dados em um DataFrame pandas
3. Análise Exploratória de Dados (EDA)
4. Visualizações estratégicas para identificar padrões

## 🛠️ Tecnologias Utilizadas
- Python 3.x
- Pandas (para manipulação de dados)
- Matplotlib/Seaborn (para visualizações)
- Requests (para acesso à API)
- NumPy (para operações numéricas)

## 🔧 Como Executar
1. Certifique-se de ter Python 3.x instalado
2. Instale as dependências:
   ```bash
   pip install pandas matplotlib seaborn requests numpy
   ```
3. Execute o script Python

## 📊 Principais Análises Realizadas
1. **Carregamento dos Dados**:
   - Conexão com a API para obter dados em formato JSON
   - Conversão para DataFrame pandas

2. **Análise Exploratória**:
   - Verificação da estrutura dos dados (colunas, tipos de dados)
   - Identificação de valores ausentes
   - Estatísticas descritivas das variáveis numéricas
   - Distribuição das variáveis categóricas

3. **Análise de Churn**:
   - Distribuição da variável target (Churn)
   - Taxa de evasão por categoria (gênero, tipo de contrato, etc.)
   - Correlações entre variáveis numéricas

4. **Visualizações**:
   - Gráficos de distribuição para variáveis numéricas e categóricas
   - Heatmap de correlação
   - Comparação de taxas de churn entre diferentes grupos

## 📈 Insights Principais
(O relatório completo de insights seria gerado após execução do código)
- Variáveis mais correlacionadas com churn
- Grupos de clientes com maior risco de evasão
- Fatores demográficos e de serviço associados à retenção

## ➡️ Próximos Passos
1. Tratamento de dados ausentes
2. Engenharia de features
3. Desenvolvimento de modelo preditivo
4. Criação de estratégias de retenção baseadas nos insights

## 📝 Observações
- O código está configurado para rodar em notebooks Jupyter (%matplotlib inline)
- Pode ser adaptado para scripts Python convencionais removendo a linha magic
- Os dados são carregados diretamente do repositório GitHub especificado
