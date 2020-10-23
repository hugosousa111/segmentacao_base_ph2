# SEGMENTAÇÃO DE IMAGENS DE LESÕES DE PELE

Códigos do meu Trabalho de Conclusão de Curso em Engenharia de Computação UFC-Sobral

## RESUMO do trabalho
As lesões de pele são estruturas pigmentadas presentes na pele, a mais problemática dessas lesões é o câncer de pele, que representa cerca de 30% dos tumores malignos que atingem brasileiros, além de apresentar alto risco de metástase. Esse trabalho apresenta uma proposta de utilização de técnicas de segmentação automática de lesões de pele,  incluindo o câncer de pele do tipo melanoma, a segmentação é uma das principais etapas para a construção de sistemas de diagnóstico de câncer de pele auxiliados por computador. É realizado um estudo comparativo entre segmentadores aplicados no banco de imagens PH². São propostos 4 tipos de experimentos, com e sem as etapas de pré e pós-processamento, esses experimentos são aplicados em 6 segmentadores. Por fim, os resultados de cada cenários são avaliados através do cálculo dos coeficientes de similaridade.  Os melhores resultados atingidos por esse trabalho são do segmentador de binarização com o método de Otsu, este também foi o melhor quando aplicado apenas para as amostras do tipo de câncer de pele melanoma. Foi identificada baixa eficácia do pré-processamento e alta eficácia do pós-processamento utilizado. Apesar dos resultados serem relativamente satisfatórios, ainda estão abaixo de resultados dos últimos trabalhos aplicados na mesma base de imagens.

Palavras-chave: Dermatoscopia. Lesões de Pele. Câncer de Pele. Binarização.

## Base de Imagens
A base de imagens utilizada para esse trabalho foi a PH².  A base contém 200 amostras de imagens coloridas com resolução de 768 x 560 pixels, divididas em 3 classes, sendo 80 amostras de nevos comuns, 80 amostras de nevos atípicos e 40 amostras do câncer de pele do tipo melanoma.
[Página do Projeto PH²](https://www.fc.up.pt/addi/ph2%20database.html)

## Arquivos
                    
Arquivo  | Conteúdo
------------- | -------------
pré_processamento.ipynb  | Pré-processamento das imagens
segmentação_e_pós_processamento.ipynb  | Segmentação, pós-processamento e remoção dos cantos
cálculo_dos_coeficientes.ipynb  | Cálculos do Jaccard e Dice
resultados_experimentos.ipynb  | Gráficos dos resultados das 3 classes
resultados_experimentos_melanoma.ipynb  | Gráficos dos resultados classe Melanoma
exemplos_amostras.ipynb  | Alguns aplicações em amostras da base

## Como executar

Os códigos estão adaptados para serem executados no ambiente Google Colaboratory com o serviço Google Drive,para acesso a base de imagens e salvar resultados. 

Copie os arquivos do link: [Pasta PH2Dataset](https://drive.google.com/drive/folders/1HAljwyIbhS-YirRsyHvo30EwEFcf1knU?usp=sharing) para uma pasta com o nome "PH2Dataset" na pasta raiz do seu Google Drive, esses são os arquivos da base de imagens. 

Copie os arquivos do link: [Pasta PH2_TCC](https://drive.google.com/drive/folders/1oQYjKo3JI8GjnyLOqPDWe8UE4g1QQH3x?usp=sharing) para uma pasta com o nome "PH2_TCC" na pasta raiz do seu Google Drive, esses são os arquivos dos resultados dos experimentos. 

Para rodar os notebooks em outro ambiente é necessária a realização de adaptações nos códigos, para mudar o caminho para a base de imagens e onde irá salvar os resultados. 