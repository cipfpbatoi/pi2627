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
| **Revisió del recorregut sobre la maqueta** | Una persona de l'equip recorre els dibuixos i una altra comprova si tots els passos, estats, errors i missatges estan representats; es registren mancances i canvis | Una prova amb persones usuàries, una validació del mercat o una pantalla programada |
| **Cas de validació tècnica futura** | Descripció del risc que es comprovarà més avant: dades inicials, acció, resultat esperat, evidència que caldrà conservar i alternativa si falla | Executar ara codi, scripts, consultes, integracions o configuracions |

En este tancament no heu de programar res. Per exemple, davant de dos peticions simultànies, ara definiu l'estat inicial, les dos accions, el resultat esperat —una acceptada i una rebutjada—, el risc i la futura evidència. L'execució es farà en un bloc posterior.

## Sobre el context del projecte

Les converses, entrevistes o consultes que apareguen en el relat del projecte **no formen part dels criteris d'aprovació**. No heu d'explicar si són reals, simulades ni d'on provenen, i tampoc heu de fer ara una entrevista per superar el punt de control.

El professorat revisarà si el projecte és internament coherent i planificable: necessitat plantejada, abast, persones usuàries, requisits, recorregut, dades, arquitectura, viabilitat, riscos, proves, decisions i autoria. Les converses no s'utilitzaran com a evidència per acreditar estos elements.

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

1. **Decidiu què ocorre amb Google Calendar, sense programar encara la integració.**
   - Si forma part de la línia base, deixeu planificada per a un bloc posterior la validació d'una franja ocupada, una lliure i una resposta d'error o temps d'espera esgotat. Definiu també una alternativa segura per continuar el préstec si Calendar no està disponible.
   - Si no és imprescindible, deixeu-lo com a ampliació futura i expliqueu quina alternativa s'utilitzarà mentrestant.
2. **Registreu la decisió i la validació futura.** Actualitzeu requisits, arquitectura, alternatives, riscos i traçabilitat perquè tots expliquen la mateixa opció. No creeu credencials, no configureu OAuth i no programeu consultes a l'API en esta fase.
3. **Reviseu el contingut preparat amb ajuda d'IA.** En l'apartat 13 i en `fonts-ia.md`, indiqueu què heu comprovat, què heu corregit i què continua pendent.
4. **Reviseu els recorreguts sobre la maqueta.** Recorreu els dibuixos del préstec, el solapament i la devolució amb avaria; comproveu passos, estats, errors i missatges, i registreu les mancances i els canvis. No cal cap participant extern.
5. **Actualitzeu B3-01–B3-05.** Cada fila ha de tindre evidència, responsable, estat fidel i, quan pertoque, reserva.
6. **Completeu les aportacions individuals.** Iker i Àngel han d'enllaçar i poder explicar una decisió, una objecció o una prova diferent.
7. **Prepareu l'acta i el commit candidat.** Incloeu riscos coneguts, recursos accessibles i qualsevol ajust que haurà de rebre la parella planificadora.

### Es podrà aprovar quan

- el paper de Calendar, la validació futura i l'alternativa segura estiguen explicats;
- B3-05 reflectisca la reserva pendent sense exigir programació anticipada ni aparéixer com a bloqueig d'este bloc;
- la revisió humana del contingut i les evidències individuals siguen localitzables;
- la checklist final coincidisca amb les proves realment fetes.

## A-2. Carta digital i comandes de BatoiBab

### Passos que heu de seguir

1. **Centreu el dossier en el problema que voleu resoldre.** No cal revisar ni justificar la procedència de les converses. Useu el context descrit només per concretar persones usuàries, necessitats i decisions; l'aprovació dependrà de la coherència i la viabilitat del projecte.
2. **Fixeu un únic recorregut principal.** Decidiu si la versió inclou carta i comandes. Manteniu proveïdors, compres i inventari fora si no hi ha evidència i temps que justifiquen incloure'ls.
3. **Resoleu la contradicció de les dades.** Si hi ha comandes, expliqueu per què es recullen nom i telèfon, qui hi accedix, durant quant de temps i com s'eliminen. No afirmeu alhora que no hi ha formulari ni dades de clientela.
4. **Justifiqueu l'aplicació pròpia.** Compareu-la amb una carta PDF, una pàgina senzilla o un menú QR segons valor, actualització, errors, cost i manteniment.
5. **Definiu com es comprovarien ingredients i al·lèrgens.** Podeu treballar amb un menú, etiquetes d'exemple o documentació disponible. Registreu autoria, límits, actualització prevista i resposta segura quan la informació no estiga confirmada.
6. **Reviseu els recorreguts sobre la maqueta.** Mostreu carta, comanda, confirmació, errors i accés del personal. Recorreu els dibuixos amb una tasca concreta i registreu pantalles o missatges que falten, contradiccions i canvis. No cal cap participant extern.
7. **Creeu les evidències individuals.** Viktoriia, Pau i Rafa necessiten un fitxer propi i una aportació verificable.
8. **Netegeu l'apartat 14.** Elimineu duplicacions entre instruccions i respostes, actualitzeu B3-01–B3-05 i completeu l'acta emissora.

