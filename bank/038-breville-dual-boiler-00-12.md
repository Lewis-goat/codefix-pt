---
title: Breville Dual Boiler 00–12: os códigos de dois dígitos
description: A Breville Dual Boiler BES920 guarda códigos 00 a 12 num menu de autoteste oculto: famílias de códigos, lado do vapor vs. lado do café e as soluções.
---

As máquinas de café expresso da Breville anunciam as avarias sobretudo no ecrã normal do dia a dia: a Barista Touch mostra códigos ER, a Oracle anuncia códigos de erro, a Oracle Jet usa números E. A **Dual Boiler BES920** segue outro caminho. A sua tabela de avarias é um conjunto simples de códigos de dois dígitos, **00 a 12**, e vive num menu de autoteste oculto em vez do painel habitual. Não os vai apanhar a observar a frente da máquina durante uma utilização normal — é preciso saber a combinação de botões.

A numeração vale a pena entender, porque é uma tabela arrumada: o bloco onde o código se senta diz o tipo de avaria e, dentro de cada bloco, o código identifica a peça que se está a queixar.

## Ler o registo de erros

O registo acede-se a partir do menu de autoteste:

1. Desligue a máquina no interruptor de parede.
2. Mantenha premidos **EXIT** e **MANUAL** enquanto liga a corrente; o menu de autoteste aparece.
3. Prima **MENU** até chegar ao item 3, o registo de erros. O item 4 mostra o estado do nível das caldeiras, reportado como LLL (baixo) ou HHH (alto).
4. No registo de erros, **MENU** avança pelos códigos 00 a 12, cada um com um contador guardado.
5. Em "ErSt", mantenha **MANUAL** premido até ouvir o sinal sonoro para limpar os códigos armazenados; o contador de chávenas não é reposicionado.

O contador importa tanto como o código. Uma avaria com um único registo há um ano é história antiga; um contador que sobe todas as semanas é um problema ativo a instalar-se.

## O que a família 00 cobre

Os códigos **00 a 05** formam o bloco dos sensores de temperatura, organizado em três pares. Em cada par, o número mais baixo significa que a sonda **não é detetada** — a placa lê-a como circuito aberto — e o número mais alto significa que está a ler em **curtocircuito**:

- **00 e 01** — sonda de temperatura da caldeira de vapor, primeiro não detetada, depois em curto.
- **02 e 03** — sonda de temperatura da caldeira de café, primeiro não detetada, depois em curto.
- **04 e 05** — sonda de temperatura do aquecimento do grupo, primeiro não detetada, depois em curto.

A BES920 tem caldeiras duplas em inox mais um grupo aquecido, por isso estas três sondas cobrem as três zonas quentes da máquina. A [página do código 00](https://pt.codefixcoffee.com/breville/dual-boiler-bes920/00/) trata da sonda da caldeira de vapor, e o conselho prático transfere-se para as outras cinco: reencaixe e inspecione o conector da sonda antes de comprar peças, e procure humidade, porque água a fazer ponte num conector lê-se como circuito aberto ou como curto conforme a posição. As sondas NTC originais custam €25 a €90 conforme a zona em causa; os kits de juntas tóricas ficam €10 a €20 e são muitas vezes o verdadeiro culpado. Para desmontagens guiadas, o [iFixit](https://www.ifixit.com) é uma referência com guias de máquinas semelhantes.

## Lado do vapor contra lado do café

O resto da tabela divide-se pela mesma fronteira de hardware dos pares de sondas:

- **Caldeira de vapor:** 06 (problema de bomba durante o arranque), 07 (falha de nível de água ou de bomba) e 11 (sobreaquecimento detetado).
- **Caldeira de café, o lado da extração:** 08 (problema de bomba ou de caudal), 09 (falha de nível de água) e 10 (sobreaquecimento detetado).
- **Grupo:** 12 (sobreaquecimento detetado).

### Os códigos que viajam em conjunto

Estas falhas estão interligadas, e é por isso que ler o registo completo vale mais do que ler um código isolado. O 08 significa que a bomba trabalhou e o caudalímetro não viu passar nada — na maioria das vezes, calcário na palheta do caudalímetro ou uma bomba a zumbir sem mover água, e a descalcificação é o primeiro passo em ambos os casos. O 11, sobretemperatura na caldeira de vapor, costuma seguir-se a uma caldeira que não está a ser reabastecida — veja se o 07 ou o 08 também acumulam contador — porque a resistência continua a aquecer uma caldeira baixa; uma junta da sonda a fugir é a outra causa. Antes de encomendar seja o que for, consulte o item 4 do menu de autoteste: um estado de nível em desacordo com o que ouve quando a máquina enche diz-lhe de que lado está realmente a falha.

O 12, sobreaquecimento do grupo, é a ponta mais rara da tabela e aquela onde a reincidência mais importa — um sobreaquecimento que volta uma e outra vez aponta para a placa de alimentação a manter uma resistência ligada, e não para uma deriva da sonda. A [página do código 12](https://pt.codefixcoffee.com/breville/dual-boiler-bes920/12/) desenvolve o tema.

### Em Portugal: a água dura e a família 08

Boa parte de Portugal tem água da torneira dura — a região de Lisboa, o Alentejo e o Algarve destacam-se pelo calcário — e é exatamente esse calcário que se deposita na palheta do caudalímetro e faz disparar o código 08. Se o contador do 08 sobe semana após semana, descalcifique antes de comprar uma bomba nova. Um descalcificador adequado custa cerca de €10 e resolve uma fatia real destas avarias sem abrir a máquina.

## O que as peças custam

- Descalcificador, para os códigos de caudal e de nível: cerca de €10, e resolve uma parte real deles.
- Bomba de enchimento: €30 a €60.
- Sonda da caldeira de vapor com kit de juntas: cerca de €85; só os kits de juntas tóricas, €10 a €20.
- Fusível térmico: €10 a €20 — mas descubra porque é que fundiu.
- Triac ou placa de alimentação: €80 a €150.

Os orçamentos de assistência Breville fora da garantia, para avarias internas, andam normalmente entre €300 e €500 para cima, por isso uma bomba ou uma sonda compensa fazer você mesmo; numa placa de máquina antiga, peça primeiro orçamento. Água e corrente elétrica partilham o topo da caldeira: desligue a ficha antes de tocar nas sondas.

Para ver como as outras máquinas da gama anunciam os códigos, veja a [secção Breville](https://pt.codefixcoffee.com/breville/) — a família ER partilha ideias de diagnóstico, mas não a numeração. No Reino Unido e na Irlanda a marca é vendida como Sage, e o [site oficial da Sage Appliances](https://www.sageappliances.co.uk) é a fonte dos manuais e da assistência; os leitores britânicos podem usar a [edição britânica](https://pt.codefixcoffee.com/uk/) do site.
