🎉 Application de Gestion d’Événements avec Spring Boot & MongoDB
Organisez, visualisez et partagez tous vos événements (anniversaire, mariage, conférences, réunions) facilement, avec partenariat pour cafés, restaurants et boîtes de nuit. 🥳✨

🚀 Technologies utilisées
Spring Boot 🌱 — Backend robuste en Java
Thymeleaf 🌸 — Templates côté serveur pour des pages dynamiques
MongoDB 🍃 — Base de données NoSQL pour stocker événements et partenaires
Spring Data MongoDB 📦 — Accès aux données
Spring Security 🔒 — Sécurité et gestion des utilisateurs/admins
Bootstrap 🎨 — Interface moderne et responsive
Font Awesome ⭐ — Icônes pour un design attrayant
⚙️ Comment installer et lancer le projet
1. Cloner le dépôt
bash
git clone https://github.com/votre-username/evenements-springboot.git
cd evenements-springboot
2. Configurer la base de données
Installez MongoDB localement ou utilisez une instance en cloud (MongoDB Atlas)
Modifier le fichier application.properties pour la connexion (URL, port, credentials)
3. Construire le projet
bash
./mvnw clean install
# ou si vous utilisez Maven installé globalement
mvn clean install
4. Lancer l’application
bash
./mvnw spring-boot:run
# ou
mvn spring-boot:run
L’application sera accessible via http://localhost:8080.

🖥️ Fonctionnalités principales
Pour l’utilisateur
🎈 Voir tous les événements avec détails : date, nombre de places disponibles, durée
✍️ Poster un événement (si autorisé)
🤝 Partner avec cafés, restaurants et boîtes de nuit
Pour l’administrateur
✅ Ajouter, modifier ou supprimer des événements
🔑 Gestion des partenaires
⚙️ Gérer la plateforme en toute sécurité
🌟 Partenariats
Cafés ☕️
Restaurants 🍽️
Boîtes de nuit 🎶
Et plus encore ! Chaque partenaire peut être associé à des événements pour couvrir tous types de réunions festives et professionnelles.

🎨 Conseils pour une interface attractive
Utiliser Bootstrap pour un design responsive et esthétique
Ajouter des icônes Font Awesome pour illustrer les actions
Couleurs vives et conviviales pour stimuler l’ambiance
Pages claires avec navigation simple
📝 Résumé des étapes pour débuter
Cloner le dépôt
Modifier application.properties avec vos paramètres MongoDB
Construire le projet (mvn clean install)
Lancer l’application (mvn spring-boot:run)
Accéder à http://localhost:8080
💡 Remarque
Assurez-vous que MongoDB tourne avant de lancer l’application
Créez des utilisateurs/admins pour la gestion sécurisée
Personnalisez le contenu pour votre ambiance ou vos partenaires
✉️ Contact
Pour toute question ou suggestion, contactez-moi ou ouvrez une issue. Bonne organisation et que la fête commence ! 🎉🎈

