---
layout: page
title: Vierailijoille
permalink: /vierailijoille/
---

Taloyhteisömme sijaitsee maisemillaan ihastuttavassa Papinsaaressa noin 9 kilometrin päässä Turun keskustasta. Kesäisin tänne on mukavaa pyöräillä keskustastakin asti. Pyörätiet ovat hyvässä kunnossa ja niitä pitkin pääsee melko suoraan perille asti.
Autollakaan tänne ei ole vaikea löytää.

Asunnot on numeroitu alusta 0-15 välillä, asunnot 0-12 ovat rivissä piha tien päätyyn asti. Keskellä sijaitsevat asunnot 13, 14 ja 15. Jokaisella talolla on lisäksi oma aakkosensa, A-G, jotka merkitään asunnon numeroon yhteydessä.

#### Autopaikoitus

Vieraisiin tuleville autopaikkoja ei valitettavasti erikseen löydy. Paikkaa kannattaa kysäistä asunnon omistajalta.

<!-- .text-center breaks Mapbox GL js -->
<center>
  <div id='map' style='width: 400px; height: 300px; text-align: left;'></div>
</center>
<script>
    mapboxgl.accessToken = 'pk.eyJ1IjoiZXNtYWxhIiwiYSI6ImNqZXZ5N2hqZzBpbWEyd3BjZm5wMHkzN2cifQ.2Vj6-u9JdYdsb92maw3jyQ';
    var map = new mapboxgl.Map({
        container: 'map',
        style: 'mapbox://styles/mapbox/streets-v10',
         center: [22.272281, 60.395314],
            zoom: 10,
    });
    new mapboxgl.Marker()
        .setLngLat([22.272281, 60.3953140])
        .addTo(map);
</script>

<!-- Add zoom controls to map. -->
<script src="https://cdn.theel0ja.info/libs/mapbox-gl-disable-map-rotation/dist/script.js"></script>
<link rel="stylesheet" href="https://cdn.theel0ja.info/libs/mapbox-gl-disable-map-rotation/dist/style.css">
<script>
    // Add zoom and rotation controls to the map.
    map.addControl(new mapboxgl.NavigationControl());

    // Disable map rotation.
    disableMapRotation(map);
</script>
