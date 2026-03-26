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


body 



/* header */

nav 


h2 


li 


#grimper 

.img 


/* header */


/* main */

main


.hero 


.hero 


.hero__container 

.hero_titre 


.hero_soustitre 


.button 


.primary


.secondary 

.logo


p 

/* Content */


.a-propos 

.a-propos-title

.subtitle-a-propos

.list 

.row 

.article_mission

.square_mission 

.frame_mission 


.mission_title 


.mission_subtitle




.user_mission 

.circle_mission


.article_croyons



.square_croyons 


.frame_croyons 


.croyons_title 

.croyons_subtitle 


.user_croyons


.circle_mission


/* products*/

.product 


.product_container

.product > .row{
  width: 80%;
}

.product_title 

.card


 .image 


 .text_content 

 .p_product
 
 .h1_product

 /* horaires */

 .horaires 

 .subtitle_horaires




  


 .items 

 .list_horaires 



 .row_horaires 
 
.clock 

.clock_icon 


.h4

 /* vector 200 */

.vector

 /* reviews */

 .reviews 
 
 .container
 
 .card_reviews

 .user
 
 .avatar

.avatar_image

.p_reviews

/*team meet*/

.team_meet 


.avatar_team

.h2_blue

.blue_button 


-----TARIFICATION------


.tarification

.list_tarification 

.tarif_card 

.image_container

.square_statement

.frame_statement 

.p_statement 

------CONTACT-------

.contact

.row_contact 


.name

.h3_contact

.textfiled

.h4_contact


.box_send 


.send_button 

------ FOOTER ------

.footer
  

.footer_container

.cta_box

.h3_footer

.pause
#### Couleurs
- --color-primary (bleu foncé) (#2C5273)
- --color-accent (vert foncé) (#074714)
- --color-light (noir) (#000000)
- --color-muted (gris clair) (#9E9E9E)
#### Typographie
 "Montagu Slab"

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
___
## Ma structure HTML prévue
Je vais créer un système de variables BEM pour que ca soit assez repérables par section pour moi

header: options du site (navgiations) + inscriptions   heade

main

  section "hero"section
  
  section "à propos"section
  
  section "les services"section
  
  section  "les horaires"section
  
  section  "les temoignages"section
  
  section "tarifs" section

  section "contact" section
  section "footer" section (le bas de la page)

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



