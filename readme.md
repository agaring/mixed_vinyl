# SymfonyCast - Symfony 6 Tutorial Series - Episode 1

Bonjour, je m'apelle Arnaud Garing.

Pour me rafraichir la mémoire sur Symfony, je suis en train de suivre la série de tutoriel sur Symfony 6
par [SymfonyCasts](https://symfonycasts.com/tracks/symfony).

Ce dépot correspond à l'episode
3 ([Doctrine, Symfony 6 & the Database](https://symfonycasts.com/screencast/symfony-doctrine)) de la série.

J'ai peu apprendre :

* Comment créer une application Symfony
* Créer et configurer des Routes, ajouter des validations
* Comment installer des packages via composer et en particulier les recettes présent dans
  le [Dépot des Recettes Symfony](https://github.com/symfony/recipes)( Symfony Recipes Repository)
* Comment installer et utliser Twig, l'héritage
* Comment utiliser et profiter du Profiler Symfony
* Comment partager des images, des scripts et du CSS via WebPack Encore : un outil permettant de facilement les grouper
* Comment des interface de programmation (API) Json via symfony
* Comment trouver et implémenter les Services dans un projet symfony
* Comment créer des élements interactif avec [Stimulus](https://stimulus.hotwired.dev/)
* Comment accélerer un site via [Turbo](https://turbo.hotwired.dev/)

## Installation

**Composer**

Assurez-vous que vous avez [Composer installé](https://getcomposer.org/download/) puis exécutez :

```shell
composer install
```

Vous pouvez également lancer `php composer.phar install`, en fonction de la façon dont vous avez installé Composer.

**Webpack Encore**

Cette application utilise Webpack Encore pour les fichiers CSS, JS et images.

Assurez-vous d'avoir installé [yarn](https://yarnpkg.com/lang/en/) ou `npm` installé (`npm` est livré avec Node) et
ensuite lancez :

```shell
yarn install
yarn encore dev --watch

# ou
npm install
npm run watch
```

**Symfony**

Vous pouvez utiliser Nginx ou Apache, mais le serveur web local de Symfony est plus pratique pour le développement local.

Pour installer le serveur web local Symfony, suivez les instructions de "Downloading the Symfony client" trouvées
ici : https://symfony.com/download - vous n'avez besoin de faire cela qu'une seule fois sur votre système.

Ensuite, pour démarrer le serveur web, ouvrez un terminal, placez-vous dans le projet et exécutez :

```shell
symfony serve
```

(Si c'est la première fois que vous utilisez cette commande, il se peut que vous voyiez une erreur indiquant que vous
devez d'abord lancer `symfony server:ca:install`).

Maintenant, regardez le site à `https://localhost:8000`