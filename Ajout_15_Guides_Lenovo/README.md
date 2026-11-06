# MaintiDoc
### Assistant documentaire multimodal pour la maintenance informatique

**Réalisé par :** Zainab BELGAS  
**Encadré par :** Pr. Mariam CHERRABI  
**Module :** IA générative multimodale  
**Établissement :** EMSI  

---

## Présentation

MaintiDoc est un projet d’assistant destiné aux techniciens de maintenance d’ordinateurs portables et de tablettes Lenovo. Il vise à faciliter la recherche dans les manuels techniques, à exploiter les schémas et les photographies de maintenance, et à préparer des tickets à partir des informations recueillies.

Chaque réponse doit s’appuyer sur des références consultables. Lorsque les sources sont insuffisantes ou que l’équipement n’est pas clairement identifié, l’assistant demande des précisions.

## Cas d’usage

- Retrouver une procédure adaptée au modèle et au symptôme signalé.
- Associer une question ou une image aux passages et figures utiles de la documentation.
- Consulter l’historique des interventions d’un équipement.
- Préparer un ticket et soumettre son contenu à la validation du technicien avant sa création.

## Périmètre

Le projet porte sur deux familles d’équipements :

| Famille | Modèles de référence |
|---|---|
| Ordinateurs portables | Lenovo ThinkPad T480 (corpus principal) |
| Tablettes | Lenovo TAB 2 A10-70 |

MaintiDoc apporte une aide documentaire. L’interprétation d’une image ne suffit pas à confirmer une panne ; le technicien conserve la décision d’intervention.

## Architecture envisagée

| Composant | Rôle prévu |
|---|---|
| Interface web | Saisie des questions, ajout d’images et consultation des sources |
| API FastAPI | Gestion des requêtes et contrôle des accès |
| Orchestrateur LangGraph | Coordination des agents et validation humaine |
| Recherche documentaire avec LangChain | Récupération des passages et des éléments visuels pertinents |
| Modèle vision-langage | Analyse des images en lien avec les documents retrouvés |
| Service MCP | Consultation des historiques et gestion des tickets de démonstration |

## Données et documentation

Le corpus de travail rassemble des manuels, des procédures, des schémas et des photographies de maintenance. L’inventaire conserve la provenance, la version, le périmètre matériel et les conditions d’utilisation de chaque document.

Les documents et images de tiers conservent leurs licences et leurs attributions. Leur intégration au dépôt dépend des droits de redistribution applicables.

## Avancement

Le projet est au stade du cadrage, de l’organisation du corpus et de la conception de l’architecture. Les prochaines étapes portent sur la recherche documentaire, l’intégration multimodale, les outils de maintenance et l’évaluation.


## Composition du corpus

La sélection documentaire comprend 30 fichiers : 15 guides français ThinkPad T480, 6 guides Lenovo TAB 2 A10-70 en anglais, 6 photos de réparation tablette et 3 documents de test. Les versions T14/P14s sont conservées en réserve. Les traductions signalées comme automatiques sont indiquées dans l’inventaire et doivent être relues.
