# 🎬 Análise de Dados Netflix: Catálogo de Séries e Filmes (Até 2025)

![Netflix Logo](imagens/netflix.png)

## 📊 Visão Geral do Projeto

Este repositório apresenta uma **Análise Exploratória de Dados (EDA)** aprofundada sobre o vasto catálogo de séries e filmes da Netflix, utilizando dados atualizados até o ano de 2025. O projeto visa desvendar padrões, tendências e características do conteúdo disponível na plataforma, fornecendo insights valiosos sobre sua evolução e composição.

### 🎯 Objetivos da Análise

* **Compreender a Proporção:** Analisar a distribuição entre filmes e séries no catálogo da Netflix.
* **Tendências Temporais:** Investigar a evolução do volume de conteúdo por ano de lançamento e por ano de adição à plataforma.
* **Conteúdo Popular:** Identificar os gêneros mais predominantes, bem como os diretores e atores mais prolíficos.
* **Geografia do Conteúdo:** Explorar a origem dos títulos, destacando os países que mais contribuem para o catálogo.
* **Classificação Etária e Avaliações:** Examinar a distribuição das classificações indicativas e das avaliações numéricas do conteúdo.
* **Características do Conteúdo:** Analisar a distribuição da duração de filmes e o número de temporadas de séries.

## 🚀 Tecnologias Utilizadas

Este projeto foi desenvolvido utilizando as seguintes ferramentas e bibliotecas:

* **Python:** Linguagem de programação fundamental para análise e manipulação de dados.
* **Jupyter Notebook:** Ambiente interativo para desenvolvimento, execução e documentação da análise (`notebook/analise_netflix_series_filmes_2025.ipynb`).
* **Pandas:** Biblioteca robusta para estruturas de dados e ferramentas de análise de dados de alto desempenho.
* **Matplotlib:** Biblioteca para criação de gráficos estáticos, animados e interativos em Python.
* **Seaborn:** Biblioteca de visualização de dados baseada em Matplotlib, fornecendo uma interface de alto nível para gráficos estatísticos atraentes.
* **Git & GitHub:** Para controle de versão do projeto e hospedagem do código-fonte.

## 📁 Estrutura do Projeto

O repositório está organizado de forma clara para facilitar a navegação e compreensão:

├── dados/

│   ├── netflix_movies_detailed_up_to_2025.csv

│   └── netflix_tv_shows_detailed_up_to_2025.csv

├── imagens/

│   ├── (Gráficos gerados pela análise: ex: distribuicao_conteudo_por_ano_lancamento.png, top_10_generos_filmes.png, etc.)

├── notebook/

│   └── analise_netflix_series_filmes_2025.ipynb

├── .gitignore

└── README.md


* `dados/`: Contém os conjuntos de dados brutos em formato CSV utilizados na análise.
* `imagens/`: Armazena todos os gráficos e visualizações gerados durante a fase de Análise Exploratória de Dados.
* `notebook/`: Contém o Jupyter Notebook principal, que engloba todas as etapas da análise, desde o carregamento dos dados até a geração dos insights e gráficos.
* `.gitignore`: Arquivo de configuração para o Git, que especifica quais arquivos e diretórios devem ser ignorados do controle de versão.
* `README.md`: Este documento, fornecendo uma visão geral completa do projeto.

## 📈 Análise e Resultados (Insights Principais)

A análise dos dados da Netflix revelou padrões e tendências interessantes no catálogo da plataforma. Abaixo estão os principais insights derivados das visualizações:

### 1. Evolução do Catálogo ao Longo do Tempo

* **Ano de Lançamento:** A distribuição do ano de lançamento (`distribuicao_conteudo_por_ano_lancamento.png`) mostra que, embora a Netflix adicione conteúdo de diversas épocas, há uma clara predominância de títulos mais recentes, indicando um foco contínuo em produções atuais.
* **Ano de Adição à Plataforma:** O volume de conteúdo adicionado à Netflix (`distribuicao_conteudo_por_ano_adicao.png`) apresenta um crescimento exponencial, com um pico significativo por volta de [**INSIRA O ANO DO PICO DE ADIÇÃO, ex: 2020-2021**]. Isso reflete a fase de intensa expansão e investimento da plataforma em seu catálogo.

