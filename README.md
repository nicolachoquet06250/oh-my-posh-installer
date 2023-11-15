# oh-my-posh-installer
Création d'un alias d'installation symplifier pour oh-my-posh

![Image Oh My Posh](https://ohmyposh.dev/img/hero.png)

## Installation
```shell
git clone https://github.com/nicolachoquet06250/oh-my-posh-installer.git
```
ou
```shell
git clone git@github.com:nicolachoquet06250/oh-my-posh-installer.git
```
ou installer le cli github : https://github.com/cli/cli/blob/trunk/docs/install_linux.md

puis
```shell
gh repo clone nicolachoquet06250/oh-my-posh-installer
```

Un lien symbolique du répertoire va se créer dans votre répertoire personnel 
puis le fichier `.bash_aliases_oh-my-posh` de ce répertoire sera sourcé 
dans `.bash_aliases`

# Utilisation

## Aide

```shell
oh-my-posh-installer
```
ou
```shell
oh-my-posh-installer help
```
ou
```shell
oh-my-posh-installer --help
```
ou
```shell
oh-my-posh-installer -h
```

## Installation de Oh My Posh
```shell
oh-my-posh-installer install
```
ou
```shell
oh-my-posh-installer i
```

### Installer sans les thèmes
```shell
oh-my-posh-installer install --no-themes|-nt
```
ou
```shell
oh-my-posh-installer i --no-themes|-nt
```

## Mise à jour de Oh My Posh
```shell
oh-my-posh-installer update
```
ou
```shell
oh-my-posh-installer u
```

### Mise à jour avec les thèmes
```shell
oh-my-posh-installer update --with-themes|-wt
```
ou
```shell
oh-my-posh-installer u --with-themes|-wt
```

## Cloner un fichier de configuration
```shell
oh-my-posh-installer clone-conf --conf|-c --output|-o
```
ou
```shell
oh-my-posh-installer cc --conf|-c --output|-o
```

## Afficher le lien vers le site officiel
```shell
oh-my-posh-installer official-site
```
ou
```shell
oh-my-posh-installer os
```

## Afficher le lien des différentes parties de la documentation
```shell
oh-my-posh-installer docs
```
ou
```shell
oh-my-posh-installer d
```