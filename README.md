# Airline Passenger Satisfaction Analysis
Baseado em diversos campos de avaliação preenchidos por passageiros de uma mesma companhia aérea, propomos uma MLP capaz de predizer com 94% de acurácia a avaliação final do passageiro sobre sua viagem. A avaliação final é fundamental pois diz respeito sobre se o passageiro se diz satisfeito ou não com sua experiência com a empresa, infliu&enciando diretamente na sua decisão sobre retornar a comprar com a mesma.

O dataset está disponível no [Kaggle](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction?resource=download). 

Foi realizado um extensivo pré-processamento e fine tuning.

## Fine-tunig:

A primeira ertapa do fine-tuning consistiu em avaliar o impacto na variação do número de camadas da MLP, optando por 2 camadas hidden.
![image](https://github.com/user-attachments/assets/92391598-112b-43bf-bc36-2af1e040eef3)

Então uma série de testes foram feitos alterando um parâmetro por vez:
![image](https://github.com/user-attachments/assets/9aba0b9c-1fa7-4172-8a21-0a3d5353826d)

![image](https://github.com/user-attachments/assets/1d4181a1-4bfe-4bb3-9d65-2b196e6f6fdb)

A melhor arquitetura foi escolhida balanceando acuárica e custo computacional.

Autores: Felipe Góes e Emanuel Vieira dos Santos

