

<div align="left">

<img src="https://img.shields.io/badge/Architecture%20SI-2C3E50?style=for-the-badge&logo=diagrams.net&logoColor=white" />
<img src="https://img.shields.io/badge/Web%20%26%20Plateformes-3498DB?style=for-the-badge&logo=googlechrome&logoColor=white" />
<img src="https://img.shields.io/badge/Data-27AE60?style=for-the-badge&logo=databricks&logoColor=white" />
<img src="https://img.shields.io/badge/IA%20G%C3%A9n%C3%A9rative-8E44AD?style=for-the-badge&logo=openai&logoColor=white" />
<img src="https://img.shields.io/badge/Automatisation-E67E22?style=for-the-badge&logo=zapier&logoColor=white" />

</div>



```
┌──────────────────────────────────────────────────────────────────────────┐
│  DIRECTEUR TECHNIQUE DIGITAL · ARCHITECTE SOLUTIONS IA                   │
│                                                                          │
│  Transformation numérique · Architecture SI · Intelligence Artificielle  │
│                                                                          │
│  Web · Data · Automatisation · LLM · Machine Learning · Agents IA        │
└──────────────────────────────────────────────────────────────────────────┘
```

📍 Paris / Puteaux · 🔗 [linkedin.com/in/bretonarnaud](https://www.linkedin.com/in/bretonarnaud)

J'accompagne les entreprises dans la conception et l'évolution de leurs plateformes numériques en combinant architecture SI, développement web, intelligence artificielle et automatisation.

Fort d'une expérience dans la réalisation de projets digitaux complexes, je conçois des solutions intégrant IA générative, RAG, agents IA, systèmes de recommandation et workflows intelligents, de l'architecture jusqu'à la mise en production.

Ma conviction : l'IA crée de la valeur lorsqu'elle s'intègre naturellement au système d'information pour rendre les processus plus intelligents, fiables et évolutifs.

```
┌──────────────────────────────────────────────────────────────────────────┐
│  Projets                                                                 │
└──────────────────────────────────────────────────────────────────────────┘
```



### 01 - DataToForm - Automatisation intelligente des processus de contribution

<img src="https://img.shields.io/badge/BtoB-6366F1?style=flat-square"/> <img src="https://img.shields.io/badge/BtoC-6366F1?style=flat-square"/> <img src="https://img.shields.io/badge/Node.js-555?style=flat-square"/> <img src="https://img.shields.io/badge/Playwright-555?style=flat-square"/> <img src="https://img.shields.io/badge/Excel-555?style=flat-square"/>

DataToForm transforme les interfaces métier en parcours de saisie intelligents. À partir d’un fichier Excel, la solution identifie automatiquement les champs, établit le mapping avec le formulaire cible et automatise la saisie dans des environnements web complexes.

Projet SaaS B2B avec une déclinaison B2C, conçu pour réduire les tâches répétitives de contribution, fiabiliser les données saisies et accélérer les opérations métier.

**Valeur**

Réduction du temps de saisie, amélioration de la qualité des données et automatisation des opérations de contribution.

**Cibles**

PME · ETI · grands comptes · agences digitales · e-commerce · éditeurs SaaS · collectivités

**Cas d'usage**

- contribution de catalogues produits
- intégration de contenus dans CMS
- saisie dans CRM, ERP ou SIRH
- migration de données entre applications
- automatisation de formulaires administratifs

→ Site : [www.datatoform.com](http://www.datatoform.com)  
→ Architecture : [Architecture technique](https://github.com/arnoweb/data-to-form/document-architecture.html)

---



### 02 - Moteur IA de recommandation de produits temps réel (RecSys)

<img src="https://img.shields.io/badge/IA-6366F1?style=flat-square"/> <img src="https://img.shields.io/badge/Recommandation-6366F1?style=flat-square"/> <img src="https://img.shields.io/badge/Python-555?style=flat-square"/> <img src="https://img.shields.io/badge/PyTorch-555?style=flat-square"/> <img src="https://img.shields.io/badge/FastAPI-555?style=flat-square"/>

Conception d’un moteur de recommandation combinant filtrage collaboratif et approche item-based afin de proposer des suggestions personnalisées en temps réel.

Le système est exposé via une API REST et une interface de test, ce qui facilite son intégration à tout type de plateforme disposant d'un catalogue de produits ou de contenus, qu'il s'agisse de biens physiques (mode, électronique, etc.) ou de contenus numériques (VOD, ebooks, musique, presse en ligne...).

**Valeur**

Amélioration de l'engagement utilisateur et augmentation des ventes grâce à des recommandations personnalisées.

**Cibles**

E-commerce · médias · streaming · marketplaces · retail · plateformes de contenus

**Cas d'usage**

- recommandations produits
- "Vous pourriez aussi aimer"
- cross-selling
- up-selling
- personnalisation de la page d'accueil
- recommandations de contenus (VOD, musique, ebooks, presse)

→ Démo API : [likyly.com/recsys-api/docs](https://likyly.com/recsys-api/docs)  
→ Architecture : [Architecture technique](https://github.com/arnoweb/recsys-spotlight-pytorch-fastapi/document-architecture.html)  
→ Code : [github.com/arnoweb/recsys-spotlight-pytorch-fastapi](https://github.com/arnoweb/recsys-spotlight-pytorch-fastapi)

---



### 03 - Moteur de recherche FAQ intelligent (RAG & fine-tuning LLM)

<img src="https://img.shields.io/badge/IA-6366F1?style=flat-square"/> <img src="https://img.shields.io/badge/Multilingue-6366F1?style=flat-square"/> <img src="https://img.shields.io/badge/RAG-555?style=flat-square"/> <img src="https://img.shields.io/badge/Python-555?style=flat-square"/> <img src="https://img.shields.io/badge/Hugging%20Face-555?style=flat-square"/>

Développement d’un moteur de recherche sémantique capable d’interroger une base documentaire multilingue et de générer des réponses contextualisées grâce à une architecture RAG.

Le projet compare les performances d’un modèle d’embeddings de base à une version fine-tunée avec Hugging Face AutoTrain, avec suivi de métriques de qualité telles que MRR et Recall@K. Les réponses sont produites par un LLM local afin de garantir confidentialité et maîtrise des traitements.

**Valeur**

Accès instantané à une information fiable tout en conservant la confidentialité des données.

**Cibles**

Service client · support technique · éditeurs logiciels · industrie · banques · assurances · administrations

**Cas d'usage**

- FAQ intelligente
- assistant documentaire interne
- recherche dans procédures
- support collaborateurs
- base de connaissances
- chatbot métier sécurisé

→ Démo RAG : [arnoweb-rag-llm-faq-finetuned-huggingface.streamlit.app](https://arnoweb-rag-llm-faq-finetuned-huggingface.streamlit.app)  
→ Comparatif base vs fine-tuné : [arnoweb-rag-faq-compare-basevsfinetuned-huggingface.streamlit.app](https://arnoweb-rag-faq-compare-basevsfinetuned-huggingface.streamlit.app)  
→ Architecture : [Architecture technique](https://github.com/arnoweb/ai_finetunedmodel_faq_multilingue/document-architecture.html)  
→ Code : [github.com/arnoweb/ai_finetunedmodel_faq_multilingue](https://github.com/arnoweb/ai_finetunedmodel_faq_multilingue)

---



### 04 - Système de gestion de licences

<img src="https://img.shields.io/badge/SaaS-6366F1?style=flat-square"/> <img src="https://img.shields.io/badge/S%C3%A9curit%C3%A9-6366F1?style=flat-square"/> <img src="https://img.shields.io/badge/Python-555?style=flat-square"/> <img src="https://img.shields.io/badge/FastAPI-555?style=flat-square"/> <img src="https://img.shields.io/badge/API%20REST-555?style=flat-square"/>

Conception d’un système générique de gestion de licences couvrant l’ensemble du cycle de vie : création, attribution, validation, renouvellement et révocation.

La solution est exposée via une API REST et utilisée en production pour l’add-on TouchPortal XP-FlightDeck, garantissant un contrôle fiable des accès et une intégration simple avec les applications clientes.

**Valeur**

Protection des logiciels et simplification de la gestion des licences via une API REST.

**Cibles**

Éditeurs de logiciels · SaaS · développeurs indépendants · ISV · éditeurs de plugins

**Cas d'usage**

- activation de licences
- validation en ligne
- renouvellement d'abonnements
- gestion des essais
- limitation d'accès aux fonctionnalités Premium

→ Documentation : [api.xp-flightdeck.com/licenses-api/v1/guides](https://api.xp-flightdeck.com/licenses-api/v1/guides)  
→ Architecture : [Architecture technique](https://github.com/arnoweb/licences-manager-for-softwares-api/document-architecture.html)

---



### 05 - Autres projets

| Projet | Description | Stack | Lien |
|---|---|---|---|
| XPlane-MCP-AI-Connector | Connecteur open-source basé sur le Model Context Protocol reliant le simulateur X-Plane 12 à n'importe quel LLM local, pour un pilotage en langage naturel en temps réel. | <img src="https://img.shields.io/badge/IA%20Agentique-6366F1?style=flat-square"/> <img src="https://img.shields.io/badge/MCP-555?style=flat-square"/> <img src="https://img.shields.io/badge/LLM-555?style=flat-square"/> | [Architecture technique](https://github.com/arnoweb/XPlane-MCP-AI-Connector/document-architecture.html)<br>[Code](https://github.com/arnoweb/XPlane-MCP-AI-Connector) |
| Architecture Web universelle sans API | Architecture full-stack unifiée supprimant la duplication de la logique métier entre back et front, tout en conservant les gains de performance et de SEO du rendu serveur. | <img src="https://img.shields.io/badge/Architecture%20Web-6366F1?style=flat-square"/> <img src="https://img.shields.io/badge/Laravel%2012-555?style=flat-square"/> <img src="https://img.shields.io/badge/React%20SSR-555?style=flat-square"/> | [Architecture technique](https://github.com/arnoweb/kitstarter-laravel-ssr-noapi/document-architecture.html)<br>[Code](https://github.com/arnoweb/kitstarter-laravel-ssr-noapi) |
| Golf & Performance | Étude des facteurs de performance au golf par corrélations statistiques et Machine Learning (projet antérieur). | <img src="https://img.shields.io/badge/Data%20Science-6366F1?style=flat-square"/> <img src="https://img.shields.io/badge/Python-555?style=flat-square"/> <img src="https://img.shields.io/badge/Machine%20Learning-555?style=flat-square"/> | — |
| machine-learning-linearreg-kneighbours-kfold | Régression linéaire, k-NN, validation croisée (k-fold) sur données Airbnb. | <img src="https://img.shields.io/badge/Machine%20Learning-6366F1?style=flat-square"/> <img src="https://img.shields.io/badge/Python-555?style=flat-square"/> <img src="https://img.shields.io/badge/Scikit--learn-555?style=flat-square"/> | [Code](https://github.com/arnoweb/machine-learning-linearreg-kneighbours-kfold) |
| googlecoral | Scripts d'inférence ML embarquée sur Coral Dev Board (Edge TPU). | <img src="https://img.shields.io/badge/Edge%20AI-6366F1?style=flat-square"/> <img src="https://img.shields.io/badge/Python-555?style=flat-square"/> | [Code](https://github.com/arnoweb/googlecoral) |

```
┌──────────────────────────────────────────────────────────────────────────┐
│  Parcours --projets-cles                                                 │
└──────────────────────────────────────────────────────────────────────────┘
```

**2024–2026 — Projets IA générative, ML & IA agentique**
RAG · fine-tuning LLM · systèmes de recommandation · agents IA

**2018–2025 — Directeur de projet technique digital, Mazarine**
Direction technique & MOE multi-comptes · Opéra national de Paris · Accor-Thalassa · Accor-LVMH

**2015–2017 — Chef de projet technique digital, Mazarine**
Sites Maisons de Luxe (Groupe OTB - Maison Margiela, Bottega Veneta)

**2012–2015 — Lead développeur backend, WillUP**
Billetterie, e-commerce, streaming · architecture APIs (Apigee)

**2005–2012 — Développeur full stack, Zone Rouge**
Live scoring temps réel sport automobile (flux XML/SOAP)

```
┌──────────────────────────────────────────────────────────────────────────┐
│  Compétences techniques                                                  │
└──────────────────────────────────────────────────────────────────────────┘
```

**Systèmes IA (IA générative, Machine Learning & automatisation)**
Python · PyTorch · Scikit-learn · FastAPI · LangChain · Hugging Face · Vector DB (Pinecone) · n8n · MCP (Model Context Protocol)

**Développement assisté par IA générative**
Claude Code · Cursor · Codex · Warp · LM Studio

**Architecture & backend**
PHP · Laravel · WordPress · Drupal · React · Node.js · SOA · API / APIM (Apigee)

**Cloud & DevOps**
Docker · AWS · DigitalOcean · Claranet · Linux · Git · CI/CD · load testing

**Pilotage de projet**
Agile / Scrum · Jira · Confluence · Miro · Notion · Smartsheet

**Langues**
Anglais (courant, pro) · Espagnol (intermédiaire)

