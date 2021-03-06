<h2 id="LatLng"> LatLng class </h2><p>
<code><span itemprop="path">google.maps</span>.<span itemprop="name">LatLng</span></code>
class
</p><p>A <code>LatLng</code> is a point in geographical coordinates: latitude and longitude.<br> </p><ul> <li>Latitude ranges between -90 and 90 degrees, inclusive. Values above or below this range will be clamped to the range [-90, 90]. This means that if the value specified is less than -90, it will be set to -90. And if the value is greater than 90, it will be set to 90.</li> <li>Longitude ranges between -180 and 180 degrees, inclusive. Values above or below this range will be wrapped so that they fall within the range. For example, a value of -190 will be converted to 170. A value of 190 will be converted to -170. This reflects the fact that longitudes wrap around the globe.</li> </ul><em>first</em><br><code>LatLng</code><br><p> Most methods that accept <code>LatLng</code> objects also accept a <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLngLiteral.md">LatLngLiteral</a></code> object, so that the following are equivalent: </p><pre><div class="devsite-code-button-wrapper"><div class="devsite-code-button gc-analytics-event material-icons devsite-dark-code-button" data-category="Site-Wide Custom Events" data-label="Dark Code Toggle" track-type="exampleCode" track-name="darkCodeToggle" data-tooltip-align="b,c" data-tooltip="Dark code theme" aria-label="Dark code theme" data-title="Dark code theme"></div></div> map.setCenter(new google.maps.LatLng(-34, 151));<br> map.setCenter({lat: -34, lng: 151}); </pre><p> The constructor also accepts literal objects, and converts them to instances of <code>LatLng</code>: </p><pre><div class="devsite-code-button-wrapper"><div class="devsite-code-button gc-analytics-event material-icons devsite-dark-code-button" data-category="Site-Wide Custom Events" data-label="Dark Code Toggle" track-type="exampleCode" track-name="darkCodeToggle" data-tooltip-align="b,c" data-tooltip="Dark code theme" aria-label="Dark code theme" data-title="Dark code theme"></div></div> myLatLng = new google.maps.LatLng({lat: -34, lng: 151}); </pre><p></p><div class="devsite-table-wrapper"><table class="constructors responsive" summary="class LatLng - Constructor">
<thead>
<tr><th colspan="2">Constructor</th>
</tr></thead>
<tbody>
<tr>
<td><code><span>LatLng(<wbr>lat:number,<wbr> lng:number,<wbr> noWrap?:boolean)</span></code></td>
<td>Creates a <code><span>LatLng</span></code> object representing a geographic point. Latitude is specified in degrees within the range [-90, 90]. Longitude is specified in degrees within the range [-180, 180]. Set <code><span>noWrap</span></code> to <code><span>true</span></code> to enable values outside of this range. Note the ordering of latitude and longitude.</td>
</tr>
</tbody>
</table></div><div class="devsite-table-wrapper"><table class="methods responsive" summary="class LatLng - Methods">
<thead>
<tr><th colspan="2">Methods</th>
</tr></thead>
<tbody>
<tr>
<td><code><span>equals(<wbr>other:</span><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md"><span>LatLng</span></a><span>)</span></code></td>
<td><div><strong>Return Value:</strong>&nbsp; <code>boolean</code></div>
<div class="desc">Comparison function.</div></td>
</tr>
<tr>
<td><code><span>lat()</span></code></td>
<td><div><strong>Return Value:</strong>&nbsp; <code>number</code></div>
<div class="desc">Returns the latitude in degrees.</div></td>
</tr>
<tr>
<td><code><span>lng()</span></code></td>
<td><div><strong>Return Value:</strong>&nbsp; <code>number</code></div>
<div class="desc">Returns the longitude in degrees.</div></td>
</tr>
<tr>
<td><code><span>toJSON()</span></code></td>
<td><div><strong>Return Value:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLngLiteral.md">LatLngLiteral</a></code></div>
<div class="desc">Converts to JSON representation. This function is intended to be used via <code>JSON.stringify</code>.</div></td>
</tr>
<tr>
<td><code><span>toString()</span></code></td>
<td><div><strong>Return Value:</strong>&nbsp; <code>string</code></div>
<div class="desc">Converts to string representation.</div></td>
</tr>
<tr>
<td><code><span>toUrlValue(<wbr>precision?:number)</span></code></td>
<td><div><strong>Return Value:</strong>&nbsp; <code>string</code></div>
<div class="desc">Returns a string of the form "lat,lng" for this LatLng. We round the lat/lng values to 6 decimal places by default.</div></td>
</tr>
</tbody>
</table></div>