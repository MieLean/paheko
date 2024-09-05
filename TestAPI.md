# Test API avec Postman
[doc API REST de Paheko](https://paheko.cloud/api)

## Assurance de la qualité
Objectifs : Vérification des fonctionnalités, conformité aux exigences

## Détection de bugs et défauts

## Contribution à l'amélioration de la sécurité
Objectifs : Détecter des vulnérabilités potentielles (injections SQL, failles XSS...)

## Performance
Objectifs : Test de charge, temps de réponse...

## Expérience UI

## Contribution à l'amélioration de la Documentation
Objectifs : identification des incohérences, absence d'information, clarté et précision, observations

### 4.4.3 user/new (POST)
CTAPI-00#:
- Cas de test : utilisation du mdp "passw0rd"
- Résultat : 
```""error": "Le mot de passe choisi figure dans une liste de mots de passe compromis (piratés), il ne peut donc être utilisé ici. Si vous l'avez utilisé sur d'autres sites il est recommandé de le changer sur ces autres sites également."```
- Remarques : Message d'erreur pas assez explicite. Quelle est cette liste ? L'administrateur y a t'il accès ?

CTAPI-00#:
- Cas de test : Ajouter un nouvel utilisateur "Il est possible d'utiliser tous les champs de la fiche membre en utilisant leur clé unique, ainsi que les clés suivantes"
- Résultat : 
```{
    "error": "\"Nom & prénom\" : ce champ est requis"
}```
- Remarques : Quels sont les autres clés uniques pour compléter au format .json ?
