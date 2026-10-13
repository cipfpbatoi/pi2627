# Mínims dels mòduls integrats en el prototip

## Finalitat

Cada proposta ha de permetre construir, dins del temps del bloc 5, un recorregut funcional que integre de manera coherent els mínims confirmats pels mòduls participants. No cal implementar-los en els blocs 2–4: primer se'n justifica la funció dins del projecte i després se'n planifiquen les tasques, els recursos, els riscos, les proves i les evidències.

Estos mínims no incorporen percentatges ni determinen la qualificació del Projecte Intermodular. Cada mòdul aplica els seus instruments i criteris d'avaluació. En Projecte Intermodular s'observa com l'equip integra, dissenya, planifica, executa, controla i valida el conjunt.

## Desenvolupament Web en Entorn Servidor

1. **Selecció justificada de l'*stack*.** L'equip compararà alternatives i justificarà la selecció segons la necessitat, els requisits, els riscos, les capacitats de l'equip, el temps i el desplegament. No n'hi ha prou amb indicar una preferència o una tecnologia coneguda.
2. **Framework de servidor i persistència.** El projecte usarà un framework de servidor. Una base de dades conservarà comptes d'usuari i almenys una entitat relacionada amb el problema; les migracions crearan l'esquema i els *seeders* carregaran dades de prova fictícies. El recorregut principal consultarà i modificarà dades amb validació i integritat adequades.
3. **Manteniment administratiu.** El prototip inclourà una funcionalitat administrativa per consultar i mantindre les dades principals del projecte. L'abast concret, els accessos i les operacions necessàries s'han de justificar segons el problema; no s'han d'afegir rols o pantalles sense una funció real.
4. **Creació, consum i documentació d'una API.** El servidor exposarà una API pròpia relacionada amb el recorregut principal. Se'n documentaran peticions, respostes, errors i condicions d'accés, i se'n demostrarà el consum des d'un client.
5. **Integració híbrida.** Una funció recuperarà i processarà informació d'un repositori o servici existent i la combinarà amb dades o lògica pròpies per aportar valor. Se'n documentaran la font, les condicions d'ús, els límits i el comportament davant d'una fallada. Les proves poden usar dades controlades per no dependre del servici extern en directe.

## Desenvolupament Web en Entorn Client

1. **Selecció justificada del framework.** L'equip compararà alternatives per al client i justificarà la selecció segons la necessitat, els requisits, els riscos, les capacitats de l'equip, el temps i el desplegament. La comparació inclourà l'opció de desenvolupar amb JavaScript Vanilla. No n'hi ha prou amb indicar una preferència o una tecnologia coneguda.
2. **Creació d'una SPA.** Es crearà una aplicació d'una sola pàgina (SPA) relacionada amb el recorregut principal del projecte, que consumirà dades de l'API pròpia.
3. **Autenticació contra l'API desenvolupada.** El client permetrà iniciar sessió mitjançant l'API pròpia, gestionarà l'estat autenticat segons el mecanisme justificat i consumirà almenys una operació protegida necessària per al recorregut de la SPA. Es comprovaran l'accés correcte, les credencials incorrectes, l'accés no autoritzat i el tancament de sessió. No s'imposa JWT, sessions o una llibreria concreta.

## Desplegament d'Aplicacions Web

1. **Solució d'infraestructura justificada.** A partir dels requeriments base i del problema del projecte, l'equip proposarà una solució que explique quins components necessita, com es relacionen i per què són adequats per a l'aplicació, les dades, la seguretat, la disponibilitat, els costos i la continuïtat.
2. **Infraestructura en el núvol.** El prototip es desplegarà en una infraestructura en el núvol. Se'n documentaran els servicis, els entorns, la configuració, els accessos, els secrets, les dependències, els límits i els costos aplicables, sense publicar credencials.
3. **Integració i desplegament continus.** El repositori inclourà un procés automatitzat que, davant d'un canvi versionat, execute les comprovacions acordades i desplegue l'aplicació en l'entorn previst. Se'n conservaran la configuració, els disparadors, les etapes, els artefactes, les comprovacions, el resultat i la resposta davant d'una fallada.
4. **Documentació de desplegament.** Una tercera persona podrà preparar l'entorn, desplegar, verificar, actualitzar i, quan pertoque, recuperar o revertir l'aplicació seguint les instruccions. Les proves identificaran versió, entorn o URL, resultat, temps, incidències i ajustos.

## Disseny d'Interfícies Web

