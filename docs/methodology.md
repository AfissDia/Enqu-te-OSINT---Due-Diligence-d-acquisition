# Méthodologie OSINT

## Principe
L'enquête utilise uniquement des informations publiquement accessibles et des techniques passives ou non intrusives. Aucune exploitation de vulnérabilité, authentification forcée, phishing ou ingénierie sociale active n'est réalisée.

## Processus
1. Définir le périmètre et les hypothèses.
2. Identifier les sources pertinentes.
3. Collecter les informations.
4. Recouper les éléments avec au moins une source indépendante lorsque possible.
5. Enregistrer les preuves et la date de collecte.
6. Évaluer le niveau de confiance.
7. Évaluer probabilité et impact.
8. Documenter immédiatement le résultat dans la timeline et le rapport.

## Axes d'analyse
- identité et historique de l'entreprise ;
- dirigeants et actionnariat ;
- contentieux ;
- exposition cyber ;
- fuites et dépôts publics ;
- typosquatting ;
- conformité apparente RGPD / NIS2 ;
- réputation et signaux faibles.

## Échelle de confiance
- Faible : source unique ou peu vérifiable.
- Moyen : élément plausible et partiellement corroboré.
- Élevé : preuve directe ou plusieurs sources cohérentes.

## Échelle de risque
Probabilité : 1 à 5
Impact : 1 à 5
Score = Probabilité × Impact

- 1–4 : Faible
- 5–9 : Modéré
- 10–14 : Élevé
- 15–25 : Critique

## Traçabilité
Chaque recherche significative est inscrite dans `investigation/timeline.csv`. Chaque source est référencée dans `investigation/sources.csv`. Chaque risque confirmé ou suffisamment crédible est enregistré dans `investigation/findings.csv`.