### 2. Gêneros e Conteúdo

* **Gêneros de Filmes:** Os **Top 10 Gêneros de Filmes** (`top_10_generos_filmes.png`) destacam [**INSIRA AQUI OS PRINCIPAIS GÊNEROS DE FILMES, ex: "Drama", "Comédia", "Documentário"**] como os mais abundantes, sugerindo que esses são pilares do acervo cinematográfico da Netflix.
* **Gêneros de Séries:** Similarmente, para séries, os **Top 10 Gêneros de Séries** (`top_10_generos_series.png`) revelam a popularidade de categorias como [**INSIRA AQUI OS PRINCIPAIS GÊNEROS DE SÉRIES, ex: "Drama", "Séries de TV", "Comédia"**], indicando a diversidade e o apelo a diferentes públicos.

### 3. Principais Talentos

* **Diretores:** Os **Top 10 Diretores** para filmes (`top_10_diretores_filmes.png`) e séries (`top_10_diretores_series.png`) mostram a influência de certos criadores, com [**INSIRA O NOME DE UM OU DOIS DIRETORES PRINCIPAIS**] frequentemente contribuindo com múltiplos títulos.
* **Atores/Atrizes:** Os **Top 10 Atores/Atrizes** (`top_10_atores_filmes.png`, `top_10_atores_series.png`) indicam figuras recorrentes no catálogo, como [**INSIRA O NOME DE UM OU DOIS ATORES/ATRIZES PRINCIPAIS**], que participam de diversas produções, o que pode atrair fãs específicos.

### 4. Classificações e Origem do Conteúdo

* **Classificações Numéricas:** A **Distribuição de Classificações Numéricas** para filmes (`distribuicao_ratings_numericos_filmes.png`) e séries (`distribuicao_ratings_numericos_series.png`) revela uma concentração de títulos com avaliações entre [**INSIRA A FAIXA DE VALORES MAIS COMUM, ex: 6.0 e 8.0**]. A presença de valores `0.0` pode indicar conteúdo ainda não avaliado ou valores ausentes nos dados originais.
* **Países Produtores:** Os **Top 10 Países Produtores** (`top_10_paises_filmes.png`, `top_10_paises_series.png`) demonstram que [**INSIRA O PAÍS PRINCIPAL, ex: "Estados Unidos"**] é o maior contribuinte de conteúdo, seguido por uma crescente diversidade de produções internacionais, como [**INSIRA OUTROS PAÍSES RELEVANTES, ex: "Índia", "Reino Unido"**].

### 5. Características de Duração

* **Duração de Filmes:** O gráfico de **Duração de Filmes** (`distribuicao_duracao_filmes.png`) indica que a maioria dos filmes na Netflix tem uma duração concentrada entre [**INSIRA A FAIXA DE MINUTOS MAIS COMUM, ex: 90 e 120 minutos**], alinhando-se a um formato padrão de longa-metragem.
* **Número de Temporadas de Séries:** A **Distribuição do Número de Temporadas de Séries** (`distribuicao_num_temporadas_series.png`) revela uma forte predominância de séries com 1 temporada, o que pode indicar uma estratégia da Netflix de lançar séries mais curtas ou com potencial para futuras temporadas, dependendo do sucesso inicial.

## 🤝 Como Contribuir

Contribuições são bem-vindas! Se você tiver sugestões de melhorias, correções ou novas análises, sinta-se à vontade para:

1.  Abrir uma [Issue](https://github.com/diegojlfigueredo/analise_netflix_series_filmes_2025/issues) para relatar bugs ou sugerir novas funcionalidades.
2.  Criar um [Pull Request](https://github.com/diegojlfigueredo/analise_netflix_series_filmes_2025/pulls) com suas modificações e melhorias.

## 📧 Contato

* **[Diego Juliano Lima Figueredo]**
* **LinkedIn:** https://www.linkedin.com/in/diego-juliano-lima-figueredo-7112816a/

## 📜 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE.md](LICENSE.md) (se você for adicionar um arquivo LICENSE.md) para detalhes. Caso contrário, remova esta linha ou adapte-a.