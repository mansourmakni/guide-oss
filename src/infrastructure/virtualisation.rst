Virtualisation
==============

La virtualisation de serveurs est un ensemble de techniques et d’outils permettant de faire tourner plusieurs systèmes d’exploitation sur un même serveur physique.

Le principe de la virtualisation est donc un principe de partage : les différents systèmes d’exploitation se partagent les ressources du serveur.

Pour être utile de manière opérationnelle, la virtualisation doit respecter deux principes fondamentaux : le cloisonnement (chaque système d’exploitation a un fonctionnement indépendant, et ne peut interférer avec les autres en aucune manière) et la transparence (le fait de fonctionner en mode virtualisé ne change rien au fonctionnement du système d’exploitation et a fortiori des applications).

Dans cette catégorie, 4 outils open ont été sélectionnés dont les plus connus dans l’univers professionnel, Xen et KVM.




Xen
---

:Version: 4.1.1
:Site: http://xen.org
:Porteur: un éditeur (Citrix)
:Licence: GPL

Xen est un hyperviseur gérant la paravirtualisation. Le projet est né en 2003 sous la forme d'un projet de recherche de l'université de Cambridge au Royaume-Uni.

La paravirtualisation désigne la capacité pour un système de virtualisation à interagir avec les systèmes virtualisés. Les machines virtuelles sont ainsi plus performantes, et mieux administrables. Xen est issu d'un projet de recherche universitaire, et fait désormais partie du noyau Linux. Une version entreprise et le support associé est proposée par Citrix.


OpenVZ
------

:Version: 3.0.25
:Site: www.openvz.org
:Porteur: une communauté
:Licence: GPL v2

OpenVZ est une solution de virtualisation légère pour Linux créée en 2005.

Comme toute solution de virtualisation légère, il n'est possible d'exécuter que des systèmes Linux au sein d'OpenVZ. Cependant cet handicap est compensé par des performances bien plus proches des performances natives que tout autre type de virtualisation, en particulier pour les entrées-sorties, ainsi qu'une consommation de mémoire réduite. OpenVZ est principalement utilisé dans les environnements de développement et de tests, où il n'est pas rare d'avoir plusieurs dizaines de systèmes sur un même hôte.


KVM
---

:Version: 2.6.20
:Site: www.linux-kvm.org
:Porteur: une communauté
:Licence: GPL

KVM est une solution de virtualisation complète basée sur Linux datant de 2005. KVM est un fork de QEMU. Parfois, le code source des deux produits est resynchronisé.

Intégré au noyau Linux (depuis la version 2.6.2), KVM est capable d'exécuter des systèmes virtuels sous tous les OS courants en simulant un matériel standardisé, et supporte des fonctions avancées telles que la migration et l'inspection en profondeur de l'état de la VM.


Oracle VirtualBox
-----------------

:Version: 4.1.2
:Site: www.virtualbox.org
:Porteur: un éditeur (Oracle)
:Licence: GPL v2

VirtualBox est une solution de virtualisation, créée en 2007 et destinée aux postes de travail,.

VirtualBox supporte un grand nombre de systèmes d'exploitation invités, et dispose de fonctionnalités d'interaction avec ces systèmes : partage de fichiers, intégration du pointeur de souris, fusion du bureau avec le bureau hôte. Certaines options, telles le partage des périphériques USB, peuvent être ajoutées sous forme de plugins propriétaires.


Autres
------

Parmi les produits de l’univers Virtualisation, on peut compléter la liste avec les outils ci-dessous :



Nom	URL / Site web

Qemu	http://wiki.qemu.org

