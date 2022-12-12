---
title: Intel·ligència artificial per millorar la localització d'objectes a
  l'interior d'entorns industrials
language: ca
destacat: false
date: 2022-12-12T07:58:08.834Z
general:
  img: https://www.uoc.edu/portal/_resources/common/imatges/sala_de_premsa/noticies/2022/278-localitzacio-interiors.jpg_914553990.jpg
  titol: Intel·ligència artificial per millorar la localització d'objectes a
    l'interior d'entorns industrials
descripcio:
  entrada: Un nou projecte amb la UOC farà servir algoritmes d'aprenentatge
    profund per augmentar la precisió i les prestacions d'aquesta tecnologia
  text: >-
    <!--StartFragment-->


    Les tecnologies de posicionament d'interiors són un dels motors clau de la transformació digital del sector industrial. La capacitat de rastrejar objectes, actius i persones de manera precisa i barata podria estalviar recursos, temps i diners a les empreses de diferents sectors, des del logístic fins al sanitari. El catedràtic dels [Estudis d'Informàtica, Multimèdia i Telecomunicació](https://www.uoc.edu/portal/ca/estudis_arees/informatica_multimedia_telecomunicacio/index.html) i líder del grup Wireless Networks (**[WiNE](http://transfer.rdi.uoc.edu/ca/grup/UOC-WINE-wireless-networks)**), de l'Internet Interdisciplinary Institute (**[IN3](https://www.uoc.edu/portal/ca/in3/index.html)**) de la UOC, **[Xavier Vilajosana](http://transfer.rdi.uoc.edu/ca/investigador/vilajosana-guilln-xavier)** coordina la participació de la Universitat en un nou projecte europeu que desenvolupa **solucions innovadores per millorar la localització en interiors**. **DUNE** fa servir tècniques d'aprenentatge profund (*[deep learning](https://blogs.uoc.edu/informatica/machine-learning-vs-deep-learning-diferencias/)*) combinades amb sistemes de computació distribuïts, que aprofiten tant el **núvol** com **l'*edge*** (extrem); és a dir, arquitectures de computació que tenen lloc tant en servidors llunyans com a prop d'on es generen les dades. L'objectiu és aconseguir un sistema versàtil que permeti aprofitar les diferents tecnologies existents i que s'adapti als diferents casos d'ús potencials. 


    "En l'actualitat hi ha nombrosos enfocaments tecnològics que tracten d'explotar les característiques dels senyals de ràdio com a eina per derivar la posició relativa entre objectes. Aquesta heterogeneïtat tecnològica i la varietat de casos en què es poden fer servir, amb gran diversitat de pressupostos i entorns d'aplicació, fan necessari desenvolupar un **marc potent per gestionar les dades d'ubicació de diferents tecnologies en temps real**, que al mateix temps s'adapti a les múltiples necessitats industrials i que sigui econòmicament atractiu", explica Xavier Vilajosana. 


     


    ### **Posicionament assistit per tècniques d'aprenentatge profund**


    La localització d'actius en interiors tracta de deduir, des del punt de vista del dispositiu receptor, **de quina direcció prové el senyal emès pels objectes i després traduir aquesta informació en una estimació de la posició**. Un dels reptes principals d'aquesta tecnologia és el gran marge d'error causat pels obstacles entre el transmissor i el receptor del senyal, especialment en entorns industrials, així com la propagació multicamí, és a dir, el fenomen que fa que els senyals arribin a les antenes receptores per dos camins o més i en diferents moments.


    Per aquest motiu, és imprescindible el processament del senyal, ja que, en cas contrari, sorgeixen ambigüitats i els errors es propaguen a la posició dels objectes. Davant aquest repte, DUNE **incorpora mecanismes de posicionament assistits per tècniques d'aprenentatge profund en diferents etapes del procés de localització** amb l'objectiu d'oferir un rendiment òptim. L'aprenentatge profund és una classe d'algoritmes d'aprenentatge automàtic, és a dir, que es poden entrenar perquè aprenguin a partir de les dades introduïdes i després aprofitin aquest coneixement per extreure conclusions amb informació nova. "El processament de les dades es farà mitjançant diferents enfocaments, com ara mètodes d'aprenentatge profund entrenats per seleccionar les estimacions de posició que localitzin millor els objectes en seguiment", explica l'investigador. 


     


    ### **Estratègia de computació distribuïda**


    El projecte també aprofitarà **diferents arquitectures de computació**, **des del núvol fins a l'*edge* i el *far edge***. O sigui, en comptes d'una estratègia centralitzada, la computació es distribuirà en diferents nodes, més propers al lloc de la generació de dades, de manera que es redueixen els processos informàtics en núvol **i es disminueix el temps de resposta dels servidors i l'amplada de banda, a fi d’augmentar al mateix temps la seguretat de les dades.**


    El sistema està completament distribuït i compost per **diferents sensors o tecnologies de localització situades als objectes que es volen localitzar**. Aquests dispositius generen traces de dades en brut que s'han de processar per obtenir les posicions individuals estimades; un primer processament de dades tindrà lloc a l'anomenat *far edge*, és a dir, a prop de les antenes que transmeten els senyals. 


     


    ### **Actualització de dades en temps real**


    Els senyals de ràdio dels sensors connectats als objectes o persones que s'han de seguir es reben per la matriu d'antenes del localitzador. Aquestes **dades s'han de transformar per estimar els angles que defineixen la direcció del senyal i permetre una actualització en temps real**. "En un món perfecte, aquesta transformació és un procés geomètric que depèn de l'espai entre antenes (distància) i de la radiofreqüència (longitud d'ona). Tanmateix, aquests entorns estan subjectes a sorolls i irregularitats", destaca Xavier Vilajosana.


    "Quan es tracten aquests problemes —continua—, els mètodes d'aprenentatge profund poden esdevenir una **eina molta valuosa per obtenir estimacions precises de la posició dels objectes**."


    Per millorar el rendiment del sistema, el processament i l'agregació de dades en temps real es farà des d'uns altres dispositius anomenats *edge*. Aquí s'introduirà un pas de filtratge posterior per millorar la traducció del senyal i **poder incorporar diferents tecnologies**, fent servir també mètodes d'aprenentatge profund, entre d'altres. 


     


    ### **Infraestructura també en núvol** 


    Des d'aquests dispositius *edge* es lliuraran les posicions estimades en temps real a una infraestructura en núvol, connectada als sistemes d'informació de la fàbrica o del magatzem logístic on es treballi. En núvol, els mètodes avançats d'intel·ligència artificial es poden utilitzar per **corregir, millorar, classificar, detectar anomalies o optimitzar les operacions**. 


    Aquesta infraestructura en núvol s'encarregarà de la visualització i el seguiment dels objectes, així com de **connectar i interrelacionar aquesta informació amb altres subsistemes com ara els d'inventari** de la fàbrica o magatzem.


     


    ### **Banc de proves a gran escala**


    Aquesta proposta tecnològica s'avaluarà al llarg del projecte, que tindrà una durada de dotze mesos, en diferents escenaris, i **es compararan els resultats amb altres solucions tecnològiques actuals**. En primer lloc, es faran tests en el mateix [laboratori del grup de recerca](https://www.uoc.edu/portal/ca/news/actualitat/2022/269-inauguracio-hub-recerca-UOC.html) i, posteriorment, es faran proves a gran escala en un **edifici especialment dissenyat per a aquest tipus d'experiments** que cobreix 1.000 m2 i que permet avaluar diferents tecnologies.




    <!--EndFragment-->
---
