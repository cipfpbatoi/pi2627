# Exemple orientatiu del Bloc 2

!!! info "Cas fictici per entendre el procés"

    Totes les dades i evidències d'esta pàgina són inventades amb finalitat didàctica. No les podeu presentar com a investigació pròpia ni heu de copiar la proposta. Useu l'exemple per entendre **com es passa d'una necessitat a una decisió justificada** i apliqueu el mateix raonament al vostre context.

## 1. Situació inicial: material compartit en una associació cultural

Una associació cultural presta equips de so, focus, taules i altres materials als grups que organitzen activitats. Les peticions arriben per missatges i després una persona intenta actualitzar un full de càlcul. De vegades falten dates, no es registra una devolució o dos grups creuen que tenen reservat el mateix material.

La necessitat no es formularia com «falta una aplicació». Una formulació més útil seria:

> Les persones que organitzen activitats i la persona responsable del magatzem necessiten conéixer la disponibilitat i l'estat de cada material perquè les peticions incompletes i els solapaments generen temps perdut i canvis d'última hora.

Esta formulació permet investigar el problema encara que la millor resposta final no siga construir una aplicació nova.

## 2. Evidències i limitacions

L'equip fictici registra estes evidències inicials:

| Afirmació | Evidència fictícia | Classificació | Limitació |
| --- | --- | --- | --- |
| Les peticions arriben incompletes | En 6 de 18 peticions d'un mes faltava la data de devolució o la quantitat | Confirmada en la mostra | Només s'ha revisat un mes |
| Es produïxen solapaments | S'han localitzat 3 peticions incompatibles sobre el mateix material | Confirmada en la mostra | No se sap si és habitual en altres períodes |
| Consultar la disponibilitat lleva massa temps | Dos organitzadors indiquen que han d'esperar una resposta per missatge | Probable | Només s'han consultat dos organitzadors |
| Totes les persones preferixen fer la petició des del mòbil | Encara no hi ha evidència | Suposada | Cal preguntar-ho i observar els dispositius disponibles |

Una conclusió adequada seria: «Hi ha indicis suficients per explorar el problema, però encara no podem generalitzar la freqüència ni afirmar quina interfície preferixen totes les persones usuàries».

## 3. Parts interessades

| Part interessada | Necessitat o interés | Com podria participar en la validació? |
| --- | --- | --- |
| Responsable del magatzem | Evitar solapaments i saber què està pendent de devolució | Revisar el recorregut d'aprovació i provar casos amb conflictes |
| Organitzadors i organitzadores | Consultar disponibilitat i fer una petició completa | Fer tasques amb el prototip i explicar dubtes o passos innecessaris |
| Junta de l'associació | Controlar l'accés, els costos i les responsabilitats | Validar rols, condicions i abast |

No cal recopilar converses privades ni dades personals reals. Es poden usar noms ficticis i casos controlats.

## 4. Tres alternatives diferents

| Alternativa | Resposta proposada | Valor esperat | Prototip per validar-la | Risc o cost principal |
| --- | --- | --- | --- | --- |
| **A. Gestió integral pròpia** | Aplicació web amb inventari, calendari, peticions, aprovació, devolucions i manteniment | Unificar tot el procés | Recorregut complet des de l'alta del material fins a la devolució | Abast elevat i moltes regles per definir |
| **B. Adaptar una ferramenta existent** | Configurar una ferramenta d'inventari o calendari amb formularis i automatitzacions | Posada en marxa ràpida i menys desenvolupament | Configuració mínima amb una petició i un conflicte | Límits de personalització, llicència o integració |
| **C. Portal web centrat en la reserva** | Mantindre l'inventari bàsic i construir només consulta de disponibilitat, petició i estat | Resoldre el punt més problemàtic amb un recorregut reduït | Catàleg curt, dos dates, petició, aprovació i estat | Dependència de la qualitat de les dades i del control de solapaments |

Les alternatives no són tres *frameworks*. Canvien l'abast i la manera de respondre al problema.

## 5. Criteris definits abans de puntuar

L'equip usa una escala de l'1 al 3:

- **1:** resposta dèbil o amb obstacles importants;
- **2:** resposta possible, però amb condicions o incerteses;
- **3:** resposta sòlida amb les evidències disponibles.

La importància també es representa de l'1 al 3. Primer s'acorda què significa cada criteri i després es valoren les alternatives.

