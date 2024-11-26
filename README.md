Créer un utilisateur wilder et l'ajouter au groupe students.  

![Pic](/ADDS3/screen1.png)  

Créer la GPO  et activer l'interdiction d'accès au panneau de configuration .  

![Pic](/ADDS3/screen2.png)  

Ajouter ensuite la GPO sur le groupe Students.

Connectez vous sur l'utilisateur dans le domaine, faites gpupdate /force sur powershell pour activer la règle  
si ce n'est pas déjà le cas.  
  
Tester d'ouvrir le panneau de configuration. Un message d'interdiction va s'afficher.  

![Pic](/ADDS3/screen4.png)  

