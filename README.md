# 🚗 GAN_Cifar10  
**Gerando imagens de carros a partir do conjunto de dados CIFAR-10**  

Este projeto implementa uma **Rede Generativa Adversária (GAN)** para a geração de imagens de carros com base no dataset **CIFAR-10**.  

## 📉 Evolução da Perda  
Durante o treinamento, a função de perda se manteve relativamente estável, mas eventualmente começou a divergir. Esse comportamento pode ter sido causado pela **baixa complexidade do gerador**, permitindo que o discriminador reduzisse seu erro de forma significativa.  

![Erro do treinamento](loss.png)  

## 🏎️ Imagens Geradas  
As imagens abaixo foram geradas pela rede em sua última etapa de treinamento. É possível identificar características de carros, embora ainda seja perceptível o efeito de **distorção** comum em geradores pouco treinados ou com arquitetura limitada.  

![Último resultado](imgs/fig4356.png)  
