---
title: Máquinas de lavar loiça GE — os códigos C de drenagem, enchimento e aquecimento
description: Códigos C nas máquinas GE de lavar loiça — drenagem, enchimento e aquecimento nos códigos C1 a C8, e 888/CFE para a placa.
---

As máquinas de lavar loiça GE reportam avarias em códigos C no visor: C1 a C8, mais H2O para problemas de enchimento e 888 ou CFE quando o mal-estar está nas placas. Ao contrário da maioria dos fabricantes, a GE não publica qualquer lista oficial dos significados, e o dono fica a tentar casar dois caracteres com um sintoma pela sua conta. A [secção de máquinas de lavar loiça GE](https://pt.codefixcoffee.com/ge/dishwasher/) cobre todos os códigos; este artigo percorre as famílias pela ordem em que as vai encontrar e termina com o truque do menu de serviço que revela o último erro guardado.

## A família da drenagem — C1 a C3

Três códigos, um só sistema. C1 significa que a bomba de drenagem trabalhou mais de dois minutos sem esvaziar o tanque (em alguns modelos mais antigos assinala antes uma tecla presa); C2, que a bomba nem sequer arrancou ou que a tubagem estava totalmente bloqueada; C3 é a entrada genérica de "não drena como devia". Os suspeitos são sempre os mesmos — filtro e cuba entupidos, mangueira de drenagem dobrada, um triturador de resíduos instalado recentemente com a tampa de obstrução ainda no lugar, ou uma bomba de drenagem avariada. Comece pelo trabalho gratuito indicado na [página do C1](https://pt.codefixcoffee.com/ge/dishwasher/c1/): retire o cesto inferior, limpe o filtro e a cuba e verifique a mangueira por baixo da pia. Uma bomba de drenagem custa €40 a €80, se afinal estiver a zumbir ou calada.

## Falhas de enchimento — C4, C5 e H2O

- **C4** — excesso de água, ou a máquina encheu duas vezes na sequência de um corte de corrente. A válvula de admissão não fecha por completo, ou o interruptor de flutuação que devia travar o enchimento está preso por detritos. A verificação do flutuador está na [página do C4](https://pt.codefixcoffee.com/ge/dishwasher/c4/); se o tanque encher com a máquina desligada, a válvula de admissão está a passar e tem de ser substituída (€25 a €50).
- **C5** — enchimento insuficiente: não chegou água suficiente no tempo previsto. Torneira de alimentação meio fechada, crivo de admissão entupido ou válvula fraca.
- **H2O** — sem água nenhum. Confirme primeiro que a torneira por baixo da pia está aberta e que a mangueira não está dobrada, antes de mexer em mais alguma coisa.

## Falhas de aquecimento — C6 a C8

C6 indica que a água nunca atingiu os cerca de 120 °F (perto de 49 °C) nem com o período de aquecimento prolongado. Deixe correr a água quente da torneira da cozinha antes de iniciar o ciclo: se a água que entra está fria, a resistência de aquecimento pode simplesmente não dar conta do recupero. Se a loiça sai fria e molhada, meça a continuidade da resistência; as resistências custam €30 a €60 e o termóstato de limite €10 a €20. C7 é a falha do circuito da sonda de temperatura da água (termístor) — um conector solto ou uma sonda barata, embora nalguns modelos o mesmo código cubra antes o sensor de turbidez. C8 é habitualmente mecânico e não térmico: o copo do detergente não abriu porque uma peça de loiça o bloqueava ou porque detergente seco encrava o trinco.

## 888 e CFE — os códigos das placas

Quando a avaria é eletrónica e não hidráulica, a GE diz-o sem rodeios. O [888](https://pt.codefixcoffee.com/ge/dishwasher/888/) significa que a placa de controlo principal falhou no próprio autoteste — muitas vezes depois de um pico de tensão numa trovoada corromper um registo de memória, e ocasionalmente porque uma fuga molhou a placa. O [CFE](https://pt.codefixcoffee.com/ge/dishwasher/cfe/) indica que a interface de utilizador montada na porta deixou de comunicar com a placa principal: costuma ser um cabo desgastado na zona das dobradiças ou um conector húmido. Ambos começam com um reset no disjuntor; ambos acabam numa placa se o código voltar — €90 a €200 pela placa principal, €60 a €120 pela interface.

## O truque do menu de serviço — ler o último erro

Uma máquina que anda a parar há semanas muitas vezes não mostra nada quando está à sua frente. A placa lembra-se, e na maioria das máquinas GE pode perguntar-lhe:

1. Abra completamente a porta.
1. Mantenha o botão Start premido durante cinco segundos para entrar no menu de serviço.
1. Nos modelos em que o visor fica escondido atrás da guarnição da porta, prima Select Cycle e Start em conjunto durante cinco segundos.
1. Leia no visor o último erro guardado e feche a porta.
1. Para reiniciar a própria placa, corte a corrente no disjuntor durante 60 segundos.

Anote o código, limpe-o e corra um ciclo: um C3 guardado há três semanas mais um C3 fresco hoje é uma avaria real de drenagem, não uma falha passageira.

## Quanto custam as reparações

Quase todos os códigos C se resolvem com uma bomba, uma válvula, uma sonda ou um distribuidor — peças entre €10 e €80 — mais o seu trabalho, se estiver à vontade para cortar a corrente e retirar um painel. As placas são a exceção, a €90 a €200. Uma deslocação de um técnico de electrodomésticos custa €120 a €250 com diagnóstico e peça, dinheiro bem gasto nos códigos de placa e raramente necessário para um filtro entupido. Manuais e assistência por modelo estão na área de apoio da [GE Appliances](https://www.geappliances.com).

### Uma GE em Portugal — o que ponderar antes

As máquinas de lavar loiça GE não têm distribuição oficial em Portugal, por isso quase todas chegaram por importação — e a maioria vem dos Estados Unidos, onde a rede é de 120 V e 60 Hz. Antes de qualquer diagnóstico, confirme que o aparelho é compatível com os 230 V e 50 Hz portugueses ou que o transformador instalado dá conta do consumo, porque uma alimentação errada produz sintomas que imitam avarias de placa. Sem rede oficial, os reparadores independentes são o caminho natural, e guias de desmontagem destas máquinas existem no [iFixit](https://www.ifixit.com).
