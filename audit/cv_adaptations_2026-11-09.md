# CV adaptés — suivi des sources et limites (09/11/2026)

## Périmètre
- Douze candidatures affichées : cinq sous « À découvrir », sept dans l'historique « Transmises via Constanza ».
- Chaque ligne pointe vers un PDF de 1 page A4 (`cv/CV_Salah_<offre>.pdf`) et sa version HTML modifiable (`cv.html?poste=<offre>`).
- Le bouton « Voir l'offre » ouvre directement la proposition dans un nouvel onglet. Pour ETLB / Côté Sushi, le lien retenu est France Travail (réf. 214YWWX), déjà testé manuellement : la page précise que l'offre est gérée par une agence France Travail et que « Postuler » ouvre directement le formulaire sur candidat.francetravail.fr après connexion. C'est un canal explicitement identifié comme gestionnaire de l'annonce, à privilégier sur un duplicata de portail commercial (sans garantie du résultat). Le lien HelloWork alternatif est conservé dans `audit/offres_2026-11-09.json`.
- Les versions PDF ont été produites via Chrome à partir du HTML générateur, à mise en page A4. Les 12 PDF ont été régénérés le 09/11/2026 après la dernière personnalisation et vérifiés comme documents d'une seule page, avec la mention « Anglais · C1 ».

## Sources utilisées
1. `proyecto_cv_salah.zip` fourni par l'utilisateur : `CV_Salah_referencia_reconstruida.pdf`, `cv_salah.html` et `README.md`. Ce dernier avertit qu'il s'agit d'une reproduction visuelle, pas de la source originale de l'outil auteur. Les coordonnées, expériences, études et dates des CV proviennent de ce document.
2. Corpus antérieur : 8 impressions PDF du portfolio Streamlit Salah (Accueil, Dashboard, Analyse, Stratégies, Projets, Formation, CV, Chatbot), vérifiées dans `Auditoria_integral_Salah_9_PDF_y_estrategia_radar_2026-11-06.md`, et un CV PDF plus récent présent dans la bibliothèque utilisateur.
3. Descriptions des douze annonces archivées dans les URL de la table, consultées pour choisir des compétences et des projets directement pertinents.

## Règles de rédaction
- L'expérience professionnelle Aplus est distincte des projets personnels ou pédagogiques. Son `+30 %` de reporting est un chiffre fourni par le CV, sans audit indépendant.
- L'expérience Comexposium est distincte des projets de portfolio. Son `−40 %` de temps de traitement est également une déclaration du CV.
- L'utilisateur a confirmé le 09/11/2026 que Salah est l'auteur principal des projets techniques du portfolio, sauf projets explicitement collaboratifs, et que les chiffres, pourcentages et résultats correspondent à ses analyses réelles. Les sept projets du portfolio sont des études de cas à partir de jeux de données et non sept missions facturées. Les chiffres d'Olist, RFM, campagnes, leads, banque et churn sont attribués aux analyses publiées, sans prétendre à un gain causé ou à un déploiement en entreprise.
- Power BI/DAX et modèle en étoile sont déclarés dans le CV du portfolio. Aucun PBIX ou référentiel de mesures DAX n'a été audité dans cette livraison.
- Les descriptions du chatbot Streamlit ne suffisent pas à confirmer un système RAG déployé et évalué ; le CV décrit un prototype présenté.
- Pas de maîtrise revendiquée de Salesforce, HubSpot, Qlik, Piano, Imagino, ASO, Meta Ads, gestion de backlog en production ou modèles ML déployés sans preuve.
- Le document original reçu mentionne anglais B2 ; le niveau C1 a été **confirmé expressément par l'utilisateur le 09/11/2026**. Les 12 versions adaptées et leurs PDF affichent donc anglais C1.
- BlaBlaCar Bus est inclus en tant qu'expérience de coordination (déc. 2025 à sept. 2026), présente dans le ZIP d'origine ; vérifier les dates avant candidature.
- TalTech est présenté de manière volontairement générale, les récits fournis du projet étant divergents.
- La disponibilité immédiate et le rythme Efrei 2 semaines entreprise / 1 semaine école proviennent du CV de référence, mais l'éligibilité propre à chaque annonce ne constitue pas une confirmation de la part de l'école.

## Risque de confidentialité
Le site GitHub Pages et le dépôt sont publics. Les PDF et pages CV exposent le nom, le téléphone, l'email et le LinkedIn de Salah, comme dans le CV communiqué. L'utilisateur a explicitement confirmé l'autorisation de publier ces coordonnées le 09/11/2026.

## Utilisation
- « PDF » : ouvre la version figée prête à relire avant envoi.
- « Éditer » : ouvre une mise en page HTML avec bouton « Modifier le texte ». Ensuite « Imprimer / enregistrer en PDF ». Les modifications au navigateur sont locales et ne mettent pas à jour le dépôt.
- Pour rendre durable un changement dans une offre, mettre à jour la fiche correspondante dans l'objet `P` de `cv.html`, re-générer le PDF et republier.

## Contrôles restants avant envoi
Le niveau d'anglais C1, l'autorisation de publication des coordonnées et l'authenticité des résultats des projets ont été confirmés par l'utilisateur. Reste à vérifier, lors de la candidature, les dates exactes, la disponibilité et les modalités académiques, ainsi que toute affirmation non corroborée par les documents. Les chiffres des stages (+30 % Aplus, −40 % Comexposium) proviennent du CV fourni et ne sont pas audités indépendamment. Ne pas promettre le succès d'une candidature : ce sont des CV ciblés, non une certification de correspondance aux exigences.

## Dernière ronde de ciblage — 09/11/2026
- Chaque poste dispose d'un titre, d'un argumentaire, d'une sélection de compétences et de trois projets adaptés à ses missions, sans inventer de responsabilités ou de logiciels non démontrés.
- Séparation stricte entre résultats réels **observés** dans les jeux de données de référence et améliorations **annoncées** dans les expériences professionnelles figurant sur le CV fourni.
- La sélection bancaire de 30 % regroupant 66 % des réponses ne constitue pas un gain causal ; la mesure de prévision Favorita de 7,5 % conserve une réserve explicite sur sa définition ; le prototype LLM ne devient pas une plateforme RAG de production.
- La formation est conservée telle que déclarée dans le CV de référence : Bachelor Ingénierie Data, Marketing & IA, Efrei Paris, période 2024–2027. Pas de date d'obtention ni de diplôme supplémentaire inventé.
- Les 12 PDF, imprimés depuis `cv.html` après ciblage, sont en A4 et une page chacun. Les versions modifiables et PDF expriment anglais C1.
