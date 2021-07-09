<!-- Please remove this file from your project -->
<template>
  <div>
    <client-only>
      <vl-map style="height: 500px">
        <vl-layer-tile>
          <vl-source-osm />
        </vl-layer-tile>
      </vl-map>
    </client-only>
  </div>
</template>

<script>
if (process.client) {
  console.dir(require('~/plugins/ol'))
}

export default {
}
</script>
