# lets-play-science

Un petit repo pour aggréger les suggestions de **Lets Play Science** !  
Vive l'intelligence collaborative !  

**Pourquoi github?** Parce que cette application permet de faire des **révisions avec validation du propriétaire** d'un document collaboratif, cf le point suivant. 

**Pour faire une proposition d'édition**, *c'est pas sorcier* :

- [Créez un compte github](https://github.com/join)
- Sélectionnez le fichier [README.MD](README.MD)
- appuyez sur le symbole en forme de stylo *edit*
- faites vos modifications 
- en bas de la page, section **Propose file change** :
  - renseignez une phrase qui décrit la modification
  - appuyez sur **propose file change**

Je me chargerais de faire la validation des requêtes. Si d'autres veulent me pretter la main pour la modération, [laissez un message ici](https://github.com/sveinburne/lets-play-science/issues/1)! 

# Solution 1 : Trouver/Créer un forum qui permettrait... 
## **1** Différents types de likes ( proposé par [https://www.youtube.com/user/koukaloukaki] )
L'idée est de faire du filatrage collaboratif en catégorisant subjectivement l'intérêt 

- pousse vert ça veut dire "bonne blague"
- pousse bleu ça veut dire "pas con"
- pousse rouge ça veut dire "nul" ou "spam"

Ainsi on peut filtrer suivant notre approche, "érudite" ou "détente" !

## **2** Une certaine forme de modération (proposé par une vaste majorité)
En dehors de la gestion des trolls, un moderateur pourra marquer un post comme :
- houleux ( il ne sera plus favorisé dans l'algorithme de tri ) 
- exceptionnel ( il sera mit en avant dans l'algorithme de tri ) 

## **3** Des #hashtags  ( proposé par []() )
Permet de filtrer rapidement le contenu, et d'avoir un accès facile aux posts relatifs

## **4** Possibilité de marquer un post comme "évalué"
Extension de la proposition **3** : 
Si on a ni liké, ni jugé le contenu extraordinaire, ni merdique, on peut le marquer comme "lu", cf la proposition **5**

## **5** Une interface qui favorise l'évaluation entre pairs
Inspiré de la proposition de [koukaloukaki](https://www.youtube.com/user/koukaloukaki)
- Proposer à l'utilisateur un mode "évalutation" ou son travail est d'évaluer des posts qu'il n'a pas encore évalué. Grosso modo, ça lui permet de s'y retrouver facilement !  
Dans ce mode, **seuls les contenus non marqué (comme "vu", "pas con", "spam" ou "drôle") seront visibles**. 

## **6** S'insipirer de republique-numerique.fr [proposé par hackedbrain17](https://www.youtube.com/user/hackedbrain17)
Avec notamment : 
- La proposition **1**
- La possibiliter d'éditer collectivement les propositions (soumettre une édition à l'auteur du post, comme sur github^^)

## **7** Utilisé la statistique pour évaluer la qualité des posts [proposé par Fjellfrass ](https://www.youtube.com/user/Fjellfrass) et [par Sebastien Huet](https://www.youtube.com/user/huetse)

Faire une analyse sémantique des commentaires google pour rapprocher les posts similaires en utilisant l'API de google. 
(à développer)

# Candidats possibles 
## [Discourse](https://www.discourse.org/) proposé par [kokodroid](https://www.youtube.com/user/kokodroid)
**Pros**
- Open source
- Moderne
**Cons**
- Ne supporte pas la personnalisation des likes à ma connaissance
