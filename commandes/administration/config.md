---
description: >-
  Avec cette commande vous pourrez changer le prefix, activer/désactiver des
  commandes, définir le rôle modérateur...
---

# Config

{% hint style="info" %}
Il y a différentes importances des éléments à mettre dans les commande :

* element -&gt; obligatoire à écrire tel quel
* \[element\] -&gt; obligatoire
* {element} -&gt; facultatif / optionnels
* \(element1\|element2\) -&gt; multiples \(1 à choisir\)
{% endhint %}

## Config

{% hint style="warning" %}
`alias : pas d'alias  
bot requiere permissions : send_message, read_message  
user requiere permissions : administrator`
{% endhint %}

### Prefix

Permet de changer le préfix du bot

#### Utilisation :

```text
!config prefix [nouveau prefix]
```

### Role

Permet de définir un rôle comme modérateur \(que modérateur, et que un seul rôle pour le moment\)

#### Utilisation :

```text
!config role mod (@role|role id|role name)
```

### Command

Permet d’activer ou de désactiver des commandes

#### Utilisation :

```text
!config commande [nom de la commande] {(on|off)}
```

### Module

Permet d'activer ou de désactiver des modules

#### Utilisation :

```text
!config module [nom du module] {(on|off)}
```

