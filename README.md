# SEGMENTAÇÃO DE IMAGENS DE LESÕES DE PELE

Códigos do Trabalho de Conclusão de Curso em Engenharia de Computação UFC-Sobral

## RESUMO do trabalho
As lesões de pele são estruturas pigmentadas presentes na pele, a mais problemática dessas lesões é o câncer de pele, que representa cerca de 30% dos tumores malignos que atingem brasileiros, além de apresentar alto risco de metástase. Esse trabalho apresenta uma proposta de utilização de técnicas de segmentação automática de lesões de pele,  incluindo o câncer de pele do tipo melanoma, a segmentação é uma das principais etapas para a construção de sistemas de diagnóstico de câncer de pele auxiliados por computador. É realizado um estudo comparativo entre segmentadores aplicados no banco de imagensPH2. São propostos 4 tipos de experimentos, com e sem as etapas de pré e pós-processamento, esses experimentos são aplicados em 6 segmentadores. Por fim, os resultados de cada cenários são avaliados através do cálculo dos coeficientes de similaridade.  Os melhores resultados atingidos por esse trabalho são do segmentador de binarização com o método de Otsu, este também foi o melhor quando aplicado apenas para as amostras do tipo de câncer de pele melanoma. Foi identificada baixa eficácia do pré-processamento e alta eficácia do pós-processamento utilizado. Apesar dos resultados serem relativamente satisfatórios, ainda estão abaixo de resultados dos últimos trabalhos aplicados na mesma base de imagens.

Palavras-chave: Dermatoscopia. Lesões de Pele. Câncer de Pele. Binarização.

## Base de Imagens
Link do site

## Arquivos
                    
Arquivo  | Conteúdo
------------- | -------------
pré_processamento.ipynb  | pré-processamento das imagens
segmentação_e_pós_processamento.ipynb  | aplicação da segmentação, pós-processamento e remoção dos cantos
cálculo_dos_coeficientes.ipynb  | Cálculos do Jaccard e Dice
resultados_experimentos.ipynb  | Gráficos dos resultados das 3 classes
resultados_experimentos_melanoma.ipynb  | Gráficos dos resultados classe Melanoma
exemplos_amostras.ipynb  | Alguns aplicações em amostras da base

## Como executar

Colocar que precisa colocar no git a base e a pasta com as imagens

Arquivos: 
https://drive.google.com/drive/folders/1oQYjKo3JI8GjnyLOqPDWe8UE4g1QQH3x?usp=sharing

Base de Imagens: 
https://drive.google.com/drive/folders/1HAljwyIbhS-YirRsyHvo30EwEFcf1knU?usp=sharing


## Metodologia dos Experimentos

### Segmentadores

### Pré-Processamento

### Pós-processamento

## Resultados 
