# Résumé du Référentiel général d'écoconception de services numériques (RGESN)

URL du document original : https://ecoresponsable.numerique.gouv.fr/publications/referentiel-general-ecoconception/

## Stratégie

1. Le service doit bien connaitre sa cible.
2. Le service doit proposer des fonctionnalités qui répondent à un besoin précis.
3. Le service ne doit pas proposer de fonctionnalités superflues.
4. Le service doit pouvoir être utilisé par d'anciens terminaux (5 ans ou plus).
5. Le service doit utiliser le plus possible des technologies standards, interopérables.

## Spécifications

1. Les choix de conception, d'architecture et de services tiers doivent avoir pour objectif de réduire l'impact environnemental du service.

## Architecture

1. Le service doit privilégier un potentiel passage à l'échelle plutôt qu'un surdimensionnement.
2. Le service doit anticiper l'obsolescence des protocoles utilisés.
3. Le service doit limiter l'échange de données.
4. Le service doit proposer des mises à jour durant toute la durée de vie des équipements et logiciels liés au service.

## UX/UI

1. Le service doit privilégier les composants natifs.
2. Le service doit limiter l'utilisation de ressources lourdes comme des vidéos (privilégier texte et images).
3. Le service doit informer l'utilisateur lorsqu'un traitement est en cours.

## Contenus

1. Le service doit utiliser des formats de données adaptés au contenu qu'il manipule, notamment pour en réduire la taille.
2. Le service doit utiliser un niveau de compression adapté au contexte. Par exemple, compresser un JPEG à 60% si c'est acceptable.
3. Le service doit disposer d'une stratégie d'archivage ou de suppression des données obsolètes.
4. Le service ne doit dupliquer les données que lorsque c'est nécessaire.

## Frontend

1. Le service doit optimiser l'affichage pour la résolution/taille de l'écran servis.
2. Le service doit privilégier la mise en cache et le stockage de ressources côté client lorsque c'est pertinent.
3. Le service doit privilégier un chargement progressif des ressources.
4. Le service ne doit pas charger de ressource inutile.

## Backend

1. Le service doit privilégier la mise en cache côté serveur lorsque c'est pertinent.
2. Le service doit privilégier la transmission de données compressées.

## Hébergement

1. Le service doit privilégier un hébergeur signataire du Code de conduite européen, et engagé dans la réduction de son impact environnemental.
2. Le service doit privilégier un hébergeur qui communique des indicateurs liés à son impact environnemental (notamment : origine de l'électricité consommée, Power Usage Effectiveness, Water Usage Effectiveness).
3. Le service doit privilégier un hébergeur proche des utilisateurs du service.
4. Le service doit utiliser un stockage adapté pour les données chaudes et froides.
