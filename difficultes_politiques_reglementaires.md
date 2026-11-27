# Les difficultés du projet : politique et réglementation

Ce document reprend les deux grandes difficultés que le projet va rencontrer au Cameroun et en CEMAC. Pour chacune, on explique ce qui se passe et ce que ça change concrètement pour l'app.

---

## Partie 1 : Les difficultés politiques

**Le gros risque politique, c'est l'incertitude au sommet de l'État.** Il pèse sur le projet de cinq façons.

### 1. La succession de Paul Biya n'est pas réglée

Paul Biya a 93 ans et il est au pouvoir depuis 1982. En avril 2026, une réforme de la Constitution a recréé le poste de vice-président, mais personne n'y a encore été nommé. S'il disparaissait avant de nommer quelqu'un, le président du Sénat assurerait l'intérim, et une élection aurait lieu dans un délai de 20 à 120 jours.

Des législatives et des municipales sont aussi prévues le 7 février 2027. Le climat est déjà tendu : la présidentielle de 2025 reste contestée et un parti d'opposition vient d'être suspendu.

**Ce que ça change pour nous :**
- Quand la situation politique est incertaine, les gens gardent leur argent en liquide et les investisseurs attendent.
- On évite de lancer l'app ou de lever des fonds pendant les périodes électorales.
- On garde assez de trésorerie pour tenir plusieurs mois si l'activité ralentit.

### 2. Le pouvoir peut couper Internet

Après la présidentielle, Internet a été fortement perturbé le 23 octobre 2025. Ensuite, TikTok, Facebook, Instagram, Telegram et plusieurs VPN ont été bloqués entre le 31 octobre et le 5 novembre 2025.

**Ce que ça change pour nous :** c'est le risque qui touche le plus directement l'app.
- Il faut pouvoir cotiser par USSD ou par SMS, pas seulement par Internet.
- On ne compte pas sur WhatsApp pour les rappels de paiement.
- Le modèle ML doit repérer les jours de coupure. Sinon, un membre qui paie en retard parce que le réseau était coupé passera pour un mauvais payeur.

### 3. L'État taxe le mobile money et cherche de l'argent

Chaque transfert paie déjà une taxe de 0,2 %, plus un forfait de 4 FCFA. Or l'État est sous pression : en 2026, rembourser sa dette devrait lui coûter 43,5 % de ses recettes. Avec un tel besoin d'argent, il est tentant de relever les taxes sur le mobile money.

**Ce que ça change pour nous :**
- Une tontine, ce sont beaucoup de petits versements réguliers. Chaque hausse de taxe nous touche donc plus que les autres.
- Envoyer de l'argent vers un autre opérateur coûte beaucoup plus cher : 2 604 FCFA pour 100 000 FCFA, contre 204 FCFA en restant chez Orange.
- Le modèle économique doit tenir même si ces frais augmentent.

### 4. Placer la caisse en titres d'État, c'est prêter à cet État

Les banques camerounaises détiennent déjà 32 % de leurs actifs en titres d'État, et le FMI juge le risque de surendettement élevé.

**Ce que ça change pour nous :**
- Si on place la caisse en titres camerounais, on dépend de la santé de l'État.
- On répartit les placements entre plusieurs pays de la CEMAC.
- On garde toujours une partie de l'argent disponible tout de suite.

### 5. La BEAC contrôle de près l'argent de la diaspora

Depuis le 5 mai 2026, une instruction de la BEAC oblige à prouver que les devises sont bien arrivées dans la zone avant de verser l'argent venu de l'étranger. Les particuliers peuvent toujours recevoir leurs fonds, mais certains transferts risquent de prendre plus de temps.

**Ce que ça change pour nous :**
- Faire cotiser les Camerounais de l'étranger sera plus compliqué.
- Il nous faut un établissement de paiement agréé comme partenaire.
- On prévient les membres que l'argent venu de l'étranger peut arriver avec du retard.

### Ce qu'il faut retenir

Le pouvoir n'a aucune raison de s'opposer au projet. Le danger vient des crises qui peuvent frapper l'app de côté : une coupure d'Internet, une nouvelle taxe, une période d'instabilité. Une app qui marche sans Internet, qui place l'argent dans plusieurs pays et qui reste neutre politiquement peut traverser tout ça.

---

## Partie 2 : Les difficultés réglementaires

**La règle à retenir : dès que l'app garde l'argent de la caisse, elle fait un métier réglementé.** Tant qu'elle se contente d'organiser la tontine, les contraintes restent légères. Chaque nouveau service demande une nouvelle autorisation, et donc plus de capital.

### 1. Garder l'argent de la caisse demande un agrément

En CEMAC, seuls une banque, un établissement de microfinance (EMF) ou un établissement de paiement agréé peuvent émettre de la monnaie électronique et proposer des services de paiement. L'agrément est donné par le ministre des Finances, après un avis favorable de la COBAC.

Pour un établissement de paiement, il faut une société anonyme et au moins 500 millions FCFA de capital. Un rapport de 2026 parle plutôt de 4 milliards FCFA, donc le chiffre exact reste à confirmer auprès de la COBAC. Autre point important : collecter l'épargne du public sans être un EMF agréé de 2e catégorie est illégal.

