<template>
    <div class="place">
        <img :src="img" width="235" height="300"/>
        <h2>{{name}}</h2>
        <p>{{desc}}</p>
      </div>
</template>
<script>
export default {
  props: ["img", "name", "desc"]
};
</script>
