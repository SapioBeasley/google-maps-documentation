<h2 id="MapsEngineLayerOptions">
google.maps.visualization.MapsEngineLayerOptions
object specification
</h2><p>This object defines the properties that can be set on a <code>MapsEngineLayer</code> object. <code>layerId</code>, or both <code>mapId</code> and <code>layerKey</code>, must be set.</p><h3>Library</h3><p>visualization</p><h3>Properties</h3><table summary="interface MapsEngineLayerOptions - Properties" width="100%">
<thead>
<tr><th>Properties</th>
<th>Type</th>
<th>Description</th>
</tr></thead>
<tbody>
<tr>
<td><code>accessToken</code></td>
<td><code>string</code></td>
<td>The authentication token returned by an OAuth 2.0 authentication request.</td>
</tr>
<tr>
<td><code>clickable</code></td>
<td><code>boolean</code></td>
<td>If true, the layer receives mouse events. Default value is true.</td>
</tr>
<tr>
<td><code>fitBounds</code></td>
<td><code>boolean</code></td>
<td>If this option is set to true, the map viewport is centered and zoomed to the bounding box of the contents of the layer. Default value is false. Applies only to KML layers. Note: Be careful when setting this option for other layer types, as it may become effective in the future.</td>
</tr>
<tr>
<td><code>layerId</code></td>
<td><code>string</code></td>
<td>The ID of a single Maps Engine layer to display.</td>
</tr>
<tr>
<td><code>layerKey</code></td>
<td><code>string</code></td>
<td>The key of the layer to display. Maps Engine layer keys are only unique within a single map, and can be changed by map owners.</td>
</tr>
<tr>
<td><code>map</code></td>
<td><code><a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/google.maps.Map.md">Map</a></code></td>
<td>The map on which to display the layer.</td>
</tr>
<tr>
<td><code>mapId</code></td>
<td><code>string</code></td>
<td>The ID of the Maps Engine map that contains the layer with the given <code>layerKey</code>.</td>
</tr>
<tr>
<td><code>opacity</code></td>
<td><code>number</code></td>
<td>The opacity of the layer, expressed as a number between 0 and 1. Defaults to 1. Applies only to imagery layers. Note: Be careful of setting this option for other layer types, as it may become effective in the future.</td>
</tr>
<tr>
<td><code>suppressInfoWindows</code></td>
<td><code>boolean</code></td>
<td>Suppress the rendering of info windows when layer features are clicked.</td>
</tr>
<tr>
<td><code>zIndex</code></td>
<td><code>number</code></td>
<td>The z-index of the layer. Only applies to Vector and KML layers.</td>
</tr>
</tbody>
</table>