# Sessió 2. Comparar alternatives

## Objectiu

Convertireu les necessitats millor fonamentades en diferents opcions de projecte, comparareu el seu valor i la seua viabilitat inicial i seleccionareu una proposta sense tancar prematurament la solució tècnica.

En acabar la sessió heu de poder explicar **quina necessitat voleu atendre, quines respostes heu comparat, per què n'heu seleccionat una, quin és el límit del prototip i què podria fer-vos canviar de decisió**. No es tracta de convéncer amb una idea atractiva, sinó de mostrar una decisió raonada i revisable.

En esta sessió encara no heu de programar, triar definitivament un *framework* ni preparar una arquitectura detallada. Primer heu de decidir què val la pena validar i quin recorregut mínim permetria comprovar-ho.

## Abans de començar

Obriu el fitxer `docs/01-proposta/dossier-1.md` del repositori de l'equip i reviseu el treball de la sessió 1. Durant la sessió l'actualitzareu directament: no creeu un segon dossier ni repartiu els apartats de manera que cada persona només conega la seua part.

Tingueu també oberts els registres `evidencies/alumnat/nom-cognoms.md`. Cada membre hi haurà d'escriure la seua resposta individual i enllaçar-la des de l'apartat 14 del dossier.

Si necessiteu veure com s'aplica el procés a casos pròxims, consulteu els [exemples orientatius del Bloc 2](bloc2-exemple.md). Les dades són fictícies: observeu el raonament i no copieu les propostes ni les evidències.

## Organització

| Activitat | Temps | Treball | Resultat que ha de quedar registrat |
| --- | ---: | --- | --- |
| 1. Revisar les evidències | 15 min | Equip | Afirmacions revisades en els apartats 3 i 5 |
| 2. Generar alternatives | 25 min | Individual i equip | Tres respostes diferenciades en l'apartat 6 |
| 3. Definir criteris | 15 min | Equip | Criteris definits abans de puntuar |
| 4. Comparar i seleccionar | 30 min | Equip | Matriu, sensibilitat, proposta i viabilitat inicial en els apartats 7–9 |
| 5. Revisar i preparar la defensa | 35 min | Individual i equip | Revisió creuada, respostes individuals i presentació preparada |
| 6. Presentar i validar | 60 min | Equip, cada membre i professorat | Contrast oral, decisió docent i ajustos registrats |

Les primeres cinc activitats completen les **cinc hores** assignades a `PR-Q.2.1.x` entre les dos sessions. L'última hora correspon a la defensa `DO-Q.2.2.x`.

## Activitat 1. Revisar les evidències

Recupereu les necessitats finalistes de la sessió anterior. Llegiu les afirmacions importants i contrasteu-les amb les fonts o els resultats que heu registrat. No convertiu una opinió o una possibilitat en un fet només perquè encaixa amb la idea que preferiu.

Classifiqueu les afirmacions de la sessió anterior:

| Afirmació | Confirmada, probable o suposada? | Evidència | Risc si és falsa | Cal verificar-la abans de decidir? |
| --- | --- | --- | --- | --- |
|  |  |  |  |  |

Si una necessitat només es basa en suposicions, investigueu-la més o reduïu la confiança amb què la presenteu. Una limitació reconeguda és millor evidència de criteri que una afirmació segura sense suport.

**Punt de control:** en els apartats 3 i 5 del Dossier 1 han de quedar diferenciats els fets, les inferències i les hipòtesis, amb la font o limitació corresponent.

## Activitat 2. Generar alternatives

Proposeu almenys **tres respostes diferenciades**. Una alternativa no és simplement canviar de framework: ha de modificar l'abast, el procés, el tipus de producte o la manera d'aportar valor.

Considereu també una resposta de baixa tecnologia o l'adaptació d'una ferramenta existent. Si sempre concloeu que cal programar-ho tot des de zero, probablement falta comparar opcions.

