<template>
  <div>
    <section class="text-3xl flex justify-center content-ce
    <div>

    </div>nter flex-col mx-auto text-center"
    >Buy Now</section>
    <section class="flex text=6l justify-center content-center">
      <div class="days nr-2 relative">
        {{displayDays}}
        <div class="label text-sm absolute bottom-0">days</div>
      </div>
      <span class="leading-snug">:</span>
      <div class="hours mx-2 relative">
        {{displayHours}}
        <div class="label text-sm absolute bottom-0">hours</div>
      </div>
      <span class="leading-snug">:</span>
      <div class="minutes mx-2 relative">
        {{displayMinutes}}
        <div class="label text-sm absolute bottom-0">minutes</div>
      </div>
      <span class="leading-snug">:</span>
      <div class="seconds ml-2 relative">
        <div>{{displaySeconds}}</div>
        <div class="label text-sm absolute bottom-0">seconds</div>
      </div>
    </section> 
  </div>
</template>

<script>
  export default {
    data: () => ({
      displayDays: 0,
      displayHours: 0,
      displayMinutes: 0,
      displaySeconds: 0
    })
  }
</script>

<style lang="scss" scoped>

</style>