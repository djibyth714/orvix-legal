---
title: Politique de confidentialité — Orvix IPTV
---

# POLITIQUE DE CONFIDENTIALITÉ

**Application : Orvix IPTV**  
**Version : 1.0**  
**Dernière mise à jour : 9 octobre 2026**  
**Responsable du traitement : DF Prod Lab**

## 1. Introduction

La présente Politique de confidentialité explique comment l’application Orvix IPTV traite les données liées à son utilisation.

L’Application est un lecteur multimédia IPTV permettant aux utilisateurs d’importer leurs propres playlists M3U/M3U8, de configurer leurs sources compatibles avec Xtream Codes et de lire les contenus accessibles depuis ces sources.

Dans sa version de base, l’Application est conçue pour fonctionner sans création obligatoire de compte utilisateur et sans serveur central nécessaire à son fonctionnement.

La protection des données personnelles et la sécurité des informations enregistrées sur l’appareil constituent des principes de conception de l’Application.

## 2. Responsable du traitement

Le responsable du traitement est :

* Nom : DF Prod Lab
* Adresse électronique : dfprodlab@gmail.com
* Site Internet : https://djibyth714.github.io/orvix-legal/

Pour toute question relative à la protection des données personnelles, vous pouvez contacter le responsable du traitement à l’adresse indiquée ci-dessus.

Aucun délégué à la protection des données (DPO) n’a été désigné.

## 3. Principe de fonctionnement local

Dans sa version de base, l’Application enregistre certaines informations directement sur l’appareil de l’utilisateur.

Ces informations peuvent comprendre :

* les noms et adresses des playlists ajoutées ;
* les chaînes et catégories importées ;
* les favoris ;
* l’historique et la progression de lecture ;
* les préférences du lecteur ;
* les données EPG mises en cache ;
* les paramètres de l’Application.

Ces données sont utilisées pour fournir les fonctionnalités demandées par l’utilisateur.

La base de données locale SQLite ne constitue pas, à elle seule, un service de stockage centralisé. Les données d’un appareil ne sont pas automatiquement synchronisées avec celles d’un autre appareil.

## 4. Identifiants IPTV et données d’authentification

Lorsque l’utilisateur configure une source utilisant Xtream Codes ou un mécanisme équivalent, l’Application peut traiter :

* l’adresse du serveur ;
* le nom d’utilisateur ;
* le mot de passe ;
* les informations nécessaires à la connexion ;
* les réponses techniques du serveur.

Les secrets doivent être conservés dans le stockage sécurisé de la plateforme, lorsque cela est techniquement possible, notamment le Keychain sur les appareils Apple et un mécanisme sécurisé équivalent sur Android.

Les mots de passe ne doivent pas être enregistrés en clair dans la base SQLite ni apparaître dans les journaux techniques.

Lorsque l’utilisateur se connecte à un serveur IPTV externe, les informations nécessaires à cette connexion sont transmises à ce serveur. L’opérateur de ce serveur peut traiter ces informations conformément à ses propres pratiques et obligations légales.

L’utilisateur doit donc vérifier la fiabilité du fournisseur auquel il transmet ses identifiants.

## 5. Données transmises aux fournisseurs IPTV

Pour lire une chaîne, importer un catalogue distant ou récupérer un guide des programmes, l’Application doit parfois communiquer avec des serveurs externes.

Ces serveurs peuvent recevoir des données techniques telles que :

* l’adresse IP de connexion ;
* les requêtes HTTP ou HTTPS ;
* l’URL de la ressource demandée ;
* les identifiants nécessaires à l’authentification, lorsqu’ils sont utilisés ;
* les informations techniques indispensables à la réponse du serveur.

Ces traitements sont effectués afin de permettre la connexion, l’importation et la lecture des contenus demandés.

Les serveurs externes sont exploités par des tiers qui ne sont pas nécessairement contrôlés par l’éditeur de l’Application. Leur politique de confidentialité et leur durée de conservation des données doivent être vérifiées directement auprès de ces opérateurs.

## 6. Données que l’Application ne demande pas dans sa version de base

