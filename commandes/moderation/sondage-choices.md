---
description: Ces commandes servent à créer des sondages interactifs !
---

# Sondage / Choices

{% hint style="info" %}
Il y a différentes importances des éléments à mettre dans les commande :

* element -&gt; obligatoire à écrire tel quel
* \[element\] -&gt; obligatoire
* {element} -&gt; facultatif / optionnels
* \(element1\|element2\) -&gt; multiples \(1 à choisir\)
{% endhint %}

## Sondage

{% hint style="warning" %}
* `alias : strawpoll, survey, poll`
* `permissions necessaires au bot : send_messages, manage_messages, embed_link`
* `permissions necessaires à l'utilisateur : administrator/mod_role`
{% endhint %}

#### Utilisation :

```text
!sondage [sujet]
```

Le bot va ensuite supprimer votre message et mettre en place le message de sondage !

![Le message se met &#xE0; jour en fonction du nombre de vote.](../../.gitbook/assets/image%20%283%29.png)

## Choices

{% hint style="warning" %}
* `alias : aucun`
* `permissions necessaires au bot : send_messages, manage_messages, embed_links`
* `permissions necessaires à l'utilisateur : administrator/mod_role`
{% endhint %}

#### Utilisation :

```text
!choices [sujet]
```

Le bot va ensuite vous demander combien de choix vous voulez, et vous les demander 1 à 1

![Il vous pose la question a cet endroit](../../.gitbook/assets/image%20%287%29.png)

#### Exemple :

![](../../.gitbook/assets/2020-02-28_10-12-29-1-.gif)

