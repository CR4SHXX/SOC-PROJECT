# SOC-LAB - Detection, investigation et reponse aux incidents

## Sommaire

1. [Presentation du projet](#1-presentation-du-projet)
2. [Architecture et environnement du SOC](#2-architecture-et-environnement-du-soc)
3. [Outils et technologies](#3-outils-et-technologies)
4. [Fonctionnement du SOC](#4-fonctionnement-du-soc)
5. [Supervision et detection des menaces](#5-supervision-et-detection-des-menaces)
6. [Automatisation et playbooks SOAR](#6-automatisation-et-playbooks-soar)
7. [Gestion des alertes et reponse aux incidents](#7-gestion-des-alertes-et-reponse-aux-incidents)
8. [Simulation d'attaques et scenarios de validation](#8-simulation-dattaques-et-scenarios-de-validation)
9. [Resultats, limites et ameliorations](#9-resultats-limites-et-ameliorations)
10. [Documentation technique](#10-documentation-technique)
11. [Competences developpees](#11-competences-developpees)
12. [Ressources et references](#12-ressources-et-references)

---

## 1. Presentation du projet

### 1.1 Contexte

J'ai realise ce projet pour approfondir mes competences en securite defensive et mettre en pratique les concepts lies au fonctionnement d'un Security Operations Center (SOC).

Pour cela, j'ai mis en place un laboratoire SOC local en utilisant plusieurs solutions open source comme Wazuh, Shuffle, TheHive et Cortex.

L'objectif n'est pas de reproduire un SOC d'entreprise complet, mais de construire un environnement defensif adapte a l'etude de quelques techniques d'attaque specifiques issues de MITRE ATT&CK.

Je vais preparer et configurer ce SOC pour detecter ces techniques, automatiser le traitement des alertes et tester les mecanismes de reponse a travers des simulations d'attaques controlees.

### 1.2 Objectif general

Mon objectif est de concevoir et mettre en place un SOC local capable de collecter et analyser des evenements de securite, detecter des comportements suspects et automatiser certaines actions de traitement et de reponse aux incidents.

Je cherche egalement a evaluer le fonctionnement de cette chaine defensive a travers des simulations d'attaques controlees basees sur des techniques MITRE ATT&CK.

### 1.3 Objectifs specifiques

- **Supervision et collecte** : centraliser les journaux de securite des endpoints Windows et Linux pour surveiller les activites du systeme.

- **Detection des menaces** : utiliser Wazuh et ses regles de detection pour identifier des comportements suspects et generer des alertes de securite.

- **Automatisation et orchestration** : developper des playbooks Shuffle pour automatiser le traitement des alertes et certaines actions de reponse.

- **Gestion des incidents** : integrer TheHive et Cortex pour faciliter la creation de cas, l'enrichissement des alertes et le suivi des incidents.

- **Simulation d'attaques** : utiliser Atomic Red Team et MITRE Caldera pour reproduire des techniques d'attaque dans un environnement controle.

- **Validation defensive** : tester la chaine de detection et de reponse sur quelques scenarios precis et analyser les resultats obtenus.

- **Documentation technique** : documenter l'architecture, les configurations, les regles, les playbooks et les scenarios avec leurs resultats et preuves.

## 2. Architecture et environnement du SOC

## 3. Outils et technologies

| Categorie | Outils | Role |
|---|---|---|
| SIEM / XDR | Wazuh | Supervision, collecte et detection |
| SOAR | Shuffle | Automatisation et orchestration |
| Gestion des incidents | TheHive | Gestion et suivi des cas |
| Analyse et enrichissement | Cortex | Analyse des observables |
| Infrastructure | Docker, Docker Compose | Deploiement des services |
| Collecte des evenements | Wazuh Agent, Sysmon | Surveillance des endpoints |
| Simulation d'attaques | Atomic Red Team, MITRE Caldera | Tests des capacites defensives |
| Framework | MITRE ATT&CK | Classification des techniques d'attaque |

## 4. Fonctionnement du SOC

## 5. Supervision et detection des menaces

## 6. Automatisation et playbooks SOAR

## 7. Gestion des alertes et reponse aux incidents

## 8. Simulation d'attaques et scenarios de validation

## 9. Resultats, limites et ameliorations

## 10. Documentation technique

## 11. Competences developpees

## 12. Ressources et references
