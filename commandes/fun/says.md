---
description: >-
  Ces commande servent à faire parler le bot, ou a vous faire parler comme un
  bot.
---

# Says

{% hint style="info" %}
Il y a différentes importances des éléments à mettre dans les commande :

* element -&gt; obligatoire à écrire tel quel
* \[element\] -&gt; obligatoire
* {element} -&gt; facultatif / optionnels
* \(element1\|element2\) -&gt; multiples \(1 à choisir\)
{% endhint %}

## Say

{% hint style="warning" %}
* `alias : dire, repeat`
* `permissions nécessaires au bot : send_messages`
* `permissions nécessaires à l'utilisateur : aucunes`
{% endhint %}

#### Utilisation :

```text
!say [phrase]
```

Le bot va ensuite dire exactement le même message que `[phrase]` et supprimer le message d'évocation si il a la permission `manage_messages`.

## Websay

{% hint style="warning" %}
* `alias : bot_speak`
* `permissions nécessaires au bot : send_messages, manage_webhooks`
* `permissions nécessaires à l'utilisateur : aucunes`
{% endhint %}

#### Utilisation :

```text
!websay [phrase]
```

Le bot va ensuite créer un `webhook` \(une sorte de bot\) qui aura votre nom, votre avatar, mais avec l'étiquette " BOT " derrière le nom. Le bot supprime le message d'évocation si il a la permission `manage_messages`.

![Un exemple de webhook](../../.gitbook/assets/image%20%284%29.png)

## Vocsay

{% hint style="warning" %}
* `alias : voice_speak, vocalsay`
* `permissions nécessaires au bot : connect, speak`
* `permissions nécessaires à l'utilisateur : aucunes`
* `commande premium : partiellement`
{% endhint %}

#### Utilisation :

```text
!vocsay [phrase]
```

Le bot va ensuite se connecter au salon, lire votre phrase, et se déconnecter.

{% hint style="info" %}
Le bot peut parler avec une voix dite "neuronale", c'est a dire qui est basée sur de l'intelligence artificielle, qui parait donc naturelle ! Mais cette voix est limitée a 2 000 caractères par mois et par serveur si il n'est pas premium, et 20 000 caractères par mois et par serveur si il est premium.

Au delà de ce nombre de caractères, ce sera une voix un peu plus robotique qui sera utilisée, limitée a 10x plus de caractères.
{% endhint %}

