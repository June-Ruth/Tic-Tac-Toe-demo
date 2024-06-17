# Tic-Tac-Toe

## Instructions
Création d'une pipeline CI/CD à des fins de démonstration.

### Fréquence
- La pipeline doit pouvoir être exécutée manuellement
- La pipeline doit être exécutée à chaque action de push et de merge request

### Contenu
- La pipeline doit exécuter les tests
- Le stage de test doit mentionner le type de tests exéutés selon la pyramide des tests (soit dans son nom, soit dans la console lors de l'exécution)
- La pipeline doit fournir un rapport de couverture Clover
- La pipeline doit fournir les artefacts de distribution nécessaires au déploiement

### Correction des tests
- Les tests non-validés par la pipeline doivent être corrigés afin d'être valides