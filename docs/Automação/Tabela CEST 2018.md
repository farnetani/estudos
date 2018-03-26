# Tabela CEST 2018 Atualizada

## Download

* [Tabela CEST 2018 Mysql][1]

* [Tabela CEST 2018 Firebird][2]

* [Tabela CSV][3]

[1]: ../../assets/downloads/tabela_cest_mysql_2018.sql
[2]: ../../assets/downloads/tabela_cest_firebird_2018.sql
[3]: ../../assets/downloads/tabela_csv.csv

***

## Tabela CEST 2018 em SQL para Mysql

- Estrutura: id, cest, ncm, descricao, item

```
INSERT INTO tab_cest VALUES
(1, '0100100', '38151210', 'Catalisadores em colmeia cerâmica ou metálica para conversão catalítica de gases de escape de veículos e outros catalisadores', '1.0'),
(2, '0100100', '38151290', 'Catalisadores em colmeia cerâmica ou metálica para conversão catalítica de gases de escape de veículos e outros catalisadores', '1.0'),
(3, '0100200', '3917', 'Tubos e seus acessórios (por exemplo, juntas, cotovelos, flanges, uniões), de plásticos', '2.0'),
(4, '0100300', '39181000', 'Protetores de caçamba', '3.0'),
(5, '0100400', '39233000', 'Reservatórios de óleo', '4.0'),
(6, '0100500', '39263000', 'Frisos, decalques, molduras e acabamentos', '5.0'),
(7, '0100600', '40103', 'Correias de transmissão de borracha vulcanizada, de matérias têxteis, mesmo impregnadas, revestidas ou recobertas, de plástico, ou estratificadas com plástico ou reforçadas com metal ou com outras matérias', '6.0'),
(8, '0100600', '59100000', 'Correias de transmissão de borracha vulcanizada, de matérias têxteis, mesmo impregnadas, revestidas ou recobertas, de plástico, ou estratificadas com plástico ou reforçadas com metal ou com outras matérias', '6.0'),
(9, '0100700', '40169300', 'Juntas, gaxetas e outros elementos com função semelhante de vedação', '7.0'),
(10, '0100700', '4823909', 'Juntas, gaxetas e outros elementos com função semelhante de vedação', '7.0'),
(11, '0100800', '40161010', 'Partes de veículos automóveis, tratores e máquinas autopropulsadas', '8.0'),
(12, '0100900', '40169990', 'Tapetes, revestimentos, mesmo confeccionados, batentes, buchas e coxins', '9.0'),
(13, '0100900', '57050000', 'Tapetes, revestimentos, mesmo confeccionados, batentes, buchas e coxins', '9.0'),
(14, '0101000', '59039000', 'Tecidos impregnados, revestidos, recobertos ou estratificados, com plástico', '10.0'),
(15, '0101100', '59090000', 'Mangueiras e tubos semelhantes, de matérias têxteis, mesmo com reforço ou acessórios de outras matérias', '11.0'),
(16, '0101200', '63061', 'Encerados e toldos', '12.0'),
(17, '0101300', '65061000', 'Capacetes e artefatos de uso semelhante, de proteção, para uso em motocicletas, incluídos ciclomotores', '13.0'),
(18, '0101400', '6813', 'Guarnições de fricção (por exemplo, placas, rolos, tiras, segmentos, discos, anéis, pastilhas), não montadas, para freios, embreagens ou qualquer outro mecanismo de fricção, à base de amianto, de outras substâncias minerais ou de celulose, mesmo combinadas com têxteis ou outras matérias', '14.0'),
(19, '0101500', '70071100', 'Vidros de dimensões e formatos que permitam aplicação automotiva', '15.0'),
(20, '0101500', '70072100', 'Vidros de dimensões e formatos que permitam aplicação automotiva', '15.0'),
(21, '0101600', '70091000', 'Espelhos retrovisores', '16.0'),
(22, '0101700', '70140000', 'Lentes de faróis, lanternas e outros utensílios', '17.0'),
(23, '0101800', '73110000', 'Cilindro de aço para GNV (gás natural veicular)', '18.0'),
(24, '0101900', '73110000', 'Recipientes para gases comprimidos ou liquefeitos, de ferro fundido, ferro ou aço, exceto o descrito no item 18.0', '19.0'),
(25, '0102000', '7320', 'Molas e folhas de molas, de ferro ou aço', '20.0'),
(26, '0102100', '7325', 'Obras moldadas, de ferro fundido, ferro ou aço, exceto as do código 7325.91.00', '21.0'),
(27, '0102200', '780600', 'Peso de chumbo para balanceamento de roda', '22.0'),
(28, '0102300', '80070090', 'Peso para balanceamento de roda e outros utensílios de estanho', '23.0'),
(29, '0102400', '830120', 'Fechaduras e partes de fechaduras', '24.0'),
(30, '0102400', '830160', 'Fechaduras e partes de fechaduras', '24.0'),
(31, '0102500', '830170', 'Chaves apresentadas isoladamente', '25.0'),
(32, '0102600', '83021000', 'Dobradiças, guarnições, ferragens e artigos semelhantes de metais comuns', '26.0'),
(33, '0102600', '83023000', 'Dobradiças, guarnições, ferragens e artigos semelhantes de metais comuns', '26.0'),
(34, '0102700', '831000', 'Triângulo de segurança', '27.0'),
(35, '0102800', '84073', 'Motores de pistão alternativo dos tipos utilizados para propulsão de veículos do Capítulo 87', '28.0'),
(36, '0102900', '840820', 'Motores dos tipos utilizados para propulsão de veículos automotores', '29.0'),
(37, '0103000', '84099', 'Partes reconhecíveis como exclusiva ou principalmente destinadas aos motores das posições 8407 ou 8408', '30.0'),
(38, '0103100', '84122', 'Motores hidráulicos', '31.0'),
(39, '0103200', '841330', 'Bombas para combustíveis, lubrificantes ou líquidos de arrefecimento, próprias para motores de ignição por centelha ou por compressão', '32.0'),
(40, '0103300', '84141000', 'Bombas de vácuo', '33.0'),
(41, '0103400', '8414801', 'Compressores e turbocompressores de ar', '34.0'),
(42, '0103400', '8414802', 'Compressores e turbocompressores de ar', '34.0'),
(43, '0103500', '84139190', 'Partes das bombas, compressores e turbocompressores dos CEST 01.032.00, 01.033.00 e 01.034.00', '35.0'),
(44, '0103500', '84149010', 'Partes das bombas, compressores e turbocompressores dos CEST 01.032.00, 01.033.00 e 01.034.00', '35.0'),
(45, '0103500', '8414903', 'Partes das bombas, compressores e turbocompressores dos CEST 01.032.00, 01.033.00 e 01.034.00', '35.0'),
(46, '0103500', '8414909', 'Partes das bombas, compressores e turbocompressores dos CEST 01.032.00, 01.033.00 e 01.034.00', '35.0'),
(47, '0103600', '841520', 'Máquinas e aparelhos de ar condicionado', '36.0'),
(48, '0103700', '84212300', 'Aparelhos para filtrar óleos minerais nos motores de ignição por centelha ou por compressão', '37.0'),
(49, '0103800', '84212990', 'Filtros a vácuo', '38.0'),
(50, '0103900', '84219', 'Partes dos aparelhos para filtrar ou depurar líquidos ou gases', '39.0'),
(51, '0104000', '84241000', 'Extintores, mesmo carregados', '40.0'),
(52, '0104100', '84213100', 'Filtros de entrada de ar para motores de ignição por centelha ou por compressão', '41.0'),
(53, '0104200', '84213920', 'Depuradores por conversão catalítica de gases de escape', '42.0'),
(54, '0104300', '84254200', 'Macacos', '43.0'),
(55, '0104500', '8431492', 'Partes reconhecíveis como exclusiva ou principalmente destinadas às máquinas agrícolas ou rodoviárias', '45.0'),
(56, '0104501', '84339090', 'Partes reconhecíveis como exclusiva ou principalmente destinadas às máquinas agrícolas ou rodoviárias', '45.1'),
(57, '0104600', '84811000', 'Válvulas redutoras de pressão', '46.0'),
(58, '0104700', '84812', 'Válvulas para transmissão óleo-hidráulicas ou pneumáticas', '47.0'),
(59, '0104800', '84818092', 'Válvulas solenoides', '48.0'),
(60, '0104900', '8482', 'Rolamentos', '49.0'),
(61, '0105000', '8483', 'Árvores de transmissão (incluídas as árvores de “cames” e virabrequins) e manivelas; mancais e “bronzes”; engrenagens e rodas de fricção; eixos de esferas ou de roletes; redutores, multiplicadores, caixas de transmissão e variadores de velocidade, incluídos os conversores de torque; volantes e polias, incluídas as polias para cadernais; embreagens e dispositivos de acoplamento, incluídas as juntas de articulação', '50.0'),
(62, '0105100', '8484', 'Juntas metaloplásticas; jogos ou sortidos de juntas de composições diferentes, apresentados em bolsas, envelopes ou embalagens semelhantes; juntas de vedação mecânicas (selos mecânicos)', '51.0'),
(63, '0105200', '850520', 'Acoplamentos, embreagens, variadores de velocidade e freios, eletromagnéticos', '52.0'),
(64, '0105300', '850710', 'Acumuladores elétricos de chumbo, do tipo utilizado para o arranque dos motores de pistão, exceto os classificados no CEST 01.053.01', '53.0'),
(65, '0105301', '85071010', 'Acumuladores elétricos de chumbo, do tipo utilizado para o arranque dos motores de pistão e de capacidade inferior ou igual a 20 Ah e tensão inferior ou igual a 12 V', '53.1'),
(66, '0105400', '8511', 'Aparelhos e dispositivos elétricos de ignição ou de arranque para motores de ignição por centelha ou por compressão (por exemplo, magnetos, dínamos-magnetos, bobinas de ignição, velas de ignição ou de aquecimento, motores de arranque); geradores (dínamos e alternadores, por exemplo) e conjuntores-disjuntores utilizados com estes motores', '54.0'),
(67, '0105500', '851220', 'Aparelhos elétricos de iluminação ou de sinalização (exceto os da posição 8539), limpadores de para-brisas, degeladores e desembaçadores (desembaciadores) elétricos e suas partes', '55.0'),
(68, '0105500', '851240', 'Aparelhos elétricos de iluminação ou de sinalização (exceto os da posição 8539), limpadores de para-brisas, degeladores e desembaçadores (desembaciadores) elétricos e suas partes', '55.0'),
(69, '0105500', '85129000', 'Aparelhos elétricos de iluminação ou de sinalização (exceto os da posição 8539), limpadores de para-brisas, degeladores e desembaçadores (desembaciadores) elétricos e suas partes', '55.0'),
(70, '0105600', '85171213', 'Telefones móveis do tipo dos utilizados em veículos automóveis.', '56.0'),
(71, '0105700', '8518', 'Alto-falantes, amplificadores elétricos de audiofrequência e partes', '57.0'),
(72, '0105800', '85185000', 'Aparelhos elétricos de amplificação de som para veículos automotores', '58.0'),
(73, '0105900', '851981', 'Aparelhos de reprodução de som', '59.0'),
(74, '0106000', '8525501', 'Aparelhos transmissores (emissores) de radiotelefonia ou radiotelegrafia (rádio receptor/transmissor)', '60.0'),
(75, '0106000', '85256010', 'Aparelhos transmissores (emissores) de radiotelefonia ou radiotelegrafia (rádio receptor/transmissor)', '60.0'),
(76, '0106100', '85272100', 'Aparelhos receptores de radiodifusão que só funcionem com fonte externa de energia combinados com um aparelho de gravação ou de reprodução de som, do tipo utilizado em veículos automóveis', '61.0'),
(77, '0106200', '85272900', 'Outros aparelhos receptores de radiodifusão que só funcionem com fonte externa de energia, do tipo utilizado em veículos automóveis', '62.0'),
(78, '0106201', '85219090', 'Outros aparelhos videofônicos de gravação ou de reprodução, mesmo incorporando um receptor de sinais videofônicos, dos tipos utilizados exclusivamente em veículos automotores', '62.1'),
(79, '0106300', '85291090', 'Antenas', '63.0'),
(80, '0106400', '853400', 'Circuitos impressos', '64.0'),
(81, '0106500', '853530', 'Interruptores e seccionadores e comutadores', '65.0'),
(82, '0106500', '853650', 'Interruptores e seccionadores e comutadores', '65.0'),
(83, '0106600', '85361000', 'Fusíveis e corta-circuitos de fusíveis', '66.0'),
(84, '0106700', '85362000', 'Disjuntores', '67.0'),
(85, '0106800', '85364', 'Relés', '68.0'),
(86, '0106900', '8538', 'Partes reconhecíveis como exclusivas ou principalmente destinados aos aparelhos dos CEST 01.065.00, 01.066.00, 01.067.00 e 01.068.00', '69.0'),
(87, '0107000', '853910', 'Faróis e projetores, em unidades seladas', '70.0'),
(88, '0107100', '85392', 'Lâmpadas e tubos de incandescência, exceto de raios ultravioleta ou infravermelhos', '71.0'),
(89, '0107200', '85442000', 'Cabos coaxiais e outros condutores elétricos coaxiais', '72.0'),
(90, '0107300', '85443000', 'Jogos de fios para velas de ignição e outros jogos de fios', '73.0'),
(91, '0107400', '8707', 'Carroçarias para os veículos automóveis das posições 8701 a 8705, incluídas as cabinas', '74.0'),
(92, '0107500', '8708', 'Partes e acessórios dos veículos automóveis das posições 8701 a 8705', '75.0'),
(93, '0107600', '87141', 'Parte e acessórios de motocicletas (incluídos os ciclomotores)', '76.0'),
(94, '0107700', '87169090', 'Engates para reboques e semirreboques', '77.0'),
(95, '0107800', '902610', 'Medidores de nível; Medidores de vazão', '78.0'),
(96, '0107900', '902620', 'Aparelhos para medida ou controle da pressão', '79.0'),
(97, '0108000', '9029', 'Contadores, indicadores de velocidade e tacômetros, suas partes e acessórios', '80.0'),
(98, '0108100', '90303321', 'Amperímetros', '81.0'),
(99, '0108200', '90318040', 'Aparelhos digitais, de uso em veículos automóveis, para medida e indicação de múltiplas grandezas tais como: velocidade média, consumos instantâneo e médio e autonomia (computador de bordo)', '82.0'),
(100, '0108300', '9032892', 'Controladores eletrônicos', '83.0'),
(101, '0108400', '91040000', 'Relógios para painéis de instrumentos e relógios semelhantes', '84.0'),
(102, '0108500', '94012000', 'Assentos e partes de assentos', '85.0'),
(103, '0108500', '94019090', 'Assentos e partes de assentos', '85.0'),
(104, '0108600', '96138000', 'Acendedores', '86.0'),
(105, '0108700', '4009', 'Tubos de borracha vulcanizada não endurecida, mesmo providos de seus acessórios', '87.0'),
(106, '0108800', '45049000', 'Juntas de vedação de cortiça natural e de amianto', '88.0'),
(107, '0108800', '68129910', 'Juntas de vedação de cortiça natural e de amianto', '88.0'),
(108, '0108900', '48234000', 'Papel-diagrama para tacógrafo, em disco', '89.0'),
(109, '0109000', '39191010', 'Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários', '90.0'),
(110, '0109000', '39191020', 'Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários', '90.0'),
(111, '0109000', '39191090', 'Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários', '90.0'),
(112, '0109000', '39199010', 'Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários', '90.0'),
(113, '0109000', '39199020', 'Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários', '90.0'),
(114, '0109000', '39199090', 'Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários', '90.0'),
(115, '0109000', '87082999', 'Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários', '90.0'),
(116, '0109100', '84123110', 'Cilindros pneumáticos', '91.0'),
(117, '0109200', '84131900', 'Bomba elétrica de lavador de para-brisa', '92.0'),
(118, '0109200', '84135090', 'Bomba elétrica de lavador de para-brisa', '92.0'),
(119, '0109200', '84138100', 'Bomba elétrica de lavador de para-brisa', '92.0'),
(120, '0109300', '84136019', 'Bomba de assistência de direção hidráulica', '93.0'),
(121, '0109300', '84137010', 'Bomba de assistência de direção hidráulica', '93.0'),
(122, '0109400', '84145910', 'Motoventiladores', '94.0'),
(123, '0109400', '84145990', 'Motoventiladores', '94.0'),
(124, '0109500', '84213990', 'Filtros de pólen do ar-condicionado', '95.0'),
(125, '0109600', '85011019', '“Máquina” de vidro elétrico de porta', '96.0'),
(126, '0109700', '85013110', 'Motor de limpador de para-brisa', '97.0'),
(127, '0109800', '85045000', 'Bobinas de reatância e de autoindução', '98.0'),
(128, '0109900', '850720', 'Baterias de chumbo e de níquel-cádmio', '99.0'),
(129, '0109900', '850730', 'Baterias de chumbo e de níquel-cádmio', '99.0'),
(130, '0110000', '85123000', 'Aparelhos de sinalização acústica (buzina)', '100.0'),
(131, '0110100', '9032898', 'Instrumentos para regulação de grandezas não elétricas', '101.0'),
(132, '0110100', '9032899', 'Instrumentos para regulação de grandezas não elétricas', '101.0'),
(133, '0110200', '90271000', 'Analisadores de gases ou de fumaça (sonda lambda)', '102.0'),
(134, '0110300', '40081100', 'Perfilados de borracha vulcanizada não endurecida', '103.0'),
(135, '0110400', '56012219', 'Artefatos de pasta de fibra de uso automotivo', '104.0'),
(136, '0110500', '57032000', 'Tapetes/carpetes - nailón', '105.0'),
(137, '0110600', '57033000', 'Tapetes de matérias têxteis sintéticas', '106.0'),
(138, '0110700', '59119000', 'Forração interior capacete', '107.0'),
(139, '0110800', '69039099', 'Outros para-brisas', '108.0'),
(140, '0110900', '70072900', 'Moldura com espelho', '109.0'),
(141, '0111000', '73145000', 'Corrente de transmissão', '110.0'),
(142, '0111100', '73151100', 'Corrente transmissão', '111.0'),
(143, '0111200', '73151210', 'Outras correntes de transmissão', '112.0'),
(144, '0111300', '84189900', 'Condensador tubular metálico', '113.0'),
(145, '0111400', '841950', 'Trocadores de calor', '114.0'),
(146, '0111500', '84249090', 'Partes de aparelhos mecânicos de pulverizar ou dispersar', '115.0'),
(147, '0111600', '84254910', 'Macacos manuais para veículos', '116.0'),
(148, '0111700', '84314100', 'Caçambas, pás, ganchos e tenazes para máquinas rodoviárias', '117.0'),
(149, '0111800', '85016100', 'Geradores de corrente alternada de potência não superior a 75 kva', '118.0'),
(150, '0111900', '85311090', 'Aparelhos elétricos para alarme de uso automotivo', '119.0'),
(151, '0112000', '90141000', 'Bússolas', '120.0'),
(152, '0112100', '90251990', 'Indicadores de temperatura', '121.0'),
(153, '0112200', '90259010', 'Partes de indicadores de temperatura', '122.0'),
(154, '0112300', '902690', 'Partes de aparelhos de medida ou controle', '123.0'),
(155, '0112400', '90321010', 'Termostatos', '124.0'),
(156, '0112500', '90321090', 'Instrumentos e aparelhos para regulação', '125.0'),
(157, '0112600', '90322000', 'Pressostatos', '126.0'),
(158, '0112700', '871690', 'Peças para reboques e semirreboques, exceto os itens classificados no CEST 01.077.00', '127.0'),
(159, '0112800', '73229010', 'Geradores de ar quente a combustível líquido, com capacidade superior ou igual a 1.500 kcal/h, mas inferior ou igual a 10.400 kcal/h, do tipo dos utilizados em veículos automóveis', '128.0'),
(160, '0199900', 'NT', 'Outras peças, partes e acessórios para veículos automotores não relacionados nos demais itens deste anexo', '999.0'),
(161, '0200100', '2205', 'Aperitivos, amargos, bitter e similares', '1.0'),
(162, '0200100', '22089000', 'Aperitivos, amargos, bitter e similares', '1.0'),
(163, '0200200', '22089000', 'Batida e similares', '2.0'),
(164, '0200300', '22089000', 'Bebida ice', '3.0'),
(165, '0200400', '220720', 'Cachaça e aguardentes', '4.0'),
(166, '0200400', '22084000', 'Cachaça e aguardentes', '4.0'),
(167, '0200500', '2205', 'Catuaba e similares', '5.0'),
(168, '0200500', '22060090', 'Catuaba e similares', '5.0'),
(169, '0200500', '22089000', 'Catuaba e similares', '5.0'),
(170, '0200600', '22082000', 'Conhaque, brandy e similares', '6.0'),
(171, '0200700', '22060090', 'Cooler', '7.0'),
(172, '0200700', '22089000', 'Cooler', '7.0'),
(173, '0200800', '22085000', 'Gim (gin) e genebra', '8.0'),
(174, '0200900', '2205', 'Jurubeba e similares', '9.0'),
(175, '0200900', '22060090', 'Jurubeba e similares', '9.0'),
(176, '0200900', '22089000', 'Jurubeba e similares', '9.0'),
(177, '0201000', '22087000', 'Licores e similares', '10.0'),
(178, '0201100', '22082000', 'Pisco', '11.0'),
(179, '0201200', '22084000', 'Rum', '12.0'),
(180, '0201300', '22060090', 'Saquê', '13.0'),
(181, '0201400', '22089000', 'Steinhaeger', '14.0'),
(182, '0201500', '22089000', 'Tequila', '15.0'),
(183, '0201600', '220830', 'Uísque', '16.0'),
(184, '0201700', '2205', 'Vermute e similares', '17.0'),
(185, '0201800', '22086000', 'Vodka', '18.0'),
(186, '0201900', '22089000', 'Derivados de vodka', '19.0'),
(187, '0202000', '22089000', 'Arak', '20.0'),
(188, '0202100', '22082000', 'Aguardente vínica / grappa', '21.0'),
(189, '0202200', '22060010', 'Sidra e similares', '22.0'),
(190, '0202300', '2205', 'Sangrias e coquetéis', '23.0'),
(191, '0202300', '22060090', 'Sangrias e coquetéis', '23.0'),
(192, '0202300', '22089000', 'Sangrias e coquetéis', '23.0'),
(193, '0202400', '2204', 'Vinhos de uvas frescas, incluindo os vinhos enriquecidos com álcool; mostos de uvas.', '24.0'),
(194, '0299900', '2205', 'Outras bebidas alcoólicas não especificadas nos itens anteriores', '999.0'),
(195, '0299900', '2206', 'Outras bebidas alcoólicas não especificadas nos itens anteriores', '999.0'),
(196, '0299900', '2207', 'Outras bebidas alcoólicas não especificadas nos itens anteriores', '999.0'),
(197, '0299900', '2208', 'Outras bebidas alcoólicas não especificadas nos itens anteriores', '999.0'),
(198, '0300100', '22011000', 'Água mineral, gasosa ou não, ou potável, naturais, em garrafa de vidro, retornável ou não, com capacidade de até 500 ml', '1.0'),
(199, '0300200', '22011000', 'Água mineral, gasosa ou não, ou potável, naturais, em embalagem com capacidade igual ou superior a 5.000 ml; exceto as classificadas no CEST 03.024.00 e 03.025.00', '2.0'),
(200, '0300300', '22011000', 'Água mineral, gasosa ou não, ou potável, naturais, em embalagem de vidro, não retornável, com capacidade de até 300 ml', '3.0'),
(201, '0300400', '22011000', 'Água mineral, gasosa ou não, ou potável, naturais, em garrafa plástica de 1.500 ml', '4.0'),
(202, '0300500', '22011000', 'Água mineral, gasosa ou não, ou potável, naturais, em copos plásticos e embalagem plástica com capacidade de até 500 ml', '5.0'),
(203, '0300600', '22011000', 'Outras águas minerais, potáveis ou naturais, gasosas ou não, inclusive gaseificadas; exceto as classificadas no CEST 03.024.00 e 03.025.00', '6.0'),
(204, '0300700', '22021000', 'Águas minerais, potáveis ou naturais, gasosas ou não, inclusive gaseificadas ou aromatizadas artificialmente, exceto os refrescos e refrigerantes', '7.0'),
(205, '0300800', '22029900', 'Outras águas minerais, potáveis ou naturais, gasosas ou não, inclusive gaseificadas ou aromatizadas artificialmente', '8.0'),
(206, '0301000', '2202', 'Refrigerantes em garrafa com capacidade igual ou superior a 600 ml, exceto os classificados no CEST 03.011.01', '10.0'),
(207, '0301100', '2202', 'Demais refrigerantes, exceto os classificados no CEST 03.010.00 e 03.011.01', '11.0'),
(208, '0301101', '2202', 'Espumantes sem álcool', '11.1'),
(209, '0301200', '21069010', 'Xarope ou extrato concentrado destinados ao preparo de refrigerante em máquina “pré-mix” ou “post-mix”', '12.0'),
(210, '0301300', '210690', 'Bebidas energéticas em embalagem com capacidade inferior a 600ml', '13.0'),
(211, '0301300', '22029900', 'Bebidas energéticas em embalagem com capacidade inferior a 600ml', '13.0'),
(212, '0301400', '210690', 'Bebidas energéticas em embalagem com capacidade igual ou superior a 600ml', '14.0'),
(213, '0301400', '22029900', 'Bebidas energéticas em embalagem com capacidade igual ou superior a 600ml', '14.0'),
(214, '0301500', '210690', 'Bebidas hidroeletrolíticas (isotônicas) em embalagem com capacidade inferior a 600ml', '15.0'),
(215, '0301500', '22029900', 'Bebidas hidroeletrolíticas (isotônicas) em embalagem com capacidade inferior a 600ml', '15.0'),
(216, '0301600', '210690', 'Bebidas hidroeletrolíticas (isotônicas) em embalagem com capacidade inferior a 600ml', '16.0'),
(217, '0301600', '22029900', 'Bebidas hidroeletrolíticas (isotônicas) em embalagem com capacidade igual ou superior a 600ml', '16.0'),
(218, '0302100', '22030000', 'Cerveja', '21.0'),
(219, '0302200', '22029100', 'Cerveja sem álcool', '22.0'),
(220, '0302300', '22030000', 'Chope', '23.0'),
(221, '0400100', '2402', 'Charutos, cigarrilhas e cigarros, de tabaco ou dos seus sucedâneos', '1.0'),
(222, '0400200', '24031', 'Tabaco para fumar, mesmo contendo sucedâneos de tabaco em qualquer proporção', '2.0'),
(223, '0500100', '2523', 'Cimento', '1.0'),
(224, '0600100', '22071010', 'Álcool etílico não desnaturado, com um teor alcoólico em volume igual ou superior a 80% vol - Com um teor de água igual ou inferior a 1 % vol (álcool etílico anidro combustível)', '1.0'),
(225, '0600101', '22071090', 'Álcool etílico não desnaturado, com um teor alcoólico em volume igual ou superior a 80% vol - Outros (álcool etílico hidratado combustível)', '1.1'),
(226, '0600200', '27101259', 'Gasolina automotiva A, exceto Premium', '2.0'),
(227, '0600201', '27101259', 'Gasolina automotiva C, exceto Premium', '2.1'),
(228, '0600202', '27101259', 'Gasolina automotiva A Premium', '2.2'),
(229, '0600203', '27101259', 'Gasolina automotiva C Premium', '2.3'),
(230, '0600300', '27101251', 'Gasolina de aviação', '3.0'),
(231, '0600400', '27101919', 'Querosenes, exceto de aviação', '4.0'),
(232, '0600500', '27101911', 'Querosene de aviação', '5.0'),
(233, '0600600', '2710192', 'Óleo diesel A, exceto S10 e Marítimo', '6.0'),
(234, '0600601', '2710192', 'Óleo diesel B, exceto S10 (mistura obrigatória)', '6.1'),
(235, '0600602', '2710192', 'Óleo diesel B, exceto S10 (misturas autorizativas)', '6.2'),
(236, '0600603', '2710192', 'Óleo diesel B, exceto S10 (misturas experimentais)', '6.3'),
(237, '0600604', '2710192', 'Óleo diesel A S10', '6.4'),
(238, '0600605', '2710192', 'Óleo diesel B S10 (mistura obrigatória)', '6.5'),
(239, '0600606', '2710192', 'Óleo diesel B S10 (misturas autorizativas)', '6.6'),
(240, '0600607', '2710192', 'Óleo diesel B S10 (misturas experimentais)', '6.7'),
(241, '0600608', '2710192', 'Óleo Diesel Marítimo', '6.8'),
(242, '0600609', '2710192', 'Outros óleos combustíveis, exceto os classificados no CEST 06.006.10 e 06.006.11', '6.9'),
(243, '0600610', '2710192', 'Óleo combustível derivado de xisto', '6.10'),
(244, '0600611', '27101922', 'Óleo combustível pesado', '6.11'),
(245, '0600700', '2710193', 'Óleos lubrificantes', '7.0'),
(246, '0600800', '2710199', 'Outros óleos de petróleo ou de minerais betuminosos (exceto óleos brutos) e preparações não especificadas nem compreendidas noutras posições, que contenham, como constituintes básicos, 70% ou mais, em peso, de óleos de petróleo ou de minerais betuminosos, exceto os que contenham biodiesel, exceto os resíduos de óleos e exceto as graxas lubrificantes', '8.0'),
(247, '0600801', '2710199', 'Graxa lubrificante', '8.1'),
(248, '0600900', '27109', 'Resíduos de óleos', '9.0'),
(249, '0601000', '2711', 'Gás de petróleo e outros hidrocarbonetos gasosos, exceto GLP, GLGN, Gás Natural e Gás de xisto.', '10.0'),
(250, '0601100', '27111910', 'Gás liquefeito de petróleo em botijão de 13 Kg (GLP)', '11.0'),
(251, '0601101', '27111910', 'Gás liquefeito de petróleo (GLP), exceto em botijão de 13 Kg', '11.1'),
(252, '0601102', '27111910', 'Gás liquefeito de petróleo em botijão de 13 Kg (GLGNn)', '11.2'),
(253, '0601103', '27111910', 'Gás liquefeito de petróleo (GLGNn), exceto em botijão de 13 Kg', '11.3'),
(254, '0601104', '27111910', 'Gás liquefeito de petróleo em botijão de 13 Kg (GLGNi)', '11.4'),
(255, '0601105', '27111910', 'Gás liquefeito de petróleo (GLGNi), exceto em botijão de 13 Kg', '11.5'),
(256, '0601106', '27111910', 'Gás liquefeito de petróleo em botijão de 13 kg (Misturas)', '11.6'),
(257, '0601107', '27111910', 'Gás liquefeito de petróleo (Misturas), exceto em botijão de 13 Kg', '11.7'),
(258, '0601200', '27111100', 'Gás Natural Liquefeito', '12.0'),
(259, '0601300', '27112100', 'Gás Natural Gasoso', '13.0'),
(260, '0601400', '27112990', 'Gás de xisto', '14.0'),
(261, '0601500', '2713', 'Coque de petróleo e outros resíduos de óleo de petróleo ou de minerais betuminosos', '15.0'),
(262, '0601600', '38260000', 'Biodiesel e suas misturas, que não contenham ou que contenham menos de 70%, em peso, de óleos de petróleo ou de óleos minerais betuminosos', '16.0'),
(263, '0601700', '3403', 'Preparações lubrificantes, exceto as contendo, como constituintes de base, 70% ou mais, em peso, de óleos de petróleo ou de minerais betuminosos', '17.0'),
(264, '0601800', '27102000', 'Óleos de petróleo ou de minerais betuminosos (exceto óleos brutos) e preparações não especificadas nem compreendidas noutras posições, que contenham, como constituintes básicos, 70% ou mais, em peso, de óleos de petróleo ou de minerais betuminosos, que contenham biodiesel, exceto os resíduos de óleos', '18.0'),
(265, '0700100', '27160000', 'Energia elétrica', '1.0'),
(266, '0800100', '40169990', 'Ferramentas de borracha vulcanizada não endurecida', '1.0'),
(267, '0800200', '44170010', 'Ferramentas, armações e cabos de ferramentas, de madeira', '2.0'),
(268, '0800200', '44170090', 'Ferramentas, armações e cabos de ferramentas, de madeira', '2.0'),
(269, '0800300', '6804', 'Mós e artefatos semelhantes, sem armação, para moer, desfibrar, triturar, amolar, polir, retificar ou cortar; pedras para amolar ou para polir, manualmente, e suas partes, de pedras naturais, de abrasivos naturais ou artificiais aglomerados ou de cerâmica, mesmo com partes de outras matérias', '3.0'),
(270, '0800400', '8201', 'Pás, alviões, picaretas, enxadas, sachos, forcados e forquilhas, ancinhos e raspadeiras; machados, podões e ferramentas semelhantes com gume; tesouras de podar de todos os tipos; foices e foicinhas, facas para feno ou para palha, tesouras para sebes, cunhas e outras ferramentas manuais para agricultura, horticultura ou silvicultura', '4.0'),
(271, '0800500', '82022000', 'Folhas de serras de fita', '5.0'),
(272, '0800600', '82029100', 'Lâminas de serras máquinas', '6.0'),
(273, '0800700', '8202', 'Serras manuais e outras folhas de serras (incluídas as fresas-serras e as folhas não dentadas para serrar), exceto as classificadas nos CEST 08.005.00 e 08.006.00', '7.0'),
(274, '0800800', '8203', 'Limas, grosas, alicates (mesmo cortantes), tenazes, pinças, cisalhas para metais, corta-tubos, corta-pinos, saca-bocados e ferramentas semelhantes, manuais, exceto as pinças para sobrancelhas classificadas na posição 8203.20.90', '8.0'),
(275, '0800900', '8204', 'Chaves de porcas, manuais (incluídas as chaves dinamométricas); chaves de caixa intercambiáveis, mesmo com cabos', '9.0'),
(276, '0801000', '8205', 'Ferramentas manuais (incluídos os diamantes de vidraceiro) não especificadas nem compreendidas em outras posições, lamparinas ou lâmpadas de soldar (maçaricos) e semelhantes; tornos de apertar, sargentos e semelhantes, exceto os acessórios ou partes de máquinas-ferramentas; bigornas; forjas-portáteis; mós com armação, manuais ou de pedal', '10.0'),
(277, '0801100', '82060000', 'Ferramentas de pelo menos duas das posições 8202 a 8205, acondicionadas em sortidos para venda a retalho', '11.0'),
(278, '0801200', '820740', 'Ferramentas de roscar interior ou exteriormente; de mandrilar ou de brochar; e de fresar', '12.0'),
(279, '0801200', '820760', 'Ferramentas de roscar interior ou exteriormente; de mandrilar ou de brochar; e de fresar', '12.0'),
(280, '0801200', '820770', 'Ferramentas de roscar interior ou exteriormente; de mandrilar ou de brochar; e de fresar', '12.0'),
(281, '0801300', '8207', 'Outras ferramentas intercambiáveis para ferramentas manuais, mesmo mecânicas, ou para máquinas-ferramentas (por exemplo, de embutir, estampar, puncionar, furar, tornear, aparafusar), incluídas as fieiras de estiragem ou de extrusão, para metais, e as ferramentas de perfuração ou de sondagem, exceto forma ou gabarito de produtos em epoxy e as classificadas no CEST 08.012.00', '13.0'),
(282, '0801400', '8208', 'Facas e lâminas cortantes, para máquinas ou para aparelhos mecânicos', '14.0'),
(283, '0801500', '82090011', 'Plaquetas ou pastilhas intercambiáveis', '15.0'),
(284, '0801600', '820900', 'Outras plaquetas, varetas, pontas e objetos semelhantes para ferramentas, não montados, de ceramais (“cermets”), exceto as classificadas no CEST 08.015.00', '16.0'),
(285, '0801700', '8211', 'Facas de lâmina cortante ou serrilhada, incluídas as podadeiras de lâmina móvel, e suas lâminas, exceto as de uso doméstico', '17.0'),
(286, '0801800', '8213', 'Tesouras e suas lâminas', '18.0'),
(287, '0801900', '8467', 'Ferramentas pneumáticas, hidráulicas ou com motor (elétrico ou não elétrico) incorporado, de uso manual, exceto o descrito no CEST 08.019.01', '19.0'),
(288, '0801901', '84678100', 'Moto-serras portáteis de corrente, com motor incorporado, não elétrico, de uso agrícola', '19.1'),
(289, '0802000', '9015', 'nstrumentos e aparelhos de geodesia, topografia, agrimensura, nivelamento, fotogrametria, hidrografia, oceanografia, hidrologia, meteorologia ou de geofísica, exceto bussolas; telêmetros', '20.0'),
(290, '0802100', '90172000', 'Instrumentos de desenho, de traçado ou de cálculo; metros, micrômetros, paquímetros, calibres e semelhantes; partes e acessórios', '21.0'),
(291, '0802100', '901730', 'Instrumentos de desenho, de traçado ou de cálculo; metros, micrômetros, paquímetros, calibres e semelhantes; partes e acessórios', '21.0'),
(292, '0802100', '901780', 'Instrumentos de desenho, de traçado ou de cálculo; metros, micrômetros, paquímetros, calibres e semelhantes; partes e acessórios', '21.0'),
(293, '0802100', '90179090', 'Instrumentos de desenho, de traçado ou de cálculo; metros, micrômetros, paquímetros, calibres e semelhantes; partes e acessórios', '21.0'),
(294, '0802200', '90251190', 'Termômetros, suas partes e acessórios', '22.0'),
(295, '0802200', '90259010', 'Termômetros, suas partes e acessórios', '22.0'),
(296, '0802300', '902519', 'Pirômetros, suas partes e acessórios', '23.0'),
(297, '0802300', '90259090', 'Pirômetros, suas partes e acessórios', '23.0'),
(298, '0900100', '8539', 'Lâmpadas elétricas', '1.0'),
(299, '0900200', '8540', 'Lâmpadas eletrônicas', '2.0'),
(300, '0900300', '85041000', 'Reatores para lâmpadas ou tubos de descargas', '3.0'),
(301, '0900400', '853650', '“Starter”', '4.0'),
(302, '0900500', '85395000', 'Lâmpadas de LED (Diodos Emissores de Luz)', '5.0'),
(303, '1000100', '2522', 'Cal', '1.0'),
(304, '1000200', '3816001', 'Argamassas', '2.0'),
(305, '1000200', '38245000', 'Argamassas', '2.0'),
(306, '1000300', '32149000', 'Outras argamassas', '3.0'),
(307, '1000400', '391000', 'Silicones em formas primárias, para uso na construção', '4.0'),
(308, '1000500', '3916', 'Revestimentos de PVC e outros plásticos; forro, sancas e afins de PVC, para uso na construção', '5.0'),
(309, '1000600', '3917', 'Tubos, e seus acessórios (por exemplo, juntas, cotovelos, flanges, uniões), de plásticos, para uso na construção', '6.0'),
(310, '1000700', '3918', 'Revestimento de pavimento de PVC e outros plásticos', '7.0'),
(311, '1000800', '3919', 'Chapas, folhas, tiras, fitas, películas e outras formas planas, autoadesivas, de plásticos, mesmo em rolos, para uso na construção', '8.0'),
(312, '1000900', '3919', 'Veda rosca, lona plástica para uso na construção, fitas isolantes e afins', '9.0'),
(313, '1000900', '3920', 'Veda rosca, lona plástica para uso na construção, fitas isolantes e afins', '9.0'),
(314, '1000900', '3921', 'Veda rosca, lona plástica para uso na construção, fitas isolantes e afins', '9.0'),
(315, '1001000', '3921', 'Telha de plástico, mesmo reforçada com fibra de vidro', '10.0'),
(316, '1001100', '3921', 'Cumeeira de plástico, mesmo reforçada com fibra de vidro', '11.0'),
(317, '1001200', '3921', 'Chapas, laminados plásticos em bobina, para uso na construção, exceto os descritos no CEST 10.010.00 e 10.011.00', '12.0'),
(318, '1001300', '3922', 'Banheiras, boxes para chuveiros, pias, lavatórios, bidês, sanitários e seus assentos e tampas, caixas de descarga e artigos semelhantes para usos sanitários ou higiênicos, de plásticos', '13.0'),
(319, '1001400', '3924', 'Artefatos de higiene/toucador de plástico, para uso na construção', '14.0'),
(320, '1001500', '39251000', 'Caixa d’água, inclusive sua tampa, de plástico, mesmo reforçadas com fibra de vidro', '15.0'),
(321, '1001600', '392590', 'Outras telhas, cumeeira e caixa d’água, inclusive sua tampa, de plástico, mesmo reforçadas com fibra de vidro', '16.0'),
(322, '1001700', '39251000', 'Artefatos para apetrechamento de construções, de plásticos, não especificados nem compreendidos em outras posições, incluindo persianas, sancas, molduras, apliques e rosetas, caixilhos de polietileno e outros plásticos, exceto os descritos nos CEST 10.015.00 e 10.016.00', '17.0'),
(323, '1001700', '392590', 'Artefatos para apetrechamento de construções, de plásticos, não especificados nem compreendidos em outras posições, incluindo persianas, sancas, molduras, apliques e rosetas, caixilhos de polietileno e outros plásticos, exceto os descritos nos CEST 10.015.00 e 10.016.00', '17.0'),
(324, '1001800', '39252000', 'Portas, janelas e seus caixilhos, alizares e soleiras', '18.0'),
(325, '1001900', '39253000', 'Postigos, estores (incluídas as venezianas) e artefatos semelhantes e suas partes', '19.0'),
(326, '1002000', '392690', 'Outras obras de plástico, para uso na construção', '20.0'),
(327, '1002100', '4814', 'Papel de parede e revestimentos de parede semelhantes; papel para vitrais', '21.0'),
(328, '1002200', '68101900', 'Telhas de concreto', '22.0'),
(329, '1002300', '6811', 'Telha, cumeeira e caixa d’água, inclusive sua tampa, de fibrocimento, cimento-celulose', '23.0'),
(330, '1002400', '6811', 'Caixas d’água, tanques e reservatórios e suas tampas, telhas, calhas, cumeeiras e afins, de fibrocimento, cimento-celulose ou semelhantes, contendo ou não amianto, exceto os descritos no CEST 10.023.00', '24.0'),
(331, '1002500', '69010000', 'Tijolos, placas (lajes), ladrilhos e outras peças cerâmicas de farinhas siliciosas fósseis (“kieselghur”, tripolita, diatomita, por exemplo) ou de terras siliciosas semelhantes', '25.0'),
(332, '1002600', '6902', 'Tijolos, placas (lajes), ladrilhos e peças cerâmicas semelhantes, para uso na construção, refratários, que não sejam de farinhas siliciosas fósseis nem de terras siliciosas semelhantes', '26.0'),
(333, '1002700', '6904', 'Tijolos para construção, tijoleiras, tapa-vigas e produtos semelhantes, de cerâmica', '27.0'),
(334, '1002800', '6905', 'Telhas, elementos de chaminés, condutores de fumaça, ornamentos arquitetônicos, de cerâmica, e outros produtos cerâmicos para uso na construção', '28.0'),
(335, '1002900', '69060000', 'Tubos, calhas ou algerozes e acessórios para canalizações, de cerâmica', '29.0'),
(336, '1003000', '6907', 'Ladrilhos e placas de cerâmica, exclusivamente para pavimentação ou revestimento', '30.0'),
(337, '1003001', '6907', 'Cubos, pastilhas e artigos semelhantes de cerâmica, mesmo com suporte, exceto os descritos CEST 10.030.00', '30.1'),
(338, '1003100', '6910', 'Pias, lavatórios, colunas para lavatórios, banheiras, bidês, sanitários, caixas de descarga, mictórios e aparelhos fixos semelhantes para usos sanitários, de cerâmica', '31.0'),
(339, '1003200', '69120000', 'Artefatos de higiene/toucador de cerâmica', '32.0'),
(340, '1003300', '7003', 'Vidro vazado ou laminado, em chapas, folhas ou perfis, mesmo com camada absorvente, refletora ou não, mas sem qualquer outro trabalho', '33.0'),
(341, '1003400', '7004', 'Vidro estirado ou soprado, em folhas, mesmo com camada absorvente, refletora ou não, mas sem qualquer outro trabalho', '34.0'),
(342, '1003500', '7005', 'Vidro flotado e vidro desbastado ou polido em uma ou em ambas as faces, em chapas ou em folhas, mesmo com camada absorvente, refletora ou não, mas sem qualquer outro trabalho', '35.0'),
(343, '1003600', '70071900', 'Vidros temperados', '36.0'),
(344, '1003700', '70072900', 'Vidros laminados', '37.0'),
(345, '1003800', '7008', 'Vidros isolantes de paredes múltiplas', '38.0'),
(346, '1003900', '7016', 'Blocos, placas, tijolos, ladrilhos, telhas e outros artefatos, de vidro prensado ou moldado, mesmo armado, para uso na construção; cubos, pastilhas e outros artigos semelhantes', '39.0'),
(347, '1004000', '72142000', 'Barras próprias para construções, exceto vergalhões', '40.0'),
(348, '1004100', '73089010', 'Outras barras próprias para construções, exceto vergalhões', '41.0'),
(349, '1004200', '72142000', 'Vergalhões', '42.0'),
(350, '1004300', '7213', 'Outros vergalhões', '43.0'),
(351, '1004300', '73089010', 'Outros vergalhões', '43.0'),
(352, '1004400', '72171090', 'Fios de ferro ou aço não ligados, não revestidos, mesmo polidos; cordas, cabos, tranças (entrançados), lingas e artefatos semelhantes, de ferro ou aço, não isolados para usos elétricos', '44.0'),
(353, '1004400', '7312', 'Fios de ferro ou aço não ligados, não revestidos, mesmo polidos; cordas, cabos, tranças (entrançados), lingas e artefatos semelhantes, de ferro ou aço, não isolados para usos elétricos', '44.0'),
(354, '1004500', '72172010', 'Outros fios de ferro ou aço, não ligados, galvanizados com teor de carbono superior ou igual a 0,6%, em peso', '45.0'),
(355, '1004501', '72172090', 'Outros fios de ferro ou aço, não ligados, galvanizados', '45.1'),
(356, '1004600', '7307', 'Acessórios para tubos (inclusive uniões, cotovelos, luvas ou mangas), de ferro fundido, ferro ou aço', '46.0'),
(357, '1004700', '73083000', 'Portas e janelas, e seus caixilhos, alizares e soleiras de ferro fundido, ferro ou aço', '47.0'),
(358, '1004800', '73084000', 'Material para andaimes, para armações (cofragens) e para escoramentos, (inclusive armações prontas, para estruturas de concreto armado ou argamassa armada), eletrocalhas e perfilados de ferro fundido, ferro ou aço, próprios para construção, exceto treliças de aço', '48.0'),
(359, '1004800', '730890', 'Material para andaimes, para armações (cofragens) e para escoramentos, (inclusive armações prontas, para estruturas de concreto armado ou argamassa armada), eletrocalhas e perfilados de ferro fundido, ferro ou aço, próprios para construção, exceto treliças de aço', '48.0'),
(360, '1004900', '73084000', 'Treliças de aço', '49.0'),
(361, '1005000', '73089090', 'Telhas metálicas', '50.0'),
(362, '1005100', '7310', 'Caixas diversas (tais como caixa de correio, de entrada de água, de energia, de instalação) de ferro fundido, ferro ou aço; próprias para a construção', '51.0'),
(363, '1005200', '73130000', 'Arame farpado, de ferro ou aço, arames ou tiras, retorcidos, mesmo farpados, de ferro ou aço, dos tipos utilizados em cercas', '52.0'),
(364, '1005300', '7314', 'Telas metálicas, grades e redes, de fios de ferro ou aço', '53.0'),
(365, '1005400', '73151100', 'Correntes de rolos, de ferro fundido, ferro ou aço', '54.0'),
(366, '1005500', '73151290', 'Outras correntes de elos articulados, de ferro fundido, ferro ou aço', '55.0'),
(367, '1005600', '73158200', 'Correntes de elos soldados, de ferro fundido, de ferro ou aço', '56.0'),
(368, '1005700', '731700', 'Tachas, pregos, percevejos, escápulas, grampos ondulados ou biselados e artefatos semelhantes, de ferro fundido, ferro ou aço, mesmo com a cabeça de outra matéria, exceto cobre', '57.0'),
(369, '1005800', '7318', 'Parafusos, pinos ou pernos, roscados, porcas, tira-fundos, ganchos roscados, rebites, chavetas, cavilhas, contrapinos, arruelas (incluídas as de pressão) e artefatos semelhantes, de ferro fundido, ferro ou aço', '58.0'),
(370, '1005900', '7323', 'Palha de ferro ou aço, exceto os de uso doméstico classificados na posição NCM 7323.10.00', '59.0'),
(371, '1005901', '7323', 'Esponjas, esfregões, luvas e artefatos semelhantes para limpeza, polimento e usos semelhantes, de ferro ou aço, exceto os de uso doméstico classificados na posição NCM 7323.10.00', '59.1'),
(372, '1006000', '7324', 'Artefatos de higiene ou de toucador, e suas partes, de ferro fundido, ferro ou aço, incluídas as pias, banheiras, lavatórios, cubas, mictórios, tanques e afins de ferro fundido, ferro ou aço, para uso na construção', '60.0'),
(373, '1006100', '7325', 'Outras obras moldadas, de ferro fundido, ferro ou aço, para uso na construção', '61.0'),
(374, '1006200', '7326', 'Abraçadeiras', '62.0'),
(375, '1006300', '7407', 'Barras de cobre', '63.0'),
(376, '1006400', '74111010', 'Tubos de cobre e suas ligas, para instalações de água quente e gás, para uso na construção', '64.0'),
(377, '1006500', '7412', 'Acessórios para tubos (por exemplo, uniões, cotovelos, luvas ou mangas) de cobre e suas ligas, para uso na construção', '65.0'),
(378, '1006600', '7415', 'Tachas, pregos, percevejos, escápulas e artefatos semelhantes, de cobre, ou de ferro ou aço com cabeça de cobre, parafusos, pinos ou pernos, roscados, porcas, ganchos roscados, rebites, chavetas, cavilhas, contrapinos, arruelas (incluídas as de pressão), e artefatos semelhantes, de cobre', '66.0'),
(379, '1006700', '74182000', 'Artefatos de higiene/toucador de cobre, para uso na construção', '67.0'),
(380, '1006800', '76071990', 'Manta de subcobertura aluminizada', '68.0'),
(381, '1006900', '7608', 'Tubos de alumínio e suas ligas, para refrigeração e ar condicionado, para uso na construção', '69.0'),
(382, '1007000', '76090000', 'Acessórios para tubos (por exemplo, uniões, cotovelos, luvas ou mangas), de alumínio, para uso na construção', '70.0'),
(383, '1007100', '7610', 'Construções e suas partes (por exemplo, pontes e elementos de pontes, torres, pórticos ou pilones, pilares, colunas, armações, estruturas para telhados, portas e janelas, e seus caixilhos, alizares e soleiras, balaustradas), de alumínio, exceto as construções pré-fabricadas da posição 9406; chapas, barras, perfis, tubos e semelhantes, de alumínio, próprios para construções', '71.0'),
(384, '1007200', '76152000', 'Artefatos de higiene/toucador de alumínio, para uso na construção', '72.0'),
(385, '1007300', '7616', 'Outras obras de alumínio, próprias para construções, incluídas as persianas', '73.0'),
(386, '1007400', '83024100', 'Outras guarnições, ferragens e artigos semelhantes de metais comuns, para construções, inclusive puxadores.', '74.0'),
(387, '1007500', '8301', 'Fechaduras e ferrolhos (de chave, de segredo ou elétricos), de metais comuns, incluídas as suas partes fechos e armações com fecho, com fechadura, de metais comuns chaves para estes artigos, de metais comuns; exceto os de uso automotivo', '75.0'),
(388, '1007600', '83021000', 'Dobradiças de metais comuns, de qualquer tipo', '76.0'),
(389, '1007700', '8307', 'Tubos flexíveis de metais comuns, mesmo com acessórios, para uso na construção', '77.0'),
(390, '1007800', '8311', 'Fios, varetas, tubos, chapas, eletrodos e artefatos semelhantes, de metais comuns ou de carbonetos metálicos, revestidos exterior ou interiormente de decapantes ou de fundentes, para soldagem (soldadura) ou depósito de metal ou de carbonetos metálicos fios e varetas de pós de metais comuns aglomerados, para metalização por projeção', '78.0'),
(391, '1007900', '8481', 'Torneiras, válvulas (incluídas as redutoras de pressão e as termostáticas) e dispositivos semelhantes, para canalizações, caldeiras, reservatórios, cubas e outros recipientes', '79.0'),
(392, '1008000', '7009', 'Espelhos de vidro, mesmo emoldurados, exceto os de uso automotivo', '80.0'),
(393, '1100100', '28289011', 'Água sanitária, branqueador e outros alvejantes', '1.0'),
(394, '1100100', '28289019', 'Água sanitária, branqueador e outros alvejantes', '1.0'),
(395, '1100100', '32064100', 'Água sanitária, branqueador e outros alvejantes', '1.0'),
(396, '1100100', '34022000', 'Água sanitária, branqueador e outros alvejantes', '1.0'),
(397, '1100100', '38089419', 'Água sanitária, branqueador e outros alvejantes', '1.0'),
(398, '1100200', '34012090', 'Sabões em pó, flocos, palhetas, grânulos ou outras formas semelhantes, para lavar roupas', '2.0'),
(399, '1100300', '34012090', 'Sabões líquidos para lavar roupas', '3.0'),
(400, '1100400', '34022000', 'Detergentes em pó, flocos, palhetas, grânulos ou outras formas semelhantes', '4.0'),
(401, '1100500', '34022000', 'Detergentes líquidos, exceto para lavar roupa', '5.0'),
(402, '1100600', '34022000', 'Detergente líquido para lavar roupa', '6.0'),
(403, '1100700', '3402', 'Outros agentes orgânicos de superfície (exceto sabões); preparações tensoativas, preparações para lavagem (incluídas as preparações auxiliares para lavagem) e preparações para limpeza (inclusive multiuso e limpadores), mesmo contendo sabão, exceto os produtos descritos nos CEST 11.001.00, 11.004.00, 11.005.00 e 11.006.00; em embalagem de conteúdo inferior ou igual a 50 litros ou 50 kg', '7.0'),
(404, '1100800', '38099190', 'Amaciante/suavizante', '8.0'),
(405, '1100900', '39241000', 'Esponjas para limpeza', '9.0'),
(406, '1100900', '39249000', 'Esponjas para limpeza', '9.0'),
(407, '1100900', '68053010', 'Esponjas para limpeza', '9.0'),
(408, '1100900', '68053090', 'Esponjas para limpeza', '9.0'),
(409, '1101000', '2207', 'Álcool etílico para limpeza', '10.0'),
(410, '1101000', '22089000', 'Álcool etílico para limpeza', '10.0'),
(411, '1101100', '73231000', 'Esponjas e palhas de aço; esponjas para limpeza, polimento ou uso semelhantes; todas de uso doméstico', '11.0'),
(412, '1101200', '39232', 'Sacos de lixo de conteúdo igual ou inferior a 100 litros', '12.0'),
(413, '1200100', '8504', 'Transformadores, bobinas de reatância e de auto indução, inclusive os transformadores de potência superior a 16 KVA, classificados nas posições 8504.33.00 e 8504.34.00; exceto os demais transformadores da subposição 8504.3, os reatores para lâmpadas elétricas de descarga classificados no código 8504.10.00, os carregadores de acumuladores do código 8504.40.10, os equipamentos de alimentação ininterrupta de energia (UPS ou “no break”), no código 8504.40.40 e os de uso automotivo', '1.0'),
(414, '1200200', '8516', 'Aquecedores elétricos de água, incluídos os de imersão, chuveiros ou duchas elétricos, torneiras elétricas, resistências de aquecimento, inclusive as de duchas e chuveiros elétricos e suas partes; exceto outros fornos, fogareiros (incluídas as chapas de cocção), grelhas e assadeiras, classificados na posição 8516.60.00', '2.0'),
(415, '1200300', '8535', 'Aparelhos para interrupção, seccionamento, proteção, derivação, ligação ou conexão de circuitos elétricos (por exemplo, interruptores, comutadores, corta-circuitos, para-raios, limitadores de tensão, eliminadores de onda, tomadas de corrente e outros conectores, caixas de junção), para tensão superior a 1.000V, exceto os de uso automotivo', '3.0'),
(416, '1200400', '8536', 'Aparelhos para interrupção, seccionamento, proteção, derivação, ligação ou conexão de circuitos elétricos (por exemplo, interruptores, comutadores, relés, corta-circuitos, eliminadores de onda, plugues e tomadas de corrente, suportes para lâmpadas e outros conectores, caixas de junção), para uma tensão não superior a 1.000V; conectores para fibras ópticas, feixes ou cabos de fibras ópticas; exceto “starter” classificado na subposição 8536.50 e os de uso automotivo', '4.0'),
(417, '1200500', '8538', 'Partes reconhecíveis como exclusiva ou principalmente destinadas aos aparelhos das posições 8535 e 8536', '5.0'),
(418, '1200600', '74130000', 'Cabos, tranças e semelhantes, de cobre, não isolados para usos elétricos, exceto os de uso automotivo', '6.0'),
(419, '1200700', '7605', 'Fios, cabos (incluídos os cabos coaxiais) e outros condutores, isolados ou não, para usos elétricos (incluídos os de cobre ou alumínio, envernizados ou oxidados anodicamente), mesmo com peças de conexão, inclusive fios e cabos elétricos, para tensão não superior a 1000V, para uso na construção; fios e cabos telefônicos e para transmissão de dados; cabos de fibras ópticas, constituídos de fibras embainhadas individualmente, mesmo com condutores elétricos ou munidos de peças de conexão; cordas, cabos, tranças e semelhantes, de alumínio, não isolados para uso elétricos; exceto os de uso automotivo', '7.0'),
(420, '1200700', '7614', 'Fios, cabos (incluídos os cabos coaxiais) e outros condutores, isolados ou não, para usos elétricos (incluídos os de cobre ou alumínio, envernizados ou oxidados anodicamente), mesmo com peças de conexão, inclusive fios e cabos elétricos, para tensão não superior a 1000V, para uso na construção; fios e cabos telefônicos e para transmissão de dados; cabos de fibras ópticas, constituídos de fibras embainhadas individualmente, mesmo com condutores elétricos ou munidos de peças de conexão; cordas, cabos, tranças e semelhantes, de alumínio, não isolados para uso elétricos; exceto os de uso automotivo', '7.0'),
(421, '1200700', '8544', 'Fios, cabos (incluídos os cabos coaxiais) e outros condutores, isolados ou não, para usos elétricos (incluídos os de cobre ou alumínio, envernizados ou oxidados anodicamente), mesmo com peças de conexão, inclusive fios e cabos elétricos, para tensão não superior a 1000V, para uso na construção; fios e cabos telefônicos e para transmissão de dados; cabos de fibras ópticas, constituídos de fibras embainhadas individualmente, mesmo com condutores elétricos ou munidos de peças de conexão; cordas, cabos, tranças e semelhantes, de alumínio, não isolados para uso elétricos; exceto os de uso automotivo', '7.0'),
(422, '1200800', '8546', 'Isoladores de qualquer matéria, para usos elétricos', '8.0'),
(423, '1200900', '8547', 'Peças isolantes inteiramente de matérias isolantes, ou com simples peças metálicas de montagem (suportes roscados, por exemplo) incorporadas na massa, para máquinas, aparelhos e instalações elétricas; tubos isoladores e suas peças de ligação, de metais comuns, isolados interiormente', '9.0'),
(424, '1300100', '3003', 'Medicamentos de referência - positiva, exceto para uso veterinário', '1.0'),
(425, '1300100', '3004', 'Medicamentos de referência - positiva, exceto para uso veterinário', '1.0'),
(426, '1300101', '3003', 'Medicamentos de referência - negativa, exceto para uso veterinário', '1.1'),
(427, '1300101', '3004', 'Medicamentos de referência - negativa, exceto para uso veterinário', '1.1'),
(428, '1300102', '3003', 'Medicamentos de referência - neutra, exceto para uso veterinário', '1.2'),
(429, '1300102', '3004', 'Medicamentos de referência - neutra, exceto para uso veterinário', '1.2'),
(430, '1300200', '3003', 'Medicamentos genérico - positiva, exceto para uso veterinário', '2.0'),
(431, '1300200', '3004', 'Medicamentos genérico - positiva, exceto para uso veterinário', '2.0'),
(432, '1300201', '3003', 'Medicamentos genérico - negativa, exceto para uso veterinário', '2.1'),
(433, '1300201', '3004', 'Medicamentos genérico - negativa, exceto para uso veterinário', '2.1'),
(434, '1300202', '3003', 'Medicamentos genérico - neutra, exceto para uso veterinário', '2.2'),
(435, '1300202', '3004', 'Medicamentos genérico - neutra, exceto para uso veterinário', '2.2'),
(436, '1300300', '3003', 'Medicamentos similar - positiva, exceto para uso veterinário', '3.0'),
(437, '1300300', '3004', 'Medicamentos similar - positiva, exceto para uso veterinário', '3.0'),
(438, '1300301', '3003', 'Medicamentos similar - negativa, exceto para uso veterinário', '3.1'),
(439, '1300301', '3004', 'Medicamentos similar - negativa, exceto para uso veterinário', '3.1'),
(440, '1300302', '3003', 'Medicamentos similar - neutra, exceto para uso veterinário', '3.2'),
(441, '1300302', '3004', 'Medicamentos similar - neutra, exceto para uso veterinário', '3.2'),
(442, '1300400', '3003', 'Outros tipos de medicamentos - positiva, exceto para uso veterinário', '4.0'),
(443, '1300400', '3004', 'Outros tipos de medicamentos - positiva, exceto para uso veterinário', '4.0'),
(444, '1300401', '3003', 'Outros tipos de medicamentos - negativa, exceto para uso veterinário', '4.1'),
(445, '1300401', '3004', 'Outros tipos de medicamentos - negativa, exceto para uso veterinário', '4.1'),
(446, '1300402', '3003', 'Outros tipos de medicamentos - neutra, exceto para uso veterinário', '4.2'),
(447, '1300402', '3004', 'Outros tipos de medicamentos - neutra, exceto para uso veterinário', '4.2'),
(448, '1300500', '30066000', 'Preparações químicas contraceptivas à base de hormônios, de outros produtos da posição 29.37 ou de espermicidas - positiva', '5.0'),
(449, '1300501', '30066000', 'Preparações químicas contraceptivas à base de hormônios, de outros produtos da posição 29.37 ou de espermicidas - negativa', '5.1'),
(450, '1300600', '2936', 'Provitaminas e vitaminas, naturais ou reproduzidas por síntese (incluídos os concentrados naturais), bem como os seus derivados utilizados principalmente como vitaminas, misturados ou não entre si, mesmo em quaisquer soluções - neutra', '6.0'),
(451, '1300700', '300630', 'Preparações opacificantes (contrastantes) para exames radiográficos e reagentes de diagnóstico concebidos para serem administrados ao paciente - positiva', '7.0'),
(452, '1300701', '300630', 'Preparações opacificantes (contrastantes) para exames radiográficos e reagentes de diagnóstico concebidos para serem administrados ao paciente - negativa', '7.1'),
(453, '1300800', '3002', 'Antissoro, outras frações do sangue, produtos imunológicos modificados, mesmo obtidos por via biotecnológica, exceto para uso veterinário - positiva', '8.0'),
(454, '1300801', '3002', 'Antissoro, outras frações do sangue, produtos imunológicos modificados, mesmo obtidos por via biotecnológica, exceto para uso veterinário - negativa', '8.1'),
(455, '1300900', '3002', 'Vacinas e produtos semelhantes, exceto para uso veterinário - positiva;', '9.0'),
(456, '1300901', '3002', 'Vacinas e produtos semelhantes, exceto para uso veterinário - negativa;', '9.1'),
(457, '1301000', '30051010', 'Curativos (pensos) adesivos e outros artigos com uma camada adesiva, impregnados ou recobertos de substâncias farmacêuticas - Lista Positiva', '10.0'),
(458, '1301001', '30051010', 'Curativos (pensos) adesivos e outros artigos com uma camada adesiva, impregnados ou recobertos de substâncias farmacêuticas - Lista Negativa', '10.1'),
(459, '1301100', '3005', 'Algodão, atadura, esparadrapo, gazes, pensos, sinapismos, e outros, acondicionados para venda a retalho para usos medicinais, cirúrgicos ou dentários, não impregnados ou recobertos de substâncias farmacêuticas - Lista Neutra', '11.0'),
(460, '1301200', '40151100', 'Luvas cirúrgicas e luvas de procedimento - neutra', '12.0'),
(461, '1301200', '40151900', 'Luvas cirúrgicas e luvas de procedimento - neutra', '12.0'),
(462, '1301300', '40141000', 'Preservativo – neutra', '13.0'),
(463, '1301400', '901831', 'Seringas, mesmo com agulhas - neutra', '14.0'),
(464, '1301500', '9018321', 'Agulhas para seringas - neutra', '15.0'),
(465, '1301600', '39269090', 'Contraceptivos (dispositivos intrauterinos - DIU) - neutra', '16.0'),
(466, '1301600', '90189099', 'Contraceptivos (dispositivos intrauterinos - DIU) - neutra', '16.0'),
(467, '1400100', '7013', 'Objetos de vidro para serviço de mesa ou de cozinha', '1.0'),
(468, '1400200', '70133700', 'Outros copos, exceto de vitrocerâmica', '2.0'),
(469, '1400300', '70134290', 'Objetos para serviço de mesa (exceto copos) ou de cozinha, exceto de vitrocerâmica', '3.0'),
(470, '1400400', '3919', 'Lonas plásticas, exceto as para uso na construção', '4.0'),
(471, '1400400', '3920', 'Lonas plásticas, exceto as para uso na construção', '4.0'),
(472, '1400400', '3921', 'Lonas plásticas, exceto as para uso na construção', '4.0'),
(473, '1400500', '3924', 'Artefatos de higiene/toucador de plástico, exceto os para uso na construção', '5.0'),
(474, '1400600', '39241000', 'Serviços de mesa e outros utensílios de mesa ou de cozinha, de plástico, não descartáveis', '6.0'),
(475, '1400601', '39241000', 'Serviços de mesa e outros utensílios de mesa ou de cozinha, de plástico, descartáveis', '6.1'),
(476, '1400700', '69111010', 'Artigos para serviço de mesa ou de cozinha, de porcelana, inclusive os descartáveis – estojos', '7.0'),
(477, '1400800', '69111090', 'Artigos para serviço de mesa ou de cozinha, de porcelana, inclusive os descartáveis – avulsos', '8.0'),
(478, '1400900', '69120000', 'Artigos para serviço de mesa ou de cozinha, de cerâmica', '9.0'),
(479, '1401000', '69120000', 'Velas para filtros', '10.0'),
(480, '1401100', '4823209', 'Filtros descartáveis para coar café ou chá', '11.0'),
(481, '1401200', '48236', 'Bandejas, travessas, pratos, xícaras ou chávenas, taças, copos e artigos semelhantes, de papel ou cartão', '12.0'),
(482, '1401300', '48131000', 'Papel para cigarro', '13.0'),
(483, '1600100', '40111000', 'Pneus novos, dos tipos utilizados em automóveis de passageiros (incluídos os veículos de uso misto - camionetas e os automóveis de corrida)', '1.0'),
(484, '1600200', '4011', 'Pneus novos, dos tipos utilizados em caminhões (inclusive para os fora-de-estrada), ônibus, aviões, máquinas de terraplenagem, de construção e conservação de estradas, máquinas e tratores agrícolas, pá-carregadeira', '2.0'),
(485, '1600300', '40114000', 'Pneus novos para motocicletas', '3.0'),
(486, '1600400', '4011', 'Outros tipos de pneus novos, exceto os itens classificados no CEST 16.005.00', '4.0'),
(487, '1600500', '40115000', 'Pneus novos de borracha dos tipos utilizados em bicicletas', '5.0'),
(488, '1600600', '40121', 'Pneus recauchutados', '6.0'),
(489, '1600700', '401290', 'Protetores de borracha, exceto os itens classificados no CEST 16.007.01', '7.0'),
(490, '1600701', '401290', 'Protetores de borracha para bicicletas', '7.1'),
(491, '1600800', '4013', 'Câmaras de ar de borracha, exceto os itens classificados no CEST 16.009.00', '8.0'),
(492, '1600900', '40132000', 'Câmaras de ar de borracha dos tipos utilizados em bicicletas', '9.0'),
(493, '1700100', '17049010', 'Chocolate branco, em embalagens de conteúdo inferior ou igual a 1 kg, excluídos os ovos de páscoa de chocolate.', '1.0'),
(494, '1700200', '18063110', 'Chocolates contendo cacau, em embalagens de conteúdo inferior ou igual a 1 kg', '2.0'),
(495, '1700200', '18063220', 'Chocolates contendo cacau, em embalagens de conteúdo inferior ou igual a 1 kg', '2.0'),
(496, '1700300', '18063210', 'Chocolate em barras, tabletes ou blocos ou no estado líquido, em pasta, em pó, grânulos ou formas semelhantes, em recipientes ou embalagens imediatas de conteúdo inferior ou igual a 2 kg', '3.0'),
(497, '1700300', '18063220', 'Chocolate em barras, tabletes ou blocos ou no estado líquido, em pasta, em pó, grânulos ou formas semelhantes, em recipientes ou embalagens imediatas de conteúdo inferior ou igual a 2 kg', '3.0'),
(498, '1700400', '18069000', 'Chocolates e outras preparações alimentícias contendo cacau, em embalagens de conteúdo inferior ou igual a 1 kg, excluídos os achocolatados em pó e ovos de páscoa de chocolate.', '4.0'),
(499, '1700500', '17049010', 'Ovos de páscoa de chocolate branco', '5.0'),
(500, '1700501', '18069000', 'Ovos de páscoa de chocolate', '5.1'),
(501, '1700600', '18069000', 'Achocolatados em pó, em embalagens de conteúdo inferior ou igual a 1 kg, exceto os classificados no CEST 17.006.02', '6.0'),
(502, '1700601', '18061000', 'Cacau em pó, com adição de açúcar ou de outros edulcorantes, em embalagens de conteúdo inferior ou igual a 1kg', '6.1'),
(503, '1700602', '18069000', 'Achocolatados em pó, em cápsulas', '6.2'),
(504, '1700700', '18069000', 'Caixas de bombons contendo cacau, em embalagens de conteúdo inferior ou igual a 1 kg', '7.0'),
(505, '1700800', '17049090', 'Bombons, inclusive à base de chocolate branco sem cacau', '8.0'),
(506, '1700900', '18069000', 'Bombons, balas, caramelos, confeitos, pastilhas e outros produtos de confeitaria, contendo cacau', '9.0'),
(507, '1701000', '2009', 'Sucos de frutas ou de produtos hortícolas; mistura de sucos', '10.0'),
(508, '1701100', '20098', 'Água de coco', '11.0'),
(509, '1701200', '04021', 'Leite em pó, blocos ou grânulos, exceto creme de leite', '12.0'),
(510, '1701200', '04022', 'Leite em pó, blocos ou grânulos, exceto creme de leite', '12.0'),
(511, '1701200', '04029', 'Leite em pó, blocos ou grânulos, exceto creme de leite', '12.0'),
(512, '1701300', '19011020', 'Farinha láctea', '13.0'),
(513, '1701400', '19011010', 'Leite modificado para alimentação de crianças', '14.0'),
(514, '1701500', '19011090', 'Preparações para alimentação infantil à base de farinhas, grumos, sêmolas ou amidos e outros', '15.0'),
(515, '1701600', '04011010', 'Leite “longa vida” (UHT - “Ultra High Temperature”), em recipiente de conteúdo inferior ou igual a 2 litros', '16.0'),
(516, '1701600', '04012010', 'Leite “longa vida” (UHT - “Ultra High Temperature”), em recipiente de conteúdo inferior ou igual a 2 litros', '16.0'),
(517, '1701601', '04011010', 'Leite “longa vida” (UHT - “Ultra High Temperature”), em recipiente de conteúdo superior a 2 litros e inferior ou igual a 5 litros', '16.1'),
(518, '1701601', '04012010', 'Leite “longa vida” (UHT - “Ultra High Temperature”), em recipiente de conteúdo superior a 2 litros e inferior ou igual a 5 litros', '16.1'),
(519, '1701700', '04014010', 'Leite em recipiente de conteúdo inferior ou igual a 1 litro', '17.0'),
(520, '1701700', '04015010', 'Leite em recipiente de conteúdo inferior ou igual a 1 litro', '17.0'),
(521, '1701701', '04014010', 'Leite em recipiente de conteúdo superior a 1 litro e inferior ou igual a 5 litros', '17.1'),
(522, '1701701', '04015010', 'Leite em recipiente de conteúdo superior a 1 litro e inferior ou igual a 5 litros', '17.1'),
(523, '1701800', '04011090', 'Leite do tipo pasteurizado em recipiente de conteúdo inferior ou igual a 1 litro', '18.0'),
(524, '1701800', '04012090', 'Leite do tipo pasteurizado em recipiente de conteúdo inferior ou igual a 1 litro', '18.0'),
(525, '1701801', '04011090', 'Leite do tipo pasteurizado em recipiente de conteúdo superior a 1 litro e inferior ou igual a 5 litros', '18.1'),
(526, '1701801', '04012090', 'Leite do tipo pasteurizado em recipiente de conteúdo superior a 1 litro e inferior ou igual a 5 litros', '18.1'),
(527, '1701900', '0401402', 'Creme de leite, em recipiente de conteúdo inferior ou igual a 1 kg', '19.0'),
(528, '1701900', '04022130', 'Creme de leite, em recipiente de conteúdo inferior ou igual a 1 kg', '19.0'),
(529, '1701900', '04022930', 'Creme de leite, em recipiente de conteúdo inferior ou igual a 1 kg', '19.0'),
(530, '1701900', '04029', 'Creme de leite, em recipiente de conteúdo inferior ou igual a 1 kg', '19.0'),
(531, '1701901', '0401402', 'Creme de leite, em recipiente de conteúdo superior a 1 kg', '19.1'),
(532, '1701901', '04022130', 'Creme de leite, em recipiente de conteúdo superior a 1 kg', '19.1'),
(533, '1701901', '04022930', 'Creme de leite, em recipiente de conteúdo superior a 1 kg', '19.1'),
(534, '1701901', '04029', 'Creme de leite, em recipiente de conteúdo superior a 1 kg', '19.1'),
(535, '1701902', '040110', 'Outros cremes de leite, em recipiente de conteúdo inferior ou igual a 1kg', '19.2'),
(536, '1701902', '040120', 'Outros cremes de leite, em recipiente de conteúdo inferior ou igual a 1kg', '19.2'),
(537, '1701902', '040150', 'Outros cremes de leite, em recipiente de conteúdo inferior ou igual a 1kg', '19.2'),
(538, '1701902', '040210', 'Outros cremes de leite, em recipiente de conteúdo inferior ou igual a 1kg', '19.2'),
(539, '1701902', '04022920', 'Outros cremes de leite, em recipiente de conteúdo inferior ou igual a 1kg', '19.2'),
(540, '1702000', '04029', 'Leite condensado, em recipiente de conteúdo inferior ou igual a 1 kg', '20.0'),
(541, '1702001', '04029', 'Leite condensado, em recipiente de conteúdo superior a 1 kg', '20.1'),
(542, '1702100', '0403', 'Iogurte e leite fermentado em recipiente de conteúdo inferior ou igual a 2 litros', '21.0'),
(543, '1702101', '0403', 'Iogurte e leite fermentado em recipiente de conteúdo superior a 2 litros', '21.1'),
(544, '1702200', '04039000', 'Coalhada', '22.0'),
(545, '1702300', '0406', 'Requeijão e similares, em recipiente de conteúdo inferior ou igual a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g', '23.0'),
(546, '1702301', '0406', 'Requeijão e similares, em recipiente de conteúdo superior a 1 kg', '23.1'),
(547, '1702400', '0406', 'Queijos, exceto os dos CEST 17.024.01, 17.024.02, 17.024.03 e 17.024.04', '24.0'),
(548, '1702401', '04061010', 'Queijo muçarela', '24.1'),
(549, '1702402', '04061090', 'Queijo minas frescal', '24.2'),
(550, '1702403', '04061090', 'Queijo ricota', '24.3'),
(551, '1702404', '04061090', 'Queijo petit suisse', '24.4'),
(552, '1702500', '04051000', 'Manteiga, em embalagem de conteúdo inferior ou igual a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g', '25.0'),
(553, '1702501', '04051000', 'Manteiga, em embalagem de conteúdo superior a 1 kg', '25.1'),
(554, '1702502', '04059090', 'Manteiga de garrafa', '25.2'),
(555, '1702600', '15171000', 'Margarina e creme vegetal em recipiente de conteúdo inferior ou igual a 500 g, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g', '26.0'),
(556, '1702700', '15171000', 'Margarina e creme vegetal, em recipiente de conteúdo superior a 500 g e inferior ou igual a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g', '27.0'),
(557, '1702701', '15171000', 'Margarina e creme vegetal, em recipiente de conteúdo superior a 1 kg', '27.1'),
(558, '1702702', '151790', 'Outras margarinas e cremes vegetais em recipiente de conteúdo inferior a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g', '27.2'),
(559, '1702800', '15162000', 'Gorduras e óleos vegetais e respectivas frações, parcial ou totalmente hidrogenados, interesterificados, reesterificados ou elaidinizados, mesmo refinados, mas não preparados de outro modo, em recipiente de conteúdo inferior ou igual a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g', '28.0'),
(560, '1702801', '15162000', 'Gorduras e óleos vegetais e respectivas frações, parcial ou totalmente hidrogenados, interesterificados, reesterificados ou elaidinizados, mesmo refinados, mas não preparados de outro modo, em recipiente de conteúdo superior a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g', '28.1'),
(561, '1702900', '19019020', 'Doces de leite', '29.0'),
(562, '1703000', '19041000', 'Produtos à base de cereais, obtidos por expansão ou torrefação', '30.0'),
(563, '1703000', '19049000', 'Produtos à base de cereais, obtidos por expansão ou torrefação', '30.0'),
(564, '1703100', '19059090', 'Salgadinhos diversos', '31.0'),
(565, '1703200', '20052000', 'Batata frita, inhame e mandioca fritos', '32.0'),
(566, '1703300', '20081', 'Amendoim e castanhas tipo aperitivo, em embalagem de conteúdo inferior ou igual a 1 kg', '33.0'),
(567, '1703301', '20081', 'Amendoim e castanhas tipo aperitivo, em embalagem de conteúdo superior a 1 kg', '33.1'),
(568, '1703400', '21032010', 'Catchup em embalagens imediatas de conteúdo inferior ou igual a 650 g, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g', '34.0'),
(569, '1703500', '21039021', 'Condimentos e temperos compostos, incluindo molho de pimenta e outros molhos, em embalagens imediatas de conteúdo inferior ou igual a 1 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 3 g', '35.0'),
(570, '1703500', '21039091', 'Condimentos e temperos compostos, incluindo molho de pimenta e outros molhos, em embalagens imediatas de conteúdo inferior ou igual a 1 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 3 g', '35.0'),
(571, '1703600', '21031010', 'Molhos de soja preparados em embalagens imediatas de conteúdo inferior ou igual a 650 g, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g', '36.0'),
(572, '1703700', '21033010', 'Farinha de mostarda em embalagens de conteúdo inferior ou igual a 1 kg', '37.0'),
(573, '1703800', '21033021', 'Mostarda preparada em embalagens imediatas de conteúdo inferior ou igual a 650 g, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g', '38.0'),
(574, '1703900', '21039011', 'Maionese em embalagens imediatas de conteúdo inferior ou igual a 650 g, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g', '39.0'),
(575, '1704000', '2002', 'Tomates preparados ou conservados, exceto em vinagre ou em ácido acético, em embalagens de conteúdo inferior ou igual a 1 kg', '40.0'),
(576, '1704100', '21032010', 'Molhos de tomate em embalagens imediatas de conteúdo inferior ou igual a 1 kg', '41.0'),
(577, '1704200', '17049090', 'Barra de cereais', '42.0'),
(578, '1704200', '19042000', 'Barra de cereais', '42.0'),
(579, '1704200', '19049000', 'Barra de cereais', '42.0'),
(580, '1704300', '18063120', 'Barra de cereais contendo cacau', '43.0'),
(581, '1704300', '18063220', 'Barra de cereais contendo cacau', '43.0'),
(582, '1704300', '18069000', 'Barra de cereais contendo cacau', '43.0'),
(583, '1704400', '11010010', 'Farinha de trigo especial, em embalagem inferior ou igual a 1 kg', '44.0'),
(584, '1704401', '11010010', 'Farinha de trigo especial, em embalagem superior a 1 kg e inferior a 5 kg', '44.1'),
(585, '1704402', '11010010', 'Farinha de trigo especial, em embalagem igual a 5 kg', '44.2'),
(586, '1704403', '11010010', 'Farinha de trigo especial, em embalagem superior a 5 kg e inferior ou igual a 25 kg', '44.3'),
(587, '1704404', '11010010', 'Farinha de trigo especial, em embalagem superior a 25 kg e inferior ou igual a 50 kg', '44.4'),
(588, '1704405', '11010010', 'Farinha de trigo comum, em embalagem igual a 5 kg', '44.5'),
(589, '1704406', '11010010', 'Farinha de trigo comum, em embalagem superior a 5 kg e inferior ou igual a 25 kg', '44.6'),
(590, '1704407', '11010010', 'Farinha de trigo comum, em embalagem superior a 25 kg e inferior ou igual a 50 kg', '44.7'),
(591, '1704408', '11010010', 'Farinha de trigo doméstica especial, em embalagem superior a 5 kg e inferior e igual a 10 kg', '44.8'),
(592, '1704409', '11010010', 'Farinha de trigo doméstica com fermento, em embalagem superior a 5 kg e inferior e igual a 10 kg', '44.9'),
(593, '1704410', '11010010', 'Farinha de trigo especial, em embalagem superior a 50 Kg', '44.10'),
(594, '1704411', '11010010', 'Farinha de trigo comum, em embalagem inferior ou igual a 1 kg', '44.11'),
(595, '1704412', '11010010', 'Farinha de trigo comum, em embalagem superior a 1 kg e inferior a 5 Kg', '44.12'),
(596, '1704413', '11010010', 'Farinha de trigo comum, em embalagem superior a 50 kg', '44.13'),
(597, '1704414', '11010010', 'Farinha de trigo doméstica especial, em embalagem inferior ou igual a 1 kg', '44.14'),
(598, '1704415', '11010010', 'Farinha de trigo doméstica especial, em embalagem superior a 1 kg e inferior a 5 Kg', '44.15'),
(599, '1704416', '11010010', 'Farinha de trigo doméstica especial, em embalagem igual a 5 Kg', '44.16'),
(600, '1704417', '11010010', 'Farinha de trigo doméstica especial, em embalagem superior a 10 Kg', '44.17'),
(601, '1704418', '11010010', 'Farinha de trigo doméstica com fermento, em embalagem inferior ou igual a 1 kg', '44.18'),
(602, '1704419', '11010010', 'Farinha de trigo doméstica com fermento, em embalagem superior a 1 kg e inferior a 5 Kg', '44.19'),
(603, '1704420', '11010010', 'Farinha de trigo doméstica com fermento, em embalagem igual a 5 Kg', '44.20'),
(604, '1704421', '11010010', 'Farinha de trigo doméstica com fermento, em embalagem superior a 10 Kg', '44.21'),
(605, '1704422', '11010010', 'Outras farinhas de trigo, em embalagem inferior ou igual a 1 kg', '44.22'),
(606, '1704423', '11010010', 'Outras farinhas de trigo, em embalagem superior a 1 kg e inferior a 5 Kg', '44.23'),
(607, '1704424', '11010010', 'Outras farinhas de trigo, em embalagem igual a 5 Kg', '44.24'),
(608, '1704425', '11010010', 'Outras farinhas de trigo, em embalagem superior a 5 Kg e inferior ou igual a 25 kg', '44.25'),
(609, '1704426', '11010010', 'Outras farinhas de trigo, em embalagem superior a 25 Kg e inferior ou igual a 50 kg', '44.26'),
(610, '1704427', '11010010', 'Outras farinhas de trigo, em embalagem superior a 50 Kg', '44.27'),
(611, '1704500', '11010020', 'Farinha de mistura de trigo com centeio (méteil)', '45.0'),
(612, '1704600', '19012000', 'Misturas e preparações para bolos, em embalagem inferior 5 kg', '46.0'),
(613, '1704600', '19019090', 'Misturas e preparações para bolos, em embalagem inferior 5 kg', '46.0'),
(614, '1704601', '19012000', 'Misturas e preparações para bolos, em embalagem igual a 5 kg', '46.1'),
(615, '1704601', '19019090', 'Misturas e preparações para bolos, em embalagem igual a 5 kg', '46.1'),
(616, '1704602', '19012000', 'Misturas e preparações para bolos, em embalagem superior a 5 kg e inferior ou igual a 25 Kg', '46.2'),
(617, '1704602', '19019090', 'Misturas e preparações para bolos, em embalagem superior a 5 kg e inferior ou igual a 25 Kg', '46.2'),
(618, '1704603', '19012000', 'Misturas e preparações para bolos, em embalagem superior a 25 kg e inferior ou igual a 50 Kg', '46.3'),
(619, '1704603', '19019090', 'Misturas e preparações para bolos, em embalagem superior a 25 kg e inferior ou igual a 50 Kg', '46.3'),
(620, '1704604', '19012000', 'Misturas e preparações para bolos, em embalagem superior a 50 Kg', '46.4'),
(621, '1704604', '19019090', 'Misturas e preparações para bolos, em embalagem superior a 50 Kg', '46.4'),
(622, '1704605', '19012000', 'Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem inferior a 5 kg', '46.5'),
(623, '1704605', '19019090', 'Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem inferior a 5 kg', '46.5'),
(624, '1704606', '19012000', 'Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem igual a 5 kg', '46.6'),
(625, '1704606', '19019090', 'Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem igual a 5 kg', '46.6'),
(626, '1704607', '19012000', 'Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem superior a 5 kg e inferior ou igual a 25 Kg', '46.7'),
(627, '1704607', '19019090', 'Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem superior a 5 kg e inferior ou igual a 25 Kg', '46.7'),
(628, '1704608', '19012000', 'Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem superior a 25 kg e inferior ou igual a 50 Kg', '46.8'),
(629, '1704608', '19019090', 'Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem superior a 25 kg e inferior ou igual a 50 Kg', '46.8'),
(630, '1704609', '19012000', 'Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem superior a 50 Kg', '46.9'),
(631, '1704609', '19019090', 'Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem superior a 50 Kg', '46.9'),
(632, '1704610', '19012000', 'Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem inferior a 5 kg', '46.10'),
(633, '1704610', '19019090', 'Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem inferior a 5 kg', '46.10'),
(634, '1704611', '19012000', 'Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem igual a 5 kg', '46.11'),
(635, '1704611', '19019090', 'Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem igual a 5 kg', '46.11'),
(636, '1704612', '19012000', 'Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem superior a 5 kg e inferior ou igual a 25 Kg', '46.12'),
(637, '1704612', '19019090', 'Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem superior a 5 kg e inferior ou igual a 25 Kg', '46.12'),
(638, '1704613', '19012000', 'Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem superior a 25 kg e inferior ou igual a 50 Kg', '46.13'),
(639, '1704613', '19019090', 'Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem superior a 25 kg e inferior ou igual a 50 Kg', '46.13'),
(640, '1704614', '19012000', 'Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem superior a 50 Kg', '46.14'),
(641, '1704614', '19019090', 'Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem superior a 50 Kg', '46.14'),
(642, '1704700', '19023000', 'Massas alimentícias tipo instantânea', '47.0'),
(643, '1704800', '1902', 'Massas alimentícias, cozidas ou recheadas (de carne ou de outras substâncias) ou preparadas de outro modo, exceto as descritas nos CEST 17.047.00, 17.048.01, e 17.048.02', '48.0'),
(644, '1704801', '19024000', 'Cuscuz', '48.1'),
(645, '1704802', '19022000', 'Massas alimentícias recheadas (mesmo cozidas ou preparadas de outro modo)', '48.2'),
(646, '1704900', '19021', 'Massas alimentícias do tipo comum, não cozidas, nem recheadas, nem preparadas de outro modo, exceto a descrita no CEST 17.049.03', '49.0'),
(647, '1704901', '19021', 'Massas alimentícias do tipo sêmola, não cozidas, nem recheadas, nem preparadas de outro modo, exceto a descrita no CEST 17.049.04', '49.1'),
(648, '1704902', '19021', 'Massas alimentícias do tipo granoduro, não cozidas, nem recheadas, nem preparadas de outro modo, exceto a descrita no CEST 17.049.05', '49.2'),
(649, '1704903', '19021900', 'Massas alimentícias do tipo comum, não cozidas, nem recheadas, nem preparadas de outro modo, que não contenham ovos', '49.3'),
(650, '1704904', '19021900', 'Massas alimentícias do tipo sêmola, não cozidas, nem recheadas, nem preparadas de outro modo, que não contenham ovos', '49.4'),
(651, '1704905', '19021900', 'Massas alimentícias do tipo granoduro, não cozidas, nem recheadas, nem preparadas de outro modo, que não contenham ovos', '49.5'),
(652, '1705000', '190520', 'Pães industrializados, inclusive de especiarias, exceto panetones e bolo de forma', '50.0'),
(653, '1705100', '19052090', 'Bolo de forma, inclusive de especiarias', '51.0'),
(654, '1705200', '19052010', 'Panetones', '52.0'),
(655, '1705300', '19053100', 'Biscoitos e bolachas derivados de farinha de trigo; (exceto dos tipos “cream cracker”, “água e sal”, “maisena”, “maria” e outros de consumo popular que não sejam adicionados de cacau, nem recheados, cobertos ou amanteigados, independentemente de sua denominação comercial)', '53.0'),
(656, '1705301', '19053100', 'Biscoitos e bolachas derivados de farinha de trigo dos tipos “maisena” e “maria” e outros de consumo popular que não sejam adicionados de cacau, nem recheados, cobertos ou amanteigados, independentemente de sua denominação comercial, exceto o CEST 17.053.02', '53.1'),
(657, '1705302', '19053100', 'Biscoitos e bolachas derivados de farinha de trigo dos tipos "cream cracker" e "água e sal" de consumo popular', '53.2'),
(658, '1705400', '19053100', 'Biscoitos e bolachas não derivados de farinha de trigo; (exceto dos tipos "cream cracker", "água e sal", "maisena" e "maria" e outros de consumo popular que não sejam adicionados de cacau, nem recheados, cobertos ou amanteigados, independentemente de sua denominação comercial)', '54.0'),
(659, '1705401', '19053100', 'Biscoitos e bolachas não derivados de farinha de trigo dos tipos "maisena" e "maria" e outros de consumo popular que não sejam adicionados de cacau, nem recheados, cobertos ou amanteigados, independentemente de sua denominação comercial, exceto o CEST 17.054.02', '54.1'),
(660, '1705402', '19053100', 'Biscoitos e bolachas não derivados de farinha de trigo dos tipos "cream cracker" e "água e sal" de consumo popular', '54.2'),
(661, '1705600', '19059020', 'Biscoitos e bolachas derivados de farinha de trigo dos tipos “cream cracker” e “água e sal”', '56.0'),
(662, '1705601', '19059020', 'Biscoitos e bolachas não derivados de farinha de trigo dos tipos “cream cracker” e “água e sal”', '56.1'),
(663, '1705602', '19059020', 'Outras bolachas, exceto casquinhas para sorvete e os biscoitos e bolachas relacionados nos CEST 17.056.00 e 17.056.01', '56.2'),
(664, '1705700', '19053200', '“Waffles” e “wafers” - sem cobertura', '57.0'),
(665, '1705800', '19053200', '“Waffles” e “wafers” - com cobertura', '58.0'),
(666, '1705900', '19054000', 'Torradas, pão torrado e produtos semelhantes torrados', '59.0'),
(667, '1706000', '19059010', 'Outros pães de forma', '60.0'),
(668, '1706200', '19059090', 'Outros pães, exceto pão francês de até 200 g', '62.0'),
(669, '1706201', '19059090', 'Outros bolos industrializados e produtos de panificação não especificados anteriormente; exceto casquinhas para sorvete e pães', '62.1'),
(670, '1706300', '19051000', 'Pão denominado knackebrot', '63.0'),
(671, '1706400', '190590', 'Demais pães industrializados', '64.0'),
(672, '1706500', '15079011', 'Óleo de soja refinado, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros', '65.0'),
(673, '1706600', '1508', 'Óleo de amendoim refinado, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros', '66.0'),
(674, '1706700', '1509', 'Azeites de oliva, em recipientes com capacidade inferior a 2 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 20 mililitros', '67.0'),
(675, '1706701', '1509', 'Azeites de oliva, em recipientes com capacidade igual ou superior a 2 litros e inferior ou igual a 5 litros', '67.1'),
(676, '1706702', '1509', 'Azeites de oliva, em recipientes com capacidade superior a 5 litros', '67.2'),
(677, '1706800', '15100000', 'Outros óleos e respectivas frações, obtidos exclusivamente a partir de azeitonas, mesmo refinados, mas não quimicamente modificados, e misturas desses óleos ou frações com óleos ou frações da posição 15.09, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros', '68.0'),
(678, '1706900', '15121911', 'Óleo de girassol em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros', '69.0'),
(679, '1706901', '15122910', 'Óleo de algodão refinado em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros', '69.1'),
(680, '1707000', '15141', 'Óleo de canola, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros', '70.0'),
(681, '1707100', '15151900', 'Óleo de linhaça refinado, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros', '71.0'),
(682, '1707200', '15152910', 'Óleo de milho refinado, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros', '72.0'),
(683, '1707300', '15122990', 'Outros óleos refinados, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros', '73.0'),
(684, '1707400', '15179010', 'Misturas de óleos refinados, para consumo humano, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros', '74.0'),
(685, '1707500', '1511', 'Outros óleos vegetais comestíveis não especificados anteriormente', '75.0'),
(686, '1707500', '1513', 'Outros óleos vegetais comestíveis não especificados anteriormente', '75.0'),
(687, '1707500', '1514', 'Outros óleos vegetais comestíveis não especificados anteriormente', '75.0'),
(688, '1707500', '1515', 'Outros óleos vegetais comestíveis não especificados anteriormente', '75.0'),
(689, '1707500', '1516', 'Outros óleos vegetais comestíveis não especificados anteriormente', '75.0'),
(690, '1707500', '1518', 'Outros óleos vegetais comestíveis não especificados anteriormente', '75.0'),
(691, '1707600', '16010000', 'Enchidos (embutidos) e produtos semelhantes, de carne, miudezas ou sangue; exceto salsicha, linguiça e mortadela', '76.0'),
(692, '1707700', '16010000', 'Salsicha e linguiça, exceto as descritas nos CEST 17.077.01', '77.0'),
(693, '1707701', '16010000', 'Salsicha em lata', '77.1'),
(694, '1707800', '16010000', 'Mortadela', '78.0'),
(695, '1707900', '1602', 'Outras preparações e conservas de carne, miudezas ou de sangue, exceto as descritas nos CEST 17.079.01, 17.079.02, 17.079.03, 17.079.04, 17.079.05, 17.079.06 e 17.079.07', '79.0'),
(696, '1707901', '16023100', 'Outras preparações e conservas de carne, de miudezas ou de sangue, de aves da posição 01.05: de peruas e de perus.', '79.1'),
(697, '1707902', '16023210', 'Outras preparações e conservas de carne, de miudezas ou de sangue, de aves da posição 01.05: de galos e de galinhas, com conteúdo de carne ou de miudezas superior ou igual a 57 %, em peso, não cozidas', '79.2'),
(698, '1707903', '16023220', 'Outras preparações e conservas de carne, de miudezas ou de sangue, todas de aves da posição 01.05: de galos e de galinhas, com conteúdo de carne ou de miudezas superior ou igual a 57 %, em peso, cozidas', '79.3'),
(699, '1707904', '16024100', 'Outras preparações e conservas de carne, de miudezas ou de sangue, da espécie suína: pernas e respectivos pedaços', '79.4'),
(700, '1707905', '16024900', 'Outras preparações e conservas de carne, de miudezas ou de sangue, da espécie suína: outras, incluindo as misturas', '79.5'),
(701, '1707906', '16025000', 'Outras preparações e conservas de carne, de miudezas ou de sangue, da espécie bovina, exceto os descritos no CEST 17.079.07', '79.6'),
(702, '1707907', '16025000', 'Apresuntado', '79.7'),
(703, '1708000', '1604', 'Preparações e conservas de peixes; caviar e seus sucedâneos preparados a partir de ovas de peixe; exceto os descritos nos CEST 17.080.01 e 17.081.00', '80.0'),
(704, '1708001', '16042010', 'Outras preparações e conservas de atuns', '80.1'),
(705, '1708100', '1604', 'Sardinha em conserva', '81.0'),
(706, '1708200', '1605', 'Crustáceos, moluscos e outros invertebrados aquáticos, preparados ou em conservas', '82.0'),
(707, '1708300', '02102000', 'Carne de gado bovino, ovino e bufalino e produtos comestíveis resultantes da matança desse gado submetidos à salga, secagem ou desidratação', '83.0'),
(708, '1708300', '02109900', 'Carne de gado bovino, ovino e bufalino e produtos comestíveis resultantes da matança desse gado submetidos à salga, secagem ou desidratação', '83.0'),
(709, '1708300', '1502', 'Carne de gado bovino, ovino e bufalino e produtos comestíveis resultantes da matança desse gado submetidos à salga, secagem ou desidratação', '83.0'),
(710, '1708400', '0201', 'Carne de gado bovino, ovino e bufalino e demais produtos comestíveis resultantes da matança desse gado frescos, refrigerados ou congelados', '84.0'),
(711, '1708400', '0202', 'Carne de gado bovino, ovino e bufalino e demais produtos comestíveis resultantes da matança desse gado frescos, refrigerados ou congelados', '84.0'),
(712, '1708400', '0204', 'Carne de gado bovino, ovino e bufalino e demais produtos comestíveis resultantes da matança desse gado frescos, refrigerados ou congelados', '84.0'),
(713, '1708400', '0206', 'Carne de gado bovino, ovino e bufalino e demais produtos comestíveis resultantes da matança desse gado frescos, refrigerados ou congelados', '84.0'),
(714, '1708500', '0204', 'Carnes de animais das espécies caprina, frescas, refrigeradas ou congeladas', '85.0'),
(715, '1708600', '02109900', 'Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados ou salmourados resultantes do abate de caprinos', '86.0'),
(716, '1708600', '15021019', 'Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados ou salmourados resultantes do abate de caprinos', '86.0'),
(717, '1708600', '15029000', 'Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados ou salmourados resultantes do abate de caprinos', '86.0'),
(718, '1708700', '0207', 'Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de aves, exceto os descritos no CEST 17.087.02', '87.0'),
(719, '1708700', '0209', 'Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de aves, exceto os descritos no CEST 17.087.02', '87.0'),
(720, '1708700', '02109900', 'Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de aves, exceto os descritos no CEST 17.087.02', '87.0'),
(721, '1708700', '1501', 'Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de aves, exceto os descritos no CEST 17.087.02', '87.0'),
(722, '1708701', '0203', 'Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de suínos', '87.1'),
(723, '1708701', '0206', 'Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de suínos', '87.1'),
(724, '1708701', '0209', 'Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de suínos', '87.1'),
(725, '1708701', '02101', 'Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de suínos', '87.1'),
(726, '1708701', '02109900', 'Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de suínos', '87.1'),
(727, '1708701', '1501', 'Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de suínos', '87.1'),
(728, '1708702', '02071', 'Carnes de aves inteiras e com peso unitário superior a 3 kg, temperadas', '87.2'),
(729, '1708702', '02072', 'Carnes de aves inteiras e com peso unitário superior a 3 kg, temperadas', '87.2'),
(730, '1708800', '0710', 'Produtos hortícolas, cozidos em água ou vapor, congelados, em embalagens de conteúdo inferior ou igual a 1 kg', '88.0'),
(731, '1708801', '0710', 'Produtos hortícolas, cozidos em água ou vapor, congelados, em embalagens de conteúdo superior a 1 kg', '88.1'),
(732, '1708900', '0811', 'Frutas, não cozidas ou cozidas em água ou vapor, congeladas, mesmo adicionadas de açúcar ou de outros edulcorantes, em embalagens de conteúdo inferior ou igual a 1 kg', '89.0'),
(733, '1708901', '0811', 'Frutas, não cozidas ou cozidas em água ou vapor, congeladas, mesmo adicionadas de açúcar ou de outros edulcorantes, em embalagens de conteúdo superior a 1 kg', '89.1'),
(734, '1709000', '2001', 'Produtos hortícolas, frutas e outras partes comestíveis de plantas, preparados ou conservados em vinagre ou em ácido acético, em embalagens de conteúdo inferior ou igual a 1 kg', '90.0'),
(735, '1709001', '2001', 'Produtos hortícolas, frutas e outras partes comestíveis de plantas, preparados ou conservados em vinagre ou em ácido acético, em embalagens de conteúdo superior a 1 kg', '90.1'),
(736, '1709100', '2004', 'Outros produtos hortícolas preparados ou conservados, exceto em vinagre ou em ácido acético, congelados, com exceção dos produtos da posição 20.06, em embalagens de conteúdo inferior ou igual a 1 kg', '91.0'),
(737, '1709101', '2004', 'Outros produtos hortícolas preparados ou conservados, exceto em vinagre ou em ácido acético, congelados, com exceção dos produtos da posição 20.06, em embalagens de conteúdo superior a 1 kg', '91.1'),
(738, '1709200', '2005', 'Outros produtos hortícolas preparados ou conservados, exceto em vinagre ou em ácido acético, não congelados, com exceção dos produtos da posição 20.06, excluídos batata, inhame e mandioca fritos, em embalagens de conteúdo inferior ou igual a 1 kg', '92.0'),
(739, '1709201', '2005', 'Outros produtos hortícolas preparados ou conservados, exceto em vinagre ou em ácido acético, não congelados, com exceção dos produtos da posição 20.06, excluídos batata, inhame e mandioca fritos, em embalagens de conteúdo superior a 1 kg', '92.1'),
(740, '1709300', '20060000', 'Produtos hortícolas, frutas, cascas de frutas e outras partes de plantas, conservados com açúcar (passados por calda, glaceados ou cristalizados), em embalagens de conteúdo inferior ou igual a 1 kg', '93.0'),
(741, '1709301', '20060000', 'Produtos hortícolas, frutas, cascas de frutas e outras partes de plantas, conservados com açúcar (passados por calda, glaceados ou cristalizados), em embalagens de conteúdo superior a 1 kg', '93.1'),
(742, '1709400', '2007', 'Doces, geleias, “marmelades”, purês e pastas de frutas, obtidos por cozimento, com ou sem adição de açúcar ou de outros edulcorantes, em embalagens de conteúdo inferior ou igual a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g', '94.0'),
(743, '1709401', '2007', 'Doces, geleias, “marmelades”, purês e pastas de frutas, obtidos por cozimento, com ou sem adição de açúcar ou de outros edulcorantes, em embalagens de conteúdo superior a 1 kg', '94.1'),
(744, '1709500', '2008', 'Frutas e outras partes comestíveis de plantas, preparadas ou conservadas de outro modo, com ou sem adição de açúcar ou de outros edulcorantes ou de álcool, não especificadas nem compreendidas em outras posições, excluídos os amendoins e castanhas tipo aperitivo, da posição 2008.1, em embalagens de conteúdo inferior ou igual a 1 kg', '95.0'),
(745, '1709501', '2008', 'Frutas e outras partes comestíveis de plantas, preparadas ou conservadas de outro modo, com ou sem adição de açúcar ou de outros edulcorantes ou de álcool, não especificadas nem compreendidas em outras posições, excluídos os amendoins e castanhas tipo aperitivo, da posição 2008.1, em embalagens superior a 1 kg', '95.1'),
(746, '1709600', '0901', 'Café torrado e moído, em embalagens de conteúdo inferior ou igual a 2 kg, exceto os classificados nos CEST 17.096.04 e 17.096.05', '96.0'),
(747, '1709601', '0901', 'Café torrado e moído, em embalagens de conteúdo superior a 2 kg', '96.1'),
(748, '1709602', '0901', 'Café torrado em grão, em embalagens de conteúdo inferior ou igual a 2 kg', '96.2'),
(749, '1709603', '0901', 'Café torrado em grão, em embalagens de conteúdo superior a 2 kg', '96.3'),
(750, '1709604', '0901', 'Café torrado e moído, em cápsulas, exceto os descritos no CEST 17.096.05', '96.4'),
(751, '1709605', '0901', 'Café descafeinado torrado e moído, em cápsulas', '96.5'),
(752, '1709700', '0902', 'Chá, mesmo aromatizado', '97.0'),
(753, '1709700', '12119090', 'Chá, mesmo aromatizado', '97.0'),
(754, '1709700', '21069090', 'Chá, mesmo aromatizado', '97.0'),
(755, '1709800', '090300', 'Mate', '98.0'),
(756, '1709900', '17011', 'Açúcar refinado, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g', '99.0'),
(757, '1709900', '17019900', 'Açúcar refinado, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g', '99.0'),
(758, '1709901', '17011', 'Açúcar refinado, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg', '99.1'),
(759, '1709901', '17019900', 'Açúcar refinado, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg', '99.1'),
(760, '1709902', '17011', 'Açúcar refinado, em embalagens de conteúdo superior a 5 kg', '99.2'),
(761, '1709902', '17019900', 'Açúcar refinado, em embalagens de conteúdo superior a 5 kg', '99.2'),
(762, '1710000', '17019100', 'Açúcar refinado adicionado de aromatizante ou de corante em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g', '100.0'),
(763, '1710001', '17019100', 'Açúcar refinado adicionado de aromatizante ou de corante em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg', '100.1'),
(764, '1710002', '17019100', 'Açúcar refinado adicionado de aromatizante ou de corante em embalagens de conteúdo superior a 5 kg', '100.2'),
(765, '1710100', '17011', 'Açúcar cristal, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g', '101.0'),
(766, '1710100', '17019900', 'Açúcar cristal, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g', '101.0'),
(767, '1710101', '17011', 'Açúcar cristal, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg', '101.1'),
(768, '1710101', '17019900', 'Açúcar cristal, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg', '101.1'),
(769, '1710102', '17011', 'Açúcar cristal, em embalagens de conteúdo superior a 5 kg', '101.2'),
(770, '1710102', '17019900', 'Açúcar cristal, em embalagens de conteúdo superior a 5 kg', '101.2'),
(771, '1710200', '17019100', 'Açúcar cristal adicionado de aromatizante ou de corante, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g', '102.0'),
(772, '1710201', '17019100', 'Açúcar cristal adicionado de aromatizante ou de corante, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg', '102.1'),
(773, '1710202', '170191', 'Açúcar cristal adicionado de aromatizante ou de corante, em embalagens de conteúdo superior a 5 kg', '102.2'),
(774, '1710300', '17011', 'Outros tipos de açúcar, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g', '103.0'),
(775, '1710300', '17019900', 'Outros tipos de açúcar, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g', '103.0'),
(776, '1710301', '17011', 'Outros tipos de açúcar, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg', '103.1'),
(777, '1710301', '17019900', 'Outros tipos de açúcar, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg', '103.1'),
(778, '1710302', '17011', 'Outros tipos de açúcar, em embalagens de conteúdo superior a 5 kg', '103.2'),
(779, '1710302', '17019900', 'Outros tipos de açúcar, em embalagens de conteúdo superior a 5 kg', '103.2'),
(780, '1710400', '17019100', 'Outros tipos de açúcar adicionado de aromatizante ou de corante, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g', '104.0'),
(781, '1710401', '17019100', 'Outros tipos de açúcar adicionado de aromatizante ou de corante, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg', '104.1'),
(782, '1710402', '17019100', 'Outros tipos de açúcar adicionado de aromatizante ou de corante, em embalagens de conteúdo superior a 5 kg', '104.2'),
(783, '1710500', '1702', 'Outros açúcares em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g', '105.0'),
(784, '1710501', '1702', 'Outros açúcares, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg', '105.1'),
(785, '1710502', '1702', 'Outros açúcares, em embalagens de conteúdo superior a 5 kg', '105.2'),
(786, '1710600', '20081900', 'Milho para pipoca (micro-ondas)', '106.0'),
(787, '1710700', '21011', 'Extratos, essências e concentrados de café e preparações à base destes extratos, essências ou concentrados ou à base de café, em embalagens de conteúdo inferior ou igual a 500 g, exceto os classificados no CEST 17.107.01', '107.0'),
(788, '1710701', '21011', 'Extratos, essências e concentrados de café e preparações à base destes extratos, essências ou concentrados ou à base de café, em cápsulas', '107.1'),
(789, '1710800', '210120', 'Extratos, essências e concentrados de chá ou de mate e preparações à base destes extratos, essências ou concentrados ou à base de chá ou de mate, em embalagens de conteúdo inferior ou igual a 500 g, exceto as bebidas prontas à base de mate ou chá e os itens classificados no CEST 17.108.01', '108.0'),
(790, '1710801', '210120', 'Extratos, essências e concentrados de chá ou de mate e preparações à base destes extratos, essências ou concentrados ou à base de chá ou de mate, em cápsulas', '108.1'),
(791, '1710900', '19019090', 'Preparações em pó para cappuccino e similares, em embalagens de conteúdo inferior ou igual a 500 g', '109.0'),
(792, '1710900', '21011190', 'Preparações em pó para cappuccino e similares, em embalagens de conteúdo inferior ou igual a 500 g', '109.0'),
(793, '1710900', '21011200', 'Preparações em pó para cappuccino e similares, em embalagens de conteúdo inferior ou igual a 500 g', '109.0'),
(794, '1711000', '22021000', 'Refrescos e outras bebidas prontas para beber, à base de chá e mate', '110.0'),
(795, '1711100', '22021000', 'Refrescos e outras bebidas não alcoólicas, exceto os refrigerantes e as demais bebidas nos CEST 03.007.00 e 17.110.00', '111.0'),
(796, '1711200', '22029900', 'Néctares de frutas e outras bebidas não alcoólicas prontas para beber, exceto isotônicos e energéticos', '112.0'),
(797, '1711300', '210120', 'Bebidas prontas à base de mate ou chá', '113.0'),
(798, '1711300', '22029900', 'Bebidas prontas à base de mate ou chá', '113.0'),
(799, '1711400', '22029900', 'Bebidas prontas à base de café', '114.0'),
(800, '1711500', '22029900', 'Bebidas alimentares prontas à base de soja, leite ou cacau, inclusive os produtos denominados bebidas lácteas', '115.0'),
(801, '1900100', '32131000', 'Tinta guache', '1.0'),
(802, '1900200', '39162000', 'Espiral - perfil para encadernação, de plástico e outros materiais classificados nas posições 3901 a 3914', '2.0'),
(803, '1900300', '39161000', 'Outros espirais - perfil para encadernação, de plástico e outros materiais classificados nas posições 3901 a 3914', '3.0'),
(804, '1900300', '391690', 'Outros espirais - perfil para encadernação, de plástico e outros materiais classificados nas posições 3901 a 3914', '3.0'),
(805, '1900400', '39261000', 'Artigos de escritório e artigos escolares de plástico e outros materiais classificados nas posições 3901 a 3914, exceto estojos', '4.0'),
(806, '1900500', '42021', 'Maletas e pastas para documentos e de estudante, e artefatos semelhantes', '5.0'),
(807, '1900500', '42029', 'Maletas e pastas para documentos e de estudante, e artefatos semelhantes', '5.0'),
(808, '1900501', '42021', 'Baús, malas e maletas para viagem', '5.1'),
(809, '1900501', '42029', 'Baús, malas e maletas para viagem', '5.1'),
(810, '1900600', '39269090', 'Prancheta de plástico', '6.0'),
(811, '1900700', '48022090', 'Bobina para fax', '7.0'),
(812, '1900700', '48119090', 'Bobina para fax', '7.0'),
(813, '1900800', '4802549', 'Papel seda', '8.0'),
(814, '1900900', '48025499', 'Bobina para máquina de calcular, PDV ou equipamentos similares', '9.0'),
(815, '1900900', '48025799', 'Bobina para máquina de calcular, PDV ou equipamentos similares', '9.0'),
(816, '1900900', '48162000', 'Bobina para máquina de calcular, PDV ou equipamentos similares', '9.0'),
(817, '1901000', '4802569', 'Cartolina escolar e papel cartão, brancos e coloridos; recados auto adesivos (LP note); papéis de presente, todos cortados em tamanho pronto para uso escolar e doméstico', '10.0'),
(818, '1901000', '4802579', 'Cartolina escolar e papel cartão, brancos e coloridos; recados auto adesivos (LP note); papéis de presente, todos cortados em tamanho pronto para uso escolar e doméstico', '10.0'),
(819, '1901000', '4802589', 'Cartolina escolar e papel cartão, brancos e coloridos; recados auto adesivos (LP note); papéis de presente, todos cortados em tamanho pronto para uso escolar e doméstico', '10.0'),
(820, '1901100', '37031010', 'Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia “Thermo-autochrome”, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela', '11.0'),
(821, '1901100', '37031029', 'Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia “Thermo-autochrome”, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela', '11.0'),
(822, '1901100', '37032000', 'Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia “Thermo-autochrome”, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela', '11.0'),
(823, '1901100', '37039010', 'Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia “Thermo-autochrome”, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela', '11.0'),
(824, '1901100', '37040000', 'Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia “Thermo-autochrome”, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela', '11.0'),
(825, '1901100', '48022010', 'Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia “Thermo-autochrome”, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela', '11.0'),
(826, '1901100', '48022090', 'Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia “Thermo-autochrome”, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela', '11.0'),
(827, '1901200', '48101390', 'Papel almaço', '12.0'),
(828, '1901300', '48169010', 'Papel hectográfico', '13.0'),
(829, '1901400', '39202019', 'Papel celofane e tipo celofane', '14.0'),
(830, '1901500', '48062000', 'Papel impermeável', '15.0'),
(831, '1901600', '48081000', 'Papel crepon', '16.0'),
(832, '1901700', '48102290', 'Papel fantasia', '17.0'),
(833, '1901800', '4809', 'Papel-carbono, papel autocopiativo (exceto os vendidos em rolos de diâmetro igual ou superior a 60 cm e os vendidos em folhas de formato igual ou superior a 60 cm de altura e igual ou superior a 90 cm de largura) e outros papéis para cópia ou duplicação (incluídos os papéis para estênceis ou para chapas ofsete), estênceis completos e chapas ofsete, de papel, em folhas, mesmo acondicionados em caixas', '18.0'),
(834, '1901800', '4816', 'Papel-carbono, papel autocopiativo (exceto os vendidos em rolos de diâmetro igual ou superior a 60 cm e os vendidos em folhas de formato igual ou superior a 60 cm de altura e igual ou superior a 90 cm de largura) e outros papéis para cópia ou duplicação (incluídos os papéis para estênceis ou para chapas ofsete), estênceis completos e chapas ofsete, de papel, em folhas, mesmo acondicionados em caixas', '18.0'),
(835, '1901900', '4817', 'Envelopes, aerogramas, bilhetes-postais não ilustrados e cartões para correspondência, de papel ou cartão, caixas, sacos e semelhantes, de papel ou cartão, contendo um sortido de artigos para correspondência', '19.0'),
(836, '1902000', '48201000', 'Livros de registro e de contabilidade, blocos de notas, de encomendas, de recibos, de apontamentos, de papel para cartas, agendas e artigos semelhantes', '20.0'),
(837, '1902100', '48202000', 'Cadernos', '21.0'),
(838, '1902200', '48203000', 'Classificadores, capas para encadernação (exceto as capas para livros) e capas de processos', '22.0'),
(839, '1902300', '48204000', 'Formulários em blocos tipo “manifold”, mesmo com folhas intercaladas de papel-carbono', '23.0'),
(840, '1902400', '48205000', 'Álbuns para amostras ou para coleções', '24.0'),
(841, '1902500', '48209000', 'Pastas para documentos, outros artigos escolares, de escritório ou de papelaria, de papel ou cartão e capas para livros, de papel ou cartão', '25.0'),
(842, '1902600', '49090000', 'Cartões postais impressos ou ilustrados, cartões impressos com votos ou mensagens pessoais, mesmo ilustrados, com ou sem envelopes, guarnições ou aplicações (conhecidos como cartões de expressão social - de época/sentimento)', '26.0'),
(843, '1902700', '96081000', 'Canetas esferográficas', '27.0'),
(844, '1902800', '96082000', 'Canetas e marcadores, com ponta de feltro ou com outras pontas porosas', '28.0'),
(845, '1902900', '96083000', 'Canetas tinteiro', '29.0'),
(846, '1903000', '9608', 'Outras canetas; sortidos de canetas', '30.0'),
(847, '1903100', '480256', 'Papel cortado “cutsize” (tipo A3, A4, ofício I e II, carta e outros)', '31.0'),
(848, '1903200', '52105990', 'Papel camurça', '32.0'),
(849, '1903300', '76071190', 'Papel laminado e papel espelho', '33.0'),
(850, '2000100', '12119090', 'Henna (embalagens de conteúdo inferior ou igual a 200 g)', '1.0'),
(851, '2000101', '12119090', 'Henna (embalagens de conteúdo superior a 200 g)', '1.1'),
(852, '2000200', '27121000', 'Vaselina', '2.0'),
(853, '2000300', '28142000', 'Amoníaco em solução aquosa (amônia)', '3.0'),
(854, '2000400', '28470000', 'Peróxido de hidrogênio, em embalagens de conteúdo inferior ou igual a 500 ml', '4.0'),
(855, '2000500', '30067000', 'Lubrificação íntima', '5.0'),
(856, '2000600', '3301', 'Óleos essenciais (desterpenados ou não), incluídos os chamados “concretos” ou “absolutos”; resinoides; oleorresinas de extração; soluções concentradas de óleos essenciais em gorduras, em óleos fixos, em ceras ou em matérias análogas, obtidas por tratamento de flores através de substâncias gordas ou por maceração; subprodutos terpênicos residuais da desterpenação dos óleos essenciais; águas destiladas aromáticas e soluções aquosas de óleos essenciais, em embalagens de conteúdo inferior ou igual a 500 ml', '6.0'),
(857, '2000700', '33030010', 'Perfumes (extratos)', '7.0'),
(858, '2000800', '33030020', 'Águas-de-colônia', '8.0'),
(859, '2000900', '33041000', 'Produtos de maquilagem para os lábios', '9.0'),
(860, '2001000', '33042010', 'Sombra, delineador, lápis para sobrancelhas e rímel', '10.0'),
(861, '2001100', '33042090', 'Outros produtos de maquilagem para os olhos', '11.0'),
(862, '2001200', '33043000', 'Preparações para manicuros e pedicuros, incluindo removedores de esmalte à base de acetona', '12.0'),
(863, '2001300', '33049100', 'Pós, incluídos os compactos', '13.0'),
(864, '2001400', '33049910', 'Cremes de beleza, cremes nutritivos e loções tônicas', '14.0'),
(865, '2001500', '33049990', 'Outros produtos de beleza ou de maquilagem preparados e preparações para conservação ou cuidados da pele, exceto as preparações solares e antissolares', '15.0'),
(866, '2001600', '33049990', 'Preparações solares e antissolares', '16.0'),
(867, '2001700', '33051000', 'Xampus para o cabelo', '17.0'),
(868, '2001800', '33052000', 'Preparações para ondulação ou alisamento, permanentes, dos cabelos', '18.0'),
(869, '2001900', '33053000', 'Laquês para o cabelo', '19.0'),
(870, '2002000', '33059000', 'Outras preparações capilares, incluindo máscaras e finalizadores', '20.0'),
(871, '2002100', '33059000', 'Condicionadores', '21.0'),
(872, '2002200', '33059000', 'Tintura para o cabelo', '22.0'),
(873, '2002300', '33061000', 'Dentifrícios', '23.0'),
(874, '2002400', '33062000', 'Fios utilizados para limpar os espaços interdentais (fios dentais)', '24.0'),
(875, '2002500', '33069000', 'Outras preparações para higiene bucal ou dentária', '25.0'),
(876, '2002600', '33071000', 'Preparações para barbear (antes, durante ou após)', '26.0'),
(877, '2002700', '33072010', 'Desodorantes (desodorizantes) corporais líquidos, exceto os classificados no CEST 20.027.01', '27.0'),
(878, '2002701', '33072010', 'Loções e óleos desodorantes hidratantes líquidos', '27.1'),
(879, '2002800', '33072010', 'Antiperspirantes líquidos', '28.0'),
(880, '2002900', '33072090', 'Outros desodorantes (desodorizantes) corporais, exceto os classificados no CEST 20.029.01', '29.0'),
(881, '2002901', '33072090', 'Outras loções e óleos desodorantes hidratantes', '29.1'),
(882, '2003000', '33072090', 'Outros antiperspirantes', '30.0'),
(883, '2003100', '33073000', 'Sais perfumados e outras preparações para banhos', '31.0'),
(884, '2003200', '33079000', 'Outros produtos de perfumaria preparados', '32.0'),
(885, '2003201', '33079000', 'Outros produtos de toucador preparados', '32.1'),
(886, '2003300', '33079000', 'Soluções para lentes de contato ou para olhos artificiais', '33.0'),
(887, '2003400', '34011190', 'Sabões de toucador em barras, pedaços ou figuras moldados', '34.0'),
(888, '2003500', '34011900', 'Outros sabões, produtos e preparações, em barras, pedaços ou figuras moldados', '35.0'),
(889, '2003501', '34011900', 'Lenços umedecidos', '35.1'),
(890, '2003600', '34012010', 'Sabões de toucador sob outras formas', '36.0'),
(891, '2003700', '34013000', 'Produtos e preparações orgânicos tensoativos para lavagem da pele, na forma de líquido ou de creme, acondicionados para venda a retalho, mesmo contendo sabão', '37.0'),
(892, '2003800', '40149010', 'Bolsa para gelo ou para água quente', '38.0'),
(893, '2003900', '40149090', 'Chupetas e bicos para mamadeiras e para chupetas, de borracha', '39.0'),
(894, '2004000', '39249000', 'Chupetas e bicos para mamadeiras e para chupetas, de silicone', '40.0'),
(895, '2004000', '39269040', 'Chupetas e bicos para mamadeiras e para chupetas, de silicone', '40.0'),
(896, '2004000', '39269090', 'Chupetas e bicos para mamadeiras e para chupetas, de silicone', '40.0'),
(897, '2004100', '42021', 'Malas e maletas de toucador', '41.0'),
(898, '2004200', '48181000', 'Papel higiênico - folha simples', '42.0'),
(899, '2004300', '48181000', 'Papel higiênico - folha dupla e tripla', '43.0'),
(900, '2004400', '48182000', 'Lenços (incluídos os de maquilagem) e toalhas de mão', '44.0'),
(901, '2004500', '48182000', 'Papel toalha de uso institucional do tipo comercializado em rolos igual ou superior a 80 metros e do tipo comercializado em folhas intercaladas', '45.0'),
(902, '2004600', '48183000', 'Toalhas e guardanapos de mesa', '46.0'),
(903, '2004700', '48189090', 'Toalhas de cozinha (papel toalha de uso doméstico)', '47.0'),
(904, '2004800', '96190000', 'Fraldas, exceto os descritos no CEST 20.048.01', '48.0'),
(905, '2004801', '96190000', 'Fraldas de fibras têxteis', '48.1'),
(906, '2004900', '96190000', 'Tampões higiênicos', '49.0'),
(907, '2005000', '96190000', 'Absorventes higiênicos externos', '50.0'),
(908, '2005100', '56012190', 'Hastes flexíveis (uso não medicinal)', '51.0'),
(909, '2005200', '56039290', 'Sutiã descartável, assemelhados e papel para depilação', '52.0'),
(910, '2005300', '82032090', 'Pinças para sobrancelhas', '53.0'),
(911, '2005400', '82141000', 'Espátulas (artigos de cutelaria)', '54.0'),
(912, '2005500', '82142000', 'Utensílios e sortidos de utensílios de manicuros ou de pedicuros (incluídas as limas para unhas)', '55.0'),
(913, '2005600', '90251110', 'Termômetros, inclusive o digital', '56.0'),
(914, '2005600', '90251990', 'Termômetros, inclusive o digital', '56.0'),
(915, '2005700', '96032', 'Escovas e pincéis de barba, escovas para cabelos, para cílios ou para unhas e outras escovas de toucador de pessoas, incluídas as que sejam partes de aparelhos, exceto escovas de dentes', '57.0'),
(916, '2005800', '96032100', 'Escovas de dentes, incluídas as escovas para dentaduras', '58.0'),
(917, '2005900', '96033000', 'Pincéis para aplicação de produtos cosméticos', '59.0'),
(918, '2006000', '96050000', 'Sortidos de viagem, para toucador de pessoas para costura ou para limpeza de calçado ou de roupas', '60.0'),
(919, '2006100', '9615', 'Pentes, travessas para cabelo e artigos semelhantes; grampos (alfinetes) para cabelo; pinças (pinceguiches), onduladores, bobes (rolos) e artefatos semelhantes para penteados, e suas partes, exceto os classificados na posição 8516 e suas partes', '61.0'),
(920, '2006200', '96162000', 'Borlas ou esponjas para pós ou para aplicação de outros cosméticos ou de produtos de toucador', '62.0'),
(921, '2006300', '39233000', 'Mamadeiras', '63.0'),
(922, '2006300', '39241000', 'Mamadeiras', '63.0'),
(923, '2006300', '39249000', 'Mamadeiras', '63.0'),
(924, '2006300', '40149090', 'Mamadeiras', '63.0'),
(925, '2006300', '70102000', 'Mamadeiras', '63.0'),
(926, '2006400', '82121020', 'Aparelhos e lâminas de barbear', '64.0'),
(927, '2006400', '82122010', 'Aparelhos e lâminas de barbear', '64.0'),
(928, '2100100', '73211100', 'Fogões de cozinha de uso doméstico e suas partes', '1.0'),
(929, '2100100', '73218100', 'Fogões de cozinha de uso doméstico e suas partes', '1.0'),
(930, '2100100', '73219000', 'Fogões de cozinha de uso doméstico e suas partes', '1.0'),
(931, '2100200', '84181000', 'Combinações de refrigeradores e congeladores (“freezers”), munidos de portas exteriores separadas', '2.0'),
(932, '2100300', '84182100', 'Refrigeradores do tipo doméstico, de compressão', '3.0'),
(933, '2100400', '84182900', 'Outros refrigeradores do tipo doméstico', '4.0'),
(934, '2100500', '84183000', 'Congeladores (“freezers”) horizontais tipo arca, de capacidade não superior a 800 litros', '5.0'),
(935, '2100600', '84184000', 'Congeladores (“freezers”) verticais tipo armário, de capacidade não superior a 900 litros', '6.0'),
(936, '2100700', '841850', 'Outros móveis (arcas, armários, vitrines, balcões e móveis semelhantes) para a conservação e exposição de produtos, que incorporem um equipamento para a produção de frio', '7.0'),
(937, '2100800', '8418699', 'Mini adega e similares', '8.0'),
(938, '2100900', '84186999', 'Máquinas para produção de gelo', '9.0'),
(939, '2101000', '84189900', 'Partes dos refrigeradores, congeladores, mini adegas e similares, máquinas para produção de gelo e bebedouros descritos nos CEST 21.002.00, 21.003.00, 21.004.00, 21.005.00, 21.006.00, 21.007.00, 21.008.00, 21.009.00 e 21.013.00', '10.0'),
(940, '2101100', '842112', 'Secadoras de roupa de uso doméstico', '11.0'),
(941, '2101200', '84211990', 'Outras secadoras de roupas e centrífugas de uso doméstico', '12.0'),
(942, '2101300', '84186931', 'Bebedouros refrigerados para água', '13.0'),
(943, '2101400', '84219', 'Partes das secadoras de roupas e centrífugas de uso doméstico e dos aparelhos para filtrar ou depurar água, descritos nos CEST 21.011.00 e 21.012.00 e 21.098.00', '14.0'),
(944, '2101500', '84221100', 'Máquinas de lavar louça do tipo doméstico e suas partes', '15.0'),
(945, '2101500', '84229010', 'Máquinas de lavar louça do tipo doméstico e suas partes', '15.0'),
(946, '2101600', '844331', 'Máquinas que executem pelo menos duas das seguintes funções: impressão, cópia ou transmissão de telecópia (fax), capazes de ser conectadas a uma máquina automática para processamento de dados ou a uma rede', '16.0'),
(947, '2101700', '844332', 'Outras impressoras, máquinas copiadoras e telecopiadores (fax), mesmo combinados entre si, capazes de ser conectados a uma máquina automática para processamento de dados ou a uma rede', '17.0'),
(948, '2101800', '84439', 'Partes e acessórios de máquinas e aparelhos de impressão por meio de blocos, cilindros e outros elementos de impressão da posição 8442; e de outras impressoras, máquinas copiadoras e telecopiadores (fax), mesmo combinados entre si', '18.0'),
(949, '2101900', '84501100', 'Máquinas de lavar roupa, mesmo com dispositivos de secagem, de uso doméstico, de capacidade não superior a 10 kg, em peso de roupa seca, inteiramente automáticas', '19.0'),
(950, '2102000', '84501200', 'Outras máquinas de lavar roupa, mesmo com dispositivos de secagem, de uso doméstico, com secador centrífugo incorporado', '20.0'),
(951, '2102100', '84501900', 'Outras máquinas de lavar roupa, mesmo com dispositivos de secagem, de uso doméstico', '21.0'),
(952, '2102200', '845020', 'Máquinas de lavar roupa, mesmo com dispositivos de secagem, de uso doméstico, de capacidade superior a 10 kg, em peso de roupa seca', '22.0'),
(953, '2102300', '845090', 'Partes de máquinas de lavar roupa, mesmo com dispositivos de secagem, de uso doméstico', '23.0'),
(954, '2102400', '84512100', 'Máquinas de secar de uso doméstico de capacidade não superior a 10 kg, em peso de roupa seca', '24.0'),
(955, '2102500', '84512990', 'Outras máquinas de secar de uso doméstico', '25.0'),
(956, '2102600', '845190', 'Partes de máquinas de secar de uso doméstico', '26.0'),
(957, '2102700', '84521000', 'Máquinas de costura de uso doméstico', '27.0'),
(958, '2102800', '847130', 'Máquinas automáticas para processamento de dados, portáteis, de peso não superior a 10 kg, contendo pelo menos uma unidade central de processamento, um teclado e uma tela', '28.0'),
(959, '2102900', '84714', 'Outras máquinas automáticas para processamento de dados', '29.0'),
(960, '2103000', '84715010', 'Unidades de processamento, de pequena capacidade, exceto as das subposições 8471.41 ou 8471.49, podendo conter, no mesmo corpo, um ou dois dos seguintes tipos de unidades: unidade de memória, unidade de entrada e unidade de saída; baseadas em microprocessadores, com capacidade de instalação, dentro do mesmo gabinete, de unidades de memória da subposição 8471.70, podendo conter múltiplos conectores de expansão (“slots”), e valor FOB inferior ou igual a US$ 12.500,00, por unidade', '30.0'),
(961, '2103100', '8471605', 'Unidades de entrada, exceto as classificadas no código 8471.60.54', '31.0'),
(962, '2103200', '84716090', 'Outras unidades de entrada ou de saída, podendo conter, no mesmo corpo, unidades de memória', '32.0'),
(963, '2103300', '847170', 'Unidades de memória', '33.0'),
(964, '2103400', '847190', 'Outras máquinas automáticas para processamento de dados e suas unidades; leitores magnéticos ou ópticos, máquinas para registrar dados em suporte sob forma codificada, e máquinas para processamento desses dados, não especificadas nem compreendidas em outras posições', '34.0'),
(965, '2103500', '847330', 'Partes e acessórios das máquinas da posição 84.71', '35.0'),
(966, '2103600', '85043', 'Outros transformadores, exceto os classificados nos códigos 8504.33.00 e 8504.34.00', '36.0'),
(967, '2103700', '85044010', 'Carregadores de acumuladores', '37.0'),
(968, '2103800', '85044040', 'Equipamentos de alimentação ininterrupta de energia (UPS ou “no break”)', '38.0'),
(969, '2103900', '85078000', 'Outros acumuladores', '39.0'),
(970, '2104000', '8508', 'Aspiradores', '40.0'),
(971, '2104100', '8509', 'Aparelhos eletromecânicos de motor elétrico incorporado, de uso doméstico e suas partes', '41.0'),
(972, '2104200', '85098010', 'Enceradeiras', '42.0'),
(973, '2104300', '85161000', 'Chaleiras elétricas', '43.0'),
(974, '2104400', '85164000', 'Ferros elétricos de passar', '44.0'),
(975, '2104500', '85165000', 'Fornos de micro-ondas', '45.0'),
(976, '2104600', '85166000', 'Outros fornos; fogareiros (incluídas as chapas de cocção), grelhas e assadeiras, exceto os portáteis', '46.0'),
(977, '2104700', '85166000', 'Outros fornos; fogareiros (incluídas as chapas de cocção), grelhas e assadeiras, portáteis', '47.0'),
(978, '2104800', '85167100', 'Outros aparelhos eletrotérmicos de uso doméstico - Cafeteiras', '48.0'),
(979, '2104900', '85167200', 'Outros aparelhos eletrotérmicos de uso doméstico - Torradeiras', '49.0'),
(980, '2105000', '851679', 'Outros aparelhos eletrotérmicos de uso doméstico', '50.0'),
(981, '2105100', '85169000', 'Partes das chaleiras, ferros, fornos e outros aparelhos eletrotérmicos da posição 85.16, descritos nos CEST 21.043.00, 21.044.00, 21.045.00, 21.046.00, 21.047.00, 21.048.00, 21.049.00 e 21.050.00', '51.0'),
(982, '2105200', '85171100', 'Aparelhos telefônicos por fio com unidade auscultador - microfone sem fio', '52.0'),
(983, '2105300', '8517123', 'Telefones para redes celulares, exceto por satélite, os de uso automotivo e os classificados no CEST 21.053.01', '53.0'),
(984, '2105301', '85171231', 'Telefones para redes celulares portáteis, exceto por satélite', '53.1'),
(985, '2105400', '851712', 'Outros telefones para outras redes sem fio, exceto para redes de celulares e os de uso automotivo', '54.0'),
(986, '2105500', '85171891', 'Outros aparelhos telefônicos não combinados com outros aparelhos', '55.0'),
(987, '2105501', '85171899', 'Outros aparelhos telefônicos', '55.1'),
(988, '2105600', '8517625', 'Aparelhos para transmissão ou recepção de voz, imagem ou outros dados em rede com fio, exceto os classificados nos códigos 8517.62.51, 8517.62.52 e 8517.62.53', '56.0'),
(989, '2105700', '8518', 'Microfones e seus suportes; alto-falantes, mesmo montados nos seus receptáculos, fones de ouvido (auscultadores), mesmo combinados com microfone e conjuntos ou sortidos constituídos por um microfone e um ou mais alto-falantes, amplificadores elétricos de audiofrequência, aparelhos elétricos de amplificação de som; suas partes e acessórios; exceto os de uso automotivo', '57.0'),
(990, '2105800', '8519', 'Aparelhos de radiodifusão suscetíveis de funcionarem sem fonte externa de energia. Aparelhos de gravação de som; aparelhos de reprodução de som; aparelhos de gravação e de reprodução de som; partes e acessórios; exceto os de uso automotivo', '58.0'),
(991, '2105800', '8522', 'Aparelhos de radiodifusão suscetíveis de funcionarem sem fonte externa de energia. Aparelhos de gravação de som; aparelhos de reprodução de som; aparelhos de gravação e de reprodução de som; partes e acessórios; exceto os de uso automotivo', '58.0'),
(992, '2105800', '85271', 'Aparelhos de radiodifusão suscetíveis de funcionarem sem fonte externa de energia. Aparelhos de gravação de som; aparelhos de reprodução de som; aparelhos de gravação e de reprodução de som; partes e acessórios; exceto os de uso automotivo', '58.0'),
(993, '2105900', '85198190', 'Outros aparelhos de gravação de som; aparelhos de reprodução de som; aparelhos de gravação e de reprodução de som; partes e acessórios; exceto os de uso automotivo', '59.0'),
(994, '2106000', '85219010', 'Gravador-reprodutor e editor de imagem e som, em discos, por meio magnético, óptico ou optomagnético, exceto de uso automotivo', '60.0'),
(995, '2106100', '85219090', 'Outros aparelhos videofônicos de gravação ou reprodução, mesmo incorporando um receptor de sinais videofônicos, exceto os de uso automotivo', '61.0'),
(996, '2106200', '85235110', 'Cartões de memória ("memory cards")', '62.0'),
(997, '2106300', '85235200', 'Cartões inteligentes ("smart cards")', '63.0'),
(998, '2106400', '85235200', 'Cartões inteligentes ("sim cards")', '64.0'),
(999, '2106500', '8525802', 'Câmeras fotográficas digitais e câmeras de vídeo e suas partes', '65.0'),
(1000, '2106600', '85279', 'Outros aparelhos receptores para radiodifusão, mesmo combinados num invólucro, com um aparelho de gravação ou de reprodução de som, ou com um relógio, inclusive caixa acústica para Home Theaters classificados na posição 8518', '66.0'),
(1001, '2106700', '85284929', 'Monitores e projetores que não incorporem aparelhos receptores de televisão, policromáticos', '67.0'),
(1002, '2106700', '85285920', 'Monitores e projetores que não incorporem aparelhos receptores de televisão, policromáticos', '67.0'),
(1003, '2106700', '852869', 'Monitores e projetores que não incorporem aparelhos receptores de televisão, policromáticos', '67.0'),
(1004, '2106701', '85286200', 'Projetores capazes de serem conectados diretamente a uma máquina automática para processamento de dados da posição 84.71 e concebidos para serem utilizados com esta máquina', '67.1'),
(1005, '2106800', '85285220', 'Outros monitores capazes de serem conectados diretamente a uma máquina automática para processamento de dados da posição 84.71 e concebidos para serem utilizados com esta máquina, policromáticos', '68.0'),
(1006, '2106900', '85287', 'Aparelhos receptores de televisão, mesmo que incorporem um aparelho receptor de radiodifusão ou um aparelho de gravação ou reprodução de som ou de imagens - Televisores de CRT (tubo de raios catódicos)', '69.0'),
(1007, '2107000', '85287', 'Aparelhos receptores de televisão, mesmo que incorporem um aparelho receptor de radiodifusão ou um aparelho de gravação ou reprodução de som ou de imagens - Televisores de LCD (Display de Cristal Líquido)', '70.0'),
(1008, '2107100', '85287', 'Aparelhos receptores de televisão, mesmo que incorporem um aparelho receptor de radiodifusão ou um aparelho de gravação ou reprodução de som ou de imagens - Televisores de Plasma', '71.0'),
(1009, '2107200', '85287', 'Outros aparelhos receptores de televisão não dotados de monitores ou display de vídeo', '72.0'),
(1010, '2107300', '85287', 'Outros aparelhos receptores de televisão não relacionados nos CEST 21.069.00, 21.070.00, 21.071.00 e 21.072.00', '73.0'),
(1011, '2107400', '900659', 'Câmeras fotográficas dos tipos utilizadas para preparação de clichês ou cilindros de impressão', '74.0'),
(1012, '2107500', '90064000', 'Câmeras fotográficas para filmes de revelação e copiagem instantâneas', '75.0'),
(1013, '2107600', '90189050', 'Aparelhos de diatermia', '76.0'),
(1014, '2107700', '90191000', 'Aparelhos de massagem', '77.0'),
(1015, '2107800', '90328911', 'Reguladores de voltagem eletrônicos', '78.0'),
(1016, '2107900', '95045000', 'Consoles e máquinas de jogos de vídeo, exceto os classificados na subposição 9504.30', '79.0'),
(1017, '2108000', '8517621', 'Multiplexadores e concentradores', '80.0'),
(1018, '2108100', '85176222', 'Centrais automáticas privadas, de capacidade inferior ou igual a 25 ramais', '81.0'),
(1019, '2108200', '85176239', 'Outros aparelhos para comutação', '82.0'),
(1020, '2108300', '8517624', 'Roteadores digitais, em redes com ou sem fio', '83.0'),
(1021, '2108400', '85176262', 'Aparelhos emissores com receptor incorporado de sistema troncalizado (“trunking”), de tecnologia celular', '84.0'),
(1022, '2108500', '8517629', 'Outros aparelhos de recepção, conversão e transmissão ou regeneração de voz, imagens ou outros dados, incluindo os aparelhos de comutação e roteamento', '85.0'),
(1023, '2108600', '85177021', 'Antenas próprias para telefones celulares portáteis, exceto as telescópicas', '86.0'),
(1024, '2108700', '821490', 'Aparelhos ou máquinas de barbear, máquinas de cortar o cabelo ou de tosquiar e aparelhos de depilar, e suas partes', '87.0'),
(1025, '2108700', '8510', 'Aparelhos ou máquinas de barbear, máquinas de cortar o cabelo ou de tosquiar e aparelhos de depilar, e suas partes', '87.0'),
(1026, '2108800', '84145', 'Ventiladores, exceto os de uso agrícola', '88.0'),
(1027, '2108900', '84145990', 'Ventiladores de uso agrícola', '89.0'),
(1028, '2109000', '84146000', 'Coifas com dimensão horizontal máxima não superior a 120 cm', '90.0'),
(1029, '2109100', '84149020', 'Partes de ventiladores ou coifas aspirantes', '91.0'),
(1030, '2109200', '841510', 'Máquinas e aparelhos de ar condicionado contendo um ventilador motorizado e dispositivos próprios para modificar a temperatura e a umidade, incluídos as máquinas e aparelhos em que a umidade não seja regulável separadamente', '92.0'),
(1031, '2109200', '84158', 'Máquinas e aparelhos de ar condicionado contendo um ventilador motorizado e dispositivos próprios para modificar a temperatura e a umidade, incluídos as máquinas e aparelhos em que a umidade não seja regulável separadamente', '92.0'),
(1032, '2109300', '84151011', 'Aparelhos de ar-condicionado tipo Split System (sistema com elementos separados) com unidade externa e interna', '93.0'),
(1033, '2109400', '84151019', 'Aparelhos de ar-condicionado com capacidade inferior ou igual a 30.000 frigorias/hora', '94.0'),
(1034, '2109500', '84151090', 'Aparelhos de ar-condicionado com capacidade acima de 30.000 frigorias/hora', '95.0'),
(1035, '2109600', '84159010', 'Unidades evaporadoras (internas) de aparelho de ar-condicionado do tipo Split System (sistema com elementos separados), com capacidade inferior ou igual a 30.000 frigorias/hora', '96.0'),
(1036, '2109700', '84159020', 'Unidades condensadoras (externas) de aparelho de ar-condicionado do tipo Split System (sistema com elementos separados), com capacidade inferior ou igual a 30.000 frigorias/hora', '97.0'),
(1037, '2109800', '84212100', 'Aparelhos elétricos para filtrar ou depurar água (purificadores de água refrigerados), exceto os itens classificados no CEST 21.098.01', '98.0'),
(1038, '2109801', '84212100', 'Outros aparelhos elétricos para filtrar ou depurar água', '98.1'),
(1039, '2109900', '84243010', 'Lavadora de alta pressão e suas partes', '99.0'),
(1040, '2109900', '84243090', 'Lavadora de alta pressão e suas partes', '99.0'),
(1041, '2109900', '84249090', 'Lavadora de alta pressão e suas partes', '99.0'),
(1042, '2110000', '84672100', 'Furadeiras elétricas', '100.0'),
(1043, '2110100', '85162', 'Aparelhos elétricos para aquecimento de ambientes', '101.0'),
(1044, '2110200', '85163100', 'Secadores de cabelo', '102.0'),
(1045, '2110300', '85163200', 'Outros aparelhos para arranjos do cabelo', '103.0'),
(1046, '2110400', '8527', 'Aparelhos receptores para radiodifusão, mesmo combinados num mesmo invólucro, com um aparelho de gravação ou de reprodução de som, ou com um relógio, exceto os classificados na posição 8527.1, 8527.2 e 8527.9 que sejam de uso automotivo', '104.0'),
(1047, '2110500', '84796000', 'Climatizadores de ar', '105.0'),
(1048, '2110600', '84159090', 'Outras partes para máquinas e aparelhos de ar-condicionado que contenham um ventilador motorizado e dispositivos próprios para modificar a temperatura e a umidade, incluindo as máquinas e aparelhos em que a umidade não seja regulável separadamente', '106.0'),
(1049, '2110700', '85258019', 'Câmeras de televisão e suas partes', '107.0'),
(1050, '2110800', '84231000', 'Balanças de uso doméstico', '108.0'),
(1051, '2110900', '8540', 'Tubos e válvulas, eletrônicos, de cátodo quente, cátodo frio ou fotocátodo (por exemplo, tubos e válvulas, de vácuo, de vapor ou de gás, ampolas retificadoras de vapor de mercúrio, tubos catódicos, tubos e válvulas para câmeras de televisão)', '109.0'),
(1052, '2111000', '8517', 'Aparelhos elétricos para telefonia; outros aparelhos para transmissão ou recepção de voz, imagens ou outros dados, incluídos os aparelhos para comunicação em redes por fio ou redes sem fio (tal como uma rede local (LAN) ou uma rede de área estendida (WAN), incluídas suas partes, exceto os de uso automotivo e os classificados nos códigos 8517.62.51, 8517.62.52 e 8517.62.53', '110.0'),
(1053, '2111100', '8517', 'Interfones, seus acessórios, tomadas e “plugs”', '111.0'),
(1054, '2111200', '8529', 'Partes reconhecíveis como exclusiva ou principalmente destinadas aos aparelhos das posições 8525 a 8528; exceto as de uso automotivo', '112.0'),
(1055, '2111300', '8531', 'Aparelhos elétricos de sinalização acústica ou visual (por exemplo, campainhas, sirenes, quadros indicadores, aparelhos de alarme para proteção contra roubo ou incêndio); exceto os de uso automotivo e os classificados nas posições 8531.10 e 8531.80.00.', '113.0'),
(1056, '2111400', '853110', 'Aparelhos elétricos de alarme, para proteção contra roubo ou incêndio e aparelhos semelhantes, exceto os de uso automotivo', '114.0'),
(1057, '2111500', '85318000', 'Outros aparelhos de sinalização acústica ou visual, exceto os de uso automotivo', '115.0'),
(1058, '2111600', '853400', 'Circuitos impressos, exceto os de uso automotivo', '116.0'),
(1059, '2111700', '85414011', 'Diodos emissores de luz (LED), exceto diodos “laser”', '117.0'),
(1060, '2111700', '85414021', 'Diodos emissores de luz (LED), exceto diodos “laser”', '117.0'),
(1061, '2111700', '85414022', 'Diodos emissores de luz (LED), exceto diodos “laser”', '117.0'),
(1062, '2111800', '85437092', 'Eletrificadores de cercas eletrônicos', '118.0'),
(1063, '2111900', '90303', 'Aparelhos e instrumentos para medida ou controle da tensão, intensidade, resistência ou da potência, sem dispositivo registrador; exceto os de uso automotivo', '119.0'),
(1064, '2112000', '903089', 'Analisadores lógicos de circuitos digitais, de espectro de frequência, frequencímetros, fasímetros, e outros instrumentos e aparelhos de controle de grandezas elétricas e detecção', '120.0'),
(1065, '2112100', '910700', 'Interruptores horários e outros aparelhos que permitam acionar um mecanismo em tempo determinado, munidos de maquinismo de aparelhos de relojoaria ou de motor síncrono', '121.0'),
(1066, '2112200', '9405', 'Aparelhos de iluminação (incluídos os projetores) e suas partes, não especificados nem compreendidos em outras posições; anúncios, cartazes ou tabuletas e placas indicadoras luminosos, e artigos semelhantes, contendo uma fonte luminosa fixa permanente, e suas partes não especificadas nem compreendidas em outras posições, com exceção dos itens classificados nos CEST 21.123.00, 21.124.00 e 21.125.00', '122.0'),
(1067, '2112300', '940510', 'Lustres e outros aparelhos elétricos de iluminação, próprios para serem suspensos ou fixados no teto ou na parede, exceto os dos tipos utilizados na iluminação pública; e suas partes', '123.0'),
(1068, '2112300', '94059', 'Lustres e outros aparelhos elétricos de iluminação, próprios para serem suspensos ou fixados no teto ou na parede, exceto os dos tipos utilizados na iluminação pública; e suas partes', '123.0'),
(1069, '2112400', '94052000', 'Abajures de cabeceiras, de escritório e lampadários de interior, elétricos e suas partes', '124.0'),
(1070, '2112400', '94059', 'Abajures de cabeceiras, de escritório e lampadários de interior, elétricos e suas partes', '124.0'),
(1071, '2112500', '940540', 'Outros aparelhos elétricos de iluminação e suas partes', '125.0'),
(1072, '2112500', '94059', 'Outros aparelhos elétricos de iluminação e suas partes', '125.0'),
(1073, '2112600', '85423190', 'Microprocessador', '126.0'),
(1074, '2200100', '2309', 'Ração tipo “pet” para animais domésticos', '1.0'),
(1075, '2300100', '210500', 'Sorvetes de qualquer espécie', '1.0'),
(1076, '2300200', '1806', 'Preparados para fabricação de sorvete em máquina', '2.0'),
(1077, '2300200', '1901', 'Preparados para fabricação de sorvete em máquina', '2.0'),
(1078, '2300200', '2106', 'Preparados para fabricação de sorvete em máquina', '2.0'),
(1079, '2400100', '3208', 'Tintas, vernizes', '1.0'),
(1080, '2400100', '3209', 'Tintas, vernizes', '1.0'),
(1081, '2400100', '321000', 'Tintas, vernizes', '1.0'),
(1082, '2400200', '2821', 'Xadrez e pós assemelhados, exceto pigmentos à base de dióxido de titânio classificados no código 3206.11.19', '2.0'),
(1083, '2400200', '32041700', 'Xadrez e pós assemelhados, exceto pigmentos à base de dióxido de titânio classificados no código 3206.11.19', '2.0'),
(1084, '2400200', '3206', 'Xadrez e pós assemelhados, exceto pigmentos à base de dióxido de titânio classificados no código 3206.11.19', '2.0'),
(1085, '2400300', '3204', 'Corantes para aplicação em bases, tintas e vernizes', '3.0'),
(1086, '2400300', '32050000', 'Corantes para aplicação em bases, tintas e vernizes', '3.0'),
(1087, '2400300', '3206', 'Corantes para aplicação em bases, tintas e vernizes', '3.0'),
(1088, '2400300', '3212', 'Corantes para aplicação em bases, tintas e vernizes', '3.0'),
(1089, '2500100', '87021000', 'Veículos automóveis para transporte de 10 pessoas ou mais, incluindo o motorista, unicamente com motor de pistão, de ignição por compressão (diesel ou semidiesel), com volume interno de habitáculo, destinado a passageiros e motorista, superior a 6 m³, mas inferior a 9 m³', '1.0'),
(1090, '2500200', '87024090', 'Veículos automóveis para transporte de 10 pessoas ou mais, incluindo o motorista, unicamente com motor elétrico para propulsão, com volume interno de habitáculo, destinado a passageiros e motorista, superior a 6 m³, mas inferior a 9 m³', '2.0'),
(1091, '2500300', '87032100', 'Automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada não superior a 1000 cm³', '3.0'),
(1092, '2500400', '87032210', 'Automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada superior a 1000 cm³, mas não superior a 1500 cm³, com capacidade de transporte de pessoas sentadas inferior ou igual a 6, incluído o condutor, exceto carro celular', '4.0'),
(1093, '2500500', '87032290', 'Outros automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada superior a 1000 cm³, mas não superior a 1500 cm³, exceto carro celular', '5.0'),
(1094, '2500600', '87032310', 'Automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada superior a 1500 cm³, mas não superior a 3000 cm³, com capacidade de transporte de pessoas sentadas inferior ou igual a 6, incluído o condutor, exceto carro celular, carro funerário e automóveis de corrida', '6.0'),
(1095, '2500700', '87032390', 'Outros automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada superior a 1500 cm³, mas não superior a 3000 cm³, exceto carro celular, carro funerário e automóveis de corrida', '7.0'),
(1096, '2500800', '87032410', 'Automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada superior a 3000 cm³, com capacidade de transporte de pessoas sentadas inferior ou igual a 6, incluído o condutor, exceto carro celular, carro funerário e automóveis de corrida', '8.0'),
(1097, '2500900', '87032490', 'Outros automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada superior a 3000 cm³, exceto carro celular, carro funerário e automóveis de corrida', '9.0'),
(1098, '2501000', '87033210', 'Automóveis unicamente com motor diesel ou semidiesel, de cilindrada superior a 1500 cm³, mas não superior a 2500 cm³, com capacidade de transporte de pessoas sentadas inferior ou igual a 6, incluído o condutor, exceto ambulância, carro celular e carro funerário', '10.0'),
(1099, '2501100', '87033290', 'Outros automóveis unicamente com motor diesel ou semidiesel, de cilindrada superior a 1500 cm³, mas não superior a 2500 cm³, exceto ambulância, carro celular e carro funerário', '11.0'),
(1100, '2501200', '87033310', 'Automóveis unicamente com motor diesel ou semidiesel, de cilindrada superior a 2500 cm³, com capacidade de transporte de pessoas sentadas inferior ou igual a 6, incluído o condutor, exceto carro celular e carro funerário', '12.0'),
(1101, '2501300', '87033390', 'Outros automóveis unicamente com motor diesel ou semidiesel, de cilindrada superior a 2500 cm³, exceto carro celular e carro funerário', '13.0'),
(1102, '2501400', '87042110', 'Veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, chassis com motor diesel ou semidiesel e cabina, exceto caminhão de peso em carga máxima superior a 3,9 toneladas', '14.0'),
(1103, '2501500', '87042120', 'Veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, com motor diesel ou semidiesel, com caixa basculante, exceto caminhão de peso em carga máxima superior a 3,9 toneladas', '15.0'),
(1104, '2501600', '87042130', 'Veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, frigoríficos ou isotérmicos, com motor diesel ou semidiesel, exceto caminhão de peso em carga máxima superior a 3,9 toneladas', '16.0'),
(1105, '2501700', '87042190', 'Outros veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, com motor diesel ou semidiesel, exceto carro-forte para transporte de valores e caminhão de peso em carga máxima superior a 3,9 toneladas', '17.0'),
(1106, '2501800', '87043110', 'Veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, com motor a explosão, chassis e cabina, exceto caminhão de peso em carga máxima superior a 3,9 toneladas', '18.0'),
(1107, '2501900', '87043120', 'Veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, com motor explosão com caixa basculante, exceto caminhão de peso em carga máxima superior a 3,9 toneladas', '19.0'),
(1108, '2502000', '87043130', 'Veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, frigoríficos ou isotérmicos com motor explosão, exceto caminhão de peso em carga máxima superior a 3,9 toneladas', '20.0'),
(1109, '2502100', '87043190', 'Outros veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, com motor a explosão, exceto carro-forte para transporte de valores e caminhão de peso em carga máxima superior a 3,9 toneladas', '21.0'),
(1110, '2502200', '87022000', 'Veículos automóveis para transporte de 10 pessoas ou mais, incluindo o motorista, com motor de pistão, de ignição por compressão (diesel ou semidiesel) e um motor elétrico, com volume interno de habitáculo, destinado a passageiros e motorista, superior a 6 m³, mas inferior a 9 m³', '22.0'),
(1111, '2502300', '87023000', 'Veículos automóveis para transporte de 10 pessoas ou mais, incluindo o motorista, com motor de pistão alternativo, de ignição por centelha (faísca) e um motor elétrico, com volume interno de habitáculo, destinado a passageiros e motorista, superior a 6 m³, mas inferior a 9 m³', '23.0'),
(1112, '2502400', '87029000', 'Outros veículos automóveis para transporte de 10 pessoas ou mais, incluindo o motorista, com volume interno de habitáculo, destinado a passageiros e motorista, superior a 6 m³, mas inferior a 9 m³', '24.0'),
(1113, '2502500', '87034000', 'Automóveis equipados para propulsão, simultaneamente, com um motor de pistão alternativo de ignição por centelha (faísca*) e um motor elétrico, exceto os suscetíveis de serem carregados por conexão a uma fonte externa de energia elétrica, o carro celular e o carro funerário', '25.0'),
(1114, '2502600', '87035000', 'Automóveis equipados para propulsão, simultaneamente, com um motor de pistão por compressão (diesel ou semidiesel) e um motor elétrico, exceto os suscetíveis de serem carregados por conexão a uma fonte externa de energia elétrica, exceto o carro celular e o carro funerário', '26.0'),
(1115, '2502700', '87036000', 'Automóveis equipados para propulsão, simultaneamente, com um motor de pistão alternativo de ignição por centelha (faísca*) e um motor elétrico, suscetíveis de serem carregados por conexão a uma fonte externa de energia elétrica, exceto o carro celular e o carro funerário', '27.0'),
(1116, '2502800', '87037000', 'Automóveis equipados para propulsão, simultaneamente, com um motor de pistão por compressão (diesel ou semidiesel) e um motor elétrico, suscetíveis de serem carregados por conexão a uma fonte externa de energia elétrica, exceto o carro celular e o carro funerário', '28.0'),
(1117, '2502900', '87038000', 'Outros veículos, equipados unicamente com motor elétrico para propulsão', '29.0'),
(1118, '2600100', '8711', 'Motocicletas (incluídos os ciclomotores) e outros ciclos equipados com motor auxiliar, mesmo com carro lateral; carros laterais', '1.0'),
(1119, '2800100', '33030010', 'Perfumes (extratos)', '1.0'),
(1120, '2800200', '33030020', 'Águas-de-colônia', '2.0'),
(1121, '2800300', '33041000', 'Produtos de maquiagem para os lábios', '3.0'),
(1122, '2800400', '33042010', 'Sombra, delineador, lápis para sobrancelhas e rímel', '4.0'),
(1123, '2800500', '33042090', 'Outros produtos de maquiagem para os olhos', '5.0'),
(1124, '2800600', '33043000', 'Preparações para manicuros e pedicuros', '6.0'),
(1125, '2800700', '33049100', 'Pós para maquiagem, incluindo os compactos', '7.0'),
(1126, '2800800', '33049910', 'Cremes de beleza, cremes nutritivos e loções tônicas', '8.0'),
(1127, '2800900', '33049990', 'Outros produtos de beleza ou de maquiagem preparados e preparações para conservação ou cuidados da pele, exceto as preparações antissolares e os bronzeadores', '9.0'),
(1128, '2801000', '33049990', 'Preparações antissolares e os bronzeadores', '10.0'),
(1129, '2801100', '33051000', 'Xampus para o cabelo', '11.0'),
(1130, '2801200', '33052000', 'Preparações para ondulação ou alisamento, permanentes, dos cabelos', '12.0'),
(1131, '2801300', '33059000', 'Outras preparações capilares', '13.0'),
(1132, '2801400', '33059000', 'Tintura para o cabelo', '14.0'),
(1133, '2801500', '33071000', 'Preparações para barbear (antes, durante ou após)', '15.0'),
(1134, '2801600', '33072010', 'Desodorantes corporais e antiperspirantes, líquidos', '16.0'),
(1135, '2801700', '33072090', 'Outros desodorantes corporais e antiperspirantes', '17.0'),
(1136, '2801800', '33079000', 'Outros produtos de perfumaria ou de toucador preparados', '18.0'),
(1137, '2801900', '33079000', 'Outras preparações cosméticas', '19.0'),
(1138, '2802000', '34011190', 'Sabões de toucador, em barras, pedaços ou figuras moldadas', '20.0'),
(1139, '2802100', '34011900', 'Outros sabões, produtos e preparações orgânicos tensoativos, inclusive papel, pastas (ouates), feltros e falsos tecidos, impregnados, revestidos ou recobertos de sabão ou de detergentes', '21.0'),
(1140, '2802200', '34012010', 'Sabões de toucador sob outras formas', '22.0'),
(1141, '2802300', '34013000', 'Produtos e preparações orgânicos tensoativos para lavagem da pele, em forma de líquido ou de creme, acondicionados para venda a retalho, mesmo contendo sabão', '23.0'),
(1142, '2802400', '48182000', 'Lenços de papel, incluindo os de desmaquiar', '24.0'),
(1143, '2802401', '48182000', 'Toalhas de mão', '24.1'),
(1144, '2802500', '82141000', 'Apontadores de lápis para maquiagem', '25.0'),
(1145, '2802501', '82141000', 'Espátulas, abre-cartas e raspadeiras', '25.1'),
(1146, '2802502', '82141000', 'Lâminas de espátulas, de abre-cartas, de raspadeiras e de apontadores de lápis', '25.2'),
(1147, '2802600', '82142000', 'Utensílios e sortidos de utensílios de manicuros ou de pedicuros (incluindo as limas para unhas)', '26.0'),
(1148, '2802700', '96032900', 'Escovas e pincéis de barba, escovas para cabelos, para cílios ou para unhas e outras escovas de toucador de pessoas', '27.0'),
(1149, '2802701', '96032900', 'Vassouras e escovas, mesmo constituindo partes de máquinas, de aparelhos ou de veículos, vassouras mecânicas de uso manual não motorizadas, pincéis e espanadores; cabeças preparadas para escovas, pincéis e artigos semelhantes; bonecas e rolos para pintura; rodos de borracha ou de matérias flexíveis semelhantes, outros', '27.1'),
(1150, '2802800', '96033000', 'Pincéis para aplicação de produtos cosméticos', '28.0'),
(1151, '2802801', '96033000', 'Pincéis e escovas, para artistas e pincéis de escrever', '28.1'),
(1152, '2802900', '96161000', 'Vaporizadores de toucador, suas armações e cabeças de armações', '29.0'),
(1153, '2803000', '96162000', 'Borlas ou esponjas para pós ou para aplicação de outros cosméticos ou de produtos de toucador', '30.0'),
(1154, '2803100', '42021', 'Malas e maletas de toucador', '31.0'),
(1155, '2803200', '9615', 'Pentes, travessas para cabelo e artigos semelhantes; grampos (alfinetes) para cabelo; pinças (“pinceguiches”), onduladores, bobs (rolos) e artefatos semelhantes para penteados, e suas partes', '32.0'),
(1156, '2803300', '39233000', 'Mamadeiras', '33.0'),
(1157, '2803300', '39241000', 'Mamadeiras', '33.0'),
(1158, '2803300', '39249000', 'Mamadeiras', '33.0'),
(1159, '2803300', '40149090', 'Mamadeiras', '33.0'),
(1160, '2803300', '70102000', 'Mamadeiras', '33.0'),
(1161, '2803400', '40149090', 'Chupetas e bicos para mamadeiras e para chupetas', '34.0'),
(1162, '2803500', '12119090', 'Outras plantas e partes, para perfumaria, medicina e semelhantes', '35.0'),
(1163, '2803600', '39262000', 'Vestuário e seus acessórios, de plásticos, inclusive luvas', '36.0'),
(1164, '2803700', '39264000', 'Estatuetas e outros objetos de ornamentação, de plásticos', '37.0'),
(1165, '2803800', '39269090', 'Outras obras de plásticos', '38.0'),
(1166, '2803900', '42022210', 'Bolsas de folhas de plástico', '39.0'),
(1167, '2804000', '42022220', 'Bolsas de matérias têxteis', '40.0'),
(1168, '2804100', '42022900', 'Bolsas de outras matérias', '41.0'),
(1169, '2804200', '42023900', 'Artigos de bolsos/bolsas, de outras matérias', '42.0'),
(1170, '2804300', '42029200', 'Outros artefatos, de folhas de plásticos ou matérias têxteis', '43.0'),
(1171, '2804400', '42029900', 'Outros artefatos, de outras matérias', '44.0'),
(1172, '2804500', '48192000', 'Caixas e cartonagens, dobráveis, de papel/cartão, não ondulados', '45.0'),
(1173, '2804600', '48194000', 'Outros sacos, bolsas e cartuchos, de papel ou cartão', '46.0'),
(1174, '2804700', '48211000', 'Etiquetas de papel ou cartão, impressas', '47.0'),
(1175, '2804800', '49111090', 'Outros impressos publicitários, catálogos comerciais e semelhantes', '48.0'),
(1176, '2804900', '61159900', 'Outras meias de malha de outras matérias têxteis', '49.0'),
(1177, '2805000', '62171000', 'Outros acessórios confeccionados, de vestuário', '50.0'),
(1178, '2805100', '63026000', 'Roupas de toucador/cozinha, de tecidos atoalhados de algodão', '51.0'),
(1179, '2805200', '63079090', 'Outros artefatos têxteis confeccionados', '52.0'),
(1180, '2805300', '65069900', 'Chapéus e outros artefatos de outras matérias, exceto de malha', '53.0'),
(1181, '2805400', '95059000', 'Artigos para outras festas, carnaval ou outros divertimentos', '54.0'),
(1182, '2805500', '33', 'Produtos destinados à higiene bucal', '55.0'),
(1183, '2805600', '33', 'Outros produtos cosméticos e de higiene pessoal não relacionados em outros itens deste anexo', '56.0'),
(1184, '2805600', '34', 'Outros produtos cosméticos e de higiene pessoal não relacionados em outros itens deste anexo', '56.0'),
(1185, '2805700', '14', 'Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo', '57.0'),
(1186, '2805700', '39', 'Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo', '57.0'),
(1187, '2805700', '40', 'Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo', '57.0'),
(1188, '2805700', '44', 'Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo', '57.0'),
(1189, '2805700', '48', 'Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo', '57.0'),
(1190, '2805700', '63', 'Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo', '57.0'),
(1191, '2805700', '65', 'Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo', '57.0'),
(1192, '2805700', '67', 'Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo', '57.0'),
(1193, '2805700', '70', 'Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo', '57.0'),
(1194, '2805700', '82', 'Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo', '57.0'),
(1195, '2805700', '90', 'Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo', '57.0'),
(1196, '2805700', '96', 'Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo', '57.0'),
(1197, '2805800', '39', 'Acessórios (por exemplo, bijuterias, relógios, óculos de sol, bolsas, mochilas, frasqueiras, carteiras, porta-cartões, porta-documentos, porta-celulares e embalagens presenteáveis (por exemplo, caixinhas de papel), entre outros itens assemelhados)', '58.0'),
(1198, '2805800', '42', 'Acessórios (por exemplo, bijuterias, relógios, óculos de sol, bolsas, mochilas, frasqueiras, carteiras, porta-cartões, porta-documentos, porta-celulares e embalagens presenteáveis (por exemplo, caixinhas de papel), entre outros itens assemelhados)', '58.0'),
(1199, '2805800', '48', 'Acessórios (por exemplo, bijuterias, relógios, óculos de sol, bolsas, mochilas, frasqueiras, carteiras, porta-cartões, porta-documentos, porta-celulares e embalagens presenteáveis (por exemplo, caixinhas de papel), entre outros itens assemelhados)', '58.0'),
(1200, '2805800', '90', 'Acessórios (por exemplo, bijuterias, relógios, óculos de sol, bolsas, mochilas, frasqueiras, carteiras, porta-cartões, porta-documentos, porta-celulares e embalagens presenteáveis (por exemplo, caixinhas de papel), entre outros itens assemelhados)', '58.0'),
(1201, '2805800', '91', 'Acessórios (por exemplo, bijuterias, relógios, óculos de sol, bolsas, mochilas, frasqueiras, carteiras, porta-cartões, porta-documentos, porta-celulares e embalagens presenteáveis (por exemplo, caixinhas de papel), entre outros itens assemelhados)', '58.0'),
(1202, '2805900', '61', 'Vestuário e seus acessórios; calçados, polainas e artefatos semelhantes, e suas partes', '59.0'),
(1203, '2805900', '62', 'Vestuário e seus acessórios; calçados, polainas e artefatos semelhantes, e suas partes', '59.0'),
(1204, '2805900', '64', 'Vestuário e seus acessórios; calçados, polainas e artefatos semelhantes, e suas partes', '59.0'),
(1205, '2806000', '42', 'Outros artigos de vestuário em geral, exceto os relacionados no item anterior', '60.0'),
(1206, '2806000', '52', 'Outros artigos de vestuário em geral, exceto os relacionados no item anterior', '60.0'),
(1207, '2806000', '55', 'Outros artigos de vestuário em geral, exceto os relacionados no item anterior', '60.0'),
(1208, '2806000', '58', 'Outros artigos de vestuário em geral, exceto os relacionados no item anterior', '60.0'),
(1209, '2806000', '63', 'Outros artigos de vestuário em geral, exceto os relacionados no item anterior', '60.0'),
(1210, '2806000', '65', 'Outros artigos de vestuário em geral, exceto os relacionados no item anterior', '60.0'),
(1211, '2806100', '39', 'Artigos de casa', '61.0'),
(1212, '2806100', '40', 'Artigos de casa', '61.0'),
(1213, '2806100', '52', 'Artigos de casa', '61.0'),
(1214, '2806100', '56', 'Artigos de casa', '61.0'),
(1215, '2806100', '62', 'Artigos de casa', '61.0'),
(1216, '2806100', '63', 'Artigos de casa', '61.0'),
(1217, '2806100', '66', 'Artigos de casa', '61.0'),
(1218, '2806100', '69', 'Artigos de casa', '61.0'),
(1219, '2806100', '70', 'Artigos de casa', '61.0'),
(1220, '2806100', '73', 'Artigos de casa', '61.0'),
(1221, '2806100', '76', 'Artigos de casa', '61.0'),
(1222, '2806100', '82', 'Artigos de casa', '61.0'),
(1223, '2806100', '83', 'Artigos de casa', '61.0'),
(1224, '2806100', '84', 'Artigos de casa', '61.0'),
(1225, '2806100', '91', 'Artigos de casa', '61.0'),
(1226, '2806100', '94', 'Artigos de casa', '61.0'),
(1227, '2806100', '96', 'Artigos de casa', '61.0'),
(1228, '2806200', '13', 'Produtos das indústrias alimentares e bebidas', '62.0'),
(1229, '2806200', '15', 'Produtos das indústrias alimentares e bebidas', '62.0'),
(1230, '2806200', '23', 'Produtos das indústrias alimentares e bebidas', '62.0'),
(1231, '2806300', '22', 'Produtos de limpeza e conservação doméstica', '63.0'),
(1232, '2806300', '27', 'Produtos de limpeza e conservação doméstica', '63.0'),
(1233, '2806300', '28', 'Produtos de limpeza e conservação doméstica', '63.0'),
(1234, '2806300', '29', 'Produtos de limpeza e conservação doméstica', '63.0'),
(1235, '2806300', '33', 'Produtos de limpeza e conservação doméstica', '63.0'),
(1236, '2806300', '34', 'Produtos de limpeza e conservação doméstica', '63.0'),
(1237, '2806300', '35', 'Produtos de limpeza e conservação doméstica', '63.0'),
(1238, '2806300', '38', 'Produtos de limpeza e conservação doméstica', '63.0'),
(1239, '2806300', '39', 'Produtos de limpeza e conservação doméstica', '63.0'),
(1240, '2806300', '63', 'Produtos de limpeza e conservação doméstica', '63.0'),
(1241, '2806300', '68', 'Produtos de limpeza e conservação doméstica', '63.0'),
(1242, '2806300', '73', 'Produtos de limpeza e conservação doméstica', '63.0'),
(1243, '2806300', '84', 'Produtos de limpeza e conservação doméstica', '63.0'),
(1244, '2806300', '85', 'Produtos de limpeza e conservação doméstica', '63.0'),
(1245, '2806300', '96', 'Produtos de limpeza e conservação doméstica', '63.0'),
(1246, '2806400', '39', 'Artigos infantis', '64.0'),
(1247, '2806400', '49', 'Artigos infantis', '64.0'),
(1248, '2806400', '95', 'Artigos infantis', '64.0'),
(1249, '2806400', '96', 'Artigos infantis', '64.0'),
(1250, '2899900', 'NT', 'Outros produtos comercializados pelo sistema de marketing direto porta-a-porta a consumidor final não relacionados em outros itens deste anexo', '999.0'),
(1251, '0104400', '84311010', 'Partes para macacos do CEST 01.043.00', '44.0'),
(1252, '2806200', '16', 'Produtos das indústrias alimentares e bebidas', '62.0'),
(1253, '2806200', '17', 'Produtos das indústrias alimentares e bebidas', '62.0'),
(1254, '2806200', '18', 'Produtos das indústrias alimentares e bebidas', '62.0'),
(1255, '2806200', '19', 'Produtos das indústrias alimentares e bebidas', '62.0'),
(1256, '2806200', '20', 'Produtos das indústrias alimentares e bebidas', '62.0'),
(1257, '2806200', '21', 'Produtos das indústrias alimentares e bebidas', '62.0'),
(1258, '2806200', '22', 'Produtos das indústrias alimentares e bebidas', '62.0'),
(1259, '0302400', '22011000', 'Água mineral em embalagens retornáveis com capacidade igual ou superior a 10 (dez) e inferior a 20 (vinte) litros', '24.0'),
(1260, '0302500', '22011000', 'Água mineral em embalagens retornáveis com capacidade igual ou superior a 20 (vinte) litros', '25.0');
```


## Tabela CEST 2018 em SQL para Firebird

  - Estrutura: cest, ncm, descricao

```
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0100100','38151210','Catalisadores em colmeia cerâmica ou metálica para conversão catalítica de gases de escape de veículos e outros catalisadores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0100100','38151290','Catalisadores em colmeia cerâmica ou metálica para conversão catalítica de gases de escape de veículos e outros catalisadores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0100200','3917','Tubos e seus acessórios (por exemplo, juntas, cotovelos, flanges, uniões), de plásticos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0100300','39181000','Protetores de caçamba');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0100400','39233000','Reservatórios de óleo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0100500','39263000','Frisos, decalques, molduras e acabamentos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0100600','40103','Correias de transmissão de borracha vulcanizada, de matérias têxteis, mesmo impregnadas, revestidas ou recobertas, de plástico, ou estratificadas com plástico ou reforçadas com metal ou com outras matérias');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0100600','59100000','Correias de transmissão de borracha vulcanizada, de matérias têxteis, mesmo impregnadas, revestidas ou recobertas, de plástico, ou estratificadas com plástico ou reforçadas com metal ou com outras matérias');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0100700','40169300','Juntas, gaxetas e outros elementos com função semelhante de vedação');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0100700','4823909','Juntas, gaxetas e outros elementos com função semelhante de vedação');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0100800','40161010','Partes de veículos automóveis, tratores e máquinas autopropulsadas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0100900','40169990','Tapetes, revestimentos, mesmo confeccionados, batentes, buchas e coxins');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0100900','57050000','Tapetes, revestimentos, mesmo confeccionados, batentes, buchas e coxins');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0101000','59039000','Tecidos impregnados, revestidos, recobertos ou estratificados, com plástico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0101100','59090000','Mangueiras e tubos semelhantes, de matérias têxteis, mesmo com reforço ou acessórios de outras matérias');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0101200','63061','Encerados e toldos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0101300','65061000','Capacetes e artefatos de uso semelhante, de proteção, para uso em motocicletas, incluídos ciclomotores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0101400','6813','Guarnições de fricção (por exemplo, placas, rolos, tiras, segmentos, discos, anéis, pastilhas), não montadas, para freios, embreagens ou qualquer outro mecanismo de fricção, à base de amianto, de outras substâncias minerais ou de celulose, mesmo combinadas com têxteis ou outras matérias');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0101500','70071100','Vidros de dimensões e formatos que permitam aplicação automotiva');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0101500','70072100','Vidros de dimensões e formatos que permitam aplicação automotiva');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0101600','70091000','Espelhos retrovisores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0101700','70140000','Lentes de faróis, lanternas e outros utensílios');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0101800','73110000','Cilindro de aço para GNV (gás natural veicular)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0101900','73110000','Recipientes para gases comprimidos ou liquefeitos, de ferro fundido, ferro ou aço, exceto o descrito no item 18.0');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0102000','7320','Molas e folhas de molas, de ferro ou aço');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0102100','7325','Obras moldadas, de ferro fundido, ferro ou aço, exceto as do código 7325.91.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0102200','780600','Peso de chumbo para balanceamento de roda');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0102300','80070090','Peso para balanceamento de roda e outros utensílios de estanho');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0102400','830120','Fechaduras e partes de fechaduras');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0102400','830160','Fechaduras e partes de fechaduras');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0102500','830170','Chaves apresentadas isoladamente');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0102600','83021000','Dobradiças, guarnições, ferragens e artigos semelhantes de metais comuns');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0102600','83023000','Dobradiças, guarnições, ferragens e artigos semelhantes de metais comuns');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0102700','831000','Triângulo de segurança');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0102800','84073','Motores de pistão alternativo dos tipos utilizados para propulsão de veículos do Capítulo 87');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0102900','840820','Motores dos tipos utilizados para propulsão de veículos automotores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0103000','84099','Partes reconhecíveis como exclusiva ou principalmente destinadas aos motores das posições 8407 ou 8408');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0103100','84122','Motores hidráulicos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0103200','841330','Bombas para combustíveis, lubrificantes ou líquidos de arrefecimento, próprias para motores de ignição por centelha ou por compressão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0103300','84141000','Bombas de vácuo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0103400','8414801','Compressores e turbocompressores de ar');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0103400','8414802','Compressores e turbocompressores de ar');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0103500','84139190','Partes das bombas, compressores e turbocompressores dos CEST 01.032.00, 01.033.00 e 01.034.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0103500','84149010','Partes das bombas, compressores e turbocompressores dos CEST 01.032.00, 01.033.00 e 01.034.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0103500','8414903','Partes das bombas, compressores e turbocompressores dos CEST 01.032.00, 01.033.00 e 01.034.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0103500','8414909','Partes das bombas, compressores e turbocompressores dos CEST 01.032.00, 01.033.00 e 01.034.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0103600','841520','Máquinas e aparelhos de ar condicionado');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0103700','84212300','Aparelhos para filtrar óleos minerais nos motores de ignição por centelha ou por compressão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0103800','84212990','Filtros a vácuo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0103900','84219','Partes dos aparelhos para filtrar ou depurar líquidos ou gases');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0104000','84241000','Extintores, mesmo carregados');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0104100','84213100','Filtros de entrada de ar para motores de ignição por centelha ou por compressão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0104200','84213920','Depuradores por conversão catalítica de gases de escape');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0104300','84254200','Macacos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0104400','84311010','Partes para macacos do CEST 01.043.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0104500','8431492','Partes reconhecíveis como exclusiva ou principalmente destinadas às máquinas agrícolas ou rodoviárias');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0104501','84339090','Partes reconhecíveis como exclusiva ou principalmente destinadas às máquinas agrícolas ou rodoviárias');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0104600','84811000','Válvulas redutoras de pressão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0104700','84812','Válvulas para transmissão óleo-hidráulicas ou pneumáticas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0104800','84818092','Válvulas solenoides');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0104900','8482','Rolamentos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0105000','8483','Árvores de transmissão (incluídas as árvores de “cames” e virabrequins) e manivelas; mancais e “bronzes”; engrenagens e rodas de fricção; eixos de esferas ou de roletes; redutores, multiplicadores, caixas de transmissão e variadores de velocidade, incluídos os conversores de torque; volantes e polias, incluídas as polias para cadernais; embreagens e dispositivos de acoplamento, incluídas as juntas de articulação');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0105100','8484','Juntas metaloplásticas; jogos ou sortidos de juntas de composições diferentes, apresentados em bolsas, envelopes ou embalagens semelhantes; juntas de vedação mecânicas (selos mecânicos)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0105200','850520','Acoplamentos, embreagens, variadores de velocidade e freios, eletromagnéticos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0105300','850710','Acumuladores elétricos de chumbo, do tipo utilizado para o arranque dos motores de pistão, exceto os classificados no CEST 01.053.01');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0105301','85071010','Acumuladores elétricos de chumbo, do tipo utilizado para o arranque dos motores de pistão e de capacidade inferior ou igual a 20 Ah e tensão inferior ou igual a 12 V');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0105400','8511','Aparelhos e dispositivos elétricos de ignição ou de arranque para motores de ignição por centelha ou por compressão (por exemplo, magnetos, dínamos-magnetos, bobinas de ignição, velas de ignição ou de aquecimento, motores de arranque); geradores (dínamos e alternadores, por exemplo) e conjuntores-disjuntores utilizados com estes motores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0105500','851220','Aparelhos elétricos de iluminação ou de sinalização (exceto os da posição 8539), limpadores de para-brisas, degeladores e desembaçadores (desembaciadores) elétricos e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0105500','851240','Aparelhos elétricos de iluminação ou de sinalização (exceto os da posição 8539), limpadores de para-brisas, degeladores e desembaçadores (desembaciadores) elétricos e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0105500','85129000','Aparelhos elétricos de iluminação ou de sinalização (exceto os da posição 8539), limpadores de para-brisas, degeladores e desembaçadores (desembaciadores) elétricos e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0105600','85171213','Telefones móveis do tipo dos utilizados em veículos automóveis.');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0105700','8518','Alto-falantes, amplificadores elétricos de audiofrequência e partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0105800','85185000','Aparelhos elétricos de amplificação de som para veículos automotores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0105900','851981','Aparelhos de reprodução de som');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0106000','8525501','Aparelhos transmissores (emissores) de radiotelefonia ou radiotelegrafia (rádio receptor/transmissor)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0106000','85256010','Aparelhos transmissores (emissores) de radiotelefonia ou radiotelegrafia (rádio receptor/transmissor)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0106100','85272100','Aparelhos receptores de radiodifusão que só funcionem com fonte externa de energia combinados com um aparelho de gravação ou de reprodução de som, do tipo utilizado em veículos automóveis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0106200','85272900','Outros aparelhos receptores de radiodifusão que só funcionem com fonte externa de energia, do tipo utilizado em veículos automóveis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0106201','85219090','Outros aparelhos videofônicos de gravação ou de reprodução, mesmo incorporando um receptor de sinais videofônicos, dos tipos utilizados exclusivamente em veículos automotores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0106300','85291090','Antenas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0106400','853400','Circuitos impressos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0106500','853530','Interruptores e seccionadores e comutadores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0106500','853650','Interruptores e seccionadores e comutadores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0106600','85361000','Fusíveis e corta-circuitos de fusíveis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0106700','85362000','Disjuntores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0106800','85364','Relés');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0106900','8538','Partes reconhecíveis como exclusivas ou principalmente destinados aos aparelhos dos CEST 01.065.00, 01.066.00, 01.067.00 e 01.068.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0107000','853910','Faróis e projetores, em unidades seladas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0107100','85392','Lâmpadas e tubos de incandescência, exceto de raios ultravioleta ou infravermelhos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0107200','85442000','Cabos coaxiais e outros condutores elétricos coaxiais');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0107300','85443000','Jogos de fios para velas de ignição e outros jogos de fios');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0107400','8707','Carroçarias para os veículos automóveis das posições 8701 a 8705, incluídas as cabinas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0107500','8708','Partes e acessórios dos veículos automóveis das posições 8701 a 8705');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0107600','87141','Parte e acessórios de motocicletas (incluídos os ciclomotores)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0107700','87169090','Engates para reboques e semirreboques');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0107800','902610','Medidores de nível; Medidores de vazão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0107900','902620','Aparelhos para medida ou controle da pressão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0108000','9029','Contadores, indicadores de velocidade e tacômetros, suas partes e acessórios');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0108100','90303321','Amperímetros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0108200','90318040','Aparelhos digitais, de uso em veículos automóveis, para medida e indicação de múltiplas grandezas tais como: velocidade média, consumos instantâneo e médio e autonomia (computador de bordo)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0108300','9032892','Controladores eletrônicos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0108400','91040000','Relógios para painéis de instrumentos e relógios semelhantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0108500','94012000','Assentos e partes de assentos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0108500','94019090','Assentos e partes de assentos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0108600','96138000','Acendedores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0108700','4009','Tubos de borracha vulcanizada não endurecida, mesmo providos de seus acessórios');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0108800','45049000','Juntas de vedação de cortiça natural e de amianto');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0108800','68129910','Juntas de vedação de cortiça natural e de amianto');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0108900','48234000','Papel-diagrama para tacógrafo, em disco');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109000','39191010','Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109000','39191020','Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109000','39191090','Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109000','39199010','Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109000','39199020','Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109000','39199090','Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109000','87082999','Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109100','84123110','Cilindros pneumáticos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109200','84131900','Bomba elétrica de lavador de para-brisa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109200','84135090','Bomba elétrica de lavador de para-brisa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109200','84138100','Bomba elétrica de lavador de para-brisa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109300','84136019','Bomba de assistência de direção hidráulica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109300','84137010','Bomba de assistência de direção hidráulica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109400','84145910','Motoventiladores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109400','84145990','Motoventiladores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109500','84213990','Filtros de pólen do ar-condicionado');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109600','85011019','“Máquina” de vidro elétrico de porta');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109700','85013110','Motor de limpador de para-brisa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109800','85045000','Bobinas de reatância e de autoindução');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109900','850720','Baterias de chumbo e de níquel-cádmio');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0109900','850730','Baterias de chumbo e de níquel-cádmio');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0110000','85123000','Aparelhos de sinalização acústica (buzina)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0110100','9032898','Instrumentos para regulação de grandezas não elétricas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0110100','9032899','Instrumentos para regulação de grandezas não elétricas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0110200','90271000','Analisadores de gases ou de fumaça (sonda lambda)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0110300','40081100','Perfilados de borracha vulcanizada não endurecida');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0110400','56012219','Artefatos de pasta de fibra de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0110500','57032000','Tapetes/carpetes - nailón');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0110600','57033000','Tapetes de matérias têxteis sintéticas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0110700','59119000','Forração interior capacete');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0110800','69039099','Outros para-brisas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0110900','70072900','Moldura com espelho');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0111000','73145000','Corrente de transmissão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0111100','73151100','Corrente transmissão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0111200','73151210','Outras correntes de transmissão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0111300','84189900','Condensador tubular metálico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0111400','841950','Trocadores de calor');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0111500','84249090','Partes de aparelhos mecânicos de pulverizar ou dispersar');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0111600','84254910','Macacos manuais para veículos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0111700','84314100','Caçambas, pás, ganchos e tenazes para máquinas rodoviárias');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0111800','85016100','Geradores de corrente alternada de potência não superior a 75 kva');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0111900','85311090','Aparelhos elétricos para alarme de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0112000','90141000','Bússolas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0112100','90251990','Indicadores de temperatura');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0112200','90259010','Partes de indicadores de temperatura');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0112300','902690','Partes de aparelhos de medida ou controle');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0112400','90321010','Termostatos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0112500','90321090','Instrumentos e aparelhos para regulação');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0112600','90322000','Pressostatos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0112700','871690','Peças para reboques e semirreboques, exceto os itens classificados no CEST 01.077.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0112800','73229010','Geradores de ar quente a combustível líquido, com capacidade superior ou igual a 1.500 kcal/h, mas inferior ou igual a 10.400 kcal/h, do tipo dos utilizados em veículos automóveis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0199900','NT','Outras peças, partes e acessórios para veículos automotores não relacionados nos demais itens deste anexo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0200100','2205','Aperitivos, amargos, bitter e similares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0200100','22089000','Aperitivos, amargos, bitter e similares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0200200','22089000','Batida e similares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0200300','22089000','Bebida ice');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0200400','220720','Cachaça e aguardentes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0200400','22084000','Cachaça e aguardentes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0200500','2205','Catuaba e similares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0200500','22060090','Catuaba e similares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0200500','22089000','Catuaba e similares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0200600','22082000','Conhaque, brandy e similares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0200700','22060090','Cooler');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0200700','22089000','Cooler');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0200800','22085000','Gim (gin) e genebra');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0200900','2205','Jurubeba e similares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0200900','22060090','Jurubeba e similares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0200900','22089000','Jurubeba e similares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0201000','22087000','Licores e similares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0201100','22082000','Pisco');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0201200','22084000','Rum');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0201300','22060090','Saquê');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0201400','22089000','Steinhaeger');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0201500','22089000','Tequila');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0201600','220830','Uísque');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0201700','2205','Vermute e similares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0201800','22086000','Vodka');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0201900','22089000','Derivados de vodka');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0202000','22089000','Arak');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0202100','22082000','Aguardente vínica / grappa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0202200','22060010','Sidra e similares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0202300','2205','Sangrias e coquetéis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0202300','22060090','Sangrias e coquetéis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0202300','22089000','Sangrias e coquetéis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0202400','2204','Vinhos de uvas frescas, incluindo os vinhos enriquecidos com álcool; mostos de uvas.');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0299900','2205','Outras bebidas alcoólicas não especificadas nos itens anteriores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0299900','2206','Outras bebidas alcoólicas não especificadas nos itens anteriores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0299900','2207','Outras bebidas alcoólicas não especificadas nos itens anteriores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0299900','2208','Outras bebidas alcoólicas não especificadas nos itens anteriores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0300100','22011000','Água mineral, gasosa ou não, ou potável, naturais, em garrafa de vidro, retornável ou não, com capacidade de até 500 ml');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0300200','22011000','Água mineral, gasosa ou não, ou potável, naturais, em embalagem com capacidade igual ou superior a 5.000 ml; exceto as classificadas no CEST 03.024.00 e 03.025.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0300300','22011000','Água mineral, gasosa ou não, ou potável, naturais, em embalagem de vidro, não retornável, com capacidade de até 300 ml');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0300400','22011000','Água mineral, gasosa ou não, ou potável, naturais, em garrafa plástica de 1.500 ml');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0300500','22011000','Água mineral, gasosa ou não, ou potável, naturais, em copos plásticos e embalagem plástica com capacidade de até 500 ml');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0300600','22011000','Outras águas minerais, potáveis ou naturais, gasosas ou não, inclusive gaseificadas; exceto as classificadas no CEST 03.024.00 e 03.025.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0300700','22021000','Águas minerais, potáveis ou naturais, gasosas ou não, inclusive gaseificadas ou aromatizadas artificialmente, exceto os refrescos e refrigerantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0300800','22029900','Outras águas minerais, potáveis ou naturais, gasosas ou não, inclusive gaseificadas ou aromatizadas artificialmente');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0301000','2202','Refrigerantes em garrafa com capacidade igual ou superior a 600 ml, exceto os classificados no CEST 03.011.01');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0301100','2202','Demais refrigerantes, exceto os classificados no CEST 03.010.00 e 03.011.01');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0301101','2202','Espumantes sem álcool');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0301200','21069010','Xarope ou extrato concentrado destinados ao preparo de refrigerante em máquina “pré-mix” ou “post-mix”');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0301300','210690','Bebidas energéticas em embalagem com capacidade inferior a 600ml');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0301300','22029900','Bebidas energéticas em embalagem com capacidade inferior a 600ml');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0301400','210690','Bebidas energéticas em embalagem com capacidade igual ou superior a 600ml');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0301400','22029900','Bebidas energéticas em embalagem com capacidade igual ou superior a 600ml');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0301500','210690','Bebidas hidroeletrolíticas (isotônicas) em embalagem com capacidade inferior a 600ml');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0301500','22029900','Bebidas hidroeletrolíticas (isotônicas) em embalagem com capacidade inferior a 600ml');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0301600','210690','Bebidas hidroeletrolíticas (isotônicas) em embalagem com capacidade inferior a 600ml');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0301600','22029900','Bebidas hidroeletrolíticas (isotônicas) em embalagem com capacidade igual ou superior a 600ml');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0302100','22030000','Cerveja');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0302200','22029100','Cerveja sem álcool');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0302300','22030000','Chope');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0302400','22011000','Água mineral em embalagens retornáveis com capacidade igual ou superior a 10 (dez) e inferior a 20 (vinte) litros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0302500','22011000','Água mineral em embalagens retornáveis com capacidade igual ou superior a 20 (vinte) litros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0400100','2402','Charutos, cigarrilhas e cigarros, de tabaco ou dos seus sucedâneos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0400200','24031','Tabaco para fumar, mesmo contendo sucedâneos de tabaco em qualquer proporção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0500100','2523','Cimento');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600100','22071010','Álcool etílico não desnaturado, com um teor alcoólico em volume igual ou superior a 80% vol - Com um teor de água igual ou inferior a 1 % vol (álcool etílico anidro combustível)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600101','22071090','Álcool etílico não desnaturado, com um teor alcoólico em volume igual ou superior a 80% vol - Outros (álcool etílico hidratado combustível)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600200','27101259','Gasolina automotiva A, exceto Premium');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600201','27101259','Gasolina automotiva C, exceto Premium');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600202','27101259','Gasolina automotiva A Premium');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600203','27101259','Gasolina automotiva C Premium');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600300','27101251','Gasolina de aviação');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600400','27101919','Querosenes, exceto de aviação');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600500','27101911','Querosene de aviação');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600600','2710192','Óleo diesel A, exceto S10 e Marítimo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600601','2710192','Óleo diesel B, exceto S10 (mistura obrigatória)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600602','2710192','Óleo diesel B, exceto S10 (misturas autorizativas)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600603','2710192','Óleo diesel B, exceto S10 (misturas experimentais)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600604','2710192','Óleo diesel A S10');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600605','2710192','Óleo diesel B S10 (mistura obrigatória)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600606','2710192','Óleo diesel B S10 (misturas autorizativas)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600607','2710192','Óleo diesel B S10 (misturas experimentais)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600608','2710192','Óleo Diesel Marítimo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600609','2710192','Outros óleos combustíveis, exceto os classificados no CEST 06.006.10 e 06.006.11');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600610','2710192','Óleo combustível derivado de xisto');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600611','27101922','Óleo combustível pesado');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600700','2710193','Óleos lubrificantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600800','2710199','Outros óleos de petróleo ou de minerais betuminosos (exceto óleos brutos) e preparações não especificadas nem compreendidas noutras posições, que contenham, como constituintes básicos, 70% ou mais, em peso, de óleos de petróleo ou de minerais betuminosos, exceto os que contenham biodiesel, exceto os resíduos de óleos e exceto as graxas lubrificantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600801','2710199','Graxa lubrificante');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0600900','27109','Resíduos de óleos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0601000','2711','Gás de petróleo e outros hidrocarbonetos gasosos, exceto GLP, GLGN, Gás Natural e Gás de xisto.');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0601100','27111910','Gás liquefeito de petróleo em botijão de 13 Kg (GLP)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0601101','27111910','Gás liquefeito de petróleo (GLP), exceto em botijão de 13 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0601102','27111910','Gás liquefeito de petróleo em botijão de 13 Kg (GLGNn)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0601103','27111910','Gás liquefeito de petróleo (GLGNn), exceto em botijão de 13 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0601104','27111910','Gás liquefeito de petróleo em botijão de 13 Kg (GLGNi)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0601105','27111910','Gás liquefeito de petróleo (GLGNi), exceto em botijão de 13 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0601106','27111910','Gás liquefeito de petróleo em botijão de 13 kg (Misturas)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0601107','27111910','Gás liquefeito de petróleo (Misturas), exceto em botijão de 13 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0601200','27111100','Gás Natural Liquefeito');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0601300','27112100','Gás Natural Gasoso');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0601400','27112990','Gás de xisto');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0601500','2713','Coque de petróleo e outros resíduos de óleo de petróleo ou de minerais betuminosos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0601600','38260000','Biodiesel e suas misturas, que não contenham ou que contenham menos de 70%, em peso, de óleos de petróleo ou de óleos minerais betuminosos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0601700','3403','Preparações lubrificantes, exceto as contendo, como constituintes de base, 70% ou mais, em peso, de óleos de petróleo ou de minerais betuminosos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0601800','27102000','Óleos de petróleo ou de minerais betuminosos (exceto óleos brutos) e preparações não especificadas nem compreendidas noutras posições, que contenham, como constituintes básicos, 70% ou mais, em peso, de óleos de petróleo ou de minerais betuminosos, que contenham biodiesel, exceto os resíduos de óleos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0700100','27160000','Energia elétrica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0800100','40169990','Ferramentas de borracha vulcanizada não endurecida');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0800200','44170010','Ferramentas, armações e cabos de ferramentas, de madeira');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0800200','44170090','Ferramentas, armações e cabos de ferramentas, de madeira');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0800300','6804','Mós e artefatos semelhantes, sem armação, para moer, desfibrar, triturar, amolar, polir, retificar ou cortar; pedras para amolar ou para polir, manualmente, e suas partes, de pedras naturais, de abrasivos naturais ou artificiais aglomerados ou de cerâmica, mesmo com partes de outras matérias');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0800400','8201','Pás, alviões, picaretas, enxadas, sachos, forcados e forquilhas, ancinhos e raspadeiras; machados, podões e ferramentas semelhantes com gume; tesouras de podar de todos os tipos; foices e foicinhas, facas para feno ou para palha, tesouras para sebes, cunhas e outras ferramentas manuais para agricultura, horticultura ou silvicultura');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0800500','82022000','Folhas de serras de fita');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0800600','82029100','Lâminas de serras máquinas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0800700','8202','Serras manuais e outras folhas de serras (incluídas as fresas-serras e as folhas não dentadas para serrar), exceto as classificadas nos CEST 08.005.00 e 08.006.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0800800','8203','Limas, grosas, alicates (mesmo cortantes), tenazes, pinças, cisalhas para metais, corta-tubos, corta-pinos, saca-bocados e ferramentas semelhantes, manuais, exceto as pinças para sobrancelhas classificadas na posição 8203.20.90');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0800900','8204','Chaves de porcas, manuais (incluídas as chaves dinamométricas); chaves de caixa intercambiáveis, mesmo com cabos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0801000','8205','Ferramentas manuais (incluídos os diamantes de vidraceiro) não especificadas nem compreendidas em outras posições, lamparinas ou lâmpadas de soldar (maçaricos) e semelhantes; tornos de apertar, sargentos e semelhantes, exceto os acessórios ou partes de máquinas-ferramentas; bigornas; forjas-portáteis; mós com armação, manuais ou de pedal');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0801100','82060000','Ferramentas de pelo menos duas das posições 8202 a 8205, acondicionadas em sortidos para venda a retalho');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0801200','820740','Ferramentas de roscar interior ou exteriormente; de mandrilar ou de brochar; e de fresar');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0801200','820760','Ferramentas de roscar interior ou exteriormente; de mandrilar ou de brochar; e de fresar');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0801200','820770','Ferramentas de roscar interior ou exteriormente; de mandrilar ou de brochar; e de fresar');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0801300','8207','Outras ferramentas intercambiáveis para ferramentas manuais, mesmo mecânicas, ou para máquinas-ferramentas (por exemplo, de embutir, estampar, puncionar, furar, tornear, aparafusar), incluídas as fieiras de estiragem ou de extrusão, para metais, e as ferramentas de perfuração ou de sondagem, exceto forma ou gabarito de produtos em epoxy e as classificadas no CEST 08.012.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0801400','8208','Facas e lâminas cortantes, para máquinas ou para aparelhos mecânicos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0801500','82090011','Plaquetas ou pastilhas intercambiáveis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0801600','820900','Outras plaquetas, varetas, pontas e objetos semelhantes para ferramentas, não montados, de ceramais (“cermets”), exceto as classificadas no CEST 08.015.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0801700','8211','Facas de lâmina cortante ou serrilhada, incluídas as podadeiras de lâmina móvel, e suas lâminas, exceto as de uso doméstico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0801800','8213','Tesouras e suas lâminas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0801900','8467','Ferramentas pneumáticas, hidráulicas ou com motor (elétrico ou não elétrico) incorporado, de uso manual, exceto o descrito no CEST 08.019.01');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0801901','84678100','Moto-serras portáteis de corrente, com motor incorporado, não elétrico, de uso agrícola');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0802000','9015','nstrumentos e aparelhos de geodesia, topografia, agrimensura, nivelamento, fotogrametria, hidrografia, oceanografia, hidrologia, meteorologia ou de geofísica, exceto bussolas; telêmetros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0802100','90172000','Instrumentos de desenho, de traçado ou de cálculo; metros, micrômetros, paquímetros, calibres e semelhantes; partes e acessórios');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0802100','901730','Instrumentos de desenho, de traçado ou de cálculo; metros, micrômetros, paquímetros, calibres e semelhantes; partes e acessórios');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0802100','901780','Instrumentos de desenho, de traçado ou de cálculo; metros, micrômetros, paquímetros, calibres e semelhantes; partes e acessórios');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0802100','90179090','Instrumentos de desenho, de traçado ou de cálculo; metros, micrômetros, paquímetros, calibres e semelhantes; partes e acessórios');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0802200','90251190','Termômetros, suas partes e acessórios');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0802200','90259010','Termômetros, suas partes e acessórios');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0802300','902519','Pirômetros, suas partes e acessórios');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0802300','90259090','Pirômetros, suas partes e acessórios');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0900100','8539','Lâmpadas elétricas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0900200','8540','Lâmpadas eletrônicas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0900300','85041000','Reatores para lâmpadas ou tubos de descargas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0900400','853650','“Starter”');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('0900500','85395000','Lâmpadas de LED (Diodos Emissores de Luz)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1000100','2522','Cal');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1000200','3816001','Argamassas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1000200','38245000','Argamassas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1000300','32149000','Outras argamassas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1000400','391000','Silicones em formas primárias, para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1000500','3916','Revestimentos de PVC e outros plásticos; forro, sancas e afins de PVC, para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1000600','3917','Tubos, e seus acessórios (por exemplo, juntas, cotovelos, flanges, uniões), de plásticos, para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1000700','3918','Revestimento de pavimento de PVC e outros plásticos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1000800','3919','Chapas, folhas, tiras, fitas, películas e outras formas planas, autoadesivas, de plásticos, mesmo em rolos, para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1000900','3919','Veda rosca, lona plástica para uso na construção, fitas isolantes e afins');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1000900','3920','Veda rosca, lona plástica para uso na construção, fitas isolantes e afins');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1000900','3921','Veda rosca, lona plástica para uso na construção, fitas isolantes e afins');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1001000','3921','Telha de plástico, mesmo reforçada com fibra de vidro');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1001100','3921','Cumeeira de plástico, mesmo reforçada com fibra de vidro');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1001200','3921','Chapas, laminados plásticos em bobina, para uso na construção, exceto os descritos no CEST 10.010.00 e 10.011.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1001300','3922','Banheiras, boxes para chuveiros, pias, lavatórios, bidês, sanitários e seus assentos e tampas, caixas de descarga e artigos semelhantes para usos sanitários ou higiênicos, de plásticos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1001400','3924','Artefatos de higiene/toucador de plástico, para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1001500','39251000','Caixa d’água, inclusive sua tampa, de plástico, mesmo reforçadas com fibra de vidro');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1001600','392590','Outras telhas, cumeeira e caixa d’água, inclusive sua tampa, de plástico, mesmo reforçadas com fibra de vidro');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1001700','39251000','Artefatos para apetrechamento de construções, de plásticos, não especificados nem compreendidos em outras posições, incluindo persianas, sancas, molduras, apliques e rosetas, caixilhos de polietileno e outros plásticos, exceto os descritos nos CEST 10.015.00 e 10.016.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1001700','392590','Artefatos para apetrechamento de construções, de plásticos, não especificados nem compreendidos em outras posições, incluindo persianas, sancas, molduras, apliques e rosetas, caixilhos de polietileno e outros plásticos, exceto os descritos nos CEST 10.015.00 e 10.016.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1001800','39252000','Portas, janelas e seus caixilhos, alizares e soleiras');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1001900','39253000','Postigos, estores (incluídas as venezianas) e artefatos semelhantes e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1002000','392690','Outras obras de plástico, para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1002100','4814','Papel de parede e revestimentos de parede semelhantes; papel para vitrais');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1002200','68101900','Telhas de concreto');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1002300','6811','Telha, cumeeira e caixa d’água, inclusive sua tampa, de fibrocimento, cimento-celulose');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1002400','6811','Caixas d’água, tanques e reservatórios e suas tampas, telhas, calhas, cumeeiras e afins, de fibrocimento, cimento-celulose ou semelhantes, contendo ou não amianto, exceto os descritos no CEST 10.023.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1002500','69010000','Tijolos, placas (lajes), ladrilhos e outras peças cerâmicas de farinhas siliciosas fósseis (“kieselghur”, tripolita, diatomita, por exemplo) ou de terras siliciosas semelhantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1002600','6902','Tijolos, placas (lajes), ladrilhos e peças cerâmicas semelhantes, para uso na construção, refratários, que não sejam de farinhas siliciosas fósseis nem de terras siliciosas semelhantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1002700','6904','Tijolos para construção, tijoleiras, tapa-vigas e produtos semelhantes, de cerâmica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1002800','6905','Telhas, elementos de chaminés, condutores de fumaça, ornamentos arquitetônicos, de cerâmica, e outros produtos cerâmicos para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1002900','69060000','Tubos, calhas ou algerozes e acessórios para canalizações, de cerâmica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1003000','6907','Ladrilhos e placas de cerâmica, exclusivamente para pavimentação ou revestimento');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1003001','6907','Cubos, pastilhas e artigos semelhantes de cerâmica, mesmo com suporte, exceto os descritos CEST 10.030.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1003100','6910','Pias, lavatórios, colunas para lavatórios, banheiras, bidês, sanitários, caixas de descarga, mictórios e aparelhos fixos semelhantes para usos sanitários, de cerâmica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1003200','69120000','Artefatos de higiene/toucador de cerâmica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1003300','7003','Vidro vazado ou laminado, em chapas, folhas ou perfis, mesmo com camada absorvente, refletora ou não, mas sem qualquer outro trabalho');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1003400','7004','Vidro estirado ou soprado, em folhas, mesmo com camada absorvente, refletora ou não, mas sem qualquer outro trabalho');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1003500','7005','Vidro flotado e vidro desbastado ou polido em uma ou em ambas as faces, em chapas ou em folhas, mesmo com camada absorvente, refletora ou não, mas sem qualquer outro trabalho');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1003600','70071900','Vidros temperados');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1003700','70072900','Vidros laminados');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1003800','7008','Vidros isolantes de paredes múltiplas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1003900','7016','Blocos, placas, tijolos, ladrilhos, telhas e outros artefatos, de vidro prensado ou moldado, mesmo armado, para uso na construção; cubos, pastilhas e outros artigos semelhantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1004000','72142000','Barras próprias para construções, exceto vergalhões');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1004100','73089010','Outras barras próprias para construções, exceto vergalhões');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1004200','72142000','Vergalhões');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1004300','7213','Outros vergalhões');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1004300','73089010','Outros vergalhões');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1004400','72171090','Fios de ferro ou aço não ligados, não revestidos, mesmo polidos; cordas, cabos, tranças (entrançados), lingas e artefatos semelhantes, de ferro ou aço, não isolados para usos elétricos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1004400','7312','Fios de ferro ou aço não ligados, não revestidos, mesmo polidos; cordas, cabos, tranças (entrançados), lingas e artefatos semelhantes, de ferro ou aço, não isolados para usos elétricos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1004500','72172010','Outros fios de ferro ou aço, não ligados, galvanizados com teor de carbono superior ou igual a 0,6%, em peso');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1004501','72172090','Outros fios de ferro ou aço, não ligados, galvanizados');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1004600','7307','Acessórios para tubos (inclusive uniões, cotovelos, luvas ou mangas), de ferro fundido, ferro ou aço');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1004700','73083000','Portas e janelas, e seus caixilhos, alizares e soleiras de ferro fundido, ferro ou aço');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1004800','73084000','Material para andaimes, para armações (cofragens) e para escoramentos, (inclusive armações prontas, para estruturas de concreto armado ou argamassa armada), eletrocalhas e perfilados de ferro fundido, ferro ou aço, próprios para construção, exceto treliças de aço');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1004800','730890','Material para andaimes, para armações (cofragens) e para escoramentos, (inclusive armações prontas, para estruturas de concreto armado ou argamassa armada), eletrocalhas e perfilados de ferro fundido, ferro ou aço, próprios para construção, exceto treliças de aço');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1004900','73084000','Treliças de aço');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1005000','73089090','Telhas metálicas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1005100','7310','Caixas diversas (tais como caixa de correio, de entrada de água, de energia, de instalação) de ferro fundido, ferro ou aço; próprias para a construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1005200','73130000','Arame farpado, de ferro ou aço, arames ou tiras, retorcidos, mesmo farpados, de ferro ou aço, dos tipos utilizados em cercas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1005300','7314','Telas metálicas, grades e redes, de fios de ferro ou aço');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1005400','73151100','Correntes de rolos, de ferro fundido, ferro ou aço');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1005500','73151290','Outras correntes de elos articulados, de ferro fundido, ferro ou aço');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1005600','73158200','Correntes de elos soldados, de ferro fundido, de ferro ou aço');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1005700','731700','Tachas, pregos, percevejos, escápulas, grampos ondulados ou biselados e artefatos semelhantes, de ferro fundido, ferro ou aço, mesmo com a cabeça de outra matéria, exceto cobre');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1005800','7318','Parafusos, pinos ou pernos, roscados, porcas, tira-fundos, ganchos roscados, rebites, chavetas, cavilhas, contrapinos, arruelas (incluídas as de pressão) e artefatos semelhantes, de ferro fundido, ferro ou aço');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1005900','7323','Palha de ferro ou aço, exceto os de uso doméstico classificados na posição NCM 7323.10.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1005901','7323','Esponjas, esfregões, luvas e artefatos semelhantes para limpeza, polimento e usos semelhantes, de ferro ou aço, exceto os de uso doméstico classificados na posição NCM 7323.10.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1006000','7324','Artefatos de higiene ou de toucador, e suas partes, de ferro fundido, ferro ou aço, incluídas as pias, banheiras, lavatórios, cubas, mictórios, tanques e afins de ferro fundido, ferro ou aço, para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1006100','7325','Outras obras moldadas, de ferro fundido, ferro ou aço, para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1006200','7326','Abraçadeiras');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1006300','7407','Barras de cobre');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1006400','74111010','Tubos de cobre e suas ligas, para instalações de água quente e gás, para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1006500','7412','Acessórios para tubos (por exemplo, uniões, cotovelos, luvas ou mangas) de cobre e suas ligas, para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1006600','7415','Tachas, pregos, percevejos, escápulas e artefatos semelhantes, de cobre, ou de ferro ou aço com cabeça de cobre, parafusos, pinos ou pernos, roscados, porcas, ganchos roscados, rebites, chavetas, cavilhas, contrapinos, arruelas (incluídas as de pressão), e artefatos semelhantes, de cobre');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1006700','74182000','Artefatos de higiene/toucador de cobre, para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1006800','76071990','Manta de subcobertura aluminizada');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1006900','7608','Tubos de alumínio e suas ligas, para refrigeração e ar condicionado, para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1007000','76090000','Acessórios para tubos (por exemplo, uniões, cotovelos, luvas ou mangas), de alumínio, para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1007100','7610','Construções e suas partes (por exemplo, pontes e elementos de pontes, torres, pórticos ou pilones, pilares, colunas, armações, estruturas para telhados, portas e janelas, e seus caixilhos, alizares e soleiras, balaustradas), de alumínio, exceto as construções pré-fabricadas da posição 9406; chapas, barras, perfis, tubos e semelhantes, de alumínio, próprios para construções');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1007200','76152000','Artefatos de higiene/toucador de alumínio, para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1007300','7616','Outras obras de alumínio, próprias para construções, incluídas as persianas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1007400','83024100','Outras guarnições, ferragens e artigos semelhantes de metais comuns, para construções, inclusive puxadores.');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1007500','8301','Fechaduras e ferrolhos (de chave, de segredo ou elétricos), de metais comuns, incluídas as suas partes fechos e armações com fecho, com fechadura, de metais comuns chaves para estes artigos, de metais comuns; exceto os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1007600','83021000','Dobradiças de metais comuns, de qualquer tipo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1007700','8307','Tubos flexíveis de metais comuns, mesmo com acessórios, para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1007800','8311','Fios, varetas, tubos, chapas, eletrodos e artefatos semelhantes, de metais comuns ou de carbonetos metálicos, revestidos exterior ou interiormente de decapantes ou de fundentes, para soldagem (soldadura) ou depósito de metal ou de carbonetos metálicos fios e varetas de pós de metais comuns aglomerados, para metalização por projeção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1007900','8481','Torneiras, válvulas (incluídas as redutoras de pressão e as termostáticas) e dispositivos semelhantes, para canalizações, caldeiras, reservatórios, cubas e outros recipientes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1008000','7009','Espelhos de vidro, mesmo emoldurados, exceto os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1100100','28289011','Água sanitária, branqueador e outros alvejantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1100100','28289019','Água sanitária, branqueador e outros alvejantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1100100','32064100','Água sanitária, branqueador e outros alvejantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1100100','34022000','Água sanitária, branqueador e outros alvejantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1100100','38089419','Água sanitária, branqueador e outros alvejantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1100200','34012090','Sabões em pó, flocos, palhetas, grânulos ou outras formas semelhantes, para lavar roupas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1100300','34012090','Sabões líquidos para lavar roupas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1100400','34022000','Detergentes em pó, flocos, palhetas, grânulos ou outras formas semelhantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1100500','34022000','Detergentes líquidos, exceto para lavar roupa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1100600','34022000','Detergente líquido para lavar roupa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1100700','3402','Outros agentes orgânicos de superfície (exceto sabões); preparações tensoativas, preparações para lavagem (incluídas as preparações auxiliares para lavagem) e preparações para limpeza (inclusive multiuso e limpadores), mesmo contendo sabão, exceto os produtos descritos nos CEST 11.001.00, 11.004.00, 11.005.00 e 11.006.00; em embalagem de conteúdo inferior ou igual a 50 litros ou 50 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1100800','38099190','Amaciante/suavizante');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1100900','39241000','Esponjas para limpeza');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1100900','39249000','Esponjas para limpeza');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1100900','68053010','Esponjas para limpeza');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1100900','68053090','Esponjas para limpeza');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1101000','2207','Álcool etílico para limpeza');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1101000','22089000','Álcool etílico para limpeza');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1101100','73231000','Esponjas e palhas de aço; esponjas para limpeza, polimento ou uso semelhantes; todas de uso doméstico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1101200','39232','Sacos de lixo de conteúdo igual ou inferior a 100 litros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1200100','8504','Transformadores, bobinas de reatância e de auto indução, inclusive os transformadores de potência superior a 16 KVA, classificados nas posições 8504.33.00 e 8504.34.00; exceto os demais transformadores da subposição 8504.3, os reatores para lâmpadas elétricas de descarga classificados no código 8504.10.00, os carregadores de acumuladores do código 8504.40.10, os equipamentos de alimentação ininterrupta de energia (UPS ou “no break”), no código 8504.40.40 e os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1200200','8516','Aquecedores elétricos de água, incluídos os de imersão, chuveiros ou duchas elétricos, torneiras elétricas, resistências de aquecimento, inclusive as de duchas e chuveiros elétricos e suas partes; exceto outros fornos, fogareiros (incluídas as chapas de cocção), grelhas e assadeiras, classificados na posição 8516.60.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1200300','8535','Aparelhos para interrupção, seccionamento, proteção, derivação, ligação ou conexão de circuitos elétricos (por exemplo, interruptores, comutadores, corta-circuitos, para-raios, limitadores de tensão, eliminadores de onda, tomadas de corrente e outros conectores, caixas de junção), para tensão superior a 1.000V, exceto os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1200400','8536','Aparelhos para interrupção, seccionamento, proteção, derivação, ligação ou conexão de circuitos elétricos (por exemplo, interruptores, comutadores, relés, corta-circuitos, eliminadores de onda, plugues e tomadas de corrente, suportes para lâmpadas e outros conectores, caixas de junção), para uma tensão não superior a 1.000V; conectores para fibras ópticas, feixes ou cabos de fibras ópticas; exceto “starter” classificado na subposição 8536.50 e os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1200500','8538','Partes reconhecíveis como exclusiva ou principalmente destinadas aos aparelhos das posições 8535 e 8536');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1200600','74130000','Cabos, tranças e semelhantes, de cobre, não isolados para usos elétricos, exceto os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1200700','7605','Fios, cabos (incluídos os cabos coaxiais) e outros condutores, isolados ou não, para usos elétricos (incluídos os de cobre ou alumínio, envernizados ou oxidados anodicamente), mesmo com peças de conexão, inclusive fios e cabos elétricos, para tensão não superior a 1000V, para uso na construção; fios e cabos telefônicos e para transmissão de dados; cabos de fibras ópticas, constituídos de fibras embainhadas individualmente, mesmo com condutores elétricos ou munidos de peças de conexão; cordas, cabos, tranças e semelhantes, de alumínio, não isolados para uso elétricos; exceto os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1200700','7614','Fios, cabos (incluídos os cabos coaxiais) e outros condutores, isolados ou não, para usos elétricos (incluídos os de cobre ou alumínio, envernizados ou oxidados anodicamente), mesmo com peças de conexão, inclusive fios e cabos elétricos, para tensão não superior a 1000V, para uso na construção; fios e cabos telefônicos e para transmissão de dados; cabos de fibras ópticas, constituídos de fibras embainhadas individualmente, mesmo com condutores elétricos ou munidos de peças de conexão; cordas, cabos, tranças e semelhantes, de alumínio, não isolados para uso elétricos; exceto os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1200700','8544','Fios, cabos (incluídos os cabos coaxiais) e outros condutores, isolados ou não, para usos elétricos (incluídos os de cobre ou alumínio, envernizados ou oxidados anodicamente), mesmo com peças de conexão, inclusive fios e cabos elétricos, para tensão não superior a 1000V, para uso na construção; fios e cabos telefônicos e para transmissão de dados; cabos de fibras ópticas, constituídos de fibras embainhadas individualmente, mesmo com condutores elétricos ou munidos de peças de conexão; cordas, cabos, tranças e semelhantes, de alumínio, não isolados para uso elétricos; exceto os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1200800','8546','Isoladores de qualquer matéria, para usos elétricos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1200900','8547','Peças isolantes inteiramente de matérias isolantes, ou com simples peças metálicas de montagem (suportes roscados, por exemplo) incorporadas na massa, para máquinas, aparelhos e instalações elétricas; tubos isoladores e suas peças de ligação, de metais comuns, isolados interiormente');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300100','3003','Medicamentos de referência - positiva, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300100','3004','Medicamentos de referência - positiva, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300101','3003','Medicamentos de referência - negativa, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300101','3004','Medicamentos de referência - negativa, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300102','3003','Medicamentos de referência - neutra, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300102','3004','Medicamentos de referência - neutra, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300200','3003','Medicamentos genérico - positiva, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300200','3004','Medicamentos genérico - positiva, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300201','3003','Medicamentos genérico - negativa, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300201','3004','Medicamentos genérico - negativa, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300202','3003','Medicamentos genérico - neutra, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300202','3004','Medicamentos genérico - neutra, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300300','3003','Medicamentos similar - positiva, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300300','3004','Medicamentos similar - positiva, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300301','3003','Medicamentos similar - negativa, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300301','3004','Medicamentos similar - negativa, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300302','3003','Medicamentos similar - neutra, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300302','3004','Medicamentos similar - neutra, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300400','3003','Outros tipos de medicamentos - positiva, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300400','3004','Outros tipos de medicamentos - positiva, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300401','3003','Outros tipos de medicamentos - negativa, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300401','3004','Outros tipos de medicamentos - negativa, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300402','3003','Outros tipos de medicamentos - neutra, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300402','3004','Outros tipos de medicamentos - neutra, exceto para uso veterinário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300500','30066000','Preparações químicas contraceptivas à base de hormônios, de outros produtos da posição 29.37 ou de espermicidas - positiva');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300501','30066000','Preparações químicas contraceptivas à base de hormônios, de outros produtos da posição 29.37 ou de espermicidas - negativa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300600','2936','Provitaminas e vitaminas, naturais ou reproduzidas por síntese (incluídos os concentrados naturais), bem como os seus derivados utilizados principalmente como vitaminas, misturados ou não entre si, mesmo em quaisquer soluções - neutra');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300700','300630','Preparações opacificantes (contrastantes) para exames radiográficos e reagentes de diagnóstico concebidos para serem administrados ao paciente - positiva');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300701','300630','Preparações opacificantes (contrastantes) para exames radiográficos e reagentes de diagnóstico concebidos para serem administrados ao paciente - negativa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300800','3002','Antissoro, outras frações do sangue, produtos imunológicos modificados, mesmo obtidos por via biotecnológica, exceto para uso veterinário - positiva');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300801','3002','Antissoro, outras frações do sangue, produtos imunológicos modificados, mesmo obtidos por via biotecnológica, exceto para uso veterinário - negativa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300900','3002','Vacinas e produtos semelhantes, exceto para uso veterinário - positiva;');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1300901','3002','Vacinas e produtos semelhantes, exceto para uso veterinário - negativa;');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1301000','30051010','Curativos (pensos) adesivos e outros artigos com uma camada adesiva, impregnados ou recobertos de substâncias farmacêuticas - Lista Positiva');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1301001','30051010','Curativos (pensos) adesivos e outros artigos com uma camada adesiva, impregnados ou recobertos de substâncias farmacêuticas - Lista Negativa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1301100','3005','Algodão, atadura, esparadrapo, gazes, pensos, sinapismos, e outros, acondicionados para venda a retalho para usos medicinais, cirúrgicos ou dentários, não impregnados ou recobertos de substâncias farmacêuticas - Lista Neutra');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1301200','40151100','Luvas cirúrgicas e luvas de procedimento - neutra');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1301200','40151900','Luvas cirúrgicas e luvas de procedimento - neutra');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1301300','40141000','Preservativo – neutra');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1301400','901831','Seringas, mesmo com agulhas - neutra');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1301500','9018321','Agulhas para seringas - neutra');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1301600','39269090','Contraceptivos (dispositivos intrauterinos - DIU) - neutra');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1301600','90189099','Contraceptivos (dispositivos intrauterinos - DIU) - neutra');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1400100','7013','Objetos de vidro para serviço de mesa ou de cozinha');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1400200','70133700','Outros copos, exceto de vitrocerâmica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1400300','70134290','Objetos para serviço de mesa (exceto copos) ou de cozinha, exceto de vitrocerâmica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1400400','3919','Lonas plásticas, exceto as para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1400400','3920','Lonas plásticas, exceto as para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1400400','3921','Lonas plásticas, exceto as para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1400500','3924','Artefatos de higiene/toucador de plástico, exceto os para uso na construção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1400600','39241000','Serviços de mesa e outros utensílios de mesa ou de cozinha, de plástico, não descartáveis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1400601','39241000','Serviços de mesa e outros utensílios de mesa ou de cozinha, de plástico, descartáveis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1400700','69111010','Artigos para serviço de mesa ou de cozinha, de porcelana, inclusive os descartáveis – estojos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1400800','69111090','Artigos para serviço de mesa ou de cozinha, de porcelana, inclusive os descartáveis – avulsos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1400900','69120000','Artigos para serviço de mesa ou de cozinha, de cerâmica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1401000','69120000','Velas para filtros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1401100','4823209','Filtros descartáveis para coar café ou chá');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1401200','48236','Bandejas, travessas, pratos, xícaras ou chávenas, taças, copos e artigos semelhantes, de papel ou cartão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1401300','48131000','Papel para cigarro');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1600100','40111000','Pneus novos, dos tipos utilizados em automóveis de passageiros (incluídos os veículos de uso misto - camionetas e os automóveis de corrida)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1600200','4011','Pneus novos, dos tipos utilizados em caminhões (inclusive para os fora-de-estrada), ônibus, aviões, máquinas de terraplenagem, de construção e conservação de estradas, máquinas e tratores agrícolas, pá-carregadeira');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1600300','40114000','Pneus novos para motocicletas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1600400','4011','Outros tipos de pneus novos, exceto os itens classificados no CEST 16.005.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1600500','40115000','Pneus novos de borracha dos tipos utilizados em bicicletas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1600600','40121','Pneus recauchutados');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1600700','401290','Protetores de borracha, exceto os itens classificados no CEST 16.007.01');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1600701','401290','Protetores de borracha para bicicletas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1600800','4013','Câmaras de ar de borracha, exceto os itens classificados no CEST 16.009.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1600900','40132000','Câmaras de ar de borracha dos tipos utilizados em bicicletas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1700100','17049010','Chocolate branco, em embalagens de conteúdo inferior ou igual a 1 kg, excluídos os ovos de páscoa de chocolate.');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1700200','18063110','Chocolates contendo cacau, em embalagens de conteúdo inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1700200','18063220','Chocolates contendo cacau, em embalagens de conteúdo inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1700300','18063210','Chocolate em barras, tabletes ou blocos ou no estado líquido, em pasta, em pó, grânulos ou formas semelhantes, em recipientes ou embalagens imediatas de conteúdo inferior ou igual a 2 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1700300','18063220','Chocolate em barras, tabletes ou blocos ou no estado líquido, em pasta, em pó, grânulos ou formas semelhantes, em recipientes ou embalagens imediatas de conteúdo inferior ou igual a 2 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1700400','18069000','Chocolates e outras preparações alimentícias contendo cacau, em embalagens de conteúdo inferior ou igual a 1 kg, excluídos os achocolatados em pó e ovos de páscoa de chocolate.');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1700500','17049010','Ovos de páscoa de chocolate branco');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1700501','18069000','Ovos de páscoa de chocolate');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1700600','18069000','Achocolatados em pó, em embalagens de conteúdo inferior ou igual a 1 kg, exceto os classificados no CEST 17.006.02');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1700601','18061000','Cacau em pó, com adição de açúcar ou de outros edulcorantes, em embalagens de conteúdo inferior ou igual a 1kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1700602','18069000','Achocolatados em pó, em cápsulas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1700700','18069000','Caixas de bombons contendo cacau, em embalagens de conteúdo inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1700800','17049090','Bombons, inclusive à base de chocolate branco sem cacau');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1700900','18069000','Bombons, balas, caramelos, confeitos, pastilhas e outros produtos de confeitaria, contendo cacau');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701000','2009','Sucos de frutas ou de produtos hortícolas; mistura de sucos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701100','20098','Água de coco');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701200','04021','Leite em pó, blocos ou grânulos, exceto creme de leite');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701200','04022','Leite em pó, blocos ou grânulos, exceto creme de leite');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701200','04029','Leite em pó, blocos ou grânulos, exceto creme de leite');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701300','19011020','Farinha láctea');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701400','19011010','Leite modificado para alimentação de crianças');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701500','19011090','Preparações para alimentação infantil à base de farinhas, grumos, sêmolas ou amidos e outros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701600','04011010','Leite “longa vida” (UHT - “Ultra High Temperature”), em recipiente de conteúdo inferior ou igual a 2 litros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701600','04012010','Leite “longa vida” (UHT - “Ultra High Temperature”), em recipiente de conteúdo inferior ou igual a 2 litros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701601','04011010','Leite “longa vida” (UHT - “Ultra High Temperature”), em recipiente de conteúdo superior a 2 litros e inferior ou igual a 5 litros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701601','04012010','Leite “longa vida” (UHT - “Ultra High Temperature”), em recipiente de conteúdo superior a 2 litros e inferior ou igual a 5 litros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701700','04014010','Leite em recipiente de conteúdo inferior ou igual a 1 litro');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701700','04015010','Leite em recipiente de conteúdo inferior ou igual a 1 litro');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701701','04014010','Leite em recipiente de conteúdo superior a 1 litro e inferior ou igual a 5 litros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701701','04015010','Leite em recipiente de conteúdo superior a 1 litro e inferior ou igual a 5 litros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701800','04011090','Leite do tipo pasteurizado em recipiente de conteúdo inferior ou igual a 1 litro');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701800','04012090','Leite do tipo pasteurizado em recipiente de conteúdo inferior ou igual a 1 litro');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701801','04011090','Leite do tipo pasteurizado em recipiente de conteúdo superior a 1 litro e inferior ou igual a 5 litros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701801','04012090','Leite do tipo pasteurizado em recipiente de conteúdo superior a 1 litro e inferior ou igual a 5 litros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701900','0401402','Creme de leite, em recipiente de conteúdo inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701900','04022130','Creme de leite, em recipiente de conteúdo inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701900','04022930','Creme de leite, em recipiente de conteúdo inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701900','04029','Creme de leite, em recipiente de conteúdo inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701901','0401402','Creme de leite, em recipiente de conteúdo superior a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701901','04022130','Creme de leite, em recipiente de conteúdo superior a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701901','04022930','Creme de leite, em recipiente de conteúdo superior a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701901','04029','Creme de leite, em recipiente de conteúdo superior a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701902','040110','Outros cremes de leite, em recipiente de conteúdo inferior ou igual a 1kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701902','040120','Outros cremes de leite, em recipiente de conteúdo inferior ou igual a 1kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701902','040150','Outros cremes de leite, em recipiente de conteúdo inferior ou igual a 1kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701902','040210','Outros cremes de leite, em recipiente de conteúdo inferior ou igual a 1kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1701902','04022920','Outros cremes de leite, em recipiente de conteúdo inferior ou igual a 1kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702000','04029','Leite condensado, em recipiente de conteúdo inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702001','04029','Leite condensado, em recipiente de conteúdo superior a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702100','0403','Iogurte e leite fermentado em recipiente de conteúdo inferior ou igual a 2 litros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702101','0403','Iogurte e leite fermentado em recipiente de conteúdo superior a 2 litros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702200','04039000','Coalhada');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702300','0406','Requeijão e similares, em recipiente de conteúdo inferior ou igual a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702301','0406','Requeijão e similares, em recipiente de conteúdo superior a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702400','0406','Queijos, exceto os dos CEST 17.024.01, 17.024.02, 17.024.03 e 17.024.04');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702401','04061010','Queijo muçarela');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702402','04061090','Queijo minas frescal');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702403','04061090','Queijo ricota');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702404','04061090','Queijo petit suisse');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702500','04051000','Manteiga, em embalagem de conteúdo inferior ou igual a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702501','04051000','Manteiga, em embalagem de conteúdo superior a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702502','04059090','Manteiga de garrafa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702600','15171000','Margarina e creme vegetal em recipiente de conteúdo inferior ou igual a 500 g, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702700','15171000','Margarina e creme vegetal, em recipiente de conteúdo superior a 500 g e inferior ou igual a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702701','15171000','Margarina e creme vegetal, em recipiente de conteúdo superior a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702702','151790','Outras margarinas e cremes vegetais em recipiente de conteúdo inferior a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702800','15162000','Gorduras e óleos vegetais e respectivas frações, parcial ou totalmente hidrogenados, interesterificados, reesterificados ou elaidinizados, mesmo refinados, mas não preparados de outro modo, em recipiente de conteúdo inferior ou igual a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702801','15162000','Gorduras e óleos vegetais e respectivas frações, parcial ou totalmente hidrogenados, interesterificados, reesterificados ou elaidinizados, mesmo refinados, mas não preparados de outro modo, em recipiente de conteúdo superior a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1702900','19019020','Doces de leite');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1703000','19041000','Produtos à base de cereais, obtidos por expansão ou torrefação');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1703000','19049000','Produtos à base de cereais, obtidos por expansão ou torrefação');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1703100','19059090','Salgadinhos diversos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1703200','20052000','Batata frita, inhame e mandioca fritos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1703300','20081','Amendoim e castanhas tipo aperitivo, em embalagem de conteúdo inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1703301','20081','Amendoim e castanhas tipo aperitivo, em embalagem de conteúdo superior a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1703400','21032010','Catchup em embalagens imediatas de conteúdo inferior ou igual a 650 g, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1703500','21039021','Condimentos e temperos compostos, incluindo molho de pimenta e outros molhos, em embalagens imediatas de conteúdo inferior ou igual a 1 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 3 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1703500','21039091','Condimentos e temperos compostos, incluindo molho de pimenta e outros molhos, em embalagens imediatas de conteúdo inferior ou igual a 1 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 3 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1703600','21031010','Molhos de soja preparados em embalagens imediatas de conteúdo inferior ou igual a 650 g, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1703700','21033010','Farinha de mostarda em embalagens de conteúdo inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1703800','21033021','Mostarda preparada em embalagens imediatas de conteúdo inferior ou igual a 650 g, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1703900','21039011','Maionese em embalagens imediatas de conteúdo inferior ou igual a 650 g, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704000','2002','Tomates preparados ou conservados, exceto em vinagre ou em ácido acético, em embalagens de conteúdo inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704100','21032010','Molhos de tomate em embalagens imediatas de conteúdo inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704200','17049090','Barra de cereais');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704200','19042000','Barra de cereais');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704200','19049000','Barra de cereais');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704300','18063120','Barra de cereais contendo cacau');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704300','18063220','Barra de cereais contendo cacau');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704300','18069000','Barra de cereais contendo cacau');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704400','11010010','Farinha de trigo especial, em embalagem inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704401','11010010','Farinha de trigo especial, em embalagem superior a 1 kg e inferior a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704402','11010010','Farinha de trigo especial, em embalagem igual a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704403','11010010','Farinha de trigo especial, em embalagem superior a 5 kg e inferior ou igual a 25 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704404','11010010','Farinha de trigo especial, em embalagem superior a 25 kg e inferior ou igual a 50 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704405','11010010','Farinha de trigo comum, em embalagem igual a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704406','11010010','Farinha de trigo comum, em embalagem superior a 5 kg e inferior ou igual a 25 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704407','11010010','Farinha de trigo comum, em embalagem superior a 25 kg e inferior ou igual a 50 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704408','11010010','Farinha de trigo doméstica especial, em embalagem superior a 5 kg e inferior e igual a 10 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704409','11010010','Farinha de trigo doméstica com fermento, em embalagem superior a 5 kg e inferior e igual a 10 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704410','11010010','Farinha de trigo especial, em embalagem superior a 50 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704411','11010010','Farinha de trigo comum, em embalagem inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704412','11010010','Farinha de trigo comum, em embalagem superior a 1 kg e inferior a 5 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704413','11010010','Farinha de trigo comum, em embalagem superior a 50 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704414','11010010','Farinha de trigo doméstica especial, em embalagem inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704415','11010010','Farinha de trigo doméstica especial, em embalagem superior a 1 kg e inferior a 5 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704416','11010010','Farinha de trigo doméstica especial, em embalagem igual a 5 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704417','11010010','Farinha de trigo doméstica especial, em embalagem superior a 10 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704418','11010010','Farinha de trigo doméstica com fermento, em embalagem inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704419','11010010','Farinha de trigo doméstica com fermento, em embalagem superior a 1 kg e inferior a 5 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704420','11010010','Farinha de trigo doméstica com fermento, em embalagem igual a 5 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704421','11010010','Farinha de trigo doméstica com fermento, em embalagem superior a 10 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704422','11010010','Outras farinhas de trigo, em embalagem inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704423','11010010','Outras farinhas de trigo, em embalagem superior a 1 kg e inferior a 5 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704424','11010010','Outras farinhas de trigo, em embalagem igual a 5 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704425','11010010','Outras farinhas de trigo, em embalagem superior a 5 Kg e inferior ou igual a 25 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704426','11010010','Outras farinhas de trigo, em embalagem superior a 25 Kg e inferior ou igual a 50 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704427','11010010','Outras farinhas de trigo, em embalagem superior a 50 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704500','11010020','Farinha de mistura de trigo com centeio (méteil)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704600','19012000','Misturas e preparações para bolos, em embalagem inferior 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704600','19019090','Misturas e preparações para bolos, em embalagem inferior 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704601','19012000','Misturas e preparações para bolos, em embalagem igual a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704601','19019090','Misturas e preparações para bolos, em embalagem igual a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704602','19012000','Misturas e preparações para bolos, em embalagem superior a 5 kg e inferior ou igual a 25 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704602','19019090','Misturas e preparações para bolos, em embalagem superior a 5 kg e inferior ou igual a 25 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704603','19012000','Misturas e preparações para bolos, em embalagem superior a 25 kg e inferior ou igual a 50 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704603','19019090','Misturas e preparações para bolos, em embalagem superior a 25 kg e inferior ou igual a 50 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704604','19012000','Misturas e preparações para bolos, em embalagem superior a 50 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704604','19019090','Misturas e preparações para bolos, em embalagem superior a 50 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704605','19012000','Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem inferior a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704605','19019090','Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem inferior a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704606','19012000','Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem igual a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704606','19019090','Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem igual a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704607','19012000','Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem superior a 5 kg e inferior ou igual a 25 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704607','19019090','Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem superior a 5 kg e inferior ou igual a 25 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704608','19012000','Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem superior a 25 kg e inferior ou igual a 50 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704608','19019090','Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem superior a 25 kg e inferior ou igual a 50 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704609','19012000','Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem superior a 50 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704609','19019090','Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem superior a 50 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704610','19012000','Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem inferior a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704610','19019090','Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem inferior a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704611','19012000','Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem igual a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704611','19019090','Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem igual a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704612','19012000','Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem superior a 5 kg e inferior ou igual a 25 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704612','19019090','Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem superior a 5 kg e inferior ou igual a 25 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704613','19012000','Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem superior a 25 kg e inferior ou igual a 50 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704613','19019090','Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem superior a 25 kg e inferior ou igual a 50 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704614','19012000','Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem superior a 50 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704614','19019090','Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem superior a 50 Kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704700','19023000','Massas alimentícias tipo instantânea');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704800','1902','Massas alimentícias, cozidas ou recheadas (de carne ou de outras substâncias) ou preparadas de outro modo, exceto as descritas nos CEST 17.047.00, 17.048.01, e 17.048.02');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704801','19024000','Cuscuz');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704802','19022000','Massas alimentícias recheadas (mesmo cozidas ou preparadas de outro modo)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704900','19021','Massas alimentícias do tipo comum, não cozidas, nem recheadas, nem preparadas de outro modo, exceto a descrita no CEST 17.049.03');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704901','19021','Massas alimentícias do tipo sêmola, não cozidas, nem recheadas, nem preparadas de outro modo, exceto a descrita no CEST 17.049.04');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704902','19021','Massas alimentícias do tipo granoduro, não cozidas, nem recheadas, nem preparadas de outro modo, exceto a descrita no CEST 17.049.05');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704903','19021900','Massas alimentícias do tipo comum, não cozidas, nem recheadas, nem preparadas de outro modo, que não contenham ovos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704904','19021900','Massas alimentícias do tipo sêmola, não cozidas, nem recheadas, nem preparadas de outro modo, que não contenham ovos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1704905','19021900','Massas alimentícias do tipo granoduro, não cozidas, nem recheadas, nem preparadas de outro modo, que não contenham ovos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1705000','190520','Pães industrializados, inclusive de especiarias, exceto panetones e bolo de forma');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1705100','19052090','Bolo de forma, inclusive de especiarias');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1705200','19052010','Panetones');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1705300','19053100','Biscoitos e bolachas derivados de farinha de trigo; (exceto dos tipos “cream cracker”, “água e sal”, “maisena”, “maria” e outros de consumo popular que não sejam adicionados de cacau, nem recheados, cobertos ou amanteigados, independentemente de sua denominação comercial)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1705301','19053100','Biscoitos e bolachas derivados de farinha de trigo dos tipos “maisena” e “maria” e outros de consumo popular que não sejam adicionados de cacau, nem recheados, cobertos ou amanteigados, independentemente de sua denominação comercial, exceto o CEST 17.053.02');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1705302','19053100','Biscoitos e bolachas derivados de farinha de trigo dos tipos "cream cracker" e "água e sal" de consumo popular');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1705400','19053100','Biscoitos e bolachas não derivados de farinha de trigo; (exceto dos tipos "cream cracker", "água e sal", "maisena" e "maria" e outros de consumo popular que não sejam adicionados de cacau, nem recheados, cobertos ou amanteigados, independentemente de sua denominação comercial)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1705401','19053100','Biscoitos e bolachas não derivados de farinha de trigo dos tipos "maisena" e "maria" e outros de consumo popular que não sejam adicionados de cacau, nem recheados, cobertos ou amanteigados, independentemente de sua denominação comercial, exceto o CEST 17.054.02');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1705402','19053100','Biscoitos e bolachas não derivados de farinha de trigo dos tipos "cream cracker" e "água e sal" de consumo popular');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1705600','19059020','Biscoitos e bolachas derivados de farinha de trigo dos tipos “cream cracker” e “água e sal”');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1705601','19059020','Biscoitos e bolachas não derivados de farinha de trigo dos tipos “cream cracker” e “água e sal”');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1705602','19059020','Outras bolachas, exceto casquinhas para sorvete e os biscoitos e bolachas relacionados nos CEST 17.056.00 e 17.056.01');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1705700','19053200','“Waffles” e “wafers” - sem cobertura');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1705800','19053200','“Waffles” e “wafers” - com cobertura');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1705900','19054000','Torradas, pão torrado e produtos semelhantes torrados');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1706000','19059010','Outros pães de forma');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1706200','19059090','Outros pães, exceto pão francês de até 200 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1706201','19059090','Outros bolos industrializados e produtos de panificação não especificados anteriormente; exceto casquinhas para sorvete e pães');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1706300','19051000','Pão denominado knackebrot');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1706400','190590','Demais pães industrializados');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1706500','15079011','Óleo de soja refinado, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1706600','1508','Óleo de amendoim refinado, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1706700','1509','Azeites de oliva, em recipientes com capacidade inferior a 2 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 20 mililitros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1706701','1509','Azeites de oliva, em recipientes com capacidade igual ou superior a 2 litros e inferior ou igual a 5 litros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1706702','1509','Azeites de oliva, em recipientes com capacidade superior a 5 litros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1706800','15100000','Outros óleos e respectivas frações, obtidos exclusivamente a partir de azeitonas, mesmo refinados, mas não quimicamente modificados, e misturas desses óleos ou frações com óleos ou frações da posição 15.09, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1706900','15121911','Óleo de girassol em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1706901','15122910','Óleo de algodão refinado em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707000','15141','Óleo de canola, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707100','15151900','Óleo de linhaça refinado, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707200','15152910','Óleo de milho refinado, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707300','15122990','Outros óleos refinados, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707400','15179010','Misturas de óleos refinados, para consumo humano, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707500','1511','Outros óleos vegetais comestíveis não especificados anteriormente');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707500','1513','Outros óleos vegetais comestíveis não especificados anteriormente');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707500','1514','Outros óleos vegetais comestíveis não especificados anteriormente');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707500','1515','Outros óleos vegetais comestíveis não especificados anteriormente');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707500','1516','Outros óleos vegetais comestíveis não especificados anteriormente');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707500','1518','Outros óleos vegetais comestíveis não especificados anteriormente');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707600','16010000','Enchidos (embutidos) e produtos semelhantes, de carne, miudezas ou sangue; exceto salsicha, linguiça e mortadela');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707700','16010000','Salsicha e linguiça, exceto as descritas nos CEST 17.077.01');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707701','16010000','Salsicha em lata');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707800','16010000','Mortadela');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707900','1602','Outras preparações e conservas de carne, miudezas ou de sangue, exceto as descritas nos CEST 17.079.01, 17.079.02, 17.079.03, 17.079.04, 17.079.05, 17.079.06 e 17.079.07');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707901','16023100','Outras preparações e conservas de carne, de miudezas ou de sangue, de aves da posição 01.05: de peruas e de perus.');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707902','16023210','Outras preparações e conservas de carne, de miudezas ou de sangue, de aves da posição 01.05: de galos e de galinhas, com conteúdo de carne ou de miudezas superior ou igual a 57 %, em peso, não cozidas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707903','16023220','Outras preparações e conservas de carne, de miudezas ou de sangue, todas de aves da posição 01.05: de galos e de galinhas, com conteúdo de carne ou de miudezas superior ou igual a 57 %, em peso, cozidas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707904','16024100','Outras preparações e conservas de carne, de miudezas ou de sangue, da espécie suína: pernas e respectivos pedaços');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707905','16024900','Outras preparações e conservas de carne, de miudezas ou de sangue, da espécie suína: outras, incluindo as misturas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707906','16025000','Outras preparações e conservas de carne, de miudezas ou de sangue, da espécie bovina, exceto os descritos no CEST 17.079.07');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1707907','16025000','Apresuntado');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708000','1604','Preparações e conservas de peixes; caviar e seus sucedâneos preparados a partir de ovas de peixe; exceto os descritos nos CEST 17.080.01 e 17.081.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708001','16042010','Outras preparações e conservas de atuns');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708100','1604','Sardinha em conserva');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708200','1605','Crustáceos, moluscos e outros invertebrados aquáticos, preparados ou em conservas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708300','02102000','Carne de gado bovino, ovino e bufalino e produtos comestíveis resultantes da matança desse gado submetidos à salga, secagem ou desidratação');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708300','02109900','Carne de gado bovino, ovino e bufalino e produtos comestíveis resultantes da matança desse gado submetidos à salga, secagem ou desidratação');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708300','1502','Carne de gado bovino, ovino e bufalino e produtos comestíveis resultantes da matança desse gado submetidos à salga, secagem ou desidratação');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708400','0201','Carne de gado bovino, ovino e bufalino e demais produtos comestíveis resultantes da matança desse gado frescos, refrigerados ou congelados');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708400','0202','Carne de gado bovino, ovino e bufalino e demais produtos comestíveis resultantes da matança desse gado frescos, refrigerados ou congelados');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708400','0204','Carne de gado bovino, ovino e bufalino e demais produtos comestíveis resultantes da matança desse gado frescos, refrigerados ou congelados');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708400','0206','Carne de gado bovino, ovino e bufalino e demais produtos comestíveis resultantes da matança desse gado frescos, refrigerados ou congelados');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708500','0204','Carnes de animais das espécies caprina, frescas, refrigeradas ou congeladas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708600','02109900','Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados ou salmourados resultantes do abate de caprinos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708600','15021019','Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados ou salmourados resultantes do abate de caprinos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708600','15029000','Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados ou salmourados resultantes do abate de caprinos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708700','0207','Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de aves, exceto os descritos no CEST 17.087.02');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708700','0209','Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de aves, exceto os descritos no CEST 17.087.02');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708700','02109900','Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de aves, exceto os descritos no CEST 17.087.02');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708700','1501','Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de aves, exceto os descritos no CEST 17.087.02');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708701','0203','Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de suínos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708701','0206','Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de suínos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708701','0209','Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de suínos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708701','02101','Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de suínos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708701','02109900','Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de suínos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708701','1501','Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de suínos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708702','02071','Carnes de aves inteiras e com peso unitário superior a 3 kg, temperadas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708702','02072','Carnes de aves inteiras e com peso unitário superior a 3 kg, temperadas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708800','0710','Produtos hortícolas, cozidos em água ou vapor, congelados, em embalagens de conteúdo inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708801','0710','Produtos hortícolas, cozidos em água ou vapor, congelados, em embalagens de conteúdo superior a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708900','0811','Frutas, não cozidas ou cozidas em água ou vapor, congeladas, mesmo adicionadas de açúcar ou de outros edulcorantes, em embalagens de conteúdo inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1708901','0811','Frutas, não cozidas ou cozidas em água ou vapor, congeladas, mesmo adicionadas de açúcar ou de outros edulcorantes, em embalagens de conteúdo superior a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709000','2001','Produtos hortícolas, frutas e outras partes comestíveis de plantas, preparados ou conservados em vinagre ou em ácido acético, em embalagens de conteúdo inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709001','2001','Produtos hortícolas, frutas e outras partes comestíveis de plantas, preparados ou conservados em vinagre ou em ácido acético, em embalagens de conteúdo superior a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709100','2004','Outros produtos hortícolas preparados ou conservados, exceto em vinagre ou em ácido acético, congelados, com exceção dos produtos da posição 20.06, em embalagens de conteúdo inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709101','2004','Outros produtos hortícolas preparados ou conservados, exceto em vinagre ou em ácido acético, congelados, com exceção dos produtos da posição 20.06, em embalagens de conteúdo superior a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709200','2005','Outros produtos hortícolas preparados ou conservados, exceto em vinagre ou em ácido acético, não congelados, com exceção dos produtos da posição 20.06, excluídos batata, inhame e mandioca fritos, em embalagens de conteúdo inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709201','2005','Outros produtos hortícolas preparados ou conservados, exceto em vinagre ou em ácido acético, não congelados, com exceção dos produtos da posição 20.06, excluídos batata, inhame e mandioca fritos, em embalagens de conteúdo superior a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709300','20060000','Produtos hortícolas, frutas, cascas de frutas e outras partes de plantas, conservados com açúcar (passados por calda, glaceados ou cristalizados), em embalagens de conteúdo inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709301','20060000','Produtos hortícolas, frutas, cascas de frutas e outras partes de plantas, conservados com açúcar (passados por calda, glaceados ou cristalizados), em embalagens de conteúdo superior a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709400','2007','Doces, geleias, “marmelades”, purês e pastas de frutas, obtidos por cozimento, com ou sem adição de açúcar ou de outros edulcorantes, em embalagens de conteúdo inferior ou igual a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709401','2007','Doces, geleias, “marmelades”, purês e pastas de frutas, obtidos por cozimento, com ou sem adição de açúcar ou de outros edulcorantes, em embalagens de conteúdo superior a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709500','2008','Frutas e outras partes comestíveis de plantas, preparadas ou conservadas de outro modo, com ou sem adição de açúcar ou de outros edulcorantes ou de álcool, não especificadas nem compreendidas em outras posições, excluídos os amendoins e castanhas tipo aperitivo, da posição 2008.1, em embalagens de conteúdo inferior ou igual a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709501','2008','Frutas e outras partes comestíveis de plantas, preparadas ou conservadas de outro modo, com ou sem adição de açúcar ou de outros edulcorantes ou de álcool, não especificadas nem compreendidas em outras posições, excluídos os amendoins e castanhas tipo aperitivo, da posição 2008.1, em embalagens superior a 1 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709600','0901','Café torrado e moído, em embalagens de conteúdo inferior ou igual a 2 kg, exceto os classificados nos CEST 17.096.04 e 17.096.05');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709601','0901','Café torrado e moído, em embalagens de conteúdo superior a 2 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709602','0901','Café torrado em grão, em embalagens de conteúdo inferior ou igual a 2 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709603','0901','Café torrado em grão, em embalagens de conteúdo superior a 2 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709604','0901','Café torrado e moído, em cápsulas, exceto os descritos no CEST 17.096.05');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709605','0901','Café descafeinado torrado e moído, em cápsulas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709700','0902','Chá, mesmo aromatizado');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709700','12119090','Chá, mesmo aromatizado');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709700','21069090','Chá, mesmo aromatizado');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709800','090300','Mate');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709900','17011','Açúcar refinado, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709900','17019900','Açúcar refinado, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709901','17011','Açúcar refinado, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709901','17019900','Açúcar refinado, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709902','17011','Açúcar refinado, em embalagens de conteúdo superior a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1709902','17019900','Açúcar refinado, em embalagens de conteúdo superior a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710000','17019100','Açúcar refinado adicionado de aromatizante ou de corante em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710001','17019100','Açúcar refinado adicionado de aromatizante ou de corante em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710002','17019100','Açúcar refinado adicionado de aromatizante ou de corante em embalagens de conteúdo superior a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710100','17011','Açúcar cristal, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710100','17019900','Açúcar cristal, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710101','17019900','Açúcar cristal, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710101','17011','Açúcar cristal, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710102','17011','Açúcar cristal, em embalagens de conteúdo superior a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710102','17019900','Açúcar cristal, em embalagens de conteúdo superior a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710200','17019100','Açúcar cristal adicionado de aromatizante ou de corante, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710201','17019100','Açúcar cristal adicionado de aromatizante ou de corante, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710202','170191','Açúcar cristal adicionado de aromatizante ou de corante, em embalagens de conteúdo superior a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710300','17011','Outros tipos de açúcar, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710300','17019900','Outros tipos de açúcar, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710301','17011','Outros tipos de açúcar, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710301','17019900','Outros tipos de açúcar, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710302','17011','Outros tipos de açúcar, em embalagens de conteúdo superior a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710302','17019900','Outros tipos de açúcar, em embalagens de conteúdo superior a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710400','17019100','Outros tipos de açúcar adicionado de aromatizante ou de corante, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710401','17019100','Outros tipos de açúcar adicionado de aromatizante ou de corante, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710402','17019100','Outros tipos de açúcar adicionado de aromatizante ou de corante, em embalagens de conteúdo superior a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710500','1702','Outros açúcares em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710501','1702','Outros açúcares, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710502','1702','Outros açúcares, em embalagens de conteúdo superior a 5 kg');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710600','20081900','Milho para pipoca (micro-ondas)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710700','21011','Extratos, essências e concentrados de café e preparações à base destes extratos, essências ou concentrados ou à base de café, em embalagens de conteúdo inferior ou igual a 500 g, exceto os classificados no CEST 17.107.01');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710701','21011','Extratos, essências e concentrados de café e preparações à base destes extratos, essências ou concentrados ou à base de café, em cápsulas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710800','210120','Extratos, essências e concentrados de chá ou de mate e preparações à base destes extratos, essências ou concentrados ou à base de chá ou de mate, em embalagens de conteúdo inferior ou igual a 500 g, exceto as bebidas prontas à base de mate ou chá e os itens classificados no CEST 17.108.01');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710801','210120','Extratos, essências e concentrados de chá ou de mate e preparações à base destes extratos, essências ou concentrados ou à base de chá ou de mate, em cápsulas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710900','19019090','Preparações em pó para cappuccino e similares, em embalagens de conteúdo inferior ou igual a 500 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710900','21011190','Preparações em pó para cappuccino e similares, em embalagens de conteúdo inferior ou igual a 500 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1710900','21011200','Preparações em pó para cappuccino e similares, em embalagens de conteúdo inferior ou igual a 500 g');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1711000','22021000','Refrescos e outras bebidas prontas para beber, à base de chá e mate');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1711100','22021000','Refrescos e outras bebidas não alcoólicas, exceto os refrigerantes e as demais bebidas nos CEST 03.007.00 e 17.110.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1711200','22029900','Néctares de frutas e outras bebidas não alcoólicas prontas para beber, exceto isotônicos e energéticos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1711300','210120','Bebidas prontas à base de mate ou chá');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1711300','22029900','Bebidas prontas à base de mate ou chá');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1711400','22029900','Bebidas prontas à base de café');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1711500','22029900','Bebidas alimentares prontas à base de soja, leite ou cacau, inclusive os produtos denominados bebidas lácteas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1900100','32131000','Tinta guache');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1900200','39162000','Espiral - perfil para encadernação, de plástico e outros materiais classificados nas posições 3901 a 3914');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1900300','39161000','Outros espirais - perfil para encadernação, de plástico e outros materiais classificados nas posições 3901 a 3914');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1900300','391690','Outros espirais - perfil para encadernação, de plástico e outros materiais classificados nas posições 3901 a 3914');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1900400','39261000','Artigos de escritório e artigos escolares de plástico e outros materiais classificados nas posições 3901 a 3914, exceto estojos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1900500','42021','Maletas e pastas para documentos e de estudante, e artefatos semelhantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1900500','42029','Maletas e pastas para documentos e de estudante, e artefatos semelhantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1900501','42021','Baús, malas e maletas para viagem');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1900501','42029','Baús, malas e maletas para viagem');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1900600','39269090','Prancheta de plástico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1900700','48022090','Bobina para fax');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1900700','48119090','Bobina para fax');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1900800','4802549','Papel seda');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1900900','48025499','Bobina para máquina de calcular, PDV ou equipamentos similares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1900900','48025799','Bobina para máquina de calcular, PDV ou equipamentos similares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1900900','48162000','Bobina para máquina de calcular, PDV ou equipamentos similares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1901000','4802569','Cartolina escolar e papel cartão, brancos e coloridos; recados auto adesivos (LP note); papéis de presente, todos cortados em tamanho pronto para uso escolar e doméstico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1901000','4802579','Cartolina escolar e papel cartão, brancos e coloridos; recados auto adesivos (LP note); papéis de presente, todos cortados em tamanho pronto para uso escolar e doméstico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1901000','4802589','Cartolina escolar e papel cartão, brancos e coloridos; recados auto adesivos (LP note); papéis de presente, todos cortados em tamanho pronto para uso escolar e doméstico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1901100','37031010','Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia “Thermo-autochrome”, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1901100','37031029','Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia “Thermo-autochrome”, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1901100','37032000','Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia “Thermo-autochrome”, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1901100','37039010','Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia “Thermo-autochrome”, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1901100','37040000','Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia “Thermo-autochrome”, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1901100','48022010','Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia “Thermo-autochrome”, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1901100','48022090','Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia “Thermo-autochrome”, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1901200','48101390','Papel almaço');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1901300','48169010','Papel hectográfico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1901400','39202019','Papel celofane e tipo celofane');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1901500','48062000','Papel impermeável');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1901600','48081000','Papel crepon');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1901700','48102290','Papel fantasia');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1901800','4809','Papel-carbono, papel autocopiativo (exceto os vendidos em rolos de diâmetro igual ou superior a 60 cm e os vendidos em folhas de formato igual ou superior a 60 cm de altura e igual ou superior a 90 cm de largura) e outros papéis para cópia ou duplicação (incluídos os papéis para estênceis ou para chapas ofsete), estênceis completos e chapas ofsete, de papel, em folhas, mesmo acondicionados em caixas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1901800','4816','Papel-carbono, papel autocopiativo (exceto os vendidos em rolos de diâmetro igual ou superior a 60 cm e os vendidos em folhas de formato igual ou superior a 60 cm de altura e igual ou superior a 90 cm de largura) e outros papéis para cópia ou duplicação (incluídos os papéis para estênceis ou para chapas ofsete), estênceis completos e chapas ofsete, de papel, em folhas, mesmo acondicionados em caixas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1901900','4817','Envelopes, aerogramas, bilhetes-postais não ilustrados e cartões para correspondência, de papel ou cartão, caixas, sacos e semelhantes, de papel ou cartão, contendo um sortido de artigos para correspondência');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1902000','48201000','Livros de registro e de contabilidade, blocos de notas, de encomendas, de recibos, de apontamentos, de papel para cartas, agendas e artigos semelhantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1902100','48202000','Cadernos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1902200','48203000','Classificadores, capas para encadernação (exceto as capas para livros) e capas de processos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1902300','48204000','Formulários em blocos tipo “manifold”, mesmo com folhas intercaladas de papel-carbono');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1902400','48205000','Álbuns para amostras ou para coleções');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1902500','48209000','Pastas para documentos, outros artigos escolares, de escritório ou de papelaria, de papel ou cartão e capas para livros, de papel ou cartão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1902600','49090000','Cartões postais impressos ou ilustrados, cartões impressos com votos ou mensagens pessoais, mesmo ilustrados, com ou sem envelopes, guarnições ou aplicações (conhecidos como cartões de expressão social - de época/sentimento)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1902700','96081000','Canetas esferográficas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1902800','96082000','Canetas e marcadores, com ponta de feltro ou com outras pontas porosas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1902900','96083000','Canetas tinteiro');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1903000','9608','Outras canetas; sortidos de canetas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1903100','480256','Papel cortado “cutsize” (tipo A3, A4, ofício I e II, carta e outros)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1903200','52105990','Papel camurça');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('1903300','76071190','Papel laminado e papel espelho');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2000100','12119090','Henna (embalagens de conteúdo inferior ou igual a 200 g)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2000101','12119090','Henna (embalagens de conteúdo superior a 200 g)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2000200','27121000','Vaselina');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2000300','28142000','Amoníaco em solução aquosa (amônia)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2000400','28470000','Peróxido de hidrogênio, em embalagens de conteúdo inferior ou igual a 500 ml');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2000500','30067000','Lubrificação íntima');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2000600','3301','Óleos essenciais (desterpenados ou não), incluídos os chamados “concretos” ou “absolutos”; resinoides; oleorresinas de extração; soluções concentradas de óleos essenciais em gorduras, em óleos fixos, em ceras ou em matérias análogas, obtidas por tratamento de flores através de substâncias gordas ou por maceração; subprodutos terpênicos residuais da desterpenação dos óleos essenciais; águas destiladas aromáticas e soluções aquosas de óleos essenciais, em embalagens de conteúdo inferior ou igual a 500 ml');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2000700','33030010','Perfumes (extratos)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2000800','33030020','Águas-de-colônia');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2000900','33041000','Produtos de maquilagem para os lábios');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2001000','33042010','Sombra, delineador, lápis para sobrancelhas e rímel');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2001100','33042090','Outros produtos de maquilagem para os olhos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2001200','33043000','Preparações para manicuros e pedicuros, incluindo removedores de esmalte à base de acetona');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2001300','33049100','Pós, incluídos os compactos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2001400','33049910','Cremes de beleza, cremes nutritivos e loções tônicas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2001500','33049990','Outros produtos de beleza ou de maquilagem preparados e preparações para conservação ou cuidados da pele, exceto as preparações solares e antissolares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2001600','33049990','Preparações solares e antissolares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2001700','33051000','Xampus para o cabelo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2001800','33052000','Preparações para ondulação ou alisamento, permanentes, dos cabelos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2001900','33053000','Laquês para o cabelo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2002000','33059000','Outras preparações capilares, incluindo máscaras e finalizadores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2002100','33059000','Condicionadores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2002200','33059000','Tintura para o cabelo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2002300','33061000','Dentifrícios');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2002400','33062000','Fios utilizados para limpar os espaços interdentais (fios dentais)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2002500','33069000','Outras preparações para higiene bucal ou dentária');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2002600','33071000','Preparações para barbear (antes, durante ou após)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2002700','33072010','Desodorantes (desodorizantes) corporais líquidos, exceto os classificados no CEST 20.027.01');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2002701','33072010','Loções e óleos desodorantes hidratantes líquidos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2002800','33072010','Antiperspirantes líquidos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2002900','33072090','Outros desodorantes (desodorizantes) corporais, exceto os classificados no CEST 20.029.01');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2002901','33072090','Outras loções e óleos desodorantes hidratantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2003000','33072090','Outros antiperspirantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2003100','33073000','Sais perfumados e outras preparações para banhos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2003200','33079000','Outros produtos de perfumaria preparados');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2003201','33079000','Outros produtos de toucador preparados');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2003300','33079000','Soluções para lentes de contato ou para olhos artificiais');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2003400','34011190','Sabões de toucador em barras, pedaços ou figuras moldados');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2003500','34011900','Outros sabões, produtos e preparações, em barras, pedaços ou figuras moldados');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2003501','34011900','Lenços umedecidos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2003600','34012010','Sabões de toucador sob outras formas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2003700','34013000','Produtos e preparações orgânicos tensoativos para lavagem da pele, na forma de líquido ou de creme, acondicionados para venda a retalho, mesmo contendo sabão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2003800','40149010','Bolsa para gelo ou para água quente');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2003900','40149090','Chupetas e bicos para mamadeiras e para chupetas, de borracha');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2004000','39249000','Chupetas e bicos para mamadeiras e para chupetas, de silicone');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2004000','39269040','Chupetas e bicos para mamadeiras e para chupetas, de silicone');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2004000','39269090','Chupetas e bicos para mamadeiras e para chupetas, de silicone');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2004100','42021','Malas e maletas de toucador');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2004200','48181000','Papel higiênico - folha simples');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2004300','48181000','Papel higiênico - folha dupla e tripla');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2004400','48182000','Lenços (incluídos os de maquilagem) e toalhas de mão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2004500','48182000','Papel toalha de uso institucional do tipo comercializado em rolos igual ou superior a 80 metros e do tipo comercializado em folhas intercaladas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2004600','48183000','Toalhas e guardanapos de mesa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2004700','48189090','Toalhas de cozinha (papel toalha de uso doméstico)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2004800','96190000','Fraldas, exceto os descritos no CEST 20.048.01');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2004801','96190000','Fraldas de fibras têxteis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2004900','96190000','Tampões higiênicos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2005000','96190000','Absorventes higiênicos externos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2005100','56012190','Hastes flexíveis (uso não medicinal)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2005200','56039290','Sutiã descartável, assemelhados e papel para depilação');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2005300','82032090','Pinças para sobrancelhas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2005400','82141000','Espátulas (artigos de cutelaria)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2005500','82142000','Utensílios e sortidos de utensílios de manicuros ou de pedicuros (incluídas as limas para unhas)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2005600','90251110','Termômetros, inclusive o digital');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2005600','90251990','Termômetros, inclusive o digital');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2005700','96032','Escovas e pincéis de barba, escovas para cabelos, para cílios ou para unhas e outras escovas de toucador de pessoas, incluídas as que sejam partes de aparelhos, exceto escovas de dentes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2005800','96032100','Escovas de dentes, incluídas as escovas para dentaduras');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2005900','96033000','Pincéis para aplicação de produtos cosméticos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2006000','96050000','Sortidos de viagem, para toucador de pessoas para costura ou para limpeza de calçado ou de roupas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2006100','9615','Pentes, travessas para cabelo e artigos semelhantes; grampos (alfinetes) para cabelo; pinças (pinceguiches), onduladores, bobes (rolos) e artefatos semelhantes para penteados, e suas partes, exceto os classificados na posição 8516 e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2006200','96162000','Borlas ou esponjas para pós ou para aplicação de outros cosméticos ou de produtos de toucador');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2006300','39233000','Mamadeiras');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2006300','39241000','Mamadeiras');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2006300','39249000','Mamadeiras');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2006300','40149090','Mamadeiras');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2006300','70102000','Mamadeiras');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2006400','82121020','Aparelhos e lâminas de barbear');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2006400','82122010','Aparelhos e lâminas de barbear');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2100100','73211100','Fogões de cozinha de uso doméstico e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2100100','73218100','Fogões de cozinha de uso doméstico e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2100100','73219000','Fogões de cozinha de uso doméstico e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2100200','84181000','Combinações de refrigeradores e congeladores (“freezers”), munidos de portas exteriores separadas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2100300','84182100','Refrigeradores do tipo doméstico, de compressão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2100400','84182900','Outros refrigeradores do tipo doméstico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2100500','84183000','Congeladores (“freezers”) horizontais tipo arca, de capacidade não superior a 800 litros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2100600','84184000','Congeladores (“freezers”) verticais tipo armário, de capacidade não superior a 900 litros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2100700','841850','Outros móveis (arcas, armários, vitrines, balcões e móveis semelhantes) para a conservação e exposição de produtos, que incorporem um equipamento para a produção de frio');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2100800','8418699','Mini adega e similares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2100900','84186999','Máquinas para produção de gelo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2101000','84189900','Partes dos refrigeradores, congeladores, mini adegas e similares, máquinas para produção de gelo e bebedouros descritos nos CEST 21.002.00, 21.003.00, 21.004.00, 21.005.00, 21.006.00, 21.007.00, 21.008.00, 21.009.00 e 21.013.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2101100','842112','Secadoras de roupa de uso doméstico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2101200','84211990','Outras secadoras de roupas e centrífugas de uso doméstico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2101300','84186931','Bebedouros refrigerados para água');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2101400','84219','Partes das secadoras de roupas e centrífugas de uso doméstico e dos aparelhos para filtrar ou depurar água, descritos nos CEST 21.011.00 e 21.012.00 e 21.098.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2101500','84221100','Máquinas de lavar louça do tipo doméstico e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2101500','84229010','Máquinas de lavar louça do tipo doméstico e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2101600','844331','Máquinas que executem pelo menos duas das seguintes funções: impressão, cópia ou transmissão de telecópia (fax), capazes de ser conectadas a uma máquina automática para processamento de dados ou a uma rede');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2101700','844332','Outras impressoras, máquinas copiadoras e telecopiadores (fax), mesmo combinados entre si, capazes de ser conectados a uma máquina automática para processamento de dados ou a uma rede');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2101800','84439','Partes e acessórios de máquinas e aparelhos de impressão por meio de blocos, cilindros e outros elementos de impressão da posição 8442; e de outras impressoras, máquinas copiadoras e telecopiadores (fax), mesmo combinados entre si');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2101900','84501100','Máquinas de lavar roupa, mesmo com dispositivos de secagem, de uso doméstico, de capacidade não superior a 10 kg, em peso de roupa seca, inteiramente automáticas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2102000','84501200','Outras máquinas de lavar roupa, mesmo com dispositivos de secagem, de uso doméstico, com secador centrífugo incorporado');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2102100','84501900','Outras máquinas de lavar roupa, mesmo com dispositivos de secagem, de uso doméstico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2102200','845020','Máquinas de lavar roupa, mesmo com dispositivos de secagem, de uso doméstico, de capacidade superior a 10 kg, em peso de roupa seca');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2102300','845090','Partes de máquinas de lavar roupa, mesmo com dispositivos de secagem, de uso doméstico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2102400','84512100','Máquinas de secar de uso doméstico de capacidade não superior a 10 kg, em peso de roupa seca');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2102500','84512990','Outras máquinas de secar de uso doméstico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2102600','845190','Partes de máquinas de secar de uso doméstico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2102700','84521000','Máquinas de costura de uso doméstico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2102800','847130','Máquinas automáticas para processamento de dados, portáteis, de peso não superior a 10 kg, contendo pelo menos uma unidade central de processamento, um teclado e uma tela');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2102900','84714','Outras máquinas automáticas para processamento de dados');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2103000','84715010','Unidades de processamento, de pequena capacidade, exceto as das subposições 8471.41 ou 8471.49, podendo conter, no mesmo corpo, um ou dois dos seguintes tipos de unidades: unidade de memória, unidade de entrada e unidade de saída; baseadas em microprocessadores, com capacidade de instalação, dentro do mesmo gabinete, de unidades de memória da subposição 8471.70, podendo conter múltiplos conectores de expansão (“slots”), e valor FOB inferior ou igual a US$ 12.500,00, por unidade');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2103100','8471605','Unidades de entrada, exceto as classificadas no código 8471.60.54');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2103200','84716090','Outras unidades de entrada ou de saída, podendo conter, no mesmo corpo, unidades de memória');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2103300','847170','Unidades de memória');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2103400','847190','Outras máquinas automáticas para processamento de dados e suas unidades; leitores magnéticos ou ópticos, máquinas para registrar dados em suporte sob forma codificada, e máquinas para processamento desses dados, não especificadas nem compreendidas em outras posições');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2103500','847330','Partes e acessórios das máquinas da posição 84.71');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2103600','85043','Outros transformadores, exceto os classificados nos códigos 8504.33.00 e 8504.34.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2103700','85044010','Carregadores de acumuladores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2103800','85044040','Equipamentos de alimentação ininterrupta de energia (UPS ou “no break”)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2103900','85078000','Outros acumuladores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2104000','8508','Aspiradores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2104100','8509','Aparelhos eletromecânicos de motor elétrico incorporado, de uso doméstico e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2104200','85098010','Enceradeiras');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2104300','85161000','Chaleiras elétricas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2104400','85164000','Ferros elétricos de passar');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2104500','85165000','Fornos de micro-ondas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2104600','85166000','Outros fornos; fogareiros (incluídas as chapas de cocção), grelhas e assadeiras, exceto os portáteis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2104700','85166000','Outros fornos; fogareiros (incluídas as chapas de cocção), grelhas e assadeiras, portáteis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2104800','85167100','Outros aparelhos eletrotérmicos de uso doméstico - Cafeteiras');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2104900','85167200','Outros aparelhos eletrotérmicos de uso doméstico - Torradeiras');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2105000','851679','Outros aparelhos eletrotérmicos de uso doméstico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2105100','85169000','Partes das chaleiras, ferros, fornos e outros aparelhos eletrotérmicos da posição 85.16, descritos nos CEST 21.043.00, 21.044.00, 21.045.00, 21.046.00, 21.047.00, 21.048.00, 21.049.00 e 21.050.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2105200','85171100','Aparelhos telefônicos por fio com unidade auscultador - microfone sem fio');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2105300','8517123','Telefones para redes celulares, exceto por satélite, os de uso automotivo e os classificados no CEST 21.053.01');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2105301','85171231','Telefones para redes celulares portáteis, exceto por satélite');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2105400','851712','Outros telefones para outras redes sem fio, exceto para redes de celulares e os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2105500','85171891','Outros aparelhos telefônicos não combinados com outros aparelhos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2105501','85171899','Outros aparelhos telefônicos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2105600','8517625','Aparelhos para transmissão ou recepção de voz, imagem ou outros dados em rede com fio, exceto os classificados nos códigos 8517.62.51, 8517.62.52 e 8517.62.53');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2105700','8518','Microfones e seus suportes; alto-falantes, mesmo montados nos seus receptáculos, fones de ouvido (auscultadores), mesmo combinados com microfone e conjuntos ou sortidos constituídos por um microfone e um ou mais alto-falantes, amplificadores elétricos de audiofrequência, aparelhos elétricos de amplificação de som; suas partes e acessórios; exceto os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2105800','8519','Aparelhos de radiodifusão suscetíveis de funcionarem sem fonte externa de energia. Aparelhos de gravação de som; aparelhos de reprodução de som; aparelhos de gravação e de reprodução de som; partes e acessórios; exceto os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2105800','8522','Aparelhos de radiodifusão suscetíveis de funcionarem sem fonte externa de energia. Aparelhos de gravação de som; aparelhos de reprodução de som; aparelhos de gravação e de reprodução de som; partes e acessórios; exceto os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2105800','85271','Aparelhos de radiodifusão suscetíveis de funcionarem sem fonte externa de energia. Aparelhos de gravação de som; aparelhos de reprodução de som; aparelhos de gravação e de reprodução de som; partes e acessórios; exceto os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2105900','85198190','Outros aparelhos de gravação de som; aparelhos de reprodução de som; aparelhos de gravação e de reprodução de som; partes e acessórios; exceto os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2106000','85219010','Gravador-reprodutor e editor de imagem e som, em discos, por meio magnético, óptico ou optomagnético, exceto de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2106100','85219090','Outros aparelhos videofônicos de gravação ou reprodução, mesmo incorporando um receptor de sinais videofônicos, exceto os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2106200','85235110','Cartões de memória ("memory cards")');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2106300','85235200','Cartões inteligentes ("smart cards")');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2106400','85235200','Cartões inteligentes ("sim cards")');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2106500','8525802','Câmeras fotográficas digitais e câmeras de vídeo e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2106600','85279','Outros aparelhos receptores para radiodifusão, mesmo combinados num invólucro, com um aparelho de gravação ou de reprodução de som, ou com um relógio, inclusive caixa acústica para Home Theaters classificados na posição 8518');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2106700','85284929','Monitores e projetores que não incorporem aparelhos receptores de televisão, policromáticos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2106700','85285920','Monitores e projetores que não incorporem aparelhos receptores de televisão, policromáticos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2106700','852869','Monitores e projetores que não incorporem aparelhos receptores de televisão, policromáticos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2106701','85286200','Projetores capazes de serem conectados diretamente a uma máquina automática para processamento de dados da posição 84.71 e concebidos para serem utilizados com esta máquina');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2106800','85285220','Outros monitores capazes de serem conectados diretamente a uma máquina automática para processamento de dados da posição 84.71 e concebidos para serem utilizados com esta máquina, policromáticos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2106900','85287','Aparelhos receptores de televisão, mesmo que incorporem um aparelho receptor de radiodifusão ou um aparelho de gravação ou reprodução de som ou de imagens - Televisores de CRT (tubo de raios catódicos)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2107000','85287','Aparelhos receptores de televisão, mesmo que incorporem um aparelho receptor de radiodifusão ou um aparelho de gravação ou reprodução de som ou de imagens - Televisores de LCD (Display de Cristal Líquido)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2107100','85287','Aparelhos receptores de televisão, mesmo que incorporem um aparelho receptor de radiodifusão ou um aparelho de gravação ou reprodução de som ou de imagens - Televisores de Plasma');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2107200','85287','Outros aparelhos receptores de televisão não dotados de monitores ou display de vídeo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2107300','85287','Outros aparelhos receptores de televisão não relacionados nos CEST 21.069.00, 21.070.00, 21.071.00 e 21.072.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2107400','900659','Câmeras fotográficas dos tipos utilizadas para preparação de clichês ou cilindros de impressão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2107500','90064000','Câmeras fotográficas para filmes de revelação e copiagem instantâneas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2107600','90189050','Aparelhos de diatermia');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2107700','90191000','Aparelhos de massagem');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2107800','90328911','Reguladores de voltagem eletrônicos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2107900','95045000','Consoles e máquinas de jogos de vídeo, exceto os classificados na subposição 9504.30');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2108000','8517621','Multiplexadores e concentradores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2108100','85176222','Centrais automáticas privadas, de capacidade inferior ou igual a 25 ramais');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2108200','85176239','Outros aparelhos para comutação');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2108300','8517624','Roteadores digitais, em redes com ou sem fio');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2108400','85176262','Aparelhos emissores com receptor incorporado de sistema troncalizado (“trunking”), de tecnologia celular');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2108500','8517629','Outros aparelhos de recepção, conversão e transmissão ou regeneração de voz, imagens ou outros dados, incluindo os aparelhos de comutação e roteamento');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2108600','85177021','Antenas próprias para telefones celulares portáteis, exceto as telescópicas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2108700','821490','Aparelhos ou máquinas de barbear, máquinas de cortar o cabelo ou de tosquiar e aparelhos de depilar, e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2108700','8510','Aparelhos ou máquinas de barbear, máquinas de cortar o cabelo ou de tosquiar e aparelhos de depilar, e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2108800','84145','Ventiladores, exceto os de uso agrícola');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2108900','84145990','Ventiladores de uso agrícola');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2109000','84146000','Coifas com dimensão horizontal máxima não superior a 120 cm');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2109100','84149020','Partes de ventiladores ou coifas aspirantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2109200','841510','Máquinas e aparelhos de ar condicionado contendo um ventilador motorizado e dispositivos próprios para modificar a temperatura e a umidade, incluídos as máquinas e aparelhos em que a umidade não seja regulável separadamente');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2109200','84158','Máquinas e aparelhos de ar condicionado contendo um ventilador motorizado e dispositivos próprios para modificar a temperatura e a umidade, incluídos as máquinas e aparelhos em que a umidade não seja regulável separadamente');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2109300','84151011','Aparelhos de ar-condicionado tipo Split System (sistema com elementos separados) com unidade externa e interna');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2109400','84151019','Aparelhos de ar-condicionado com capacidade inferior ou igual a 30.000 frigorias/hora');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2109500','84151090','Aparelhos de ar-condicionado com capacidade acima de 30.000 frigorias/hora');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2109600','84159010','Unidades evaporadoras (internas) de aparelho de ar-condicionado do tipo Split System (sistema com elementos separados), com capacidade inferior ou igual a 30.000 frigorias/hora');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2109700','84159020','Unidades condensadoras (externas) de aparelho de ar-condicionado do tipo Split System (sistema com elementos separados), com capacidade inferior ou igual a 30.000 frigorias/hora');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2109800','84212100','Aparelhos elétricos para filtrar ou depurar água (purificadores de água refrigerados), exceto os itens classificados no CEST 21.098.01');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2109801','84212100','Outros aparelhos elétricos para filtrar ou depurar água');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2109900','84243010','Lavadora de alta pressão e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2109900','84243090','Lavadora de alta pressão e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2109900','84249090','Lavadora de alta pressão e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2110000','84672100','Furadeiras elétricas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2110100','85162','Aparelhos elétricos para aquecimento de ambientes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2110200','85163100','Secadores de cabelo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2110300','85163200','Outros aparelhos para arranjos do cabelo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2110400','8527','Aparelhos receptores para radiodifusão, mesmo combinados num mesmo invólucro, com um aparelho de gravação ou de reprodução de som, ou com um relógio, exceto os classificados na posição 8527.1, 8527.2 e 8527.9 que sejam de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2110500','84796000','Climatizadores de ar');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2110600','84159090','Outras partes para máquinas e aparelhos de ar-condicionado que contenham um ventilador motorizado e dispositivos próprios para modificar a temperatura e a umidade, incluindo as máquinas e aparelhos em que a umidade não seja regulável separadamente');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2110700','85258019','Câmeras de televisão e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2110800','84231000','Balanças de uso doméstico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2110900','8540','Tubos e válvulas, eletrônicos, de cátodo quente, cátodo frio ou fotocátodo (por exemplo, tubos e válvulas, de vácuo, de vapor ou de gás, ampolas retificadoras de vapor de mercúrio, tubos catódicos, tubos e válvulas para câmeras de televisão)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2111000','8517','Aparelhos elétricos para telefonia; outros aparelhos para transmissão ou recepção de voz, imagens ou outros dados, incluídos os aparelhos para comunicação em redes por fio ou redes sem fio (tal como uma rede local (LAN) ou uma rede de área estendida (WAN), incluídas suas partes, exceto os de uso automotivo e os classificados nos códigos 8517.62.51, 8517.62.52 e 8517.62.53');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2111100','8517','Interfones, seus acessórios, tomadas e “plugs”');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2111200','8529','Partes reconhecíveis como exclusiva ou principalmente destinadas aos aparelhos das posições 8525 a 8528; exceto as de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2111300','8531','Aparelhos elétricos de sinalização acústica ou visual (por exemplo, campainhas, sirenes, quadros indicadores, aparelhos de alarme para proteção contra roubo ou incêndio); exceto os de uso automotivo e os classificados nas posições 8531.10 e 8531.80.00.');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2111400','853110','Aparelhos elétricos de alarme, para proteção contra roubo ou incêndio e aparelhos semelhantes, exceto os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2111500','85318000','Outros aparelhos de sinalização acústica ou visual, exceto os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2111600','853400','Circuitos impressos, exceto os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2111700','85414011','Diodos emissores de luz (LED), exceto diodos “laser”');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2111700','85414021','Diodos emissores de luz (LED), exceto diodos “laser”');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2111700','85414022','Diodos emissores de luz (LED), exceto diodos “laser”');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2111800','85437092','Eletrificadores de cercas eletrônicos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2111900','90303','Aparelhos e instrumentos para medida ou controle da tensão, intensidade, resistência ou da potência, sem dispositivo registrador; exceto os de uso automotivo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2112000','903089','Analisadores lógicos de circuitos digitais, de espectro de frequência, frequencímetros, fasímetros, e outros instrumentos e aparelhos de controle de grandezas elétricas e detecção');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2112100','910700','Interruptores horários e outros aparelhos que permitam acionar um mecanismo em tempo determinado, munidos de maquinismo de aparelhos de relojoaria ou de motor síncrono');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2112200','9405','Aparelhos de iluminação (incluídos os projetores) e suas partes, não especificados nem compreendidos em outras posições; anúncios, cartazes ou tabuletas e placas indicadoras luminosos, e artigos semelhantes, contendo uma fonte luminosa fixa permanente, e suas partes não especificadas nem compreendidas em outras posições, com exceção dos itens classificados nos CEST 21.123.00, 21.124.00 e 21.125.00');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2112300','940510','Lustres e outros aparelhos elétricos de iluminação, próprios para serem suspensos ou fixados no teto ou na parede, exceto os dos tipos utilizados na iluminação pública; e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2112300','94059','Lustres e outros aparelhos elétricos de iluminação, próprios para serem suspensos ou fixados no teto ou na parede, exceto os dos tipos utilizados na iluminação pública; e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2112400','94052000','Abajures de cabeceiras, de escritório e lampadários de interior, elétricos e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2112400','94059','Abajures de cabeceiras, de escritório e lampadários de interior, elétricos e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2112500','940540','Outros aparelhos elétricos de iluminação e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2112500','94059','Outros aparelhos elétricos de iluminação e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2112600','85423190','Microprocessador');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2200100','2309','Ração tipo “pet” para animais domésticos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2300100','210500','Sorvetes de qualquer espécie');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2300200','1806','Preparados para fabricação de sorvete em máquina');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2300200','1901','Preparados para fabricação de sorvete em máquina');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2300200','2106','Preparados para fabricação de sorvete em máquina');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2400100','3208','Tintas, vernizes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2400100','3209','Tintas, vernizes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2400100','321000','Tintas, vernizes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2400200','2821','Xadrez e pós assemelhados, exceto pigmentos à base de dióxido de titânio classificados no código 3206.11.19');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2400200','32041700','Xadrez e pós assemelhados, exceto pigmentos à base de dióxido de titânio classificados no código 3206.11.19');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2400200','3206','Xadrez e pós assemelhados, exceto pigmentos à base de dióxido de titânio classificados no código 3206.11.19');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2400300','3204','Corantes para aplicação em bases, tintas e vernizes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2400300','32050000','Corantes para aplicação em bases, tintas e vernizes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2400300','3206','Corantes para aplicação em bases, tintas e vernizes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2400300','3212','Corantes para aplicação em bases, tintas e vernizes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2500100','87021000','Veículos automóveis para transporte de 10 pessoas ou mais, incluindo o motorista, unicamente com motor de pistão, de ignição por compressão (diesel ou semidiesel), com volume interno de habitáculo, destinado a passageiros e motorista, superior a 6 m³, mas inferior a 9 m³');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2500200','87024090','Veículos automóveis para transporte de 10 pessoas ou mais, incluindo o motorista, unicamente com motor elétrico para propulsão, com volume interno de habitáculo, destinado a passageiros e motorista, superior a 6 m³, mas inferior a 9 m³');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2500300','87032100','Automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada não superior a 1000 cm³');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2500400','87032210','Automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada superior a 1000 cm³, mas não superior a 1500 cm³, com capacidade de transporte de pessoas sentadas inferior ou igual a 6, incluído o condutor, exceto carro celular');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2500500','87032290','Outros automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada superior a 1000 cm³, mas não superior a 1500 cm³, exceto carro celular');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2500600','87032310','Automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada superior a 1500 cm³, mas não superior a 3000 cm³, com capacidade de transporte de pessoas sentadas inferior ou igual a 6, incluído o condutor, exceto carro celular, carro funerário e automóveis de corrida');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2500700','87032390','Outros automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada superior a 1500 cm³, mas não superior a 3000 cm³, exceto carro celular, carro funerário e automóveis de corrida');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2500800','87032410','Automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada superior a 3000 cm³, com capacidade de transporte de pessoas sentadas inferior ou igual a 6, incluído o condutor, exceto carro celular, carro funerário e automóveis de corrida');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2500900','87032490','Outros automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada superior a 3000 cm³, exceto carro celular, carro funerário e automóveis de corrida');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2501000','87033210','Automóveis unicamente com motor diesel ou semidiesel, de cilindrada superior a 1500 cm³, mas não superior a 2500 cm³, com capacidade de transporte de pessoas sentadas inferior ou igual a 6, incluído o condutor, exceto ambulância, carro celular e carro funerário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2501100','87033290','Outros automóveis unicamente com motor diesel ou semidiesel, de cilindrada superior a 1500 cm³, mas não superior a 2500 cm³, exceto ambulância, carro celular e carro funerário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2501200','87033310','Automóveis unicamente com motor diesel ou semidiesel, de cilindrada superior a 2500 cm³, com capacidade de transporte de pessoas sentadas inferior ou igual a 6, incluído o condutor, exceto carro celular e carro funerário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2501300','87033390','Outros automóveis unicamente com motor diesel ou semidiesel, de cilindrada superior a 2500 cm³, exceto carro celular e carro funerário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2501400','87042110','Veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, chassis com motor diesel ou semidiesel e cabina, exceto caminhão de peso em carga máxima superior a 3,9 toneladas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2501500','87042120','Veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, com motor diesel ou semidiesel, com caixa basculante, exceto caminhão de peso em carga máxima superior a 3,9 toneladas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2501600','87042130','Veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, frigoríficos ou isotérmicos, com motor diesel ou semidiesel, exceto caminhão de peso em carga máxima superior a 3,9 toneladas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2501700','87042190','Outros veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, com motor diesel ou semidiesel, exceto carro-forte para transporte de valores e caminhão de peso em carga máxima superior a 3,9 toneladas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2501800','87043110','Veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, com motor a explosão, chassis e cabina, exceto caminhão de peso em carga máxima superior a 3,9 toneladas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2501900','87043120','Veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, com motor explosão com caixa basculante, exceto caminhão de peso em carga máxima superior a 3,9 toneladas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2502000','87043130','Veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, frigoríficos ou isotérmicos com motor explosão, exceto caminhão de peso em carga máxima superior a 3,9 toneladas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2502100','87043190','Outros veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, com motor a explosão, exceto carro-forte para transporte de valores e caminhão de peso em carga máxima superior a 3,9 toneladas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2502200','87022000','Veículos automóveis para transporte de 10 pessoas ou mais, incluindo o motorista, com motor de pistão, de ignição por compressão (diesel ou semidiesel) e um motor elétrico, com volume interno de habitáculo, destinado a passageiros e motorista, superior a 6 m³, mas inferior a 9 m³');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2502300','87023000','Veículos automóveis para transporte de 10 pessoas ou mais, incluindo o motorista, com motor de pistão alternativo, de ignição por centelha (faísca) e um motor elétrico, com volume interno de habitáculo, destinado a passageiros e motorista, superior a 6 m³, mas inferior a 9 m³');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2502400','87029000','Outros veículos automóveis para transporte de 10 pessoas ou mais, incluindo o motorista, com volume interno de habitáculo, destinado a passageiros e motorista, superior a 6 m³, mas inferior a 9 m³');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2502500','87034000','Automóveis equipados para propulsão, simultaneamente, com um motor de pistão alternativo de ignição por centelha (faísca*) e um motor elétrico, exceto os suscetíveis de serem carregados por conexão a uma fonte externa de energia elétrica, o carro celular e o carro funerário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2502600','87035000','Automóveis equipados para propulsão, simultaneamente, com um motor de pistão por compressão (diesel ou semidiesel) e um motor elétrico, exceto os suscetíveis de serem carregados por conexão a uma fonte externa de energia elétrica, exceto o carro celular e o carro funerário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2502700','87036000','Automóveis equipados para propulsão, simultaneamente, com um motor de pistão alternativo de ignição por centelha (faísca*) e um motor elétrico, suscetíveis de serem carregados por conexão a uma fonte externa de energia elétrica, exceto o carro celular e o carro funerário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2502800','87037000','Automóveis equipados para propulsão, simultaneamente, com um motor de pistão por compressão (diesel ou semidiesel) e um motor elétrico, suscetíveis de serem carregados por conexão a uma fonte externa de energia elétrica, exceto o carro celular e o carro funerário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2502900','87038000','Outros veículos, equipados unicamente com motor elétrico para propulsão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2600100','8711','Motocicletas (incluídos os ciclomotores) e outros ciclos equipados com motor auxiliar, mesmo com carro lateral; carros laterais');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2800100','33030010','Perfumes (extratos)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2800200','33030020','Águas-de-colônia');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2800300','33041000','Produtos de maquiagem para os lábios');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2800400','33042010','Sombra, delineador, lápis para sobrancelhas e rímel');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2800500','33042090','Outros produtos de maquiagem para os olhos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2800600','33043000','Preparações para manicuros e pedicuros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2800700','33049100','Pós para maquiagem, incluindo os compactos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2800800','33049910','Cremes de beleza, cremes nutritivos e loções tônicas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2800900','33049990','Outros produtos de beleza ou de maquiagem preparados e preparações para conservação ou cuidados da pele, exceto as preparações antissolares e os bronzeadores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2801000','33049990','Preparações antissolares e os bronzeadores');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2801100','33051000','Xampus para o cabelo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2801200','33052000','Preparações para ondulação ou alisamento, permanentes, dos cabelos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2801300','33059000','Outras preparações capilares');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2801400','33059000','Tintura para o cabelo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2801500','33071000','Preparações para barbear (antes, durante ou após)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2801600','33072010','Desodorantes corporais e antiperspirantes, líquidos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2801700','33072090','Outros desodorantes corporais e antiperspirantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2801800','33079000','Outros produtos de perfumaria ou de toucador preparados');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2801900','33079000','Outras preparações cosméticas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2802000','34011190','Sabões de toucador, em barras, pedaços ou figuras moldadas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2802100','34011900','Outros sabões, produtos e preparações orgânicos tensoativos, inclusive papel, pastas (ouates), feltros e falsos tecidos, impregnados, revestidos ou recobertos de sabão ou de detergentes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2802200','34012010','Sabões de toucador sob outras formas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2802300','34013000','Produtos e preparações orgânicos tensoativos para lavagem da pele, em forma de líquido ou de creme, acondicionados para venda a retalho, mesmo contendo sabão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2802400','48182000','Lenços de papel, incluindo os de desmaquiar');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2802401','48182000','Toalhas de mão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2802500','82141000','Apontadores de lápis para maquiagem');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2802501','82141000','Espátulas, abre-cartas e raspadeiras');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2802502','82141000','Lâminas de espátulas, de abre-cartas, de raspadeiras e de apontadores de lápis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2802600','82142000','Utensílios e sortidos de utensílios de manicuros ou de pedicuros (incluindo as limas para unhas)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2802700','96032900','Escovas e pincéis de barba, escovas para cabelos, para cílios ou para unhas e outras escovas de toucador de pessoas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2802701','96032900','Vassouras e escovas, mesmo constituindo partes de máquinas, de aparelhos ou de veículos, vassouras mecânicas de uso manual não motorizadas, pincéis e espanadores; cabeças preparadas para escovas, pincéis e artigos semelhantes; bonecas e rolos para pintura; rodos de borracha ou de matérias flexíveis semelhantes, outros');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2802800','96033000','Pincéis para aplicação de produtos cosméticos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2802801','96033000','Pincéis e escovas, para artistas e pincéis de escrever');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2802900','96161000','Vaporizadores de toucador, suas armações e cabeças de armações');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2803000','96162000','Borlas ou esponjas para pós ou para aplicação de outros cosméticos ou de produtos de toucador');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2803100','42021','Malas e maletas de toucador');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2803200','9615','Pentes, travessas para cabelo e artigos semelhantes; grampos (alfinetes) para cabelo; pinças (“pinceguiches”), onduladores, bobs (rolos) e artefatos semelhantes para penteados, e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2803300','39233000','Mamadeiras');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2803300','39241000','Mamadeiras');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2803300','39249000','Mamadeiras');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2803300','40149090','Mamadeiras');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2803300','70102000','Mamadeiras');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2803400','40149090','Chupetas e bicos para mamadeiras e para chupetas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2803500','12119090','Outras plantas e partes, para perfumaria, medicina e semelhantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2803600','39262000','Vestuário e seus acessórios, de plásticos, inclusive luvas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2803700','39264000','Estatuetas e outros objetos de ornamentação, de plásticos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2803800','39269090','Outras obras de plásticos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2803900','42022210','Bolsas de folhas de plástico');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2804000','42022220','Bolsas de matérias têxteis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2804100','42022900','Bolsas de outras matérias');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2804200','42023900','Artigos de bolsos/bolsas, de outras matérias');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2804300','42029200','Outros artefatos, de folhas de plásticos ou matérias têxteis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2804400','42029900','Outros artefatos, de outras matérias');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2804500','48192000','Caixas e cartonagens, dobráveis, de papel/cartão, não ondulados');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2804600','48194000','Outros sacos, bolsas e cartuchos, de papel ou cartão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2804700','48211000','Etiquetas de papel ou cartão, impressas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2804800','49111090','Outros impressos publicitários, catálogos comerciais e semelhantes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2804900','61159900','Outras meias de malha de outras matérias têxteis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805000','62171000','Outros acessórios confeccionados, de vestuário');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805100','63026000','Roupas de toucador/cozinha, de tecidos atoalhados de algodão');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805200','63079090','Outros artefatos têxteis confeccionados');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805300','65069900','Chapéus e outros artefatos de outras matérias, exceto de malha');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805400','95059000','Artigos para outras festas, carnaval ou outros divertimentos');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805500','33','Produtos destinados à higiene bucal');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805600','33','Outros produtos cosméticos e de higiene pessoal não relacionados em outros itens deste anexo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805600','34','Outros produtos cosméticos e de higiene pessoal não relacionados em outros itens deste anexo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805700','14','Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805700','39','Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805700','40','Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805700','44','Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805700','48','Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805700','63','Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805700','65','Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805700','67','Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805700','70','Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805700','82','Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805700','90','Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805700','96','Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805800','39','Acessórios (por exemplo, bijuterias, relógios, óculos de sol, bolsas, mochilas, frasqueiras, carteiras, porta-cartões, porta-documentos, porta-celulares e embalagens presenteáveis (por exemplo, caixinhas de papel), entre outros itens assemelhados)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805800','42','Acessórios (por exemplo, bijuterias, relógios, óculos de sol, bolsas, mochilas, frasqueiras, carteiras, porta-cartões, porta-documentos, porta-celulares e embalagens presenteáveis (por exemplo, caixinhas de papel), entre outros itens assemelhados)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805800','48','Acessórios (por exemplo, bijuterias, relógios, óculos de sol, bolsas, mochilas, frasqueiras, carteiras, porta-cartões, porta-documentos, porta-celulares e embalagens presenteáveis (por exemplo, caixinhas de papel), entre outros itens assemelhados)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805800','90','Acessórios (por exemplo, bijuterias, relógios, óculos de sol, bolsas, mochilas, frasqueiras, carteiras, porta-cartões, porta-documentos, porta-celulares e embalagens presenteáveis (por exemplo, caixinhas de papel), entre outros itens assemelhados)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805800','91','Acessórios (por exemplo, bijuterias, relógios, óculos de sol, bolsas, mochilas, frasqueiras, carteiras, porta-cartões, porta-documentos, porta-celulares e embalagens presenteáveis (por exemplo, caixinhas de papel), entre outros itens assemelhados)');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805900','61','Vestuário e seus acessórios; calçados, polainas e artefatos semelhantes, e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805900','62','Vestuário e seus acessórios; calçados, polainas e artefatos semelhantes, e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2805900','64','Vestuário e seus acessórios; calçados, polainas e artefatos semelhantes, e suas partes');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806000','42','Outros artigos de vestuário em geral, exceto os relacionados no item anterior');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806000','52','Outros artigos de vestuário em geral, exceto os relacionados no item anterior');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806000','55','Outros artigos de vestuário em geral, exceto os relacionados no item anterior');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806000','58','Outros artigos de vestuário em geral, exceto os relacionados no item anterior');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806000','63','Outros artigos de vestuário em geral, exceto os relacionados no item anterior');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806000','65','Outros artigos de vestuário em geral, exceto os relacionados no item anterior');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806100','39','Artigos de casa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806100','40','Artigos de casa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806100','52','Artigos de casa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806100','56','Artigos de casa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806100','62','Artigos de casa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806100','63','Artigos de casa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806100','66','Artigos de casa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806100','69','Artigos de casa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806100','70','Artigos de casa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806100','73','Artigos de casa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806100','76','Artigos de casa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806100','82','Artigos de casa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806100','83','Artigos de casa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806100','84','Artigos de casa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806100','91','Artigos de casa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806100','94','Artigos de casa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806100','96','Artigos de casa');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806200','13','Produtos das indústrias alimentares e bebidas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806200','15','Produtos das indústrias alimentares e bebidas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806200','23','Produtos das indústrias alimentares e bebidas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806200','16','Produtos das indústrias alimentares e bebidas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806200','17','Produtos das indústrias alimentares e bebidas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806200','18','Produtos das indústrias alimentares e bebidas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806200','19','Produtos das indústrias alimentares e bebidas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806200','20','Produtos das indústrias alimentares e bebidas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806200','21','Produtos das indústrias alimentares e bebidas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806200','22','Produtos das indústrias alimentares e bebidas');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806300','22','Produtos de limpeza e conservação doméstica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806300','27','Produtos de limpeza e conservação doméstica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806300','28','Produtos de limpeza e conservação doméstica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806300','29','Produtos de limpeza e conservação doméstica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806300','33','Produtos de limpeza e conservação doméstica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806300','34','Produtos de limpeza e conservação doméstica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806300','35','Produtos de limpeza e conservação doméstica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806300','38','Produtos de limpeza e conservação doméstica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806300','39','Produtos de limpeza e conservação doméstica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806300','63','Produtos de limpeza e conservação doméstica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806300','68','Produtos de limpeza e conservação doméstica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806300','73','Produtos de limpeza e conservação doméstica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806300','84','Produtos de limpeza e conservação doméstica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806300','85','Produtos de limpeza e conservação doméstica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806300','96','Produtos de limpeza e conservação doméstica');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806400','39','Artigos infantis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806400','49','Artigos infantis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806400','95','Artigos infantis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2806400','96','Artigos infantis');
insert into TAB_CEST(CEST,NCM,DESCRICAO) values ('2899900','NT','Outros produtos comercializados pelo sistema de marketing direto porta-a-porta a consumidor final não relacionados em outros itens deste anexo');
```

## Tabela.csv

- Estrutura: segmento;descricao;item;cest;ncm;descricao;data_inicio;data_fim

```
segmento;descricao;item;cest;ncm;descricao;data_inicio;data_fim
01;Autopeças;1.0;0100100;38151210;Catalisadores em colmeia cerâmica ou metálica para conversão catalítica de gases de escape de veículos e outros catalisadores;2017-07-01;
01;Autopeças;1.0;0100100;38151290;Catalisadores em colmeia cerâmica ou metálica para conversão catalítica de gases de escape de veículos e outros catalisadores;2017-07-01;
01;Autopeças;2.0;0100200;3917;Tubos e seus acessórios (por exemplo, juntas, cotovelos, flanges, uniões), de plásticos;2017-07-01;
01;Autopeças;3.0;0100300;39181000;Protetores de caçamba;2017-07-01;
01;Autopeças;4.0;0100400;39233000;Reservatórios de óleo;2017-07-01;
01;Autopeças;5.0;0100500;39263000;Frisos, decalques, molduras e acabamentos;2017-07-01;
01;Autopeças;6.0;0100600;40103;Correias de transmissão de borracha vulcanizada, de matérias têxteis, mesmo impregnadas, revestidas ou recobertas, de plástico, ou estratificadas com plástico ou reforçadas com metal ou com outras matérias;2017-07-01;
01;Autopeças;6.0;0100600;59100000;Correias de transmissão de borracha vulcanizada, de matérias têxteis, mesmo impregnadas, revestidas ou recobertas, de plástico, ou estratificadas com plástico ou reforçadas com metal ou com outras matérias;2017-07-01;
01;Autopeças;7.0;0100700;40169300;Juntas, gaxetas e outros elementos com função semelhante de vedação;2017-07-01;
01;Autopeças;7.0;0100700;4823909;Juntas, gaxetas e outros elementos com função semelhante de vedação;2017-07-01;
01;Autopeças;8.0;0100800;40161010;Partes de veículos automóveis, tratores e máquinas autopropulsadas;2017-07-01;
01;Autopeças;9.0;0100900;57050000;Tapetes, revestimentos, mesmo confeccionados, batentes, buchas e coxins;2017-07-01;
01;Autopeças;9.0;0100900;40169990;Tapetes, revestimentos, mesmo confeccionados, batentes, buchas e coxins;2017-07-01;
01;Autopeças;10.0;0101000;59039000;Tecidos impregnados, revestidos, recobertos ou estratificados, com plástico;2017-07-01;
01;Autopeças;11.0;0101100;59090000;Mangueiras e tubos semelhantes, de matérias têxteis, mesmo com reforço ou acessórios de outras matérias;2017-07-01;
01;Autopeças;12.0;0101200;63061;Encerados e toldos;2017-07-01;
01;Autopeças;13.0;0101300;65061000;Capacetes e artefatos de uso semelhante, de proteção, para uso em motocicletas, incluídos ciclomotores;2017-07-01;
01;Autopeças;14.0;0101400;6813;Guarnições de fricção (por exemplo, placas, rolos, tiras, segmentos, discos, anéis, pastilhas), não montadas, para freios, embreagens ou qualquer outro mecanismo de fricção, à base de amianto, de outras substâncias minerais ou de celulose, mesmo combinadas com têxteis ou outras matérias;2017-07-01;
01;Autopeças;15.0;0101500;70072100;Vidros de dimensões e formatos que permitam aplicação automotiva;2017-07-01;
01;Autopeças;15.0;0101500;70071100;Vidros de dimensões e formatos que permitam aplicação automotiva;2017-07-01;
01;Autopeças;16.0;0101600;70091000;Espelhos retrovisores;2017-07-01;
01;Autopeças;17.0;0101700;70140000;Lentes de faróis, lanternas e outros utensílios;2017-07-01;
01;Autopeças;18.0;0101800;73110000;Cilindro de aço para GNV (gás natural veicular);2017-07-01;
01;Autopeças;19.0;0101900;73110000;Recipientes para gases comprimidos ou liquefeitos, de ferro fundido, ferro ou aço, exceto o descrito no item 18.0;2017-07-01;
01;Autopeças;20.0;0102000;7320;Molas e folhas de molas, de ferro ou aço;2017-07-01;
01;Autopeças;21.0;0102100;7325;Obras moldadas, de ferro fundido, ferro ou aço, exceto as do código 7325.91.00;2017-07-01;
01;Autopeças;22.0;0102200;780600;Peso de chumbo para balanceamento de roda;2017-07-01;
01;Autopeças;23.0;0102300;80070090;Peso para balanceamento de roda e outros utensílios de estanho;2017-07-01;
01;Autopeças;24.0;0102400;830120;Fechaduras e partes de fechaduras;2017-07-01;
01;Autopeças;24.0;0102400;830160;Fechaduras e partes de fechaduras;2017-07-01;
01;Autopeças;25.0;0102500;830170;Chaves apresentadas isoladamente;2017-07-01;
01;Autopeças;26.0;0102600;83021000;Dobradiças, guarnições, ferragens e artigos semelhantes de metais comuns;2017-07-01;
01;Autopeças;26.0;0102600;83023000;Dobradiças, guarnições, ferragens e artigos semelhantes de metais comuns;2017-07-01;
01;Autopeças;27.0;0102700;831000;Triângulo de segurança;2017-07-01;
01;Autopeças;28.0;0102800;84073;Motores de pistão alternativo dos tipos utilizados para propulsão de veículos do Capítulo 87;2017-07-01;
01;Autopeças;29.0;0102900;840820;Motores dos tipos utilizados para propulsão de veículos automotores;2017-07-01;
01;Autopeças;30.0;0103000;84099;Partes reconhecíveis como exclusiva ou principalmente destinadas aos motores das posições 8407 ou 8408;2017-07-01;
01;Autopeças;31.0;0103100;84122;Motores hidráulicos;2017-07-01;
01;Autopeças;32.0;0103200;841330;Bombas para combustíveis, lubrificantes ou líquidos de arrefecimento, próprias para motores de ignição por centelha ou por compressão;2017-07-01;
01;Autopeças;33.0;0103300;84141000;Bombas de vácuo;2017-07-01;
01;Autopeças;34.0;0103400;8414801;Compressores e turbocompressores de ar;2017-07-01;
01;Autopeças;34.0;0103400;8414802;Compressores e turbocompressores de ar;2017-07-01;
01;Autopeças;35.0;0103500;8414909;Partes das bombas, compressores e turbocompressores dos CEST 01.032.00, 01.033.00 e 01.034.00;2017-07-01;
01;Autopeças;35.0;0103500;84139190;Partes das bombas, compressores e turbocompressores dos CEST 01.032.00, 01.033.00 e 01.034.00;2017-07-01;
01;Autopeças;35.0;0103500;84149010;Partes das bombas, compressores e turbocompressores dos CEST 01.032.00, 01.033.00 e 01.034.00;2017-07-01;
01;Autopeças;35.0;0103500;8414903;Partes das bombas, compressores e turbocompressores dos CEST 01.032.00, 01.033.00 e 01.034.00;2017-07-01;
01;Autopeças;36.0;0103600;841520;Máquinas e aparelhos de ar condicionado;2017-07-01;
01;Autopeças;37.0;0103700;84212300;Aparelhos para filtrar óleos minerais nos motores de ignição por centelha ou por compressão;2017-07-01;
01;Autopeças;38.0;0103800;84212990;Filtros a vácuo;2017-07-01;
01;Autopeças;39.0;0103900;84219;Partes dos aparelhos para filtrar ou depurar líquidos ou gases;2017-07-01;
01;Autopeças;40.0;0104000;84241000;Extintores, mesmo carregados;2017-07-01;
01;Autopeças;41.0;0104100;84213100;Filtros de entrada de ar para motores de ignição por centelha ou por compressão;2017-07-01;
01;Autopeças;42.0;0104200;84213920;Depuradores por conversão catalítica de gases de escape;2017-07-01;
01;Autopeças;43.0;0104300;84254200;Macacos;2017-07-01;
01;Autopeças;44.0;0104400;84311010;Partes para macacos do CEST 01.043.00;2017-07-01;
01;Autopeças;45.0;0104500;8431492;Partes reconhecíveis como exclusiva ou principalmente destinadas às máquinas agrícolas ou rodoviárias;2017-07-01;
01;Autopeças;45.1;0104501;84339090;Partes reconhecíveis como exclusiva ou principalmente destinadas às máquinas agrícolas ou rodoviárias;2017-07-01;
01;Autopeças;46.0;0104600;84811000;Válvulas redutoras de pressão;2017-07-01;
01;Autopeças;47.0;0104700;84812;Válvulas para transmissão óleo-hidráulicas ou pneumáticas;2017-07-01;
01;Autopeças;48.0;0104800;84818092;Válvulas solenoides;2017-07-01;
01;Autopeças;49.0;0104900;8482;Rolamentos;2017-07-01;
01;Autopeças;50.0;0105000;8483;"Árvores de transmissão (incluídas as árvores de cames e virabrequins) e manivelas; mancais e bronzes; engrenagens e rodas de fricção; eixos de esferas ou de roletes; redutores, multiplicadores, caixas de transmissão e variadores de velocidade, incluídos os conversores de torque; volantes e polias, incluídas as polias para cadernais; embreagens e dispositivos de acoplamento, incluídas as juntas de articulação";2017-07-01;
01;Autopeças;51.0;0105100;8484;"Juntas metaloplásticas; jogos ou sortidos de juntas de composições diferentes, apresentados em bolsas, envelopes ou embalagens semelhantes; juntas de vedação mecânicas (selos mecânicos)";2017-07-01;
01;Autopeças;52.0;0105200;850520;Acoplamentos, embreagens, variadores de velocidade e freios, eletromagnéticos;2017-07-01;
01;Autopeças;53.0;0105300;850710;Acumuladores elétricos de chumbo, do tipo utilizado para o arranque dos motores de pistão, exceto os classificados no CEST 01.053.01;2017-07-01;
01;Autopeças;53.1;0105301;85071010;Acumuladores elétricos de chumbo, do tipo utilizado para o arranque dos motores de pistão e de capacidade inferior ou igual a 20 Ah e tensão inferior ou igual a 12 V;2017-07-01;
01;Autopeças;54.0;0105400;8511;"Aparelhos e dispositivos elétricos de ignição ou de arranque para motores de ignição por centelha ou por compressão (por exemplo, magnetos, dínamos-magnetos, bobinas de ignição, velas de ignição ou de aquecimento, motores de arranque); geradores (dínamos e alternadores, por exemplo) e conjuntores-disjuntores utilizados com estes motores";2017-07-01;
01;Autopeças;55.0;0105500;851240;Aparelhos elétricos de iluminação ou de sinalização (exceto os da posição 8539), limpadores de para-brisas, degeladores e desembaçadores (desembaciadores) elétricos e suas partes;2017-07-01;
01;Autopeças;55.0;0105500;851220;Aparelhos elétricos de iluminação ou de sinalização (exceto os da posição 8539), limpadores de para-brisas, degeladores e desembaçadores (desembaciadores) elétricos e suas partes;2017-07-01;
01;Autopeças;55.0;0105500;85129000;Aparelhos elétricos de iluminação ou de sinalização (exceto os da posição 8539), limpadores de para-brisas, degeladores e desembaçadores (desembaciadores) elétricos e suas partes;2017-07-01;
01;Autopeças;56.0;0105600;85171213;Telefones móveis do tipo dos utilizados em veículos automóveis.;2017-07-01;
01;Autopeças;57.0;0105700;8518;Alto-falantes, amplificadores elétricos de audiofrequência e partes;2017-07-01;
01;Autopeças;58.0;0105800;85185000;Aparelhos elétricos de amplificação de som para veículos automotores;2017-07-01;
01;Autopeças;59.0;0105900;851981;Aparelhos de reprodução de som;2017-07-01;
01;Autopeças;60.0;0106000;8525501;Aparelhos transmissores (emissores) de radiotelefonia ou radiotelegrafia (rádio receptor/transmissor);2017-07-01;
01;Autopeças;60.0;0106000;85256010;Aparelhos transmissores (emissores) de radiotelefonia ou radiotelegrafia (rádio receptor/transmissor);2017-07-01;
01;Autopeças;61.0;0106100;85272100;Aparelhos receptores de radiodifusão que só funcionem com fonte externa de energia combinados com um aparelho de gravação ou de reprodução de som, do tipo utilizado em veículos automóveis;2017-07-01;
01;Autopeças;62.0;0106200;85272900;Outros aparelhos receptores de radiodifusão que só funcionem com fonte externa de energia, do tipo utilizado em veículos automóveis;2017-07-01;
01;Autopeças;62.1;0106201;85219090;Outros aparelhos videofônicos de gravação ou de reprodução, mesmo incorporando um receptor de sinais videofônicos, dos tipos utilizados exclusivamente em veículos automotores;2017-07-01;
01;Autopeças;63.0;0106300;85291090;Antenas;2017-07-01;
01;Autopeças;64.0;0106400;853400;Circuitos impressos;2017-07-01;
01;Autopeças;65.0;0106500;853650;Interruptores e seccionadores e comutadores;2017-07-01;
01;Autopeças;65.0;0106500;853530;Interruptores e seccionadores e comutadores;2017-07-01;
01;Autopeças;66.0;0106600;85361000;Fusíveis e corta-circuitos de fusíveis;2017-07-01;
01;Autopeças;67.0;0106700;85362000;Disjuntores;2017-07-01;
01;Autopeças;68.0;0106800;85364;Relés;2017-07-01;
01;Autopeças;69.0;0106900;8538;Partes reconhecíveis como exclusivas ou principalmente destinados aos aparelhos dos CEST 01.065.00, 01.066.00, 01.067.00 e 01.068.00;2017-07-01;
01;Autopeças;70.0;0107000;853910;Faróis e projetores, em unidades seladas;2017-07-01;
01;Autopeças;71.0;0107100;85392;Lâmpadas e tubos de incandescência, exceto de raios ultravioleta ou infravermelhos;2017-07-01;
01;Autopeças;72.0;0107200;85442000;Cabos coaxiais e outros condutores elétricos coaxiais;2017-07-01;
01;Autopeças;73.0;0107300;85443000;Jogos de fios para velas de ignição e outros jogos de fios;2017-07-01;
01;Autopeças;74.0;0107400;8707;Carroçarias para os veículos automóveis das posições 8701 a 8705, incluídas as cabinas;2017-07-01;
01;Autopeças;75.0;0107500;8708;Partes e acessórios dos veículos automóveis das posições 8701 a 8705;2017-07-01;
01;Autopeças;76.0;0107600;87141;Parte e acessórios de motocicletas (incluídos os ciclomotores);2017-07-01;
01;Autopeças;77.0;0107700;87169090;Engates para reboques e semirreboques;2017-07-01;
01;Autopeças;78.0;0107800;902610;"Medidores de nível; Medidores de vazão";2017-07-01;
01;Autopeças;79.0;0107900;902620;Aparelhos para medida ou controle da pressão;2017-07-01;
01;Autopeças;80.0;0108000;9029;Contadores, indicadores de velocidade e tacômetros, suas partes e acessórios;2017-07-01;
01;Autopeças;81.0;0108100;90303321;Amperímetros;2017-07-01;
01;Autopeças;82.0;0108200;90318040;Aparelhos digitais, de uso em veículos automóveis, para medida e indicação de múltiplas grandezas tais como: velocidade média, consumos instantâneo e médio e autonomia (computador de bordo);2017-07-01;
01;Autopeças;83.0;0108300;9032892;Controladores eletrônicos;2017-07-01;
01;Autopeças;84.0;0108400;91040000;Relógios para painéis de instrumentos e relógios semelhantes;2017-07-01;
01;Autopeças;85.0;0108500;94019090;Assentos e partes de assentos;2017-07-01;
01;Autopeças;85.0;0108500;94012000;Assentos e partes de assentos;2017-07-01;
01;Autopeças;86.0;0108600;96138000;Acendedores;2017-07-01;
01;Autopeças;87.0;0108700;4009;Tubos de borracha vulcanizada não endurecida, mesmo providos de seus acessórios;2017-07-01;
01;Autopeças;88.0;0108800;68129910;Juntas de vedação de cortiça natural e de amianto;2017-07-01;
01;Autopeças;88.0;0108800;45049000;Juntas de vedação de cortiça natural e de amianto;2017-07-01;
01;Autopeças;89.0;0108900;48234000;Papel-diagrama para tacógrafo, em disco;2017-07-01;
01;Autopeças;90.0;0109000;39191010;"Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários";2017-07-01;
01;Autopeças;90.0;0109000;39191020;"Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários";2017-07-01;
01;Autopeças;90.0;0109000;39199010;"Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários";2017-07-01;
01;Autopeças;90.0;0109000;39199020;"Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários";2017-07-01;
01;Autopeças;90.0;0109000;39199090;"Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários";2017-07-01;
01;Autopeças;90.0;0109000;87082999;"Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários";2017-07-01;
01;Autopeças;90.0;0109000;39191090;"Fitas, tiras, adesivos, autocolantes, de plástico, refletores, mesmo em rolos; placas metálicas com película de plástico refletora, próprias para colocação em carrocerias, para-choques de veículos de carga, motocicletas, ciclomotores, capacetes, bonés de agentes de trânsito e de condutores de veículos, atuando como dispositivos refletivos de segurança rodoviários";2017-07-01;
01;Autopeças;91.0;0109100;84123110;Cilindros pneumáticos;2017-07-01;
01;Autopeças;92.0;0109200;84138100;Bomba elétrica de lavador de para-brisa;2017-07-01;
01;Autopeças;92.0;0109200;84131900;Bomba elétrica de lavador de para-brisa;2017-07-01;
01;Autopeças;92.0;0109200;84135090;Bomba elétrica de lavador de para-brisa;2017-07-01;
01;Autopeças;93.0;0109300;84136019;Bomba de assistência de direção hidráulica;2017-07-01;
01;Autopeças;93.0;0109300;84137010;Bomba de assistência de direção hidráulica;2017-07-01;
01;Autopeças;94.0;0109400;84145910;Motoventiladores;2017-07-01;
01;Autopeças;94.0;0109400;84145990;Motoventiladores;2017-07-01;
01;Autopeças;95.0;0109500;84213990;Filtros de pólen do ar-condicionado;2017-07-01;
01;Autopeças;96.0;0109600;85011019;Máquina de vidro elétrico de porta;2017-07-01;
01;Autopeças;97.0;0109700;85013110;Motor de limpador de para-brisa;2017-07-01;
01;Autopeças;98.0;0109800;85045000;Bobinas de reatância e de autoindução;2017-07-01;
01;Autopeças;99.0;0109900;850730;Baterias de chumbo e de níquel-cádmio;2017-07-01;
01;Autopeças;99.0;0109900;850720;Baterias de chumbo e de níquel-cádmio;2017-07-01;
01;Autopeças;100.0;0110000;85123000;Aparelhos de sinalização acústica (buzina);2017-07-01;
01;Autopeças;101.0;0110100;9032899;Instrumentos para regulação de grandezas não elétricas;2017-07-01;
01;Autopeças;101.0;0110100;9032898;Instrumentos para regulação de grandezas não elétricas;2017-07-01;
01;Autopeças;102.0;0110200;90271000;Analisadores de gases ou de fumaça (sonda lambda);2017-07-01;
01;Autopeças;103.0;0110300;40081100;Perfilados de borracha vulcanizada não endurecida;2017-07-01;
01;Autopeças;104.0;0110400;56012219;Artefatos de pasta de fibra de uso automotivo;2017-07-01;
01;Autopeças;105.0;0110500;57032000;Tapetes/carpetes - nailón;2017-07-01;
01;Autopeças;106.0;0110600;57033000;Tapetes de matérias têxteis sintéticas;2017-07-01;
01;Autopeças;107.0;0110700;59119000;Forração interior capacete;2017-07-01;
01;Autopeças;108.0;0110800;69039099;Outros para-brisas;2017-07-01;
01;Autopeças;109.0;0110900;70072900;Moldura com espelho;2017-07-01;
01;Autopeças;110.0;0111000;73145000;Corrente de transmissão;2017-07-01;
01;Autopeças;111.0;0111100;73151100;Corrente transmissão;2017-07-01;
01;Autopeças;112.0;0111200;73151210;Outras correntes de transmissão;2017-07-01;
01;Autopeças;113.0;0111300;84189900;Condensador tubular metálico;2017-07-01;
01;Autopeças;114.0;0111400;841950;Trocadores de calor;2017-07-01;
01;Autopeças;115.0;0111500;84249090;Partes de aparelhos mecânicos de pulverizar ou dispersar;2017-07-01;
01;Autopeças;116.0;0111600;84254910;Macacos manuais para veículos;2017-07-01;
01;Autopeças;117.0;0111700;84314100;Caçambas, pás, ganchos e tenazes para máquinas rodoviárias;2017-07-01;
01;Autopeças;118.0;0111800;85016100;Geradores de corrente alternada de potência não superior a 75 kva;2017-07-01;
01;Autopeças;119.0;0111900;85311090;Aparelhos elétricos para alarme de uso automotivo;2017-07-01;
01;Autopeças;120.0;0112000;90141000;Bússolas;2017-07-01;
01;Autopeças;121.0;0112100;90251990;Indicadores de temperatura;2017-07-01;
01;Autopeças;122.0;0112200;90259010;Partes de indicadores de temperatura;2017-07-01;
01;Autopeças;123.0;0112300;902690;Partes de aparelhos de medida ou controle;2017-07-01;
01;Autopeças;124.0;0112400;90321010;Termostatos;2017-07-01;
01;Autopeças;125.0;0112500;90321090;Instrumentos e aparelhos para regulação;2017-07-01;
01;Autopeças;126.0;0112600;90322000;Pressostatos;2017-07-01;
01;Autopeças;127.0;0112700;871690;Peças para reboques e semirreboques, exceto os itens classificados no CEST 01.077.00;2017-07-01;
01;Autopeças;128.0;0112800;73229010;Geradores de ar quente a combustível líquido, com capacidade superior ou igual a 1.500 kcal/h, mas inferior ou igual a 10.400 kcal/h, do tipo dos utilizados em veículos automóveis;2017-07-01;
01;Autopeças;999.0;0199900;NT;Outras peças, partes e acessórios para veículos automotores não relacionados nos demais itens deste anexo;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;1.0;0200100;2205;Aperitivos, amargos, bitter e similares;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;1.0;0200100;22089000;Aperitivos, amargos, bitter e similares;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;2.0;0200200;22089000;Batida e similares;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;3.0;0200300;22089000;Bebida ice;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;4.0;0200400;22084000;Cachaça e aguardentes;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;4.0;0200400;220720;Cachaça e aguardentes;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;5.0;0200500;22060090;Catuaba e similares;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;5.0;0200500;22089000;Catuaba e similares;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;5.0;0200500;2205;Catuaba e similares;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;6.0;0200600;22082000;Conhaque, brandy e similares;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;7.0;0200700;22060090;Cooler;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;7.0;0200700;22089000;Cooler;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;8.0;0200800;22085000;Gim (gin) e genebra;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;9.0;0200900;2205;Jurubeba e similares;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;9.0;0200900;22060090;Jurubeba e similares;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;9.0;0200900;22089000;Jurubeba e similares;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;10.0;0201000;22087000;Licores e similares;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;11.0;0201100;22082000;Pisco;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;12.0;0201200;22084000;Rum;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;13.0;0201300;22060090;Saquê;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;14.0;0201400;22089000;Steinhaeger;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;15.0;0201500;22089000;Tequila;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;16.0;0201600;220830;Uísque;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;17.0;0201700;2205;Vermute e similares;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;18.0;0201800;22086000;Vodka;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;19.0;0201900;22089000;Derivados de vodka;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;20.0;0202000;22089000;Arak;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;21.0;0202100;22082000;Aguardente vínica / grappa;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;22.0;0202200;22060010;Sidra e similares;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;23.0;0202300;22060090;Sangrias e coquetéis;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;23.0;0202300;22089000;Sangrias e coquetéis;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;23.0;0202300;2205;Sangrias e coquetéis;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;24.0;0202400;2204;"Vinhos de uvas frescas, incluindo os vinhos enriquecidos com álcool; mostos de uvas.";2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;999.0;0299900;2206;Outras bebidas alcoólicas não especificadas nos itens anteriores;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;999.0;0299900;2208;Outras bebidas alcoólicas não especificadas nos itens anteriores;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;999.0;0299900;2205;Outras bebidas alcoólicas não especificadas nos itens anteriores;2017-07-01;
02;Bebidas alcoólicas, exceto cerveja e chope;999.0;0299900;2207;Outras bebidas alcoólicas não especificadas nos itens anteriores;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;1.0;0300100;22011000;Água mineral, gasosa ou não, ou potável, naturais, em garrafa de vidro, retornável ou não, com capacidade de até 500 ml;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;2.0;0300200;22011000;"Água mineral, gasosa ou não, ou potável, naturais, em embalagem com capacidade igual ou superior a 5.000 ml; exceto as classificadas no CEST 03.024.00 e 03.025.00";2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;3.0;0300300;22011000;Água mineral, gasosa ou não, ou potável, naturais, em embalagem de vidro, não retornável, com capacidade de até 300 ml;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;4.0;0300400;22011000;Água mineral, gasosa ou não, ou potável, naturais, em garrafa plástica de 1.500 ml;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;5.0;0300500;22011000;Água mineral, gasosa ou não, ou potável, naturais, em copos plásticos e embalagem plástica com capacidade de até 500 ml;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;6.0;0300600;22011000;"Outras águas minerais, potáveis ou naturais, gasosas ou não, inclusive gaseificadas; exceto as classificadas no CEST 03.024.00 e 03.025.00";2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;7.0;0300700;22021000;Águas minerais, potáveis ou naturais, gasosas ou não, inclusive gaseificadas ou aromatizadas artificialmente, exceto os refrescos e refrigerantes;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;8.0;0300800;22029900;Outras águas minerais, potáveis ou naturais, gasosas ou não, inclusive gaseificadas ou aromatizadas artificialmente;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;10.0;0301000;2202;Refrigerantes em garrafa com capacidade igual ou superior a 600 ml, exceto os classificados no CEST 03.011.01;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;11.0;0301100;2202;Demais refrigerantes, exceto os classificados no CEST 03.010.00 e 03.011.01;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;11.1;0301101;2202;Espumantes sem álcool;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;12.0;0301200;21069010;Xarope ou extrato concentrado destinados ao preparo de refrigerante em máquina pré-mix ou post-mix;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;13.0;0301300;22029900;Bebidas energéticas em embalagem com capacidade inferior a 600ml;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;13.0;0301300;210690;Bebidas energéticas em embalagem com capacidade inferior a 600ml;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;14.0;0301400;210690;Bebidas energéticas em embalagem com capacidade igual ou superior a 600ml;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;14.0;0301400;22029900;Bebidas energéticas em embalagem com capacidade igual ou superior a 600ml;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;15.0;0301500;22029900;Bebidas hidroeletrolíticas (isotônicas) em embalagem com capacidade inferior a 600ml;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;15.0;0301500;210690;Bebidas hidroeletrolíticas (isotônicas) em embalagem com capacidade inferior a 600ml;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;16.0;0301600;210690;Bebidas hidroeletrolíticas (isotônicas) em embalagem com capacidade inferior a 600ml;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;16.0;0301600;22029900;Bebidas hidroeletrolíticas (isotônicas) em embalagem com capacidade igual ou superior a 600ml;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;21.0;0302100;22030000;Cerveja;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;22.0;0302200;22029100;Cerveja sem álcool;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;23.0;0302300;22030000;Chope;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;24.0;0302400;22011000;Água mineral em embalagens retornáveis com capacidade igual ou superior a 10 (dez) e inferior a 20 (vinte) litros;2017-07-01;
03;Cervejas, chopes, refrigerantes, águas e outras bebidas;25.0;0302500;22011000;Água mineral em embalagens retornáveis com capacidade igual ou superior a 20 (vinte) litros;2017-07-01;
04;Cigarros e outros produtos derivados do fumo;1.0;0400100;2402;Charutos, cigarrilhas e cigarros, de tabaco ou dos seus sucedâneos;2017-07-01;
04;Cigarros e outros produtos derivados do fumo;2.0;0400200;24031;Tabaco para fumar, mesmo contendo sucedâneos de tabaco em qualquer proporção;2017-07-01;
05;Cimentos;1.0;0500100;2523;Cimento;2017-07-01;
06;Combustíveis e lubrificantes;1.0;0600100;22071010;Álcool etílico não desnaturado, com um teor alcoólico em volume igual ou superior a 80% vol - Com um teor de água igual ou inferior a 1 % vol (álcool etílico anidro combustível);2017-07-01;
06;Combustíveis e lubrificantes;1.1;0600101;22071090;Álcool etílico não desnaturado, com um teor alcoólico em volume igual ou superior a 80% vol - Outros (álcool etílico hidratado combustível);2017-07-01;
06;Combustíveis e lubrificantes;2.0;0600200;27101259;Gasolina automotiva A, exceto Premium;2017-07-01;
06;Combustíveis e lubrificantes;2.1;0600201;27101259;Gasolina automotiva C, exceto Premium;2017-07-01;
06;Combustíveis e lubrificantes;2.2;0600202;27101259;Gasolina automotiva A Premium;2017-07-01;
06;Combustíveis e lubrificantes;2.3;0600203;27101259;Gasolina automotiva C Premium;2017-07-01;
06;Combustíveis e lubrificantes;3.0;0600300;27101251;Gasolina de aviação;2017-07-01;
06;Combustíveis e lubrificantes;4.0;0600400;27101919;Querosenes, exceto de aviação;2017-07-01;
06;Combustíveis e lubrificantes;5.0;0600500;27101911;Querosene de aviação;2017-07-01;
06;Combustíveis e lubrificantes;6.0;0600600;2710192;Óleo diesel A, exceto S10 e Marítimo;2017-07-01;
06;Combustíveis e lubrificantes;6.1;0600601;2710192;Óleo diesel B, exceto S10 (mistura obrigatória);2017-07-01;
06;Combustíveis e lubrificantes;6.2;0600602;2710192;Óleo diesel B, exceto S10 (misturas autorizativas);2017-07-01;
06;Combustíveis e lubrificantes;6.3;0600603;2710192;Óleo diesel B, exceto S10 (misturas experimentais);2017-07-01;
06;Combustíveis e lubrificantes;6.4;0600604;2710192;Óleo diesel A S10;2017-07-01;
06;Combustíveis e lubrificantes;6.5;0600605;2710192;Óleo diesel B S10 (mistura obrigatória);2017-07-01;
06;Combustíveis e lubrificantes;6.6;0600606;2710192;Óleo diesel B S10 (misturas autorizativas);2017-07-01;
06;Combustíveis e lubrificantes;6.7;0600607;2710192;Óleo diesel B S10 (misturas experimentais);2017-07-01;
06;Combustíveis e lubrificantes;6.8;0600608;2710192;Óleo Diesel Marítimo;2017-07-01;
06;Combustíveis e lubrificantes;6.9;0600609;2710192;Outros óleos combustíveis, exceto os classificados no CEST 06.006.10 e 06.006.11;2017-07-01;
06;Combustíveis e lubrificantes;6.10;0600610;2710192;Óleo combustível derivado de xisto;2017-07-01;
06;Combustíveis e lubrificantes;6.11;0600611;27101922;Óleo combustível pesado;2017-07-01;
06;Combustíveis e lubrificantes;7.0;0600700;2710193;Óleos lubrificantes;2017-07-01;
06;Combustíveis e lubrificantes;8.0;0600800;2710199;Outros óleos de petróleo ou de minerais betuminosos (exceto óleos brutos) e preparações não especificadas nem compreendidas noutras posições, que contenham, como constituintes básicos, 70% ou mais, em peso, de óleos de petróleo ou de minerais betuminosos, exceto os que contenham biodiesel, exceto os resíduos de óleos e exceto as graxas lubrificantes;2017-07-01;
06;Combustíveis e lubrificantes;8.1;0600801;2710199;Graxa lubrificante;2017-07-01;
06;Combustíveis e lubrificantes;9.0;0600900;27109;Resíduos de óleos;2017-07-01;
06;Combustíveis e lubrificantes;10.0;0601000;2711;Gás de petróleo e outros hidrocarbonetos gasosos, exceto GLP, GLGN, Gás Natural e Gás de xisto.;2017-07-01;
06;Combustíveis e lubrificantes;11.0;0601100;27111910;Gás liquefeito de petróleo em botijão de 13 Kg (GLP);2017-07-01;
06;Combustíveis e lubrificantes;11.1;0601101;27111910;Gás liquefeito de petróleo (GLP), exceto em botijão de 13 Kg;2017-07-01;
06;Combustíveis e lubrificantes;11.2;0601102;27111910;Gás liquefeito de petróleo em botijão de 13 Kg (GLGNn);2017-07-01;
06;Combustíveis e lubrificantes;11.3;0601103;27111910;Gás liquefeito de petróleo (GLGNn), exceto em botijão de 13 Kg;2017-07-01;
06;Combustíveis e lubrificantes;11.4;0601104;27111910;Gás liquefeito de petróleo em botijão de 13 Kg (GLGNi);2017-07-01;
06;Combustíveis e lubrificantes;11.5;0601105;27111910;Gás liquefeito de petróleo (GLGNi), exceto em botijão de 13 Kg;2017-07-01;
06;Combustíveis e lubrificantes;11.6;0601106;27111910;Gás liquefeito de petróleo em botijão de 13 kg (Misturas);2017-07-01;
06;Combustíveis e lubrificantes;11.7;0601107;27111910;Gás liquefeito de petróleo (Misturas), exceto em botijão de 13 Kg;2017-07-01;
06;Combustíveis e lubrificantes;12.0;0601200;27111100;Gás Natural Liquefeito;2017-07-01;
06;Combustíveis e lubrificantes;13.0;0601300;27112100;Gás Natural Gasoso;2017-07-01;
06;Combustíveis e lubrificantes;14.0;0601400;27112990;Gás de xisto;2017-07-01;
06;Combustíveis e lubrificantes;15.0;0601500;2713;Coque de petróleo e outros resíduos de óleo de petróleo ou de minerais betuminosos;2017-07-01;
06;Combustíveis e lubrificantes;16.0;0601600;38260000;Biodiesel e suas misturas, que não contenham ou que contenham menos de 70%, em peso, de óleos de petróleo ou de óleos minerais betuminosos;2017-07-01;
06;Combustíveis e lubrificantes;17.0;0601700;3403;Preparações lubrificantes, exceto as contendo, como constituintes de base, 70% ou mais, em peso, de óleos de petróleo ou de minerais betuminosos;2017-07-01;
06;Combustíveis e lubrificantes;18.0;0601800;27102000;Óleos de petróleo ou de minerais betuminosos (exceto óleos brutos) e preparações não especificadas nem compreendidas noutras posições, que contenham, como constituintes básicos, 70% ou mais, em peso, de óleos de petróleo ou de minerais betuminosos, que contenham biodiesel, exceto os resíduos de óleos;2017-07-01;
07;Energia elétrica;1.0;0700100;27160000;Energia elétrica;2017-07-01;
08;Ferramentas;1.0;0800100;40169990;Ferramentas de borracha vulcanizada não endurecida;2017-07-01;
08;Ferramentas;2.0;0800200;44170010;Ferramentas, armações e cabos de ferramentas, de madeira;2017-07-01;
08;Ferramentas;2.0;0800200;44170090;Ferramentas, armações e cabos de ferramentas, de madeira;2017-07-01;
08;Ferramentas;3.0;0800300;6804;"Mós e artefatos semelhantes, sem armação, para moer, desfibrar, triturar, amolar, polir, retificar ou cortar; pedras para amolar ou para polir, manualmente, e suas partes, de pedras naturais, de abrasivos naturais ou artificiais aglomerados ou de cerâmica, mesmo com partes de outras matérias";2017-07-01;
08;Ferramentas;4.0;0800400;8201;"Pás, alviões, picaretas, enxadas, sachos, forcados e forquilhas, ancinhos e raspadeiras; machados, podões e ferramentas semelhantes com gume; tesouras de podar de todos os tipos; foices e foicinhas, facas para feno ou para palha, tesouras para sebes, cunhas e outras ferramentas manuais para agricultura, horticultura ou silvicultura";2017-07-01;
08;Ferramentas;5.0;0800500;82022000;Folhas de serras de fita;2017-07-01;
08;Ferramentas;6.0;0800600;82029100;Lâminas de serras máquinas;2017-07-01;
08;Ferramentas;7.0;0800700;8202;Serras manuais e outras folhas de serras (incluídas as fresas-serras e as folhas não dentadas para serrar), exceto as classificadas nos CEST 08.005.00 e 08.006.00;2017-07-01;
08;Ferramentas;8.0;0800800;8203;Limas, grosas, alicates (mesmo cortantes), tenazes, pinças, cisalhas para metais, corta-tubos, corta-pinos, saca-bocados e ferramentas semelhantes, manuais, exceto as pinças para sobrancelhas classificadas na posição 8203.20.90;2017-07-01;
08;Ferramentas;9.0;0800900;8204;"Chaves de porcas, manuais (incluídas as chaves dinamométricas); chaves de caixa intercambiáveis, mesmo com cabos";2017-07-01;
08;Ferramentas;10.0;0801000;8205;"Ferramentas manuais (incluídos os diamantes de vidraceiro) não especificadas nem compreendidas em outras posições, lamparinas ou lâmpadas de soldar (maçaricos) e semelhantes; tornos de apertar, sargentos e semelhantes, exceto os acessórios ou partes de máquinas-ferramentas; bigornas; forjas-portáteis; mós com armação, manuais ou de pedal";2017-07-01;
08;Ferramentas;11.0;0801100;82060000;Ferramentas de pelo menos duas das posições 8202 a 8205, acondicionadas em sortidos para venda a retalho;2017-07-01;
08;Ferramentas;12.0;0801200;820740;"Ferramentas de roscar interior ou exteriormente; de mandrilar ou de brochar; e de fresar";2017-07-01;
08;Ferramentas;12.0;0801200;820760;"Ferramentas de roscar interior ou exteriormente; de mandrilar ou de brochar; e de fresar";2017-07-01;
08;Ferramentas;12.0;0801200;820770;"Ferramentas de roscar interior ou exteriormente; de mandrilar ou de brochar; e de fresar";2017-07-01;
08;Ferramentas;13.0;0801300;8207;Outras ferramentas intercambiáveis para ferramentas manuais, mesmo mecânicas, ou para máquinas-ferramentas (por exemplo, de embutir, estampar, puncionar, furar, tornear, aparafusar), incluídas as fieiras de estiragem ou de extrusão, para metais, e as ferramentas de perfuração ou de sondagem, exceto forma ou gabarito de produtos em epoxy e as classificadas no CEST 08.012.00;2017-07-01;
08;Ferramentas;14.0;0801400;8208;Facas e lâminas cortantes, para máquinas ou para aparelhos mecânicos;2017-07-01;
08;Ferramentas;15.0;0801500;82090011;Plaquetas ou pastilhas intercambiáveis;2017-07-01;
08;Ferramentas;16.0;0801600;820900;Outras plaquetas, varetas, pontas e objetos semelhantes para ferramentas, não montados, de ceramais (cermets), exceto as classificadas no CEST 08.015.00;2017-07-01;
08;Ferramentas;17.0;0801700;8211;Facas de lâmina cortante ou serrilhada, incluídas as podadeiras de lâmina móvel, e suas lâminas, exceto as de uso doméstico;2017-07-01;
08;Ferramentas;18.0;0801800;8213;Tesouras e suas lâminas;2017-07-01;
08;Ferramentas;19.0;0801900;8467;Ferramentas pneumáticas, hidráulicas ou com motor (elétrico ou não elétrico) incorporado, de uso manual, exceto o descrito no CEST 08.019.01;2017-07-01;
08;Ferramentas;19.1;0801901;84678100;Moto-serras portáteis de corrente, com motor incorporado, não elétrico, de uso agrícola;2017-07-01;
08;Ferramentas;20.0;0802000;9015;"nstrumentos e aparelhos de geodesia, topografia, agrimensura, nivelamento, fotogrametria, hidrografia, oceanografia, hidrologia, meteorologia ou de geofísica, exceto bussolas; telêmetros";2017-07-01;
08;Ferramentas;21.0;0802100;90172000;"Instrumentos de desenho, de traçado ou de cálculo; metros, micrômetros, paquímetros, calibres e semelhantes; partes e acessórios";2017-07-01;
08;Ferramentas;21.0;0802100;901730;"Instrumentos de desenho, de traçado ou de cálculo; metros, micrômetros, paquímetros, calibres e semelhantes; partes e acessórios";2017-07-01;
08;Ferramentas;21.0;0802100;901780;"Instrumentos de desenho, de traçado ou de cálculo; metros, micrômetros, paquímetros, calibres e semelhantes; partes e acessórios";2017-07-01;
08;Ferramentas;21.0;0802100;90179090;"Instrumentos de desenho, de traçado ou de cálculo; metros, micrômetros, paquímetros, calibres e semelhantes; partes e acessórios";2017-07-01;
08;Ferramentas;22.0;0802200;90251190;Termômetros, suas partes e acessórios;2017-07-01;
08;Ferramentas;22.0;0802200;90259010;Termômetros, suas partes e acessórios;2017-07-01;
08;Ferramentas;23.0;0802300;902519;Pirômetros, suas partes e acessórios;2017-07-01;
08;Ferramentas;23.0;0802300;90259090;Pirômetros, suas partes e acessórios;2017-07-01;
09;Lâmpadas, reatores e “starter”;1.0;0900100;8539;Lâmpadas elétricas;2017-07-01;
09;Lâmpadas, reatores e “starter”;2.0;0900200;8540;Lâmpadas eletrônicas;2017-07-01;
09;Lâmpadas, reatores e “starter”;3.0;0900300;85041000;Reatores para lâmpadas ou tubos de descargas;2017-07-01;
09;Lâmpadas, reatores e “starter”;4.0;0900400;853650;Starter;2017-07-01;
09;Lâmpadas, reatores e “starter”;5.0;0900500;85395000;Lâmpadas de LED (Diodos Emissores de Luz);2017-07-01;
10;Materiais de construção e congêneres;1.0;1000100;2522;Cal;2017-07-01;
10;Materiais de construção e congêneres;2.0;1000200;38245000;Argamassas;2017-07-01;
10;Materiais de construção e congêneres;2.0;1000200;3816001;Argamassas;2017-07-01;
10;Materiais de construção e congêneres;3.0;1000300;32149000;Outras argamassas;2017-07-01;
10;Materiais de construção e congêneres;4.0;1000400;391000;Silicones em formas primárias, para uso na construção;2017-07-01;
10;Materiais de construção e congêneres;5.0;1000500;3916;"Revestimentos de PVC e outros plásticos; forro, sancas e afins de PVC, para uso na construção";2017-07-01;
10;Materiais de construção e congêneres;6.0;1000600;3917;Tubos, e seus acessórios (por exemplo, juntas, cotovelos, flanges, uniões), de plásticos, para uso na construção;2017-07-01;
10;Materiais de construção e congêneres;7.0;1000700;3918;Revestimento de pavimento de PVC e outros plásticos;2017-07-01;
10;Materiais de construção e congêneres;8.0;1000800;3919;Chapas, folhas, tiras, fitas, películas e outras formas planas, autoadesivas, de plásticos, mesmo em rolos, para uso na construção;2017-07-01;
10;Materiais de construção e congêneres;9.0;1000900;3921;Veda rosca, lona plástica para uso na construção, fitas isolantes e afins;2017-07-01;
10;Materiais de construção e congêneres;9.0;1000900;3919;Veda rosca, lona plástica para uso na construção, fitas isolantes e afins;2017-07-01;
10;Materiais de construção e congêneres;9.0;1000900;3920;Veda rosca, lona plástica para uso na construção, fitas isolantes e afins;2017-07-01;
10;Materiais de construção e congêneres;10.0;1001000;3921;Telha de plástico, mesmo reforçada com fibra de vidro;2017-07-01;
10;Materiais de construção e congêneres;11.0;1001100;3921;Cumeeira de plástico, mesmo reforçada com fibra de vidro;2017-07-01;
10;Materiais de construção e congêneres;12.0;1001200;3921;Chapas, laminados plásticos em bobina, para uso na construção, exceto os descritos no CEST 10.010.00 e 10.011.00;2017-07-01;
10;Materiais de construção e congêneres;13.0;1001300;3922;Banheiras, boxes para chuveiros, pias, lavatórios, bidês, sanitários e seus assentos e tampas, caixas de descarga e artigos semelhantes para usos sanitários ou higiênicos, de plásticos;2017-07-01;
10;Materiais de construção e congêneres;14.0;1001400;3924;Artefatos de higiene/toucador de plástico, para uso na construção;2017-07-01;
10;Materiais de construção e congêneres;15.0;1001500;39251000;Caixa dágua, inclusive sua tampa, de plástico, mesmo reforçadas com fibra de vidro;2017-07-01;
10;Materiais de construção e congêneres;16.0;1001600;392590;Outras telhas, cumeeira e caixa dágua, inclusive sua tampa, de plástico, mesmo reforçadas com fibra de vidro;2017-07-01;
10;Materiais de construção e congêneres;17.0;1001700;392590;Artefatos para apetrechamento de construções, de plásticos, não especificados nem compreendidos em outras posições, incluindo persianas, sancas, molduras, apliques e rosetas, caixilhos de polietileno e outros plásticos, exceto os descritos nos CEST 10.015.00 e 10.016.00;2017-07-01;
10;Materiais de construção e congêneres;17.0;1001700;39251000;Artefatos para apetrechamento de construções, de plásticos, não especificados nem compreendidos em outras posições, incluindo persianas, sancas, molduras, apliques e rosetas, caixilhos de polietileno e outros plásticos, exceto os descritos nos CEST 10.015.00 e 10.016.00;2017-07-01;
10;Materiais de construção e congêneres;18.0;1001800;39252000;Portas, janelas e seus caixilhos, alizares e soleiras;2017-07-01;
10;Materiais de construção e congêneres;19.0;1001900;39253000;Postigos, estores (incluídas as venezianas) e artefatos semelhantes e suas partes;2017-07-01;
10;Materiais de construção e congêneres;20.0;1002000;392690;Outras obras de plástico, para uso na construção;2017-07-01;
10;Materiais de construção e congêneres;21.0;1002100;4814;"Papel de parede e revestimentos de parede semelhantes; papel para vitrais";2017-07-01;
10;Materiais de construção e congêneres;22.0;1002200;68101900;Telhas de concreto;2017-07-01;
10;Materiais de construção e congêneres;23.0;1002300;6811;Telha, cumeeira e caixa dágua, inclusive sua tampa, de fibrocimento, cimento-celulose;2017-07-01;
10;Materiais de construção e congêneres;24.0;1002400;6811;Caixas dágua, tanques e reservatórios e suas tampas, telhas, calhas, cumeeiras e afins, de fibrocimento, cimento-celulose ou semelhantes, contendo ou não amianto, exceto os descritos no CEST 10.023.00;2017-07-01;
10;Materiais de construção e congêneres;25.0;1002500;69010000;Tijolos, placas (lajes), ladrilhos e outras peças cerâmicas de farinhas siliciosas fósseis (kieselghur, tripolita, diatomita, por exemplo) ou de terras siliciosas semelhantes;2017-07-01;
10;Materiais de construção e congêneres;26.0;1002600;6902;Tijolos, placas (lajes), ladrilhos e peças cerâmicas semelhantes, para uso na construção, refratários, que não sejam de farinhas siliciosas fósseis nem de terras siliciosas semelhantes;2017-07-01;
10;Materiais de construção e congêneres;27.0;1002700;6904;Tijolos para construção, tijoleiras, tapa-vigas e produtos semelhantes, de cerâmica;2017-07-01;
10;Materiais de construção e congêneres;28.0;1002800;6905;Telhas, elementos de chaminés, condutores de fumaça, ornamentos arquitetônicos, de cerâmica, e outros produtos cerâmicos para uso na construção;2017-07-01;
10;Materiais de construção e congêneres;29.0;1002900;69060000;Tubos, calhas ou algerozes e acessórios para canalizações, de cerâmica;2017-07-01;
10;Materiais de construção e congêneres;30.0;1003000;6907;Ladrilhos e placas de cerâmica, exclusivamente para pavimentação ou revestimento;2017-07-01;
10;Materiais de construção e congêneres;30.1;1003001;6907;Cubos, pastilhas e artigos semelhantes de cerâmica, mesmo com suporte, exceto os descritos CEST 10.030.00;2017-07-01;
10;Materiais de construção e congêneres;31.0;1003100;6910;Pias, lavatórios, colunas para lavatórios, banheiras, bidês, sanitários, caixas de descarga, mictórios e aparelhos fixos semelhantes para usos sanitários, de cerâmica;2017-07-01;
10;Materiais de construção e congêneres;32.0;1003200;69120000;Artefatos de higiene/toucador de cerâmica;2017-07-01;
10;Materiais de construção e congêneres;33.0;1003300;7003;Vidro vazado ou laminado, em chapas, folhas ou perfis, mesmo com camada absorvente, refletora ou não, mas sem qualquer outro trabalho;2017-07-01;
10;Materiais de construção e congêneres;34.0;1003400;7004;Vidro estirado ou soprado, em folhas, mesmo com camada absorvente, refletora ou não, mas sem qualquer outro trabalho;2017-07-01;
10;Materiais de construção e congêneres;35.0;1003500;7005;Vidro flotado e vidro desbastado ou polido em uma ou em ambas as faces, em chapas ou em folhas, mesmo com camada absorvente, refletora ou não, mas sem qualquer outro trabalho;2017-07-01;
10;Materiais de construção e congêneres;36.0;1003600;70071900;Vidros temperados;2017-07-01;
10;Materiais de construção e congêneres;37.0;1003700;70072900;Vidros laminados;2017-07-01;
10;Materiais de construção e congêneres;38.0;1003800;7008;Vidros isolantes de paredes múltiplas;2017-07-01;
10;Materiais de construção e congêneres;39.0;1003900;7016;"Blocos, placas, tijolos, ladrilhos, telhas e outros artefatos, de vidro prensado ou moldado, mesmo armado, para uso na construção; cubos, pastilhas e outros artigos semelhantes";2017-07-01;
10;Materiais de construção e congêneres;40.0;1004000;72142000;Barras próprias para construções, exceto vergalhões;2017-07-01;
10;Materiais de construção e congêneres;41.0;1004100;73089010;Outras barras próprias para construções, exceto vergalhões;2017-07-01;
10;Materiais de construção e congêneres;42.0;1004200;72142000;Vergalhões;2017-07-01;
10;Materiais de construção e congêneres;43.0;1004300;7213;Outros vergalhões;2017-07-01;
10;Materiais de construção e congêneres;43.0;1004300;73089010;Outros vergalhões;2017-07-01;
10;Materiais de construção e congêneres;44.0;1004400;72171090;"Fios de ferro ou aço não ligados, não revestidos, mesmo polidos; cordas, cabos, tranças (entrançados), lingas e artefatos semelhantes, de ferro ou aço, não isolados para usos elétricos";2017-07-01;
10;Materiais de construção e congêneres;44.0;1004400;7312;"Fios de ferro ou aço não ligados, não revestidos, mesmo polidos; cordas, cabos, tranças (entrançados), lingas e artefatos semelhantes, de ferro ou aço, não isolados para usos elétricos";2017-07-01;
10;Materiais de construção e congêneres;45.0;1004500;72172010;Outros fios de ferro ou aço, não ligados, galvanizados com teor de carbono superior ou igual a 0,6%, em peso;2017-07-01;
10;Materiais de construção e congêneres;45.1;1004501;72172090;Outros fios de ferro ou aço, não ligados, galvanizados;2017-07-01;
10;Materiais de construção e congêneres;46.0;1004600;7307;Acessórios para tubos (inclusive uniões, cotovelos, luvas ou mangas), de ferro fundido, ferro ou aço;2017-07-01;
10;Materiais de construção e congêneres;47.0;1004700;73083000;Portas e janelas, e seus caixilhos, alizares e soleiras de ferro fundido, ferro ou aço;2017-07-01;
10;Materiais de construção e congêneres;48.0;1004800;73084000;Material para andaimes, para armações (cofragens) e para escoramentos, (inclusive armações prontas, para estruturas de concreto armado ou argamassa armada), eletrocalhas e perfilados de ferro fundido, ferro ou aço, próprios para construção, exceto treliças de aço;2017-07-01;
10;Materiais de construção e congêneres;48.0;1004800;730890;Material para andaimes, para armações (cofragens) e para escoramentos, (inclusive armações prontas, para estruturas de concreto armado ou argamassa armada), eletrocalhas e perfilados de ferro fundido, ferro ou aço, próprios para construção, exceto treliças de aço;2017-07-01;
10;Materiais de construção e congêneres;49.0;1004900;73084000;Treliças de aço;2017-07-01;
10;Materiais de construção e congêneres;50.0;1005000;73089090;Telhas metálicas;2017-07-01;
10;Materiais de construção e congêneres;51.0;1005100;7310;"Caixas diversas (tais como caixa de correio, de entrada de água, de energia, de instalação) de ferro fundido, ferro ou aço; próprias para a construção";2017-07-01;
10;Materiais de construção e congêneres;52.0;1005200;73130000;Arame farpado, de ferro ou aço, arames ou tiras, retorcidos, mesmo farpados, de ferro ou aço, dos tipos utilizados em cercas;2017-07-01;
10;Materiais de construção e congêneres;53.0;1005300;7314;Telas metálicas, grades e redes, de fios de ferro ou aço;2017-07-01;
10;Materiais de construção e congêneres;54.0;1005400;73151100;Correntes de rolos, de ferro fundido, ferro ou aço;2017-07-01;
10;Materiais de construção e congêneres;55.0;1005500;73151290;Outras correntes de elos articulados, de ferro fundido, ferro ou aço;2017-07-01;
10;Materiais de construção e congêneres;56.0;1005600;73158200;Correntes de elos soldados, de ferro fundido, de ferro ou aço;2017-07-01;
10;Materiais de construção e congêneres;57.0;1005700;731700;Tachas, pregos, percevejos, escápulas, grampos ondulados ou biselados e artefatos semelhantes, de ferro fundido, ferro ou aço, mesmo com a cabeça de outra matéria, exceto cobre;2017-07-01;
10;Materiais de construção e congêneres;58.0;1005800;7318;Parafusos, pinos ou pernos, roscados, porcas, tira-fundos, ganchos roscados, rebites, chavetas, cavilhas, contrapinos, arruelas (incluídas as de pressão) e artefatos semelhantes, de ferro fundido, ferro ou aço;2017-07-01;
10;Materiais de construção e congêneres;59.0;1005900;7323;Palha de ferro ou aço, exceto os de uso doméstico classificados na posição NCM 7323.10.00;2017-07-01;
10;Materiais de construção e congêneres;59.1;1005901;7323;Esponjas, esfregões, luvas e artefatos semelhantes para limpeza, polimento e usos semelhantes, de ferro ou aço, exceto os de uso doméstico classificados na posição NCM 7323.10.00;2017-07-01;
10;Materiais de construção e congêneres;60.0;1006000;7324;Artefatos de higiene ou de toucador, e suas partes, de ferro fundido, ferro ou aço, incluídas as pias, banheiras, lavatórios, cubas, mictórios, tanques e afins de ferro fundido, ferro ou aço, para uso na construção;2017-07-01;
10;Materiais de construção e congêneres;61.0;1006100;7325;Outras obras moldadas, de ferro fundido, ferro ou aço, para uso na construção;2017-07-01;
10;Materiais de construção e congêneres;62.0;1006200;7326;Abraçadeiras;2017-07-01;
10;Materiais de construção e congêneres;63.0;1006300;7407;Barras de cobre;2017-07-01;
10;Materiais de construção e congêneres;64.0;1006400;74111010;Tubos de cobre e suas ligas, para instalações de água quente e gás, para uso na construção;2017-07-01;
10;Materiais de construção e congêneres;65.0;1006500;7412;Acessórios para tubos (por exemplo, uniões, cotovelos, luvas ou mangas) de cobre e suas ligas, para uso na construção;2017-07-01;
10;Materiais de construção e congêneres;66.0;1006600;7415;Tachas, pregos, percevejos, escápulas e artefatos semelhantes, de cobre, ou de ferro ou aço com cabeça de cobre, parafusos, pinos ou pernos, roscados, porcas, ganchos roscados, rebites, chavetas, cavilhas, contrapinos, arruelas (incluídas as de pressão), e artefatos semelhantes, de cobre;2017-07-01;
10;Materiais de construção e congêneres;67.0;1006700;74182000;Artefatos de higiene/toucador de cobre, para uso na construção;2017-07-01;
10;Materiais de construção e congêneres;68.0;1006800;76071990;Manta de subcobertura aluminizada;2017-07-01;
10;Materiais de construção e congêneres;69.0;1006900;7608;Tubos de alumínio e suas ligas, para refrigeração e ar condicionado, para uso na construção;2017-07-01;
10;Materiais de construção e congêneres;70.0;1007000;76090000;Acessórios para tubos (por exemplo, uniões, cotovelos, luvas ou mangas), de alumínio, para uso na construção;2017-07-01;
10;Materiais de construção e congêneres;71.0;1007100;7610;"Construções e suas partes (por exemplo, pontes e elementos de pontes, torres, pórticos ou pilones, pilares, colunas, armações, estruturas para telhados, portas e janelas, e seus caixilhos, alizares e soleiras, balaustradas), de alumínio, exceto as construções pré-fabricadas da posição 9406; chapas, barras, perfis, tubos e semelhantes, de alumínio, próprios para construções";2017-07-01;
10;Materiais de construção e congêneres;72.0;1007200;76152000;Artefatos de higiene/toucador de alumínio, para uso na construção;2017-07-01;
10;Materiais de construção e congêneres;73.0;1007300;7616;Outras obras de alumínio, próprias para construções, incluídas as persianas;2017-07-01;
10;Materiais de construção e congêneres;74.0;1007400;83024100;Outras guarnições, ferragens e artigos semelhantes de metais comuns, para construções, inclusive puxadores.;2017-07-01;
10;Materiais de construção e congêneres;75.0;1007500;8301;"Fechaduras e ferrolhos (de chave, de segredo ou elétricos), de metais comuns, incluídas as suas partes fechos e armações com fecho, com fechadura, de metais comuns chaves para estes artigos, de metais comuns; exceto os de uso automotivo";2017-07-01;
10;Materiais de construção e congêneres;76.0;1007600;83021000;Dobradiças de metais comuns, de qualquer tipo;2017-07-01;
10;Materiais de construção e congêneres;77.0;1007700;8307;Tubos flexíveis de metais comuns, mesmo com acessórios, para uso na construção;2017-07-01;
10;Materiais de construção e congêneres;78.0;1007800;8311;Fios, varetas, tubos, chapas, eletrodos e artefatos semelhantes, de metais comuns ou de carbonetos metálicos, revestidos exterior ou interiormente de decapantes ou de fundentes, para soldagem (soldadura) ou depósito de metal ou de carbonetos metálicos fios e varetas de pós de metais comuns aglomerados, para metalização por projeção;2017-07-01;
10;Materiais de construção e congêneres;79.0;1007900;8481;Torneiras, válvulas (incluídas as redutoras de pressão e as termostáticas) e dispositivos semelhantes, para canalizações, caldeiras, reservatórios, cubas e outros recipientes;2017-07-01;
10;Materiais de construção e congêneres;80.0;1008000;7009;Espelhos de vidro, mesmo emoldurados, exceto os de uso automotivo;2017-07-01;
11;Materiais de limpeza;1.0;1100100;28289011;Água sanitária, branqueador e outros alvejantes;2017-07-01;
11;Materiais de limpeza;1.0;1100100;28289019;Água sanitária, branqueador e outros alvejantes;2017-07-01;
11;Materiais de limpeza;1.0;1100100;32064100;Água sanitária, branqueador e outros alvejantes;2017-07-01;
11;Materiais de limpeza;1.0;1100100;34022000;Água sanitária, branqueador e outros alvejantes;2017-07-01;
11;Materiais de limpeza;1.0;1100100;38089419;Água sanitária, branqueador e outros alvejantes;2017-07-01;
11;Materiais de limpeza;2.0;1100200;34012090;Sabões em pó, flocos, palhetas, grânulos ou outras formas semelhantes, para lavar roupas;2017-07-01;
11;Materiais de limpeza;3.0;1100300;34012090;Sabões líquidos para lavar roupas;2017-07-01;
11;Materiais de limpeza;4.0;1100400;34022000;Detergentes em pó, flocos, palhetas, grânulos ou outras formas semelhantes;2017-07-01;
11;Materiais de limpeza;5.0;1100500;34022000;Detergentes líquidos, exceto para lavar roupa;2017-07-01;
11;Materiais de limpeza;6.0;1100600;34022000;Detergente líquido para lavar roupa;2017-07-01;
11;Materiais de limpeza;7.0;1100700;3402;"Outros agentes orgânicos de superfície (exceto sabões); preparações tensoativas, preparações para lavagem (incluídas as preparações auxiliares para lavagem) e preparações para limpeza (inclusive multiuso e limpadores), mesmo contendo sabão, exceto os produtos descritos nos CEST 11.001.00, 11.004.00, 11.005.00 e 11.006.00; em embalagem de conteúdo inferior ou igual a 50 litros ou 50 kg";2017-07-01;
11;Materiais de limpeza;8.0;1100800;38099190;Amaciante/suavizante;2017-07-01;
11;Materiais de limpeza;9.0;1100900;39249000;Esponjas para limpeza;2017-07-01;
11;Materiais de limpeza;9.0;1100900;68053010;Esponjas para limpeza;2017-07-01;
11;Materiais de limpeza;9.0;1100900;68053090;Esponjas para limpeza;2017-07-01;
11;Materiais de limpeza;9.0;1100900;39241000;Esponjas para limpeza;2017-07-01;
11;Materiais de limpeza;10.0;1101000;22089000;Álcool etílico para limpeza;2017-07-01;
11;Materiais de limpeza;10.0;1101000;2207;Álcool etílico para limpeza;2017-07-01;
11;Materiais de limpeza;11.0;1101100;73231000;"Esponjas e palhas de aço; esponjas para limpeza, polimento ou uso semelhantes; todas de uso doméstico";2017-07-01;
11;Materiais de limpeza;12.0;1101200;39232;Sacos de lixo de conteúdo igual ou inferior a 100 litros;2017-07-01;
12;Materiais elétricos;1.0;1200100;8504;"Transformadores, bobinas de reatância e de auto indução, inclusive os transformadores de potência superior a 16 KVA, classificados nas posições 8504.33.00 e 8504.34.00; exceto os demais transformadores da subposição 8504.3, os reatores para lâmpadas elétricas de descarga classificados no código 8504.10.00, os carregadores de acumuladores do código 8504.40.10, os equipamentos de alimentação ininterrupta de energia (UPS ou no break), no código 8504.40.40 e os de uso automotivo";2017-07-01;
12;Materiais elétricos;2.0;1200200;8516;"Aquecedores elétricos de água, incluídos os de imersão, chuveiros ou duchas elétricos, torneiras elétricas, resistências de aquecimento, inclusive as de duchas e chuveiros elétricos e suas partes; exceto outros fornos, fogareiros (incluídas as chapas de cocção), grelhas e assadeiras, classificados na posição 8516.60.00";2017-07-01;
12;Materiais elétricos;3.0;1200300;8535;Aparelhos para interrupção, seccionamento, proteção, derivação, ligação ou conexão de circuitos elétricos (por exemplo, interruptores, comutadores, corta-circuitos, para-raios, limitadores de tensão, eliminadores de onda, tomadas de corrente e outros conectores, caixas de junção), para tensão superior a 1.000V, exceto os de uso automotivo;2017-07-01;
12;Materiais elétricos;4.0;1200400;8536;"Aparelhos para interrupção, seccionamento, proteção, derivação, ligação ou conexão de circuitos elétricos (por exemplo, interruptores, comutadores, relés, corta-circuitos, eliminadores de onda, plugues e tomadas de corrente, suportes para lâmpadas e outros conectores, caixas de junção), para uma tensão não superior a 1.000V; conectores para fibras ópticas, feixes ou cabos de fibras ópticas; exceto starter classificado na subposição 8536.50 e os de uso automotivo";2017-07-01;
12;Materiais elétricos;5.0;1200500;8538;Partes reconhecíveis como exclusiva ou principalmente destinadas aos aparelhos das posições 8535 e 8536;2017-07-01;
12;Materiais elétricos;6.0;1200600;74130000;Cabos, tranças e semelhantes, de cobre, não isolados para usos elétricos, exceto os de uso automotivo;2017-07-01;
12;Materiais elétricos;7.0;1200700;7614;"Fios, cabos (incluídos os cabos coaxiais) e outros condutores, isolados ou não, para usos elétricos (incluídos os de cobre ou alumínio, envernizados ou oxidados anodicamente), mesmo com peças de conexão, inclusive fios e cabos elétricos, para tensão não superior a 1000V, para uso na construção; fios e cabos telefônicos e para transmissão de dados; cabos de fibras ópticas, constituídos de fibras embainhadas individualmente, mesmo com condutores elétricos ou munidos de peças de conexão; cordas, cabos, tranças e semelhantes, de alumínio, não isolados para uso elétricos; exceto os de uso automotivo";2017-07-01;
12;Materiais elétricos;7.0;1200700;8544;"Fios, cabos (incluídos os cabos coaxiais) e outros condutores, isolados ou não, para usos elétricos (incluídos os de cobre ou alumínio, envernizados ou oxidados anodicamente), mesmo com peças de conexão, inclusive fios e cabos elétricos, para tensão não superior a 1000V, para uso na construção; fios e cabos telefônicos e para transmissão de dados; cabos de fibras ópticas, constituídos de fibras embainhadas individualmente, mesmo com condutores elétricos ou munidos de peças de conexão; cordas, cabos, tranças e semelhantes, de alumínio, não isolados para uso elétricos; exceto os de uso automotivo";2017-07-01;
12;Materiais elétricos;7.0;1200700;7605;"Fios, cabos (incluídos os cabos coaxiais) e outros condutores, isolados ou não, para usos elétricos (incluídos os de cobre ou alumínio, envernizados ou oxidados anodicamente), mesmo com peças de conexão, inclusive fios e cabos elétricos, para tensão não superior a 1000V, para uso na construção; fios e cabos telefônicos e para transmissão de dados; cabos de fibras ópticas, constituídos de fibras embainhadas individualmente, mesmo com condutores elétricos ou munidos de peças de conexão; cordas, cabos, tranças e semelhantes, de alumínio, não isolados para uso elétricos; exceto os de uso automotivo";2017-07-01;
12;Materiais elétricos;8.0;1200800;8546;Isoladores de qualquer matéria, para usos elétricos;2017-07-01;
12;Materiais elétricos;9.0;1200900;8547;"Peças isolantes inteiramente de matérias isolantes, ou com simples peças metálicas de montagem (suportes roscados, por exemplo) incorporadas na massa, para máquinas, aparelhos e instalações elétricas; tubos isoladores e suas peças de ligação, de metais comuns, isolados interiormente";2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;1.0;1300100;3004;Medicamentos de referência - positiva, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;1.0;1300100;3003;Medicamentos de referência - positiva, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;1.1;1300101;3004;Medicamentos de referência - negativa, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;1.1;1300101;3003;Medicamentos de referência - negativa, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;1.2;1300102;3004;Medicamentos de referência - neutra, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;1.2;1300102;3003;Medicamentos de referência - neutra, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;2.0;1300200;3003;Medicamentos genérico - positiva, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;2.0;1300200;3004;Medicamentos genérico - positiva, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;2.1;1300201;3003;Medicamentos genérico - negativa, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;2.1;1300201;3004;Medicamentos genérico - negativa, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;2.2;1300202;3004;Medicamentos genérico - neutra, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;2.2;1300202;3003;Medicamentos genérico - neutra, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;3.0;1300300;3004;Medicamentos similar - positiva, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;3.0;1300300;3003;Medicamentos similar - positiva, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;3.1;1300301;3004;Medicamentos similar - negativa, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;3.1;1300301;3003;Medicamentos similar - negativa, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;3.2;1300302;3004;Medicamentos similar - neutra, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;3.2;1300302;3003;Medicamentos similar - neutra, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;4.0;1300400;3004;Outros tipos de medicamentos - positiva, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;4.0;1300400;3003;Outros tipos de medicamentos - positiva, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;4.1;1300401;3004;Outros tipos de medicamentos - negativa, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;4.1;1300401;3003;Outros tipos de medicamentos - negativa, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;4.2;1300402;3004;Outros tipos de medicamentos - neutra, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;4.2;1300402;3003;Outros tipos de medicamentos - neutra, exceto para uso veterinário;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;5.0;1300500;30066000;Preparações químicas contraceptivas à base de hormônios, de outros produtos da posição 29.37 ou de espermicidas - positiva;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;5.1;1300501;30066000;Preparações químicas contraceptivas à base de hormônios, de outros produtos da posição 29.37 ou de espermicidas - negativa;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;6.0;1300600;2936;Provitaminas e vitaminas, naturais ou reproduzidas por síntese (incluídos os concentrados naturais), bem como os seus derivados utilizados principalmente como vitaminas, misturados ou não entre si, mesmo em quaisquer soluções - neutra;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;7.0;1300700;300630;Preparações opacificantes (contrastantes) para exames radiográficos e reagentes de diagnóstico concebidos para serem administrados ao paciente - positiva;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;7.1;1300701;300630;Preparações opacificantes (contrastantes) para exames radiográficos e reagentes de diagnóstico concebidos para serem administrados ao paciente - negativa;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;8.0;1300800;3002;Antissoro, outras frações do sangue, produtos imunológicos modificados, mesmo obtidos por via biotecnológica, exceto para uso veterinário - positiva;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;8.1;1300801;3002;Antissoro, outras frações do sangue, produtos imunológicos modificados, mesmo obtidos por via biotecnológica, exceto para uso veterinário - negativa;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;9.0;1300900;3002;"Vacinas e produtos semelhantes, exceto para uso veterinário - positiva;";2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;9.1;1300901;3002;"Vacinas e produtos semelhantes, exceto para uso veterinário - negativa;";2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;10.0;1301000;30051010;Curativos (pensos) adesivos e outros artigos com uma camada adesiva, impregnados ou recobertos de substâncias farmacêuticas - Lista Positiva;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;10.1;1301001;30051010;Curativos (pensos) adesivos e outros artigos com uma camada adesiva, impregnados ou recobertos de substâncias farmacêuticas - Lista Negativa;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;11.0;1301100;3005;Algodão, atadura, esparadrapo, gazes, pensos, sinapismos, e outros, acondicionados para venda a retalho para usos medicinais, cirúrgicos ou dentários, não impregnados ou recobertos de substâncias farmacêuticas - Lista Neutra;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;12.0;1301200;40151900;Luvas cirúrgicas e luvas de procedimento - neutra;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;12.0;1301200;40151100;Luvas cirúrgicas e luvas de procedimento - neutra;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;13.0;1301300;40141000;Preservativo  neutra;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;14.0;1301400;901831;Seringas, mesmo com agulhas - neutra;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;15.0;1301500;9018321;Agulhas para seringas - neutra;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;16.0;1301600;39269090;Contraceptivos (dispositivos intrauterinos - DIU) - neutra;2017-07-01;
13;Medicamentos e outros produtos farmacêuticos para uso humano;16.0;1301600;90189099;Contraceptivos (dispositivos intrauterinos - DIU) - neutra;2017-07-01;
14;Papéis;1.0;1400100;7013;Objetos de vidro para serviço de mesa ou de cozinha;2017-07-01;
14;Papéis;2.0;1400200;70133700;Outros copos, exceto de vitrocerâmica;2017-07-01;
14;Papéis;3.0;1400300;70134290;Objetos para serviço de mesa (exceto copos) ou de cozinha, exceto de vitrocerâmica;2017-07-01;
14;Papéis;4.0;1400400;3921;Lonas plásticas, exceto as para uso na construção;2017-07-01;
14;Papéis;4.0;1400400;3919;Lonas plásticas, exceto as para uso na construção;2017-07-01;
14;Papéis;4.0;1400400;3920;Lonas plásticas, exceto as para uso na construção;2017-07-01;
14;Papéis;5.0;1400500;3924;Artefatos de higiene/toucador de plástico, exceto os para uso na construção;2017-07-01;
14;Papéis;6.0;1400600;39241000;Serviços de mesa e outros utensílios de mesa ou de cozinha, de plástico, não descartáveis;2017-07-01;
14;Papéis;6.1;1400601;39241000;Serviços de mesa e outros utensílios de mesa ou de cozinha, de plástico, descartáveis;2017-07-01;
14;Papéis;7.0;1400700;69111010;Artigos para serviço de mesa ou de cozinha, de porcelana, inclusive os descartáveis  estojos;2017-07-01;
14;Papéis;8.0;1400800;69111090;Artigos para serviço de mesa ou de cozinha, de porcelana, inclusive os descartáveis  avulsos;2017-07-01;
14;Papéis;9.0;1400900;69120000;Artigos para serviço de mesa ou de cozinha, de cerâmica;2017-07-01;
14;Papéis;10.0;1401000;69120000;Velas para filtros;2017-07-01;
14;Papéis;11.0;1401100;4823209;Filtros descartáveis para coar café ou chá;2017-07-01;
14;Papéis;12.0;1401200;48236;Bandejas, travessas, pratos, xícaras ou chávenas, taças, copos e artigos semelhantes, de papel ou cartão;2017-07-01;
14;Papéis;13.0;1401300;48131000;Papel para cigarro;2017-07-01;
16;Pneumáticos, câmaras de ar e protetores de borracha;1.0;1600100;40111000;Pneus novos, dos tipos utilizados em automóveis de passageiros (incluídos os veículos de uso misto - camionetas e os automóveis de corrida);2017-07-01;
16;Pneumáticos, câmaras de ar e protetores de borracha;2.0;1600200;4011;Pneus novos, dos tipos utilizados em caminhões (inclusive para os fora-de-estrada), ônibus, aviões, máquinas de terraplenagem, de construção e conservação de estradas, máquinas e tratores agrícolas, pá-carregadeira;2017-07-01;
16;Pneumáticos, câmaras de ar e protetores de borracha;3.0;1600300;40114000;Pneus novos para motocicletas;2017-07-01;
16;Pneumáticos, câmaras de ar e protetores de borracha;4.0;1600400;4011;Outros tipos de pneus novos, exceto os itens classificados no CEST 16.005.00;2017-07-01;
16;Pneumáticos, câmaras de ar e protetores de borracha;5.0;1600500;40115000;Pneus novos de borracha dos tipos utilizados em bicicletas;2017-07-01;
16;Pneumáticos, câmaras de ar e protetores de borracha;6.0;1600600;40121;Pneus recauchutados;2017-07-01;
16;Pneumáticos, câmaras de ar e protetores de borracha;7.0;1600700;401290;Protetores de borracha, exceto os itens classificados no CEST 16.007.01;2017-07-01;
16;Pneumáticos, câmaras de ar e protetores de borracha;7.1;1600701;401290;Protetores de borracha para bicicletas;2017-07-01;
16;Pneumáticos, câmaras de ar e protetores de borracha;8.0;1600800;4013;Câmaras de ar de borracha, exceto os itens classificados no CEST 16.009.00;2017-07-01;
16;Pneumáticos, câmaras de ar e protetores de borracha;9.0;1600900;40132000;Câmaras de ar de borracha dos tipos utilizados em bicicletas;2017-07-01;
17;Produtos alimentícios;1.0;1700100;17049010;Chocolate branco, em embalagens de conteúdo inferior ou igual a 1 kg, excluídos os ovos de páscoa de chocolate.;2017-07-01;
17;Produtos alimentícios;2.0;1700200;18063110;Chocolates contendo cacau, em embalagens de conteúdo inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;2.0;1700200;18063220;Chocolates contendo cacau, em embalagens de conteúdo inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;3.0;1700300;18063220;Chocolate em barras, tabletes ou blocos ou no estado líquido, em pasta, em pó, grânulos ou formas semelhantes, em recipientes ou embalagens imediatas de conteúdo inferior ou igual a 2 kg;2017-07-01;
17;Produtos alimentícios;3.0;1700300;18063210;Chocolate em barras, tabletes ou blocos ou no estado líquido, em pasta, em pó, grânulos ou formas semelhantes, em recipientes ou embalagens imediatas de conteúdo inferior ou igual a 2 kg;2017-07-01;
17;Produtos alimentícios;4.0;1700400;18069000;Chocolates e outras preparações alimentícias contendo cacau, em embalagens de conteúdo inferior ou igual a 1 kg, excluídos os achocolatados em pó e ovos de páscoa de chocolate.;2017-07-01;
17;Produtos alimentícios;5.0;1700500;17049010;Ovos de páscoa de chocolate branco;2017-07-01;
17;Produtos alimentícios;5.1;1700501;18069000;Ovos de páscoa de chocolate;2017-07-01;
17;Produtos alimentícios;6.0;1700600;18069000;Achocolatados em pó, em embalagens de conteúdo inferior ou igual a 1 kg, exceto os classificados no CEST 17.006.02;2017-07-01;
17;Produtos alimentícios;6.1;1700601;18061000;Cacau em pó, com adição de açúcar ou de outros edulcorantes, em embalagens de conteúdo inferior ou igual a 1kg;2017-07-01;
17;Produtos alimentícios;6.2;1700602;18069000;Achocolatados em pó, em cápsulas;2017-07-01;
17;Produtos alimentícios;7.0;1700700;18069000;Caixas de bombons contendo cacau, em embalagens de conteúdo inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;8.0;1700800;17049090;Bombons, inclusive à base de chocolate branco sem cacau;2017-07-01;
17;Produtos alimentícios;9.0;1700900;18069000;Bombons, balas, caramelos, confeitos, pastilhas e outros produtos de confeitaria, contendo cacau;2017-07-01;
17;Produtos alimentícios;10.0;1701000;2009;"Sucos de frutas ou de produtos hortícolas; mistura de sucos";2017-07-01;
17;Produtos alimentícios;11.0;1701100;20098;Água de coco;2017-07-01;
17;Produtos alimentícios;12.0;1701200;04021;Leite em pó, blocos ou grânulos, exceto creme de leite;2017-07-01;
17;Produtos alimentícios;12.0;1701200;04022;Leite em pó, blocos ou grânulos, exceto creme de leite;2017-07-01;
17;Produtos alimentícios;12.0;1701200;04029;Leite em pó, blocos ou grânulos, exceto creme de leite;2017-07-01;
17;Produtos alimentícios;13.0;1701300;19011020;Farinha láctea;2017-07-01;
17;Produtos alimentícios;14.0;1701400;19011010;Leite modificado para alimentação de crianças;2017-07-01;
17;Produtos alimentícios;15.0;1701500;19011090;Preparações para alimentação infantil à base de farinhas, grumos, sêmolas ou amidos e outros;2017-07-01;
17;Produtos alimentícios;16.0;1701600;04011010;Leite longa vida (UHT - Ultra High Temperature), em recipiente de conteúdo inferior ou igual a 2 litros;2017-07-01;
17;Produtos alimentícios;16.0;1701600;04012010;Leite longa vida (UHT - Ultra High Temperature), em recipiente de conteúdo inferior ou igual a 2 litros;2017-07-01;
17;Produtos alimentícios;16.1;1701601;04012010;Leite longa vida (UHT - Ultra High Temperature), em recipiente de conteúdo superior a 2 litros e inferior ou igual a 5 litros;2017-07-01;
17;Produtos alimentícios;16.1;1701601;04011010;Leite longa vida (UHT - Ultra High Temperature), em recipiente de conteúdo superior a 2 litros e inferior ou igual a 5 litros;2017-07-01;
17;Produtos alimentícios;17.0;1701700;04015010;Leite em recipiente de conteúdo inferior ou igual a 1 litro;2017-07-01;
17;Produtos alimentícios;17.0;1701700;04014010;Leite em recipiente de conteúdo inferior ou igual a 1 litro;2017-07-01;
17;Produtos alimentícios;17.1;1701701;04014010;Leite em recipiente de conteúdo superior a 1 litro e inferior ou igual a 5 litros;2017-07-01;
17;Produtos alimentícios;17.1;1701701;04015010;Leite em recipiente de conteúdo superior a 1 litro e inferior ou igual a 5 litros;2017-07-01;
17;Produtos alimentícios;18.0;1701800;04012090;Leite do tipo pasteurizado em recipiente de conteúdo inferior ou igual a 1 litro;2017-07-01;
17;Produtos alimentícios;18.0;1701800;04011090;Leite do tipo pasteurizado em recipiente de conteúdo inferior ou igual a 1 litro;2017-07-01;
17;Produtos alimentícios;18.1;1701801;04011090;Leite do tipo pasteurizado em recipiente de conteúdo superior a 1 litro e inferior ou igual a 5 litros;2017-07-01;
17;Produtos alimentícios;18.1;1701801;04012090;Leite do tipo pasteurizado em recipiente de conteúdo superior a 1 litro e inferior ou igual a 5 litros;2017-07-01;
17;Produtos alimentícios;19.0;1701900;04022130;Creme de leite, em recipiente de conteúdo inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;19.0;1701900;04029;Creme de leite, em recipiente de conteúdo inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;19.0;1701900;0401402;Creme de leite, em recipiente de conteúdo inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;19.0;1701900;04022930;Creme de leite, em recipiente de conteúdo inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;19.1;1701901;04022130;Creme de leite, em recipiente de conteúdo superior a 1 kg;2017-07-01;
17;Produtos alimentícios;19.1;1701901;04029;Creme de leite, em recipiente de conteúdo superior a 1 kg;2017-07-01;
17;Produtos alimentícios;19.1;1701901;0401402;Creme de leite, em recipiente de conteúdo superior a 1 kg;2017-07-01;
17;Produtos alimentícios;19.1;1701901;04022930;Creme de leite, em recipiente de conteúdo superior a 1 kg;2017-07-01;
17;Produtos alimentícios;19.2;1701902;040150;Outros cremes de leite, em recipiente de conteúdo inferior ou igual a 1kg;2017-07-01;
17;Produtos alimentícios;19.2;1701902;04022920;Outros cremes de leite, em recipiente de conteúdo inferior ou igual a 1kg;2017-07-01;
17;Produtos alimentícios;19.2;1701902;040110;Outros cremes de leite, em recipiente de conteúdo inferior ou igual a 1kg;2017-07-01;
17;Produtos alimentícios;19.2;1701902;040120;Outros cremes de leite, em recipiente de conteúdo inferior ou igual a 1kg;2017-07-01;
17;Produtos alimentícios;19.2;1701902;040210;Outros cremes de leite, em recipiente de conteúdo inferior ou igual a 1kg;2017-07-01;
17;Produtos alimentícios;20.0;1702000;04029;Leite condensado, em recipiente de conteúdo inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;20.1;1702001;04029;Leite condensado, em recipiente de conteúdo superior a 1 kg;2017-07-01;
17;Produtos alimentícios;21.0;1702100;0403;Iogurte e leite fermentado em recipiente de conteúdo inferior ou igual a 2 litros;2017-07-01;
17;Produtos alimentícios;21.1;1702101;0403;Iogurte e leite fermentado em recipiente de conteúdo superior a 2 litros;2017-07-01;
17;Produtos alimentícios;22.0;1702200;04039000;Coalhada;2017-07-01;
17;Produtos alimentícios;23.0;1702300;0406;Requeijão e similares, em recipiente de conteúdo inferior ou igual a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;23.1;1702301;0406;Requeijão e similares, em recipiente de conteúdo superior a 1 kg;2017-07-01;
17;Produtos alimentícios;24.0;1702400;0406;Queijos, exceto os dos CEST 17.024.01, 17.024.02, 17.024.03 e 17.024.04;2017-07-01;
17;Produtos alimentícios;24.1;1702401;04061010;Queijo muçarela;2017-07-01;
17;Produtos alimentícios;24.2;1702402;04061090;Queijo minas frescal;2017-07-01;
17;Produtos alimentícios;24.3;1702403;04061090;Queijo ricota;2017-07-01;
17;Produtos alimentícios;24.4;1702404;04061090;Queijo petit suisse;2017-07-01;
17;Produtos alimentícios;25.0;1702500;04051000;Manteiga, em embalagem de conteúdo inferior ou igual a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;25.1;1702501;04051000;Manteiga, em embalagem de conteúdo superior a 1 kg;2017-07-01;
17;Produtos alimentícios;25.2;1702502;04059090;Manteiga de garrafa;2017-07-01;
17;Produtos alimentícios;26.0;1702600;15171000;Margarina e creme vegetal em recipiente de conteúdo inferior ou igual a 500 g, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;27.0;1702700;15171000;Margarina e creme vegetal, em recipiente de conteúdo superior a 500 g e inferior ou igual a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;27.1;1702701;15171000;Margarina e creme vegetal, em recipiente de conteúdo superior a 1 kg;2017-07-01;
17;Produtos alimentícios;27.2;1702702;151790;Outras margarinas e cremes vegetais em recipiente de conteúdo inferior a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;28.0;1702800;15162000;Gorduras e óleos vegetais e respectivas frações, parcial ou totalmente hidrogenados, interesterificados, reesterificados ou elaidinizados, mesmo refinados, mas não preparados de outro modo, em recipiente de conteúdo inferior ou igual a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;28.1;1702801;15162000;Gorduras e óleos vegetais e respectivas frações, parcial ou totalmente hidrogenados, interesterificados, reesterificados ou elaidinizados, mesmo refinados, mas não preparados de outro modo, em recipiente de conteúdo superior a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;29.0;1702900;19019020;Doces de leite;2017-07-01;
17;Produtos alimentícios;30.0;1703000;19049000;Produtos à base de cereais, obtidos por expansão ou torrefação;2017-07-01;
17;Produtos alimentícios;30.0;1703000;19041000;Produtos à base de cereais, obtidos por expansão ou torrefação;2017-07-01;
17;Produtos alimentícios;31.0;1703100;19059090;Salgadinhos diversos;2017-07-01;
17;Produtos alimentícios;32.0;1703200;20052000;Batata frita, inhame e mandioca fritos;2017-07-01;
17;Produtos alimentícios;33.0;1703300;20081;Amendoim e castanhas tipo aperitivo, em embalagem de conteúdo inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;33.1;1703301;20081;Amendoim e castanhas tipo aperitivo, em embalagem de conteúdo superior a 1 kg;2017-07-01;
17;Produtos alimentícios;34.0;1703400;21032010;Catchup em embalagens imediatas de conteúdo inferior ou igual a 650 g, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;35.0;1703500;21039091;Condimentos e temperos compostos, incluindo molho de pimenta e outros molhos, em embalagens imediatas de conteúdo inferior ou igual a 1 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 3 g;2017-07-01;
17;Produtos alimentícios;35.0;1703500;21039021;Condimentos e temperos compostos, incluindo molho de pimenta e outros molhos, em embalagens imediatas de conteúdo inferior ou igual a 1 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 3 g;2017-07-01;
17;Produtos alimentícios;36.0;1703600;21031010;Molhos de soja preparados em embalagens imediatas de conteúdo inferior ou igual a 650 g, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;37.0;1703700;21033010;Farinha de mostarda em embalagens de conteúdo inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;38.0;1703800;21033021;Mostarda preparada em embalagens imediatas de conteúdo inferior ou igual a 650 g, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;39.0;1703900;21039011;Maionese em embalagens imediatas de conteúdo inferior ou igual a 650 g, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;40.0;1704000;2002;Tomates preparados ou conservados, exceto em vinagre ou em ácido acético, em embalagens de conteúdo inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;41.0;1704100;21032010;Molhos de tomate em embalagens imediatas de conteúdo inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;42.0;1704200;19042000;Barra de cereais;2017-07-01;
17;Produtos alimentícios;42.0;1704200;19049000;Barra de cereais;2017-07-01;
17;Produtos alimentícios;42.0;1704200;17049090;Barra de cereais;2017-07-01;
17;Produtos alimentícios;43.0;1704300;18063220;Barra de cereais contendo cacau;2017-07-01;
17;Produtos alimentícios;43.0;1704300;18069000;Barra de cereais contendo cacau;2017-07-01;
17;Produtos alimentícios;43.0;1704300;18063120;Barra de cereais contendo cacau;2017-07-01;
17;Produtos alimentícios;44.0;1704400;11010010;Farinha de trigo especial, em embalagem inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;44.1;1704401;11010010;Farinha de trigo especial, em embalagem superior a 1 kg e inferior a 5 kg;2017-07-01;
17;Produtos alimentícios;44.2;1704402;11010010;Farinha de trigo especial, em embalagem igual a 5 kg;2017-07-01;
17;Produtos alimentícios;44.3;1704403;11010010;Farinha de trigo especial, em embalagem superior a 5 kg e inferior ou igual a 25 kg;2017-07-01;
17;Produtos alimentícios;44.4;1704404;11010010;Farinha de trigo especial, em embalagem superior a 25 kg e inferior ou igual a 50 kg;2017-07-01;
17;Produtos alimentícios;44.5;1704405;11010010;Farinha de trigo comum, em embalagem igual a 5 kg;2017-07-01;
17;Produtos alimentícios;44.6;1704406;11010010;Farinha de trigo comum, em embalagem superior a 5 kg e inferior ou igual a 25 kg;2017-07-01;
17;Produtos alimentícios;44.7;1704407;11010010;Farinha de trigo comum, em embalagem superior a 25 kg e inferior ou igual a 50 kg;2017-07-01;
17;Produtos alimentícios;44.8;1704408;11010010;Farinha de trigo doméstica especial, em embalagem superior a 5 kg e inferior e igual a 10 kg;2017-07-01;
17;Produtos alimentícios;44.9;1704409;11010010;Farinha de trigo doméstica com fermento, em embalagem superior a 5 kg e inferior e igual a 10 kg;2017-07-01;
17;Produtos alimentícios;44.10;1704410;11010010;Farinha de trigo especial, em embalagem superior a 50 Kg;2017-07-01;
17;Produtos alimentícios;44.11;1704411;11010010;Farinha de trigo comum, em embalagem inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;44.12;1704412;11010010;Farinha de trigo comum, em embalagem superior a 1 kg e inferior a 5 Kg;2017-07-01;
17;Produtos alimentícios;44.13;1704413;11010010;Farinha de trigo comum, em embalagem superior a 50 kg;2017-07-01;
17;Produtos alimentícios;44.14;1704414;11010010;Farinha de trigo doméstica especial, em embalagem inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;44.15;1704415;11010010;Farinha de trigo doméstica especial, em embalagem superior a 1 kg e inferior a 5 Kg;2017-07-01;
17;Produtos alimentícios;44.16;1704416;11010010;Farinha de trigo doméstica especial, em embalagem igual a 5 Kg;2017-07-01;
17;Produtos alimentícios;44.17;1704417;11010010;Farinha de trigo doméstica especial, em embalagem superior a 10 Kg;2017-07-01;
17;Produtos alimentícios;44.18;1704418;11010010;Farinha de trigo doméstica com fermento, em embalagem inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;44.19;1704419;11010010;Farinha de trigo doméstica com fermento, em embalagem superior a 1 kg e inferior a 5 Kg;2017-07-01;
17;Produtos alimentícios;44.20;1704420;11010010;Farinha de trigo doméstica com fermento, em embalagem igual a 5 Kg;2017-07-01;
17;Produtos alimentícios;44.21;1704421;11010010;Farinha de trigo doméstica com fermento, em embalagem superior a 10 Kg;2017-07-01;
17;Produtos alimentícios;44.22;1704422;11010010;Outras farinhas de trigo, em embalagem inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;44.23;1704423;11010010;Outras farinhas de trigo, em embalagem superior a 1 kg e inferior a 5 Kg;2017-07-01;
17;Produtos alimentícios;44.24;1704424;11010010;Outras farinhas de trigo, em embalagem igual a 5 Kg;2017-07-01;
17;Produtos alimentícios;44.25;1704425;11010010;Outras farinhas de trigo, em embalagem superior a 5 Kg e inferior ou igual a 25 kg;2017-07-01;
17;Produtos alimentícios;44.26;1704426;11010010;Outras farinhas de trigo, em embalagem superior a 25 Kg e inferior ou igual a 50 kg;2017-07-01;
17;Produtos alimentícios;44.27;1704427;11010010;Outras farinhas de trigo, em embalagem superior a 50 Kg;2017-07-01;
17;Produtos alimentícios;45.0;1704500;11010020;Farinha de mistura de trigo com centeio (méteil);2017-07-01;
17;Produtos alimentícios;46.0;1704600;19019090;Misturas e preparações para bolos, em embalagem inferior 5 kg;2017-07-01;
17;Produtos alimentícios;46.0;1704600;19012000;Misturas e preparações para bolos, em embalagem inferior 5 kg;2017-07-01;
17;Produtos alimentícios;46.1;1704601;19019090;Misturas e preparações para bolos, em embalagem igual a 5 kg;2017-07-01;
17;Produtos alimentícios;46.1;1704601;19012000;Misturas e preparações para bolos, em embalagem igual a 5 kg;2017-07-01;
17;Produtos alimentícios;46.2;1704602;19019090;Misturas e preparações para bolos, em embalagem superior a 5 kg e inferior ou igual a 25 Kg;2017-07-01;
17;Produtos alimentícios;46.2;1704602;19012000;Misturas e preparações para bolos, em embalagem superior a 5 kg e inferior ou igual a 25 Kg;2017-07-01;
17;Produtos alimentícios;46.3;1704603;19019090;Misturas e preparações para bolos, em embalagem superior a 25 kg e inferior ou igual a 50 Kg;2017-07-01;
17;Produtos alimentícios;46.3;1704603;19012000;Misturas e preparações para bolos, em embalagem superior a 25 kg e inferior ou igual a 50 Kg;2017-07-01;
17;Produtos alimentícios;46.4;1704604;19019090;Misturas e preparações para bolos, em embalagem superior a 50 Kg;2017-07-01;
17;Produtos alimentícios;46.4;1704604;19012000;Misturas e preparações para bolos, em embalagem superior a 50 Kg;2017-07-01;
17;Produtos alimentícios;46.5;1704605;19019090;Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem inferior a 5 kg;2017-07-01;
17;Produtos alimentícios;46.5;1704605;19012000;Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem inferior a 5 kg;2017-07-01;
17;Produtos alimentícios;46.6;1704606;19012000;Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem igual a 5 kg;2017-07-01;
17;Produtos alimentícios;46.6;1704606;19019090;Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem igual a 5 kg;2017-07-01;
17;Produtos alimentícios;46.7;1704607;19012000;Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem superior a 5 kg e inferior ou igual a 25 Kg;2017-07-01;
17;Produtos alimentícios;46.7;1704607;19019090;Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem superior a 5 kg e inferior ou igual a 25 Kg;2017-07-01;
17;Produtos alimentícios;46.8;1704608;19019090;Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem superior a 25 kg e inferior ou igual a 50 Kg;2017-07-01;
17;Produtos alimentícios;46.8;1704608;19012000;Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem superior a 25 kg e inferior ou igual a 50 Kg;2017-07-01;
17;Produtos alimentícios;46.9;1704609;19012000;Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem superior a 50 Kg;2017-07-01;
17;Produtos alimentícios;46.9;1704609;19019090;Misturas e preparações para pães com menos de 80% de farinha de trigo na sua composição final, em embalagem superior a 50 Kg;2017-07-01;
17;Produtos alimentícios;46.10;1704610;19012000;Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem inferior a 5 kg;2017-07-01;
17;Produtos alimentícios;46.10;1704610;19019090;Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem inferior a 5 kg;2017-07-01;
17;Produtos alimentícios;46.11;1704611;19019090;Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem igual a 5 kg;2017-07-01;
17;Produtos alimentícios;46.11;1704611;19012000;Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem igual a 5 kg;2017-07-01;
17;Produtos alimentícios;46.12;1704612;19019090;Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem superior a 5 kg e inferior ou igual a 25 Kg;2017-07-01;
17;Produtos alimentícios;46.12;1704612;19012000;Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem superior a 5 kg e inferior ou igual a 25 Kg;2017-07-01;
17;Produtos alimentícios;46.13;1704613;19012000;Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem superior a 25 kg e inferior ou igual a 50 Kg;2017-07-01;
17;Produtos alimentícios;46.13;1704613;19019090;Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem superior a 25 kg e inferior ou igual a 50 Kg;2017-07-01;
17;Produtos alimentícios;46.14;1704614;19012000;Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem superior a 50 Kg;2017-07-01;
17;Produtos alimentícios;46.14;1704614;19019090;Misturas e preparações para pães com, no mínimo, 80% de farinha de trigo na sua composição final, em embalagem superior a 50 Kg;2017-07-01;
17;Produtos alimentícios;47.0;1704700;19023000;Massas alimentícias tipo instantânea;2017-07-01;
17;Produtos alimentícios;48.0;1704800;1902;Massas alimentícias, cozidas ou recheadas (de carne ou de outras substâncias) ou preparadas de outro modo, exceto as descritas nos CEST 17.047.00, 17.048.01, e 17.048.02;2017-07-01;
17;Produtos alimentícios;48.1;1704801;19024000;Cuscuz;2017-07-01;
17;Produtos alimentícios;48.2;1704802;19022000;Massas alimentícias recheadas (mesmo cozidas ou preparadas de outro modo);2017-07-01;
17;Produtos alimentícios;49.0;1704900;19021;Massas alimentícias do tipo comum, não cozidas, nem recheadas, nem preparadas de outro modo, exceto a descrita no CEST 17.049.03;2017-07-01;
17;Produtos alimentícios;49.1;1704901;19021;Massas alimentícias do tipo sêmola, não cozidas, nem recheadas, nem preparadas de outro modo, exceto a descrita no CEST 17.049.04;2017-07-01;
17;Produtos alimentícios;49.2;1704902;19021;Massas alimentícias do tipo granoduro, não cozidas, nem recheadas, nem preparadas de outro modo, exceto a descrita no CEST 17.049.05;2017-07-01;
17;Produtos alimentícios;49.3;1704903;19021900;Massas alimentícias do tipo comum, não cozidas, nem recheadas, nem preparadas de outro modo, que não contenham ovos;2017-07-01;
17;Produtos alimentícios;49.4;1704904;19021900;Massas alimentícias do tipo sêmola, não cozidas, nem recheadas, nem preparadas de outro modo, que não contenham ovos;2017-07-01;
17;Produtos alimentícios;49.5;1704905;19021900;Massas alimentícias do tipo granoduro, não cozidas, nem recheadas, nem preparadas de outro modo, que não contenham ovos;2017-07-01;
17;Produtos alimentícios;50.0;1705000;190520;Pães industrializados, inclusive de especiarias, exceto panetones e bolo de forma;2017-07-01;
17;Produtos alimentícios;51.0;1705100;19052090;Bolo de forma, inclusive de especiarias;2017-07-01;
17;Produtos alimentícios;52.0;1705200;19052010;Panetones;2017-07-01;
17;Produtos alimentícios;53.0;1705300;19053100;"Biscoitos e bolachas derivados de farinha de trigo; (exceto dos tipos cream cracker, água e sal, maisena, maria e outros de consumo popular que não sejam adicionados de cacau, nem recheados, cobertos ou amanteigados, independentemente de sua denominação comercial)";2017-07-01;
17;Produtos alimentícios;53.1;1705301;19053100;Biscoitos e bolachas derivados de farinha de trigo dos tipos maisena e maria e outros de consumo popular que não sejam adicionados de cacau, nem recheados, cobertos ou amanteigados, independentemente de sua denominação comercial, exceto o CEST 17.053.02;2017-07-01;
17;Produtos alimentícios;53.2;1705302;19053100;Biscoitos e bolachas derivados de farinha de trigo dos tipos "cream cracker" e "água e sal" de consumo popular;2017-07-01;
17;Produtos alimentícios;54.0;1705400;19053100;"Biscoitos e bolachas não derivados de farinha de trigo; (exceto dos tipos ""cream cracker"", ""água e sal"", ""maisena"" e ""maria"" e outros de consumo popular que não sejam adicionados de cacau, nem recheados, cobertos ou amanteigados, independentemente de sua denominação comercial)";2017-07-01;
17;Produtos alimentícios;54.1;1705401;19053100;Biscoitos e bolachas não derivados de farinha de trigo dos tipos "maisena" e "maria" e outros de consumo popular que não sejam adicionados de cacau, nem recheados, cobertos ou amanteigados, independentemente de sua denominação comercial, exceto o CEST 17.054.02;2017-07-01;
17;Produtos alimentícios;54.2;1705402;19053100;Biscoitos e bolachas não derivados de farinha de trigo dos tipos "cream cracker" e "água e sal" de consumo popular;2017-07-01;
17;Produtos alimentícios;56.0;1705600;19059020;Biscoitos e bolachas derivados de farinha de trigo dos tipos cream cracker e água e sal;2017-07-01;
17;Produtos alimentícios;56.1;1705601;19059020;Biscoitos e bolachas não derivados de farinha de trigo dos tipos cream cracker e água e sal;2017-07-01;
17;Produtos alimentícios;56.2;1705602;19059020;Outras bolachas, exceto casquinhas para sorvete e os biscoitos e bolachas relacionados nos CEST 17.056.00 e 17.056.01;2017-07-01;
17;Produtos alimentícios;57.0;1705700;19053200;Waffles e wafers - sem cobertura;2017-07-01;
17;Produtos alimentícios;58.0;1705800;19053200;Waffles e wafers - com cobertura;2017-07-01;
17;Produtos alimentícios;59.0;1705900;19054000;Torradas, pão torrado e produtos semelhantes torrados;2017-07-01;
17;Produtos alimentícios;60.0;1706000;19059010;Outros pães de forma;2017-07-01;
17;Produtos alimentícios;62.0;1706200;19059090;Outros pães, exceto pão francês de até 200 g;2017-07-01;
17;Produtos alimentícios;62.1;1706201;19059090;"Outros bolos industrializados e produtos de panificação não especificados anteriormente; exceto casquinhas para sorvete e pães";2017-07-01;
17;Produtos alimentícios;63.0;1706300;19051000;Pão denominado knackebrot;2017-07-01;
17;Produtos alimentícios;64.0;1706400;190590;Demais pães industrializados;2017-07-01;
17;Produtos alimentícios;65.0;1706500;15079011;Óleo de soja refinado, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros;2017-07-01;
17;Produtos alimentícios;66.0;1706600;1508;Óleo de amendoim refinado, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros;2017-07-01;
17;Produtos alimentícios;67.0;1706700;1509;Azeites de oliva, em recipientes com capacidade inferior a 2 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 20 mililitros;2017-07-01;
17;Produtos alimentícios;67.1;1706701;1509;Azeites de oliva, em recipientes com capacidade igual ou superior a 2 litros e inferior ou igual a 5 litros;2017-07-01;
17;Produtos alimentícios;67.2;1706702;1509;Azeites de oliva, em recipientes com capacidade superior a 5 litros;2017-07-01;
17;Produtos alimentícios;68.0;1706800;15100000;Outros óleos e respectivas frações, obtidos exclusivamente a partir de azeitonas, mesmo refinados, mas não quimicamente modificados, e misturas desses óleos ou frações com óleos ou frações da posição 15.09, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros;2017-07-01;
17;Produtos alimentícios;69.0;1706900;15121911;Óleo de girassol em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros;2017-07-01;
17;Produtos alimentícios;69.1;1706901;15122910;Óleo de algodão refinado em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros;2017-07-01;
17;Produtos alimentícios;70.0;1707000;15141;Óleo de canola, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros;2017-07-01;
17;Produtos alimentícios;71.0;1707100;15151900;Óleo de linhaça refinado, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros;2017-07-01;
17;Produtos alimentícios;72.0;1707200;15152910;Óleo de milho refinado, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros;2017-07-01;
17;Produtos alimentícios;73.0;1707300;15122990;Outros óleos refinados, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros;2017-07-01;
17;Produtos alimentícios;74.0;1707400;15179010;Misturas de óleos refinados, para consumo humano, em recipientes com capacidade inferior ou igual a 5 litros, exceto as embalagens individuais de conteúdo inferior ou igual a 15 mililitros;2017-07-01;
17;Produtos alimentícios;75.0;1707500;1518;Outros óleos vegetais comestíveis não especificados anteriormente;2017-07-01;
17;Produtos alimentícios;75.0;1707500;1511;Outros óleos vegetais comestíveis não especificados anteriormente;2017-07-01;
17;Produtos alimentícios;75.0;1707500;1513;Outros óleos vegetais comestíveis não especificados anteriormente;2017-07-01;
17;Produtos alimentícios;75.0;1707500;1514;Outros óleos vegetais comestíveis não especificados anteriormente;2017-07-01;
17;Produtos alimentícios;75.0;1707500;1515;Outros óleos vegetais comestíveis não especificados anteriormente;2017-07-01;
17;Produtos alimentícios;75.0;1707500;1516;Outros óleos vegetais comestíveis não especificados anteriormente;2017-07-01;
17;Produtos alimentícios;76.0;1707600;16010000;"Enchidos (embutidos) e produtos semelhantes, de carne, miudezas ou sangue; exceto salsicha, linguiça e mortadela";2017-07-01;
17;Produtos alimentícios;77.0;1707700;16010000;Salsicha e linguiça, exceto as descritas nos CEST 17.077.01;2017-07-01;
17;Produtos alimentícios;77.1;1707701;16010000;Salsicha em lata;2017-07-01;
17;Produtos alimentícios;78.0;1707800;16010000;Mortadela;2017-07-01;
17;Produtos alimentícios;79.0;1707900;1602;Outras preparações e conservas de carne, miudezas ou de sangue, exceto as descritas nos CEST 17.079.01, 17.079.02, 17.079.03, 17.079.04, 17.079.05, 17.079.06 e 17.079.07;2017-07-01;
17;Produtos alimentícios;79.1;1707901;16023100;Outras preparações e conservas de carne, de miudezas ou de sangue, de aves da posição 01.05: de peruas e de perus.;2017-07-01;
17;Produtos alimentícios;79.2;1707902;16023210;Outras preparações e conservas de carne, de miudezas ou de sangue, de aves da posição 01.05: de galos e de galinhas, com conteúdo de carne ou de miudezas superior ou igual a 57 %, em peso, não cozidas;2017-07-01;
17;Produtos alimentícios;79.3;1707903;16023220;Outras preparações e conservas de carne, de miudezas ou de sangue, todas de aves da posição 01.05: de galos e de galinhas, com conteúdo de carne ou de miudezas superior ou igual a 57 %, em peso, cozidas;2017-07-01;
17;Produtos alimentícios;79.4;1707904;16024100;Outras preparações e conservas de carne, de miudezas ou de sangue, da espécie suína: pernas e respectivos pedaços;2017-07-01;
17;Produtos alimentícios;79.5;1707905;16024900;Outras preparações e conservas de carne, de miudezas ou de sangue, da espécie suína: outras, incluindo as misturas;2017-07-01;
17;Produtos alimentícios;79.6;1707906;16025000;Outras preparações e conservas de carne, de miudezas ou de sangue, da espécie bovina, exceto os descritos no CEST 17.079.07;2017-07-01;
17;Produtos alimentícios;79.7;1707907;16025000;Apresuntado;2017-07-01;
17;Produtos alimentícios;80.0;1708000;1604;"Preparações e conservas de peixes; caviar e seus sucedâneos preparados a partir de ovas de peixe; exceto os descritos nos CEST 17.080.01 e 17.081.00";2017-07-01;
17;Produtos alimentícios;80.1;1708001;16042010;Outras preparações e conservas de atuns;2017-07-01;
17;Produtos alimentícios;81.0;1708100;1604;Sardinha em conserva;2017-07-01;
17;Produtos alimentícios;82.0;1708200;1605;Crustáceos, moluscos e outros invertebrados aquáticos, preparados ou em conservas;2017-07-01;
17;Produtos alimentícios;83.0;1708300;02102000;Carne de gado bovino, ovino e bufalino e produtos comestíveis resultantes da matança desse gado submetidos à salga, secagem ou desidratação;2017-07-01;
17;Produtos alimentícios;83.0;1708300;02109900;Carne de gado bovino, ovino e bufalino e produtos comestíveis resultantes da matança desse gado submetidos à salga, secagem ou desidratação;2017-07-01;
17;Produtos alimentícios;83.0;1708300;1502;Carne de gado bovino, ovino e bufalino e produtos comestíveis resultantes da matança desse gado submetidos à salga, secagem ou desidratação;2017-07-01;
17;Produtos alimentícios;84.0;1708400;0201;Carne de gado bovino, ovino e bufalino e demais produtos comestíveis resultantes da matança desse gado frescos, refrigerados ou congelados;2017-07-01;
17;Produtos alimentícios;84.0;1708400;0202;Carne de gado bovino, ovino e bufalino e demais produtos comestíveis resultantes da matança desse gado frescos, refrigerados ou congelados;2017-07-01;
17;Produtos alimentícios;84.0;1708400;0204;Carne de gado bovino, ovino e bufalino e demais produtos comestíveis resultantes da matança desse gado frescos, refrigerados ou congelados;2017-07-01;
17;Produtos alimentícios;84.0;1708400;0206;Carne de gado bovino, ovino e bufalino e demais produtos comestíveis resultantes da matança desse gado frescos, refrigerados ou congelados;2017-07-01;
17;Produtos alimentícios;85.0;1708500;0204;Carnes de animais das espécies caprina, frescas, refrigeradas ou congeladas;2017-07-01;
17;Produtos alimentícios;86.0;1708600;15021019;Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados ou salmourados resultantes do abate de caprinos;2017-07-01;
17;Produtos alimentícios;86.0;1708600;15029000;Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados ou salmourados resultantes do abate de caprinos;2017-07-01;
17;Produtos alimentícios;86.0;1708600;02109900;Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados ou salmourados resultantes do abate de caprinos;2017-07-01;
17;Produtos alimentícios;87.0;1708700;0209;Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de aves, exceto os descritos no CEST 17.087.02;2017-07-01;
17;Produtos alimentícios;87.0;1708700;02109900;Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de aves, exceto os descritos no CEST 17.087.02;2017-07-01;
17;Produtos alimentícios;87.0;1708700;1501;Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de aves, exceto os descritos no CEST 17.087.02;2017-07-01;
17;Produtos alimentícios;87.0;1708700;0207;Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de aves, exceto os descritos no CEST 17.087.02;2017-07-01;
17;Produtos alimentícios;87.1;1708701;0206;Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de suínos;2017-07-01;
17;Produtos alimentícios;87.1;1708701;0209;Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de suínos;2017-07-01;
17;Produtos alimentícios;87.1;1708701;02101;Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de suínos;2017-07-01;
17;Produtos alimentícios;87.1;1708701;02109900;Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de suínos;2017-07-01;
17;Produtos alimentícios;87.1;1708701;1501;Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de suínos;2017-07-01;
17;Produtos alimentícios;87.1;1708701;0203;Carnes e demais produtos comestíveis frescos, resfriados, congelados, salgados, em salmoura, simplesmente temperados, secos ou defumados, resultantes do abate de suínos;2017-07-01;
17;Produtos alimentícios;87.2;1708702;02072;Carnes de aves inteiras e com peso unitário superior a 3 kg, temperadas;2017-07-01;
17;Produtos alimentícios;87.2;1708702;02071;Carnes de aves inteiras e com peso unitário superior a 3 kg, temperadas;2017-07-01;
17;Produtos alimentícios;88.0;1708800;0710;Produtos hortícolas, cozidos em água ou vapor, congelados, em embalagens de conteúdo inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;88.1;1708801;0710;Produtos hortícolas, cozidos em água ou vapor, congelados, em embalagens de conteúdo superior a 1 kg;2017-07-01;
17;Produtos alimentícios;89.0;1708900;0811;Frutas, não cozidas ou cozidas em água ou vapor, congeladas, mesmo adicionadas de açúcar ou de outros edulcorantes, em embalagens de conteúdo inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;89.1;1708901;0811;Frutas, não cozidas ou cozidas em água ou vapor, congeladas, mesmo adicionadas de açúcar ou de outros edulcorantes, em embalagens de conteúdo superior a 1 kg;2017-07-01;
17;Produtos alimentícios;90.0;1709000;2001;Produtos hortícolas, frutas e outras partes comestíveis de plantas, preparados ou conservados em vinagre ou em ácido acético, em embalagens de conteúdo inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;90.1;1709001;2001;Produtos hortícolas, frutas e outras partes comestíveis de plantas, preparados ou conservados em vinagre ou em ácido acético, em embalagens de conteúdo superior a 1 kg;2017-07-01;
17;Produtos alimentícios;91.0;1709100;2004;Outros produtos hortícolas preparados ou conservados, exceto em vinagre ou em ácido acético, congelados, com exceção dos produtos da posição 20.06, em embalagens de conteúdo inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;91.1;1709101;2004;Outros produtos hortícolas preparados ou conservados, exceto em vinagre ou em ácido acético, congelados, com exceção dos produtos da posição 20.06, em embalagens de conteúdo superior a 1 kg;2017-07-01;
17;Produtos alimentícios;92.0;1709200;2005;Outros produtos hortícolas preparados ou conservados, exceto em vinagre ou em ácido acético, não congelados, com exceção dos produtos da posição 20.06, excluídos batata, inhame e mandioca fritos, em embalagens de conteúdo inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;92.1;1709201;2005;Outros produtos hortícolas preparados ou conservados, exceto em vinagre ou em ácido acético, não congelados, com exceção dos produtos da posição 20.06, excluídos batata, inhame e mandioca fritos, em embalagens de conteúdo superior a 1 kg;2017-07-01;
17;Produtos alimentícios;93.0;1709300;20060000;Produtos hortícolas, frutas, cascas de frutas e outras partes de plantas, conservados com açúcar (passados por calda, glaceados ou cristalizados), em embalagens de conteúdo inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;93.1;1709301;20060000;Produtos hortícolas, frutas, cascas de frutas e outras partes de plantas, conservados com açúcar (passados por calda, glaceados ou cristalizados), em embalagens de conteúdo superior a 1 kg;2017-07-01;
17;Produtos alimentícios;94.0;1709400;2007;Doces, geleias, marmelades, purês e pastas de frutas, obtidos por cozimento, com ou sem adição de açúcar ou de outros edulcorantes, em embalagens de conteúdo inferior ou igual a 1 kg, exceto as embalagens individuais de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;94.1;1709401;2007;Doces, geleias, marmelades, purês e pastas de frutas, obtidos por cozimento, com ou sem adição de açúcar ou de outros edulcorantes, em embalagens de conteúdo superior a 1 kg;2017-07-01;
17;Produtos alimentícios;95.0;1709500;2008;Frutas e outras partes comestíveis de plantas, preparadas ou conservadas de outro modo, com ou sem adição de açúcar ou de outros edulcorantes ou de álcool, não especificadas nem compreendidas em outras posições, excluídos os amendoins e castanhas tipo aperitivo, da posição 2008.1, em embalagens de conteúdo inferior ou igual a 1 kg;2017-07-01;
17;Produtos alimentícios;95.1;1709501;2008;Frutas e outras partes comestíveis de plantas, preparadas ou conservadas de outro modo, com ou sem adição de açúcar ou de outros edulcorantes ou de álcool, não especificadas nem compreendidas em outras posições, excluídos os amendoins e castanhas tipo aperitivo, da posição 2008.1, em embalagens superior a 1 kg;2017-07-01;
17;Produtos alimentícios;96.0;1709600;0901;Café torrado e moído, em embalagens de conteúdo inferior ou igual a 2 kg, exceto os classificados nos CEST 17.096.04 e 17.096.05;2017-07-01;
17;Produtos alimentícios;96.1;1709601;0901;Café torrado e moído, em embalagens de conteúdo superior a 2 kg;2017-07-01;
17;Produtos alimentícios;96.2;1709602;0901;Café torrado em grão, em embalagens de conteúdo inferior ou igual a 2 kg;2017-07-01;
17;Produtos alimentícios;96.3;1709603;0901;Café torrado em grão, em embalagens de conteúdo superior a 2 kg;2017-07-01;
17;Produtos alimentícios;96.4;1709604;0901;Café torrado e moído, em cápsulas, exceto os descritos no CEST 17.096.05;2017-07-01;
17;Produtos alimentícios;96.5;1709605;0901;Café descafeinado torrado e moído, em cápsulas;2017-07-01;
17;Produtos alimentícios;97.0;1709700;0902;Chá, mesmo aromatizado;2017-07-01;
17;Produtos alimentícios;97.0;1709700;12119090;Chá, mesmo aromatizado;2017-07-01;
17;Produtos alimentícios;97.0;1709700;21069090;Chá, mesmo aromatizado;2017-07-01;
17;Produtos alimentícios;98.0;1709800;090300;Mate;2017-07-01;
17;Produtos alimentícios;99.0;1709900;17011;Açúcar refinado, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;99.0;1709900;17019900;Açúcar refinado, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;99.1;1709901;17011;Açúcar refinado, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg;2017-07-01;
17;Produtos alimentícios;99.1;1709901;17019900;Açúcar refinado, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg;2017-07-01;
17;Produtos alimentícios;99.2;1709902;17011;Açúcar refinado, em embalagens de conteúdo superior a 5 kg;2017-07-01;
17;Produtos alimentícios;99.2;1709902;17019900;Açúcar refinado, em embalagens de conteúdo superior a 5 kg;2017-07-01;
17;Produtos alimentícios;100.0;1710000;17019100;Açúcar refinado adicionado de aromatizante ou de corante em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;100.1;1710001;17019100;Açúcar refinado adicionado de aromatizante ou de corante em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg;2017-07-01;
17;Produtos alimentícios;100.2;1710002;17019100;Açúcar refinado adicionado de aromatizante ou de corante em embalagens de conteúdo superior a 5 kg;2017-07-01;
17;Produtos alimentícios;101.0;1710100;17011;Açúcar cristal, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;101.0;1710100;17019900;Açúcar cristal, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;101.1;1710101;17011;Açúcar cristal, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg;2017-07-01;
17;Produtos alimentícios;101.1;1710101;17019900;Açúcar cristal, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg;2017-07-01;
17;Produtos alimentícios;101.2;1710102;17011;Açúcar cristal, em embalagens de conteúdo superior a 5 kg;2017-07-01;
17;Produtos alimentícios;101.2;1710102;17019900;Açúcar cristal, em embalagens de conteúdo superior a 5 kg;2017-07-01;
17;Produtos alimentícios;102.0;1710200;17019100;Açúcar cristal adicionado de aromatizante ou de corante, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;102.1;1710201;17019100;Açúcar cristal adicionado de aromatizante ou de corante, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg;2017-07-01;
17;Produtos alimentícios;102.2;1710202;170191;Açúcar cristal adicionado de aromatizante ou de corante, em embalagens de conteúdo superior a 5 kg;2017-07-01;
17;Produtos alimentícios;103.0;1710300;17011;Outros tipos de açúcar, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;103.0;1710300;17019900;Outros tipos de açúcar, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;103.1;1710301;17011;Outros tipos de açúcar, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg;2017-07-01;
17;Produtos alimentícios;103.1;1710301;17019900;Outros tipos de açúcar, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg;2017-07-01;
17;Produtos alimentícios;103.2;1710302;17011;Outros tipos de açúcar, em embalagens de conteúdo superior a 5 kg;2017-07-01;
17;Produtos alimentícios;103.2;1710302;17019900;Outros tipos de açúcar, em embalagens de conteúdo superior a 5 kg;2017-07-01;
17;Produtos alimentícios;104.0;1710400;17019100;Outros tipos de açúcar adicionado de aromatizante ou de corante, em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;104.1;1710401;17019100;Outros tipos de açúcar adicionado de aromatizante ou de corante, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg;2017-07-01;
17;Produtos alimentícios;104.2;1710402;17019100;Outros tipos de açúcar adicionado de aromatizante ou de corante, em embalagens de conteúdo superior a 5 kg;2017-07-01;
17;Produtos alimentícios;105.0;1710500;1702;Outros açúcares em embalagens de conteúdo inferior ou igual a 2 kg, exceto as embalagens contendo envelopes individualizados (sachês) de conteúdo inferior ou igual a 10 g;2017-07-01;
17;Produtos alimentícios;105.1;1710501;1702;Outros açúcares, em embalagens de conteúdo superior a 2 kg e inferior ou igual a 5 kg;2017-07-01;
17;Produtos alimentícios;105.2;1710502;1702;Outros açúcares, em embalagens de conteúdo superior a 5 kg;2017-07-01;
17;Produtos alimentícios;106.0;1710600;20081900;Milho para pipoca (micro-ondas);2017-07-01;
17;Produtos alimentícios;107.0;1710700;21011;Extratos, essências e concentrados de café e preparações à base destes extratos, essências ou concentrados ou à base de café, em embalagens de conteúdo inferior ou igual a 500 g, exceto os classificados no CEST 17.107.01;2017-07-01;
17;Produtos alimentícios;107.1;1710701;21011;Extratos, essências e concentrados de café e preparações à base destes extratos, essências ou concentrados ou à base de café, em cápsulas;2017-07-01;
17;Produtos alimentícios;108.0;1710800;210120;Extratos, essências e concentrados de chá ou de mate e preparações à base destes extratos, essências ou concentrados ou à base de chá ou de mate, em embalagens de conteúdo inferior ou igual a 500 g, exceto as bebidas prontas à base de mate ou chá e os itens classificados no CEST 17.108.01;2017-07-01;
17;Produtos alimentícios;108.1;1710801;210120;Extratos, essências e concentrados de chá ou de mate e preparações à base destes extratos, essências ou concentrados ou à base de chá ou de mate, em cápsulas;2017-07-01;
17;Produtos alimentícios;109.0;1710900;19019090;Preparações em pó para cappuccino e similares, em embalagens de conteúdo inferior ou igual a 500 g;2017-07-01;
17;Produtos alimentícios;109.0;1710900;21011190;Preparações em pó para cappuccino e similares, em embalagens de conteúdo inferior ou igual a 500 g;2017-07-01;
17;Produtos alimentícios;109.0;1710900;21011200;Preparações em pó para cappuccino e similares, em embalagens de conteúdo inferior ou igual a 500 g;2017-07-01;
17;Produtos alimentícios;110.0;1711000;22021000;Refrescos e outras bebidas prontas para beber, à base de chá e mate;2017-07-01;
17;Produtos alimentícios;111.0;1711100;22021000;Refrescos e outras bebidas não alcoólicas, exceto os refrigerantes e as demais bebidas nos CEST 03.007.00 e 17.110.00;2017-07-01;
17;Produtos alimentícios;112.0;1711200;22029900;Néctares de frutas e outras bebidas não alcoólicas prontas para beber, exceto isotônicos e energéticos;2017-07-01;
17;Produtos alimentícios;113.0;1711300;210120;Bebidas prontas à base de mate ou chá;2017-07-01;
17;Produtos alimentícios;113.0;1711300;22029900;Bebidas prontas à base de mate ou chá;2017-07-01;
17;Produtos alimentícios;114.0;1711400;22029900;Bebidas prontas à base de café;2017-07-01;
17;Produtos alimentícios;115.0;1711500;22029900;Bebidas alimentares prontas à base de soja, leite ou cacau, inclusive os produtos denominados bebidas lácteas;2017-07-01;
19;Produtos de papelaria;1.0;1900100;32131000;Tinta guache;2017-07-01;
19;Produtos de papelaria;2.0;1900200;39162000;Espiral - perfil para encadernação, de plástico e outros materiais classificados nas posições 3901 a 3914;2017-07-01;
19;Produtos de papelaria;3.0;1900300;39161000;Outros espirais - perfil para encadernação, de plástico e outros materiais classificados nas posições 3901 a 3914;2017-07-01;
19;Produtos de papelaria;3.0;1900300;391690;Outros espirais - perfil para encadernação, de plástico e outros materiais classificados nas posições 3901 a 3914;2017-07-01;
19;Produtos de papelaria;4.0;1900400;39261000;Artigos de escritório e artigos escolares de plástico e outros materiais classificados nas posições 3901 a 3914, exceto estojos;2017-07-01;
19;Produtos de papelaria;5.0;1900500;42021;Maletas e pastas para documentos e de estudante, e artefatos semelhantes;2017-07-01;
19;Produtos de papelaria;5.0;1900500;42029;Maletas e pastas para documentos e de estudante, e artefatos semelhantes;2017-07-01;
19;Produtos de papelaria;5.1;1900501;42021;Baús, malas e maletas para viagem;2017-07-01;
19;Produtos de papelaria;5.1;1900501;42029;Baús, malas e maletas para viagem;2017-07-01;
19;Produtos de papelaria;6.0;1900600;39269090;Prancheta de plástico;2017-07-01;
19;Produtos de papelaria;7.0;1900700;48022090;Bobina para fax;2017-07-01;
19;Produtos de papelaria;7.0;1900700;48119090;Bobina para fax;2017-07-01;
19;Produtos de papelaria;8.0;1900800;4802549;Papel seda;2017-07-01;
19;Produtos de papelaria;9.0;1900900;48025499;Bobina para máquina de calcular, PDV ou equipamentos similares;2017-07-01;
19;Produtos de papelaria;9.0;1900900;48025799;Bobina para máquina de calcular, PDV ou equipamentos similares;2017-07-01;
19;Produtos de papelaria;9.0;1900900;48162000;Bobina para máquina de calcular, PDV ou equipamentos similares;2017-07-01;
19;Produtos de papelaria;10.0;1901000;4802569;"Cartolina escolar e papel cartão, brancos e coloridos; recados auto adesivos (LP note); papéis de presente, todos cortados em tamanho pronto para uso escolar e doméstico";2017-07-01;
19;Produtos de papelaria;10.0;1901000;4802579;"Cartolina escolar e papel cartão, brancos e coloridos; recados auto adesivos (LP note); papéis de presente, todos cortados em tamanho pronto para uso escolar e doméstico";2017-07-01;
19;Produtos de papelaria;10.0;1901000;4802589;"Cartolina escolar e papel cartão, brancos e coloridos; recados auto adesivos (LP note); papéis de presente, todos cortados em tamanho pronto para uso escolar e doméstico";2017-07-01;
19;Produtos de papelaria;11.0;1901100;48022090;Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia Thermo-autochrome, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela;2017-07-01;
19;Produtos de papelaria;11.0;1901100;37031010;Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia Thermo-autochrome, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela;2017-07-01;
19;Produtos de papelaria;11.0;1901100;37031029;Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia Thermo-autochrome, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela;2017-07-01;
19;Produtos de papelaria;11.0;1901100;37032000;Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia Thermo-autochrome, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela;2017-07-01;
19;Produtos de papelaria;11.0;1901100;37039010;Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia Thermo-autochrome, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela;2017-07-01;
19;Produtos de papelaria;11.0;1901100;37040000;Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia Thermo-autochrome, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela;2017-07-01;
19;Produtos de papelaria;11.0;1901100;48022010;Papel fotográfico, exceto: (i) os papéis fotográficos emulsionados com haleto de prata tipo brilhante, matte ou lustre, em rolo e, com largura igual ou superior a 102 mm e comprimento inferior ou igual a 350 m, (ii) os papéis fotográficos emulsionados com haleto de prata tipo brilhante ou fosco, em folha e com largura igual ou superior a 152 mm e comprimento inferior ou igual a 307 mm, (iii) papel de qualidade fotográfica com tecnologia Thermo-autochrome, que submetido a um processo de aquecimento seja capaz de formar imagens por reação química e combinação das camadas cyan, magenta e amarela;2017-07-01;
19;Produtos de papelaria;12.0;1901200;48101390;Papel almaço;2017-07-01;
19;Produtos de papelaria;13.0;1901300;48169010;Papel hectográfico;2017-07-01;
19;Produtos de papelaria;14.0;1901400;39202019;Papel celofane e tipo celofane;2017-07-01;
19;Produtos de papelaria;15.0;1901500;48062000;Papel impermeável;2017-07-01;
19;Produtos de papelaria;16.0;1901600;48081000;Papel crepon;2017-07-01;
19;Produtos de papelaria;17.0;1901700;48102290;Papel fantasia;2017-07-01;
19;Produtos de papelaria;18.0;1901800;4809;Papel-carbono, papel autocopiativo (exceto os vendidos em rolos de diâmetro igual ou superior a 60 cm e os vendidos em folhas de formato igual ou superior a 60 cm de altura e igual ou superior a 90 cm de largura) e outros papéis para cópia ou duplicação (incluídos os papéis para estênceis ou para chapas ofsete), estênceis completos e chapas ofsete, de papel, em folhas, mesmo acondicionados em caixas;2017-07-01;
19;Produtos de papelaria;18.0;1901800;4816;Papel-carbono, papel autocopiativo (exceto os vendidos em rolos de diâmetro igual ou superior a 60 cm e os vendidos em folhas de formato igual ou superior a 60 cm de altura e igual ou superior a 90 cm de largura) e outros papéis para cópia ou duplicação (incluídos os papéis para estênceis ou para chapas ofsete), estênceis completos e chapas ofsete, de papel, em folhas, mesmo acondicionados em caixas;2017-07-01;
19;Produtos de papelaria;19.0;1901900;4817;Envelopes, aerogramas, bilhetes-postais não ilustrados e cartões para correspondência, de papel ou cartão, caixas, sacos e semelhantes, de papel ou cartão, contendo um sortido de artigos para correspondência;2017-07-01;
19;Produtos de papelaria;20.0;1902000;48201000;Livros de registro e de contabilidade, blocos de notas, de encomendas, de recibos, de apontamentos, de papel para cartas, agendas e artigos semelhantes;2017-07-01;
19;Produtos de papelaria;21.0;1902100;48202000;Cadernos;2017-07-01;
19;Produtos de papelaria;22.0;1902200;48203000;Classificadores, capas para encadernação (exceto as capas para livros) e capas de processos;2017-07-01;
19;Produtos de papelaria;23.0;1902300;48204000;Formulários em blocos tipo manifold, mesmo com folhas intercaladas de papel-carbono;2017-07-01;
19;Produtos de papelaria;24.0;1902400;48205000;Álbuns para amostras ou para coleções;2017-07-01;
19;Produtos de papelaria;25.0;1902500;48209000;Pastas para documentos, outros artigos escolares, de escritório ou de papelaria, de papel ou cartão e capas para livros, de papel ou cartão;2017-07-01;
19;Produtos de papelaria;26.0;1902600;49090000;Cartões postais impressos ou ilustrados, cartões impressos com votos ou mensagens pessoais, mesmo ilustrados, com ou sem envelopes, guarnições ou aplicações (conhecidos como cartões de expressão social - de época/sentimento);2017-07-01;
19;Produtos de papelaria;27.0;1902700;96081000;Canetas esferográficas;2017-07-01;
19;Produtos de papelaria;28.0;1902800;96082000;Canetas e marcadores, com ponta de feltro ou com outras pontas porosas;2017-07-01;
19;Produtos de papelaria;29.0;1902900;96083000;Canetas tinteiro;2017-07-01;
19;Produtos de papelaria;30.0;1903000;9608;"Outras canetas; sortidos de canetas";2017-07-01;
19;Produtos de papelaria;31.0;1903100;480256;Papel cortado cutsize (tipo A3, A4, ofício I e II, carta e outros);2017-07-01;
19;Produtos de papelaria;32.0;1903200;52105990;Papel camurça;2017-07-01;
19;Produtos de papelaria;33.0;1903300;76071190;Papel laminado e papel espelho;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;1.0;2000100;12119090;Henna (embalagens de conteúdo inferior ou igual a 200 g);2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;1.1;2000101;12119090;Henna (embalagens de conteúdo superior a 200 g);2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;2.0;2000200;27121000;Vaselina;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;3.0;2000300;28142000;Amoníaco em solução aquosa (amônia);2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;4.0;2000400;28470000;Peróxido de hidrogênio, em embalagens de conteúdo inferior ou igual a 500 ml;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;5.0;2000500;30067000;Lubrificação íntima;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;6.0;2000600;3301;"Óleos essenciais (desterpenados ou não), incluídos os chamados concretos ou absolutos; resinoides; oleorresinas de extração; soluções concentradas de óleos essenciais em gorduras, em óleos fixos, em ceras ou em matérias análogas, obtidas por tratamento de flores através de substâncias gordas ou por maceração; subprodutos terpênicos residuais da desterpenação dos óleos essenciais; águas destiladas aromáticas e soluções aquosas de óleos essenciais, em embalagens de conteúdo inferior ou igual a 500 ml";2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;7.0;2000700;33030010;Perfumes (extratos);2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;8.0;2000800;33030020;Águas-de-colônia;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;9.0;2000900;33041000;Produtos de maquilagem para os lábios;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;10.0;2001000;33042010;Sombra, delineador, lápis para sobrancelhas e rímel;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;11.0;2001100;33042090;Outros produtos de maquilagem para os olhos;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;12.0;2001200;33043000;Preparações para manicuros e pedicuros, incluindo removedores de esmalte à base de acetona;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;13.0;2001300;33049100;Pós, incluídos os compactos;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;14.0;2001400;33049910;Cremes de beleza, cremes nutritivos e loções tônicas;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;15.0;2001500;33049990;Outros produtos de beleza ou de maquilagem preparados e preparações para conservação ou cuidados da pele, exceto as preparações solares e antissolares;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;16.0;2001600;33049990;Preparações solares e antissolares;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;17.0;2001700;33051000;Xampus para o cabelo;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;18.0;2001800;33052000;Preparações para ondulação ou alisamento, permanentes, dos cabelos;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;19.0;2001900;33053000;Laquês para o cabelo;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;20.0;2002000;33059000;Outras preparações capilares, incluindo máscaras e finalizadores;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;21.0;2002100;33059000;Condicionadores;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;22.0;2002200;33059000;Tintura para o cabelo;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;23.0;2002300;33061000;Dentifrícios;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;24.0;2002400;33062000;Fios utilizados para limpar os espaços interdentais (fios dentais);2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;25.0;2002500;33069000;Outras preparações para higiene bucal ou dentária;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;26.0;2002600;33071000;Preparações para barbear (antes, durante ou após);2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;27.0;2002700;33072010;Desodorantes (desodorizantes) corporais líquidos, exceto os classificados no CEST 20.027.01;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;27.1;2002701;33072010;Loções e óleos desodorantes hidratantes líquidos;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;28.0;2002800;33072010;Antiperspirantes líquidos;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;29.0;2002900;33072090;Outros desodorantes (desodorizantes) corporais, exceto os classificados no CEST 20.029.01;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;29.1;2002901;33072090;Outras loções e óleos desodorantes hidratantes;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;30.0;2003000;33072090;Outros antiperspirantes;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;31.0;2003100;33073000;Sais perfumados e outras preparações para banhos;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;32.0;2003200;33079000;Outros produtos de perfumaria preparados;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;32.1;2003201;33079000;Outros produtos de toucador preparados;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;33.0;2003300;33079000;Soluções para lentes de contato ou para olhos artificiais;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;34.0;2003400;34011190;Sabões de toucador em barras, pedaços ou figuras moldados;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;35.0;2003500;34011900;Outros sabões, produtos e preparações, em barras, pedaços ou figuras moldados;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;35.1;2003501;34011900;Lenços umedecidos;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;36.0;2003600;34012010;Sabões de toucador sob outras formas;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;37.0;2003700;34013000;Produtos e preparações orgânicos tensoativos para lavagem da pele, na forma de líquido ou de creme, acondicionados para venda a retalho, mesmo contendo sabão;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;38.0;2003800;40149010;Bolsa para gelo ou para água quente;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;39.0;2003900;40149090;Chupetas e bicos para mamadeiras e para chupetas, de borracha;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;40.0;2004000;39269090;Chupetas e bicos para mamadeiras e para chupetas, de silicone;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;40.0;2004000;39269040;Chupetas e bicos para mamadeiras e para chupetas, de silicone;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;40.0;2004000;39249000;Chupetas e bicos para mamadeiras e para chupetas, de silicone;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;41.0;2004100;42021;Malas e maletas de toucador;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;42.0;2004200;48181000;Papel higiênico - folha simples;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;43.0;2004300;48181000;Papel higiênico - folha dupla e tripla;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;44.0;2004400;48182000;Lenços (incluídos os de maquilagem) e toalhas de mão;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;45.0;2004500;48182000;Papel toalha de uso institucional do tipo comercializado em rolos igual ou superior a 80 metros e do tipo comercializado em folhas intercaladas;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;46.0;2004600;48183000;Toalhas e guardanapos de mesa;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;47.0;2004700;48189090;Toalhas de cozinha (papel toalha de uso doméstico);2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;48.0;2004800;96190000;Fraldas, exceto os descritos no CEST 20.048.01;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;48.1;2004801;96190000;Fraldas de fibras têxteis;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;49.0;2004900;96190000;Tampões higiênicos;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;50.0;2005000;96190000;Absorventes higiênicos externos;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;51.0;2005100;56012190;Hastes flexíveis (uso não medicinal);2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;52.0;2005200;56039290;Sutiã descartável, assemelhados e papel para depilação;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;53.0;2005300;82032090;Pinças para sobrancelhas;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;54.0;2005400;82141000;Espátulas (artigos de cutelaria);2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;55.0;2005500;82142000;Utensílios e sortidos de utensílios de manicuros ou de pedicuros (incluídas as limas para unhas);2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;56.0;2005600;90251110;Termômetros, inclusive o digital;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;56.0;2005600;90251990;Termômetros, inclusive o digital;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;57.0;2005700;96032;Escovas e pincéis de barba, escovas para cabelos, para cílios ou para unhas e outras escovas de toucador de pessoas, incluídas as que sejam partes de aparelhos, exceto escovas de dentes;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;58.0;2005800;96032100;Escovas de dentes, incluídas as escovas para dentaduras;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;59.0;2005900;96033000;Pincéis para aplicação de produtos cosméticos;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;60.0;2006000;96050000;Sortidos de viagem, para toucador de pessoas para costura ou para limpeza de calçado ou de roupas;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;61.0;2006100;9615;"Pentes, travessas para cabelo e artigos semelhantes; grampos (alfinetes) para cabelo; pinças (pinceguiches), onduladores, bobes (rolos) e artefatos semelhantes para penteados, e suas partes, exceto os classificados na posição 8516 e suas partes";2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;62.0;2006200;96162000;Borlas ou esponjas para pós ou para aplicação de outros cosméticos ou de produtos de toucador;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;63.0;2006300;40149090;Mamadeiras;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;63.0;2006300;70102000;Mamadeiras;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;63.0;2006300;39249000;Mamadeiras;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;63.0;2006300;39233000;Mamadeiras;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;63.0;2006300;39241000;Mamadeiras;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;64.0;2006400;82122010;Aparelhos e lâminas de barbear;2017-07-01;
20;Produtos de perfumaria e de higiene pessoal e cosméticos;64.0;2006400;82121020;Aparelhos e lâminas de barbear;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;1.0;2100100;73218100;Fogões de cozinha de uso doméstico e suas partes;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;1.0;2100100;73219000;Fogões de cozinha de uso doméstico e suas partes;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;1.0;2100100;73211100;Fogões de cozinha de uso doméstico e suas partes;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;2.0;2100200;84181000;Combinações de refrigeradores e congeladores (freezers), munidos de portas exteriores separadas;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;3.0;2100300;84182100;Refrigeradores do tipo doméstico, de compressão;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;4.0;2100400;84182900;Outros refrigeradores do tipo doméstico;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;5.0;2100500;84183000;Congeladores (freezers) horizontais tipo arca, de capacidade não superior a 800 litros;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;6.0;2100600;84184000;Congeladores (freezers) verticais tipo armário, de capacidade não superior a 900 litros;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;7.0;2100700;841850;Outros móveis (arcas, armários, vitrines, balcões e móveis semelhantes) para a conservação e exposição de produtos, que incorporem um equipamento para a produção de frio;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;8.0;2100800;8418699;Mini adega e similares;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;9.0;2100900;84186999;Máquinas para produção de gelo;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;10.0;2101000;84189900;Partes dos refrigeradores, congeladores, mini adegas e similares, máquinas para produção de gelo e bebedouros descritos nos CEST 21.002.00, 21.003.00, 21.004.00, 21.005.00, 21.006.00, 21.007.00, 21.008.00, 21.009.00 e 21.013.00;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;11.0;2101100;842112;Secadoras de roupa de uso doméstico;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;12.0;2101200;84211990;Outras secadoras de roupas e centrífugas de uso doméstico;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;13.0;2101300;84186931;Bebedouros refrigerados para água;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;14.0;2101400;84219;Partes das secadoras de roupas e centrífugas de uso doméstico e dos aparelhos para filtrar ou depurar água, descritos nos CEST 21.011.00 e 21.012.00 e 21.098.00;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;15.0;2101500;84229010;Máquinas de lavar louça do tipo doméstico e suas partes;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;15.0;2101500;84221100;Máquinas de lavar louça do tipo doméstico e suas partes;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;16.0;2101600;844331;Máquinas que executem pelo menos duas das seguintes funções: impressão, cópia ou transmissão de telecópia (fax), capazes de ser conectadas a uma máquina automática para processamento de dados ou a uma rede;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;17.0;2101700;844332;Outras impressoras, máquinas copiadoras e telecopiadores (fax), mesmo combinados entre si, capazes de ser conectados a uma máquina automática para processamento de dados ou a uma rede;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;18.0;2101800;84439;"Partes e acessórios de máquinas e aparelhos de impressão por meio de blocos, cilindros e outros elementos de impressão da posição 8442; e de outras impressoras, máquinas copiadoras e telecopiadores (fax), mesmo combinados entre si";2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;19.0;2101900;84501100;Máquinas de lavar roupa, mesmo com dispositivos de secagem, de uso doméstico, de capacidade não superior a 10 kg, em peso de roupa seca, inteiramente automáticas;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;20.0;2102000;84501200;Outras máquinas de lavar roupa, mesmo com dispositivos de secagem, de uso doméstico, com secador centrífugo incorporado;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;21.0;2102100;84501900;Outras máquinas de lavar roupa, mesmo com dispositivos de secagem, de uso doméstico;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;22.0;2102200;845020;Máquinas de lavar roupa, mesmo com dispositivos de secagem, de uso doméstico, de capacidade superior a 10 kg, em peso de roupa seca;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;23.0;2102300;845090;Partes de máquinas de lavar roupa, mesmo com dispositivos de secagem, de uso doméstico;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;24.0;2102400;84512100;Máquinas de secar de uso doméstico de capacidade não superior a 10 kg, em peso de roupa seca;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;25.0;2102500;84512990;Outras máquinas de secar de uso doméstico;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;26.0;2102600;845190;Partes de máquinas de secar de uso doméstico;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;27.0;2102700;84521000;Máquinas de costura de uso doméstico;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;28.0;2102800;847130;Máquinas automáticas para processamento de dados, portáteis, de peso não superior a 10 kg, contendo pelo menos uma unidade central de processamento, um teclado e uma tela;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;29.0;2102900;84714;Outras máquinas automáticas para processamento de dados;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;30.0;2103000;84715010;"Unidades de processamento, de pequena capacidade, exceto as das subposições 8471.41 ou 8471.49, podendo conter, no mesmo corpo, um ou dois dos seguintes tipos de unidades: unidade de memória, unidade de entrada e unidade de saída; baseadas em microprocessadores, com capacidade de instalação, dentro do mesmo gabinete, de unidades de memória da subposição 8471.70, podendo conter múltiplos conectores de expansão (slots), e valor FOB inferior ou igual a US$ 12.500,00, por unidade";2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;31.0;2103100;8471605;Unidades de entrada, exceto as classificadas no código 8471.60.54;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;32.0;2103200;84716090;Outras unidades de entrada ou de saída, podendo conter, no mesmo corpo, unidades de memória;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;33.0;2103300;847170;Unidades de memória;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;34.0;2103400;847190;"Outras máquinas automáticas para processamento de dados e suas unidades; leitores magnéticos ou ópticos, máquinas para registrar dados em suporte sob forma codificada, e máquinas para processamento desses dados, não especificadas nem compreendidas em outras posições";2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;35.0;2103500;847330;Partes e acessórios das máquinas da posição 84.71;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;36.0;2103600;85043;Outros transformadores, exceto os classificados nos códigos 8504.33.00 e 8504.34.00;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;37.0;2103700;85044010;Carregadores de acumuladores;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;38.0;2103800;85044040;Equipamentos de alimentação ininterrupta de energia (UPS ou no break);2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;39.0;2103900;85078000;Outros acumuladores;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;40.0;2104000;8508;Aspiradores;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;41.0;2104100;8509;Aparelhos eletromecânicos de motor elétrico incorporado, de uso doméstico e suas partes;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;42.0;2104200;85098010;Enceradeiras;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;43.0;2104300;85161000;Chaleiras elétricas;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;44.0;2104400;85164000;Ferros elétricos de passar;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;45.0;2104500;85165000;Fornos de micro-ondas;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;46.0;2104600;85166000;"Outros fornos; fogareiros (incluídas as chapas de cocção), grelhas e assadeiras, exceto os portáteis";2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;47.0;2104700;85166000;"Outros fornos; fogareiros (incluídas as chapas de cocção), grelhas e assadeiras, portáteis";2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;48.0;2104800;85167100;Outros aparelhos eletrotérmicos de uso doméstico - Cafeteiras;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;49.0;2104900;85167200;Outros aparelhos eletrotérmicos de uso doméstico - Torradeiras;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;50.0;2105000;851679;Outros aparelhos eletrotérmicos de uso doméstico;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;51.0;2105100;85169000;Partes das chaleiras, ferros, fornos e outros aparelhos eletrotérmicos da posição 85.16, descritos nos CEST 21.043.00, 21.044.00, 21.045.00, 21.046.00, 21.047.00, 21.048.00, 21.049.00 e 21.050.00;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;52.0;2105200;85171100;Aparelhos telefônicos por fio com unidade auscultador - microfone sem fio;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;53.0;2105300;8517123;Telefones para redes celulares, exceto por satélite, os de uso automotivo e os classificados no CEST 21.053.01;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;53.1;2105301;85171231;Telefones para redes celulares portáteis, exceto por satélite;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;54.0;2105400;851712;Outros telefones para outras redes sem fio, exceto para redes de celulares e os de uso automotivo;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;55.0;2105500;85171891;Outros aparelhos telefônicos não combinados com outros aparelhos;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;55.1;2105501;85171899;Outros aparelhos telefônicos;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;56.0;2105600;8517625;Aparelhos para transmissão ou recepção de voz, imagem ou outros dados em rede com fio, exceto os classificados nos códigos 8517.62.51, 8517.62.52 e 8517.62.53;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;57.0;2105700;8518;"Microfones e seus suportes; alto-falantes, mesmo montados nos seus receptáculos, fones de ouvido (auscultadores), mesmo combinados com microfone e conjuntos ou sortidos constituídos por um microfone e um ou mais alto-falantes, amplificadores elétricos de audiofrequência, aparelhos elétricos de amplificação de som; suas partes e acessórios; exceto os de uso automotivo";2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;58.0;2105800;8522;"Aparelhos de radiodifusão suscetíveis de funcionarem sem fonte externa de energia. Aparelhos de gravação de som; aparelhos de reprodução de som; aparelhos de gravação e de reprodução de som; partes e acessórios; exceto os de uso automotivo";2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;58.0;2105800;8519;"Aparelhos de radiodifusão suscetíveis de funcionarem sem fonte externa de energia. Aparelhos de gravação de som; aparelhos de reprodução de som; aparelhos de gravação e de reprodução de som; partes e acessórios; exceto os de uso automotivo";2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;58.0;2105800;85271;"Aparelhos de radiodifusão suscetíveis de funcionarem sem fonte externa de energia. Aparelhos de gravação de som; aparelhos de reprodução de som; aparelhos de gravação e de reprodução de som; partes e acessórios; exceto os de uso automotivo";2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;59.0;2105900;85198190;"Outros aparelhos de gravação de som; aparelhos de reprodução de som; aparelhos de gravação e de reprodução de som; partes e acessórios; exceto os de uso automotivo";2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;60.0;2106000;85219010;Gravador-reprodutor e editor de imagem e som, em discos, por meio magnético, óptico ou optomagnético, exceto de uso automotivo;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;61.0;2106100;85219090;Outros aparelhos videofônicos de gravação ou reprodução, mesmo incorporando um receptor de sinais videofônicos, exceto os de uso automotivo;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;62.0;2106200;85235110;Cartões de memória ("memory cards");2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;63.0;2106300;85235200;Cartões inteligentes ("smart cards");2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;64.0;2106400;85235200;Cartões inteligentes ("sim cards");2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;65.0;2106500;8525802;Câmeras fotográficas digitais e câmeras de vídeo e suas partes;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;66.0;2106600;85279;Outros aparelhos receptores para radiodifusão, mesmo combinados num invólucro, com um aparelho de gravação ou de reprodução de som, ou com um relógio, inclusive caixa acústica para Home Theaters classificados na posição 8518;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;67.0;2106700;852869;Monitores e projetores que não incorporem aparelhos receptores de televisão, policromáticos;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;67.0;2106700;85284929;Monitores e projetores que não incorporem aparelhos receptores de televisão, policromáticos;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;67.0;2106700;85285920;Monitores e projetores que não incorporem aparelhos receptores de televisão, policromáticos;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;67.1;2106701;85286200;Projetores capazes de serem conectados diretamente a uma máquina automática para processamento de dados da posição 84.71 e concebidos para serem utilizados com esta máquina;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;68.0;2106800;85285220;Outros monitores capazes de serem conectados diretamente a uma máquina automática para processamento de dados da posição 84.71 e concebidos para serem utilizados com esta máquina, policromáticos;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;69.0;2106900;85287;Aparelhos receptores de televisão, mesmo que incorporem um aparelho receptor de radiodifusão ou um aparelho de gravação ou reprodução de som ou de imagens - Televisores de CRT (tubo de raios catódicos);2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;70.0;2107000;85287;Aparelhos receptores de televisão, mesmo que incorporem um aparelho receptor de radiodifusão ou um aparelho de gravação ou reprodução de som ou de imagens - Televisores de LCD (Display de Cristal Líquido);2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;71.0;2107100;85287;Aparelhos receptores de televisão, mesmo que incorporem um aparelho receptor de radiodifusão ou um aparelho de gravação ou reprodução de som ou de imagens - Televisores de Plasma;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;72.0;2107200;85287;Outros aparelhos receptores de televisão não dotados de monitores ou display de vídeo;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;73.0;2107300;85287;Outros aparelhos receptores de televisão não relacionados nos CEST 21.069.00, 21.070.00, 21.071.00 e 21.072.00;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;74.0;2107400;900659;Câmeras fotográficas dos tipos utilizadas para preparação de clichês ou cilindros de impressão;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;75.0;2107500;90064000;Câmeras fotográficas para filmes de revelação e copiagem instantâneas;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;76.0;2107600;90189050;Aparelhos de diatermia;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;77.0;2107700;90191000;Aparelhos de massagem;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;78.0;2107800;90328911;Reguladores de voltagem eletrônicos;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;79.0;2107900;95045000;Consoles e máquinas de jogos de vídeo, exceto os classificados na subposição 9504.30;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;80.0;2108000;8517621;Multiplexadores e concentradores;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;81.0;2108100;85176222;Centrais automáticas privadas, de capacidade inferior ou igual a 25 ramais;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;82.0;2108200;85176239;Outros aparelhos para comutação;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;83.0;2108300;8517624;Roteadores digitais, em redes com ou sem fio;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;84.0;2108400;85176262;Aparelhos emissores com receptor incorporado de sistema troncalizado (trunking), de tecnologia celular;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;85.0;2108500;8517629;Outros aparelhos de recepção, conversão e transmissão ou regeneração de voz, imagens ou outros dados, incluindo os aparelhos de comutação e roteamento;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;86.0;2108600;85177021;Antenas próprias para telefones celulares portáteis, exceto as telescópicas;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;87.0;2108700;821490;Aparelhos ou máquinas de barbear, máquinas de cortar o cabelo ou de tosquiar e aparelhos de depilar, e suas partes;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;87.0;2108700;8510;Aparelhos ou máquinas de barbear, máquinas de cortar o cabelo ou de tosquiar e aparelhos de depilar, e suas partes;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;88.0;2108800;84145;Ventiladores, exceto os de uso agrícola;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;89.0;2108900;84145990;Ventiladores de uso agrícola;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;90.0;2109000;84146000;Coifas com dimensão horizontal máxima não superior a 120 cm;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;91.0;2109100;84149020;Partes de ventiladores ou coifas aspirantes;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;92.0;2109200;84158;Máquinas e aparelhos de ar condicionado contendo um ventilador motorizado e dispositivos próprios para modificar a temperatura e a umidade, incluídos as máquinas e aparelhos em que a umidade não seja regulável separadamente;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;92.0;2109200;841510;Máquinas e aparelhos de ar condicionado contendo um ventilador motorizado e dispositivos próprios para modificar a temperatura e a umidade, incluídos as máquinas e aparelhos em que a umidade não seja regulável separadamente;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;93.0;2109300;84151011;Aparelhos de ar-condicionado tipo Split System (sistema com elementos separados) com unidade externa e interna;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;94.0;2109400;84151019;Aparelhos de ar-condicionado com capacidade inferior ou igual a 30.000 frigorias/hora;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;95.0;2109500;84151090;Aparelhos de ar-condicionado com capacidade acima de 30.000 frigorias/hora;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;96.0;2109600;84159010;Unidades evaporadoras (internas) de aparelho de ar-condicionado do tipo Split System (sistema com elementos separados), com capacidade inferior ou igual a 30.000 frigorias/hora;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;97.0;2109700;84159020;Unidades condensadoras (externas) de aparelho de ar-condicionado do tipo Split System (sistema com elementos separados), com capacidade inferior ou igual a 30.000 frigorias/hora;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;98.0;2109800;84212100;Aparelhos elétricos para filtrar ou depurar água (purificadores de água refrigerados), exceto os itens classificados no CEST 21.098.01;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;98.1;2109801;84212100;Outros aparelhos elétricos para filtrar ou depurar água;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;99.0;2109900;84243010;Lavadora de alta pressão e suas partes;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;99.0;2109900;84243090;Lavadora de alta pressão e suas partes;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;99.0;2109900;84249090;Lavadora de alta pressão e suas partes;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;100.0;2110000;84672100;Furadeiras elétricas;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;101.0;2110100;85162;Aparelhos elétricos para aquecimento de ambientes;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;102.0;2110200;85163100;Secadores de cabelo;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;103.0;2110300;85163200;Outros aparelhos para arranjos do cabelo;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;104.0;2110400;8527;Aparelhos receptores para radiodifusão, mesmo combinados num mesmo invólucro, com um aparelho de gravação ou de reprodução de som, ou com um relógio, exceto os classificados na posição 8527.1, 8527.2 e 8527.9 que sejam de uso automotivo;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;105.0;2110500;84796000;Climatizadores de ar;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;106.0;2110600;84159090;Outras partes para máquinas e aparelhos de ar-condicionado que contenham um ventilador motorizado e dispositivos próprios para modificar a temperatura e a umidade, incluindo as máquinas e aparelhos em que a umidade não seja regulável separadamente;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;107.0;2110700;85258019;Câmeras de televisão e suas partes;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;108.0;2110800;84231000;Balanças de uso doméstico;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;109.0;2110900;8540;Tubos e válvulas, eletrônicos, de cátodo quente, cátodo frio ou fotocátodo (por exemplo, tubos e válvulas, de vácuo, de vapor ou de gás, ampolas retificadoras de vapor de mercúrio, tubos catódicos, tubos e válvulas para câmeras de televisão);2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;110.0;2111000;8517;"Aparelhos elétricos para telefonia; outros aparelhos para transmissão ou recepção de voz, imagens ou outros dados, incluídos os aparelhos para comunicação em redes por fio ou redes sem fio (tal como uma rede local (LAN) ou uma rede de área estendida (WAN), incluídas suas partes, exceto os de uso automotivo e os classificados nos códigos 8517.62.51, 8517.62.52 e 8517.62.53";2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;111.0;2111100;8517;Interfones, seus acessórios, tomadas e plugs;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;112.0;2111200;8529;"Partes reconhecíveis como exclusiva ou principalmente destinadas aos aparelhos das posições 8525 a 8528; exceto as de uso automotivo";2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;113.0;2111300;8531;"Aparelhos elétricos de sinalização acústica ou visual (por exemplo, campainhas, sirenes, quadros indicadores, aparelhos de alarme para proteção contra roubo ou incêndio); exceto os de uso automotivo e os classificados nas posições 8531.10 e 8531.80.00.";2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;114.0;2111400;853110;Aparelhos elétricos de alarme, para proteção contra roubo ou incêndio e aparelhos semelhantes, exceto os de uso automotivo;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;115.0;2111500;85318000;Outros aparelhos de sinalização acústica ou visual, exceto os de uso automotivo;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;116.0;2111600;853400;Circuitos impressos, exceto os de uso automotivo;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;117.0;2111700;85414022;Diodos emissores de luz (LED), exceto diodos laser;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;117.0;2111700;85414021;Diodos emissores de luz (LED), exceto diodos laser;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;117.0;2111700;85414011;Diodos emissores de luz (LED), exceto diodos laser;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;118.0;2111800;85437092;Eletrificadores de cercas eletrônicos;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;119.0;2111900;90303;"Aparelhos e instrumentos para medida ou controle da tensão, intensidade, resistência ou da potência, sem dispositivo registrador; exceto os de uso automotivo";2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;120.0;2112000;903089;Analisadores lógicos de circuitos digitais, de espectro de frequência, frequencímetros, fasímetros, e outros instrumentos e aparelhos de controle de grandezas elétricas e detecção;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;121.0;2112100;910700;Interruptores horários e outros aparelhos que permitam acionar um mecanismo em tempo determinado, munidos de maquinismo de aparelhos de relojoaria ou de motor síncrono;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;122.0;2112200;9405;"Aparelhos de iluminação (incluídos os projetores) e suas partes, não especificados nem compreendidos em outras posições; anúncios, cartazes ou tabuletas e placas indicadoras luminosos, e artigos semelhantes, contendo uma fonte luminosa fixa permanente, e suas partes não especificadas nem compreendidas em outras posições, com exceção dos itens classificados nos CEST 21.123.00, 21.124.00 e 21.125.00";2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;123.0;2112300;94059;"Lustres e outros aparelhos elétricos de iluminação, próprios para serem suspensos ou fixados no teto ou na parede, exceto os dos tipos utilizados na iluminação pública; e suas partes";2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;123.0;2112300;940510;"Lustres e outros aparelhos elétricos de iluminação, próprios para serem suspensos ou fixados no teto ou na parede, exceto os dos tipos utilizados na iluminação pública; e suas partes";2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;124.0;2112400;94059;Abajures de cabeceiras, de escritório e lampadários de interior, elétricos e suas partes;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;124.0;2112400;94052000;Abajures de cabeceiras, de escritório e lampadários de interior, elétricos e suas partes;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;125.0;2112500;940540;Outros aparelhos elétricos de iluminação e suas partes;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;125.0;2112500;94059;Outros aparelhos elétricos de iluminação e suas partes;2017-07-01;
21;Produtos eletrônicos, eletroeletrônicos e eletrodomésticos;126.0;2112600;85423190;Microprocessador;2017-07-01;
22;Rações para animais domésticos;1.0;2200100;2309;Ração tipo pet para animais domésticos;2017-07-01;
23;Sorvetes e preparados para fabricação de sorvetes em máquinas;1.0;2300100;210500;Sorvetes de qualquer espécie;2017-07-01;
23;Sorvetes e preparados para fabricação de sorvetes em máquinas;2.0;2300200;2106;Preparados para fabricação de sorvete em máquina;2017-07-01;
23;Sorvetes e preparados para fabricação de sorvetes em máquinas;2.0;2300200;1901;Preparados para fabricação de sorvete em máquina;2017-07-01;
23;Sorvetes e preparados para fabricação de sorvetes em máquinas;2.0;2300200;1806;Preparados para fabricação de sorvete em máquina;2017-07-01;
24;Tintas e vernizes;1.0;2400100;321000;Tintas, vernizes;2017-07-01;
24;Tintas e vernizes;1.0;2400100;3209;Tintas, vernizes;2017-07-01;
24;Tintas e vernizes;1.0;2400100;3208;Tintas, vernizes;2017-07-01;
24;Tintas e vernizes;2.0;2400200;2821;Xadrez e pós assemelhados, exceto pigmentos à base de dióxido de titânio classificados no código 3206.11.19;2017-07-01;
24;Tintas e vernizes;2.0;2400200;32041700;Xadrez e pós assemelhados, exceto pigmentos à base de dióxido de titânio classificados no código 3206.11.19;2017-07-01;
24;Tintas e vernizes;2.0;2400200;3206;Xadrez e pós assemelhados, exceto pigmentos à base de dióxido de titânio classificados no código 3206.11.19;2017-07-01;
24;Tintas e vernizes;3.0;2400300;3212;Corantes para aplicação em bases, tintas e vernizes;2017-07-01;
24;Tintas e vernizes;3.0;2400300;3206;Corantes para aplicação em bases, tintas e vernizes;2017-07-01;
24;Tintas e vernizes;3.0;2400300;32050000;Corantes para aplicação em bases, tintas e vernizes;2017-07-01;
24;Tintas e vernizes;3.0;2400300;3204;Corantes para aplicação em bases, tintas e vernizes;2017-07-01;
25;Veículos automotores;1.0;2500100;87021000;Veículos automóveis para transporte de 10 pessoas ou mais, incluindo o motorista, unicamente com motor de pistão, de ignição por compressão (diesel ou semidiesel), com volume interno de habitáculo, destinado a passageiros e motorista, superior a 6 m³, mas inferior a 9 m³;2017-07-01;
25;Veículos automotores;2.0;2500200;87024090;Veículos automóveis para transporte de 10 pessoas ou mais, incluindo o motorista, unicamente com motor elétrico para propulsão, com volume interno de habitáculo, destinado a passageiros e motorista, superior a 6 m³, mas inferior a 9 m³;2017-07-01;
25;Veículos automotores;3.0;2500300;87032100;Automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada não superior a 1000 cm³;2017-07-01;
25;Veículos automotores;4.0;2500400;87032210;Automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada superior a 1000 cm³, mas não superior a 1500 cm³, com capacidade de transporte de pessoas sentadas inferior ou igual a 6, incluído o condutor, exceto carro celular;2017-07-01;
25;Veículos automotores;5.0;2500500;87032290;Outros automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada superior a 1000 cm³, mas não superior a 1500 cm³, exceto carro celular;2017-07-01;
25;Veículos automotores;6.0;2500600;87032310;Automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada superior a 1500 cm³, mas não superior a 3000 cm³, com capacidade de transporte de pessoas sentadas inferior ou igual a 6, incluído o condutor, exceto carro celular, carro funerário e automóveis de corrida;2017-07-01;
25;Veículos automotores;7.0;2500700;87032390;Outros automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada superior a 1500 cm³, mas não superior a 3000 cm³, exceto carro celular, carro funerário e automóveis de corrida;2017-07-01;
25;Veículos automotores;8.0;2500800;87032410;Automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada superior a 3000 cm³, com capacidade de transporte de pessoas sentadas inferior ou igual a 6, incluído o condutor, exceto carro celular, carro funerário e automóveis de corrida;2017-07-01;
25;Veículos automotores;9.0;2500900;87032490;Outros automóveis unicamente com motor de pistão alternativo de ignição por centelha (faísca*), de cilindrada superior a 3000 cm³, exceto carro celular, carro funerário e automóveis de corrida;2017-07-01;
25;Veículos automotores;10.0;2501000;87033210;Automóveis unicamente com motor diesel ou semidiesel, de cilindrada superior a 1500 cm³, mas não superior a 2500 cm³, com capacidade de transporte de pessoas sentadas inferior ou igual a 6, incluído o condutor, exceto ambulância, carro celular e carro funerário;2017-07-01;
25;Veículos automotores;11.0;2501100;87033290;Outros automóveis unicamente com motor diesel ou semidiesel, de cilindrada superior a 1500 cm³, mas não superior a 2500 cm³, exceto ambulância, carro celular e carro funerário;2017-07-01;
25;Veículos automotores;12.0;2501200;87033310;Automóveis unicamente com motor diesel ou semidiesel, de cilindrada superior a 2500 cm³, com capacidade de transporte de pessoas sentadas inferior ou igual a 6, incluído o condutor, exceto carro celular e carro funerário;2017-07-01;
25;Veículos automotores;13.0;2501300;87033390;Outros automóveis unicamente com motor diesel ou semidiesel, de cilindrada superior a 2500 cm³, exceto carro celular e carro funerário;2017-07-01;
25;Veículos automotores;14.0;2501400;87042110;Veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, chassis com motor diesel ou semidiesel e cabina, exceto caminhão de peso em carga máxima superior a 3,9 toneladas;2017-07-01;
25;Veículos automotores;15.0;2501500;87042120;Veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, com motor diesel ou semidiesel, com caixa basculante, exceto caminhão de peso em carga máxima superior a 3,9 toneladas;2017-07-01;
25;Veículos automotores;16.0;2501600;87042130;Veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, frigoríficos ou isotérmicos, com motor diesel ou semidiesel, exceto caminhão de peso em carga máxima superior a 3,9 toneladas;2017-07-01;
25;Veículos automotores;17.0;2501700;87042190;Outros veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, com motor diesel ou semidiesel, exceto carro-forte para transporte de valores e caminhão de peso em carga máxima superior a 3,9 toneladas;2017-07-01;
25;Veículos automotores;18.0;2501800;87043110;Veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, com motor a explosão, chassis e cabina, exceto caminhão de peso em carga máxima superior a 3,9 toneladas;2017-07-01;
25;Veículos automotores;19.0;2501900;87043120;Veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, com motor explosão com caixa basculante, exceto caminhão de peso em carga máxima superior a 3,9 toneladas;2017-07-01;
25;Veículos automotores;20.0;2502000;87043130;Veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, frigoríficos ou isotérmicos com motor explosão, exceto caminhão de peso em carga máxima superior a 3,9 toneladas;2017-07-01;
25;Veículos automotores;21.0;2502100;87043190;Outros veículos automóveis para transporte de mercadorias, de peso em carga máxima não superior a 5 toneladas, com motor a explosão, exceto carro-forte para transporte de valores e caminhão de peso em carga máxima superior a 3,9 toneladas;2017-07-01;
25;Veículos automotores;22.0;2502200;87022000;Veículos automóveis para transporte de 10 pessoas ou mais, incluindo o motorista, com motor de pistão, de ignição por compressão (diesel ou semidiesel) e um motor elétrico, com volume interno de habitáculo, destinado a passageiros e motorista, superior a 6 m³, mas inferior a 9 m³;2017-07-01;
25;Veículos automotores;23.0;2502300;87023000;Veículos automóveis para transporte de 10 pessoas ou mais, incluindo o motorista, com motor de pistão alternativo, de ignição por centelha (faísca) e um motor elétrico, com volume interno de habitáculo, destinado a passageiros e motorista, superior a 6 m³, mas inferior a 9 m³;2017-07-01;
25;Veículos automotores;24.0;2502400;87029000;Outros veículos automóveis para transporte de 10 pessoas ou mais, incluindo o motorista, com volume interno de habitáculo, destinado a passageiros e motorista, superior a 6 m³, mas inferior a 9 m³;2017-07-01;
25;Veículos automotores;25.0;2502500;87034000;Automóveis equipados para propulsão, simultaneamente, com um motor de pistão alternativo de ignição por centelha (faísca*) e um motor elétrico, exceto os suscetíveis de serem carregados por conexão a uma fonte externa de energia elétrica, o carro celular e o carro funerário;2017-07-01;
25;Veículos automotores;26.0;2502600;87035000;Automóveis equipados para propulsão, simultaneamente, com um motor de pistão por compressão (diesel ou semidiesel) e um motor elétrico, exceto os suscetíveis de serem carregados por conexão a uma fonte externa de energia elétrica, exceto o carro celular e o carro funerário;2017-07-01;
25;Veículos automotores;27.0;2502700;87036000;Automóveis equipados para propulsão, simultaneamente, com um motor de pistão alternativo de ignição por centelha (faísca*) e um motor elétrico, suscetíveis de serem carregados por conexão a uma fonte externa de energia elétrica, exceto o carro celular e o carro funerário;2017-07-01;
25;Veículos automotores;28.0;2502800;87037000;Automóveis equipados para propulsão, simultaneamente, com um motor de pistão por compressão (diesel ou semidiesel) e um motor elétrico, suscetíveis de serem carregados por conexão a uma fonte externa de energia elétrica, exceto o carro celular e o carro funerário;2017-07-01;
25;Veículos automotores;29.0;2502900;87038000;Outros veículos, equipados unicamente com motor elétrico para propulsão;2017-07-01;
26;Veículos de duas e três rodas motorizados;1.0;2600100;8711;"Motocicletas (incluídos os ciclomotores) e outros ciclos equipados com motor auxiliar, mesmo com carro lateral; carros laterais";2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;1.0;2800100;33030010;Perfumes (extratos);2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;2.0;2800200;33030020;Águas-de-colônia;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;3.0;2800300;33041000;Produtos de maquiagem para os lábios;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;4.0;2800400;33042010;Sombra, delineador, lápis para sobrancelhas e rímel;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;5.0;2800500;33042090;Outros produtos de maquiagem para os olhos;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;6.0;2800600;33043000;Preparações para manicuros e pedicuros;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;7.0;2800700;33049100;Pós para maquiagem, incluindo os compactos;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;8.0;2800800;33049910;Cremes de beleza, cremes nutritivos e loções tônicas;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;9.0;2800900;33049990;Outros produtos de beleza ou de maquiagem preparados e preparações para conservação ou cuidados da pele, exceto as preparações antissolares e os bronzeadores;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;10.0;2801000;33049990;Preparações antissolares e os bronzeadores;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;11.0;2801100;33051000;Xampus para o cabelo;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;12.0;2801200;33052000;Preparações para ondulação ou alisamento, permanentes, dos cabelos;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;13.0;2801300;33059000;Outras preparações capilares;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;14.0;2801400;33059000;Tintura para o cabelo;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;15.0;2801500;33071000;Preparações para barbear (antes, durante ou após);2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;16.0;2801600;33072010;Desodorantes corporais e antiperspirantes, líquidos;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;17.0;2801700;33072090;Outros desodorantes corporais e antiperspirantes;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;18.0;2801800;33079000;Outros produtos de perfumaria ou de toucador preparados;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;19.0;2801900;33079000;Outras preparações cosméticas;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;20.0;2802000;34011190;Sabões de toucador, em barras, pedaços ou figuras moldadas;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;21.0;2802100;34011900;Outros sabões, produtos e preparações orgânicos tensoativos, inclusive papel, pastas (ouates), feltros e falsos tecidos, impregnados, revestidos ou recobertos de sabão ou de detergentes;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;22.0;2802200;34012010;Sabões de toucador sob outras formas;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;23.0;2802300;34013000;Produtos e preparações orgânicos tensoativos para lavagem da pele, em forma de líquido ou de creme, acondicionados para venda a retalho, mesmo contendo sabão;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;24.0;2802400;48182000;Lenços de papel, incluindo os de desmaquiar;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;24.1;2802401;48182000;Toalhas de mão;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;25.0;2802500;82141000;Apontadores de lápis para maquiagem;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;25.1;2802501;82141000;Espátulas, abre-cartas e raspadeiras;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;25.2;2802502;82141000;Lâminas de espátulas, de abre-cartas, de raspadeiras e de apontadores de lápis;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;26.0;2802600;82142000;Utensílios e sortidos de utensílios de manicuros ou de pedicuros (incluindo as limas para unhas);2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;27.0;2802700;96032900;Escovas e pincéis de barba, escovas para cabelos, para cílios ou para unhas e outras escovas de toucador de pessoas;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;27.1;2802701;96032900;"Vassouras e escovas, mesmo constituindo partes de máquinas, de aparelhos ou de veículos, vassouras mecânicas de uso manual não motorizadas, pincéis e espanadores; cabeças preparadas para escovas, pincéis e artigos semelhantes; bonecas e rolos para pintura; rodos de borracha ou de matérias flexíveis semelhantes, outros";2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;28.0;2802800;96033000;Pincéis para aplicação de produtos cosméticos;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;28.1;2802801;96033000;Pincéis e escovas, para artistas e pincéis de escrever;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;29.0;2802900;96161000;Vaporizadores de toucador, suas armações e cabeças de armações;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;30.0;2803000;96162000;Borlas ou esponjas para pós ou para aplicação de outros cosméticos ou de produtos de toucador;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;31.0;2803100;42021;Malas e maletas de toucador;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;32.0;2803200;9615;"Pentes, travessas para cabelo e artigos semelhantes; grampos (alfinetes) para cabelo; pinças (pinceguiches), onduladores, bobs (rolos) e artefatos semelhantes para penteados, e suas partes";2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;33.0;2803300;40149090;Mamadeiras;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;33.0;2803300;70102000;Mamadeiras;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;33.0;2803300;39233000;Mamadeiras;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;33.0;2803300;39241000;Mamadeiras;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;33.0;2803300;39249000;Mamadeiras;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;34.0;2803400;40149090;Chupetas e bicos para mamadeiras e para chupetas;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;35.0;2803500;12119090;Outras plantas e partes, para perfumaria, medicina e semelhantes;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;36.0;2803600;39262000;Vestuário e seus acessórios, de plásticos, inclusive luvas;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;37.0;2803700;39264000;Estatuetas e outros objetos de ornamentação, de plásticos;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;38.0;2803800;39269090;Outras obras de plásticos;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;39.0;2803900;42022210;Bolsas de folhas de plástico;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;40.0;2804000;42022220;Bolsas de matérias têxteis;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;41.0;2804100;42022900;Bolsas de outras matérias;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;42.0;2804200;42023900;Artigos de bolsos/bolsas, de outras matérias;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;43.0;2804300;42029200;Outros artefatos, de folhas de plásticos ou matérias têxteis;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;44.0;2804400;42029900;Outros artefatos, de outras matérias;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;45.0;2804500;48192000;Caixas e cartonagens, dobráveis, de papel/cartão, não ondulados;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;46.0;2804600;48194000;Outros sacos, bolsas e cartuchos, de papel ou cartão;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;47.0;2804700;48211000;Etiquetas de papel ou cartão, impressas;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;48.0;2804800;49111090;Outros impressos publicitários, catálogos comerciais e semelhantes;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;49.0;2804900;61159900;Outras meias de malha de outras matérias têxteis;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;50.0;2805000;62171000;Outros acessórios confeccionados, de vestuário;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;51.0;2805100;63026000;Roupas de toucador/cozinha, de tecidos atoalhados de algodão;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;52.0;2805200;63079090;Outros artefatos têxteis confeccionados;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;53.0;2805300;65069900;Chapéus e outros artefatos de outras matérias, exceto de malha;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;54.0;2805400;95059000;Artigos para outras festas, carnaval ou outros divertimentos;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;55.0;2805500;33;Produtos destinados à higiene bucal;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;56.0;2805600;34;Outros produtos cosméticos e de higiene pessoal não relacionados em outros itens deste anexo;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;56.0;2805600;33;Outros produtos cosméticos e de higiene pessoal não relacionados em outros itens deste anexo;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;57.0;2805700;14;Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;57.0;2805700;39;Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;57.0;2805700;40;Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;57.0;2805700;44;Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;57.0;2805700;48;Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;57.0;2805700;63;Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;57.0;2805700;65;Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;57.0;2805700;67;Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;57.0;2805700;70;Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;57.0;2805700;82;Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;57.0;2805700;90;Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;57.0;2805700;96;Outros artigos destinados a cuidados pessoais não relacionados em outros itens deste anexo;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;58.0;2805800;39;Acessórios (por exemplo, bijuterias, relógios, óculos de sol, bolsas, mochilas, frasqueiras, carteiras, porta-cartões, porta-documentos, porta-celulares e embalagens presenteáveis (por exemplo, caixinhas de papel), entre outros itens assemelhados);2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;58.0;2805800;91;Acessórios (por exemplo, bijuterias, relógios, óculos de sol, bolsas, mochilas, frasqueiras, carteiras, porta-cartões, porta-documentos, porta-celulares e embalagens presenteáveis (por exemplo, caixinhas de papel), entre outros itens assemelhados);2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;58.0;2805800;90;Acessórios (por exemplo, bijuterias, relógios, óculos de sol, bolsas, mochilas, frasqueiras, carteiras, porta-cartões, porta-documentos, porta-celulares e embalagens presenteáveis (por exemplo, caixinhas de papel), entre outros itens assemelhados);2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;58.0;2805800;48;Acessórios (por exemplo, bijuterias, relógios, óculos de sol, bolsas, mochilas, frasqueiras, carteiras, porta-cartões, porta-documentos, porta-celulares e embalagens presenteáveis (por exemplo, caixinhas de papel), entre outros itens assemelhados);2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;58.0;2805800;42;Acessórios (por exemplo, bijuterias, relógios, óculos de sol, bolsas, mochilas, frasqueiras, carteiras, porta-cartões, porta-documentos, porta-celulares e embalagens presenteáveis (por exemplo, caixinhas de papel), entre outros itens assemelhados);2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;59.0;2805900;62;"Vestuário e seus acessórios; calçados, polainas e artefatos semelhantes, e suas partes";2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;59.0;2805900;64;"Vestuário e seus acessórios; calçados, polainas e artefatos semelhantes, e suas partes";2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;59.0;2805900;61;"Vestuário e seus acessórios; calçados, polainas e artefatos semelhantes, e suas partes";2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;60.0;2806000;58;Outros artigos de vestuário em geral, exceto os relacionados no item anterior;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;60.0;2806000;63;Outros artigos de vestuário em geral, exceto os relacionados no item anterior;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;60.0;2806000;65;Outros artigos de vestuário em geral, exceto os relacionados no item anterior;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;60.0;2806000;52;Outros artigos de vestuário em geral, exceto os relacionados no item anterior;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;60.0;2806000;42;Outros artigos de vestuário em geral, exceto os relacionados no item anterior;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;60.0;2806000;55;Outros artigos de vestuário em geral, exceto os relacionados no item anterior;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;61.0;2806100;56;Artigos de casa;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;61.0;2806100;62;Artigos de casa;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;61.0;2806100;63;Artigos de casa;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;61.0;2806100;66;Artigos de casa;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;61.0;2806100;69;Artigos de casa;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;61.0;2806100;70;Artigos de casa;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;61.0;2806100;73;Artigos de casa;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;61.0;2806100;76;Artigos de casa;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;61.0;2806100;82;Artigos de casa;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;61.0;2806100;83;Artigos de casa;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;61.0;2806100;84;Artigos de casa;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;61.0;2806100;91;Artigos de casa;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;61.0;2806100;94;Artigos de casa;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;61.0;2806100;96;Artigos de casa;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;61.0;2806100;39;Artigos de casa;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;61.0;2806100;40;Artigos de casa;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;61.0;2806100;52;Artigos de casa;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;62.0;2806200;17;Produtos das indústrias alimentares e bebidas;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;62.0;2806200;13;Produtos das indústrias alimentares e bebidas;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;62.0;2806200;15;Produtos das indústrias alimentares e bebidas;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;62.0;2806200;23;Produtos das indústrias alimentares e bebidas;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;62.0;2806200;16;Produtos das indústrias alimentares e bebidas;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;62.0;2806200;18;Produtos das indústrias alimentares e bebidas;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;62.0;2806200;19;Produtos das indústrias alimentares e bebidas;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;62.0;2806200;20;Produtos das indústrias alimentares e bebidas;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;62.0;2806200;21;Produtos das indústrias alimentares e bebidas;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;62.0;2806200;22;Produtos das indústrias alimentares e bebidas;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;63.0;2806300;63;Produtos de limpeza e conservação doméstica;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;63.0;2806300;73;Produtos de limpeza e conservação doméstica;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;63.0;2806300;84;Produtos de limpeza e conservação doméstica;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;63.0;2806300;85;Produtos de limpeza e conservação doméstica;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;63.0;2806300;96;Produtos de limpeza e conservação doméstica;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;63.0;2806300;34;Produtos de limpeza e conservação doméstica;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;63.0;2806300;35;Produtos de limpeza e conservação doméstica;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;63.0;2806300;38;Produtos de limpeza e conservação doméstica;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;63.0;2806300;39;Produtos de limpeza e conservação doméstica;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;63.0;2806300;68;Produtos de limpeza e conservação doméstica;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;63.0;2806300;29;Produtos de limpeza e conservação doméstica;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;63.0;2806300;27;Produtos de limpeza e conservação doméstica;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;63.0;2806300;28;Produtos de limpeza e conservação doméstica;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;63.0;2806300;22;Produtos de limpeza e conservação doméstica;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;63.0;2806300;33;Produtos de limpeza e conservação doméstica;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;64.0;2806400;39;Artigos infantis;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;64.0;2806400;49;Artigos infantis;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;64.0;2806400;95;Artigos infantis;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;64.0;2806400;96;Artigos infantis;2017-07-01;
28;Venda de mercadorias pelo sistema porta a porta;999.0;2899900;NT;Outros produtos comercializados pelo sistema de marketing direto porta-a-porta a consumidor final não relacionados em outros itens deste anexo;2017-07-01;
```

***
