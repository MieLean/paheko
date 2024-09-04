# PLAN DE TEST

Nom du projet : Paheko
Responsable des tests : Marilyn Nginn (QA)
Date : 04 septembre 2024

## INTRODUCTION
Paheko est un logiciel de gestion d'association, libre, simple et efficace, développé depuis 2012. Son but est de :
- Réduire le temps passé sur les tâches administratives
- Re-donner de l'autonomie aux adhérent.e.s dans la gestion de leurs données
- Simplifier la gestion administrative de l'association pour inciter à y participer
- Minimiser le nombre de logociels à installer et maintenir en intégrand les outils habituels

## OBJECTIFS DU PLAN DE TEST
L'objectif de ce plan de test est de définir la stratégie de test, les ressources nécessaires, les éléments à tester, et les critères pour garantir la qualité du logiciel Paheko

## PORTÉE DES TESTS
### Fonctionnalités à tester :
- Création et gestion de tâches : au niveau des membres, au niveau de la comptabilité , au niveau des cotisations
- Gestion des utilisateurs et des droits d'accès
- Interface utilisateur (UI) : navigation, responsivité, accessibilité
- Performance et stabilité de l'application sous charge

### Fonctionnalités non testées (Hors portée):
- Test de sécurité avancés

## APPROCHE DES TESTS
### Types de test :
- Tests fonctionnels : Vérifier que les fonctionnalités répondent aux exigences spécifiées
- Tests de régression : S'assurer que les nouvelles fonctionnalités n'introduisent pas de nouveaux bugs
- Tests d'interface utilisateur : Vérifier la cohérence de l'UI, son ergonomie et son accessibilité
- Tests de performance : Évaluer les temps de réponse, le comportement sous charge et l'utilisation des ressources
- Tests d'intégration : Vérifier que les différents modules et services s'intègrent bien ensemble
- Tests exploratoire

### Environnements de test:
- Local : Installation locale pour tester les développements en cours
- Production : Pour les tests post-déploiement

### Configuration matérielle requise  :
- Licence utilisée : Affero GPL v3 (basiquement identique à la GPL mais rajoute une obligation de distribuer le code pour une utilisation sur un serveur même si pas de distribution de binaire)
- Langage utilisé : PHP
- Base de donnée utilisée : SQLite 3 (3.25 et supérieur)
- Gestionnaire de versions : Fossil
- Nommage et namescpaces : PSR-4
- Convention de code : PSR-1 et PSR-2

## CALENDRIER DES TESTS

## RISQUES ET HYPOTHESES

## LIVRABLES
- Rapport de test : résultats, bugs, recommandation
- Scripts de test automatisés : Selenium (Pytest)
- Documentation des tests : cas de test, plan de test