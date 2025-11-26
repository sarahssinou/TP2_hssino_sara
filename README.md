Rapport TP – Workflow CI avec GitHub Actions pour projet Android
1. Objectif du TP
L’objectif de ce TP est de mettre en place un workflow CI (Continuous Integration) pour un projet Android à l’aide de GitHub Actions.
Le workflow doit :
•	Se déclencher automatiquement sur des push et pull requests.
•	Exécuter un build simulé ou réel de l’application Android.
•	Lancer des tests unitaires et signaler les échecs.
•	Afficher l’état du workflow (vert pour succès, rouge pour échec) sur la PR.
________________________________________
2. Prérequis
•	Repository GitHub pour le projet Android.
•	Visual Studio Code installé localement.
•	Git configurer sur la machine.
•	Branche principale main.
________________________________________
3. Création et configuration du workflow
 
 <img width="945" height="247" alt="image" src="https://github.com/user-attachments/assets/290b7fb1-a469-4399-bf23-d8f89a692eed" />
<img width="945" height="446" alt="image" src="https://github.com/user-attachments/assets/f6c149c7-1f22-4db4-8c77-ce1a762b46b3" />

4. Création de la Pull Request (PR)
 
 <img width="945" height="418" alt="image" src="https://github.com/user-attachments/assets/a11da049-5465-419e-a2a2-ccbb0147c4ef" />
<img width="815" height="503" alt="image" src="https://github.com/user-attachments/assets/433c6050-ad7c-4a8a-8ba3-14eca8887196" />


5. Résultats observés
 
 <img width="945" height="521" alt="image" src="https://github.com/user-attachments/assets/69c4f574-b876-46ad-9d4a-0328063267c7" />
<img width="945" height="528" alt="image" src="https://github.com/user-attachments/assets/74b2eadd-adfc-4a11-aa4f-30e9994f0869" />

 
________________________________________

Conclusion
•	Le TP a permis de mettre en place un workflow CI fonctionnel sur GitHub Actions.
•	Les tests unitaires simulés permettent de visualiser l’état d’échec ou de succès directement sur la PR.
•	La gestion des branches et PR démontre le processus CI/CD : tester avant de merger.
•	Ce TP illustre l’importance de l’intégration continue pour détecter rapidement les erreurs.

