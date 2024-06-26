Objectifs
On souhaite mettre en œuvre un système de stockage décentralisé comparable à un "Drive",
où l'accès aux fichiers est sécurisé et où la gestion de l'identité se fait de manière privée, en
utilisant les technologies : InterPlanetary File System (IPFS) et les Zero-Knowledge Proofs
(ZKPs).

Utilisation d'IPFS pour le Stockage Décentralisé :

- Intégration du protocole IPFS pour le stockage décentralisé et la distribution de
  fichiers.
- Dès le dépôt d’un fichier sur la plateforme, un smart contract est appelé et un NFT est
  créé dont l’id est relié aux CID (Content IDentifier donné par IPFS ). L’utilisateur à
  ensuite le choix entre laisser son fichier public ou restreindre son accès en donnant
  les conditions à respecter pour pouvoir y accéder.
- Possible organisation des fichier sous forme de dossier.
- Organisation des fichiers en utilisant des adresses uniques basées sur le contenu.

Gestion de l'Identité avec des ZKPs :

- Mise en place d'un système d'authentification basé sur les ZKPs pour prouver
  l'identité des utilisateurs sans divulguer d'informations sensibles. Et ainsi leur
  permettre d’accéder à certains fichiers dont l’accès est restreint.

Smart Contract sur la Blockchain :

- Développement de contrats intelligents sur la blockchain utilisant des ZKPs pour gérer
  les autorisations d'accès aux dossiers.
- Smart contract permettant de générer les NFT.

Interface Utilisateur :

- Création d'une interface utilisateur intuitive permettant aux utilisateurs d'interagir
  avec IPFS pour télécharger, stocker et partager des fichiers.
- Intégration de fonctionnalités permettant aux utilisateurs de générer et d'utiliser des
  preuves d'identité pour accéder à des dossiers spécifiques.

Lien vers l'ancien repository : https://github.com/dramob/PRO3600-Chainvault

Pour visualiser le site voici les étapes à suivre :

- Cloner le dossier sur son pc
- Ouvrir un terminal, se placer dans le dossier frontend et executer les commandes suivantes :
  - npm install # Permet d'installer les dépendances
  - npm i react-router-dom # Permet d'installer des dépendances
  - npm install --save xrpl
  - npm install ipfs-http-client
  - npm install axios
  - npm run build # Permet de créer une version de production optimisée de l'application
  - npm start # Permet de lancer le site localement

Le site devrait ensuite se lancer dans votre navigateur !
