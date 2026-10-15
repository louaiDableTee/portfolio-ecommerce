# Checklist avant publication

**Ne pas fusionner dans `main` tant que toutes les cases ne sont pas cochées.**

Cette liste reprend chaque affirmation écrite comme « fait » qui vient de la section 6B du brief (les tâches en cours de finition). Pour chaque point : la page où il apparaît, la clé du texte, et la ligne exacte dans `content/fr.json` et `content/en.json`. Coche une case seulement quand c’est vraiment fait sur la boutique. Si un point ne sera pas fait, supprime ou réécris le texte aux lignes indiquées.

Les numéros de ligne correspondent à la version de ce commit ; si les fichiers de contenu changent, cherche la clé entre parenthèses.

## Images produits

- [x] Photos libres de droits (Unsplash, Pexels) pour les 20 produits
  - `/espace-deals/` (`s5-badge-2`) → [fr.json:260](content/fr.json#L260) · [en.json:260](content/en.json#L260)
  - `/espace-deals/` (`demo-p`) → [fr.json:111](content/fr.json#L111) · [en.json:111](content/en.json#L111)
- [x] Texte alternatif écrit pour chaque image
  - `/espace-deals/` (`s5-badge-3`) → [fr.json:261](content/fr.json#L261) · [en.json:261](content/en.json#L261)

## Accueil et en-tête de la boutique en français

- [x] Hero, catégories et produits mis en avant
  - `/espace-deals/` (`s6-chip-1`) → [fr.json:270](content/fr.json#L270) · [en.json:270](content/en.json#L270)
  - `/espace-deals/` (`s8-shot-home-caption`) → [fr.json:196](content/fr.json#L196) · [en.json:196](content/en.json#L196)
- [x] Barre de réassurance : paiement à la livraison, livraison 7 DT / gratuite dès 150 DT, retours
  - `/espace-deals/` (`s6-chip-1`) → [fr.json:270](content/fr.json#L270) · [en.json:270](content/en.json#L270)
  - `/espace-deals/` (`s8-shot-home-caption`) → [fr.json:196](content/fr.json#L196) · [en.json:196](content/en.json#L196)
- [x] Mon propre logo (lien Facebook retiré du site)
  - `/espace-deals/` (`s6-chip-1`) → [fr.json:270](content/fr.json#L270) · [en.json:270](content/en.json#L270)

## SEO on-page avec Rank Math

- [x] Title et meta description pour l’accueil, les 5 catégories et les 20 fiches produits, écrits depuis la sheet
  - `/espace-deals/` (`s5-chip-1`) → [fr.json:262](content/fr.json#L262) · [en.json:262](content/en.json#L262)
  - `/espace-deals/` (`s5-line`) → [fr.json:164](content/fr.json#L164) · [en.json:164](content/en.json#L164)
  - `/espace-deals/` (`s5-shot-rankmath-caption`) → [fr.json:168](content/fr.json#L168) · [en.json:168](content/en.json#L168)
- [x] Un texte d’introduction pour chaque catégorie
  - `/espace-deals/` (`s5-chip-2`) → [fr.json:263](content/fr.json#L263) · [en.json:263](content/en.json#L263)
  - `/espace-deals/` (`s8-shot-cat-caption`) → [fr.json:198](content/fr.json#L198) · [en.json:198](content/en.json#L198)
- [x] H1 et H2 propres sur chaque page
  - `/espace-deals/` (`s5-chip-3`) → [fr.json:264](content/fr.json#L264) · [en.json:264](content/en.json#L264)
- [x] Maillage interne catégories ↔ produits ↔ guide
  - `/espace-deals/` (`s5-chip-4`) → [fr.json:265](content/fr.json#L265) · [en.json:265](content/en.json#L265)
  - `/espace-deals/` (`s5-line`) → [fr.json:164](content/fr.json#L164) · [en.json:164](content/en.json#L164)
- [x] Fil d’Ariane et sitemap XML
  - `/espace-deals/` (`s5-chip-4`) → [fr.json:265](content/fr.json#L265) · [en.json:265](content/en.json#L265)
- [x] Rank Math cité dans la liste d’outils
  - `/espace-deals/` (`fact-stack-dd`) → [fr.json:107](content/fr.json#L107) · [en.json:107](content/en.json#L107)

## Données structurées

- [x] Schéma Product / Offer (JSON-LD) sur les fiches produits, validé dans le test des résultats enrichis
  - `/espace-deals/` (`s5-chip-5`) → [fr.json:266](content/fr.json#L266) · [en.json:266](content/en.json#L266)
  - `/espace-deals/` (`s5-shot-rich-caption`) → [fr.json:170](content/fr.json#L170) · [en.json:170](content/en.json#L170)

## Suivi GA4 + Google Tag Manager (GTM4WP)

- [x] Événements view_item_list, view_item, add_to_cart, begin_checkout, purchase (aussi en dur dans `templates/espace-deals.html`, bloc `.funnel`)
  - `/espace-deals/` (`s7-line`) → [fr.json:182](content/fr.json#L182) · [en.json:182](content/en.json#L182)
  - `/espace-deals/` (`s7-shot-ga4-caption`) → [fr.json:191](content/fr.json#L191) · [en.json:191](content/en.json#L191)
- [x] Vérifiés dans l’Aperçu GTM et GA4 DebugView
  - `/espace-deals/` (`s7-checked`) → [fr.json:189](content/fr.json#L189) · [en.json:189](content/en.json#L189)
- [x] GTM4WP / GA4 cités dans les outils
  - `/` (`hero-pills`) → [fr.json:42](content/fr.json#L42) · [en.json:42](content/en.json#L42)

## Test

- [x] Commande test complète avec paiement à la livraison, de la fiche produit à la confirmation
  - `/espace-deals/` (`s6-chip-4`) → [fr.json:273](content/fr.json#L273) · [en.json:273](content/en.json#L273)
  - `/espace-deals/` (`s6-shot-order-caption`) → [fr.json:179](content/fr.json#L179) · [en.json:179](content/en.json#L179)

## Démo locale : affirmations alignées (fait le 8 oct. 2026)

- [x] Ligne « Boutique / espacedeals.com [À COMPLÉTER : lien] » retirée de la fiche d’infos
  - `/espace-deals/` (`fact-period-dd`) → [fr.json:103](content/fr.json#L103) · [en.json:103](content/en.json#L103)
- [x] « Mise en ligne prévue » au lieu de « puis mise en ligne »
- [x] « 26 pages au plan » (le guide n’est plus marqué « prévu » depuis le 9 oct.)
  - `/` (`case-fig-pages`) → [fr.json:50](content/fr.json#L50) · [en.json:50](content/en.json#L50)
  - `/espace-deals/` (`s3-h2`) → [fr.json:140](content/fr.json#L140) · [en.json:140](content/en.json#L140)
  - `/espace-deals/` (`s3-line`) → [fr.json:141](content/fr.json#L141) · [en.json:141](content/en.json#L141)
  - `/espace-deals/` (`s3-fig-guide`) → [fr.json:144](content/fr.json#L144) · [en.json:144](content/en.json#L144)
  - `/espace-deals/` (`s3-tree-guide`) → [fr.json:154](content/fr.json#L154) · [en.json:154](content/en.json#L154)
- [x] Politique de confidentialité et lien Facebook retirés de la section 06
  - `/espace-deals/` (`s6-chip-1`) → [fr.json:270](content/fr.json#L270) · [en.json:270](content/en.json#L270)
  - `/espace-deals/` (`s6-chip-2`) → [fr.json:271](content/fr.json#L271) · [en.json:271](content/en.json#L271)
- [x] Paragraphes Search Console et Meta retirés de la section 07, captures 10 et 12 retirées de la page
  - `/espace-deals/` (`s7-checked`) → [fr.json:189](content/fr.json#L189) · [en.json:189](content/en.json#L189)
  - `/espace-deals/` (`toc-7`) → [fr.json:119](content/fr.json#L119) · [en.json:119](content/en.json#L119)
- [x] Search Console et Meta for WooCommerce présentés comme étapes suivantes
  - `/espace-deals/` (`s9-next-1`) → [fr.json:209](content/fr.json#L209) · [en.json:209](content/en.json#L209)
  - `/espace-deals/` (`s9-next-2`) → [fr.json:210](content/fr.json#L210) · [en.json:210](content/en.json#L210)
- [x] Suivi sur l’accueil : GA4 via GTM, vérifié dans DebugView ; Search Console rattaché à Worku
- [x] Outils : Search Console et Meta for WooCommerce retirés des outils Espace Deals

## Captures d’écran

- [x] Captures 01 à 06 dans `public/espacedeals/` (vraies captures, 1600×1000) : `01-accueil`, `02-categorie`, `03-fiche-produit`, `04-sheet-mots-cles`, `05-import-csv`, `06-livraison-paiement`.
- [x] Captures 07, 08, 09 et 11 dans `public/espacedeals/` (vraies captures, 1600×1000) : `07-rank-math`, `08-rich-results`, `09-ga4-debugview`, `11-commande-test`.
- [x] Captures 10 et 12 retirées de la page tant que la boutique n’est pas en ligne (les fichiers restent dans `public/espacedeals/`).

## Pages Worku et UX/UI (ajoutées le 8 oct. 2026)

À confirmer avant publication : chaque affirmation doit pouvoir s’expliquer en entretien.

- [ ] `/worku/` : fichier Google Sheets de plus de 200 prospects. La capture réelle `public/images/proof/prospect-sheet.webp` remplace l’ancien tableau fictif ; noms et liens floutés (à revérifier avant publication).
- [ ] `/worku/` : enrichissement des contacts avec Worku, FullEnrich, Prospeo et ContactOut ; messages et relances rédigés par moi.
- [ ] `/worku/` : phrase « maquettes et code produits avec Claude Code et Claude Design sous ma direction ; chaque changement vérifié avant mise en ligne ».
- [ ] `/worku/` : environ 9 posts LinkedIn entre février et juillet 2026, en organique uniquement ; les 3 captures de posts sont publiables.
- [ ] `/worku/` et `/ux-ui/` : les captures « live » de worku.tn (accueil, recrutement, prospection commerciale) correspondent encore au site en ligne.
- [x] Aucune hausse de trafic ou de conversion revendiquée ; bloc « calendrier » retiré. Depuis le 15 oct. : « 50 → 540 abonnés, en organique » et la capture `linkedin-company-page-540-followers.webp` sont sur `/worku/` (chiffre confirmé par l’auteur).
- [x] Puces techniques retirées de l’accueil et de À propos (robots.txt, redirections 301, types JSON-LD) ; capture Schema Markup Validator retirée.
- [x] Section « Design system » retirée de `/ux-ui/` ; bloc TANIT WEB retiré.
- [x] « Excel » ajouté aux outils (À propos) ; retiré de la liste le 15 oct. (la rangée de logos de l’accueil et de À propos ne le contient pas).

## Ajouts du 9 oct. 2026

- [x] Article de guide en ligne sur la boutique locale : « Comment choisir sa planche à découper » (environ 980 mots), relié à la catégorie Planches à découper. Capture `13-guide`.
- [x] Gestion des commandes : confirmation par téléphone avant l’envoi, statuts, notes internes et note client. Capture `14-commande-retour` (commande test n° 1279).
- [x] Retour sous 7 jours : remboursement du produit, remise en stock, motif noté dans la commande.
- [x] Exercice Amazon : 3 produits réécrits au format Amazon.fr, longueurs contrôlées par formule, pas de compte vendeur. Capture `15-fiches-amazon`.
- [x] Rapport KPI sur le compte de démonstration public GA4 (Google Merchandise Store, pas Espace Deals), 4 actions proposées. Captures `16-rapport-kpi` et `17-rapport-kpi-actions`.
- [x] Ligne « Lecture des KPI e-commerce » ajoutée à la carte Suivi de l’accueil.

## Ajouts du 10 oct. 2026

- [x] Accueil : une ligne d’intro et 5 étiquettes dans le hero (version du 15 oct.).
- [x] À propos : « faire tourner une boutique » remplacé par « une boutique WooCommerce complète, construite et configurée de A à Z ». Plus aucune occurrence de « faire tourner » / « run a store ».
- [x] Étude de cas : l’encadré « En 30 secondes » a été retiré le 15 oct. (la vidéo est dans le hero).
- [ ] Section 08 : 4 modèles de messages clients (confirmation, retard, client injoignable, retour) — à confirmer : rédigés par moi pour la boutique de démonstration.
- [x] Contact : adresse e-mail visible dans le bloc bleu (lien mailto) ; déjà visible dans le pied de page de toutes les pages.

## Ajouts du 11 oct. 2026

- [x] Vidéo du parcours de commande (boutique de démonstration) dans le hero de l’étude de cas (`id="demo-video"`) : `espace-deals-parcours.mp4` (2,3 Mo, 1 min 14, sans son) et son poster ; lien de retour depuis la section 08.
- [ ] Vérifier la lecture de la vidéo sur la preview Vercel, sur ordinateur et sur téléphone.

## Passe « visual-first » du 15 oct. 2026

À relire sur la preview avant fusion :

- [ ] Accueil : le clip du hero est un extrait de `espace-deals-parcours.mp4` (WebM + MP4, sans son, boucle, arrêt avec « réduire les animations »). Le portrait est passé dans le hero de À propos.
- [ ] Accueil : la rangée de logos (WordPress, WooCommerce, Kadence, LocalWP, Rank Math, Google Sheets, Google Tag Manager, Google Analytics 4) correspond aux outils réellement utilisés.
- [ ] Accueil : la carte UX/UI montre des écrans FrostPeak et renvoie vers `/frostpeak/`.
- [ ] Étude de cas : chronologie de commande limitée aux statuts visibles sur la capture 14 (commande reçue, confirmée par téléphone, livrée et payée, Terminée, retour accepté, remboursée et remise en stock).
- [ ] Étude de cas : « La boutique, côté client » est maintenant la section 01 ; sections renumérotées ; menu latéral fixe seulement à partir de 1440 px.
- [ ] Étude de cas : annotations de la fiche produit (fil d’Ariane, H1, prix en DT, description courte) bien placées sur `03-fiche-produit.webp`.
- [ ] Worku : « vidéos, carrousels et formats variés réalisés avec Canva et Claude Design » et « 50 → 540 abonnés, en organique » (confirmés par l’auteur). Section « Deux acheteurs » fusionnée dans le bloc avant/après.
- [ ] À propos : titre de l’onglet « À propos : parcours et formation » (sans « CV »), EN « About: career and education ».

## À faire

- [ ] Nouveau CV en français (`public/cv/Mohamed-Louai-Bouraoui-CV-FR.pdf`) : l’actuel présente encore un profil Worku / B2B.
- [ ] CV en anglais : ajouter le PDF dans `public/cv/`, puis le mettre en premier dans la liste anglaise de `vite.config.ts` (en attendant, les pages anglaises pointent vers le CV français).
- [ ] Page Politique de confidentialité de la boutique.
- [ ] Quand la boutique sera en ligne : captures `10-search-console` et `12-catalogue-meta`, les remettre dans la section 07 avec leur texte.

## Autres `[À COMPLÉTER]`

- [x] Plus aucun `[À COMPLÉTER` dans `content/fr.json` et `content/en.json` (`grep -n "À COMPLÉTER" content/*.json`).
