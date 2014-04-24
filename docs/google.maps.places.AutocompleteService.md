<h2 id="AutocompleteService">
google.maps.places.AutocompleteService
class
</h2><p>Contains methods related to retrieving Autocomplete predictions.</p><h3>Library</h3><p>places</p><h3>Constructor</h3><table summary="class AutocompleteService - Constructor" width="100%">
<thead>
<tr><th>Constructor</th>
<th>Description</th>
</tr></thead>
<tbody>
<tr>
<td><code>AutocompleteService()</code></td>
<td>Creates a new instance of the <code>AutocompleteService</code>.</td>
</tr>
</tbody>
</table><h3>Methods</h3><table summary="class AutocompleteService - Methods" width="100%">
<thead>
<tr><th>Methods</th>
<th>Return Value</th>
<th>Description</th>
</tr></thead>
<tbody>
<tr>
<td><code>getPlacePredictions(request:<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/google.maps.places.AutocompletionRequest.md"><em>AutocompletionRequest</em></a>, callback:function(Array.&lt;<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/google.maps.places.AutocompletePrediction.md">AutocompletePrediction</a>&gt;, <a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/google.maps.places.PlacesServiceStatus.md">PlacesServiceStatus</a>))</code></td>
<td><code>None</code></td>
<td>Retrieves place autocomplete predictions based on the supplied autocomplete request.</td>
</tr>
<tr>
<td><code>getQueryPredictions(request:<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/google.maps.places.QueryAutocompletionRequest.md"><em>QueryAutocompletionRequest</em></a>, callback:function(Array.&lt;<a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/google.maps.places.QueryAutocompletePrediction.md">QueryAutocompletePrediction</a>&gt;, <a href="https://github.com/amenadiel/google-maps-documentation/blob/master/docs/google.maps.places.PlacesServiceStatus.md">PlacesServiceStatus</a>))</code></td>
<td><code>None</code></td>
<td>Retrieves query autocomplete predictions based on the supplied query autocomplete request.</td>
</tr>
</tbody>
</table>