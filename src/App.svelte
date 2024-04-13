<script lang="ts">
  import { MapLibre } from "svelte-maplibre";
</script>

<main>
  <MapLibre
    center={[0, 0]}
    zoom={4}
    class="map"
    standardControls
    style="https://tile.openstreetmap.jp/styles/osm-bright-ja/style.json"
  />
</main>

<style>
  main {
    width: 100vw;
    height: 100vh;
  }

  :global(.map) {
    height: 100vh;
  }
</style>
