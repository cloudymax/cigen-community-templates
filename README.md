# cigen-community-templates

These templates are simply Cloud-Init `user-data` files that have been parametized so they can be regex'd via [envsubst](https://linux.die.net/man/1/envsubst).

> These templates DO NOT currently work for creating Ubquity auto-install files.


## Templates

|Name| Description|
| --- | --- |
|[**ansible-boilerplate**](ansible-boilerplate.yaml)| *A base-system capable of running ansible profiles from the similarly-named [ansible-boilerplate](https://github.com/cloudymax/ansible-boilerplate) repo.*|
|[**game-ci-vdi**](game-ci-vdi.yaml)| *A virtual desktop environment for Unity3d with Editor and Hub.*|
|[**gitlab-runner**](gitlab-runner.yaml)| *Create a self-hosted gitlab runner.*
|[**scrap-metal-auto-install**](scrap-metal-auto-install.yaml)| *Replicates the bare-metal system image for Scrap-Metal as a VM.*|
|[**slim**](slim.yaml)| *Creates a minimal system image with users, ssh-keys and updated package-cache only.*|
|[**debian-gnome**](debian-gnome.yaml)| *Creates a Debian base system with a Gnome desktop.*|
