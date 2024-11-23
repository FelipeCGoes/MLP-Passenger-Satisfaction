# Airline Passenger Satisfaction Analysis
--Português--
Baseado em diversos campos de avaliação preenchidos por passageiros de uma mesma companhia aérea, propomos uma MLP capaz de predizer com 94% de acurácia a avaliação final do passageiro sobre sua viagem. A avaliação final é fundamental pois diz respeito sobre se o passageiro se diz satisfeito ou não com sua experiência com a empresa, influenciando diretamente na sua decisão sobre retornar a comprar com a mesma.

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

--English--
Based in multiple survey fields filled by passengers of the same airline company, we proposed an MLP capable of predicting with 94% accuracy the final score given by the passenger about his trip. Predicting the final score is vital as it's the ultimate data point to determine if the passenger was satisfied or not with the overall experience he had with the airline, directly influencing his decision to return flying with the same company.

The dataset is available on [Kaggle](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction?resource=download).

An extensive pre-processing and fine tuning was performed.

## Fine-tunig:

The first step of the fine tuning process was to evaluate the impact of the variation of the number of hidden layers of the MLP, opting for 2 hidden layers according to the results below.
![image](https://github.com/user-attachments/assets/92391598-112b-43bf-bc36-2af1e040eef3)

Then a series of test were performed, changing one hyper parameter at a time.
![image](https://github.com/user-attachments/assets/9aba0b9c-1fa7-4172-8a21-0a3d5353826d)

![image](https://github.com/user-attachments/assets/1d4181a1-4bfe-4bb3-9d65-2b196e6f6fdb)

The best architecture that balanced accuracy and computational cost was chosen.

Authors: Felipe Góes e Emanuel Vieira dos Santos
