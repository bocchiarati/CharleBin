# CharleBin -  CHERCHARU Sofien

## Raison d'être du projet ? 

CharleBin est un 'pastebin' (ou gestionnaire d'extraits de texte et de code source) minimaliste et open source, dans lequel le serveur n'a aucune connaissance des données envoyées. Les données sont chiffrées/déchiffrées dans le navigateur par un chiffrement AES 256 bits.

## Prérequis

PHP 8.*
```
sudo apt install php-8.*
```

make
```
sudo apt install make
```

## Installation en local 

clonage du projet :
SSH 
```
git clone git@github.com:bocchiarati/CharleBin.git
```
URL 
```
git clone https://github.com/bocchiarati/CharleBin.git
```

## Comment dev dessus ? 

Contentez vous d'effectuez vos changement en reliant le projet local à un repo en remote si vous voulez faire des chagements pour vous même ou bien, en proposer des pull request afin de proposer vos améliorations

## Déploiement 

Rendez vous dans le dossier du projet et effectuer la commande 
```
make start
```
 puis copier l'url devant ressembler à ceci : `localhost:8080` dans votre navigateur
