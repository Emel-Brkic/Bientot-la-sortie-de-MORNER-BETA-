# Bientot-la-sortie-de-MORNER-BETA-

🛡️ Morner — Surveillance réseau avancée & protection comportementale
👨‍💻 À propos du développeur

Développé par BRKIC Emel, passionné par la cybersécurité, l’analyse système et le développement d’outils défensifs avancés.

( L'application contient énormément de bug pour le moment attention !! )
Je suis en aucun cas responsable des problemes que les bugs peuvents faire !
BETA !!!

https://drive.google.com/file/d/1dYjCcx6xz3gSYF71__9wYWxHY0rv5Mwb/view?usp=sharing

Ce projet s’inscrit dans une démarche d’apprentissage approfondi du fonctionnement interne des logiciels de sécurité modernes, en recréant des mécanismes inspirés des antivirus et des solutions EDR (Endpoint Detection & Response), tout en restant transparent, personnalisable et éducatif.

🚀 Présentation du projet

Morner est une application de surveillance réseau en temps réel développée en Python, capable d’analyser l’activité réseau d’un ordinateur, de détecter des comportements suspects et de réagir automatiquement face à des menaces potentielles.

Contrairement aux outils classiques reposant uniquement sur des signatures statiques, Morner analyse le comportement réseau des processus afin d’identifier des activités anormales ou dangereuses.

Le logiciel agit comme un hybride entre :

un moniteur réseau en temps réel,

un analyseur comportemental,

et un système de protection défensive léger.

🔍 Surveillance réseau en temps réel

Morner inspecte en continu les connexions réseau actives du système via une analyse bas niveau.

Il surveille notamment :

les adresses IP distantes

les ports utilisés

les processus responsables des connexions

la fréquence des communications

l’état des connexions IPv4 et IPv6

Toutes les activités sont affichées en direct dans une interface graphique interactive.

🧠 Moteur de détection comportementale

Le cœur du projet repose sur un système d’analyse comportementale capable d’attribuer un score de danger à chaque processus.

Ce score est calculé selon plusieurs critères :

nombre de connexions par minute

quantité d’IPs uniques contactées

diversité des ports utilisés

utilisation de ports suspects

schémas réseau anormaux

Ce mécanisme permet de détecter des comportements similaires à :

botnets

malwares communiquant avec un serveur distant

scanners réseau

tentatives d’exfiltration de données

☣️ Base de données d’IP malveillantes

Morner utilise une base de données personnalisable contenant des adresses IP considérées comme dangereuses.

Lorsqu’une correspondance est détectée :

la connexion est immédiatement signalée

une alerte est générée

des actions défensives peuvent être appliquées automatiquement

La base peut être importée, modifiée et rechargée dynamiquement.

🚫 Système de protection automatique

Lorsque le mode protection est activé, Morner peut :

bloquer automatiquement une IP via le pare-feu Windows

interrompre un processus suspect

notifier l’utilisateur en temps réel

demander une autorisation manuelle

Le logiciel devient ainsi un outil de défense actif et non seulement d’observation.

🎮 Mode Gaming sécurisé

Afin d’éviter les faux positifs pendant les sessions de jeu, Morner intègre un mode spécial protégeant les processus connus liés aux jeux vidéo.

Ce mode évite :

les déconnexions involontaires

les conflits avec les anti-cheats

les interruptions de session.

🔐 Coffre-fort sécurisé

Morner inclut un système de coffre-fort chiffré permettant de stocker des informations sensibles protégées par un mot de passe maître.

Les données sont chiffrées localement à l’aide d’une clé dérivée du mot de passe utilisateur.

🧾 Journalisation & analyse forensic

Chaque événement est enregistré avec horodatage afin de permettre :

l’analyse après incident

le suivi des activités réseau

l’investigation de comportements suspects

l’export des connexions pour analyse

⚙️ Personnalisation avancée

Le comportement du moteur de détection peut être entièrement ajusté :

whitelist de processus autorisés

whitelist de domaines

blacklist de mots-clés suspects

seuils de détection comportementale

activation du blocage automatique

configuration des processus protégés

🖥️ Interface graphique moderne

L’application dispose d’une interface complète développée avec Tkinter et ttk :

affichage des connexions en temps réel

code couleur selon le niveau de danger

actions rapides (autoriser, bloquer, tuer processus)

filtrage dynamique

journal en direct

🎯 Objectif du projet

Morner a pour objectif d’explorer et de démontrer le fonctionnement interne des outils de cybersécurité modernes en recréant leurs principes fondamentaux dans un environnement pédagogique, transparent et entièrement contrôlé par l’utilisateur.

⚠️ Licence et droits d’utilisation

© BRKIC Emel — Tous droits réservés

Ce projet est une création originale protégée.

Toute modification du code source est strictement interdite sans autorisation explicite de l’auteur.

La redistribution modifiée du projet est interdite.

La revente totale ou partielle du logiciel ou de son code source est interdite.

L’utilisation commerciale est interdite sans accord écrit préalable.

Ce dépôt est fourni uniquement à des fins personnelles, éducatives et de démonstration.

Toute utilisation implique l’acceptation de ces conditions.
Et cette application est en beta je ne suis pas responsable de tout dommages sur vautre machine, et de son utilisation.

