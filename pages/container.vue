<template>
  <div>
    <div class="container bg-gray-100 overflow-y-auto">
      <div
        class="
          grid
          gap-2
          grid-cols-1
          md:grid-cols-3
          lg:grid-cols-4
          grid-rows-3
          m-3
        "
      >
        <div
          v-for="n in [
            1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19,
            20,
          ]"
          :key="n"
          class="
            p-4
            box-border
            border-1
            rounded-lg
            space-y-2
            shadow-sm
            hover:shadow-lg
            bg-white
          "
        >
          <div class="flex justify-between font-mono">
            <h3 class="font-bold">Hello world!</h3>
            <span class="text-xs">2021-204</span>
          </div>
          <div class="prose prose-slate">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Numquam
            dolorem tenetur provident earum tempore recusandae voluptatum, rerum
            quis, vitae qui iusto atque quibusdam placeat. Illo dolorem
            veritatis dolor dolores nulla.
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'ContainerPage',
}
</script>

<style lang="scss" scoped>
</style>