### Es podrà aprovar quan

- el problema, les persones usuàries i el recorregut principal siguen coherents;
- l'abast, les dades, els requisits i el recorregut no es contradiguen;
- la informació d'al·lèrgens tinga font i límits visibles;
- les tres aportacions individuals i la checklist final estiguen completes.

## A-3. BarStock

### Passos que heu de seguir

1. **Completeu la maqueta de baixa fidelitat.** Ha d'incloure consulta d'existències, registre d'un moviment, preparació d'una llista i almenys un error important.
2. **Reviseu els recorreguts sobre la maqueta.** Una persona de l'equip recorre els dibuixos per consultar existències i registrar un moviment, i l'altra comprova que cada pas, estat, error i missatge està representat. Anoteu mancances, contradiccions i canvis; no cal cap participant extern.
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
2. **Tanqueu B3-01 amb una revisió del recorregut.** Recorreu els dibuixos de «registrar una subscripció i entendre el cost mensual», comproveu passos, dades, estats, errors i missatges, i registreu mancances i canvis. No cal cap participant extern.
3. **Definiu la validació futura de B3-04.** Sense programar ara, descriviu una tasca prevista, el correu esperat, un cas de fallada, l'evidència que es conservarà i l'alternativa si el proveïdor no ho permet. Registreu els components i les fallades en l'apartat 9, la decisió D-05 en el 10, el cas complet en la fila «Operació i desplegament» de l'11, la cadena en el 12 i la reserva pendent en la fila B3-04 del 14.
4. **Registreu B3-04 com a reserva tècnica pendent.** Indiqueu el bloc d'execució i l'impacte sobre infraestructura, cost i operació. La falta de codi no bloqueja este tancament.
5. **Reviseu Frankfurter.** Confirmeu valor, condicions d'ús, límits i resposta quan el servici no està disponible.
6. **Creeu les evidències individuals.** Javi i Júlia han d'enllaçar una aportació pròpia i poder explicar una decisió global.
7. **Completeu B3-01–B3-05, la decisió, l'acta i el hash candidat.** No useu el Dossier 1 com a substitut de l'evidència individual actual.

### Es podrà aprovar quan

- la checklist siga fidel i B3-01, B3-04 i B3-05 tinguen tractament real;
- la tasca programada i el correu tinguen un cas de validació futura i una reserva justificada;
- Javi i Júlia disposen d'evidències individuals;
- el traspàs identifique clarament riscos i treball pendent.

## A-5. Plataforma d'intercanvi local

### Passos que heu de seguir

