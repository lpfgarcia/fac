# Fiocruz Article Classification 

Este projeto é uma análise de classificação de artigos da Fiocruz, utilizando Grandes Modelos de Linguagem (LLMs) e comparando-os com a classificação feita por especialistas.

## Estrutura do Projeto

- **prediction/**: Diretório para scripts e notebooks relacionados às previsões dos modelos de linguagem.
- **expert_analysis.csv**: Arquivo CSV contendo a classificação feita por especialistas (autores das publicações).
- **models.ipynb**: Notebook Jupyter contendo o código para treinamento e aplicação dos Modelos de Linguagem de Grande Escala (LLMs) para classificação.
- **preprocessing.ipynb**: Notebook Jupyter com os procedimentos de pré-processamento dos dados.
- **requirements.txt**: Arquivo contendo as dependências do projeto que precisam ser instaladas.
- **results.ipynb**: Notebook Jupyter para visualização e análise dos resultados obtidos nas classificações.
- **unidades_26082024-translated.csv**: Conjunto de dados traduzido, utilizado para análise comparativa.
- **unidades_26082024.xlsx**: Versão original do conjunto de dados para análise.

## Configuração do Ambiente

Para configurar o ambiente de desenvolvimento para este projeto, siga as instruções abaixo:

1. **Instalação do Miniconda:**

   Antes de começar, certifique-se de ter o Miniconda instalado. Você pode baixar e instalar o Miniconda a partir do site oficial: [Miniconda](https://docs.conda.io/en/latest/miniconda.html).


2. **Criando o ambiente conda:**

   Depois de instalar o Miniconda, crie um novo ambiente conda com Python 3.11 executando o seguinte comando no seu terminal:

   ```bash
   conda create -n biblios python=3.11 -y
   ```

3. **Ativando o ambiente:**

   Em seguida, ative o ambiente conda recém-criado executando o comando:
   
   ```bash
   conda activate biblios
   ```

4. **Instalando pacotes:**

   Agora, instale todas as dependências necessárias para este projeto executando o seguinte comando:

   ```bash
   pip install -r requirements.txt
   ```

5. **Executando os Notebooks:**

   Você pode começar a explorar os dados e treinar modelos executando os notebooks na pasta `notebooks/`. Para iniciar o Jupyter Notebook, basta digitar o seguinte comando no terminal:

   ```bash
   jupyter notebook
   ```
   
## Licença

Este projeto está licenciado sob a GNU v3. Consulte o arquivo `LICENSE` para obter mais detalhes.