Sous réserve des fonctionnalités effectivement intégrées, l’Application n’exige pas :

* la création d’un compte personnel ;
* le nom et le prénom de l’utilisateur ;
* son adresse postale ;
* son numéro de téléphone ;
* l’accès à ses contacts ;
* l’accès à sa localisation précise.

L’Application ne doit pas collecter ces données sans nécessité fonctionnelle, information appropriée et fondement juridique valable.

La présente section devra être actualisée si une version future introduit des comptes, de la synchronisation, de la publicité ou des services d’analyse.

## 7. Finalités et bases juridiques

Les données éventuellement traitées sont utilisées uniquement pour des finalités déterminées.

| Finalité                                                 | Base juridique possible, selon le contexte                  |
| -------------------------------------------------------- | ----------------------------------------------------------- |
| Enregistrer les playlists et préférences locales         | Exécution des fonctionnalités demandées                     |
| Authentifier une source IPTV                             | Exécution de la demande de connexion                        |
| Charger un flux ou un EPG                                | Exécution de la fonctionnalité sollicitée                   |
| Diagnostiquer une anomalie, si des rapports sont activés | Base juridique à déterminer et information préalable        |
| Répondre à une demande d’assistance                      | Mesures précontractuelles, contrat ou autre base applicable |
| Respecter une obligation légale                          | Obligation légale                                           |

La base juridique définitive doit être déterminée par le responsable du traitement en fonction des opérations réellement mises en œuvre.

Lorsque le consentement est requis, l’utilisateur doit pouvoir le retirer dans les conditions prévues par la réglementation applicable.

## 8. Publicité, statistiques et services tiers

Dans la version de base décrite par la présente politique, aucun outil publicitaire ni outil d’analyse comportementale n’est prévu.

Si des SDK publicitaires, outils de mesure d’audience, services de diagnostic externes, services de synchronisation ou autres composants tiers sont ajoutés, leur fonctionnement devra être évalué avant publication.

La présente politique devra alors préciser, selon le cas :

* les données collectées ;
* les finalités du traitement ;
* les destinataires ;
* les éventuels transferts internationaux ;
* les durées de conservation ;
* les mécanismes de consentement ou d’opposition applicables.

Les informations déclarées dans les fiches de confidentialité d’Apple et de Google devront correspondre aux pratiques réelles de l’Application et de ses composants tiers.

## 9. Partage des données

L’éditeur ne vend pas les données personnelles des utilisateurs.

Dans la version de base, les informations nécessaires à la connexion ou à la lecture sont transmises aux serveurs que l’utilisateur a lui-même configurés ou auxquels il demande à l’Application d’accéder.

Les données peuvent également être communiquées lorsque la loi l’impose ou lorsque cela est nécessaire à la défense de droits en justice, dans les limites prévues par la réglementation.

Tout nouveau partage avec un prestataire technique devra être évalué et décrit de manière transparente.

## 10. Conservation et suppression

Les données enregistrées localement sont conservées sur l’appareil jusqu’à leur suppression par l’utilisateur, leur remplacement ou leur effacement dans le cadre du fonctionnement normal de l’Application.

L’utilisateur doit pouvoir, selon les fonctionnalités effectivement disponibles :

* supprimer une playlist ;
* effacer son historique ;
* vider le cache ;
* supprimer les identifiants enregistrés ;
* effacer les données locales ;
* désinstaller l’Application.

La suppression d’une source doit également supprimer les secrets associés lorsque cela est prévu par l’architecture de stockage.

La désinstallation entraîne généralement la suppression des données privées de l’Application, mais certains fichiers exportés ou sauvegardes gérés par le système peuvent subsister.

Sur iOS, la base de données locale de l’Application peut être incluse dans la sauvegarde iCloud ou ordinateur de l’appareil, selon les réglages de l’utilisateur ; les identifiants enregistrés dans le Keychain ne sont pas transférés vers un autre appareil. Sur Android, la sauvegarde automatique des données de l’Application est désactivée.

