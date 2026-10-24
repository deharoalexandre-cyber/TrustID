# TrustID

**Français · [English](README.en.md)**

TrustID est la famille de sécurité locale des identités et des postes d'Elyne Corp. Elle associe des signaux comportementaux, des contrôles du système, un score de confiance et des réponses prévues par la politique de l'exploitant.

| Édition | Présentation | État affiché sur le site |
| --- | --- | --- |
| **v1.5 Windows** | Protection multicouche et score de confiance pondéré, sans moteur CCD de v3. | Production |
| **v3 Windows** | Onze couches de détection et moteur CCD à huit agents spécialisés, avec mémoire de cas et gouvernance. | Production |
| **v3 Linux** | Port des mécanismes vers les primitives Linux et le service systemd. | Documentation et paquet local disponibles ; qualification de déploiement à préciser |

TrustID fonctionne sur le poste protégé. Les signaux et décisions ne supposent pas l'envoi des données à un cloud. Les capacités effectives et les dépendances varient selon l'édition et l'environnement.

## Architecture et validation

- [Architecture simplifiée](docs/architecture.md)
- [Essais identifiés, résultats et limites](docs/evidence.md)
- [Notice de propriété](NOTICE.md)

Le libellé commercial « Production » est celui du [catalogue Elyne Corp](https://elynecorp.fr/). Il ne remplace pas une recette sur la configuration du client. Les nombres de techniques MITRE, les temps de réaction et les garanties cryptographiques doivent être rattachés à une édition et à un rapport de qualification avant d'être invoqués contractuellement.

## Évaluation

Les sources, configurations, journaux et rapports d'audit non expurgés ne figurent pas dans ce dépôt documentaire. Pour discuter d'une édition et de son périmètre : [admin@elynecorp.fr](mailto:admin@elynecorp.fr) · [elynecorp.fr](https://elynecorp.fr/).
