<template>
  <div>
      <div class="pt-8 w-full block md:flex">
          <div class="md:w-1/3 block pr-2">
            <div class="pl-4">
                <HeaderMainItem/>
            </div>
            <div class="pt-4 pl-4">
                <HeaderMainItem/>
            </div>
          </div>
          <div class="md:w-2/3">
                <div class="pl-4">
                    <HeaderMainItem/>
                </div>
          </div>
        </div>
      </div>
  </div>
</template>

<script>
import HeaderMainItem from './HeaderMainItem';
export default {
    components:{
        HeaderMainItem
    },
}
</script>

<style scoped>

</style>