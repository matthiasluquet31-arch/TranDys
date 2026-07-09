# TranDys
# TransDys

**TransDys** est un outil d'aide à la lecture destiné aux personnes dyslexiques. Il permet d'adapter automatiquement des documents Word afin de les rendre plus accessibles, en s'appuyant sur des ajustements de mise en forme reconnus pour faciliter la lecture chez les personnes dyslexiques.

## Le problème

La dyslexie touche une part importante de la population étudiante et professionnelle, rendant la lecture de documents classiques (polices standards, espacements resserrés, texte dense) plus fatigante et plus lente. Les outils existants pour adapter un document à ces besoins sont souvent manuels, fastidieux, ou nécessitent de reformater intégralement un fichier à chaque fois.

TransDys est né d'un besoin concret : automatiser cette adaptation pour que n'importe quel document Word puisse devenir lisible en quelques clics, sans compétences techniques ni retouche manuelle.

## Fonctionnalités actuelles

TransDys prend en entrée un document Word (.docx) et applique les transformations suivantes :

- **Police de caractères adaptée** — remplacement automatique par une police conçue spécifiquement pour améliorer la lisibilité chez les personnes dyslexiques (réduction des confusions de caractères comme b/d, p/q).
- **Taille de texte augmentée** — agrandissement du corps de texte pour réduire la fatigue visuelle.
- **Espacement optimisé** :
  - entre les lettres (évite l'effet de "fusion" visuelle des caractères) ;
  - entre les mots (facilite le repérage des limites de mots) ;
  - entre les paragraphes (aère la structure du document et améliore le suivi de lecture).

Le document original est conservé intact ; TransDys génère une version adaptée sans altérer le contenu ni la structure logique du fichier source.

## Pourquoi ce projet

TransDys a été développé initialement comme projet personnel, avant d'évoluer vers un outil destiné à un déploiement institutionnel plus large, dans le cadre d'un stage à l'IPSA (Institut Polytechnique des Sciences Avancées) visant à intégrer cet outil dans un usage pédagogique concret.

## Stack technique

- **Electron** — pour une application desktop multiplateforme
- **Next.js** — pour l'interface utilisateur
- **Traitement de fichiers .docx** via manipulation directe du format Office Open XML

## Roadmap

TransDys s'inscrit dans un écosystème plus large, encore en développement :

- [ ] Support des fichiers PDF
- [ ] Aperçu du document avant/après conversion
- [ ] Application de filtres de lecture personnalisés
- [ ] Intégration IA (TransIA) pour des adaptations contextuelles plus poussées, incluant la mise en évidence automatique des informations clés

## Contribuer

Ce projet est en développement actif. Les retours, suggestions et contributions sont les bienvenus — n'hésitez pas à ouvrir une issue ou une pull request.

## Licence

*(à préciser selon ton choix — MIT, GPL, etc.)*