1. **Integreu el treball en `main`.** El contingut de `bloc3/inici-dossier-2` s'ha de revisar mitjançant una pull request i integrar-se. El professorat no aprovarà una versió que només existisca en una branca de treball.
2. **Comproveu el Dossier 2 després de la integració.** Els apartats 1–13 han de contindre el treball real; la taula d'esmenes no substituïx el dossier.
3. **Concreteu la necessitat que voleu resoldre.** No cal justificar la procedència de les converses amb AMPA o clubs. Definiu quines persones usarien la plataforma, quin problema tindrien i quines regles necessita la solució.
4. **Fixeu les regles de comptes i persones menors.** Indiqueu qui pot crear comptes, quines dades es mostren i quines no, i com es protegix el contacte.
5. **Descriviu moderació i cicle de vida.** Concreceu publicació, denúncia, retirada, caducitat i restauració dels anuncis.
6. **Definiu la validació futura d'imatges.** Sense programar ara, concreteu formats i grandària, emmagatzematge, privacitat, eliminació, una imatge admesa, una rebutjada, l'evidència futura i l'alternativa sense imatge.
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
2. **Concreteu les regles de reserva.** No cal justificar la procedència de cap conversa amb una persona gestora. Definiu franges, restriccions, dades, autoritzacions i casos límit com a decisions del projecte.
3. **Definiu la validació futura de concurrència.** Sense crear ara una base de dades, descriviu dos intents simultanis sobre la mateixa pista i franja, les dos respostes esperades, l'estat final i l'evidència que es conservarà més avant.
4. **Expliqueu el resultat esperat i la reserva.** Només una reserva pot quedar confirmada; l'altra ha de rebre una resposta comprensible i la base de dades ha de conservar un estat coherent. Indiqueu el bloc d'execució i l'alternativa si la solució prevista falla.
5. **Compareu la font meteorològica.** Contrasteu Xweather amb OpenWeatherMap, AEMET o l'opció de no integrar dades meteorològiques. Reviseu llicència, camps, límits, disponibilitat i fallades.
6. **Decidiu si el temps modifica realment la reserva.** Si només decora la pantalla, retireu la integració de la línia base. Si aporta valor, expliqueu quina decisió canvia i què ocorre quan falla.
7. **Manteniu visible el caràcter acadèmic.** Les instal·lacions, persones i reserves han de ser fictícies mentre no existisca autorització; la maqueta ha de mostrar l'avís corresponent.
8. **Enllaceu les aportacions individuals.** Dani, Nehuen i Rustam han de tindre una decisió o prova pròpia i defensar el recorregut global.
9. **Completeu els apartats 14–15, l'acta i el commit candidat.** No descrigueu la concurrència com a comprovada si només està dissenyada.

### Es podrà aprovar quan

- la concurrència tinga un cas de validació futura i un tractament docent explícit;
- la integració meteorològica estiga justificada o retirada;
- els estats no s'autoqualifiquen com a acceptats;
- les tres evidències individuals, la checklist i l'acta siguen coherents.

## Després de l'aprovació: rebre el projecte que planificareu

Quan el professorat accepte el hash del Dossier 2 i es cree `dossier-2-v1.0`, deixareu la custòdia del projecte propi i rebreu un projecte diferent per planificar. Segons la rotació prevista:

| Equip planificador | Projecte rebut |
| --- | --- |
| A-1 | `projecte-a-2` |
| A-2 | `projecte-a-3` |
| A-3 | `projecte-a-4` |
| A-4 | `projecte-a-5` |
| A-5 | `projecte-a-6` |
| A-6 | `projecte-a-1` |

Seguiu este ordre:

1. Comproveu la versió rebuda, l'accés al repositori, les evidències i la part emissora de l'acta.
2. Llegiu-ho sense explicació oral inicial de l'equip autor. Anoteu què és planificable, què és ambigu, què falta i quines reserves s'hereten.
3. Classifiqueu cada qüestió com a **aclariment**, **decisió de planificació** o **canvi de línia base** i creeu una issue per cada qüestió accionable.
4. Després de l'auditoria, formuleu preguntes concretes a l'equip autor i registreu les respostes. No corregiu silenciosament el seu Dossier 2.
5. Completeu la part receptora de l'acta amb `acceptat`, `acceptat amb reserves` o `retornat per completar`.
6. Si queda acceptat o acceptat amb reserves, completeu en el repositori rebut els apartats **1–4** de `docs/03-planificacio/pla-projecte.md` i inicieu l'apartat **16**.
7. En esta primera sessió no completeu els apartats 5–15 ni el 17, no estimeu hores, no tanqueu el cronograma o el pressupost, no prepareu els plans definitius de proves o desplegament i no programeu.
8. Registreu una aportació individual per membre i publiqueu en `main` el commit de la sessió.

Consulteu la guia [Sessió 1 del bloc 4: rebre i descompondre](bloc4-sessio1.md). Qualsevol canvi d'abast, requisit o decisió estructural necessita motiu, impacte i autorització docent.

## Com presentar la revisió docent

Quan hàgeu acabat, envieu al professorat un únic missatge amb:

```text
Projecte: projecte-a-X
Commit candidat: HASH COMPLET
Dossier 2: enllaç al fitxer en eixe commit
Evidències individuals: enllaços
Maqueta, revisió del recorregut i casos de validació futura: enllaços
Esmenes que considereu preparades: B3-...
Reserves que continuen obertes: ...
Acta emissora: enllaç
```

El professorat revisarà exactament eixe hash. Si demana una correcció, creeu un commit nou i presenteu el nou hash; no modifiqueu la història per fer que el hash anterior apunte a un contingut diferent.

Després de rebre «apta per planificar» o «apta amb ajustos» sobre un hash concret, podreu identificar-lo com `dossier-2-v1.0` i completar el traspàs amb la parella receptora.
