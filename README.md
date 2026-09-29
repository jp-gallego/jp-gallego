# Jean-Pierre Gallego Santillan

**Apprenti informaticien CFC · ancien électricien · Lausanne**

Pendant 5 ans, j'ai tiré du câble réseau et de la fibre sur les chantiers et raccordé des racks. Aujourd'hui je suis en 1re année d'apprentissage CFC informaticien au Geneva Institute of Technology, et je m'occupe de ce qui passe dans ces câbles.

Ici, je range mes projets de formation. Pour chacun, j'ai écrit un rapport avec les étapes, les captures et les problèmes que j'ai eus.

---

### Mon parcours

```
2017 ─ 2020   CFC d'électricien
2020 ─ 2024   Monteur électricien (câblage réseau, fibre, racks)
2025          Service militaire, soldat sanitaire (spécialisation transmission)
2026 ─ ...    Apprentissage CFC informaticien au GIT
```

---

### Les 5 projets que je montre

#### 1. Réseau sous GNS3 : deux routeurs Cisco et DHCP

Deux LAN reliés par deux routeurs Cisco 7200. Chaque routeur distribue les adresses à ses PC en DHCP et les routes statiques font passer le trafic d'un côté à l'autre. J'ai noté les pannes que j'ai eues (interface restée en shutdown, pool DHCP sur le mauvais réseau) et comment je les ai trouvées.

`GNS3` `Cisco IOS` `DHCP` `routage statique` → [le rapport](https://github.com/jp-gallego/Projet-cfc-informaticien/tree/main/Reseau-GNS3-routage-DHCP)

#### 2. ESXi et vCenter sur un vrai serveur

Installation d'ESXi 8 sur un serveur rack HP ProLiant, création d'une VM Windows Server 2025, snapshot, puis déploiement de vCenter et ajout de l'hôte dans un cluster.

`VMware ESXi` `vCenter` `vSphere` `Windows Server` → [le rapport](https://github.com/jp-gallego/Projet-cfc-informaticien/tree/main/ESXi-vCenter)

#### 3. Déployer des postes avec une image système

Un poste Windows 10 de référence (comptes, logiciels, réglages), généralisé avec Sysprep, capturé puis redéployé avec Clonezilla. Pour 10 postes, ça fait gagner plusieurs heures par rapport à une installation à la main.

`Sysprep` `Clonezilla` `Windows 10` `VMware Workstation` → [le rapport](https://github.com/jp-gallego/Projet-cfc-informaticien/tree/main/Projet-5-Deploiement-image-systeme)

#### 4. Un poste partagé par plusieurs élèves

Un compte par élève, chacun ne voit que ses propres dossiers (droits NTFS), verrouillage de session et règles de mots de passe. J'ai testé avec chaque compte que personne n'accède aux fichiers des autres.

`icacls` `NTFS` `secpol.msc` `PowerShell` → [le rapport](https://github.com/jp-gallego/Projet-cfc-informaticien/tree/main/Projet-2-Poste-multi-utilisateurs)

#### 5. Installer Windows et Ubuntu avec une clé USB

Sur un vrai PC : clé bootable avec Rufus, passage par le BIOS pour démarrer dessus, installation de Windows 11 puis d'Ubuntu.

`Rufus` `BIOS/UEFI` `Windows 11` `Ubuntu` → [le rapport](https://github.com/jp-gallego/Projet-cfc-informaticien/tree/main/Installation-Windows-Ubuntu-cle-USB)

Mes autres projets (Windows 11 sur VMware, mise en service, migration, dépannage d'un poste) sont dans [Projet-cfc-informaticien](https://github.com/jp-gallego/Projet-cfc-informaticien).

---

### Ce que je cherche

Un **stage en systèmes, réseaux ou infrastructure**, entre Lausanne et Genève.

Je parle français et espagnol (langues maternelles) et un peu d'anglais.

📄 CV : [jp-gallego.github.io](https://jp-gallego.github.io) · 💼 [LinkedIn](https://www.linkedin.com/in/jean-pierre-gallego-santillan-6b4701433) · ✉️ jean-pierre.gallego@git.swiss
