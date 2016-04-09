# Superviser PostgreSQL {data-background="img/back6.jpg"}

---

## A propos de moi

- Damien Clochard ( @daamien )
- COO de Dalibo
- Président de l'association PostgreSQLFr
- Créateur de PG Mag / PostgreSQL Dashboard
- Dalibo Recrute ! ( DBA,  Dev UX/UI, Chef de projet, ... )

---

# Superviser ?

**| sy.per.vi.ze |**

> «
> Se placer au dessus pour voir, remarquer, prendre des mesures
> »

---

# Méthodologie

  * 40 logiciels étudiés
  * 6 critères d'évaluation
  * Pas d'outils propriétaires
  * Pas d'outils dans le "cloud"

---

# Est-ce que tout va bien ? {data-background="img/back1.jpg"}


---

# Zabbix

[http://www.zabbix.com/](http://www.zabbix.com)

---

# {data-background="img/zabbix.gif"  data-state="img-left"}

---

## [pg-monz](http://pg-monz.github.io/)


* Stabilité	3
* Activité	3
* Communauté	4
* Documentation	3
* Fonctionnalités	2
* Simplicité	1


---

# Nagios

[https://www.nagios.org/](https://www.nagios.org/)

---


#  {data-background="img/nagios.png"  data-state="img-left"}


----

## [check_postgres](https://bucardo.org/wiki/Check_postgres)

*  Stabilité         :  4
*  Activité          :  0
*  Communauté        :  4
*  Documentation     :  5
*  Fonctionnalités   :  3
*  Simplicité        :  3

---

## [check_pgactivity](https://github.com/OPMDG/check_pgactivity)

* Stabilité	: 5
* Activité	: 4
* Communauté	: 1
* Documentation	: 5
* Fonctionnalités : 	5
* Simplicité	: 5

---

# OPM

[http://opm.io](http://opm.io)

---

# {data-background="img/opm.gif" data-state="img-left"}

---

## OPM

* Stabilité	 : 4
* Activité	: 3
* Communauté :	2
* Documentation	: 2
* Fonctionnalités	: 3
* Simplicité	:  3


---

## Mais aussi ....

* Shinken
* Icinga
* Naemon
* ...

---

# Que se passe-t'il sur ma base ? {data-background="img/back2.jpg"  data-state="img-left"}

---

## pg_stat_activity

---

# {data-background="img/pg_stat_activity.gif"  data-state="img-left"}


---

# pg_activity

[https://github.com/julmon/pg_activity](https://github.com/julmon/pg_activity)

---

#  {data-background="img/pg_activity.gif" data-state="img-left"}


---

## pg_activity

* Stabilité :	4
* Activité	: 3
* Communauté	: 1
* Documentation	: 4
* Fonctionnalités	: 5
* Simplicité	: 5

---

## Mais Aussi ...

* [pg_top](https://github.com/markwkm/pg_top)
* [pg_view](https://github.com/zalando/pg_view)
* [pgstats](https://github.com/gleu/pgstats)
* [pgCenter](https://github.com/lesovsky/pgcenter)
* [Pome](https://github.com/rach/pome)
* [PostgreSQL Dashboard](https://daamien.github.io/PostgreSQL-Dashboard/)

---

# Que s'est-il passé hier ?  {data-background="img/back3.jpg"}

---

## pg_stat_statements

---

# {data-background="img/pg_stat_statements.gif" data-state="img-left"}


---



# Munin

[http://munin-monitoring.org/]()

---

# {data-background="img/munin.gif"  data-state="img-left"}


----

## pyMunin

* Stabilité :	4
* Activité : 	3
* Communauté :	2
* Documentation	 : 3
* Fonctionnalités	: 4
* Simplicité :	4


---

# pgBadger

[http://dalibo.github.io/pgbadger/](http://dalibo.github.io/pgbadger/)

---

# {data-background="img/pgbadger.gif"  data-state="img-left"}


---

## pgBadger

* Stabilité	: 4
* Activité :	4
* Communauté :	4
* Documentation	: 4
* Fonctionnalités	: 5
* Simplicité : 	5


---

## Mais aussi...

* [ELK]()
* [pg_query_analyser](https://github.com/WoLpH/pg_query_analyser)
* [pgAudit](https://github.com/2ndQuadrant/pgaudit)
* [pgAudit](http://pgaudit.org/)


# Comment Optimiser ? {data-background="img/back4.jpg"  data-state="img-left"}

---

# PoWA

[http://dalibo.github.io/powa/](http://dalibo.github.io/powa/)

---

# {data-background="img/powa.gif"  data-state="img-left"}

---

## PoWA

* Stabilité : 	4
* Activité  :	4
* Communauté  : 	3
* Documentation	: 4
* Fonctionnalités	: 4
* Simplicité	: 3


---

# pgObserver

[http://zalando.github.io/PGObserver/](http://zalando.github.io/PGObserver/)

---

# {data-background="img/pgobserver.png"  data-state="img-left"}

---

## pgObserver

* Stabilité :	3
* Activité :	4
* Communauté	: 2
* Documentation	: 2
* Fonctionnalités	: 3
* Simplicité :	3


---

# pgCluu

[http://pgcluu.darold.net/](http://pgcluu.darold.net/)

---

# {data-background="img/pgcluu.gif"  data-state="img-left"}

---

## pgCluu

* Stabilité	 : 4
* Activité : 	4
* Communauté :	4
* Documentation : 	4
* Fonctionnalités : 	4
* Simplicité	: 5


----

## Mais Aussi...

* [pgHero](https://github.com/ankane/pghero)
* [postgresql-metrics](https://github.com/spotify/postgresql-metrics) par Spotify
* [pgSnap](https://github.com/dalibo/pgsnap)

---

# Que Choisir ? {data-background="img/back5.jpg"}

---

## Définir un socle

* Une vue d'ensemble
* Un "top" en ligne de commande
* Un analyseur de perf
* Une historisation des métriques

---


## Rester à l'écoute

* Evaluer l'impact sur les perfs
* Domaine ultra dynamique
* Les auteurs ont besoin de feedback !
* Attention aux coûts cachés !
* « One tool to rule them all » ?

----

## Plus d'info

* Livre blanc à paraître
* [planet.postgresql.org](http://planet.postgresql.org)
* [https://wiki.postgresql.org/wiki/Monitoring](https://wiki.postgresql.org/wiki/Monitoring)
* [Awesome PostgreSQL](http://www.asad.pw/awesome-postgres/)


---

# Merci ! {data-background="img/back6.jpg"}

* contact: [damien.clochard@dalibo.com]()

* Dalibo recrute un dev UI/UX !
