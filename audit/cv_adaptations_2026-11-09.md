# CV adaptés — suivi des sources et limites (09/11/2026)

## Périmètre
- Douze candidatures affichées : cinq sous « À découvrir », sept dans l'historique « Transmises via Constanza ».
- Chaque ligne pointe vers un PDF de 1 page A4 (`cv/CV_Salah_<offre>.pdf`) et sa version HTML modifiable (`cv.html?poste=<offre>`).
- Le bouton « Voir l'offre » ouvre directement la proposition dans un nouvel onglet. Pour ETLB / Côté Sushi, le lien retenu est France Travail (réf. 214YWWX), déjà testé manuellement. Le lien HelloWork alternatif est conservé dans `audit/offres_2026-11-09.json`.
- Les versions PDF ont été produites via Chrome à partir du HTML générateur, à mise en page A4. Les 12 PDF ont été vérifiés comme documents d'une seule page.

## Sources utilisées
1. `proyecto_cv_salah.zip` fourni par l'utilisateur : `CV_Salah_referencia_reconstruida.pdf`, `cv_salah.html` et `README.md`. Ce dernier avertit qu'il s'agit d'une reproduction visuelle, pas de la source originale de l'outil auteur. Les coordonnées, expériences, études et dates des CV proviennent de ce document.
2. Corpus antérieur : 8 impressions PDF du portfolio Streamlit Salah (Accueil, Dashboard, Analyse, Stratégies, Projets, Formation, CV, Chatbot), vérifiées dans `Auditoria_integral_Salah_9_PDF_y_estrategia_radar_2026-11-06.md`, et un CV PDF plus récent présent dans la bibliothèque utilisateur.
3. Descriptions des douze annonces archivées dans les URL de la table, consultées pour choisir des compétences et des projets directement pertinents.

## Règles de rédaction
- L'expérience professionnelle Aplus est distincte des projets personnels ou pédagogiques. Son `+30 %` de reporting est un chiffre fourni par le CV, sans audit indépendant.
- L'expérience Comexposium est distincte des projets de portfolio. Son `−40 %` de temps de traitement est également une déclaration du CV.
- Les sept projets du portfolio sont des études de cas à partir de jeux de données et non sept missions facturées. Les chiffres d'Olist, RFM, campagnes, leads, banque et churn sont attribués aux analyses publiées, sans prétendre à un gain causé ou à un déploiement en entreprise.
- Power BI/DAX et modèle en étoile sont déclarés dans le CV du portfolio. Aucun PBIX ou référentiel de mesures DAX n'a été audité dans cette livraison.
- Les descriptions du chatbot Streamlit ne suffisent pas à confirmer un système RAG déployé et évalué ; le CV décrit un prototype présenté.
- Pas de maîtrise revendiquée de Salesforce, HubSpot, Qlik, Piano, Imagino, ASO, Meta Ads, gestion de backlog en production ou modèles ML déployés sans preuve.
- Le document original reçu mentionne anglais B2 ; un CV plus récent porte C1. Les versions adaptées conservent prudemment B2 jusqu'à vérification personnelle.
- BlaBlaCar Bus est inclus en tant qu'expérience de coordination (déc. 2025 à sept. 2026), présente dans le ZIP d'origine ; vérifier les dates avant candidature.
- TalTech est présenté de manière volontairement générale, les récits fournis du projet étant divergents.
- La disponibilité immédiate et le rythme Efrei 2 semaines entreprise / 1 semaine école proviennent du CV de référence, mais l'éligibilité propre à chaque annonce ne constitue pas une confirmation de la part de l'école.

## Risque de confidentialité
Le site GitHub Pages et le dépôt sont publics. Les PDF et pages CV exposent le nom, le téléphone, l'email et le LinkedIn de Salah, comme dans le CV communiqué. Retirer ou rendre privés les artefacts avant toute diffusion publique non souhaitée.

## Utilisation
- « PDF » : ouvre la version figée prête à relire avant envoi.
- « Éditer » : ouvre une mise en page HTML avec bouton « Modifier le texte ». Ensuite « Imprimer / enregistrer en PDF ». Les modifications au navigateur sont locales et ne mettent pas à jour le dépôt.
- Pour rendre durable un changement dans une offre, mettre à jour la fiche correspondante dans l'objet `P` de `cv.html`, re-générer le PDF et republier.

## Contrôles restants avant envoi
Vérifier avec Salah les niveaux de langue, les dates, les certifications, la disponibilité, les valeurs des métriques de stage, et adapter une dernière fois les mots-clés à la fiche de poste actualisée. Ne pas promettre le succès d'une candidature : ce sont des CV ciblés, non une certification de correspondance aux exigences.
