<h2 id="DynamicMapsEngineMouseEvent"> DynamicMapsEngineMouseEvent object specification </h2><p>
<code><span itemprop="path">google.maps.visualization</span>.<span itemprop="name">DynamicMapsEngineMouseEvent</span></code>
object specification
</p><p>The properties of a mouse event on a <code>DynamicMapsEngineLayer</code>.</p><h4>Library</h4><p>visualization</p><div class="devsite-table-wrapper"><table class="methods responsive" summary="interface DynamicMapsEngineMouseEvent - Methods">
<thead>
<tr><th colspan="2">Methods</th>
</tr></thead>
<tbody>
<tr>
<td><code><span>getDetails(<wbr>callback:function(<wbr></span><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/MapsEngineMouseEvent.md"><span>MapsEngineMouseEvent</span></a><span>))</span></code></td>
<td><div><strong>Return Value:</strong>&nbsp; <code>None</code></div>
<div class="desc">Takes a callback that will be called with details about the feature that may be used to render an info window.</div></td>
</tr>
</tbody>
</table></div><div class="devsite-table-wrapper"><table class="properties responsive" summary="interface DynamicMapsEngineMouseEvent - Properties">
<thead>
<tr><th colspan="2">Properties</th>
</tr></thead>
<tbody>
<tr>
<td><code><span>featureId</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code>string</code></div>
<div class="desc">The feature ID, guaranteed to be unique within the layer.</div></td>
</tr>
<tr>
<td><code><span>latLng</span></code></td>
<td><div><strong>Type:</strong>&nbsp; <code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/LatLng.md">LatLng</a></code></div>
<div class="desc">The latitude/longitude that was below the cursor when the event occurred.</div></td>
</tr>
</tbody>
</table></div>