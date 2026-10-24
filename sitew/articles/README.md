# Deux articles SiteW — versions corrigées à relire

Préparation : 24 octobre 2026. Ces fichiers ne sont PAS publiés sur SiteW. Aucun fichier llms n'est modifié.

## Fichiers
- obligation-cac-petits-groupes-body.html : corps complet de remplacement.
- obligation-cac-petits-groupes-head-jsonld.html : données structurées de remplacement.
- cac-ad-hoc-startup-body.html : corps complet de remplacement, recentré sur les informations vérifiables.
- cac-ad-hoc-startup-head-jsonld.html : données structurées de remplacement.

## Périmètre et corrections
Petits groupes : seuils actualisés, exemple corrigé (F2 ne franchit aucun seuil), distinction NEP 911 (trois exercices) / NEP 912 (six exercices), suppression de promesses commerciales non confirmées et d'affirmations générales de nullité.
CAC ad hoc : ImageObject autonome et référence primaryImageOfPage résoluble. Retrait des références jurisprudentielles non contrôlées, des numéros de normes non vérifiés pour ces missions et des généralisations concernant toutes les levées de fonds, les incompatibilités, les dépôts et les délais. Cette version est volontairement plus concise que le modèle du projet et doit être validée par le responsable éditorial/juridique.
Le slug CAC ad hoc et son image proviennent du gabarit du projet : vérifier URL canonique et accessibilité de cette image sur le site avant intégration.

## Réglages SiteW
Conserver les URL existantes. Le module Blog fournit un seul H1 ; coller le corps HTML avec H2/H3 dans les blocs adaptés. Hériter de la typographie et des couleurs du site, sans CSS global. Ne pas réimporter une image différente.

Titre SEO petits groupes : CAC petits groupes : seuils et obligations des filiales
Description : Holding et filiales : seuils de nomination du CAC, calcul du périmètre, calendrier et distinction entre NEP 911 et NEP 912.
Titre SEO startup : Commissaire ad hoc startup : actif, passif et levée de fonds
Description : Quand une startup doit-elle faire vérifier son actif et son passif ? Émission d'obligations, documents à préparer et mission du commissaire ad hoc.

Les JSON-LD ne contiennent pas de dateModified anticipée : ajouter datePublished originale et dateModified effective lors de la publication, au format ISO 8601. Si un auteur personne physique est crédité visiblement et validé, remplacer l'auteur Organization par cette Person. Les dimensions d'image et le logo sont omis faute de vérification technique actuelle.
Ne pas superposer ce graphe à des données structurées automatiques contradictoires de SiteW : inspecter le HTML final et remplacer/compléter en conséquence. Vérifier si le champ SiteW attend du JSON seul ou un bloc script avant collage.

## Pas de promesse SEO ou IA
HowTo ne produit plus de résultat enrichi Google depuis 2023. La documentation Google annonce aussi la disparition des résultats enrichis FAQ en 2026. Une FAQ visible reste utile aux lecteurs ; son balisage n'est pas une promesse de visibilité. Aucun gain de classement, d'indexation ou de citation par une IA n'est garanti. llms.txt n'est pas une condition d'indexation Google.

## Contrôles avant publication
1. Relecture juridique et validation des périmètres internationaux.
2. Vérifier les liens, les images et les canoniques.
3. Conserver les dates historiques ; ajouter les dates de modification effectives.
4. Vérifier un seul H1, le rendu mobile et les tableaux.
5. Contrôler le JSON-LD dans Schema Markup Validator ; utiliser Rich Results Test pour les fonctionnalités Google prises en charge.
6. Publier manuellement dans SiteW, puis inspecter les URL dans Search Console. Ne pas utiliser l'Indexing API réservée à certains types de contenus pour ces articles.

## Sources
- https://entreprendre.service-public.gouv.fr/vosdroits/F31440
- https://h2a-france.org/publications/nep-911-et-912-nouveaux-seuils-definis-par-decret-du-28-fevrier-2024/
- https://www.legifrance.gouv.fr/jorf/id/JORFTEXT000049209674
- https://www.legifrance.gouv.fr/codes/article_lc/LEGIARTI000034799342/
- https://developers.google.com/search/blog/2023/08/howto-faq-changes
- https://developers.google.com/search/updates
