# acppred

By Diana

a tool to predict anticancer peptides

## Setup

```
Um model preditivo para peptideos positivo ou negativo para cancer, analise de peptideos encontra-se no notebook jupyter. Este programa utiliza miniforge, com versões para todas as arquiteturas Linux, bem como para MacOS.
Cookiecutter requer Python 3.3 ou posterior (32 bits ou 64 bits) ou Anaconda 3 4.2 ou posterior
(32 bits ou 64 bits). Foi configurado Conda no Git Bash. Na base e o ambiente onde todos os
pacotes são contidos (test,...). Se você estiver interessado em ver quais pacotes estão
instalados basta digitar o comando conda list. 
O aprendizado de maquinas foi realizado a partir de redes neurais que analizaram exemplos de
treinamento, cada ponto de dados de entrada recebeu um peso, quando o numero se aproximar a 1,
e um peptido tumoral. A fim de usar Random Forest foi combinar os modelos, ao ser flexivel
permite prever os dados de teste. 
O método de ajuste é onde o aprendizado ocorre, o método de transformação e aplicado a dados
não vistos.  
ProtParam computou a composição de aminoácidos.  O modelo tem uma acuracia alta

A predictive model for peptides positive or negative for cancer, peptide analysis is found in
the jupyter notebook. This program uses miniforge, with versions for all Linux architectures,
as well as MacOS.
Cookiecutter requires Python 3.3 or later (32-bit or 64-bit) or Anaconda 3 4.2 or later (32
-bit
or 64-bit).
At the base and the environment where all the packages are contained (test,...). If you are 
interested in seeing what packages are installed just type the conda list command.
Machine learning was performed from neural networks that analyzed training examples, each
input data point received a weight, when the number approaches 1, and a tumor peptide.
The purpose of using Random Forest was to combine the models, being flexible it allows to
predict the test data.
The fit method is where learning takes place, the transformation method is applied to data.
not seen.
ProtParam computed the amino acid composition. The model has a high accuracy.



```
