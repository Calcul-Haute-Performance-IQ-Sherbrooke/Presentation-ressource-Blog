.. description

Presentation de la plaforme de Calcul Haute Performance
-------------------------------------------------------

Qu'est ce que le Calcul Haute Performance (CHP) ?
=================================================

Le Calcul Haute Performance est défini comme tout calcul qui fait une utilisation intensive des ressources sur un ordinateur.
Le CHP inclue donc toutes les tâches faisant une utilisation intensive du CPU, de la mémoire vive, d'espace de stockage, d'accélérateur ou qui nécessitent un long temps de traitement.

Cette définition est volontairement peu restrictive, ce qui implique que n'importe qui pourrait avoir besoin de ressources en ce sens.
Beaucoup pensent que leur ordinateur personnel est suffisant pour leurs besoins, car certaines tâches récurrentes ne prennent que deux minutes, peuvent tourner pendant la nuit, ou encore qu'un large jeu de données peut être traité en plusieurs étapes.
Cependant, les objectifs de recherche seraient-ils les mêmes si la tâche de deux minutes ne prendrait que 10 secondes ? 
La nuit traitant 100 tâches à la place d'une seule ?
Le large jeu de données traité en une fois, sans tâches répétitives et sans actions d'un humain ?
Sous cette perspective, les usagers intéressés sont invités reconsidérer leurs objectifs si ces derniers ont inconsciemment été limités par les capacités de calcul disponibles avant la lecture de ce paragraphe.


Les ressources disponibles à l'IQ
=================================

Pour répondre aux besoins de CHP de ses membres, l'IQ s'est doté de différentes ressources de calcul:

* Trois serveurs de type "CPU" équipés de deux processeurs AMD EPYC 7643 (48 coeurs à 2.3 GHz chacun), 512 GB de mémoire vive, un SSD local de 1 TB et configurés avec la pile logicielle de Calcul Canada.
* Un serveurs de type "GPU" équipé de deux accélérateurs NVidia A40 avec 48 GB de mémoire vive dédiée, deux processeurs Intel Xeon Gold 6342 (24 coeurs à 2.8 GHz chacun), 512 GB de mémoire vive principal, un SSD local de 1TB, aussi configuré avec la pile logicielle de Calcul Canada.
* Un serveur de données équipé de 24 disques SAS de 16 TB chacun, de deux processeurs Intel Xeon Gold 6226R (16 coeurs à 2.9 GHz chacun) et de 256 GB de RAM. Les données sont dupliquées sur les disques pour un stockage disponible d'environ 190 TB.

Ces ressources, de taille intermédiaire entre un ordinateur personnel et une grappe de calcul, peuvent être utilisées sans limite et sans coût d'utilisation associé.
Les coûts sont assumés à la fois par l'IQ et à travers une subvention de la Fondation Canadienne pour l'Innovation (FCI).
Un estimé des coûts d'utilisations des ressources peut être trouvé sur le site de l'Alliance (`Valeur monétaire des allocations 2022 <https://alliancecan.ca/en/services/advanced-research-computing/accessing-resources/resource-allocation-competitions/2022-resource-allocations-competition-results#heading-monetary-value-of-the-2022-allocations>`_).


Les autres ressources disponibles
=================================

Ressources des professeurs de l'IQ
##################################

Certains professeurs de l'IQ mettent en accès restreint ou libre leurs ressources de calcul.
Le tableau suivant présente ces ressources:

.. list-table::
   :header-rows: 1

   * - Nombre
     - Type
     - CPU
     - Coeurs
     - Mémoire
     - Disque dur
     - GPU
     - Propriétaire
     - Accès libre
     - Partition
   * - 3
     - CPU
     - AMD EPYC 7643 @ 2.3 GHz (x2)
     - 96
     - 512 GB (DDR4)
     - 1 TB (NVMe)
     -  
     - IQ
     - Oui
     - c-iq
   * - 1
     - GPU
     - Xeon Gold 6342 @ 2.8 GHz (x2)
     - 48
     - 512 (DDR4)
     - 1 TB (NVMe)
     - NVidia A40 48GB HBM2 (x2)
     - IQ
     - Oui
     - c-iq (noeud cp3705)
   * - 1
     - CPU
     - AMD EPYC 7742 @ 2.3 Ghz (x2)
     - 128
     - 2 TB (DDR4)
     - 6 TB (NVMe)
     - 
     - Batiste Royer
     - Non
     - c-royer
   * - 1
     - CPU
     - ?
     - 48
     - 1 TB (?)
     - ?
     - 
     - Stefanos Kourtis
     - Non
     - c-aphex
   * - 1
     - CPU
     - Xeon E7-8870 v3 @ 2.5 GHz (x4)
     - 72
     - 3 TB (?)
     - 2 TB (?)
     - 
     - David Sénéchal
     - Non
     - c-fat3072
   * - 4
     - CPU
     - AMD EPYC 7301 @ 2.2 GHz (x2)
     - 32
     - 256 GB (DDR4)
     - 400 GB (?)
     - 
     - David Sénéchal
     - Oui
     - c-apc
   


Ressources de l'Alliance
########################

L'Alliance pour la Recherche (anciennement Calcul Canada) met à disposition des professeurs rattachés à un université canadienne et leurs étudiants et personels de recherche l'accès à des grappes de serveurs (supercalculateurs) sans coût d'utilisation. Les personnes intéressées sont référer au site de l'Alliance qui décrit ces ressources (`National Host Sites <https://alliancecan.ca/en/services/advanced-research-computing/federation/national-host-sites>`_).


.. _demande_d_acces:

Demande d'accès aux ressources
==============================

L'accès aux ressources de calcul de l'IQ se fait en deux étapes:

#. Création d'un `compte Calcul Canada (CCDB) <https://alliancecan.ca/en/services/advanced-research-computing/account-management/apply-account>`_. À noter que la création d'un compte Calcul Canada doit se faire via un parrain (par exemple un professeur) pour les membres ayant le statut étudiants, stagiaires, stagiaires post-doctorals et personnels de recherche.

#. Après avoir obtenu leur compte CCDB, les membres doivent remplir `l'annexe C de la politique d'accès au calculateurs <https://forms.office.com/r/UKb6yPneD1>`_.

L'accès aux ressources est régi par la `politique d'accès aux calculateurs <https://www.usherbrooke.ca/iq/wp-content/uploads/2022/06/Politiques-Calculateurs-haute-performance-HPC-2022-06-02.pdf>`_.
