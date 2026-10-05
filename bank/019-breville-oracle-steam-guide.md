---
title: Breville/Sage Oracle — vapor e códigos, o que verificar primeiro
description: Falhas de vapor na Oracle da Breville/Sage — significado dos códigos do vapor, a purga a tentar primeiro e quando a culpa é do calcário.
---

O lado do vapor é a zona mais exigente de uma Breville Oracle: caldeira de vapor em inox, varinha de emulsão automática, sondas de nível e bomba de enchimento, tudo em temperatura dia após dia. É também aqui que nasce uma grande fatia dos códigos de erro da máquina. A família Oracle usa uma tabela de serviço de 32 entradas que a Breville nunca publicou, e no Reino Unido o mesmo hardware ostenta o logótipo **Sage** — os códigos são idênticos. Antes de assumir uma peça avariada, esgote as verificações baratas: a maioria das paragens do lado do vapor é um bico entupido, uma purga que ficou por fazer ou calcário numa sonda.

## Onde ficam os códigos de vapor na tabela Oracle

A Oracle (BES980) e a Oracle Touch (BES990) partilham a mesma tabela; a BES980 apresenta as entradas como "Error 1" a "Error 32" e a BES990 acrescenta o prefixo ER. As entradas do lado do vapor agrupam-se em cinco pontos:

- **Error 1 a 4** — a sonda de temperatura da caldeira de vapor, percorrendo circuito aberto no arranque, sinal perdido em funcionamento e curto-circuito nas duas situações. Uma sonda, quatro formas de o anunciar.
- **Error 13 a 16** — o mesmo quarteto para a sonda de temperatura da própria varinha de vapor, a que interrompe a emulsão automática assim que o leite atinge a temperatura certa. Vive no ponto mais húmido da máquina.
- **Error 18** — a caldeira de vapor não aquece como devia.
- **Error 20 e 21** — nível de água da caldeira de vapor ou problemas na bomba de enchimento, e uma leitura de sonda de nível que não corresponde ao que a placa esperava.
- **Error 26** — a caldeira de vapor sobreaqueceu acima do alvo; **Error 32** é uma fuga ou falha de reenchimento da caldeira de vapor.

Nem tudo o que roda a varinha é vapor: os códigos 5 a 8 pertencem à sonda da caldeira de café, sendo [Error 8](https://pt.codefixcoffee.com/breville/oracle-bes980/error-8/) a entrada de curto-circuito em funcionamento. Ler o registo armazenado ajuda a separar as famílias — na BES980, prima 1 CUP, 2 CUP e POWER em conjunto com a máquina desligada para abrir a Error Storage e percorrer os 32 códigos com as respetivas contagens.

## A primeira verificação — a rotina de purga

Vapor fraco ou intermitente, ou um código logo a seguir a uma bebida com leite, aponta quase sempre para o bico da varinha e não para a caldeira:

1. Desligue a máquina da corrente e deixe a varinha arrefecer.
1. Desenrosque o bico de vapor e mergulhe-o em água quente com um pouco de descalcificador; desobstrua todos os orifícios com o alfinete da ferramenta de limpeza.
1. Execute a purga — cerca de dez segundos de vapor para o tabuleiro de gotas com o bico retirado, e depois repita com ele montado.
1. Passe a purgar a varinha depois de cada sessão de leite; o leite seco no bico é o que dá início à maioria destas paragens.

Se a máquina monitoriza a pressão de vapor, como faz a Oracle Jet com o código E16, um bico incrustado pode fazer disparar um código antes de dar por um vapor mais franco.

## Dureza da água, calcário e as sondas de nível

Onde a água é dura, o calcário escreve códigos por conta própria. As sondas de nível da caldeira de vapor vivem em água quente permanente, e um revestimento calcário isola-as: a placa lê "sem água" com a caldeira cheia — o caminho clássico para o Error 20 ou 21, e para a falha de reenchimento do Error 32. O calcário acumula-se igualmente no trajeto da varinha e na admissão da bomba de enchimento. Uma descalcificação completa, incluindo o ciclo da caldeira de vapor, é o diagnóstico mais barato que pode fazer e elimina, por si só, uma quantidade surpreendente destes códigos.

A irmã de gama ilustra o mesmo ponto: a Dual Boiler esconde os códigos 00 a 12 num menu de autoteste, e o [código 00](https://pt.codefixcoffee.com/breville/dual-boiler-bes920/00/) — sonda da caldeira de vapor não detetada — encabeça uma tabela cujas entradas de nível e enchimento reagem exatamente da mesma forma à água dura.

### Água dura em Portugal

Grande parte de Portugal recebe água da rede dura ou muito dura — de Lisboa ao Algarve é regra, não exceção — e é precisamente esse o cenário em que as sondas de nível se incrustam mais depressa. Ajuste a definição de dureza da água na Oracle ao valor real da sua zona, com a leitura da tira de teste incluída, e pondere água filtrada no depósito. Os descalcificantes e filtros oficiais, bem como os programas de manutenção de cada modelo, estão documentados na área de apoio do [site da Sage](https://www.sageappliances.co.uk).

## Descalcificar ou desmontar

Descalcifique primeiro, desmonte só depois — mas saiba onde a descalcificação deixa de ajudar:

- **Descalcifique primeiro** nos códigos de nível, sonda e reenchimento (20, 21, 32), no vapor fraco sem código e em qualquer máquina com mais de três meses sobre o último ciclo. Custo: um frasco de descalcificador.
- **A descalcificação não resolve** um código de sonda que regressa de imediato numa máquina recém-descalcificada e já quente — seja uma entrada da caldeira de vapor, dos códigos 1 a 4, ou o [Error 8](https://pt.codefixcoffee.com/breville/oracle-bes980/error-8/) do lado do café. Um código que sobrevive à descalcificação aponta para a sonda, o cabo ou um conector.
- **Pare e veja os vedantes** se o Error 26 se repetir: um anel vedante da sonda de vapor em fuga deixa o vapor aquecer o cabo da sonda e imita uma caldeira descontrolada. Vedantes novos são baratos; uma placa com triac que não corta o aquecedor não é.
- **Error 18** numa máquina que já não produz vapor nenhum costuma ser do lado do aquecedor — fusível térmico, resistência de aquecimento ou placa — e não calcário; trate-o como reparação, não como limpeza.

## Quanto custam as peças

Os conjuntos originais de sonda de temperatura ficam entre €25 e €95 conforme o sensor; os conjuntos de varinha de vapor, que incluem a sonda, rondam os €60 a €95; um kit de sonda com vedantes fica nos €85 e uma bomba de enchimento nos €30 a €60. Em contrapartida, os orçamentos do fabricante fora de garantia para avarias internas vão com frequência de €300 a €500 — a aritmética quase sempre favorece o frasco de descalcificador primeiro e a troca da sonda depois. Guias de desmontagem destas máquinas estão reunidos no [iFixit](https://www.ifixit.com), e a cobertura das mesmas tabelas com o logótipo Sage está na [edição britânica do site](https://pt.codefixcoffee.com/uk/).
