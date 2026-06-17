# Awesome France API [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of free and useful APIs from French government, institutions and companies.

La France produit un écosystème d'APIs publiques exceptionnellement riche : données ouvertes, registres d'entreprises, géographie, transports, santé, environnement. Cette liste regroupe les plus utiles pour les développeurs qui construisent des produits ciblant la France.

## Contents

- [Gouvernement & open data](#gouvernement--open-data)
- [Entreprises & registre légal](#entreprises--registre-légal)
- [Géographie & adresses](#géographie--adresses)
- [Urbanisme & immobilier](#urbanisme--immobilier)
- [Transports & mobilité](#transports--mobilité)
- [Météo & environnement](#météo--environnement)
- [Santé](#santé)
- [Énergie](#énergie)
- [Droit & législation](#droit--législation)
- [Culture & patrimoine](#culture--patrimoine)
- [Éducation & recherche](#éducation--recherche)
- [Contribuer](#contribuer)

## Gouvernement & open data

- [data.gouv.fr](https://www.data.gouv.fr/) - Plateforme officielle française d'open data. Plus de 50 000 datasets publics, API de recherche et de consommation structurée.
- [api.gouv.fr](https://api.gouv.fr/) - Catalogue officiel des APIs gouvernementales françaises. Point d'entrée pour découvrir les APIs officielles par ministère et cas d'usage.
- [Etalab DataPass](https://datapass.api.gouv.fr/) - Demander l'accès aux APIs publiques qui nécessitent une habilitation (France Connect, Cartobio, etc.).

## Entreprises & registre légal

- [Recherche Entreprises](https://recherche-entreprises.api.gouv.fr/) - API officielle open data SIRENE. Recherche d'entreprises françaises par nom, SIREN, dirigeant, activité. Gratuite, sans clé.
- [INSEE Sirene](https://api.insee.fr/catalogue/) - API officielle INSEE sur les entreprises et établissements français. Nécessite compte développeur.
- [Pappers](https://www.pappers.fr/api) - API commerciale enrichie sur les entreprises françaises : bilans, dirigeants, actes juridiques, annonces BODACC.
- [BODACC](https://bodacc-datadila.opendatasoft.com/explore/) - Bulletin Officiel des Annonces Civiles et Commerciales. Immatriculations, radiations, procédures collectives.

## Géographie & adresses

- [Base Adresse Nationale (BAN)](https://adresse.data.gouv.fr/api-doc/adresse) - Géocodage et géocodage inverse des adresses françaises. API officielle, gratuite, illimitée.
- [Découpage administratif](https://geo.api.gouv.fr/decoupage-administratif) - Régions, départements, communes, EPCI. Données officielles, endpoints REST simples.
- [IGN Géoservices](https://geoservices.ign.fr/services-geoplateforme) - APIs officielles IGN : fond de carte, altimétrie, isodistance, tuiles vectorielles.
- [Code Officiel Géographique (COG)](https://www.insee.fr/fr/information/2560452) - Référentiel officiel INSEE des communes, codes INSEE, évolutions historiques.

## Urbanisme & immobilier

- [PermisAPI](https://permisapi.fr) - REST API des 311 000+ permis de construire en France depuis 2022, géocodés via BAN, webhooks HMAC, SDK Python sur PyPI. Plan gratuit 500 requêtes/mois.
- [Demandes de Valeurs Foncières (DVF)](https://app.dvf.etalab.gouv.fr/) - Toutes les transactions immobilières en France depuis 2014. API open data.
- [Cadastre](https://cadastre.data.gouv.fr/) - Plan cadastral informatisé, parcelles, bâtiments. Formats vectoriels et API.
- [Géorisques](https://www.georisques.gouv.fr/doc-api) - Risques naturels, technologiques, pollution des sols par parcelle ou commune.

## Transports & mobilité

- [SNCF](https://www.digital.sncf.com/startup/api) - Données temps réel et théoriques : horaires trains, gares, perturbations, vélos.
- [Navitia](https://www.navitia.io/) - API multimodale de transports publics en France et en Europe. Itinéraires, horaires, GTFS.
- [PRIM Île-de-France Mobilités](https://prim.iledefrance-mobilites.fr/) - API transports IDF : métro, RER, bus, tram, Velib, temps réel.
- [RATP Open Data](https://data.ratp.fr/) - Horaires, stations, trafic, accessibilité du réseau RATP.
- [transport.data.gouv.fr](https://transport.data.gouv.fr/) - Catalogue national des données de mobilité (GTFS, NeTEx, temps réel).

## Météo & environnement

- [Météo France Data](https://portail-api.meteofrance.fr/) - Observations, prévisions, alertes météo officielles françaises. Plans gratuits limités.
- [Qualité de l'air (Atmo)](https://www.atmo-france.org/api) - Indice qualité air ATMO pour la France métropolitaine et outre-mer.
- [Hub'Eau](https://hubeau.eaufrance.fr/) - APIs sur l'eau : cours d'eau, piézométrie, qualité, poissons, hydrobiologie.

## Santé

- [FINESS](https://finess.sante.gouv.fr/) - Fichier National des Établissements Sanitaires et Sociaux. Tous les établissements de santé français.
- [Base de Données Publique des Médicaments (BDPM)](https://base-donnees-publique.medicaments.gouv.fr/) - Médicaments autorisés en France, notices, compositions, prix.
- [Santé Publique France](https://geodes.santepubliquefrance.fr/) - Indicateurs santé publique par territoire : vaccinations, mortalité, chronique.

## Énergie

- [Enedis Open Data](https://data.enedis.fr/) - Consommation et production électrique, courbes de charge par commune, taux de pénétration ENR.
- [RTE Data Portal](https://data.rte-france.com/) - Mix électrique français temps réel, éCO2mix, disponibilité nucléaire, imports/exports.
- [ADEME Open Data](https://data.ademe.fr/) - Bases carbone, DPE, bilans GES, rénovation énergétique.
- [carbon-fr](https://carbon-fr.kovelt.fr/) - Intensité carbone de l'électricité française (gCO₂eq/kWh), national et 12 régions, à partir des données RTE/éCO2mix (ODRÉ). Séries historiques, prévision jusqu'à 72 h absente de la source, mix de production, échanges transfrontaliers et créneau le plus bas-carbone à venir. Open source, auto-hébergeable, sans clé ni quota.

## Droit & législation

- [Légifrance API](https://developer.aife.economie.gouv.fr/api-catalog-page/api/afa7a78a-8e69-46a7-a98b-02a98be7b2e9) - Textes officiels français : Codes, JORF, jurisprudence, conventions collectives.
- [DILA API](https://www.dila.premier-ministre.gouv.fr/services/api-dila) - Direction de l'information légale et administrative. Circulaires, annonces marchés publics (BOAMP).

## Culture & patrimoine

- [DATATOURISME](https://www.datatourisme.fr/) - Points d'intérêt touristiques officiels, événements, itinéraires en France.
- [Base Mérimée](https://www.pop.culture.gouv.fr/) - Monuments historiques français, immeubles protégés, patrimoine architectural.
- [Gallica BnF](https://api.bnf.fr/fr/node/209) - Bibliothèque numérique BnF : livres, manuscrits, presse historique.

## Éducation & recherche

- [Enseignement Sup Recherche](https://data.enseignementsup-recherche.gouv.fr/) - Diplômes, effectifs, insertion, établissements du sup français.
- [ONISEP Open Data](https://opendata.onisep.fr/) - Formations, métiers, établissements scolaires par territoire.
- [HAL Archive Ouverte](https://api.archives-ouvertes.fr/) - Publications scientifiques françaises en libre accès (Archive Ouverte CCSD).

## Contribuer

Contributions bienvenues. Les règles complètes sont dans [contributing.md](contributing.md).
