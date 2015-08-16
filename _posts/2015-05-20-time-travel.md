---
layout: post
category : dataviz
title : Le voyage dans le temps au Cinéma
tagline: Sujet au mal de tête ? Regardez Primer !
tags : [dataviz, science-fiction, cinema, movies,time-travel]
comments : true
identifier : 42
---
{% include JB/setup %}

Lors d'un cours thématique en anglais à <a href="//telecom-paristech.fr">Télécom ParisTech</a> concernant les œuvres de science-fiction, je me suis
penché sur la représentation du voyage dans le temps au cinéma.

C'était l'occasion d'extraire un peu d'informations de la formidable base qu'est <a href="//imdb.com">IMDb</a>. Le site associe à chaque film une liste
de <em>keywords</em> ; ce qui permet par exemple de lister de manière relativement fiable l'ensemble des 
<a href="//www.imdb.com/search/keyword?keywords=time-travel&mode=detail&page=1&title_type=movie"> films dont le scenario fait intervenir le voyage dans le temps</a>.
Par contre, IMDb ne propose pas d'API publique pour recueillir directement les données relatives aux films. Il faut donc parser la liste, puis l'enrichir avec
des outils tels que ceux proposés par <a href="http://www.myapifilms.com/">myapifilms.com</a>.

Voici donc un aperçu de l'ensemble des films dont le scénario fait appel à un certain type de voyage dans le temps, et qui ont reçu plus de 12000 notes sur IMDb.

## Visualisation

<iframe src="/assets/viz/timetravel" width="100%" height="600px" scrolling="no">
</iframe>
