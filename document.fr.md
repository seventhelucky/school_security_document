/\ [ Commandes pour scanner le système (Pour si tu pense avoir installer un virus, rootkit, etc...) ]

\ lynis
 ex: sudo lynis --quick
 ex: sudo lynis audit system

\ chkrootkit
 ex: sudo chkrootkit

\ ClamAV
 ex: sudo freshclam (à utiliser au début si possible)
 ex: sudo clamscan (Scanner tout le 'drive'? pas encore testé)
 ex: sudo clamscan -r -i DOSSIER (Pour scanner un dossier, si sa montre rien, c'est un bon signe)

\ MalDet ou LMD avec ClamAv
 ex: Le firewall de l'école m'empêche de l'installer ;P
 ex: Et torify marche pas donc je peut pas l'éviter sans utiliser un proxy 'gratuit/bourré de tracker's et de virus',
     dans un ordinateur dans le garage d'un(e) inconnu(e) a l'autre bout du monde, tu veut que je fasse confiance en LUI/ELLE? non.

\ ...

/\ [ Si tu veux scanner l'activité du système pour activité suspicieuse ]

\ vmstat
 ex: vmstat x y -S M ('x' égale le nombre de temps entre chaque analyse, et 'y' égale le nombre de fois qu'il analysera le système.
     L'option S après est pour dire que je veux les données en Megabytes, car c'est en kilobytes par défaut)

\ dstat-jamiebennett.dstat
 ex: dstat-jamiebennett.dstat (je connais pas les options et je veux pas chercher)

\ ...

/\ [ Conseil pour être plus comfortables avec les commandes ]

\ Appuyer sur TAB pour terminer une commandes si elle est l'unique seule avec ses charactères, sinon, taper TAB deux fois pour voire les commandes trouvés qui commence
  avec les charactères que tu a de taper sur la ligne de commande.

\ Appuie sur les flèches haut et bas pour regarder ou retourner de regarder les commandes qui ont ont été tapés auparavant, pratiques.

\ Le secret pour se souvenir des commandes est pas seulement une bonne mémoire, sa vient avec la pratique, après une ou deux semaine d'utiliser Linux à la maison je me    
  souvenais de toute les commandes que j'avais besoin de me souvenir de, sa pourrait vous prendre plus ou moin de temps, mais 'rusher' pas, sa vient avec le temps.

\ ...

/\ [ Conseils pour GARDER ton ordinateur sans virus et autres... ]

\ Si'l vous plais, ne visiter de 'shady website', sa a l'air simple mais se souvenir de sa peut être très utiles, surtout vous les garçons,
  il y a un temps pour tout et l'école ne l'est probablement pas pour sa,
  les sites de 'cG9ybm8gYW5kIGRydWdz'(encrypté en 'onfr64' (trouve l'algorithme extrêmement simple pour décrypter la réponse)) est aussi 'shady', ok?

\ - [ Faites pas trop confiances aux antivirus... ] Sa s'applique partout, même sur Windows et Linux (pour de différentes raisons),
  il y une limite au pouvoir des antivirus (https://www.phonandroid.com/windows-10-11-une-faille-de-securite-permet-de-prendre-le-controle-complet-de-votre-pc.html)
  si tu ne prends pas les étapes pour ne pas avoir de virus en première place,
  tu dois qu'and même te mettres de grands défis pour te mettre en sécurité.

  - Pour linux, le problème pour les antivirus est différent,
  c'est a cause d'un concept appellée 'open-source' ou free software, ce qui permet pour TOUS le monde, y compris toi, d'aller
  fouiller dans le code source au cas ou qu'il y a un sniffer de packet ou autre codes malicieux, ce que tu ne peux pas faire dans Windows,
  ce qui crée un phénomène où une personne malicieuse cherche pour une spécifique vulnérabilité, pendant que dix autres personnes
  cherche pour cette vulnérabilité dans le code pour ne pas avoir un PC en danger,
  même situation lors qu'une vulnérabilité devient connue (Il y a des cas spéciaux par contre, [log4jay] par exemple)
  1,000 personnes malicieuses sont en train de créer du malware qui exploite ce code vulnérable
  alors que 100,000 d'utilisateur alarmées du système vulnérable cherche une solution.

  - Le kernel Linux et ses distributions connues (important) sont donc très sécurisés,
  donc il y a probablement pas besoin d'antivirus puisque environ 80% des utilisateurs
  utilise Windows, donc la vaste majorité des virus que tu poigne sur Linux vont peut être même crasher avant même de faire quoi que se soit
  puisque qu'ils était fait pour les grands parent et les normies sur Windows. ;P

  - Même si tu est assez malchanceux pour te prendre un virux pour Linux ou ta distro,
  le virus est prôbablement vieux et la vulnérabilité patché,
  même si tu te prends un 'bon' virus en allant sur le dark web ou quelque chose,
  il y a quasi-zero chance que tu the prend un qui fait plus que miner du bitcoin ou voler des mots de passes,
  et si oui, c'est plus que ca, bon bein quece que tu veux que je te dise,
  il's ont probâblement déja mis un rootkit sur ton ordi, donc réinstalle tout, et par tous,
  je veux dire TOUS, y compris le UEFI ou l'autre vieux truc si ta un plus vieux ordi,
  si tu pense que sa fait rien, t'as aucun autre chois que de le mettre dans le feux
  ou demander l'aide de professionelles, se qui pourrais couter...

  - Donc vas explorer dans les terrains battues avant d'aller dans la jungle, compris?

\ ...

/\ - Maintennant que tu t'est rendus jusqu'ici, sinon tu serais déja en train de dormir.

   - Maintennant je veux te demander une petite, petite faveur...
   Aide à rajouter des choses, si tu lis sa j'ai peut être déja terminer l'école secondaire,
   IJe vais continuer a rajouter des choses jusqu'a la par contre, donc je veut te demander d'aider si tu peut,
   peut importe a qu'el point inutile quelque chose a l'aire, tant que c'ais utile à... quelqu'un, c'est correct.

   - Github link(lien) (https://github.com/seventhelucky/school_security_document)

Et autres à venir... Si j'ai le temps.

Crédits: Seth Martin G:21 | lundi 21 mars 2022, mardi 29 mars 2022, mardi 3 mai 2022, mardi 10 mai 2022, 9 juin 2022, ...
