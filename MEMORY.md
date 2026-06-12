# MEMORY - Projet DOMOYA

## 📋 Informations Clés
- **Nom du Projet :** DOMOYA
- **Secteur :** PropTech / Smart Housing & Green Tech (Bénin)
- **Fondateur :** Jesugo Abel DOTONOU
- **Enregistrement :** RCCM : RB/COT/25 A 109655

## 🎯 Décisions Stratégiques & Financement
- **2026-06-07 (Areti Fund - Volet Éclosion) :**
  - **Dossier de candidature réajusté :** Adaptation du budget pour respecter le plafond de **5 000 000 FCFA** imposé pour l'appel à projets "Éclosion" (prototypage et amorçage).
  - **Structure financière validée :**
    - Budget total de cette phase : 6 250 000 FCFA.
    - Apport Areti Fund sollicité : 5 000 000 FCFA (seuil max autorisé).
    - Apport personnel (fondateur) : 1 250 000 FCFA (fonds propres/R&D).
  - **Horizon du partenariat :** Sélection de la durée **3 à 5 ans** pour couvrir le développement du MVP, le lancement des premiers pilotes et le passage à l'échelle commerciale stable.
- **2026-06-10 (FCI4Africa Open Call 1 - DOMOYA-Agri IoT) :**
  - **Pivot thématique :** Proposition d'adaptation de la solution IoT de DOMOYA (ESP32 / Django) pour le monitoring intelligent des conditions de stockage post-récolte des grains (température, humidité, CO2) pour prévenir l'aflatoxine (Use Case 1 / Challenge 1 & 5).
  - **Budget préparé :** Dossier de subvention complet de **50 000 €** (100% de financement sans cofinancement exigé) : 34 000 € personnel (17 PM), 4 000 € sous-traitance (analyses de grains), 2 500 € déplacements, 3 000 € consommables matériels, 6 500 € coûts indirects. 8% alloués à la dissémination.
  - **TRL visé :** Passage de TRL 3-4 à TRL 6 sur une période de 12 mois (Novembre 2026 - Octobre 2027).
- **2026-06-12 (iF Social Impact Prize 2026) :**
  - **Statut :** Clôture du Tour 1 le 20 mai 2026. Candidature axée sur le Smart Housing bioclimatique (BTSC) et le Kit IoT DOMOYA (ODD 7 & 11).
  - **Prochaine étape :** Suivi des résultats du Tour 1 et préparation potentielle du Tour 2 (Novembre 2026) en cas de non-sélection.
  - **Sélecteur de langue :** Remplacé par une expérience utilisateur unifiée et exclusive en anglais (100% EN) sur index.html et demo.html pour répondre sans ambiguïté aux exigences du jury international de l'iF Design.
  - **Suppression des mentions de prix :** Toutes les références textuelles et visuelles au "iF Social Impact Prize" (badges nominatifs et mentions de pied de page) ont été retirées pour assurer une neutralité totale dans la présentation finale.
  - **Esthétique & Animations (Module FEA) :**
    - Intégration de **Three.js** dans la landing page pour un rendu 3D procédural et interactif de la structure de la villa (réactive au mouvement de la souris/parallaxe).
    - Intégration de **GSAP & ScrollTrigger** pour le séquençage fluide des animations d'entrée et d'affichage.
    - Déploiement de **Lenis** pour un défilement physique et fluide (smooth scroll) de niveau premium.
  - **Livrables :**
    - Traduction en anglais de la présentation PDF du projet (`Presentation_DOMOYA_EN.pdf`) générée via un script ReportLab automatisé (`generate_presentation_pdf_en.py`) pour soumission internationale.
    - Reconstruction de A à Z en anglais de la landing page ([index.html](file:///C:/Users/original/Desktop/UNIR/OIF_CAP_INNOVANT/index.html)) avec Three.js 3D, GSAP et calculateur de ROI (sans aucune mention du prix iF).
    - Reconstruction de A à Z en anglais du tableau de bord IoT interactif ([demo.html](file:///C:/Users/original/Desktop/UNIR/OIF_CAP_INNOVANT/demo.html)) avec plan d'architecture interactif en SVG cliquable, Chart.js et simulateur FedaPay.
    - Sauvegarde des anciennes versions hybrides françaises sous `index_v1.html` et `demo_v1.html` pour référence.
- **2026-06-12 (Internationalisation & SEO) :**
  - **Localisation en anglais :** Traduction intégrale de `index.html` vers `index_en.html` et de `demo.html` vers `demo_en.html`.
  - **Sélecteur de langue :** Intégration d'un sélecteur de langue discret (FR | EN) en mode glassmorphism dans la barre de navigation et le tableau de bord pour une bascule fluide.
  - **Vérification technique :** Maintien de 100% des styles, animations GSAP, et interactions dynamiques JS. Tous les liens croisés et balises SEO ont été adaptés pour cibler les bonnes versions linguistiques.

  - **Livrables :**
    - Traduction en anglais de la présentation PDF du projet (`Presentation_DOMOYA_EN.pdf`) générée via un script ReportLab automatisé (`generate_presentation_pdf_en.py`) pour soumission internationale.
    - Restructuration et traduction intégrale en anglais de la landing page ([index.html](file:///C:/Users/original/Desktop/UNIR/OIF_CAP_INNOVANT/index.html)) et du dashboard ([demo.html](file:///C:/Users/original/Desktop/UNIR/OIF_CAP_INNOVANT/demo.html)) de A à Z.
    - Archivage et liaison des versions françaises sous [index_fr.html](file:///C:/Users/original/Desktop/UNIR/OIF_CAP_INNOVANT/index_fr.html) et [demo_fr.html](file:///C:/Users/original/Desktop/UNIR/OIF_CAP_INNOVANT/demo_fr.html) avec commutateur de langue fonctionnel.

- **2026-06-12 (Responsiveness & Reliability) :**
  - **Three.js WebGL Fallback :** Intégration d'une image de villa moderne (`african_modern_villa.png`) s'affichant automatiquement en cas de non-chargement ou d'erreur sur la scène WebGL de Three.js.
  - **Refonte Sidebar Mobile :** Transition de la barre latérale du dashboard vers une barre de navigation horizontale de 70px de hauteur sur les écrans de moins de 768px.
  - **Correction Scrollbars Imbriquées :** Suppression des barres de défilement multiples en désactivant le scroll de `.main-container` au profit de celui du body natif sur mobile.
  - **Optimisation Chart.js :** Raccourcissement des étiquettes et repositionnement de la légende en bas pour éviter tout chevauchement ou rognage des métriques sur petits écrans.
  - **Confidentialité & Footer :** Suppression de l'adresse e-mail personnelle du fondateur (`dotonouabel@gmail.com`) du pied de page de `index.html` pour des raisons de confidentialité et de prévention du spam.