| Criteri | Importància | Què es pregunta l'equip? |
| --- | :---: | --- |
| Valor respecte de la necessitat | 3 | Reduïx peticions incompletes, esperes i solapaments? |
| Accés a validació | 2 | Es pot provar amb persones o casos representatius? |
| Abast assumible | 2 | Es pot obtindre un prototip complet en el temps disponible? |
| Risc principal | 1 | Quantes hipòtesis difícils cal resoldre? |
| Recursos i costos | 1 | Necessita servicis, llicències o treball no disponibles? |
| Integració coherent de DAW | 3 | Permet justificar client, servidor, dades i desplegament dins del recorregut? |
| Evidències individuals | 1 | Permet distribuir decisions i aportacions verificables? |
| Dades i accessibilitat | 1 | Es poden gestionar les dades mínimes i un ús accessible? |

## 6. Comparació

La puntuació ponderada és `importància × valoració`. Els nombres ajuden a ordenar la conversa, però no substituïxen la justificació.

| Criteri | Imp. | A | B | C | Justificació resumida |
| --- | :---: | :---: | :---: | :---: | --- |
| Valor respecte de la necessitat | 3 | 3 | 2 | 3 | A i C actuen directament sobre petició, disponibilitat i estat |
| Accés a validació | 2 | 3 | 3 | 3 | Les tres es poden provar amb el mateix grup de participants |
| Abast assumible | 2 | 2 | 3 | 3 | A incorpora processos que no són imprescindibles per validar la necessitat |
| Risc principal | 1 | 2 | 2 | 2 | Totes depenen de regles de disponibilitat encara poc contrastades |
| Recursos i costos | 1 | 1 | 3 | 2 | A exigix més desenvolupament; B podria usar una opció ja disponible |
| Integració coherent de DAW | 3 | 3 | 1 | 2 | A la fa evident; en B dependria de la ferramenta; C encara l'ha de demostrar |
| Evidències individuals | 1 | 3 | 2 | 3 | A i C permeten repartir investigació, disseny, dades, lògica i proves |
| Dades i accessibilitat | 1 | 2 | 2 | 3 | C treballa amb menys dades i un recorregut més curt |
| **Total orientatiu** |  | **36** | **30** | **37** | C queda primera per poc marge |

No seria correcte escriure només «guanya C perquè té 37 punts». La conclusió ha d'explicar que C conserva el valor principal, reduïx l'abast i facilita la validació, però encara presenta un dubte tècnic important.

## 7. Prova de sensibilitat

La decisió és fràgil perquè A i C només es diferencien en un punt. L'equip revisa una hipòtesi:

> Suposàvem que el portal reduït C podria integrar de manera coherent client, servidor, dades i desplegament. Si en el Bloc 3 es comprova que el recorregut depén completament d'una ferramenta externa i no permet eixa integració, la valoració de C en este criteri baixaria de 2 a 1.

Amb el canvi, C passaria de 37 a 34 punts i A quedaria primera amb 36. Per tant, l'equip no oculta la fragilitat: registra que ha de fer una prova tècnica inicial abans de confirmar l'abast.

La prova de sensibilitat no obliga a canviar ara de proposta. Indica **quina informació pot canviar la decisió**.

## 8. Proposta seleccionada provisionalment

### Proposta de valor

> Un portal web que permeta als grups de l'associació consultar material disponible, fer una petició completa i seguir-ne l'estat, perquè la persona responsable puga detectar conflictes abans de confirmar-la.

### Recorregut principal del prototip

1. Una persona autoritzada consulta el material disponible per a unes dates.
2. Selecciona dos elements i envia una petició amb les dades obligatòries.
3. El sistema detecta si existix un conflicte.
4. La persona responsable aprova o rebutja la petició.
5. Les dos parts poden consultar-ne l'estat.

### Abast inicial

| Inclòs | Exclòs o ajornat | Motiu |
| --- | --- | --- |
| Catàleg reduït, disponibilitat, petició, conflicte, aprovació i estat | Pagaments, aplicació mòbil, manteniment avançat, analítica i notificacions automàtiques | No són necessaris per validar el recorregut principal |

### Criteris d'èxit inicials

- una petició no es pot enviar sense dates i quantitats;
- dos casos incompatibles produïxen un avís identificable;
- una persona organitzadora i la responsable poden completar el recorregut sense explicació externa;
- l'estat que veuen les dos parts és coherent.

Estos criteris encara s'hauran de precisar en el Bloc 3.

## 9. Viabilitat preliminar i risc prioritari

