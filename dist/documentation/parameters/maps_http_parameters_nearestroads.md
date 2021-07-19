<!--- This is a generated file, do not edit! -->
<!--- [START maps_http_parameters_nearestroads] -->
<h3 id="required-parameters">Required parameters</h3>

-   <h4 id="points">points</h4>

    The path to be snapped. The path parameter accepts a list of latitude/longitude pairs. Latitude and longitude values should be separated by commas. Coordinates should be separated by the pipe character: "|". For example: `path=60.170880,24.942795|60.170879,24.942796|60.170877,24.942796`.
    Note: The snapping algorithm works best for points that are not too far apart. If you observe odd snapping behavior, try creating paths that have points closer together. To ensure the best snap-to-road quality, you should aim to provide paths on which consecutive pairs of points are within 300m of each other. This will also help in handling any isolated, long jumps between consecutive points caused by GPS signal loss, or noise.

<h3 id="optional-parameters">Optional parameters</h3>


<!--- [END maps_http_parameters_nearestroads] -->