<template>
  <div class="services">
    <Service
      title="Front End"
      description="Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fuga soluta obcaecati ullam provident maiores laboriosam quis? Atque asperiores saepe eligendi veniam laboriosam excepturi, impedit voluptatibus tempora sequi, debitis deserunt magni?"
    />

    <Service
      title="Back End"
      description="Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fuga soluta obcaecati ullam provident maiores laboriosam quis? Atque asperiores saepe eligendi veniam laboriosam excepturi, impedit voluptatibus tempora sequi, debitis deserunt magni?"
    />

    <Service
      title="Manutençao"
      description="Lorem ipsum, dolor sit amet consectetur adipisicing elit. Fuga soluta obcaecati ullam provident maiores laboriosam quis? Atque asperiores saepe eligendi veniam laboriosam excepturi, impedit voluptatibus tempora sequi, debitis deserunt magni?"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  components: { Service }
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 5rem;
}
</style>
