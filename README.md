# Bestvironment
### Répartition des taches durant notre projet. 


  Au cours de ce projet, chacune d’entre nous a endossé plusieurs rôles. L’idée nous est venue assez naturellement, car elle est étroitement liée à notre futur métier. Il nous a semblé évident d’intégrer ce projet dans notre parcours professionnel.

  Nous avons réfléchi autour du thème de l’école, en orientant notre réflexion vers le confort en classe, aussi bien pour les élèves que pour l’enseignant. C’est ainsi qu’est né notre projet : BestVironment — une combinaison des mots "best" et "environment" en anglais — qui évoque un environnement de classe plus agréable, propice au bien-être et à l’épanouissement du groupe.

Justine : J’ai réalisé une grande partie du support Canva pour les deux présentations orales, car j’étais à l’aise avec cet outil.

Inès : J’ai principalement réalisé la partie codage, car j’étais la plus à l’aise avec cet aspect technique du projet.

Sandy : J’ai trouvé le nom du projet car, selon moi, il reflète parfaitement le bon compromis que nous avons voulu atteindre avec cette idée : un environnement optimal, à la fois pour le bien-être des élèves et pour la qualité de l’enseignement.

Nous avons d’abord créé un groupe WhatsApp à trois pour partager nos idées plus facilement. Pendant les séances, nous utilisions également des feuilles de brouillon pour structurer et faire évoluer notre réflexion. Nous étions assez rapidement d’accord sur le choix du projet, ce qui a facilité le lancement du codage ainsi que la mise en place des différentes options que nous souhaitions ensuite perfectionner.

### Code utitlisés durant le projet : 

- Température
- Luminosité
- Buzzer

Nous avons donc créé et finalisé deux programmes : l’un pour mesurer la température de la salle de classe, et l’autre pour la luminosité. Cela a été rendu possible grâce au matériel fourni par notre enseignant (carte UCA, fils, breadboard, capteurs de température et de lumière), ainsi qu’aux logiciels de programmation, notamment Arduino.
nous avons ensuite rajouté le signal sonore apporté par le buzzer pour informer l'enseignant des nouvelles données. 

Nous avons veillé à ce que nos codes soient simples, à la fois visuellement et dans leur utilisation, afin de garantir une prise en main facile et intuitive.

Après plusieurs séances de codage et de nombreuses tentatives infructueuses, nous avons finalement réussi à fusionner nos deux programmes pour qu’ils fonctionnent ensemble. Nous avons également pu calibrer les réglages souhaités, et faire fonctionner notre système d’alerte : un buzzer qui émet un signal sonore pour indiquer à l’enseignant qu’il doit consulter les données envoyées par la carte.

Pour conclure, ce projet nous a permis de progresser en tant que groupe, de coopérer efficacement et de faire entendre nos idées. Nous avons parfois douté, aussi bien de notre projet que de nos compétences, mais le soutien de nos enseignantes ainsi que la solidarité au sein de notre trio nous ont permis d’aller au bout, avec un résultat concluant et satisfaisant

### Le code et les branchements :
Ici le capteur de luminosité (LTR-303A) et le capteur de température (SHTC3) sont déjà intégrés sur la carte UCA. Or si l'on connecte directement le buzzer à celle ci sans utilisé la breadboard alors le capteur de température est inibé. 
Les branchements à faire sont donc de connecter la borne + du buzzer à la borne D3 de la carte puis la borne - à la borne GND

<img width="358" alt="Capture d’écran 2025-05-27 à 18 19 06" src="https://github.com/user-attachments/assets/614740bf-256e-4fb2-b901-bd9eb0867092" />

<img width="900" alt="Capture d’écran 2025-05-27 à 20 25 14" src="https://github.com/user-attachments/assets/e5174c19-8f9d-457e-8f44-efd13455d9ed" />

