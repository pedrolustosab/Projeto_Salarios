
# DataScience Salary Insights
#### Projeto Final Ada Tech | Segundo Módulo - Dados - Turma 1104


#### Descrição do Projeto
Este projeto tem como objetivo proporcionar aos usuários uma visão abrangente sobre os cargos existentes na área de Data Science, fornecendo insights valiosos sobre médias salariais com base no ano e nível de experiência. Desenvolvido como um projeto técnico, ele utiliza uma variedade de funções para gerenciar dados, permitindo aos usuários inserir, remover, atualizar registros e realizar análises estatísticas.

#### Conjunto de Dados
O dataset utilizado foi adquirido no Kaggle e passou por um processo de ETL para garantir a qualidade e relevância das informações. O conjunto original continha 8.805 registros, mas após o processo de filtragem e tradução, mantivemos 219 dados específicos para análise.

#### ETL (Extract, Transform, Load)
#####  O processo de ETL envolveu as seguintes etapas:

1. Extração (Extract):
* Os dados foram carregados a partir do arquivo 'salaries_BK.json', totalizando 8.805 registros.
* Apenas os cargos relacionados a Data Science foram mantidos, resultando em 219 registros.


2. Transformação (Transform):
* Foi adicionado um ID único para cada registro.
* As chaves do conjunto de dados foram traduzidas para o português.
* Os níveis de experiência e cargos foram traduzidos para melhor compreensão.
* Algumas informações foram removidas, como moeda do salário, salário em dólares.

3. Carregamento (Load):
* Um novo arquivo 'salarios.json' foi gerado, contendo os dados transformados e filtrados.


## Funcionalidades Principais

1. Inserção e Atualização de Dados:

* Permite aos usuários inserir novos registros, capturando informações como ano de trabalho, nível de experiência, cargo, salário em dólares, residência do funcionário, localização da empresa e tamanho da empresa.
* Oferece a funcionalidade de atualizar informações existentes.

2. Remoção de Registros:

* Permite a remoção de registros com base no ID, proporcionando flexibilidade na gestão dos dados.

3. Filtragem de Dados:

* Implementa filtros para análises específicas, incluindo ano de trabalho, nível de experiência, cargo, residência do funcionário, localização da empresa e tamanho da empresa.

4. Estatísticas e Análises Salariais:

* Calcula estatísticas como número de registros, média salarial, salário mínimo e máximo.
* Gera um arquivo CSV contendo estatísticas específicas, como o salário mínimo associado a um ID.

## Estrutura do Projeto
O projeto é estruturado com funções específicas para cada tarefa, garantindo modularidade e facilidade de manutenção. As informações são armazenadas em um arquivo JSON, proporcionando persistência de dados.

## Conclusão
Este código fornece uma base para a gestão e análise de dados de salários, oferecendo funcionalidades abrangentes e uma interface simples para interação. Suas capacidades podem ser estendidas com melhorias na estruturação e implementação de novas funcionalidades.


## Autores

* Eliane Santos
* Ingrid Barbosa
* Isadora Mesquita
* Pedro Lustosa
* Rafael Guisso