Per generar-les, cada membre pot proposar primer una resposta i explicar quin valor aportaria. Després, l'equip combina, descarta o reformula les opcions fins a obtindre tres alternatives comparables. Per exemple, davant d'un problema de gestió de reserves, podríeu comparar una aplicació pròpia, l'adaptació d'una ferramenta existent i un recorregut més reduït que automatitze només el punt crític. Tres aplicacions idèntiques amb tecnologies diferents continuarien sent una sola resposta.

| Alternativa | Necessitat que cobrix | Persones beneficiàries | Valor esperat | Prototip que la podria validar | Principal risc o cost |
| --- | --- | --- | --- | --- | --- |
| A |  |  |  |  |  |
| B |  |  |  |  |  |
| C |  |  |  |  |  |

**Punt de control:** l'apartat 6 del Dossier 1 ha de permetre entendre què canvia entre les alternatives, a qui beneficia cadascuna, quin prototip la validaria i quin risc o cost principal presenta.

## Activitat 3. Definir criteris

Abans de puntuar, acordeu què significa cada criteri i quines evidències utilitzareu. Incloeu almenys:

- valor respecte de la necessitat;
- accés a persones o casos per validar;
- abast assumible en el calendari;
- incertesa i riscos principals;
- recursos i possibles costos;
- integració coherent de competències DAW;
- possibilitat de distribuir treball i obtindre evidències individuals;
- implicacions de dades, seguretat, accessibilitat i propietat intel·lectual.

Podeu usar una escala breu, però definiu-la. Per exemple, si utilitzeu valors de l'1 al 3, indiqueu què significaria un 1 i un 3 en cada criteri. Decidiu també si tots tenen la mateixa importància. No canvieu la definició o el pes després de veure quin resultat afavorix la vostra opció preferida.

Una puntuació sense justificació no és una decisió. Cada valor ha de poder relacionar-se amb una evidència, una restricció o una hipòtesi explícita.

**Punt de control:** abans de valorar les alternatives, l'apartat 7 ha de mostrar els criteris, el seu significat i la importància acordada.

## Activitat 4. Comparar i seleccionar

Valoreu les tres alternatives amb els mateixos criteris. A més de les puntuacions, anoteu les compensacions: una opció pot aportar més valor però tindre més risc, i una altra pot ser menys ambiciosa però més fàcil de validar.

| Criteri | Importància | Alternativa A | Alternativa B | Alternativa C | Evidència o justificació |
| --- | --- | ---: | ---: | ---: | --- |
|  |  |  |  |  |  |

Completeu després una **prova de sensibilitat**: canvieu raonablement la importància d'un criteri o una hipòtesi incerta i torneu a observar el resultat. Si canvia l'opció guanyadora, la decisió és fràgil; registreu què cal verificar abans de comprometre més treball. Si no canvia, expliqueu per què considereu que la selecció és robusta.

Per a l'alternativa seleccionada, definiu:

- proposta de valor en una frase;
- recorregut principal que demostraria el prototip;
- funcionalitats o resultats imprescindibles;
- exclusions inicials;
- una prova tècnica o d'ús que reduïsca el risc principal;
- alternativa de reserva si la validació falla.

El recorregut principal és una situació completa que el prototip ha de permetre demostrar de principi a fi. No és una llista de pantalles ni totes les funcionalitats imaginables. Completeu també la viabilitat preliminar de l'apartat 9: recursos, temps, costos, permisos, dades, accessibilitat i incerteses que realment afecten la proposta.

**Punt de control:** els apartats 7–9 han de permetre reconstruir la decisió sense necessitat d'una explicació oral addicional.

## Activitat 5. Revisió creuada, comprovació individual i preparació de la defensa

Intercanvieu la proposta amb un altre equip i useu la taula de l'apartat 11 per comprovar si la necessitat està demostrada, la proposta aporta valor, l'abast és assumible i el prototip permet validar la idea. Registreu les observacions rebudes i indiqueu si les accepteu, les rebutgeu o les deixeu pendents; no incorporeu suggeriments sense valorar-ne l'efecte.

