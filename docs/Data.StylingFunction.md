<h2 id="Data.StylingFunction"> Data.StylingFunction typedef </h2><p>
<code><span itemprop="path">google.maps</span>.<span itemprop="name">Data.StylingFunction</span></code>
typedef
</p><p>A function that computes the appearance of a feature.
</p><p>
The <code>Data.setStyle()</code> method can accept a styling function. Use
this when features should appear differently depending on their properties.
You can find more information about styling features in the <a href="https://developers.google.com/maps/documentation/javascript/datalayer#style_geojson_data">developer's
guide</a>.</p><p><code>function(Data.Feature):Data.StyleOptions</code></p>