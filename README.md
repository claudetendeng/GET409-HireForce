# 💼 SmartRecrut

> **Plateforme intelligente de recrutement automatisé par Intelligence Artificielle**

## 📌 Problématique

Les responsables RH consacrent énormément de temps au traitement des candidatures : lecture des CV, présélection, organisation des entretiens, suivi des candidats et communication.

Ces tâches sont longues, répétitives et peuvent entraîner des erreurs ou des biais humains.

---

# 🚀 Solution

**SmartRecrut** est une plateforme de recrutement intelligente qui automatise les premières étapes du recrutement grâce à plusieurs agents IA.

L'application permet aux recruteurs de gérer l'ensemble du processus de recrutement tandis que les candidats peuvent postuler, passer un entretien automatisé par IA et suivre l'évolution de leurs candidatures.

L'objectif est de réduire considérablement le temps de recrutement tout en améliorant la qualité des présélections.

---

## 👥 Équipe
| Membre | Rôle |
|--------|------|
| Claude Emmanuel Tendeng | Chef de produit |
| Thierno Diop | Dev UI |
| Fatoumata Binetou SEYE | Prompt Engineer |
| Caroline Ndiaye | Responsable Impact |
| Abdoulaye SOUMARE | Dev UI |


## 🚀 Démo en ligne
👉 **[https://smart-recrut.vercel.app](https://smart-recrut.vercel.app)**
*(⚠️ Remplacez cette URL par votre véritable URL Vercel une fois le déploiement finalisé)*

## 🛠️ Stack technique
- **Frontend** : React + Tailwind CSS + Vite
- **IA & Workflow** : Dify (Agentique)
- **Génération No-Code** : Bolt.new
- **Déploiement** : Vercel
- **Documentation** : Claude.ai

# 🤖 Les Agents IA

## 📄 Agent Parser

Analyse automatiquement le CV du candidat.

Il extrait :

* les compétences
* les diplômes
* les expériences
* les certifications
* les langues
* les technologies maîtrisées

Puis il construit automatiquement le profil du candidat.

---

## 🎤 Agent Testeur

Après le dépôt du CV, l'IA génère automatiquement un entretien de présélection.

Le candidat répond à des questions adaptées au poste demandé.

L'entretien comporte des règles anti-triche :

* interdiction du copier/coller
* changement d'onglet interdit
* fermeture ou actualisation de la page = entretien recommencé
* chronomètre pour chaque question

---

## 📊 Agent Évaluateur

Une fois l'entretien terminé, l'IA calcule automatiquement :

* Score global
* Score des compétences
* Score technique
* Score comportemental
* Niveau d'adéquation avec le poste

Le recruteur visualise immédiatement les meilleurs candidats.

---

## 📅 Agent Planificateur

Le recruteur peut sélectionner un candidat afin de programmer un entretien physique ou visio.

L'agent :

* crée automatiquement la convocation
* envoie un email au candidat
* affiche la convocation dans son espace personnel
* ajoute les instructions de l'entretien
* permet au recruteur de modifier le message avant l'envoi

Après la date de l'entretien RH, le dossier passe automatiquement en attente de décision finale.

---

# 👥 Deux espaces de connexion

## 👨‍💼 Recruteur

Le recruteur possède un tableau de bord complet.

### Dashboard

* Nombre de candidatures
* Nombre d'entretiens IA
* Nombre de recrutements
* Nombre de refus
* Top candidats
* Scores moyens
* Statistiques

### Gestion des candidats

Pour chaque candidat :

* CV
* Score IA
* Résultat de l'entretien IA
* Historique
* Planifier un entretien
* Refuser automatiquement
* Recruter après entretien RH

Le recrutement n'est disponible que si l'entretien RH est terminé.

---

## 👩‍💻 Candidat

Le candidat possède un espace personnel simple.

Il peut :

* compléter son profil
* ajouter une photo
* consulter son nom et son email
* déposer un CV
* sélectionner le poste auquel il postule
* passer l'entretien IA
* consulter son historique
* recevoir ses convocations
* suivre l'état de ses candidatures

Les états possibles sont uniquement :

* En évaluation
* Entretien
* Refusé
* Recruté

Le statut "Évalué" n'existe pas.

---

# 📩 Notifications

Lorsqu'un recruteur planifie un entretien :

Le candidat reçoit automatiquement :

* une notification dans son espace personnel
* un email de convocation

Le message contient :

* la date
* l'heure
* le lieu ou le lien visio
* les consignes
* les documents à préparer

Le recruteur peut personnaliser ce message avant son envoi.

---

# 💬 Assistant IA

Chaque utilisateur dispose d'un chatbot intelligent.

## Chatbot Candidat

Il peut :

* expliquer les étapes du recrutement
* répondre aux questions
* aider à préparer l'entretien
* expliquer le score obtenu
* guider le dépôt du CV

---

## Chatbot Recruteur

Il peut :

* rechercher un candidat
* expliquer les scores
* recommander les meilleurs profils
* générer des comptes rendus
* assister dans la planification des entretiens
* répondre aux questions RH

---

# 📈 Tableau de bord

Le Dashboard affiche :

* Nombre de candidats
* Nombre d'entretiens IA
* Entretiens RH programmés
* Recrutements
* Refus
* Top 10 des meilleurs scores
* Répartition des candidatures
* Statistiques en temps réel

---

# ⭐ Fonctionnalités principales

* Authentification Recruteur / Candidat
* Dépôt de CV
* Analyse IA automatique
* Entretien IA automatisé
* Score intelligent
* Classement des meilleurs candidats
* Historique des candidatures
* Notifications
* Emails automatiques
* Planification des entretiens
* Gestion des recrutements
* Chatbot IA
* Tableau de bord RH
* Mode anti-triche pendant les entretiens
* Profil utilisateur avec photo

---

# 🛠️ Stack technique

* Frontend : React
* Tailwind CSS
* Vite
* IA : OpenAI / Dify
* Base de données : Supabase
* Authentification : Supabase Auth
* Emails : Resend
* Déploiement : Vercel

---

# ⚖️ Éthique

SmartRecrut respecte plusieurs principes :

* l'IA assiste le recruteur mais ne décide jamais seule
* chaque score est expliqué
* les décisions finales restent humaines
* protection des données personnelles
* limitation des biais grâce à l'automatisation des premières étapes

---

# 🎯 Parcours utilisateur

### Candidat

Inscription → Connexion → Choix du poste → Dépôt du CV → Analyse IA → Entretien IA → En évaluation → Convocation RH → Entretien RH → Recruté ou Refusé

---

### Recruteur

Connexion → Dashboard → Analyse des scores → Sélection des meilleurs candidats → Planification des entretiens → Convocation automatique → Décision finale → Recrutement ou Refus

---

## ⚖️ Éthique, Transparence & Lutte contre les biais

SmartRecrut a été conçu pour accompagner les recruteurs tout en favorisant un processus de recrutement plus équitable, transparent et responsable.

### 🕵️ Mode Anonyme

Lors de la phase de présélection, les informations susceptibles d'introduire des biais (nom, photo, sexe ou autres données personnelles non essentielles) peuvent être masquées afin que l'évaluation repose principalement sur les compétences, les expériences et les qualifications du candidat.

### 🧠 Explicabilité de l'IA (XAI)

Les décisions de l'IA sont transparentes. Chaque score est accompagné d'une explication détaillant les critères pris en compte, tels que la correspondance des compétences, l'expérience professionnelle, les diplômes, les certifications et les résultats de l'entretien IA. Le recruteur comprend ainsi pourquoi un candidat obtient un score donné.

### 👤 L'humain reste décisionnaire

L'IA intervient uniquement comme un assistant d'aide à la décision. Elle analyse les candidatures, organise les premières étapes du recrutement et propose un classement des profils. La décision finale de recruter ou de refuser un candidat appartient exclusivement au recruteur après l'entretien RH.

### 🔒 Protection des données personnelles

Les informations des candidats sont traitées de manière sécurisée et ne sont accessibles qu'aux utilisateurs autorisés. Les données sont utilisées uniquement dans le cadre du processus de recrutement et conformément aux bonnes pratiques de confidentialité.

### 🛡️ Intégrité des entretiens IA

Afin de garantir une évaluation équitable, SmartRecrut intègre plusieurs mécanismes anti-triche durant l'entretien automatisé :

* le copier-coller est désactivé ;
* quitter ou actualiser la page entraîne le redémarrage de l'entretien ;
* chaque question est limitée dans le temps ;
* toutes les réponses sont enregistrées automatiquement.

### ⚖️ Égalité des chances

Tous les candidats passent le même processus de présélection, avec des critères d'évaluation identiques et des règles communes. Cette approche contribue à limiter les biais et à garantir une évaluation plus objective des candidatures.


**Projet réalisé dans le cadre du cours GET 409 – Swiss UMEF University – Campus de Dakar – Juillet 2026**

