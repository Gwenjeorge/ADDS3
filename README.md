Créez un utilisateur wilder et au ajoutez le groupe students.  

![Pic](/ADDS3/screen1.png)  

Créez la GPO  et activez l'interdiction d'accès au panneau de configuration .  

![Pic](/ADDS3/screen2.png)  

Ajoutez ensuite la GPO sur le groupe Students.

Connectez vous sur l'utilisateur dans le domaine, faites gpupdate /force sur powershell pour activer la règle  
si ce n'est pas déjà le cas.  
  
Testez enfin d'ouvrir le panneau de configuration pour tester l'effectivité de la GPO. Un message d'interdiction doit s'afficher.  

![Pic](/ADDS3/screen4.png)  