Abans de la defensa, sense consultar la redacció de l'equip, cada membre respondrà:

1. Quin problema es pretén resoldre i quina evidència el sosté?
2. Per què s'ha descartat l'alternativa més pròxima?
3. Quin és el límit més important del prototip?
4. Quina hipòtesi podria invalidar la proposta?
5. Quina decisió has ajudat a prendre i amb quina aportació concreta?

Escriviu les respostes en `evidencies/alumnat/nom-cognoms.md` i enllaceu-les des de l'apartat 14. No les unifiqueu després: les coincidències i les diferències també són evidències. Compareu-les per detectar acords aparents o decisions que encara no estan compartides i reviseu el dossier si descobriu una incoherència.

Prepareu després una presentació de **cinc minuts** que seguisca este fil:

```text
evidència → necessitat → alternatives → decisió → prototip i abast → risc → validació
```

La presentació ha de servir per localitzar i explicar les evidències, no per substituir el dossier. Prioritzeu el contingut i la llegibilitat; no necessiteu animacions ni un disseny complex. Exporteu-la a PDF i guardeu-la amb el nom exacte `docs/01-proposta/presentacio-bloc-2.pdf`.

**Punt de control:** abans del torn de l'equip, qualsevol membre ha de poder explicar la proposta global, la seua aportació i una decisió que haja ajudat a prendre.

## Activitat 6. Presentar i validar

Durant l'última hora, cada equip farà la presentació de **cinc minuts** i cada membre intervindrà en el contrast individual. La presentació se centrarà en les evidències, alternatives, decisió, abast, riscos i validació que s'han demanat en el dossier; el professorat distribuirà els torns i les preguntes segons el nombre d'equips.

Les preguntes no busquen continguts nous ni respostes memoritzades. Servixen per comprovar que podeu justificar la selecció, reconéixer els límits i relacionar la vostra aportació amb el conjunt. Si no sabeu una resposta, no improviseu dades: registreu la qüestió pendent, qui la investigarà i quan es revisarà.

Al final, anoteu en els apartats 12 i 15 la decisió de l'equip educatiu —acceptada, acceptada amb ajustos o reformular—, les condicions indicades i qualsevol canvi que calga fer. Una proposta amb ajustos no és un fracàs: permet corregir l'abast abans d'invertir més temps.

Useu el [recurs de consolidació](bloc2-sessio3.md) per preparar la presentació, registrar la decisió docent i conservar els ajustos demanats.

## Evidència curricular

La comparació i la proposta permeten observar principalment **RA1.c, RA1.e i RA1.f**. Els aspectes de RA2 que apareguen en el dossier són formatius en este bloc. La defensa servix per contrastar individualment estes evidències i l'autoria; no incorpora continguts nous que no s'hagen demanat.

## Lliurament de la sessió

Abans de considerar acabat el bloc, comproveu que heu incorporat:

- en els apartats 3 i 5, la revisió de les afirmacions i les fonts;
- en l'apartat 6, tres alternatives realment diferenciades;
- en l'apartat 7, els criteris, la matriu comparativa i la prova de sensibilitat;
- en els apartats 8 i 9, la proposta seleccionada, el prototip, l'abast i la viabilitat preliminar;
- en l'apartat 10, el repartiment del treball i l'autoria;
- en els apartats 11 i 12, la revisió creuada i la decisió docent;
- en l'apartat 13, les fonts i l'ús d'IA, o la declaració que no se n'ha utilitzat;
- en l'apartat 14, els enllaços a les respostes individuals;
- en l'apartat 15, la comprovació final i els ajustos pendents;
- la presentació en `docs/01-proposta/presentacio-bloc-2.pdf`.

Comproveu que els enllaços funcionen i que el PDF s'obri des del repositori. Quan s'hagen incorporat els ajustos acordats, la versió revisada quedarà identificada com `dossier-1-v1.0`.
