---
title: Códigos ER da Sage/Breville — ler a tabela de serviço escondida
description: Os códigos ER das máquinas Sage e Breville vêm de uma tabela de serviço nunca publicada. Como funciona a tabela ER01–ER18 e a numeração da Oracle.
---

Quando uma máquina Breville trava de repente e mostra ER05 no painel, o manual não diz o que isso significa. Não é um esquecimento: os códigos de erro da Breville provêm das tabelas internas de serviço usadas nas oficinas, nunca divulgadas aos proprietários. O mesmo hardware chega a Portugal e ao resto da Europa com a marca **Sage** — máquinas idênticas, só muda o logótipo — pelo que um código ER numa Sage Barista Touch quer dizer exatamente o mesmo que na Breville equivalente. A nossa [secção Breville e Sage](https://pt.codefixcoffee.com/breville/) acompanha a gama atual; este artigo mostra como a numeração está organizada, para que até um código desconhecido lhe diga algo útil.

## Porque é que a Breville não publica os códigos

O manual do utilizador cobre a limpeza e a descalcificação, não o diagnóstico. As tabelas completas vivem atrás do modo de serviço de cada máquina: ecrãs protegidos por palavra-passe, pensados para técnicos, com contadores de avarias armazenados e leituras de sensores em tempo real. Sendo uma ferramenta de reparação e não uma funcionalidade de consumidor, nunca foram editadas em documento público — e a maioria dos proprietários chega apenas a ver o código único que provocou o encerramento. O contraste com a Miele é frontal: esta imprime os significados dos códigos F nas próprias instruções, e é por isso que as [páginas de códigos Miele](https://pt.codefixcoffee.com/miele/) podem citar o manual diretamente.

## A tabela da Barista Touch — ER01 a ER18

A Barista Touch (BES880) e a Barista Touch Impress (BES881) — que partilha a família de placas de controlo e a tabela — usam uma lista de 18 entradas. Percebida a estrutura, lê-se com facilidade: os códigos de sensores chegam em **grupos de quatro**, um grupo por sensor, alternando circuito aberto no arranque, circuito aberto em funcionamento, curto-circuito no arranque e curto-circuito em funcionamento.

- **ER01 a ER04** — a sonda de temperatura do aquecedor ThermoJet (o "ferro"), nas quatro variantes aberto/curto. [ER01](https://pt.codefixcoffee.com/breville/barista-touch-bes880/er01/) é a entrada de circuito aberto no arranque.
- **ER05 a ER08** — a sonda de temperatura do jarro de leite, a pequena sonda na zona do tabuleiro de gotas que lê o jarro enquanto a varinha emulsiona o leite. O ER05, circuito aberto no arranque, é o código mais reportado de todos na Barista Touch, e as quatro entradas partilham a mesma correção.
- **ER09 a ER12** — a sonda de temperatura em linha, a da água de preparação, no mesmo padrão de quatro variantes.
- **ER13 e ER14** — erros de contagem do caudalímetro, no arranque e em funcionamento: a bomba trabalhou e a máquina não conseguiu contar a água que a atravessava.
- **ER15** — falha de comunicação entre módulos eletrónicos internos; muitas vezes um cabo flat desapertado ou um conector húmido, e não uma placa morta.
- **ER16 e ER17** — o moedor: motor sobreaquecido que se desligou por proteção e, a seguir, motor que não terminou a tarefa no tempo previsto.
- **ER18** — proteção E-fast, uma falha elétrica ou de segurança como corrente de fuga; é o código que também pode derrubar o diferencial da sua instalação.

## A família Oracle segue outra numeração

Na Oracle, a mesma ideia ganha uma tabela maior. A Oracle (BES980) e a Oracle Touch (BES990) partilham uma lista de 32 entradas, mas a BES980 apresenta-as como "Error 1" a "Error 32" enquanto a BES990 acrescenta o prefixo ER. As primeiras dezasseis seguem a lógica dos quartetos por quatro sensores — caldeira de vapor nos códigos 1 a 4, caldeira de café nos 5 a 8 (sendo [Error 8](https://pt.codefixcoffee.com/breville/oracle-bes980/error-8/) o curto-circuito da sonda da caldeira de café em funcionamento), grupo aquecido nos 9 a 12 e varinha de vapor nos 13 a 16. O resto da lista cobre caldeiras que não aquecem (17 a 19), falhas de nível e de enchimento da caldeira de vapor (20 e 21), problemas de caudalímetro (22 e 23), sondas de nível e sobreaquecimento (24 a 27), uma falha de comunicação de placa no 28, o moedor nos 29 e 30, o motor de compactação no 31 e uma fuga ou falha de reenchimento da caldeira de vapor no 32.

Duas tabelas mais pequenas completam a família. A Oracle Jet (BES985) usa uma lista própria e mais curta, de E1 a E19, e a Dual Boiler (BES920) guarda códigos de dois dígitos, 00 a 12, dentro de um menu de autoteste em vez do visor normal — uma Dual Boiler pode estar parada numa avaria que nunca chegou a ver no ecrã.

## Ler o registo de erros escondido por si

Sendo dados de serviço, a forma de consultar o histórico da máquina passa pelos próprios ecrãs de serviço. Os caminhos sabem a oficina, mas estão bem documentados por reparadores e em plataformas como o [iFixit](https://www.ifixit.com):

- **Barista Touch e Oracle Touch** — desligue à parede, mantenha o botão Power frontal premido enquanto religa a corrente, largue quando o logótipo aparecer, introduza a palavra-passe de serviço 00000 e abra Error Counter para as avarias armazenadas ou Live Debug para temperaturas e níveis em tempo real.
- **Barista Touch Impress** — a mesma sequência de botões, mas a palavra-passe é 02015.
- **Oracle BES980** — com a máquina ligada à corrente mas desligada, prima 1 CUP, 2 CUP e POWER em conjunto durante pelo menos um segundo; após o sinal sonoro longo, rode o botão SELECT para abrir a Error Storage e percorrer os erros 1 a 32 com as contagens guardadas.

Trate estes ecrãs como leitura: registe o que está armazenado, não mexa nas configurações e limpe o registo só depois de uma reparação, para confirmar se o código regressa ou não.

## Quanto custam as reparações

Mesmo perante uma tabela não publicada, a economia é previsível. Os conjuntos de sonda de temperatura custam cerca de €25 a €95 conforme o sensor (as sondas da varinha de vapor e do jarro de leite são as mais caras), os kits de anéis vedantes €10 a €20 e um kit de reparação da sonda de leite fica nos €30 a €50 contra €80 a €95 do conjunto original. Os orçamentos do fabricante fora de garantia para avarias internas rondam habitualmente os €300 a €500, pelo que a correção ao nível do sensor, a preços de reparador independente, é quase sempre o melhor caminho. Manuais, filtros e descalcificantes oficiais de cada modelo estão na área de apoio do [site da Sage Appliances](https://www.sageappliances.co.uk); a cobertura dessas mesmas tabelas com foco no Reino Unido está na [edição britânica do site](https://pt.codefixcoffee.com/uk/).

### Sage em Portugal — compra e garantia

Em Portugal, estas máquinas vendem-se com a marca Sage através de cadeias nacionais e de lojas online, e a fatura é o documento que ativa a garantia legal de dois anos — sendo ao vendedor, não ao fabricante, que deve reclamar avarias dentro desse prazo, incluindo um sensor defeituoso. Fora da garantia, os reparadores independentes de máquinas de café são a alternativa com melhor relação custo-benefício para trocas de sondas e vedantes. Guarde sempre o comprovativo de compra: sem ele, a reclamação complica-se.
