<template>
  <section>
    <h3 class="mt-8 font-black text-2xl">{{ title }}</h3>
    <div class="mt-4">
      <div class="mt-2 flex border-b border-gray-800" v-for="edge in items.edges" :key="edge.node.id">
        <div class="flex-grow px-1 py-1 m-1">
          {{ edge.node.title }}
        </div>
        <div class="flex-grow-0 text-right px-1 py-1 m-1">
          {{ edge.node.price }}
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  props: ['items', 'title'],
}
</script>