1. **Guia d'estil.** Documentarà la paleta de colors amb contrast adequat, les tipografies i els estils dels botons i components.
2. **Prototipatge previ.** Inclourà *wireframes* i maquetes de les pantalles principals elaborats amb Figma, Penpot o una ferramenta equivalent abans de programar-les.
3. **Maquetació i CSS.** El codi usarà variables CSS, Flexbox o Grid i una estructura organitzada; no usarà estils en línia. Les decisions s'adaptaran a l'arquitectura visual del projecte.
4. **Disseny adaptatiu.** Seguirà un enfocament *mobile-first* i es comprovarà en amplàries representatives de mòbil, tauleta i escriptori, sense desplaçament horitzontal ni pèrdua de funcionalitat.
5. **Imatges optimitzades.** Usarà formats i dimensions adequats, com WebP o AVIF per a imatges i SVG quan siga apropiat, amb fitxers optimitzats i sense degradació innecessària.
6. **Efectes i animacions.** Les transicions de ratolí i focus i les animacions CSS aportaran retroacció o valor, no impediran l'ús i respectaran la reducció de moviment quan pertoque.
7. **Integració obligatòria de vídeo.** El prototip integrarà almenys un vídeo relacionat amb el projecte mitjançant HTML5 o JavaScript. Se'n justificaran la funció, el format o servici, els controls, l'accessibilitat, el rendiment i el comportament davant d'una fallada.
8. **Interacció en dispositius diferents.** Els menús, formularis, controls i altres elements interactius funcionaran tant amb interacció tàctil com amb teclat i dispositius apuntadors.
9. **Estructura semàntica i accessibilitat.** Usarà HTML semàntic, jerarquia d'encapçalaments coherent i alternatives textuals significatives per a les imatges informatives; les decoratives tindran alternativa buida.
10. **Auditoria d'accessibilitat.** S'executarà Google Lighthouse en una versió identificada i se'n conservaran l'informe, les condicions d'execució, els problemes detectats i les correccions o decisions. El prototip haurà d'assolir el llindar que establisca el mòdul de Disseny d'Interfícies; el PI no fixa ni convertix eixe resultat en una qualificació.
11. **Usabilitat.** La navegació serà comprensible, els formularis tindran indicacions clares i l'estil serà coherent. Es realitzaran proves amb dues persones, amb tasques definides, resultats i canvis justificats, sense conservar dades personals innecessàries.

## Traçabilitat en el Projecte Intermodular

Cada mínim confirmat seguirà esta cadena:

```text
mòdul i mínim → funció dins del projecte → requisit
→ tasca i responsable → prova → evidència → estat i decisió
```

| Moment | Què ha de quedar clar |
| --- | --- |
| Bloc 2 · proposta | El recorregut pot integrar els mínims de manera útil i assumible, sense afegir peces desconnectades del problema. |
| Bloc 3 · avantprojecte | Funcions, components, pantalles, dades, decisions, riscos i proves previstos per a cada mínim. |
| Bloc 4 · pla | Tasques, dependències, responsables, estimacions, recursos i proves per a cada mínim. |
| Bloc 5 · prototip | Codi o artefacte executable, resultat de les proves, evidència, incidències i canvis. |
| Bloc 6 · tancament | Estat implementat, provat i validat, limitacions i continuïtat de cada mínim. |

Una proposta que no puga donar sentit o abast assumible a algun mínim confirmat s'ha de revisar amb l'equip educatiu abans del traspàs. Qualsevol canvi posterior ha d'indicar impacte, decisió i evidència.

## Ús d'IA i verificació

Podeu usar IA si registreu per a quina tasca l'heu emprada, quina ajuda heu rebut i com n'heu verificat el resultat. El codi, els dissenys o les proves suggerits s'han de revisar i comprovar; una resposta de l'eina no és una evidència suficient.

Cada membre haurà de poder explicar i modificar les parts en què ha intervingut. En els punts de control, el professorat podrà proposar un cas límit o un canvi acotat i demanar que l'equip mostre l'efecte en el producte, les proves i el pla.

## Relació amb l'avaluació dels mòduls

Les mateixes peces del prototip poden aportar evidència a diferents mòduls, però cada professor o professora les avalua amb els RA, CA i instruments del seu mòdul. Esta pàgina no assigna percentatges ni substituïx les activitats avaluables o la programació didàctica de Servidor, Client, Desplegament o Disseny d'Interfícies.

En Projecte Intermodular, estes peces permeten observar el disseny, la planificació, el seguiment, el control i la validació. Complir un mínim tècnic no acredita automàticament cap RA o CA del Projecte Intermodular ni del mòdul que l'ha proposat.
