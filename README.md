# Pwnagotchi-AI-Handshake-Auditor-Pi-Zero-2-W-

📝 Description du projet
Ce projet consiste en la mise en place d'un Pwnagotchi, une unité A2C (Deep Reinforcement Learning) basée sur du texte, qui apprend de son environnement WiFi pour optimiser la capture de "handshakes" WPA.

L'objectif de ce projet était de construire un outil de test de pénétration autonome, de configurer un environnement Linux minimaliste et de résoudre les défis matériels liés au Raspberry Pi Zero 2 W.

🛠️ Hardware & Matériel
Microcontrôleur : Raspberry Pi Zero 2 W (Choisi pour ses performances accrues par rapport au Zero W classique).

OS : Version optimisée par Jayofelony (64-bit, supportant mieux les derniers hardwares).

Écran : Waveshare e-Paper 2.13-inch.

Alimentation : Powerbank.

⚙️ Installation et Configuration
J'ai choisi d'utiliser l'image de Jayofelony car elle offre un meilleur support pour l'architecture 64 bits du Pi Zero 2 W et des plugins plus récents.

Points clés de la configuration :

Configuration du fichier config.toml pour personnaliser le comportement de l'IA.

Mise en place du mode Gadget USB pour l'accès SSH via Ethernet-over-USB.

Optimisation de l'affichage pour réduire le "ghosting" sur l'écran e-ink.

🔧 Défis Techniques & Troubleshooting 
Dans ce projet, j'ai rencontré plusieurs difficultés qui m'ont permis de renforcer mes compétences :

Compatibilité Pi Zero 2 W : L'image standard ne bootait pas correctement. J'ai dû pivoter vers le dépôt de Jayofelony et flasher manuellement les partitions.

Gestion de l'alimentation : Résolution des problèmes de sous-tension lors de l'utilisation simultanée du WiFi et de l'écran e-ink.

Debug Linux : Analyse des logs système via journalctl -fu pwnagotchi pour comprendre les erreurs de chargement des plugins.

🚀 Compétences démontrées
Linux Administration : Gestion de services (systemd), édition de fichiers de configuration, gestion des permissions.

Networking : Protocoles 802.11, captures de paquets, SSH, TCP/IP.

Hardware : Assemblage de composants, gestion d'écrans SPI/I2C, impression 3D.

Problem Solving : Recherche de solutions dans la documentation technique et sur les forums communautaires.

![pwnagotchi](https://github.com/user-attachments/assets/e7e51cf3-a525-448c-a92b-c0895935df68)


