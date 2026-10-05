---
title: Fazer você mesmo ou chamar um técnico? Ler bem a dificuldade
description: Como avaliar um código de erro: gravidade versus dificuldade, sinais de paragem, parafusos de segurança, tensão de rede e a matemática dos custos.
---

O ecrã mostra um código, o remédio do manual não o limpou, e a questão passa a sentir-se pessoal: reparo eu ou pago a alguém? Na verdade, raramente é uma questão de perícia. É uma questão sobre a avaria, e separa-se em dois juízos que merecem ser feitos de forma independente: quão perigosa é a situação e quão difícil é a reparação.

## Gravidade não é dificuldade

**Gravidade** é a urgência em parar de usar a máquina — o risco de incêndio, de inundação ou de a avaria destruir outras peças pelo caminho. **Dificuldade** é o que a reparação exige de si: ferramentas, acesso e o quanto pode correr mal pelo meio. São escalas independentes; confundi-las produz tanto pânico como despreocupação.

- **Grave mas tratável.** O [E1 numa máquina de lavar loiça GE](https://pt.codefixcoffee.com/ge/dishwasher/e1-leak/) significa que o interruptor de inundação da base atuou — gravidade alta, e a máquina não volta a funcionar enquanto a base não secar e a fuga não for encontrada (o [site da GE Appliances](https://geappliances.com) publica os passos de diagnóstico recomendados). Mesmo assim, os primeiros gestos continuam simples: feche o fornecimento de água, corte a corrente, retire o painel inferior e seque tudo.
- **Espetacular mas moderado.** O [Error 8 da Jura](https://pt.codefixcoffee.com/jura/automatic-machines/error-8/) trava a máquina por completo porque o grupo de preparação não terminou o ciclo. Lê-se como uma avaria grave e é, quase sempre, trabalho de limpeza: a maioria dos Error 8 custa uma pastilha.
- **Grave e genuinamente difícil.** O [Error 7 da Jura](https://pt.codefixcoffee.com/jura/automatic-machines/error-7/) — a válvula nunca alcançou a posição comandada pela placa — é um dos poucos códigos Jura sem correção fiável ao nível do utilizador.
- **Fora de questão desde o início.** O [F77 da Miele](https://pt.codefixcoffee.com/miele/cm-cva-machines/f77/) é uma falha interna de válvula cujo remédio oficial se esgota num ciclo de alimentação, e a caixa está explicitamente interdita de abrir: tensões internas e um circuito de água pressurizado.

A regra prática: a gravidade decide **se pára**; a dificuldade decide **quem faz o trabalho**.

## Quando um código é sinal de paragem

Algumas condições encerram a fase de faça-você-mesmo antes de qualquer ferramenta sair do sítio, seja qual for o seu nível de confiança:

- **Água onde vive a eletrónica.** Um código de interruptor de inundação numa máquina de lavar loiça, como o E1, significa que a máquina não volta a ligar enquanto a base não secar e a fuga não for rastreada — não "só mais um ciclo para ver".
- **Um aquecedor que não desliga.** A variante séria de um código de sobretemperatura recorrente é a placa de controlo a falhar o corte da resistência de aquecimento. Trate-o como risco de incêndio: desligue a máquina e não a deixe alimentada sem vigilância.
- **O limite do próprio fabricante.** Quando o remédio documentado de um código é um reinício seguido de "contacte a assistência", e o manual manda não remover a caixa, é o fabricante a dizer-lhe onde fica a fronteira dele — e a sua margem de segurança.
- **Reincidência depois de uma reposição correta.** Desligue uma máquina de café durante cinco minutos, ou corte uma máquina de lavar loiça no disjuntor durante sessenta segundos. Um código que regressa no mesmo ponto do ciclo é um componente a falhar no seu teste, não um glitch.

## Tensão de rede e parafusos de segurança

O acesso é a parte honesta da dificuldade nas máquinas de café. As caixas Jura fecham com parafusos de segurança Torx-Plus de cabeça oval, e os terminais do termobloco lá dentro transportam tensão de rede. As peças para substituir a válvula de um Error 7 vendem-se a qualquer pessoa, mas instalá-las implica parafusos de segurança, consciência do lado vivo e recalibração do mecanismo no final — o veredicto honesto para esse código é reparação de bancada, salvo se já presta assistência a estas máquinas. Se não possui a chave certa, considere a caixa fechada.

A mesma disciplina vale no resto da casa. Isole na tomada ou no disjuntor, nunca pelo interruptor da própria máquina. E nunca drible um dispositivo de segurança: um fusível térmico existe precisamente para falhar, e atalhá-lo para testar uma resistência de aquecimento não lhe ensina nada que quisesse saber. Quem quiser aprofundar técnicas de abertura e segurança encontra guias de reparação genéricos na [iFixit](https://ifixit.com).

## A matemática dos custos

Antes de escolher um caminho, pondere os três:

1. **A tentativa gratuita.** Reposição, ciclo de limpeza, reencaixe da peça, descalcificação. Não custa nada e resolve uma boa fatia dos códigos do dia a dia.
2. **A reparação caseira.** Some peças, ferramentas e o risco de um diagnóstico errado. As pastilhas de limpeza custam €15 a €25, um grupo de preparação Jura €80 a €150 e um conjunto de válvula cerâmica €60 a €150 conforme o modelo.
3. **O técnico.** O serviço pós-garantia do fabricante para uma superautomática situa-se tipicamente entre €250 e €500 com o transporte de regresso incluído, e os reparadores independentes de máquinas de café saem geralmente mais baratos num trabalho de peça única. Um técnico de eletrodomésticos ao domicílio cobra €120 a €250 pelo diagnóstico, mais a peça.

Depois pese o total contra a própria máquina. Numa [Jura](https://pt.codefixcoffee.com/jura/) Z ou GIGA de gama alta, até o valor mais alto desta gama de serviço costuma compensar; numa E ou ENA de entrada com dez anos, compare o orçamento com uma unidade recondicionada. Repare também onde a mão de obra domina: no Error 7, o trabalho de oficina costuma ultrapassar o valor da peça.

### Dica para Portugal: 230 V, diferencial e rede de assistência

Em Portugal a tensão de rede é de 230 V e as máquinas cá vendidas vêm preparadas para isso, mas a exigência de segurança mantém-se: desligue sempre na tomada e, se necessário, no disjuntor do quadro, confirmando que o circuito está protegido por interruptor diferencial. As grandes marcas têm assistência técnica autorizada em Portugal, e os reparadores independentes de máquinas de café concentram-se sobretudo em Lisboa e no Porto — peça sempre um orçamento escrito antes de autorizar a intervenção.

O código já cumpriu a sua função ao nomear o circuito. Julgue primeiro a gravidade e pare, se ele o mandar. Julgue depois a dificuldade e deixe que a distância entre a sua caixa de ferramentas e a reparação decida quem faz o trabalho.
