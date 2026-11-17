# Grup A. Passos per a l'aprovació del Dossier 2

- **Data de referència:** 17 de novembre de 2026
- **Finalitat:** preparar una versió revisable de l'avantprojecte i obtindre la decisió docent abans del primer traspàs
- **Versió que es podrà identificar després de l'aprovació:** `dossier-2-v1.0`

## Què significa que el projecte està aprovat en este punt

L'aprovació del Dossier 2 significa que una altra parella disposa d'informació suficient per convertir el projecte en un pla de treball. No significa que l'aplicació estiga construïda ni que totes les decisions siguen definitives.

El resultat docent podrà ser:

- **apta per planificar:** la línia base és comprensible i no té impediments essencials;
- **apta amb ajustos:** es pot començar a planificar, però hi ha reserves concretes amb responsable i tractament;
- **revisar:** falta una peça imprescindible per entendre l'abast, el recorregut, les dades, l'arquitectura, la viabilitat o l'autoria.

L'equip prepara el treball i presenta un commit candidat. La verificació i la decisió final corresponen al professorat.

## Vocabulari que utilitzarem

En esta fase **no heu de construir el producte final**. Quan les instruccions demanen comprovar una decisió, utilitzarem estos termes:

| Terme | Què significa | Què no significa |
| --- | --- | --- |
| **Maqueta de baixa fidelitat** | Dibuix o conjunt de pantalles senzilles que mostren la informació, la navegació, els estats i els errors | Una interfície acabada, amb disseny visual definitiu i tota la programació |
| **Prova guiada de la maqueta** | Una persona intenta seguir una tasca sobre les pantalles i l'equip registra dubtes, errors i canvis | Una validació completa del producte o del mercat |
| **Prova tècnica reduïda** | Codi, configuració o consulta mínima per comprovar un risc concret amb entrada, procediment i resultat | Construir l'aplicació completa o deixar preparada tota la funcionalitat final |
| **Demostració parcial** | Evidència menuda i reproduïble d'un únic comportament important | La versió funcional que es desenvoluparà en les fases posteriors |

Per exemple, comprovar dos peticions simultànies no obliga a crear tota l'aplicació de reserves. Es pot preparar una prova tècnica reduïda amb una taula mínima, dos peticions i el resultat final de la base de dades.

## Condicions comunes per presentar el commit candidat

Abans de demanar la revisió docent, tots els equips han de comprovar:

- [ ] Tot el treball que es vol entregar està integrat en `main`.
- [ ] Els apartats 1–13 del Dossier 2 descriuen el mateix abast i no es contradiuen.
- [ ] L'apartat 14 diferencia `Pendent`, `Preparada per revisar` i `Verificada pel professorat`.
- [ ] Cap membre de l'equip s'ha atribuït una verificació docent.
- [ ] L'apartat 15 només marca afirmacions sostingudes per evidències localitzables.
- [ ] Les proves descriuen entrada, procediment, resultat, límits i decisió.
- [ ] Allò que encara no s'ha executat apareix com a previst o pendent.
- [ ] Cada membre té un fitxer propi en `evidencies/alumnat/` i pot defensar una cadena completa.
- [ ] `docs/00-control/fonts-ia.md` diferencia treball propi, fonts, ajuda d'IA i verificació humana.
- [ ] `docs/00-control/decisions.md` conté les decisions que han canviat l'abast o la solució.
- [ ] La part emissora de `traspassos/01-avantprojecte-a-planificacio.md` està preparada.
- [ ] L'equip presenta el hash complet del commit candidat.

No creeu l'etiqueta `dossier-2-v1.0` abans que el professorat accepte un hash concret.

## A-1. Sistema de préstec de material

### Passos que heu de seguir

1. **Decidiu què ocorre amb Google Calendar.**
   - Si forma part de la línia base, feu una prova tècnica reduïda amb una franja ocupada, una lliure i una resposta d'error o temps d'espera esgotat.
   - Si no podeu comprovar-la, retireu-la del recorregut imprescindible i deixeu-la com a ampliació o alternativa futura.
2. **Registreu el resultat de la decisió.** Actualitzeu requisits, arquitectura, alternatives, riscos i traçabilitat perquè tots expliquen la mateixa opció.
3. **Reviseu el contingut preparat amb ajuda d'IA.** En l'apartat 13 i en `fonts-ia.md`, indiqueu què heu comprovat, què heu corregit i què continua pendent.
4. **Comproveu la maqueta de pantalles.** Feu una prova guiada curta del préstec, el solapament i la devolució amb avaria. Si només podeu fer un recorregut simulat, identifiqueu-lo així i no el presenteu com una prova amb persones.
5. **Actualitzeu B3-01–B3-05.** Cada fila ha de tindre evidència, responsable, estat fidel i, quan pertoque, reserva.
6. **Completeu les aportacions individuals.** Iker i Àngel han d'enllaçar i poder explicar una decisió, una objecció o una prova diferent.
7. **Prepareu l'acta i el commit candidat.** Incloeu riscos coneguts, recursos accessibles i qualsevol ajust que haurà de rebre la parella planificadora.

