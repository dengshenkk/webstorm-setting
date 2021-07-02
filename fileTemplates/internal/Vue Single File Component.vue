<template>
  <div class="${COMPONENT_NAME}-wrap">
    #[[$END$]]#
  </div>
</template>

<script>
/**
 * Created by ${USER} At ${YEAR}-${MONTH}-${DAY} ${TIME}:${SECOND}
 */
export default {
  name: '${COMPONENT_NAME}',
  props: {},
  data() {
    return {}
  },
  watch: {},
  mounted() {
    this.init()
  },
  methods: {
    init() {
      console.info('${COMPONENT_NAME} is init')
    }
  }
}
</script>

<style lang="scss" scoped>
.${COMPONENT_NAME}-wrap {

}
</style>
