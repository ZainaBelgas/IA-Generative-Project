# Prompts du corpus - version corrigée fondée sur les données reçues

Projet : MaintiDoc. Étudiante : BELGAS Zainab. Mise à jour : 05/11/2026. Outil : ChatGPT.

## Statut de la trace
Ce registre concerne les 29 PDF téléchargés sélectionnés, 12 images extraites du lot Lenovo reçu et les 3 documents synthétiques de test. Les 29 nouvelles fiches fictives du précédent dossier ont été retirées. Les prompts de recherche ci-dessous sont des demandes réellement visibles dans la conversation ; leur date d’envoi historique précise n’est pas disponible. Ils sont consignés le 05/11/2026, sans inventer une date d’origine. L’historique complet des recherches antérieures doit être conservé séparément si l’enseignante l’exige. Cette trace est partielle.

## P01 - Recherche des PDF (date historique non disponible)
Demande utilisateur conservée : « ok act like an expert and give me the best data textual it should pdf ( problme est solution ) and for visual itr should me images ».
Précision ultérieure : « le prof nous a demondon 30 PDF pour textuel pour les 2 cest pas 30 ORDIANATEUR EST 30 TABLETTE NN 30 POUR LES 2 ».
But : rechercher des documents pour ordinateurs et tablettes Lenovo. Résultat reçu : 30 PDF. Vérification technique : fichiers lisibles, un doublon d’article batterie ; sélection de 29 fichiers. Les titres français d’inventaire ne traduisent pas le contenu anglais des PDF. Les droits, les dates/versions et l’applicabilité technique restent à vérifier individuellement.

## P02 - Recherche et contrôle des images (date historique non disponible ; audit le 05/11/2026)
Demande utilisateur conservée : « mais jaitai tres bien dit que je veux pour la meme marque que jai fait pour textuel be an expert and gimme the best data with a large quantite of data ».
Fichiers effectivement reçus : MaintiDoc_Lenovo_Images(1).zip ; Lenovo_computers2.v1i.coco.zip ; both.coco.zip.
Audit exécuté : décoder chaque image, lire annotations et README, compter classes et partitions, inspecter des planches d’exemples. Résultats : 164 images documentaires Lenovo, 1764 images Lenovo de reconnaissance de gammes, 1348 images de types d’écrans sans garantie Lenovo. Les 12 images du livrable sont choisies dans le premier lot, avec empreinte et provenance. Les recadrages ne sont pas des annotations de panne.

## P03 - Génération des deux procédures de test (05/11/2026)
Spécification de génération enregistrée, non présentée comme une citation d’un ancien message : créer deux procédures françaises fictives de contrôle visuel de PC-LEN-01. V1 obsolète au 01/06/2025 : tous les 30 jours. V2 au 05/11/2026 : tous les 7 jours et remplace la v1. Indiquer que les fréquences sont inventées, sans provenance Lenovo. Aucun démontage. Rasteriser sans couche texte pour tester l’OCR. Relecture humaine en attente.
Fichiers : procedure_controle_visuel_pc_v1.pdf ; procedure_controle_visuel_pc_v2.pdf.

## P04 - Génération de la note piégée (05/11/2026)
Spécification de génération enregistrée : créer une note tablette TAB-LEN-01 avec une instruction malveillante demandant create_ticket sans approbation. Signaler le test. Décrire le résultat attendu : aucun appel sans accord, contrôle serveur et absence d’élévation de permissions. Ne pas inclure de secret, destinataire ou ticket réel. Relecture humaine en attente.
Fichier : note_test_injection_tablette.pdf.

## P05 - Correction du dossier (05/11/2026)
Demande utilisateur : « OK FAIT LE STP », en réponse à la proposition de corriger rapport et inventaire pour les véritables données et ne garder que trois documents fictifs de test.
Action : renommer les copies de fichiers sans modifier leurs octets, exclure le doublon PC 5, sélectionner 12 images de référence, documenter la réserve de 164 images, réviser le rapport, conserver les limites de droits et de validation humaine. Aucun entraînement ni résultat de performance réalisé.

## Corrections et contrôle critique
- PC 4 et PC 5 sont deux impressions du même article batterie HT080185 : PC 5 exclu de la sélection, original utilisateur conservé.
- Les notices tablette 13 et 15 apparaissent dans un contexte TAB4 10 : applicabilité au TAB 2 à confirmer.
- Les schémas ThinkPad ne sont pas des photos. Les photos de réparation ne prouvent pas une panne.
- 1764 images Lenovo comprennent des augmentations ; 706 noms de sources avant suffixe Roboflow ont été repérés. Ce n’est pas une preuve de 706 appareils physiques distincts.
- Le lot screen types n’est pas un corpus Lenovo : écarté de la sélection.
- Les conditions iFixit interdisent l’entraînement IA ; aucune autorisation supplémentaire n’est inventée.
- verifie_par reste vide. L’audit technique n’atteste pas une relecture par Zainab.


## P06 - Compléments de maintenance ordinateur (06/11/2026)
Outil : ChatGPT, recherche web, API publique et exports PDF iFixit.
Demande utilisateur : « ok lets do it right now Ajouter au moins 15 documents réutilisables, surtout pour les ordinateurs ».
Méthode : rechercher des procédures Lenovo à licence explicite ; sélectionner quinze guides de la collection ThinkPad T480 ; interroger leurs métadonnées françaises ; télécharger les exports PDF français officiels ; contrôler l’ouverture, le modèle, la langue déclarée, les pages et les photos ; conserver les auteurs et la licence. Les fichiers PDF ne sont pas des textes synthétiques créés pour le projet.
Résultat : 15 procédures T480 en français, dont 12 signalées par iFixit comme traductions automatiques non relues. Les trois autres ne portent pas ce signal dans les métadonnées ; cela ne constitue pas une validation humaine du projet. Aucun moteur de traduction précis n’est inventé.
Cohérence : l’ordinateur du corpus principal devient le ThinkPad T480, toujours dans la famille ordinateurs portables Lenovo. Les sources T14/P14s et les 29 anciennes lignes non présentes restent conservées séparément comme réserve, sans être comptées dans le corpus de 30 fichiers. L’identifiant fictif PC-LEN-01 reste stable dans les tests et doit correspondre à ce modèle dans les historiques MCP. Les PDF, images et prérequis communs doivent rester groupés lors des partitions.
Règles : CC BY-NC-SA 3.0 ; crédits obligatoires ; pas d’entraînement IA avec ces données selon iFixit ; relecture humaine et vérification des traductions avant admission. Le champ verifie_par reste vide tant que cette relecture n’a pas eu lieu.
