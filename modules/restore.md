---
description: >-
  Ce module sert a restaurer d'ancien messages (existant encore) grâce à leur
  lien !
---

# Restore

{% hint style="danger" %}
Ce module est désactivé par défaut, pour l'utiliser il faut d'abord utiliser la commande [`!config module restore on`](../commandes/administration/config.md#module)\`\`
{% endhint %}

{% hint style="warning" %}
`bot requiere permissions : send_messages`
{% endhint %}

En envoyant un lien qui renvoie vers un message, le bot va le chercher, récupérer son contenu, et le renvoyer dans la discussion actuelle ! Si il peut gérer les webhooks, il va créer un "faux utilisateur" avec le même nom et image de profile que l'ancien !

#### Exemple :

```text
https://discordapp.com/channels/332209340780118016/435020552021737484/738696213708406854
```

Lorsque que vous aurez envoyer ce message, le bot vas vous renvoyer le message en question !

