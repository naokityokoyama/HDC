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

O dataset contém inicialmente 10000 linhas com notícias reais e falsas.
Cada linha possui um texto (notícia) e um rótulo:
0 = Notícia verdadeira
1 = Fake news
Objetivo

Comparar a simplicidade, desempenho e interpretabilidade entre métodos HDC e um Transformer (BERT) no contexto de fake news detection.
Auxiliar pesquisadores e entusiastas no entendimento prático dessas abordagens para NLP.
