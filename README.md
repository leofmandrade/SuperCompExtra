# Algoritmo Genético em C++ com Plotagem de Gráficos em Python

Este projeto implementa um algoritmo genético em C++ para resolver o problema da mochila (Knapsack Problem). O algoritmo busca a solução ótima para o problema, onde a mochila tem uma capacidade limitada e os itens têm pesos e valores variados. O objetivo é maximizar o valor total dos itens na mochila sem exceder a capacidade.

## Estrutura do Projeto
- **Untitled1.ipynb**: Arquivo Jupyter com as células que fazem:
  - **algoritmo.cpp**: Implementação do algoritmo genético em C++.
  - **fitness_data.txt**: Arquivo gerado pelo programa em C++ que contém a aptidão das melhores soluções ao longo das gerações.
  - **plot_fitness.py**: Script em Python para plotar os dados de aptidão a partir do arquivo `fitness_data.txt`.

## Algoritmo Genético

O algoritmo genético segue as etapas padrão de inicialização da população, cálculo da aptidão, seleção dos pais, cruzamento e mutação. As variáveis e funções principais são:

- `num_itens`, `capacidade_mochila`, `solucoes_por_pop`, `num_geracoes`: Constantes definindo as configurações do problema.
- `gerar_itens()`: Função para gerar itens aleatórios com pesos e valores.
- `inicializar_populacao()`: Função para inicializar a população de soluções aleatoriamente.
- `calcular_aptidao()`: Função para calcular a aptidão (valor total) de uma solução.
- `selecionar_pais()`: Função para selecionar os melhores pais com base na aptidão.
- `cruzamento()`: Função para realizar o cruzamento entre dois pais.
- `mutacao()`: Função para realizar a mutação de um descendente.
- `otimizar()`: Função principal que executa o algoritmo genético ao longo de várias gerações e salva os dados de aptidão em um arquivo.


