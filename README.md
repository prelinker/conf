# [PHPTour 2014](http://www.afup.org/pages/phptourlyon2014/) - Lyon - 23/24-06-2014


## [Upgrade PHP 5.3 => 5.6](http://blog.pascal-martin.fr/public/slides-phptour-2014-migration-version-php/) ##

* PHP Code Sniffer + [PHP Compatibility](https://github.com/wimg/PHPCompatibility)

## PostgreSQL ##

* BEGIN; DROP TABLE mytable; ROLLBACK
* INDEX WHERE condition
* types de données spécifiques (tsrange, iprange)

## [Kanban by Meetic](http://fr.slideshare.net/tdiavet/transition-agile-4-real-meetic) ##

## [Take a walk on the ops side](http://fr.slideshare.net/bdu_p/take-a-walk-on-the-ops-side-php-tour-2014) ##

#### Tools
* `cURL -Iv url`
* [Sensu](http://sensuapp.org/)
* [Graphite](http://graphite.wikidot.com/) / [Graphana](http://fpt.akt.tu-berlin.de/graphana/version_2_0/index.html)
* [SysDig](http://www.sysdig.org/)
* [Seyren](https://github.com/scobal/seyren)
* [Riemann](http://riemann.io/)

#### Tests charge
* [Jmeter](http://jmeter.apache.org/)
* [gatling](http://gatling-tool.org/)

#### Stress tests
* [Siege](http://www.joedog.org/siege-home/)
* [Wrk](https://github.com/wg/wrk)

#### Misc
* [Tsung](http://tsung.erlang-projects.org/)
* [Gor](https://github.com/buger/gor)


## [Unicode / UTF-8](https://speakerdeck.com/jrf/everything-you-always-wanted-to-know-about-utf-8-but-never-dared-to-ask-1) ##

* [openl10n.io](http://openl10n.io) ([conf](http://moquet.net/talks/phptour-2014-i18n/))
* symfony l20n
* `<form accept-charset="utf-8">`;
* charset in HTTP headers & html <meta>
* replace gettext by MessageFormatter (gettext is )
* mysqld.ini => default to utf8

## [Tests unitaires](http://fr.slideshare.net/CyrilleGrandval/phptour-lyon-2014-je-veux-mes-80-de-couverture-de-code) ##

* [Roue de Deming](http://fr.wikipedia.org/wiki/Roue_de_Deming)
* [Atoum](https://github.com/atoum/)
* __Un test unitaire doit rester unitaire__ (aucune dépendance)

## [L'asynchrone](https://speakerdeck.com/odolbeau/asynchronous-tasks-in-php) ##

* Ex : Mot de passe oublié
* Publisher > Broker > Worker(s)
* Gérer l'arret des workers (pour la mise à jour, par ex)

## [Gérer sa dette technique](http://jolicode.github.io/phptour-2014--dette-technique--conf/) ##

* Faire de la veille : Source map (css) éviter de complexifier l'archi. encore faut-il le savoir
* Checker les confs sur la ré-écriture de zéro ([François Zaninotto](http://fr.slideshare.net/francoisz/php-100k), Thomas Rabaix)

## [Docker](https://speakerdeck.com/thierrymarianne/developper-et-packager-une-application-symfony2-avec-docker) ##

* win/osx => [boot2docker](http://boot2docker.io/)
* `pip install fig`
* [composer](https://getcomposer.org/) -> [toran](https://toranproxy.com/) (local cache)
* [cadvisor](https://github.com/google/cadvisor) (monitoring)

## Lightning talks ##

* [Les 42 protips du dev' PHP](http://ternel.github.io/42-protips-2014-conf/)
* [logstash](http://logstash.net/)
* [phpstack](http://dunkels.com/adam/phpstack/)
* [etckeeper](https://github.com/joeyh/etckeeper)
* [oh-my-zsh](http://ohmyz.sh/) (note: You should [really consider](http://linhmtran168.github.io/blog/2013/12/15/ditching-oh-my-zsh-for-prezto/) [prezto](https://github.com/loranger/prezto) instead)
* [sl](https://github.com/mtoyoda/sl) / [gti](http://r-wos.org/hacks/gti)
* `alias sf='php app/console'`
* `alias hcomposer='hhvm composer'` (hhvm satis?)
* [jolici](https://github.com/jolicode/JoliCi) (local travis)
* [placephant.com](http://placephant.com/)
* Outillez votre veille
* `remote_connect_back = 1` (xdebug debug)
* [curvytron](http://curvytron.elao.com/)

