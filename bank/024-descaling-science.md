---
title: Descalcificação explicada como deve ser
description: O que o calcário faz a termoblocos e válvulas, porque o vinagre não serve para algumas máquinas, ácido cítrico vs láctico e a frequência por dureza.
---

Em qualquer lista de avarias de máquinas de café há uma causa de fundo que domina todas as outras: o calcário. A água dura transporta cálcio e magnésio dissolvidos; aqueça essa água e os carbonatos saem da solução, depositando-se no metal mais quente da máquina. Só isto é o calcário — e é ele que está por trás de uma fatia desproporcional dos códigos deste site: avarias da resistência de aquecimento, avarias de válvula, falhas de primagem e luzes de descalcificação presas. É também a única família de avarias com uma solução de €10.

## O que o calcário faz a um termobloco

Um termobloco é uma massa de metal atravessada por um canal estreito onde a água aquece a caminho da chávena. O calcário deposita-se nessas paredes e o carbonato de cálcio é um isolante térmico razoável — e é exatamente aí que começa o problema.

- **O aquecimento abranda.** A resistência de aquecimento trabalha mais tempo para atingir a temperatura-alvo, e o calcário pesado chega para fazer disparar os próprios controlos de temperatura da placa em algumas máquinas — a [documentação da Jura](https://www.jura.com/) liga explicitamente o calcário à família de códigos de termobloco.
- **A sonda mente.** Uma camada de calcário altera a rapidez com que a sonda no interior do bloco sente o calor, e a placa pode acreditar que a máquina está a sobreaquecer — ou a falhar o aquecimento — quando nenhuma das coisas é verdade.
- **O bloco trabalha acima da conta.** O metal isolado fica acima da temperatura de projeto, o que força os fusíveis térmicos que o protegem. Um termobloco calcificado até ao tutano é peça para substituir, não para limpar: €90 a €180 numa Jura, por calcário que um frasco de descalcificador teria removido.

## O que o calcário faz a válvulas e orifícios estreitos

O segundo campo de batalha é tudo o que é estreito. Nas máquinas Jura com válvula cerâmica motorizada, o calcário endurece o disco até este deixar de alcançar a posição ordenada pela placa — é exatamente isso que o [Erro 6](https://pt.codefixcoffee.com/jura/automatic-machines/error-6/) reporta, e por isso a descalcificação completa é o primeiro passo, e gratuito, da sua correção. As entradas estreitas entopem pelo mesmo mecanismo: o [Erro 05 da Philips](https://pt.codefixcoffee.com/philips-saeco/espresso-machines/error-05/) pode persistir depois da primagem porque uma entrada calcificada impede a bomba de sugar água. Os sensores de nível também contam — calcário num flutuador do depósito é causa clássica do falso aviso para encher um depósito que já está cheio. E um caudalímetro calcificado deixa de contar, que é uma das formas de a [luz de descalcificação da De'Longhi ficar acesa depois de descalcificar](https://pt.codefixcoffee.com/delonghi/magnifica-dinamica/descale-light-stays-on-after-descaling/): a máquina nunca registou o ciclo que correu.

## Porque é que o vinagre não serve para algumas máquinas

O vinagre de cozinha é ácido acético e, para máquinas de espresso, acumula três deméritos. É fraco, pelo que precisa de longos tempos de contacto para amolecer calcário compacto dentro de um canal apertado. Ataca os acessórios de latão cromado e incha certas juntas de borracha. E o seu cheiro sobrevive a muitas lavagens dentro dos tubos de plástico. A [Nespresso](https://www.nespresso.com/) é explícita quanto às consequências: não descalcifique com vinagre, porque danifica o circuito e faz perder o apoio — convém recordá-lo quando o [padrão de luzes cor-de-laranja de uma Vertuo](https://pt.codefixcoffee.com/nespresso/vertuo-machines/blinking-lights/) o mandar para a rotina de descalcificação. Num bule de chá elétrico? Vinagre serve. Numa máquina com bomba, válvula e garantia? Use um descalcificador a sério.

## Ácido cítrico ou ácido láctico

Quase todos os descalcificadores comerciais assentam num de dois ácidos alimentares:

- **Ácido cítrico** — vende-se em pó, €3 a €6 para o equivalente a um ano numa casa normal, forte e rápido sobre calcário pesado. É a base da maioria dos descalcificadores universais; com bom enxaguamento, não deixa nada atrás.
- **Ácido láctico** — mais suave e praticamente inodoro, comum nos frascos de marca que acompanham as máquinas. Mais gentil para juntas e acabamentos, em troca de precisar de um tempo de contacto um pouco maior para o mesmo calcário.

Qualquer um deles funciona corrido pelo programa de descalcificação da própria máquina. O que conta é completá-lo: os contadores de aviso só registam um ciclo inteiro lançado a partir do menu de descalcificação, com o bico montado e a fase de enxaguamento incluída. Pare a meio ou improvise com um jarro, e [a luz fica acesa na mesma](https://pt.codefixcoffee.com/delonghi/magnifica-dinamica/descale-light-stays-on-after-descaling/).

## Com que frequência: depende da sua água

Os lembretes das máquinas contam volume — chávenas servidas, litros bombeados — e não dureza, por isso as casas com água dura devem descalcificar antes de a luz alguma vez acender. Uma regra prática:

- **Água macia** (abaixo de cerca de 7 °dH, ou 125 ppm): o lembrete da própria máquina chega; na prática, a cada 3 a 6 meses.
- **Moderadamente dura** (7 a 14 °dH): a cada 2 a 3 meses.
- **Dura** (acima de 14 °dH): aproximadamente uma vez por mês, e mais cedo se o caudal abrandar ou a bomba ficar ruidosa.

### E a água em Portugal?

A dureza da água varia muito dentro do país: em regra, é macia nas zonas graníticas do Norte e mais dura no Sul e nas áreas calcárias, como o Algarve e o Alentejo. A ERSAR publica a qualidade da água por sistema de abastecimento, e a entidade gestora do seu concelho indica a dureza da zona — vale a pena confirmar esse valor antes de fixar o intervalo de descalcificação. Se usar água engarrafada na máquina, o rótulo lista o resíduo seco e o cálcio, o que permite comparar marcas e escolher uma água mais macia.

Um pacote de tiras de teste de dureza custa €5 a €10, e a frequência certa sai desse número. Os sinais tardios são iguais em todas as marcas: caudais lentos e finos, bomba mais ruidosa, café mais frio — e, no fim da linha, os códigos acima. Descalcifique a tempo e a maioria desses códigos nunca chega a existir; um frasco de €10 é a reparação mais barata que este site alguma vez recomendará.
