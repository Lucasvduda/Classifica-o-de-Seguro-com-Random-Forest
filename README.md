# Classifica-o-de-Seguro-com-Random-Forest
Classificação de Seguro com Random Forest
Descrição
Este projeto utiliza o algoritmo Random Forest para classificar dados relacionados a seguros, com base no dataset insurance.csv. O objetivo é prever a categoria de seguro de um cliente com base em variáveis como idade, sexo, custos médicos, e outras informações relevantes.

O projeto demonstra uma abordagem completa para resolver um problema de classificação, incluindo carregamento de dados, pré-processamento, treinamento de modelo, avaliação de desempenho e visualização de uma árvore de decisão individual.

Estrutura do Projeto
insurance.csv: Dataset utilizado para análise e treinamento do modelo.

main.py: Script principal contendo todo o código do projeto.

README.md: Este arquivo, com detalhes sobre o projeto.

requirements.txt: Lista de dependências para reproduzir o projeto.

Tecnologias Utilizadas
Python

Bibliotecas principais:

pandas: Manipulação de dados.

numpy: Operações matemáticas e manipulação de arrays.

scikit-learn: Implementação do algoritmo Random Forest e métricas de avaliação.

matplotlib: Visualização de dados.

Funcionalidades
Pré-processamento de Dados:

Remoção de colunas desnecessárias.

Conversão de variáveis categóricas em numéricas usando LabelEncoder.

Treinamento de Modelo:

Modelo baseado no algoritmo Random Forest com 500 árvores, profundidade máxima de 20, e até 12 nós-folha.

Avaliação do Modelo:

Métricas: Acurácia, Precisão, Recall e F1-Score.

Relatório detalhado com classification_report.

Visualização:

Exibição de uma árvore individual da floresta para análise detalhada.

Como Executar o Projeto
Clone o repositório:
git clone https://github.com/seu_usuario/classificacao-seguro-randomforest.git


Instale as dependências:
pip install -r requirements.txt


Coloque o arquivo insurance.csv na pasta principal do projeto.

Execute o script:
python main.py


Resultados
O modelo obteve desempenho elevado com base nas métricas:

Acurácia: ~XX%

Precisão: ~XX%

Recall: ~XX%

F1-Score: ~XX%

Uma árvore de decisão foi visualizada para entender como as decisões são feitas.

Exemplo de Uso
Caso deseje prever a categoria de seguro para um novo cliente, basta adicionar os dados em um formato específico e executar o script. A árvore de decisão visualiza como o modelo processa as variáveis para chegar à classificação.

Contribuições
Sinta-se à vontade para abrir issues ou enviar pull requests para melhorias no projeto.
