O Que é HDC (Hyperdimensional Computing)?

Hyperdimensional Computing (HDC), ou Computação Hiperdimensional, é um paradigma inovador inspirado em como o cérebro humano processa informações. Diferente da computação tradicional, que depende de operações aritméticas sobre números de precisão finita, o HDC utiliza vetores de alta dimensão, também chamados de hipervetores, para representar e manipular dados e conhecimento.

Como Funciona a Computação Hiperdimensional

No HDC, informações são codificadas em vetores com milhares de dimensões — frequentemente de 10.000 até 100.000 dimensões — com elementos binários, inteiros ou reais. Esses hipervetores podem ser combinados através de operações matemáticas simples, como soma, multiplicação elemento-a-elemento (binding) e permutação, permitindo representar conceitos complexos de maneira compacta e robusta.

O funcionamento básico do HDC passa por três etapas principais:

Codificação:
Itens (como palavras, sensores ou categorias) são convertidos em hipervetores "aleatórios", mas reprodutíveis.
Composição:
A relação entre itens (ex: palavras numa sentença) é modelada por operações entre hipervetores, gerando um novo hipervetor que representa essa relação.
Classificação ou Decodificação:
O hipervetor composto pode ser comparado a hipervetores de referência usando medidas de similaridade (como cosseno ou Hamming) para inferir informações ou reconhecer padrões.
Diferenças em Relação à Computação Convencional e Redes Neurais

Robustez:
O HDC é extremamente tolerante a ruídos, falhas e variações nos dados — característica alcançada pelo alto número de dimensões e pela redundância da informação.
Simplicidade nas Operações:
As operações entre hipervetores são matematicamente simples e de fácil paralelização, tornando o HDC eficiente para hardware especializado e aplicações embarcadas.
Treinamento Rápido:
Algoritmos de HDC frequentemente requerem uma única passagem sobre o dado (one-shot learning), ao contrário de redes neurais profundas que demandam treinamento longo e muitos dados.
Interpretabilidade:
O HDC pode oferecer maior transparência do que modelos “caixa preta”, pois cada operação tem significado matemático claro e a representação é distribuída.
Aplicações

O HDC já foi aplicado com sucesso em diversas áreas, como:

Reconhecimento de padrões e classificação (NLP, sinais biométricos)
Processamento de linguagem natural (codificação de texto, análise de sentimentos)
Sistemas embarcados para IoT e sensores, onde recursos computacionais são limitados
Conclusão

A Computação Hiperdimensional propõe uma forma alternativa de manipular dados inspirada em mecanismos cerebrais. Sua alta eficiência, escalabilidade e robustez a tornam uma solução promissora para tarefas onde os modelos tradicionais, como redes neurais profundas, podem ser excessivos ou difíceis de aplicar. Entre suas maiores vantagens estão a facilidade de implementação, baixo custo computacional e maior interpretabilidade — características-chave para aplicações de inteligência artificial no mundo real.

### PROJETO  

Fake News Detection: Hyperdimensional Computing (HDC) vs BERT
📒 📰 🤖

Este repositório apresenta uma comparação entre algoritmos de Hyperdimensional Computing (HDC) e o modelo BERT aplicado ao problema de detecção de fake news em um dataset rotulado (0 = não fake, 1 = fake news). O objetivo é avaliar o desempenho, interpretabilidade e complexidade de cada abordagem em cenários práticos.

Notebooks do Projeto

• Notebook 1: HDC com ngram encoder (BinHD & NeuralHD)  

Implementa o encoder de n-gramas para representar textos em espaços hiperdimensionais.
Avalia dois algoritmos: BinHD (baseado em operações binárias) e NeuralHD (variante neuroinspirada).
Permite observar as diferenças de desempenho e complexidade dos algoritmos HDC.    

• Notebook 2: HDC com ngram encoder + record encoder (BinHD)  

Adiciona o uso do record encoder para enriquecer as representações hiperdimensionais.
Utiliza o algoritmo BinHD para classificação do texto como fake ou não fake.
Compara os ganhos de performance com a arquitetura apenas com ngram encoder.    

• Notebook 3: BERT para Fake News  

Usa o modelo BERT pré-treinado para classificação binária de notícias falsas.
Efetua fine-tuning no mesmo dataset dos experimentos HDC.
Serve como baseline do estado da arte para comparação com HDC.
Sobre o Dataset  

• Notebook 4: TFIDF e regressão logistica para Fake News  

Usa o modelo regressão logistica para classificação e encoder TFIDF binária de notícias falsas.
Efetua fine-tuning no mesmo dataset dos experimentos HDC.
Serve como baseline do estado da arte para comparação com HDC.  
Sobre o Dataset

O dataset contém inicialmente 10000 linhas com notícias reais e falsas.
Cada linha possui um texto (notícia) e um rótulo:
0 = Notícia verdadeira
1 = Fake news
Objetivo

Comparar a simplicidade, desempenho e interpretabilidade entre métodos HDC e um Transformer (BERT) no contexto de fake news detection.
Auxiliar pesquisadores e entusiastas no entendimento prático dessas abordagens para NLP.
