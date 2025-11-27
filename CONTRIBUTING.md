
# Contribution à la Théorie ZM

Merci de votre intérêt pour la Théorie ZM — votre aide accélère la science.  
Avant de contribuer, lisez attentivement ces règles : elles garantissent rigueur, reproductibilité et clarté.

## Contact
Pour toute question ou proposition directe, écrivez à : **zmtheorie@gmail.com**

## Principes généraux
- Respectez l'esprit scientifique du projet : clarté, traçabilité, reproductibilité.  
- Toute contribution doit être documentée et justifiée (message de commit + description PR).  
- Suivez les conventions de style (code Python conforme à PEP8).  
- Automatisez les tests et vérifiez localement avant soumission.

## Processus de contribution
1. **Fork** le dépôt.  
2. **Créez une branche** dédiée descriptive : `feature/nom-court` ou `fix/description-courte`.  
3. Implémentez vos changements. Ajoutez des tests unitaires pour toute nouvelle fonctionnalité ou correction.  
4. Mettez à jour la documentation (README, docs/, commentaires de code) si nécessaire.  
5. **Commits** : atomiques, lisibles, en anglais ou français selon le contexte. Format recommandé :


Exemples : `feat(fNL_ZM): add stabilized integrator` ou `fix(running_alpha): correct export path`.

6. **Rebase** sur `main` (ou `master`) si nécessaire pour garder l’historique propre.  
7. **Ouvrez une Pull Request** depuis votre branche forkée vers `main` du dépôt d’origine. Dans la PR, incluez :
- But de la modification  
- Instructions pour reproduire / exécuter  
- Résultats attendus et tests fournis  
- Tout compromis ou limitation connue

## Checklist pour la Pull Request
- [ ] Le code suit PEP8 / style du projet.  
- [ ] Tests unitaires ajoutés/actualisés et passent localement.  
- [ ] Documentation mise à jour.  
- [ ] Aucun secret (clé/API) inclus dans le commit.  
- [ ] Les fichiers volumineux générés automatiquement ne sont pas committés (voir `.gitignore`).

## Tests & CI
- Fournissez des tests simples qui démontrent la correction (pytest recommandé).  
- Les PRs doivent passer la CI (si configurée) avant merge.

## Gestion des données et fichiers lourds
- Ne commitez pas de fichiers binaires volumineux générés automatiquement.  
- Versionnez uniquement les rapports finaux, figures et PDF nécessaires pour la reproductibilité (répertoire `pdf/`).  
- Pour de gros artefacts, utilisez un stockage externe (OSF, Zenodo) et liez via DOI.

## Sécurité & confidentialité
- Ne publiez pas d’informations privées ou sensibles.  
- Si vous trouvez une vulnérabilité, contactez **zmtheorie@gmail.com** en privé et évitez de la divulguer publiquement jusqu’à correction.

## Licence
En soumettant une contribution, vous acceptez de la mettre à disposition sous la licence du projet (MIT), sauf indication contraire explicite convenue par écrit.

---

Merci encore pour votre contribution — chaque PR rapproche la Théorie ZM d’un prototype scientifique robuste.  
Pour toute aide ou discussion de fond : **zmtheorie@gmail.com**

