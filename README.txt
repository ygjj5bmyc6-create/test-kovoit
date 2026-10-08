COVOIT'ENTREPRISE — V1 FONCTIONNELLE

Cette version est un MVP autonome (PWA) :
- connexion de démonstration
- création de trajets
- recherche
- réservation / annulation
- mes trajets
- messagerie
- profil
- administration
- responsive mobile / ordinateur
- données persistées dans le navigateur (localStorage)

Comptes de démonstration :
Salarié : thomas@entreprise.fr / demo1234
Admin : admin@entreprise.fr / admin1234

Pour la version réellement multi-salariés en production, il faudra brancher une base de données distante, une authentification sécurisée et un hébergement HTTPS.


VERSION CORRIGEE
La connexion ne dépend plus de localStorage pour démarrer la session. Un stockage mémoire de secours est utilisé si le navigateur bloque le stockage local.

Identifiants de démonstration :
Employé : thomas@entreprise.fr / demo1234
Admin : admin@entreprise.fr / admin1234

Pour une utilisation sur iPhone, si le fichier HTML ne s'ouvre pas correctement, placez le dossier sur un petit hébergement web (ou utilisez la future version Supabase).
