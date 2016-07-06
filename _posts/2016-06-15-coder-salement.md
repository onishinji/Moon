---
layout: post
title: "Startup en phase de démarrage ? Coder salement !"
date:   2016-06-15
excerpt: "C'est contre productif de faire \"trop\" bien les choses au début. De toute façon, on ne peut faire vite et bien."
comments: true
---
Derrière ce titre racoleur que j'assume pleinement, il faut comprendre pourquoi je dis ça.

J'ai développé en agence et en start-up.

En agence, on fait au mieux en fonction du temps allouer sur la tâche par le chef de projet ou par sa propre estimation. On ne fait ni plus ni moins que ce qui est demandé. Au bout d'un certain temps, on se dit qu'on peut faire mieux si seulement on nous en laissait le temps et ça frustre. De plus, si les délais sont courts on n'hésite jamais à sacrifier de la qualité. C'est un fait.

Du coup, lors de ma première start-up, j'ai eu le raisonnement inverse, à savoir que, puisqu'on est notre propre client on va pondre du code stable, maintenable pour les années à venir. Enfin on ferra du bon code et par cette excellence technique notre start-up ne peut que réussir. De plus, mettre plein de tests, des systèmes de builds et de livraison avancés peut devenir enfin réalité.

La réalité c'est que cet état d'esprit a juste tué la start-up. Le temps de mise en place d'une solide stack de développement prend pas mal de temps, temps qui manque quand on fait notre mvp* en général. Ce temps supplémentaire pour satisfaire notre orgueil de développeurs qui nous a fait louper ou reporter des échéances clés dans la vie de la start-up. La mauvaise foi m'a déjà fait dire "On a loupé le coche mais si le produit décolle vraiment on est prêt". La start-up n'a jamais décollé.
De plus, en anticipant les demandes trop tôt, sans vérifier nos hypothèses par du bêta testing ou ne pas rencontrer nos futurs clients, il est facile de construire une stack technique pas du tout adapté. "Ah ? En fait les API REST avec OAUTH2 décentralisée tout le monde s'en fou ? Un simple export excel sur un FTP à la noix suffit ?!" Ça nous est tous arrivé de pondre une solution technique complètement à l'ouest du besoin, mais le faire en start-up est suicidaire.

C'est extrêmement frustrant parce qu'on va accoucher d'un bébé non assumé. Cependant, il faut miser sur l'avenir.

Dans la phase de création de start-up où les fonds manquent ou que les délais de mise sur le marché sont courts, il faut aller vite et tant pis pour le bien. Ce n'est pas la beauté du code qui fait fonctionner un produit c'est le produit en lui même. Même si ce n'est pas scalable, on s'en fiche tant qu'on a pas de communauté, d'utilisateurs en nombre suffisant pour garantir la réussite du projet. Souvenez-vous de la baleine bleue de Twitter à ses débuts, eux aussi ont dû commencer sale.

En phase de croisière où la start-up commence à bien tourner, que le business plan est fixé et donne des résultats, alors là, et seulement là, on peut envisager une V2 où l'on pourra être fier du code. Pas avant.

Au mieux, on code sale tout en anticipant la refonte prévue, on découpe suffisamment pour pouvoir reprendre le code parti par parti et non dans sa globalité.

Pour les développeurs qui ne jurent que par le TDD, ou le DDD, je serais curieux de savoir comment vous vous comportez dans une start-up en phase de croissance.

*minimum viable product