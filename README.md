# Solution de transfert de fichiers sécurisée vers Amazon S3 via SFTP

## Description:
Ce projet présente une architecture simple et efficace pour transférer des fichiers en toute sécurité depuis un client local vers un bucket Amazon S3 en utilisant le protocole SFTP.

## Diagramme d'architecture:
[Insérez ici votre diagramme]

## Fonctionnalités clés:
- Transfert SFTP sécurisé: Utilisation du protocole SFTP pour garantir la confidentialité et l'intégrité des données lors du transfert.
- Intégration avec Amazon S3: Stockage des fichiers transférés dans un bucket S3 pour une sauvegarde à long terme et une accessibilité facile.
- Authentification IAM: Utilisation d'identités IAM pour contrôler l'accès aux ressources AWS et sécuriser les transferts.
- Flexibilité: Configuration personnalisable pour répondre à différents besoins (bucket S3, permissions IAM, etc.).

## Cas d'utilisation:
- Sauvegardes régulières: Sauvegarde automatique de fichiers importants sur un stockage cloud sécurisé.
- Partage de fichiers: Partage de fichiers avec des collaborateurs en leur fournissant un accès SFTP.
- Migration de données: Migration de données en masse vers le cloud.

## Technologies utilisées:
- Amazon S3: Service de stockage objet hautement disponible et durable.
- AWS Transfer Family: Service managé pour créer des serveurs SFTP sécurisés.
- IAM: Service de gestion des identités et des accès AWS.

## Installation et configuration:
Prérequis:
- Un compte AWS
- Un client SFTP (FileZilla, WinSCP, etc.)

## Contributeurs:
Nelly G.
