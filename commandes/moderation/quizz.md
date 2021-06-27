---
description: Permet de créer des quizz et de les mettre en place facilement !
---

# Quizz

{% hint style="info" %}
Il y a différentes importances des éléments a mettre dans les commande :

* element -&gt; obligatoire à écrire tel quel
* \[element\] -&gt; obligatoire
* {element} -&gt; facultatif / optionnels
* \(element1\|element2\) -&gt; multiples \(1 à choisir\)
{% endhint %}

## Quizz

{% hint style="warning" %}
* `alias : quiz`
* `permissions nécessaires au bot : send_messages`
* `permissions nécessaires à l'utilisateur : aucunes`
{% endhint %}

### Create

Permet de créer un quizz

{% hint style="danger" %}
Le bot doit pouvoir vous envoyer des messages privés pour cette commande ! Vérifiez que vous n'avez pas bloqué vos messages privés !
{% endhint %}

{% hint style="warning" %}
* `alias : c`
* `permissions nécessaires au bot : aucunes`
* `permissions nécessaires à l'utilisateur : aucunes`
{% endhint %}

#### Utilisation :

```text
!quizz create
```

Le bot va vous envoyer un message en privé, ensuite, vous devrez suivre les étapes qu'il vous demande.

![Ici, vous devrez donc envoyer d&apos;abord le titre de votre quizz !](../../.gitbook/assets/image%20%288%29.png)

#### Exemple :

![Petite vid&#xE9;o de cr&#xE9;ation d&apos;un quizz](../../.gitbook/assets/2020-02-27_16-51-58-1-.gif)

### Start

Permet de démarrer un quizz qui a été créer au préalable !

{% hint style="warning" %}
* `alias : s`
* `permissions nécessaires au bot : manage_messages,manage_channels,embed_links`
* `permissions nécessaires à l'utilisateur : administrator/mod_role`
{% endhint %}

#### Utilisation :

```text
!quizz start [quizzID]
```

Le bot vous demande d'abord de confirmer si vous voulez démarrer le quizz, cliquez sur✅ :

![](../../.gitbook/assets/image%20%286%29.png)

Une fois fait, le bot démarrer le quizz en question, cela engendre quelques modification du salon :

* les membres \(everyone\) ne pourront parler seulement lorsqu'une question est posée
* le channel a un slowmode de 5 secondes qui est ajouté

Lorsque que quelqu'un trouve une réponse, l'autre question arrivera 5 secondes après. Un rappel des scores sera fait entre chaque questions.

