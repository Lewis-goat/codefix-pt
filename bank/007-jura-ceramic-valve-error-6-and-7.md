---
title: "Jura Erro 6 e 7: a válvula de cerâmica, sem rodeios"
description: "O que significam os Erros 6 e 7 numa Jura: a válvula de cerâmica motorizada, o calcário, o encoder de posição e porque o Erro 7 exige bancada."
---

Os códigos numerados da Jura são louvavelmente específicos: os Erros 1 a 5 apontam para os termoblocos e as sondas, o 8 para o grupo de preparação, o 12 para o moedor. Os Erros 6 e 7 apontam ambos para o mesmo componente: a válvula eletrónica de cerâmica, o disco motorizado que distribui a água dentro da máquina. A diferença entre eles resume-se, mais ou menos, a "faça uma descalcificação e observe" contra "marque uma reparação". Eis o que se passa na verdade.

## O que faz a válvula de cerâmica

A maioria das automáticas de café em grão alterna entre café, água quente e vapor com válvulas solenoides simples. As Jura de gama mais alta — da Z5 à Z10, a série X, da J5 à J9, a gama GIGA e as S e E mais recentes — usam antes uma válvula eletrónica de cerâmica: um pequeno motor roda um disco de cerâmica entre posições, e os canais desse disco encaminham a água para a saída de café, o bico de água quente ou o circuito de vapor. Um sensor de posição (o encoder) reporta a localização do disco a todo o momento, garantindo à placa de controlo que a água vai parar ao sítio pretendido.

É este circuito de feedback que justifica a existência dos Erros 6 e 7: a placa ordena uma posição, aguarda a confirmação do encoder e acusa erro quando ela nunca chega.

## Erro 6: o disco não chegou

O [Erro 6](https://pt.codefixcoffee.com/jura/automatic-machines/error-6/) indica que a válvula de cerâmica não está a funcionar como deve ser: o disco não atingiu a posição pedida pela placa. Na prática, há três causas, por ordem de probabilidade: o calcário endureceu o mecanismo e o motor já não o roda com folga; uma junta a vazar deixou entrar água no acionamento, molhando o motor e o encoder; ou o motor ou o respetivo sensor de posição morreram mesmo.

A causa mais provável resolve-se de graça — comece por ela.

1. Corra primeiro um ciclo completo de descalcificação. O calcário é a causa número um de um disco de cerâmica duro, e o remédio custa uma pastilha e uma hora.
2. Reinicie e escute. No arranque, a válvula percorre as suas posições com um estalido audível; se completar o ciclo de arranque, está resolvido.
3. Se o Erro 6 persistir, é preciso abrir a máquina: procure humidade à volta do corpo da válvula. Água ali significa uma junta a vazar a contaminar o acionamento.
4. A reparação passa por limpar ou substituir a válvula. Motor e válvula substituem-se em conjunto, como um conjunto único, não em separado.

Orce 55 € a 110 € para o conjunto da válvula de cerâmica, ou 10 € a 18 € se chegar apenas ao jogo de juntas.

## Erro 7: o irmão a sério

O [Erro 7](https://pt.codefixcoffee.com/jura/automatic-machines/error-7/) cobre o mesmo hardware a falhar mais a fundo, com o acionamento do grupo de preparação incluído: a máquina mandou a válvula de cerâmica (nos GIGA, a multiválvula) para uma posição e nunca a viu chegar, ou o acionamento do grupo desorientou-se pelo caminho. No GIGA X3c e X8c indica especificamente uma multiválvula avariada; no GIGA 6 surge muitas vezes relatado como motor ou bomba bloqueados. É um dos poucos códigos Jura sem solução fiável ao nível do utilizador.

Isso não significa que nada valha a pena tentar antes de marcar a recolha.

1. Desligue da corrente durante cinco minutos e reinicie. O ciclo de arranque repõe as posições do grupo e da válvula, pelo que um bloqueio passageiro pode dissipar-se sozinho.
2. Elimine as causas baratas: esvazie o recipiente de borras e a bandeja de gotejamento, confirme que nada está preso na saída do café e corra um programa de limpeza completo sem interromper.
3. Se o código continuar a voltar, o achado habitual lá dentro é o próprio conjunto da válvula — disco de cerâmica fissurado, atuador encravado ou encoder de posição avariado.

## Porque é que o Erro 7 é quase sempre reparação de bancada

O conselho honesto para este código é "bancada, a menos que já faça assistência a estas máquinas por gosto ou ofício". As razões são práticas, não misteriosas.

- As caixas Jura fecham com parafusos de segurança (Torx-Plus de cabeça oval) e há tensão de rede perto da zona de trabalho.
- A máquina tem de ser totalmente drenada antes de tocar na válvula, e o conjunto é delicado de manusear.
- Depois de substituir a válvula ou o motor do grupo, o mecanismo precisa de recalibração para a placa voltar a confiar nas leituras de posição.

Peças existem para a maioria dos modelos — um conjunto de válvula de cerâmica ou multiválvula fica entre 55 € e 140 € conforme o modelo, um motor de grupo entre 40 € e 65 € — mas a mão de obra normalmente ultrapassa a peça, por isso exija orçamento antes de encomendar seja o que for. A assistência oficial fora de garantia para uma superautomática ronda os 230 € a 460 € com transporte de regresso incluído, e uma assistência técnica independente sai geralmente mais barata quando se trata de uma peça conhecida. Para ter noção do que a desmontagem envolve, os guias de reparação do [iFixit](https://www.ifixit.com) são uma boa referência; as rotinas de manutenção oficial estão no [site da Jura](https://www.jura.com).

### A água dura do sul e o disco de cerâmica

Em Lisboa, no Alentejo e no Algarve a água da rede é notoriamente dura, e é precisamente o calcário que torna o disco da válvula rígido e difícil de rodar. Se a máquina vive numa destas zonas, faça as descalcificações a intervalos mais curtos do que os genéricos do manual e pondere um filtro de água. Sai muito mais barato do que uma válvula nova — e poupa-lhe o Erro 6.

## Vale a pena reparar?

As máquinas equipadas com válvula de cerâmica são, em regra, as que merecem ficar por casa: um Erro 6 que desaparece depois de uma descalcificação não custa um cêntimo. Com o Erro 7, a aritmética depende do modelo — numa Z ou GIGA de topo a reparação normalmente justifica-se, enquanto numa E ou ENA de entrada com dez anos convém comparar o orçamento com uma recondicionada antes de decidir.

Nem todos os códigos Jura acabam em bancada: o [Erro 12](https://pt.codefixcoffee.com/jura/automatic-machines/error-12/), o clássico encrave de uma pedra no moedor, resolve-se com um aspirador e uma vista de olhos aos grãos. A lista completa, incluindo os códigos de termobloco e de grupo de preparação, está no [índice de códigos de erro Jura](https://pt.codefixcoffee.com/jura/).