**Ce que ça change pour nous :**
- Au lancement, l'argent ne passe jamais par nos propres comptes.
- Il circule sur les comptes d'un partenaire agréé (Orange Money, MTN ou un EMF).
- L'app fournit le logiciel et organise la tontine, rien de plus.

### 2. Avancer la caisse, c'est faire un crédit

Prêter sans collecter d'épargne demande un EMF de 3e catégorie, avec 150 millions FCFA de capital. Collecter l'épargne et prêter demande la 2e catégorie, avec 300 millions FCFA.

Le taux d'usure est plafonné. La BEAC le fixe chaque trimestre, pays par pays. Un prêt au dessus de ce plafond peut coûter de 1 à 6 mois de prison et jusqu'à 100 millions FCFA d'amende. Les frais comptent dans le calcul, pas seulement le taux.

**Ce que ça change pour nous :**
- Une avance de caisse facturée est un prêt aux yeux de la loi.
- Le modèle de score peut fixer le prix, mais jamais au dessus du plafond.
- La COBAC prépare de nouvelles règles pour les EMF : suivi quotidien de la trésorerie et tests de résistance. Notre modèle de prévision de la caisse nous aidera directement à les respecter.

### 3. Créer nos propres fonds demande une société à part

La société de gestion doit être une société anonyme basée en CEMAC, avec 300 millions FCFA de capital versés en entier. Sa seule activité doit être la gestion de fonds. Une fois le dossier complet, la COSUMAF a 60 jours pour répondre.

**Ce que ça change pour nous :** les fonds ne pourront pas être gérés par la même société que l'app. Il faudra une filiale, avec ses propres dirigeants agréés et son propre capital.

### 4. Nos données et notre ML sont encadrés par la loi

La loi camerounaise sur les données personnelles s'applique pleinement depuis le 23 juin 2026. Elle impose un délégué à la protection des données quand on traite beaucoup de données. Elle met aussi des conditions aux transferts hors du Cameroun, parfois avec une autorisation préalable. Les amendes peuvent aller jusqu'à 1 milliard FCFA.

L'autorité de contrôle n'était pas encore en place en juillet 2026, mais un membre peut déjà porter plainte en s'appuyant sur la loi. Il n'existe pas encore de loi spécifique à l'IA, donc le score de crédit reste dans une zone floue.

**Ce que ça change pour nous :**
- Des serveurs en Europe (AWS par exemple) veulent dire un transfert de données hors du pays.
- Il faut demander clairement l'accord de chaque membre avant d'utiliser ses données pour le score.
- Le mieux est de prévoir tout ça dès la conception de l'app.

### 5. La liste grise du GAFI rend les partenaires plus prudents

Le 30 octobre 2026, le Cameroun était toujours sur la liste grise, avec tous ses délais dépassés. Le GAFI lui demande justement de mieux contrôler les institutions financières non bancaires.

**Ce que ça change pour nous :**
- Les banques et les opérateurs exigeront une vérification d'identité sérieuse pour chaque membre, diaspora comprise.
- L'inscription sera plus longue et coûtera plus cher.
- Certains partenaires risquent d'hésiter à travailler avec une jeune start-up.

### 6. Les établissements de paiement s'arrêtent aux frontières de la CEMAC

Le règlement limite leurs services à l'intérieur de la zone.

**Ce que ça change pour nous :** même avec notre propre agrément, l'argent de la diaspora devra passer par une société de transfert agréée.

### Une bonne nouvelle pour 2027

Une réforme des services de paiement doit entrer en vigueur le 1er janvier 2027. Elle crée une catégorie légère pour les acteurs qui lancent des paiements sans garder l'argent des clients : une simple autorisation de la COBAC suffira, sans agrément complet. Elle prévoit aussi un bac à sable, pour tester une solution pendant 12 mois (renouvelables une fois) avec des règles assouplies et des montants plafonnés.

Attention, le texte n'est encore qu'un projet. Lors de la Cameroon Fintech Week de novembre 2026, le secteur réclamait toujours ce bac à sable.

**Ce que ça change pour nous :** une app de tontine qui déclenche les paiements sans garder l'argent pourrait entrer dans cette catégorie. Ce serait la façon la moins chère de démarrer, et ça vaut le coup de préparer un dossier dès 2027.

### Les autorisations, étape par étape

| Étape | Autorisation | Capital minimum | Qui décide |
|---|---|---|---|
| Lancement | Aucune, l'argent passe par un partenaire | Aucun | Le contrat avec le partenaire |
| Paiements sans garder l'argent (dès 2027 si la réforme passe) | Autorisation | À préciser | COBAC |
| Avances et petits prêts | EMF 3e catégorie | 150 M FCFA | MINFI après avis COBAC |
| Épargne et crédit | EMF 2e catégorie | 300 M FCFA | MINFI après avis COBAC |
| Nos propres fonds | Société de gestion | 300 M FCFA | COSUMAF |

### Ce qu'il faut retenir

Pour garder un démarrage léger : l'argent reste chez un partenaire agréé, la loi sur les données est respectée dès le départ, et on vise la réforme de 2027. Les licences viennent ensuite une par une, quand le volume d'activité le justifie.

---

## Avant d'aller plus loin

Plusieurs seuils de capital sont en train de changer. Avant tout lancement, il faut faire valider le montage par un avocat spécialisé en droit bancaire CEMAC et confirmer les montants directement auprès de la COBAC et de la COSUMAF.
