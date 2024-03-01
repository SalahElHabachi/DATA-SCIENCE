## Projet de prédiction de la consommation électrique des sites d'un opérateur électrique :

Ce projet est un travail d'un mois, dans le cadre de ma formation au mastère spécialisé HPC [HPC & AI](https://www.hpc-ai.mines-paristech.fr/), à [L'école Des MINES-Paris](https://www.minesparis.psl.eu/)


## Objectif du projet   : 
Imaginons qu'on est ingénieur au siege d'un opératuer téléphonique ( Opératuer X ) et on disposons de l'historique de la consommaton d'électricité de tous les sites dont on dispose, et que on cherche à prédire la consommation d'électricité de tous les sites pour le mois prochain. C'est ce qu'on va essayer de faire.


## Les données : 

On a une base de données structues de touts les sites idenrifés par leurs noms, la consommation en KWH, et la date de début de fin de la consommation facturée.  


## Comment avoir le projet : 


Vous trouvere un fichier requiermnet où vous trouvez toutes les biblio nécessaires.
Vous trouver dans le notebook cidessu toute l'étude que j'ai fait pour répodre à ce besoin. De l'analyse des données au predictions. 


## Comment faire marcher l'application ?
### Préprer le terrain : 😉
1. Cloner le projet en local :
```bash
git clone ...............
```
2. Créer & Activer un environnement conda :
```bash
conda create --name nom_de_votre_environnement python=3.10

```
 - Sur Windows :
```bash
activate nom_de_votre_environnement
```
 - Sur Linux/macOS :
```bash
source activate nom_de_votre_environnement
```
3. Installer les package nécessaires :
> Dans ce projet on a utilisé la bibiothèque Tkinter de python :

```bash
pip install requierements.txt

```
