                                             # Simulador de Probabilidades de Combinacoes de Loteria
                     *Esse projeto está sendo criado baseado em probabilidades da engenharia da matemática e lógica.*

                                                            ##1 Simulador basico 

import random
lista1 = range (1, 60)
lista2 = range (1, 60)
lista3 = range (1, 60)
lista4 = range (1, 60)
lista5 = range (1, 60)
lista6 = range (1, 60)
escolha = random.shuffle(random.choice(lista1, lista2, lista3, lista4, lista5, lista6)
print('Simulação concluida!')
print('escolha')

* Em uma combinação de aposta aleatório com 6 números entre 1 a 60, as chances de acertos são de: 
     50.063.860 milhões, 2.154.518 milhões para a quina e 2.332 milhões para a quadra;

* Em uma única dezena que for acrescentada, 7 números 

7  números| 7.151.980 milhões de chances e de 44.981 na quina e 1.038 para quadra. 

8  números 1,787.998, quina 17.192, quadra 539

10  números 238,399 quina 3.973, quadra 198

12  números 54.182, quadra 90.



  Dezenas | Sena | Quina | Quadra
  ---|---|---|---|
  6 | 50.063.860 | 2.154.518 | 2.332 
  7 | 7.151.980 | 44.981 | 1.038 
  8 | 1.787.998 | 17.192 | 519
  10 | 238.399 | 3.973 | 195
  12 | 54.182 | 1.317 | 90 |
  
  Terminou tabela
  
--Precisa contar 100% com a sorte, porem estatísticamente a sorte pode ser manipulada aumentando essa probabilidade por meio da Engenharia da matemática, estudos de probabilidades e lógicas provaveis.--


1º Fator Matemático lógico: Lógica; A probabilidade diz que entre 5 e 7 sorteios seguenciais a um acumulo de sorteios, Se um apostador gasta 10 reais a cada aposta, em 7 apostas ele tem 70 reais, em 10 apostadores 700 reais, em 20 apostadores 1.400 reais, quanto mais apostadores mais dinheiro,aumentando a quantidade de números na aposta, No sistema cooperativo de apostas (Bolão) as chances de acerto passa para 33,3% a 50%. 

2º Fator Matemático: Plano,Analise de método estatistico de probabilidades:   

 * Para um apostador aumentar sua probabilidade ele nunca deve colocar 3 números sequenciais, nunca colocar finais iguais (exemplo 07- 17- 47) o estudo da probabilidade de isso acontecer é de 1%.

 * Estatisticamente os números laterais que são 28 números de 1 ao 10 de 10 ao 60 de 1 ao 51 e de 51 ao 30 são sorteados 2 e os centrais 32 e são sorteados 4, por lógica de proporções
 
  *01** | **02** | **03** | **04** | **05** | **06** | **07** | **08** | **09** | **10** 
  ---|---|---|---|---|---|---|---|---|---
  **11** | 12 | 13 | 14 | 15 | 16 | 17 | 18 | 19 | **20**
  **21** | 22 | 23 | 24 | 25 | 26 | 27 | 28 | 29 | **30**
  **31** | 32 | 33 | 34 | 35 | 36 | 37 | 38 | 39 | **40**
  **41** | 42 | 43 | 44 | 45 | 46 | 47 | 48 | 49 | **50**
  **51** | **52** | **53** | **54** | **55** | **56** | **57** | **58** | **59** | **60**
  
         
 * Uma aposta em todos os números pares ou em todos os impares probabilidade de de isso acontecer é de 1% segundo a matemática em estudo da probabilidade de 1453 apostas da mega-sena em teste x 6 = 8.718 números sorteados 4343 Números pares probabilidade de (49,8%) e 4.375 impares probabilidade de (50,2%) .

* No cartão de apostas dividindo as seguências em parte superior e inferior a probabilidade é a mesma. Parte superior 01 ao 30 probabilidade em 4.322 (49,5%) de probabilidade que os números sorteados na parte de superior. Parte inferior 4.396 probabilidade de 50,5 %.

* Dividindo em lado direito e esquerdo, mesmo percentual, lado direito 4,298 (49,3%) lado esquerdo 4.420 (50,7%) de probabilidade.

* Em todos esses critérios da probabilidade os percentuais são muito parecidos e obedecendo esse critério aumenta a probabilidade de acerto.

* Dividinso o cartão de apostas em 4 partes iguais quadrantes de 1 – 25 e 26 – 30 e 31- 35 e 36 – 60 quadrante sentido horário dos 8.718 números sorteados

   1º Quadrante | 24,8%
   ---|---|
   2º Quandrante | 24,8%
   3º Quadrante | 25,8%
   4º Quadrante | 24,6%

* Com um percentual muito semelhante uma aposta com 6 números tem probabiliadade de 1 número em cada quadrante sendo os outros 2 aleatório entre os quadrantes, em uma aposta de 8 números 2 em cada quadrante sendo 4 pares e 4 impares a probabilidade de acerto seria maior em teoria. Quanto mais números nessas estatisticas mais probabilidade de acerto.

* Estatística 2012
 Em analise de números mais sorteados,combinações com eles, seriam 18 acertos no sorteio principal e 23 quinas, Com os 30 menos sorteados nenhuma acerto e uma quina, Eliminando os 30 números menos sorteados e apostar entre os 30 mais sorteados maior probabilidade.

 * Aposta com 8 números, 2 cada quadrante, pares e impares. filtrando probabilidades maior probabilidade de acertos, quanto mais números maior probabilidade

 * Nesses fatores a porcentagem é de 33,3% a 40%. A soma do 1º e 2º fatores de probabilidade, 90% estatisticamente e 10% de sorte estatisticamente.

     
                                                      **Se tem Estatistica matemática da para programar!!!**

                                                                     # Sintase do Algoritimo:

- [] Criar um programa onde o usuario escolhe quantos números que ele quer solicitar para a aposta, que de a ele a possibilidade de selecionar quantos pares e quantos impares, que de possibilidade de  selecionar a quantidade de apostas nos laterais e nos centrais, que divida os 60 números em quatro e de a possibilidade de escolher entre eles e a quantidade de apostas nos lados direito e esquerdo e no superior e inferior que não escolha mais que 2 números sequênciais, que não repita números, que ele tenha a possibilidade de selecionar quantidade de números em cada quadrante, que ele possa seleconar os numeros mais sorteados e os menos sorteados para acrescentar ou eliminar de sua combinação e não repetir mais que 3 finais iguais nas dezenas

(Continua...)




