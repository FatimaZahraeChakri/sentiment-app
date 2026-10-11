## Besoin en une phrase (obligatoire)
Signaler au pharmacien toute ordonnance incomplète avant délivrance.

## Utilisateur final (obligatoire)
Le pharmacien d'officine au comptoir.

## Approche retenue (obligatoire)
Cocher une seule case :

- [x] Règles métier
- [ ] Machine learning
- [ ] RAG
- [ ] Modèle génératif seul

## Justification (obligatoire)
(a) Aucune ordonnance étiquetée n'existe au départ. (b) Le pharmacien doit pouvoir expliquer le refus au patient. (d) Une ordonnance validée à tort a une conséquence grave.

## Données nécessaires et leur origine (obligatoire)
Les règles légales et les champs présents sur le document.

## Métrique de succès et seuil d'acceptation (obligatoire)
Rappel de 1,0 sur la détection des champs manquants.

## Conséquence d'une erreur et validation humaine prévue (obligatoire)
Délivrance dangereuse, le pharmacien valide toujours manuellement.

## Risques éthiques ou de confidentialité (obligatoire)
Les données médicales sont très sensibles et confidentielles.