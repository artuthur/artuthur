## Hi there 👋

**Administrateur systèmes et réseaux junior**, diplômé du BUT Informatique (parcours Administration Systèmes et Réseaux, IUT de Lille, 2025).

Depuis la fin de mes études, je continue à me former **en autodidacte**. Ce profil GitHub est mon terrain d'apprentissage : chaque dépôt est un projet que je mène seul, de bout en bout, pour découvrir une technologie en la mettant réellement en pratique. Je choisis le sujet, je conçois l'architecture, je bute sur les problèmes, je cherche, et je documente ce que j'ai compris.

Hauts-de-France (Lille, Béthune, Bruay-la-Buissière) · **Ouvert aux opportunités** : support N1/N2, administration systèmes, réseaux

---

## Apprendre en construisant

Je n'apprends pas en suivant un tutoriel jusqu'au bout : je me fixe un objectif concret et je le mène jusqu'à un résultat qui fonctionne, vérifié et reproductible. Quelques principes que je m'impose sur chaque projet :

- **Partir d'un vrai besoin d'entreprise** plutôt que d'une démo : architecture 3-tiers, comptes d'administration dédiés, secrets chiffrés, nommage clair.
- **Comprendre avant d'avancer** : quand je bloque, je diagnostique couche par couche et je garde une trace de la cause réelle, pas seulement du correctif.
- **Documenter pour transmettre** : chaque dépôt contient un journal de bord de mes problèmes et de leur résolution, mes choix techniques justifiés, et les limites que je n'ai pas encore traitées.

## Mes projets

Après Kubernetes, j'ai réorienté ma feuille de route vers l'environnement Microsoft (Active Directory, GPO, Microsoft 365), parce que c'est ce que demandent la plupart des offres de ma région : je veux savoir réaliser ces tâches concrètement avant d'arriver en poste.
 
| Projet | Ce que j'y apprends | Stack | État |
|---|---|---|---|
| [**lab-infra-as-code**](https://github.com/artuthur/lab-infra-as-code) | Mon premier projet d'infrastructure par le code : une architecture 3-tiers (load balancer, 2 serveurs web, base de données) provisionnée entièrement avec Ansible, répartition de charge et isolation réseau vérifiées | Vagrant, Ansible, HAProxy, Nginx, PostgreSQL | Terminé |
| [**lab-cicd-pipeline**](https://github.com/artuthur/lab-cicd-pipeline) | GitLab CE auto-hébergé en HTTPS avec ma propre PKI, runner, registre de conteneurs et pipeline complet (lint, tests, build, déploiement). Résultat final : **reconstruction complète en 18 min, sans aucune action manuelle dans GitLab** | GitLab CE, GitLab CI, Docker, Ansible, Vagrant/VMware | Terminé |
| [**lab-k8s-gitops**](https://github.com/artuthur/lab-k8s-gitops) | Découvrir Kubernetes en installant moi-même un cluster multi-nœuds avec kubeadm, sans distribution simplifiée, pour comprendre chaque composant, puis le déploiement GitOps | Kubernetes, kubeadm, containerd, Vagrant/VMware | En cours |
| lab-windows-ad | Monter un environnement Microsoft d'entreprise entièrement à la main, sans automatisation, pour en maîtriser les bases : Active Directory, GPO, et Microsoft 365 / Intune dans la mesure du possible | Windows Server, Active Directory, GPO | Prévu |
| Durcissement et supervision Windows | Sécuriser et superviser l'infrastructure de lab-windows-ad | Windows Server | Prévu |
| Attaque et défense AD | Comprendre les attaques courantes contre Active Directory pour savoir les détecter et s'en protéger | Active Directory | Prévu |
| lab-terraform-cloud | Provisionner une infrastructure cloud avec Terraform | Terraform | Prévu |

Chaque dépôt commence par l'essentiel (objectif, architecture, démarrage rapide), puis détaille mon cheminement : choix techniques, sécurité et limites, journal de bord.

## Compétences

- **Systèmes** : Linux (Debian/Ubuntu), Windows Server, Active Directory, Office 365
- **Automatisation et IaC** : Ansible (rôles, Vault, `ansible-lint --profile production`), Vagrant, Terraform
- **Conteneurs et CI/CD** : Docker, Docker Swarm, GitLab CI, registre de conteneurs
- **Réseau et sécurité** : Cisco IOS, HAProxy, Traefik, PKI/TLS, UFW
- **Supervision et support** : Zabbix, GLPI
- **Bases de données et scripts** : PostgreSQL, SQL, Python, Bash
- **Cloud** : notions GCP, Azure, OVH Cloud

## Expérience

- **SIRAIL** (Crespin, 2025) · Stage : déploiement de postes WDS/MDT, support N1/N2 sous GLPI, rédaction de procédures
- **Acteam-IT** (Roubaix, 2024) · Stage : Docker Swarm et Zabbix, reverse proxy Traefik avec TLS, administration PostgreSQL

## En ce moment

- Je prépare **lab-k8s-gitops** pour découvrir Kubernetes
- Je me forme en autonomie sur la cybersécurité et les réseaux : préparation de la certification **Fortinet NSE 1**, parcours **Cisco Skills for All** (badges *Network Basics* et *Network Security* obtenus)

## Me contacter

- LinkedIn : [Debacq Arthur](https://www.linkedin.com/in/arthur-debacq-a17143233/)
- E-mail : arthur.debacq@hotmail.fr
