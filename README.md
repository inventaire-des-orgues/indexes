# Inventaire national des orgues

https://inventaire-des-orgues.fr/

contact@inventaire-des-orgues.fr

Ce dépôt contient le fichier d'index de l'iventaire national des orgues.
Un fichier d'index décrit, pour chaque orgue à tuyau de France accessible au public :

- la localisation de l'instrument
- une description très sommaire de l'instrument

## Structure de l'index

### Enregistrements (lignes)
L'index comprend un enregistrement par orgue. Un orgue correspond à un emplacement géoographique unique. Sont concernés par l'inventaire national :
- tous les orgues du territoire français, métropole et outres-mers;
- d'accès public, c'est-à-dire hébergés dans un lieu privé ou public, mais à l'exclusion des domiciles de particuliers;
- à tuyaux et alimentés mécaniquement en vent, à l'exclusion donc des instruments électroniques ou encore des harmoniums;
- existants à ce jour, à l'exclusion donc des instruments complètement disparus;
- quelque soit leur état ou leur utilisation : en fonctionnement, dégradé, partiel. Notamment, les buffets vides sont concernés;

### Champs (colonnes)
L'index comprend :
1. des champs principaux, décrivant exactement et de façon unique un emplacement géographique. Lorsque l'inventaire sera mis en ligne, ces champs ne seront modifiables que par les administrateurs.
2. des champs secondaires, décrivant les caractéristiques de l'orgue et permettant la correspondance vers d'autres bases de données. Ils seront ouverts à la modification.

- commune_insee : commune de plein droit, selon code national géographique (à l'exclusion donc des communes déléguées et associées)
- edifice : nom usuel de l'édifice
- edifice_standard : nom de l'édifice standardisé (discrimintation entre nom propre et type d'édifice)
- info_edifice : traces de traitement du nom de l'édifice
- codification_edifice : codification de l'édifice
- nomdepartement : nom du département, selon code géographique national
- code_departemnet : code du département, selon code géographique national
- nomregion : nom de la région, selon le code géographique national
- code_insee : code INSEE de la commune, selon le code géographique national
- adresse : complément d'adresse permettant l'identification de l'édifice, généralement la commune associée ou déléguée, ou l'ancien nom de commune, en cas de fusion, parfois le lieu-dit
- denomination : dénomniation de l'orgue, par exemple : "O.C." pour orgue de choeur, "G.O." pour grand-orgue, "Polyphone" pour un polyphone Debierre, ou un numéro d'ordre
- livre : livre d'inventaire dans lequel est répertorié l'orgue
- pages_pdf : pages concernant l'orgue dans le fichier scannés du livre d'inventaire. Les intervalles, inclusifs, de pages sont séparés par des virgules et notés avec un trait d'union, sauf si une page est seule. Exemple : "12, 14-18".
- pages_livre : pages concernant l'orgue telles que définies dans le livre d'inventaire. Ce ne sont pas nécessairemnt les même que celles du fichier de scan (présence de couverture, planches non numérotées dans les livres, etc.)
- pages_livre_complement : autre notation permettant l'identification des pages dans le livre d'inventaire, par exemple dans le cas de classeurs rassemblant des fiches.
- commentaire : champ libre
- log : champ libre utilisé pour des remarques sur des traitements (erreurs, alertes, etc.)
- site_ref : lien Internet du site de référencec dédiée à l'instrument, à savoir le site de l'association oeuvrant pour l'instrument.
- latitude : latitude, en format GPS, de l'emplacement.
- longitude : longitude, en format GPS, de l'emplacement.
- orgbase_manu : lien Internet sur la fiche de l'orgue sur le site Orgbase.nl, renseigné à la main.
- orgbase_commune : commune de l'orgue telle qu'écrite sur le site Orgbase.nl
- orgbase_auto : lien Internet sur la fiche de l'orgue sur le site Orgbase.nl, renseigné automatiquement par les scripts.
- orgbase_desc : description de l'orgue sur le site Orgbase.nl.
- orgbase_edifice : nom de l'édifice hébergeant l'orgue sur le site Orgbase.nl
- orgbase_facteurs : champ décrivant les facteurs étant intervenus sur l'orgue, tels que décrits sur le site Orgbase.nl
- orgbase_minicomposition : composition abrégée de l'orgue sur le site Orgbase.nl
- orgbase_edifice_standard : nom de l'édifice hébergeant l'orgue sur le site Orgbase.nl standardisé (discrimintation entre nom propre et type d'édifice)
- orgbase_edifice_log : traces de traitement du nom d'édifice en provenance de Orgbase.nl.
- orgbase_commune_insee : commune de l'orgue trouvée dans le code géographique national, transcrite depuis le site Orgbase.nl
- reference_palissy : codes Palissy de référence sur l'orgue (champ REF de Palissy). Plusieurs codes pouvant exister pour un même instrument, ils sont séparés de traits-union.
- denomination_palissy : dénomination de l'instrument dans Palissy (champ DENO de Palissy).
- edifice_palissy : nom de l'édifice dans Palissy (champ EDIF de Palissy).
- protection_palissy : protection (inscription ou classement) telle que présente dans Palissy (champ PROT).



https://git.inventaire-des-orgues.fr/Gwilherm/python/src/master/README.md