| Dimensió | Situació inicial | Què cal comprovar? |
| --- | --- | --- |
| Tècnica | El recorregut pareix compatible amb client, servidor i dades | Fer una prova de conflictes entre intervals de dates |
| Temporal | L'abast C és menor que una gestió integral | Estimar els casos especials i limitar el catàleg del prototip |
| Econòmica | Es preveu usar infraestructura educativa o gratuïta per al prototip | Confirmar límits, condicions i possible cost de continuïtat |
| Dades i permisos | Només caldrien comptes de prova i informació del material | Definir rols i evitar dades personals innecessàries |
| Accessibilitat | El recorregut és curt, però encara no s'ha prototipat | Comprovar teclat, etiquetes, contrast i missatges d'error |

La prova prioritària prevista per al Bloc 3 és construir, amb dades fictícies, dos reserves compatibles i dos incompatibles. Si la regla no es pot explicar, provar o integrar amb un cost assumible, l'equip revisarà C i considerarà A o B.

## 10. Exemple de revisió creuada

Un altre equip formula esta observació:

> «El portal pot mostrar una disponibilitat incorrecta si la persona responsable no registra les devolucions.»

L'equip l'accepta perquè afecta el valor central. Afig al recorregut un canvi d'estat mínim —pendent, aprovada, prestada i retornada—, però no incorpora un mòdul complet de manteniment.

També rep el suggeriment d'afegir notificacions per correu. El deixa pendent perquè no és necessari per comprovar la necessitat principal i podria ampliar l'abast.

## 11. Exemple de respostes individuals

Les respostes no han de ser idèntiques ni repartir el projecte en compartiments incomunicats.

**Membre 1:** «Vaig proposar comparar una ferramenta existent perquè podia reduir el temps de desenvolupament. Després de revisar les limitacions d'integració, vaig donar suport a C, però considere imprescindible la prova de conflictes entre dates.»

**Membre 2:** «Vaig ajudar a reduir l'abast de C. El límit principal és que el prototip no gestionarà pagaments ni manteniment avançat. La proposta quedaria invalidada si la persona responsable no pot mantindre l'estat del material amb un esforç raonable.»

Cada persona hauria d'enllaçar també la seua aportació verificable en el repositori.

## 12. Possible estructura de la presentació

En cinc minuts, l'equip podria seguir este fil:

1. necessitat i dos evidències, amb les seues limitacions;
2. tres alternatives i diferència principal entre elles;
3. criteris, resultat de la comparació i prova de sensibilitat;
4. recorregut i exclusions del prototip seleccionat;
5. risc prioritari, prova prevista i qüestió pendent.

Després, cada membre hauria de poder respondre preguntes com:

- Per què adaptar una ferramenta existent no és l'opció seleccionada?
- Quina evidència podria fer-vos canviar a l'alternativa A?
- Per què les notificacions no formen part del prototip?
- Quina aportació concreta has fet a la decisió?

## 13. Altres contextos per practicar el mateix raonament

Estes idees no són propostes preparades. Són punts de partida per formular una necessitat, buscar evidències i generar alternatives:

| Context | Situació que es podria investigar | Evidències que caldria buscar |
| --- | --- | --- |
| Club esportiu | Material compartit que no sempre està disponible quan comença un entrenament | Registres de préstec, incidències, observació i entrevistes |
| Hort comunitari | Tasques de reg o manteniment que queden sense responsable o es dupliquen | Historial de tasques, torns, freqüència i persones participants |
| Agenda cultural local | Informació d'activitats dispersa o poc accessible per a determinats públics | Canals actuals, proves de cerca, necessitats d'accessibilitat i entitats organitzadores |
| Associació de voluntariat | Dificultat per cobrir torns i comunicar canvis d'última hora | Torn coberts, cancel·lacions, canals utilitzats i temps de coordinació |
| Taller educatiu | Peticions de reparació incompletes que dificulten prioritzar i fer seguiment | Formularis actuals, incidències reobertes, responsables i temps de resposta |

En qualsevol context, comenceu per la situació observable i les persones afectades. La tecnologia, les funcionalitats i l'arquitectura arriben després de comparar respostes possibles.

## Què mostra curricularment l'exemple?

El cas ajuda a entendre com es poden produir evidències de **RA1.c** —necessitat identificada—, **RA1.e** —tipus de projecte seleccionat entre alternatives— i **RA1.f** —característiques requerides i abast inicial—. Llegir l'exemple no aporta per si mateix cap evidència: l'heu de generar amb la investigació, les decisions i la defensa del vostre projecte.
