---
layout: page
title: Vierailijoille
permalink: /vierailijoille/
---

Lorem Ipsum dolor sit amet


<!-- .text-center breaks Mapbox GL js -->
<div id='map' style='width: 400px; height: 300px; text-align: left;'></div>
<script>
    mapboxgl.accessToken = 'pk.eyJ1IjoiZXNtYWxhIiwiYSI6ImNqZXZ5N2hqZzBpbWEyd3BjZm5wMHkzN2cifQ.2Vj6-u9JdYdsb92maw3jyQ';
    var map = new mapboxgl.Map({
        container: 'map',
        style: 'mapbox://styles/mapbox/streets-v10'
    });
</script>

<!-- Zoom controls to map. -->
<script src="https://theel0ja.github.io/mapbox-gl-disable-map-rotation/dist/script.js?v=1"></script>
<link rel="stylesheet" href="https://theel0ja.github.io/mapbox-gl-disable-map-rotation/dist/style.css?v=1">
<script>
    // Add zoom and rotation controls to the map.
    map.addControl(new mapboxgl.NavigationControl());

    // Disable map rotation.
    disableMapRotation(map);
</script>