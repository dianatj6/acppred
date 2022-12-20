# acppred

By Diana

a tool to predict anticancer peptides

## Setup

```
Um model preditivo para peptideos positivo ou negativo para cancer, analise de peptideos encontra-se
no notebook jupyter. Dados de treinamento foram usados para ensinar um modelo de aprendizado de máquina
para ensinar um modelo de previsão. Train foi o método para medir a precisão do modelo.
Todos os modelos foram testados. O aprendizado de maquinas foi realizado a partir de redes neurais
que analizaram exemplos de treinamento, cada ponto de dados de entrada recebeu um peso,
quando o numero se aproximar a 1, e um peptido tumoral.
A fim de usar Random Forest foi combinar os modelos, ao ser flexivel permite prever os dados de teste. 
O método de ajuste é onde o aprendizado ocorreu, o método de transformação foi aplicado a dados
não vistos.  
ProtParam computou a composição de aminoácidos.  O modelo tem uma acuracia alta
Explicando o codigo
predictor, para supervisar o aprendizado
estimator.fit, aprender com os dados
transformer, para filtrar e modificar os dados
modelo, medida de ajuste dos dados 
__init__, argumento de palavras-chave
fit , recebe os dados de treinamento como argumentos
onrender.com permitiu a visualização das alterações, 
Flask, um forma de modulizar as rotas do aplicativo
Este programa utiliza miniforge, com versões para todas as arquiteturas Linux,
bem como para MacOS. Cookiecutter requer Python 3.3 ou posterior (32 bits ou 64 bits) ou Anaconda 3 4.2 
ou posterior (32 bits ou 64 bits). Foi configurado Conda no Git Bash. Na base e o ambiente onde todos os
pacotes são contidos (test,...). Se você estiver interessado em ver quais pacotes estão
instalados basta digitar o comando conda list. 





```
