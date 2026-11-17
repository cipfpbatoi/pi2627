# Recurs integrat. Arquitectura i alternatives tecnològiques

!!! info "Integrat en la sessió 2"

    Useu esta guia durant la segona sessió per justificar una decisió i definir el cas de validació tècnica que s'executarà en un bloc posterior. No és una sessió addicional.

## Objectiu

Proposareu una arquitectura preliminar i comparareu alternatives segons les necessitats, els riscos i els recursos del projecte.

## Organització

| Activitat | Temps |
| --- | ---: |
| Restriccions i preguntes | 25 min |
| Diagrama de context | 35 min |
| Alternatives | 50 min |
| Cas de validació futura | 50 min |
| Decisió i revisió individual | 20 min |

## Arquitectura mínima explicable

Prepareu un diagrama que mostre persones o sistemes externs, components propis, dades i comunicacions. Per cada component responeu: quina necessitat cobrix, qui el manté, de què depén i què passa si falla?

No incorporeu serveis, contenidors, frameworks o capes sense una raó vinculada als requisits.

Enllaceu el diagrama des de l'**apartat 9** del dossier i completeu allí una fila per component o integració amb `Component/integració`, `Necessitat coberta`, `Responsabilitat`, `Dependència` i `Fallada o risc`. Completeu també, en el mateix apartat, la matriu d'integració dels mínims dels mòduls.

## Comparar alternatives

Compareu almenys una decisió rellevant —arquitectura, persistència, autenticació, integració, allotjament o tecnologia d'interfície— i definiu el cas amb què es validarà més avant el risc tècnic principal. Incloeu dades inicials, acció, resultat esperat, evidència, bloc d'execució i alternativa si falla. En esta fase no programeu ni executeu el cas.

Useu una fila de l'**apartat 10** per cada decisió. En `Alternatives`, identifiqueu les opcions comparades; en `Criteris i evidències`, contrasteu adequació, experiència i suport, cost, risc i resultat esperat del cas de validació quan siga aplicable. No creeu una segona matriu de comparació dins del dossier.

## Registre de decisió

Completeu la mateixa fila de l'**apartat 10** amb `Decisió`, `Alternatives`, `Criteris i evidències`, `Opció`, `Conseqüències` i `Condició de revisió`. Enllaceu des d'eixa fila el cas de validació futura i actualitzeu els apartats 12 i 13. No el presenteu com una prova executada.

Cada membre haurà de poder explicar el diagrama global i defensar una decisió o una objecció pròpia.

## Evidència curricular

La sessió aporta evidència **parcial** de RA2.b, RA2.c, RA2.e i RA2.i. L'arquitectura és preliminar i podrà canviar després de planificar o provar.
