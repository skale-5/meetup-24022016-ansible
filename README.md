# Ansible Roles - AWS, Terraform, Ansible Meetup
## Roles

Disclaimer: Les rôles ont été conçus uniquement pour un périmètre d'une démonstration. Ils ne 
sont pas voués à être déployés en production.

Les roles ont été testés sur Ubuntu 14.04 avec Ansible 2.0

- Gogs: service Git en Go
- Drone: service de build (connecté à Gogs via les tasks, c'est à améliorer)
- Lego: Certificats avec Let's Encrypt automatisé (attention aux rates limits)

Le role jdauphant.nginx est à télécharger via ansible-galaxy:

`ansible-galaxy install jdauphant.nginx`

## Slides

Les slides de la présentions se trouvent sur [http://skale-5.github.io/](http://skale-5.github.io/)
