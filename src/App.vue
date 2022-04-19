<template>
  <div>
        <HeaderDiTesta />
        <FiguresDc />
        <CataLog />
        <SectionTwo />
        <SectionThree />
        <FooTer />
  </div>

</template>

<script>
import HeaderDiTesta from './components/HeaderDiTesta.vue'
import FiguresDc from './components/FiguresDc.vue'
import CataLog from './components/CataLog.vue'
import SectionTwo from './components/SectionTwo.vue'
import SectionThree from './components/SectionThree.vue'
import FooTer from './components/FooTer.vue'

export default {
  components: {
    HeaderDiTesta,
    FiguresDc,
    CataLog,
    SectionTwo,
    SectionThree,
    FooTer,
  }
}
</script>

<style lang="scss">
  @import './style/reset.scss';
</style>
