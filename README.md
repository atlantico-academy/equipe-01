# Abalones - Análise e Predições por meio das Características Físicas

Propõe a análise de dados do molusco Abalone por meio de técnicas estatísticas e de Machine Learning utilizando a metodologia CRISP-DM. O Abalone é um organismo marinho de importância econômica, sendo crucial compreender padrões e características que influenciam seu desenvolvimento. Neste dataset é abordado desde a coleta inicial de dados até a implementação de modelos preditivos, explorando insights para o entendimento das características físicas desse molusco.

A análise de dados do Abalone é relevante tanto do ponto de vista ambiental quanto econômico. Compreender fatores que afetam seu crescimento e comportamento pode fornecer informações para a preservação dessa espécie. A aplicação prática de técnicas de ciência de dados a um contexto biológico específico enriquecerá as habilidades e conhecimento dos participantes, expandido horizontes para um amplo aprendizado.

Insira aqui um resumo do projeto que será construído. Tente apresentar uma justificativa para o projeto. É desejável que também se insira um [graphical abstract](https://www.elsevier.com/authors/tools-and-resources/visual-abstract).

## Resumo Gráfico

    

## Desenvolvedores

 - [Anne Carvalho](github.com/annecarv)
 - [Augusto César](github.com/augustces)
 - [Catherine Markert](github.com/cathmarkert)
 - [Hernando Henrique](github.com/hernandohas)
 - [João](url-do-github-do-desenvolvedor-#5)

---

### Organização de diretórios


```
.
├── data/              # Diretório contendo todos os arquivos de dados
│   ├── external/      # Arquivos de dados de fontes externas
│   ├── interim/       # Arquivos de dados intermediários
│   ├── processed/     # Arquivos de dados processados
│   └── raw/           # Arquivos de dados originais, imutáveis
├── docs/              # Documentação gerada através da biblioteca mkdocs
├── models/            # Modelos treinados e serializados, predições ou resumos de modelos
├── notebooks/         # Diretório contendo todos os notebooks utilizados nos passos
├── references/        # Dicionários de dados, manuais e todo o material exploratório
├── src/               # Código fonte utilizado nesse projeto
│   ├── data/          # Classes e funções utilizadas para download e processamento de dados
│   ├── deployment/    # Classes e funções utilizadas para implantação do modelo
│   └── model/         # Classes e funções utilizadas para modelagem
├── app.py             # Arquivo com o código da aplicação do streamlit
├── Procfile           # Arquivo de configuração do heroku
├── pyproject.toml     # Arquivo de dependências para reprodução do projeto
├── poetry.lock        # Arquivo com sub-dependências do projeto principal
├── README.md          # Informações gerais do projeto
└── tasks.py           # Arquivo com funções para criação de tarefas utilizadas pelo invoke

```