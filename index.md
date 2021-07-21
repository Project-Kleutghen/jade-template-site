---
layout: archive
permalink: /
title: "The Chinese Emperor's 'Hindustan' Jades"
---
<p>
“The Chinese Emperor’s Hindustan Jades” integrates text analysis, mapping, and interactive
 image viewers to visualize eighteenth-century China’s engagement with the Islamic world. 
 The textual dataset is a group of approximately one hundred poems that the Qianlong emperor
 (r. 1736-1795) wrote about and ordered incised into the Islamic jades in his collection. The
 image/object dataset is the group of extant inscribed jades. Comparing the published printed 
 text and the inscribed text reveals that they are not identical, and the same text could be 
 inscribed onto multiple objects from different places around the Islamic world. The bilingual 
 textual analysis and object-centered stylistic comparisons will be presented in a map and 
 embedded image viewer that combines methodology from historical GIS and digital art history, 
 with an emphasis on open-source tools and open access scholarship. At this stage of the project, 
 both Sarah and Gloria are learning Python: Sarah will use it for Chinese textual analysis and 
 comparison, while Gloria will use it together with the Folium library to create maps in Leaflet. 
 Professor Kleutghen is focusing on image presentation with IIIF, which integrates with Leaflet 
 and allows image annotations that will be drawn from the text analysis.
</p>

<div class="tiles">
{% for post in site.posts %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->