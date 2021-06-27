---
description: Attribue des roles à des emojis !
---

# Role\_emote

{% hint style="info" %}
Il y a différentes importances des éléments à mettre dans les commande :

* element -&gt; obligatoire à écrire tel quel
* \[element\] -&gt; obligatoire
* {element} -&gt; facultatif / optionnels
* \(element1\|element2\) -&gt; multiples \(1 à choisir\)
{% endhint %}

## Role\_emote

{% hint style="warning" %}
* `alias : emote_role, emoterole, role_emoji, emoji_role, emojirole`
* `permissions nécessaires au bot : send_messages, manage_emojis`
* `permissions nécessaires à l'utilisateur : administrator`
{% endhint %}

`Role_emote` est une commande qui permet d'assigner des rôles a des emoji custom sur le serveur ! Vous pouvez donc ajouter un emoji, et définir que seul tels ou tels rôles peuvent l'utiliser !

#### Utilisation :

```text
!role_emote [custom_emote] {role}
```

Si vous ne mettez pas l'argument "role", le bot va simplement vous renvoyer les roles qui peuvent actuellement utiliser cet emote. Si vous le mettez, il va avoir effet de "toggle", c'est a dire : si le role peut déjà l'utiliser, il va le retirer, sinon, il va l'ajouter.

#### Exemple :

![Parfois, il faudra actualiser Discord pour voir les changements \(crtl+R\)](../../.gitbook/assets/ezgif.com-video-to-gif-1-.gif)