### Es podrà aprovar quan

- el recorregut principal no depenga d'una integració no comprovada;
- B3-05 deixe d'aparéixer com a bloqueig sense resoldre;
- la revisió humana del contingut i les evidències individuals siguen localitzables;
- la checklist final coincidisca amb les proves realment fetes.

## A-2. Carta digital i comandes de BatoiBab

### Passos que heu de seguir

1. **Separeu els tipus d'evidència.** Indiqueu quines converses van ocórrer realment, amb quin rol i quins límits; convertiu en hipòtesi qualsevol exemple o resposta orientativa que no procedisca d'una consulta real.
2. **Fixeu un únic recorregut principal.** Decidiu si la versió inclou carta i comandes. Manteniu proveïdors, compres i inventari fora si no hi ha evidència i temps que justifiquen incloure'ls.
3. **Resoleu la contradicció de les dades.** Si hi ha comandes, expliqueu per què es recullen nom i telèfon, qui hi accedix, durant quant de temps i com s'eliminen. No afirmeu alhora que no hi ha formulari ni dades de clientela.
4. **Justifiqueu l'aplicació pròpia.** Compareu-la amb una carta PDF, una pàgina senzilla o un menú QR segons valor, actualització, errors, cost i manteniment.
5. **Definiu la font d'ingredients i al·lèrgens.** Registreu autoria, correspondència amb els productes reals, data o responsabilitat d'actualització i resposta segura quan la informació no estiga confirmada.
6. **Reviseu la maqueta de pantalles.** Mostreu carta, comanda, confirmació, errors i accés del personal. Feu una prova guiada amb una tasca concreta i registreu els canvis.
7. **Creeu les evidències individuals.** Viktoriia, Pau i Rafa necessiten un fitxer propi i una aportació verificable.
8. **Netegeu l'apartat 14.** Elimineu duplicacions entre instruccions i respostes, actualitzeu B3-01–B3-05 i completeu l'acta emissora.

### Es podrà aprovar quan

- les afirmacions sobre el negoci siguen honestes i contrastables;
- l'abast, les dades, els requisits i el recorregut no es contradiguen;
- la informació d'al·lèrgens tinga font i límits visibles;
- les tres aportacions individuals i la checklist final estiguen completes.

## A-3. BarStock

### Passos que heu de seguir

1. **Completeu la maqueta de baixa fidelitat.** Ha d'incloure consulta d'existències, registre d'un moviment, preparació d'una llista i almenys un error important.
2. **Feu una prova guiada de la maqueta.** Una persona ha d'intentar consultar existències i registrar un moviment. Anoteu què entén, on dubta i quin canvi decidiu.
3. **Completeu la viabilitat.** Tracteu les dimensions tècnica, temporal, econòmica, legal, de desplegament i d'accessibilitat amb recursos, límits, riscos i accions.
4. **Tanqueu la decisió sobre la integració externa.** Seleccioneu una font amb valor, llicència i resposta a fallades, o justifiqueu que no s'inclou en la línia base.
5. **Concreceu permisos i infraestructura.** Indiqueu qui consulta i modifica, com es protegix l'operació principal i quines decisions continuen provisionals.
6. **Actualitzeu traçabilitat i autoria.** Clodoaldo i Unai han de poder explicar una cadena necessitat → objectiu → requisit → component → prova → risc.
7. **Completeu els apartats 14–15 i l'acta.** No marqueu les proves previstes com a realitzades.

### Es podrà aprovar quan

- la interfície i la viabilitat deixen de ser apartats buits;
- el recorregut d'inventari puga convertir-se en lliurables verificables;
- les decisions provisionals, les proves pendents i les aportacions individuals queden identificades;
- hi haja un commit candidat complet en `main`.

## A-4. Gestió de subscripcions

### Passos que heu de seguir

1. **Reviseu la checklist final.** Desmarqueu qualsevol afirmació que no tinga una evidència localitzable. Una casella marcada no tanca una esmena per si mateixa.
2. **Tanqueu B3-01.** Feu una prova guiada de la maqueta amb la tasca «registrar una subscripció i entendre el cost mensual». Registreu participants o casos, resultat, límits i canvis.
3. **Tanqueu B3-04 amb una prova tècnica reduïda.** No cal construir el sistema complet. Comproveu, de manera aïllada, que una tasca es pot programar i que un correu de prova s'envia o que l'error queda registrat de manera visible.
4. **Si la prova no és viable en el proveïdor triat,** compareu una alternativa, registreu el límit descobert i canvieu la decisió o convertiu-la en una reserva explícita.
5. **Reviseu Frankfurter.** Confirmeu valor, condicions d'ús, límits i resposta quan el servici no està disponible.
6. **Creeu les evidències individuals.** Javi i Júlia han d'enllaçar una aportació pròpia i poder explicar una decisió global.
7. **Completeu B3-01–B3-05, la decisió, l'acta i el hash candidat.** No useu el Dossier 1 com a substitut de l'evidència individual actual.

