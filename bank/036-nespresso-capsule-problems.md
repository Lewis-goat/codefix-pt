---
title: "Nespresso: quando a máquina culpa a cápsula"
description: "A sua Nespresso culpa a cápsula quando a falha está no sensor, na janela suja ou numa descalcificação interrompida. Descodifique os pisca-piscas e o 1301."
---

Poucas avarias apontam tão depressa para o utilizador como uma Nespresso Vertuo que recusa uma cápsula. A cápsula entra, a alavanca fecha e a máquina comporta-se como se não houvesse nada — ou pisca e desiste. A gama Vertuo (Next, Plus, Pop, Evoluo) fala quase exclusivamente em padrões de luz, documentados nas páginas de assistência do [site oficial da Nespresso](https://www.nespresso.com); já os códigos numéricos dos modelos conectados vêm dos ecrãs das máquinas e de relatos de proprietários, não de qualquer tabela oficial. As duas linguagens estão cobertas na [secção Nespresso](https://pt.codefixcoffee.com/nespresso/) do nosso site; este artigo ocupa-se do caso em que a máquina acusa a cápsula — e a cápsula é inocente.

## Como é que uma Vertuo lê uma cápsula

As cápsulas Vertuo trazem um código de barras impresso à volta da borda. A máquina lê-o através de uma pequena janela na cabeça, fura a folha e põe a cápsula a rodar enquanto empurra água através dela. Duas coisas têm de correr bem:

- **O sensor tem de ler o código de barras.** Salpicos de café e pó na janela da cápsula chegam para uma leitura falhada.
- **A cápsula tem de assentar direita,** de modo a que a folha seja furada de forma limpa e a cápsula rode sem oscilar.

Se qualquer das duas falhar, a máquina reporta um problema de cápsula sem indicar de que lado esteve a falha — a origem de quase toda a confusão.

### Sintomas que apontam para a máquina, não para a cápsula

- A máquina comporta-se como se não houvesse cápsula, apesar de ela estar colocada e da cabeça fechada.
- Recusa **todas** as cápsulas — embalagens diferentes, stock fresco, cápsulas originais.
- Limpar a janela e o porta-cápsulas melhora ou resolve o problema.
- Nas máquinas conectadas surge um código da família 1301 — o ramo do sensor de cápsula, detalhado na nossa [referência 1301–1305](https://pt.codefixcoffee.com/nespresso/vertuo-machines/1301-1305/).

Se a falha acompanha a máquina por todas as cápsulas que tem em casa, deixe de comprar embalagens novas e passe a limpar.

## Quando a cápsula é mesmo o problema

Também há cápsulas que falham, e vale a pena eliminá-las do lado mais barato antes de tocar na máquina:

- Uma borda amolgada ou esmagada — por transporte, armazenamento ou uma queda — impede a cápsula de assentar direita; é furada de lado e pinga em vez de extrair.
- Folha rasgada ou abaulada em cápsulas velhas; as cápsulas absorvem humidade lentamente e incham fora da tolerância.
- Uma cápsula presa no porta-cápsulas de um ciclo anterior, a impedir a seguinte de assentar.

O teste que encerra a questão: experimente uma cápsula original fresca, tirada do meio de uma embalagem nova; se extrair normalmente, o problema eram as cápsulas anteriores. E nunca force o fecho da cabeça sobre uma cápsula que não esteja bem sentada.

## Padrões de luz que apontam para as cápsulas

As Vertuo não têm um piscar dedicado a "cápsula inválida"; o botão único e o anel de luz codificam subsistemas, não peças isoladas. Os padrões que voltam sempre:

- **Piscas sequenciais ou alternados logo a seguir à ligação** significam modo de aquecimento. Espere quinze a vinte e cinco segundos; não é avaria nenhuma.
- **Laranja intermitente, em qualquer padrão,** pertence à família descalcificação — necessária, em curso ou atrasada. Um laranja que nunca termina quer quase sempre dizer que uma descalcificação foi iniciada e nunca concluída.
- **Vermelho fixo ou a repetir-se** é estado de erro, tipicamente sobreaquecimento ou erro interno. Desligue da corrente durante pelo menos dez minutos, deixe arrefecer e tente de novo.

Antes de mexer em seja o que for, repare na cor, se está fixa ou intermitente e quantas piscas há por grupo — o [descodificador de luzes Vertuo](https://pt.codefixcoffee.com/nespresso/vertuo-machines/blinking-lights/) mapeia cada padrão no seu subsistema. E guarde o reset de fábrica para o fim, nunca para o princípio: ele apaga os lembretes de descalcificação e o emparelhamento sem consertar nada de mecânico.

## A sobreposição do 1301: o código que culpa a cápsula

Nas Vertuo conectadas, a família 1300 é onde o problema da cápsula e o da descalcificação se cruzam. Os relatos dos proprietários associam de forma consistente o 1301 a dois estados: a máquina presa em modo de descalcificação (ou com ele em atraso), e o sensor que não lê a cápsula, com os códigos vizinhos da mesma família. Ou seja: um código com ar de reclamação da cápsula pode ser uma reclamação de descalcificação com o mesmo número. A sequência oficial ataca as duas metades ao mesmo tempo:

1. Reset de fábrica: com a alavanca na posição UNLOCKED, prima o botão cinco vezes em três segundos; a máquina pisca laranja cinco vezes a confirmar.
2. Corra um ciclo de descalcificação completo com descalcificador Nespresso, sem interrupções — uma descalcificação cancelada é a forma clássica de estas máquinas ficarem presas nesse modo.
3. Retire o porta-cápsulas e limpe a janela da cápsula e a cabeça da máquina, para o sensor conseguir ler o código de barras.
4. Esvazie e volte a encher o depósito de água; teste com uma cápsula fresca.
5. Se o problema persistir depois de todos os passos, contacte a assistência da Nespresso em vez de continuar a insistir — a empresa costuma substituir as Vertuo avariadas ao abrigo da garantia, em vez de as reparar.

Duas cautelas: nunca descalcifique com vinagre, porque danifica o circuito e pode fazer perder a assistência; e, em matéria de custos, esta sequência raramente passa do descalcificador, a cerca de €10 a €15.

### Em Portugal

A assistência da Nespresso em Portugal passa pelo Clube Nespresso — aplicação, telefone ou balcão — e há boutiques em Lisboa e no Porto onde pode entregar a máquina. Como o desfecho habitual é a troca em garantia, guarde bem o comprovativo da compra: pedem-no quase sempre. O descalcificador oficial chega por encomenda ou em qualquer boutique.

## O contraste com uma máquina de grãos

Uma Philips ou Saeco que mói os próprios grãos bloqueia à sua maneira — café moído a compactar no funil, o [Erro 01](https://pt.codefixcoffee.com/philips-saeco/espresso-machines/error-01/) —, enquanto as falhas do percurso do café numa máquina de cápsulas se reduzem quase sempre aos mesmos três suspeitos: a janela do código de barras, a perfuração da folha ou uma descalcificação nunca concluída. Limpe a janela, teste uma cápsula de confiança, descodifique o anel de luz antes de agir — e a máquina deixa de culpar as cápsulas.
