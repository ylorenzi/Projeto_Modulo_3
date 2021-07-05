# ⚠️ Lockdown funciona! ⚠️
## O caso de Araraquara

![](https://static.6minutos.uol.com.br/2021/03/shutterstock_1845160789-1200x675.jpg)

Projeto do terceiro módulo do bootcamp de data science aplicada da Alura

## 1- Introdução

Neste repositório se encontra o projeto do terceiro módulo do bootcamp de data science aplicada da Alura.
O projeto consiste em um estudo sobre como o município de Araraquara (SP) usou um lockdown para combater a COVID-19.
Utilizando o Prophet, uma ferramenta Open Source para forecasting (previões) desenvolvida pelo Facebook, foi feita uma previsão de como se espalharia a doença caso o lockdown não tivesse acontecido. Em seguida foi comparada a previsão com o que de fato ocorreu. 

## 2- Dados

Os dados utilizados foram cedidos pelo Urbie (Grupo de Inovação e Extensão em Engenharia Urbana), que é vinculado ao PPGEU (Programa de Pós-Graduação em Engenharia Urbana) da UFSCar. A base de dados possui informações diárias sobre algumas informações como: número total de casos de COVID, novas notificações de casos, número total de óbitos e novas notificações de óbitos. 


## 3- Metodologia

Foi utilizado o Prophet para criar uma previsão da quantidade de casos de COVID-19 que teriam acontecido em Araraquara caso não tivesse sido feito o lockdown. Os dados fornecidos ao modelo foram dados de números de novas notificações até a data de 22 de fevereiro de 2021 (um dia antes do início do lockdown). A partir desses dados o Prophet produziu previsões sobre os números de casos para os dias subsequentes. Com a previsão em mãos, foram comparados o total de casos previstos com o total de casos reportados.

## 4- Conclusões

