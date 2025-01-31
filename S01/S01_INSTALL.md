---
 ### 🌑 **Infrastructure actuelle**  
---
L'infrastructure actuelle est organisée de la manière suivante :  

- 183 collaborateurs répartis dans 10 départements : communication, direction financière, direction générale, direction marketing, DSI, R&D, RH, services généraux, service juridique, ventes et développement commercial
  
- 100% d'ordinateurs portables
  
- Aucun serveur ni matériel réseau  

- Réseau Wi-Fi fourni par un FAI et des répéteurs Wi-Fi

- PCs en workgroups avec une connexion sans mot de passe  

- Adresse réseau en 192.168.10.0/24  

- Messagerie hébergée en cloud sur le web  

- Une partie des membres du département ventes et développement commercial sont nomades  

- Le stockage de données se fait en local sur les machines

>Schéma de l'infrastructure actuelle 

![InfraEkoloclast](https://github.com/user-attachments/assets/c8bbd394-53b5-4b5e-8a0b-da7a3db06c8b)  

---
### 🌞 **Infrastructure prévisionnelle**  
---
L'infrastructure est composée de 10 réseaux distincts mis en place pour chaque département.  
Ekoloclast prévoit une future fusion/acquisition. De ce fait, la création de réseaux distincts nous permet d'anticiper un besoin en adresses IP supplémentaires dans chaque département.  
En optant pour des sous-réseaux, on risquerait de ne pas avoir assez d'adresses IP adressables lors de cette future fusion/acquisition.  
Nous prévoyons la mise en place d'une DMZ, composée d'un Active Directory, d'un serveur DHCP, d'un DNS, d'un serveur SMTP, d'un serveur FTP et d'une base de donnée.  
Un pare-feu serait installé entre le routeur et la DMZ, permettant de contrôler le trafic Internet entrant et sortant de notre réseau.  

>Schéma de l'infrastructure prévisionnelle  

![Nouvelle organisation](https://github.com/user-attachments/assets/e70ffb26-8dc1-400f-8d9d-5895b47c6d19)

