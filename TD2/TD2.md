## Organisation

| Temps    | Sujets                      |
| -------- | --------------------------- |
| 25 min   | Révision période précédente |
| 5 min    | Pause Random                |
| 25 min   | Cours                       |
| 5 min    | Pause                       |
| 0-25 min | Q&A                         |
| 5-10 min | Contrôle                    |
| 5 min    | Présenter le prochain TD    |

## Cours

- Cryptomonnaies
  - Création d'une crypto
  - Volatilité
  - Coins
  - Tokens
  - Le minage
  - Sécurité
    - Les risques
    - Comment s'en protéger
  - Le halving du BTC

# Le processus de création d'une cryptomonnaie

## Son utilité

Chaque crypto à son propre objectifs, certaines sont liées à des jeux, d'autres résolvent certain problèmes technologies, pour des échanges ou d'autres ne servent à rien.

Pour la création d'une crypto, il faut d'abord savoir à quoi elle va servir, par exemple dans le cas de notre cryptomonnaie l'ApsioCoin, on a d'abord inventé le concet de rémunérer des étudiants avant d'aller plus loin.

## La création de la crypto

Etre présent sur un exchangen des gens cherchent des cryptos avec un fort potentiel => permet de faire entrer sur le marché de nouvelles cryptos sur des sites du type : #exemple

# Volatilité de la crypto

## La loi de l'offre et la demande

Contrairement au monnaies fiat (euro, dollars, etc..), les cryptomonnaies sont seulement régies par l'offre et la demande.

Les action sont valuées en fonction de la perf de l'entreprise, les crypto n'ont pas de valeur intrinsèques et leurs cours et régie par le niveau de spéculation.

## Pas de regulation

> "_Sur le marché boursier, il faut savoir que **Wall Street suspend les échanges** dès que le marché perd plus de 7 %. De plus, lorsque les marchés s’écroulent, **la finance met sous pression les banques centrales pour qu’elles mettent en place des plans de relance**. Ces mécanismes existent justement pour éviter une trop grande volatilité à la baisse des monnaies fiat et écarter les cracks boursiers._"

- #Cryptonaute, [[https://cryptonaute.fr/volatilite-des-cryptomonnaies-pourquoi-et-comment-en-profiter/]]

Ce n'est pas le cas des cryptomonnaies, le marché est ouvert h24, et si on regarde les courbes, on peut voir que faire -7% est assez commun

Btc 40% de tout donc quand elle monte les autres aussi (en gros).

# Décentralisation

Se base sur une blockchain :
![[infog-block-chain.jpg]]
`economie.gouv.fr`

1. Lorsque bob veut envoyer de l'argent à alice, il passe par une banque qui valide la transaction et sert de référence en cas de litige.
2. Avec un réseau décentralisé ce sont les particuliers (les mineurs) qui vont tous se mettre d'accord sur le fait qu'alice envoie tel montant à bob. Ainsi chacun à un registre valide, et même si un malin essaye de le traffiquer, les autres n'auront pas le même et ma transaction ne sera pas valide.

Décentraliser permet donc de savoir qui a envoyer quoi et a qui et de se passer d'une entité souverraine.

# Les coins

https://academy.binance.com/en/articles/how-to-create-your-own-cryptocurrency

Ce sont les cryptomonnaies que nous connaissons (BTC, ETH, WAVES), ils reposent sur leur propre blockchain qui à souvent le même nom que la crypto.
Ils sont utiles au fonctionnement de la blockchain, notamment avec les frais de transaction.
Ces frais sont appliqués pour chaque transactions et permettent de :

1. Éviter les utilisateurs de spammer la blockchain
2. Remunérer les mineurs

# Les tokens

Un token repose sur une blobkchain déjà existante (USDT, USDC, SHIBA, etc...)

## NFTs

C'est un token qui n'existe qu'en 1 seul exemplaire, il est atomique (pas divisible en sous parties) et pas interchangeable (un NFT ne vaut pas un autre NFT, même si ce sont tous les 2 des images)
Le principe est de lier une image, un audio, une vidéo a un token qui est unique. C'est une sorte de certificat d'authenticité. Il est inscrit dans la blockchain et tous le monde peut savoir en temps réel qui possède tel NFT.

Cela s'apparente au marché de l'art, la joconde vaut des millions mais je peux acheter un poster pour 5€ chez monoprix

# Le minage

L'or est limuté, effort de minage et économie derriere, btc a fait pareil.
C'est un PC qui fait tourner un algo complexe, cet effort est récompensé par du BTC qui provient des frais de transactions et de la **création monétaire**. C'est appellé la preuve de travail ou Proof Of Work.
Cela permet de prouver qu'on a depensé de la puissance de calcul pour faire partie de la blockchain

# Sécurité

### Les risques

#### Les transactions

Si on fait un virement a un mauvais RIB, le virement n'est pas declenché car il n'existe pas.
Or pour les cryptos c'est le contraire, chaque addresses (elles s'apparentent a des Ribs) existe déjà. Donc si une transaction est faite sur une mauvaise addresse, la somme est perdue à jamais.

#### Prix fluctuant dans les 2 sens

On entends souvent dire qu'il possible de devenir millionaire rapidement en investissant des les crypros.
Effectivement quand on regarde la courbe, nos yeux sont fixés sur l'enorme pic entre juillet 2020 et juin 2021 et on se dit "Ah si j'avais su".

![[Screenshot_20221026_125251.jpg]]
En effet si j'avais acheté 10 000€ de BTC en juin 2020 et que je vendais tous 1 an après j'aurai gagné 50 000€ sans rien faire.

Or la vie n'est pas si belle. Il faut se rappeller que si on peut vite gagner, on peut aussi vite perdre.

