<template>
  <div>
    <h2>this is bb</h2>
    <button @click.stop="$router.push({path: '/c'})">to c</button>
  </div>
</template>
<script>
export default {
  name: 'bb'
}
</script>