### Es podrà aprovar quan

- la checklist siga fidel i B3-01, B3-04 i B3-05 tinguen tractament real;
- la tasca programada i el correu tinguen un resultat reduït o una reserva justificada;
- Javi i Júlia disposen d'evidències individuals;
- el traspàs identifique clarament riscos i treball pendent.

## A-5. Plataforma d'intercanvi local

### Passos que heu de seguir

1. **Integreu el treball en `main`.** El contingut de `bloc3/inici-dossier-2` s'ha de revisar mitjançant una pull request i integrar-se. El professorat no aprovarà una versió que només existisca en una branca de treball.
2. **Comproveu el Dossier 2 després de la integració.** Els apartats 1–13 han de contindre el treball real; la taula d'esmenes no substituïx el dossier.
3. **Expliqueu l'origen de la necessitat amb honestedat.** Diferencieu experiència, cas representatiu, font pública i hipòtesi. Si no hi ha una AMPA o un club participant, no els presenteu com a client real.
4. **Fixeu les regles de comptes i persones menors.** Indiqueu qui pot crear comptes, quines dades es mostren i quines no, i com es protegix el contacte.
5. **Descriviu moderació i cicle de vida.** Concreceu publicació, denúncia, retirada, caducitat i restauració dels anuncis.
6. **Enllaceu la prova tècnica reduïda d'imatges.** Ha de mostrar una imatge acceptada, una rebutjada, límits, emmagatzematge i decisió.
7. **Compareu fonts o servicis externs.** Expliqueu el valor real de la font de centres o descarteu-la si no modifica cap decisió útil.
8. **Completeu autoria i revisió.** Carlos i Francesc han d'enllaçar les seues evidències, registrar l'ús d'IA i revisar mútuament els apartats.
9. **Completeu la checklist, l'acta emissora i el commit candidat de `main`.**

### Es podrà aprovar quan

- el treball complet estiga integrat en `main`;
- els apartats 1–13 deixen de ser una plantilla buida;
- comptes, contacte, moderació, imatges i font externa tinguen decisions coherents;
- l'autoria i les evidències siguen localitzables des del dossier.

## A-6. Reserva d'instal·lacions esportives

### Passos que heu de seguir

1. **Corregiu els estats B3-01–B3-06.** L'equip pot indicar `Preparada per revisar`, però només el professorat pot escriure `Verificada` o donar l'aprovació.
2. **Executeu una prova tècnica reduïda de concurrència.** Prepareu una taula mínima i dos intents simultanis sobre la mateixa pista i franja. Registreu les dos respostes i l'estat final de la base de dades.
3. **Expliqueu el resultat esperat.** Només una reserva pot quedar confirmada; l'altra ha de rebre una resposta comprensible i la base de dades ha de conservar un estat coherent.
4. **Compareu la font meteorològica.** Contrasteu Xweather amb OpenWeatherMap, AEMET o l'opció de no integrar dades meteorològiques. Reviseu llicència, camps, límits, disponibilitat i fallades.
5. **Decidiu si el temps modifica realment la reserva.** Si només decora la pantalla, retireu la integració de la línia base. Si aporta valor, expliqueu quina decisió canvia i què ocorre quan falla.
6. **Manteniu visible el caràcter acadèmic.** Les instal·lacions, persones i reserves han de ser fictícies mentre no existisca autorització; la maqueta ha de mostrar l'avís corresponent.
7. **Enllaceu les aportacions individuals.** Dani, Nehuen i Rustam han de tindre una decisió o prova pròpia i defensar el recorregut global.
8. **Completeu els apartats 14–15, l'acta i el commit candidat.** No descrigueu la concurrència com a comprovada si només està dissenyada.

### Es podrà aprovar quan

- la concurrència tinga un resultat reproduïble o un tractament docent explícit;
- la integració meteorològica estiga justificada o retirada;
- els estats no s'autoqualifiquen com a acceptats;
- les tres evidències individuals, la checklist i l'acta siguen coherents.

## Com presentar la revisió docent

Quan hàgeu acabat, envieu al professorat un únic missatge amb:

```text
Projecte: projecte-a-X
Commit candidat: HASH COMPLET
Dossier 2: enllaç al fitxer en eixe commit
Evidències individuals: enllaços
Proves tècniques reduïdes o proves guiades: enllaços
Esmenes que considereu preparades: B3-...
Reserves que continuen obertes: ...
Acta emissora: enllaç
```

El professorat revisarà exactament eixe hash. Si demana una correcció, creeu un commit nou i presenteu el nou hash; no modifiqueu la història per fer que el hash anterior apunte a un contingut diferent.

Després de rebre «apta per planificar» o «apta amb ajustos» sobre un hash concret, podreu identificar-lo com `dossier-2-v1.0` i completar el traspàs amb la parella receptora.
