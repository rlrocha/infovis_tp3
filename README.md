# TP 3 InfoVis

Trabalho desenvolvido na disciplina Visualização da Informação do Programa de Pós-Graduação em Ciência da Computação (PPGCC) da Universidade Federal do Pará (UFPA) em 2021.1.

O trabalho prático 3 foi desenvolvido com base no desafio anual denominado VAST Challenge 2021. O objetivo do desafio VAST anual é avançar o campo de análise visual por meio da competição. O desafio foi projetado para ajudar os pesquisadores a entender como seu software seria usado em uma variedade de tarefas analíticas e estimular a inovação em transformações de dados e visualizações interativas. Os problamas do VAST Challenge fornecem aos pesquisadores tarefas e conjuntos de dados realistas para avaliar o software.

## Desafio

O desafio escolhido é o Mini-Challenge 2, que visa analisar a movimentação e dados de rastreamento dos funcionários da GAStech. Os dados utilizados são de deuas samans antes do desaparecimento de algumas pessoas da GAStech, e são formados por dados de rastreamento (GPS), além de transações de cartões de crédito e uso do cartão fidelidade. As bases utilizadas estão presentes no diretório [datasets](datasets).

## Desenvolvimento

Abaixo estão as descrição das funcionalidades dos códigos utilizados de apoio para análise dos dados, bem como o código principal com as visualizações realizados para responder as perguntas do desafio.

* [Joining Datasets](Joining Datasets.ipynb): Utilizado para realizar a junção das bases do cartão de crédito e fidelidade.
* [preprocessing](preprocessing.ipynb): Utilizado para aplicar alguns ajustes necessários nas bases.
* [ts_analysis](ts_analysis.ipynb): Utilizado para analisar o tempo de parada de cada veículo, possibilitando a descoberta das coordenadas dos locais, além de relacionar os ID's dos veículos aos cartões de crédito e fidelidade.
