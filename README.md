J'ai réussi a déployer Sémaphore :
- Avec terraform, je crée mon architecture et mon instance.
- Avec Ansible, je déploie mon sémaphore en faisant attention de bien ouvrir le port 3000

Ce que je n'ai pas réussi :
- Utiliser bolt afin de configurer mon fichier de compte et pouvoir créer un user pour me connecter au Sémaphore

Ce que j'ai tenté pour y arriver :
- Installer sémaphore via docker afin de faire un conteneur et l'éxécuter, je n'ai pas eu le temps de bien l'élaborer
- Modifier mon fichier de conf sémaphore via Ansible
