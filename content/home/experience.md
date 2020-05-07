+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Analyste Informatique / DevOps"
  company = "Universit&eacute; du Qu&eacute;bec &agrave; Montr&eacute;al - UQ&Agrave;M"
  company_url = "https://uqam.ca"
  location = "Montréal"
  date_start = "2018-05-01"
  date_end = ""
  description = """

  Responsibilities include:
  
  * Planifier, implémenter et documenter la migration d’une partie des services on-premise vers les services autogérés de AWS;
  * Mettre en place deux clusters kubernetes 1.12 (un cluster de développement et de production) résilient et haute disponibilité sur une infrastructure VMware VCenter totalement IaC, avec possibilité de mise à jour Canary des noeuds du cluster;
  * Ecrire des recettes Puppet 5 pour provisionner les nouveaux serveurs VMs de l’infrastructure et migrer les serveurs de Puppet 3 à Puppet 5;
  * Supporter les équipes de développement dans la migration les applications legacy (plus de 80 applications) vers les applications conteneurisées, vers des applications microservices et les déployer via des pipelines CI/CD sur le cluster Kubernetes de production;
  * Supporter les équipes de développement dans la mise	en place des pipelines de développement intégrant les tests unitaires et fonctionnels ainsi les tests de sécurité;
  * Mettre en place une application nommée APIINFRA en python servant de point d’entrée pour gérer et le fournir les ressources du cluster Kubernetes en self-service via un processus/workflow jira - amazon sqs - apiinfra - bitbucket - jenkins - puppet - k8s;
  * Mise en place d’un cluster EKS sur AWS et migration de certains services et applications
  * Preuve de concept GKE sur Google Cloud, Preuve de concept Openshift;
  * Mise en place d’un cluster AKS sur Azure et migration de certains services et applications;
  * Mise en place de la suite Grafana et Prometheus pour mesurer les métriques des applications et des noeuds Kubernetes;
  * Mise en place de la suite Elasticsearch, APM, Fluentd et Kibana pour monitorer les applications;
  * Administrer les dépôts de gestion de code sources (bitbucket cloud), conseiller et documenter les bonnes pratiques en matière de système de nommage des branches adaptés aux projets;
  * Lead une équipe de 3 techniciens informatiques;
  * Mettre en place les bonnes pratiques DevOps, choisir les outils adaptés pour chacun des projets;
  * Développer la dynamique Agile - DevOps - Kanban.
  """

[[experience]]
  title = "Administrateur système / DevOps"
  company = "Adaware"
  company_url = ""
  location = "Montréal"
  date_start = "2016-07-01"
  date_end = "2018-05-21"
  description = """
  
  Responsibilities include:
  
  * Automatiser la création des environnements de test pour les développeurs avec Ansible;
  * Automatiser la création des environnements de pré-production et production pour la mise en production avec Ansible;
  * Développer des tests unitaires automatisés afin de garantir le bon fonctionnement du produit et sauver du temps avant la mise en production;
  * Faire de l’intégration continue et du déploiement continue afin d’accélérer la mise en service des nouvelles fonctionnalités d’un produit ou d’un nouveau produit;
  * Assurer le monitoring et la veille technologique;
  * Supporter les utilisateurs des applications et des ressources partagées;
  * Documenter les procédures de maintenance;
  """

[[experience]]
  title = "Technicien en support technique informatique"
  company = "Upclick"
  company_url = ""
  location = "Montréal"
  date_start = "2016-02-01"
  date_end = "2018-07-07"
  description = """
  
  Responsibilities include:
  
  * Quart d’heure de travail : de minuit à 8h30;
  * Répondre aux appels téléphoniques des clients;
  * Se connecter et dépanner leurs ordinateurs et tablettes à distance;
  * Donner des conseils pratiques dans l’utilisation de leurs équipements informatiques;
  * Documenter les procédures de maintenance;
  """

[[experience]]
  title = "Analyste informatique / Administrateur des systèmes"
  company = "SIGES / Université de Dschang"
  company_url = ""
  location = "Cameroun"
  date_start = "2011-12-01"
  date_end = "2015-12-20"
  description = """
  
  Responsibilities include:
  
  * Administrer 3 serveurs physiques et 28 serveurs virtuels dans un environnement mixte Windows en majorité et Linux pour certain comprenant des contrôleurs de domaine, Stratégies de  groupes, serveur DHCP, serveur de messagerie Exchange, serveur de Voip, pare-feu/passerelle/proxy, serveur Linux Apache MySQL PhP hébergeant le système de gestion de scolarité de l’université, et des serveurs de backup/réplication/monitoring;
  * Déployer Microsoft SharePoint pour la gestion de nos services Intranet;
  * Mettre en place et administrer les comptes des utilisateurs du système;
  * Mettre en place des solutions de sauvegarde et de restauration automatique du système;
  * Automatiser l’exécution de certaines tâches d’administration des serveurs;
  * Faire la veille technologique sur ces serveurs;
  * Sauvegarder le système en local et hors site (en ligne);
  * Documenter toutes les actions surs les serveurs;
  * Former et faire du support technique aux utilisateurs des services réseaux et ressources partagées.
  """

[[experience]]
  title = "Consultant / intégrateur des solutions web"
  company = "k2m digital consulting"
  company_url = ""
  location = "Montréal"
  date_start = "2013-12-01"
  date_end = ""
  description = """
  
  Responsibilities include:
  
  * Hebergement de plateforme web;
  * Administer les services des clients sur les fourbisseurs de cloud (AWS, GCP, Azure);
  * Ecrire de API pour de clients;
  * Faire de l'accompagnement start-up.
  """

+++
