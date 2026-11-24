# Áreas de conhecimento
Lista das áreas que estudei e as quais escrevi sobre. Assuntos que não estão listados são aqueles que ainda não estudei.
Os assuntos seguem o currículo da IEEE Computer Society e estudos pessoais no tempo livre. Esta lista está incompleta, pois ainda estou estudando novos assuntos até hoje.
Meu foco principal atual é Algoritmos.
Tradução automática feita por IA com edições manuais.

# Algoritmos
**Estruturas de Dados e Algoritmos**
1. Tipo Abstrato de Dados e operações de dicionário (inserir, remover, buscar)
2. Arrays - a. Numéricos, não numéricos, cadeias de caracteres. b. Vetor vs matriz
3. Structs/Tuplas e Objetos (POO)
4. Listas encadeadas - a. Simples vs dupla e linear vs circular
5. Pilhas
6. Filas e deques - a. Fila de prioridade baseada em heap
7. Tabelas hash/mapas - a. Resolução de colisões e complexidade (ex.: sondagem, encadeamento, rehash)
8. Grafos (ex.: [não] direcionados, [a]cíclicos, [des]conexos e [não] ponderados) - a. Lista de adjacência vs matriz
9. Árvores - a. Binárias e de busca. b. Balanceadas (ex.: AVL, rubro-negra, heap)
10. Conjuntos
11. Algoritmos de busca - a. Complexidade O(n) (ex.: busca linear/sequencial em array/lista). b. Complexidade O(log₂ n) (ex.: busca binária). c. Complexidade O(log_b n) (ex.: busca em árvore não informada, em profundidade/largura)
12. Algoritmos de ordenação (ex.: estáveis, instáveis) - a. Complexidade O(n²) (ex.: inserção, seleção). b. Complexidade O(n log n) (ex.: quicksort, merge, timsort, heapsort). c. Pseudo O(n) (ex.: bucket, counting, radix)
13. Algoritmos em grafos - a. Caminho mínimo (ex.: Dijkstra, Floyd). b. Árvore geradora mínima (ex.: Prim, Kruskal). c. Fecho transitivo (ex.: Warshall). d. Ordenação topológica
14. Correspondência (matching) - a. Maior subsequência comum. b. Correspondência de expressões regulares

**Estratégias Algorítmicas**
1. Paradigmas - a. Força bruta (ex.: busca linear, ordenação por seleção, problema da mochila). b. Diminuir e conquistar - i. Por uma constante (ex.: ordenação por inserção, ordenação topológica). ii. Por um fator constante (ex.: busca binária). c. Dividir e conquistar (ex.: busca binária, quicksort, mergesort). d. Guloso (ex.: Dijkstra, Kruskal, problema da mochila). e. Transformar e conquistar - i. Redução de problema (ex.: mínimo múltiplo comum). ii. Programação dinâmica (ex.: Floyd). f. Compromisso entre espaço e tempo (ex.: hashing)
2. Iteração vs recursão (ex.: fatorial, busca em árvore)

**Complexidade**
1. Estrutura de análise de complexidade - a. Desempenho de melhor caso, caso médio e pior caso de um algoritmo. b. Medições empíricas e relativas (ordem de crescimento). c. Tamanho da entrada e operações primitivas. d. Eficiência de tempo e espaço
2. Análise de complexidade assintótica (limites de caso médio e pior caso) - a. Notações formais Big-O, Big-Omega e Big-Theta. b. Classes de complexidade fundamentais e exemplos/problemas representativos - i. O(1) Constante (ex.: acesso a array). ii. O(log₂ n) Logarítmica (ex.: busca binária). iii. O(n) Linear (ex.: busca linear). iv. O(n log₂ n) Log-linear (ex.: mergesort). v. O(n²) Quadrática (ex.: ordenação por seleção). vi. O(nᶜ) Polinomial. vii. O(2ⁿ) Exponencial (ex.: problema da mochila, Satisfatibilidade (SAT))
3. Tratabilidade e intratabilidade - a. Classes de complexidade P, NP e NP-completo. b. Problemas NP-completos (ex.: SAT, mochila, caixeiro-viajante)
4. Little-o
5. Análise recursiva formal
6. Análise amortizada
7. Modelos de complexidade baseados em Máquina de Turing - a. Complexidade de tempo - i. Classes P, NP, NP-completo e EXP. b. Complexidade de espaço - i. NSpace e PSpace. ii. Teorema de Savitch

**Modelos Computacionais e Linguagens Formais**
1. Autômatos formais - a. Finitos. b. De pilha. c. Linearmente limitados. d. Máquina de Turing
2. Linguagens formais, gramáticas e Hierarquia de Chomsky - a. Regulares (Tipo 3) - i. Expressões regulares. b. Livres de contexto (Tipo 2). c. Sensíveis ao contexto (Tipo 1). d. Recursivamente enumeráveis (Tipo 0)
3. Relações entre autômatos formais, linguagens e gramáticas
4. Decidibilidade, (in)computabilidade e problema da parada - a. Aritmetização e diagonalização
5. A tese de Church-Turing
6. Corretude de algoritmos - a. Invariantes (ex.: em iteração, recursão, busca em árvore)
7. Autômatos determinísticos e não determinísticos
8. Provas de limitações de linguagens - a. Autômatos finitos (linguagens regulares). b. Autômatos de pilha (linguagens livres de contexto)
9. Redutibilidade e reduções
10. Modelos equivalentes de computação algorítmica - a. Máquinas de Turing e variações (ex.: multifita, não determinística). b. Cálculo lambda


# Fundamentos de Desenvolvimento de Software
**Conceitos e Práticas Fundamentais de Programação**
1. Conceitos básicos como variáveis, tipos de dados primitivos, expressões e sua avaliação
2. Construções básicas como instruções de atribuição, instruções condicionais e iterativas, E/S básica
3. Modularidade: funções, métodos e classes, passagem de parâmetros, escopo, abstração, encapsulamento
4. Tipos de dados estruturados: arrays, listas, dicionários, conjuntos, tuplas e quando usá-los
5. Recursão
6. Tratamento de erros em tempo de execução em programas (ex.: tratamento de exceções).
7. Conceitos básicos de erros de programação, testes e depuração
8. Documentação/comentários de código no nível do programa e do módulo.

**Estruturas de Dados Fundamentais**
1. Tipos abstratos de dados padrão como listas, pilhas, filas, conjuntos e mapas/dicionários, incluindo suas operações
2. Seleção e uso de estruturas de dados apropriadas
3. Implicações de desempenho da escolha de estrutura(s) de dados
4. Strings e processamento de strings

**Algoritmos**
1. Conceito de algoritmo e noção de eficiência de algoritmos
2. Alguns algoritmos comuns (ex.: ordenação, busca, percurso de árvores, percurso de grafos)
3. Impacto dos algoritmos na eficiência de tempo e espaço dos programas

**Práticas de Desenvolvimento de Software**
1. Testes básicos, incluindo projeto de casos de teste
2. Uso de uma IDE de propósito geral, incluindo seu depurador
3. Estilo de programação que melhora a legibilidade
4. Especificação da funcionalidade de um módulo em linguagem natural
