# 📡 Projet Réseau — ESGI Security (Mai 2025)

Ce dépôt contient un projet complet de **conception et sécurisation d’une infrastructure réseau multisite** réalisé dans le cadre de la 3e année à l’ESGI.

## 📝 Objectifs du projet

- Concevoir un plan d’adressage IPv4 optimisé (VLSM)
- Relier plusieurs agences (Rennes, Strasbourg, Grenoble, Bordeaux) au siège à Paris
- Mettre en place :
  - Routage OSPF
  - DHCP dynamique par VLAN
  - VLANs sécurisés
  - Port security
  - Filtrage ACL (anti-ICMP, Telnet/FTP)
- Simuler le tout sous Cisco Packet Tracer

## 🗂 Contenu du dépôt
```text

Projet-Reseau_Securisation_infrastructure/
├── ProjetReseau_ESGI_Slimani_Anis_Mai2025.pdf # Rapport détaillé du projet
└── projet_reseau_ESGI_SlimaniAnis.pkt # Fichier Cisco Packet Tracer
```



✅ **Rapport PDF** : Retrouvez tous les détails techniques (adressage, OSPF, sécurité, tests CLI) dans le fichier `Sécurisation_infrastructure_réseau.pdf`.

📥 **Fichier .pkt** : Pour tester la simulation réseau dans [Cisco Packet Tracer](https://www.netacad.com/), cliquez sur **"View Raw"** sur `Projet_Reseau.pkt(Cisco_packet_tracer)` pour le télécharger.

---

## 🖥️ Extrait des fonctionnalités validées

- Ping et traceroute entre agences
- Attribution DHCP automatique
- Routage OSPF fonctionnel
- Blocage des protocoles non sécurisés (Telnet, FTP)
- Protection contre les attaques ICMP
- Port Security avec MAC sticky

---

## 🔐 Sécurité appliquée

| Type de sécurité          | Description                                      |
|--------------------------|--------------------------------------------------|
| VLAN                     | Cloisonnement logique des postes métiers         |
| ACL FAI                  | Blocage Telnet/FTP, ICMP                        |
| Port-Security            | Anti-intrusion physique                         |
| Routage centralisé       | Trafic inter-agence via Paris                   |

---

## 📌 Auteur

- **Anis Slimani** — Étudiant en 3e année Cybersécurité à l’ESGI

---

> 📂 Pour plus de détails, consultez le fichier PDF du rapport.  
> 📎 Pour tester le réseau, ouvrez le fichier `.pkt` avec Cisco Packet Tracer (version 8.2.2 recommandée).