Les fichiers de sauvegarde exportés volontairement par l’utilisateur depuis l’Application ne contiennent jamais de mot de passe ni d’adresse de playlist : après restauration, l’utilisateur ressaisit ses identifiants.

Les données éventuellement conservées par un fournisseur IPTV ou un autre service tiers doivent être supprimées selon les règles et procédures de ce fournisseur.

## 11. Sécurité

L’éditeur met en œuvre des mesures techniques et organisationnelles proportionnées aux risques et aux caractéristiques de l’Application.

Ces mesures doivent notamment inclure, lorsque techniquement applicable :

* le stockage sécurisé des identifiants ;
* la protection des communications par HTTPS lorsque le serveur le permet ;
* la limitation des données enregistrées ;
* l’absence de mots de passe en clair dans les journaux ;
* la validation des URL et des fichiers importés ;
* la gestion des erreurs sans divulgation des secrets ;
* la mise à jour des dépendances ;
* la suppression des données lorsque l’utilisateur le demande.

Aucun système informatique ne peut garantir une sécurité absolue. L’utilisateur reste responsable de la sécurité de son appareil et du choix de ses fournisseurs externes.

## 12. Droits des personnes

Lorsque la réglementation applicable, notamment le Règlement général sur la protection des données (RGPD), s’applique, les personnes concernées peuvent disposer des droits suivants :

* droit d’accès ;
* droit de rectification ;
* droit à l’effacement ;
* droit à la limitation du traitement ;
* droit d’opposition ;
* droit à la portabilité, lorsque ses conditions sont réunies ;
* droit de retirer un consentement lorsque le traitement repose sur celui-ci ;
* droit d’introduire une réclamation auprès d’une autorité de contrôle compétente.

Pour exercer ces droits, vous pouvez écrire à : dfprodlab@gmail.com.

La demande doit contenir suffisamment d’informations pour permettre son traitement, sans transmettre de mot de passe IPTV ni d’autre secret inutile.

Le responsable du traitement répond dans les délais prévus par la réglementation applicable. Une vérification proportionnée de l’identité peut être effectuée si cela est nécessaire pour protéger les données concernées.

Pour les utilisateurs situés en France, l’autorité de contrôle est la Commission nationale de l’informatique et des libertés (CNIL) : https://www.cnil.fr/.

## 13. Transferts internationaux

L’Application peut accéder à des serveurs tiers situés dans différents pays, selon les sources configurées par l’utilisateur.

Ces connexions peuvent impliquer le transfert de données techniques vers les pays où ces serveurs sont exploités.

L’éditeur ne détermine pas nécessairement la localisation de ces serveurs. L’utilisateur est invité à consulter les conditions et la politique de confidentialité de son fournisseur.

Si l’éditeur met ultérieurement en place un service cloud ou fait appel à des prestataires qui transfèrent des données personnelles hors de l’Espace économique européen, il devra vérifier et mettre en place les garanties requises par la réglementation applicable.

## 14. Données des mineurs

L’Application n’est pas spécifiquement destinée aux enfants.

L’utilisateur doit respecter les règles applicables à la protection des mineurs et à l’accès aux contenus.

Si l’Application est ultérieurement conçue ou commercialisée comme une application destinée aux enfants, des exigences supplémentaires relatives à la confidentialité, aux autorisations et à la conception devront être évaluées avant sa publication.

## 15. Modifications de la politique

La présente politique peut être modifiée pour tenir compte de l’évolution des fonctionnalités, des obligations légales ou des pratiques de traitement.

La date de dernière mise à jour sera indiquée en tête du document.

En cas de modification substantielle nécessitant une information ou un consentement spécifique, les mesures appropriées seront mises en œuvre avant l’application du nouveau traitement.

## 16. Contact

Pour toute question relative à la présente Politique de confidentialité ou à la protection des données :

**Responsable du traitement : DF Prod Lab**  
Contact par e-mail uniquement.  
E-mail : dfprodlab@gmail.com  
Site Internet : https://djibyth714.github.io/orvix-legal/

---

*Fin de la Politique de confidentialité.*
