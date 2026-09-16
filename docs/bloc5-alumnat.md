# Bloc 5. Desenvolupament i validació del prototip

## Executar un pla rebut i comprovar-lo

Durant **42 hores, en 14 sessions**, assumireu la custòdia del pla d'un tercer projecte. Començareu per auditar la versió `pla-v1.0` i l'acta del segon traspàs. La vostra tasca és obtindre un recorregut funcional demostrable, provar-lo i explicar les desviacions respecte del pla. Un defecte heretat s'ha de registrar amb l'origen i la resposta, sense alterar l'autoria anterior.

## Iteracions i punts de control

| Iteració | Sessions | Hores | Resultat verificable |
| --- | ---: | ---: | --- |
| [5.1. Prova tècnica inicial](bloc5-iteracio1.md) | 1–2 | 6 | Entorn reproduïble i risc tècnic contrastat |
| [5.2. Recorregut mínim](bloc5-iteracio2.md) | 3–6 | 12 | Flux complet amb proves bàsiques |
| [5.3. Increment de valor](bloc5-iteracio3.md) | 7–11 | 15 | Requisits prioritaris incorporats o descartats amb motiu |
| [5.4. Validació i desplegament](bloc5-iteracio4.md) | 12–14 | 9 | Prototip provat, demostrable i amb limitacions conegudes |

Al final de cada iteració entregueu una versió o commit immutable i un [informe breu](bloc5-informe-iteracio.md). Identifiqueu tasques previstes i acabades, hores estimades i reals, proves, incidències, canvis, riscos i decisió per a la iteració següent. El tauler, el pla, el registre de decisions i les evidències individuals han de reflectir l'estat real.

## Com decidir l'abast

Preserveu primer el recorregut que permet comprovar la necessitat principal. Prioritzeu segons valor, dependències, capacitat i risc. La integració de client, servidor i dades depén del projecte; si un component no és necessari, justifiqueu-ho. No afegiu funcionalitats sense revisar el cost, les proves i l'efecte en el desplegament.

Per a cada requisit treballat, conserveu la cadena **necessitat → requisit → issue → persona responsable → canvi → prova → resultat → decisió**. Un resultat negatiu també és evidència si orienta una decisió registrada.

## Tancament del bloc

Prepareu `prototip-v1.0` amb codi, instruccions per executar-lo, dades de prova sense informació sensible, informe de validació, desplegament o demostració reproduïble, limitacions i treball pendent. Completeu `docs/04-seguiment/`, actualitzeu el pla i traslladeu els resultats a `docs/05-tancament/` per al bloc 6. En Aules entregueu l'URL i la versió exacta segons les indicacions docents.

**Punt de control:** una altra persona pot executar el recorregut, repetir les proves i entendre què s'ha canviat respecte del pla?

## Abast curricular

Els informes i registres de les iteracions poden aportar evidència **suficient dins del bloc** de RA4.a–e quan documenten procediments aplicats, indicadors, incidències, canvis i avaluació. La validació amb persones usuàries i el control de condicions poden aportar RA4.f–g quan pertoquen. Les revisions justificades del pla poden aportar evidència **parcial o suficient**, segons el treball real, de RA3.a–h. El prototip és evidència de les decisions i del control, no un RA nou. L'abast s'atribuirà individualment amb la traça i la defensa.
