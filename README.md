Félix Arcand | Hiver 2026 TIM

## Analyse générale de la maquette
La maquette présente une page complète pour un centre d’escalade.
Elle est structurée en 9 sections principales :
-  le Header qui contient: ( logo compagnie, non compagnie, options de nagivations et bouton d'inscriptions)
- Hero (essentiellement page d'aceuil attrayante)
- À propos (mini phrase explicative, leur missions et leur croyances) 
- Services 
- Horaires
- Témoignages
- Tarification
- Contact
- Footer ( options de navigations (en row) presque similaire au header), et button d'inscriptions + obtentions passe) 
La mise en page utilise principalement Flexbox pour organiser les éléments en lignes et en colonnes.
Les espacements sont constants et la hiérarchie typographique est claire (titres, sous‑titres, paragraphes).
La palette de couleurs est simple : bleu foncé, blanc, orange.
___
## Variables CSS prévues
Je vais créer un système de variables pour :
#### Couleurs
- --color-primary (bleu foncé) (#2C5273)
- --color-accent (vert foncé) (#074714)
- --color-light (noir) (#000000)
- --color-muted (gris clair) (#9E9E9E)
#### Typographie
- Overcame demo, 60px,titre
- Sporteria,20px,sous titre
- Sporteria,14px,texte
#### Espacements
- space-8
- space-16
- space-24
- space-32
___

## Les composantes identfiés dans la maquette
La maquette contient plusieurs composants réutilisables :
- Boutons (CTA)
- Cartes de services
- Cartes de tarification
- Blocs “À propos”
- Navigation du header
- Formulaire de contact
- Section de témoignages
Je vais les coder de manière modulaire pour faciliter la maintenance.
___
## Ma structure HTML prévue
header: options du site (navgiations) + inscriptions   header

main

  section "hero"section
  
  section "à propos"section
  
  section "les services"section
  
  section  "les horaires"section
  
  section  "les temoignages"section
  
  section "tarifs" section

main

footer coordonées de l'entreprise footer
___
## Mon Plan d’intégration

- Créer la structure HTML complète
- Définir les variables CSS
- Intégrer le header
- Intégrer le hero
- Intégrer les sections une par une
- Ajuster les espacements et alignements
- Ajouter la responsivité
- Finaliser les détails visuels