Prenons un exemple du 11/2021 au 11/2022 de 70 000$ à 20 000$.

Donc possibilité de perdre plus de la moitié de ses actifs très rapidemment.

#### Les arnaques

Des mails frauduleux se faisant passer pour votre plateforme d'echange favorite (fishing).

#### Les hacks

Plus il y a à gagner, plus les hackeurs investissent du temps et de l'argent pour accéder à leur butin.

Un hackeur à réussi à récupérer le numéro de téléphone d'une baleine et à appeller son FAI. La personne au bout du fil n'a pas bien fait son travail et à seulement demander son adresse mail, sa date de naissance... des info assez peut privées.
Le FAI à donc fait confiance au hackeur qui à demandé d'envoyer une nouvelle carte SIM. Il a pu changer tous les mot de passes de la victime et a pu récuperer toutes ses crypto. Depuis des mesures ont été mises en place mais c'est un exemole pour montrer qu'il peut y avoir des failles.

Il y a eu d'autres hacks dans le passé et le plus récent connu date du 7 octobre 2022 et est un vol d'un million de BNB, ce qui correspond à plus de 100 millions de $.

Lorsque des hacks comme celui ci se produisent, les plateformes d'echanges comme Binance ou Crypto.com ont une assurance pour rembourser les utilisateurs qui ont été volés. Néanmoins il n'est obligatoire de se faire rembourser.
Le cours de la crypto en question chute aussi (-4% dans le cas du BNB).

### Comment s'en protéger

Il y a de nombreux risques de perdre ses actifs mais il y a tous de même des techniques pour éviter de trop en perdre

## Le livre blanc ( whitepaper )

Les cryptos n'ont pas toute la meme utilité, certaines sont faites pour les echanges, d'autres resolvent des problemes techniques, d'autres sont liés à des jeux vidéo, et certaines de servent a rien (DODGE COIN, SHIBA INU).

Tout ceci est décris dans un livre blanc (white paper) qui explique pourquoi cette crypromonnaie existe.

### Permet de promouvoir

Il est aussi utilisé pour promouvoir sa crypto pour attirer les investisseurs pendant des levées de fonds.

### Pour présenter sa crypto

BTC fait 8 pages et résume son utilité et son fonctionnement.
Il présente aussi ses caractéristiques techniques, comme son type de concensus (PoW).
En plus de cela, il anticipe les problèmes à venir et décrit les règles à suivre en cas de conflits.

### Avertissement

Il n'est néanmoins pas un gage de qualité car il n'est pas obligatoire et la blockchain peut evoluer sans pour autant mettre a jour le white paper.
Exemple d'évolution de blockchain : ETH passe en PoS.

# Le halving du btc

## Qu'est ce que c'est

Division en 2 des récompenses des mineurs.
Ca à été fixé dès le debut par l créateur du btc.

## Pourquoi ?

Cela permet de créer de la rareté, contrairement à l'euro ou le dolars il y a un nombre limité de BTC (21 millions en circulatio). C'est cette limite qui en fait une denrée rare, comme l'or.
90% des BTC sont déjà en circulation et une fois cette limite atteinte il n'y en aura plus jamais de nouveau minés.
Cette limite renforce le fait que cette denrée rare peut s'épuiser et gagner en rareté, donc en valeur.

Le halfing est là pour retarder cette limite.
En effet si tous les mineurs seraient restés à 50 BTC par bloc il n'y en aurai déjà plus
Il à été calculé que la limite sera atteinte en 2140.

Dès lors que la limite sera atteinte on ne sait pas ce qui se passera, mais la solution envisagée est de remunerer les mineurs avec des frais de maintenances.

### Pourquoi 21 Millions ?

Il y a 2 suppositions :

1. à l'époque il y avait 21 trilliards de dollars, donc Satoshi Nakamoto s'est dit que si le BTC deviens une minnaie courante, il vaudrait 1 millions de dollars.
2. Une question de commodité pour répondre à une logique mathématique.

## Quand ?

En pratique le halfing se passe tous les 210 000 blocs, étant donné qu'un bloc se mine en 10 minutes, on peut en déduire que le halfing se passe toutes les 3.995 années.

| Année                     | 2008 | 2012 | 2016 | 2020 | 2024  |
| ------------------------- | ---- | ---- | ---- | ---- | ----- |
| Gain en BTC par bloc miné | 50   | 25   | 12.5 | 6.25 | 3.125 |
|                           |      |      |      |      |

## Les conséquences

Des hausses importantes mais pas nécessairement dessuite. Cette hausse est logique. Effectivement il devient de plus en plus rare car moins produit, ce qui est rare est cher.
Comme vu précédemment, quand le BTC augmente la majorité augmente, donc les autres cryptos auront aussi tendance à exploser.
Il y aura un effet boule de neige car de nombreuses personnes en parleront et influencerons les autres.

# La loi française avec les cryptos

Flat taxe

Qu'est-ce que la DEFI
Source : Youtube - BIS

Decentralized Finance (DeFi) employs public Blockchain networks andsmart contracts to build open, transparent, composable and non-custodial financial protocols.

Open: Open to anyone, no access restrictions, no boss.
Transparent: Mathematically verifiable by anyone. Data availability.
Composable: Interoperable lego pieces.

La construction de la DEFI
Source : Fabian Schär - Decentralized Finance: On Blockchain- and Smart Contract-Based Financial Markets

Exemple avec la Blockchain Ethereum, qui a le plus de transactions DEFI.
Pasted image 20221105114840.png

Chaque layer est au maximum aussi sécurisé que celui qui est en dessous de lui. Ainsi il est facile de comprendre que même si on a un protocol qui permet une bonne décentralisation si la blockchain est ne l'est pas cela ne sert à rien.
