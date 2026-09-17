# Condicions tècniques comunes del prototip

## Finalitat

Cada proposta ha de permetre construir, dins del temps del bloc 5, un recorregut funcional que integre client, servidor i dades. L'equip tria el problema, la solució i les tecnologies, però el prototip final ha de complir les condicions següents. No cal implementar-les en els blocs 2–4: primer es justifiquen i es planifiquen.

## Mínims de servidor

1. **Dades pròpies.** Una base de dades amb comptes d'usuari i almenys una entitat relacionada amb el problema. Les migracions crearan l'esquema i els seeders carregaran dades de prova fictícies. El recorregut principal consultarà i modificarà dades de manera persistent, amb validació i mesures d'integritat adequades.
2. **API i accés.** El client iniciarà sessió mitjançant una API i consumirà almenys una operació de negoci pròpia del projecte exposada pel servidor. L'API documentarà peticions, respostes, errors i les condicions d'accés; es provarà amb un client.
3. **Pàgina dinàmica de servidor.** Una funcionalitat usarà un framework de servidor i plantilles per generar HTML variable. Inclourà interacció mitjançant un formulari, validació de l'entrada i una resposta visible amb el resultat o els errors. Pot ser una vista concreta; una API que només retorna dades al client no substituïx esta evidència.
4. **Integració híbrida.** Una funció recuperarà i processarà informació d'un repositori o servei existent, i la combinarà amb dades o lògica pròpies per aportar valor al recorregut. Se'n documentaran la font, les condicions d'ús, els límits i el comportament davant d'una fallada. No cal dependre d'un servei extern en directe durant les proves.
5. **Proves i reproducció.** Les instruccions permetran crear la base de dades, executar migracions i seeders i iniciar l'aplicació. Hi haurà proves automatitzades d'un cas correcte, una entrada invàlida i un accés no autoritzat, així com una prova de la integració externa amb dades controlades. Les proves s'enllaçaran amb els requisits que verifiquen.

## Decisió i evidències per fase

| Moment | Què ha de quedar clar |
| --- | --- |
| Bloc 2 · proposta | Un recorregut útil que faça plausibles els cinc mínims i una font d'informació existent accessible. |
| Bloc 3 · avantprojecte | Entitats i dades, operació de l'API, vista generada al servidor, integració, riscos i casos de prova previstos. |
| Bloc 4 · pla | Tasques, dependències, responsables, estimacions, entorn i proves per a cada mínim. |
| Bloc 5 · prototip | Codi executable, dades de prova, API documentada i consumida, pàgina dinàmica, integració i resultats de les proves. |

Una proposta que no puga donar sentit a algun mínim s'ha de revisar amb l'equip educatiu abans del traspàs. Les decisions poden canviar després si hi ha una justificació, una estimació d'impacte i una nova evidència.

## Ús d'IA i verificació

Podeu usar IA en el desenvolupament si registreu per a quina tasca l'heu emprada, quina ajuda heu rebut i com n'heu verificat el resultat. El codi generat i les proves suggerides per IA s'han d'executar i revisar; una resposta de l'eina no és una prova.

Cada membre haurà de poder explicar i modificar les parts en què ha intervingut. En els punts de control, el professorat podrà proposar un cas límit o un canvi acotat d'una regla i demanar que l'equip mostre l'efecte en el codi, les proves i el pla. Es valoraran les decisions i evidències atribuïbles, no la quantitat de codi produïda.

## Relació amb l'avaluació

Estes condicions poden aportar evidències aplicades dels RA6–RA9 de **Desenvolupament Web en Entorn Servidor**, segons els criteris que corresponguen a cada treball. Les activitats pròpies d'eixe mòdul completen la seua avaluació. En **Projecte Intermodular**, les mateixes peces servixen per observar el disseny, la planificació, el seguiment i la validació; complir-les no acredita automàticament cap RA o CA de cap dels dos mòduls.

El [Reial decret 405/2023](https://www.boe.es/buscar/doc.php?id=BOE-A-2023-13221) establix la redacció actualitzada dels RA6–RA9 del mòdul 0613. Migracions, seeders i les proves mínimes ací descrites són condicions de l'enunciat del projecte, no noms de criteris d'avaluació de la norma.
