---
description: >-
  Permet de créer des émotes (ou émojis) personnalisé, en en fusionnant
  plusieurs !
---

# Emote

{% hint style="info" %}
Il y a différentes importances des éléments à mettre dans les commande :

* element -&gt; obligatoire à écrire tel quel
* \[element\] -&gt; obligatoire
* {element} -&gt; facultatif / optionnels
* \(element1\|element2\) -&gt; multiples \(1 à choisir\)
{% endhint %}

## Emote

{% hint style="warning" %}
* `alias : emoji, emotes`
* `permissions nécessaires au bot : send_messages, embed_links, add_reactions`
* `permissions nécessaires à l'utilisateur : aucunes`
{% endhint %}

#### Utilisation :

```text
!emote {emote1} {emote2} {emote3}
```

Le bot vas ensuite envoyer une fusion de ces émojis, a condition qu'il en ai trouvé une dans sa base de donnée ! \(En conséquent, plus il y a d'émoji définis, moins il y aura de résultats !\)

Le bot ajoute 3 réactions, ⬅\|➡\|🎭:

* les flèches servent a voir les résultats suivants ou précédent
* la 3e réaction sert a enlever le pourtour blanc autour de l'émoji, si vous voulez l'ajouter a votre liste d'émojis personnalisé \(pour votre serveur\). Attention, ça ne fonctionne que avec les émojis "normaux".

