# Análise de Dados Netflix: Séries e Filmes (Até 2025)

## 📊 Visão Geral do Projeto

Este projeto consiste em uma análise exploratória de dados (EDA) detalhada sobre o catálogo de séries e filmes da Netflix, utilizando dados atualizados até o ano de 2025. O objetivo é extrair insights sobre tendências de conteúdo, popularidade de gêneros, diretores, atores, países de origem e padrões de adição de títulos à plataforma ao longo do tempo.

### 🎯 Objetivos da Análise

* Compreender a composição do catálogo da Netflix (filmes vs. séries).
* Identificar os gêneros mais predominantes e populares.
* Analisar a distribuição de conteúdo por ano de lançamento e adição à plataforma.
* Descobrir os diretores e atores mais prolíficos.
* Explorar a origem geográfica do conteúdo.
* Analisar a distribuição de classificações etárias (ratings) e numéricas.
* Visualizar a distribuição da duração de filmes e o número de temporadas de séries.

## 🚀 Tecnologias Utilizadas

* **Python:** Linguagem de programação principal.
* **Jupyter Notebook:** Ambiente interativo para desenvolvimento e apresentação da análise (`analise_netflix_series_filmes_2025.ipynb`).
* **Pandas:** Biblioteca para manipulação e análise de dados.
* **Matplotlib:** Biblioteca para criação de gráficos estáticos.
* **Seaborn:** Biblioteca para visualização de dados estatísticos (baseada no Matplotlib).
* **Git & GitHub:** Controle de versão e hospedagem do projeto.

## 📁 Estrutura do Projeto

O repositório está organizado da seguinte forma:

├── dados/

│   ├── netflix_movies_detailed_up_to_2025.csv

│   └── netflix_tv_shows_detailed_up_to_2025.csv

├── imagens/

│   ├── (Gráficos gerados pela análise: ex: distribuicao_conteudo_por_ano_lancamento.png, top_10_generos_filmes.png, etc.)

├── notebook/

│   └── analise_netflix_series_filmes_2025.ipynb

├── .gitignore

└── README.md


* `dados/`: Contém os arquivos CSV brutos utilizados na análise.
* `imagens/`: Armazena todos os gráficos e visualizações gerados durante a EDA.
* `notebook/`: Contém o Jupyter Notebook principal com todo o código de análise.
* `.gitignore`: Define quais arquivos e pastas devem ser ignorados pelo Git.
* `README.md`: Este arquivo, fornecendo uma visão geral do projeto.

## 📊 Análise e Resultados (Insights Principais)

Nesta seção, você deve resumir os insights mais interessantes que obteve dos seus gráficos. **Seja conciso e use os nomes dos gráficos como referência.**

**Preencha com as SUAS PRÓPRIAS CONCLUSÕES baseadas nos gráficos gerados:**

* **Crescimento do Catálogo:** Observe a "Distribuição de Conteúdo por Ano de Adição à Plataforma". Há um crescimento constante? Houve picos ou quedas em anos específicos?
    * *Exemplo:* "Os gráficos de adição de conteúdo à plataforma ('distribuicao_conteudo_por_ano_adicao.png') indicam um crescimento significativo do catálogo da Netflix a partir de 2015, com um pico notável em [Ano do Pico], mostrando a expansão da empresa."
* **Tendências de Lançamento:** Analise a "Distribuição de Conteúdo Netflix por Ano de Lançamento". Há mais conteúdo recente ou mais antigo?
    * *Exemplo:* "A maioria dos títulos lançados anualmente se concentra em [intervalo de anos], enquanto a plataforma continua a adicionar filmes e séries de anos anteriores, conforme visto em 'distribuicao_conteudo_por_ano_lancamento.png'."
* **Gêneros Dominantes:** Quais são os gêneros mais comuns para filmes e séries nos gráficos de "Top 10 Gêneros"?
    * *Exemplo:* "Os gêneros 'Drama' e 'Comédia' se destacam consistentemente como os mais presentes tanto para filmes ('top_10_generos_filmes.png') quanto para séries ('top_10_generos_series.png'), refletindo um possível foco nesses segmentos."
* **Classificações Numéricas:** Observe os gráficos de "Distribuição de Classificações Numéricas". Quais faixas de pontuação são mais comuns? O que o valor 0.0 pode indicar?
    * *Exemplo:* "A análise das classificações numéricas ('distribuicao_ratings_numericos_filmes.png' e 'distribuicao_ratings_numericos_series.png') mostra que a maior parte do conteúdo tem uma pontuação entre [valor mínimo] e [valor máximo], sugerindo uma vasta oferta de títulos de qualidade média a alta. A alta contagem de 0.0 pode indicar conteúdo não avaliado."
* **Origem do Conteúdo:** Quais países se destacam na produção de filmes e séries? Veja os gráficos de "Top 10 Países Produtores".
    * *Exemplo:* "Os Estados Unidos são o principal país de origem para filmes e séries na Netflix, como evidenciado nos gráficos de 'top_10_paises_filmes.png' e 'top_10_paises_series.png'. Há também uma presença notável de produções de [Outro País 1] e [Outro País 2]."
* **Duração e Formato de Séries/Filmes:** Quais são as durações mais comuns para filmes e quantas temporadas são mais frequentes para séries?
    * *Exemplo:* "A maioria dos filmes na Netflix tem uma duração concentrada entre [X] e [Y] minutos ('distribuicao_duracao_filmes.png'). Para séries, observa-se uma clara preferência por títulos com 1 ou 2 temporadas ('distribuicao_num_temporadas_series.png'), o que pode influenciar a estratégia de consumo."

## 🤝 Como Contribuir

Sinta-se à vontade para abrir issues ou pull requests para melhorias, sugestões ou correções neste projeto. Toda contribuição é bem-vinda!

## 📧 Contato

* **[Diego Juliano Lima Figueredo]**
* **LinkedIn:** https://www.linkedin.com/in/diego-juliano-lima-figueredo-7112816a/

## 📜 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE.md](LICENSE.md) (se você for adicionar um arquivo LICENSE.md) para detalhes. Caso contrário, remova esta linha ou adapte-a.