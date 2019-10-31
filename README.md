Bonjour et bienvenus !!! :) 

Voici comment lancer le programme : 

  DANS LE TERMINAL, TAPER LES COMMANDES SUIVANTES : 

    - git clone https://github.com/Maxx-N/s5_j4_gossip_project_facebook_style.git

    - cd s5_j4_gossip_project_facebook_style/

    - bundle install

    - rails db:migrate

    - rails db:seed

    - rails server
    
    (laisser tourner le serveur)

  PUIS, DANS VOTRE NAVIGATEUR, SAISIR L'URL : 

    - http://localhost:3000/


Après des heures passées à essayer, je n'ai finalement toujours pas réussi à déconnecter un utilisateur : J'ai eu beau le tourner dans tous les sens, le server ne comprend pas ma requête "delete" qui vise la méthode destroy du sessions_controller... il la prend pour une requête "get" ...
Je me suis déjà arraché beaucoup de cheveux donc si vous avez des conseils pour mon bien capillaire, je suis preneur !!! Merci d'avance :)

  