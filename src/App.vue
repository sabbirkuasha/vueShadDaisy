<script setup>
import { Button } from '@/components/ui/button'


import { Calendar } from '@/components/ui/calendar'

// const value = ref(today(getLocalTimeZone())) 
</script>

<template>
  <div class="p-4 flex flex-col gap-5">

    <h1 class="text-3xl border p-2">Hello World</h1>
    <h2 class="ring p-4">Hey</h2>
    <div>
      <Button>Click me</Button>
    </div>
  </div>

  <div class="flex p-4">
    <Calendar v-model="value" :weekday-format="'short'" class="rounded-md border" />
  </div>

  <div class="p-4">
    <button class="btn btn-primary">Hello</button>
  </div>

</template>
