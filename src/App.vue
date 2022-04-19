<template>
    <div>
        <HeaderDiTesta />
        <FiguresDc />
        <CataLog />
        <SectionTwo />
        <SectionThree />
    </div>

</template>

<script>
import HeaderDiTesta from './components/HeaderDiTesta.vue'
import FiguresDc from './components/FiguresDc.vue'
import CataLog from './components/CataLog.vue'
import SectionTwo from './components/SectionTwo.vue'
import SectionThree from './components/SectionThree.vue'

export default {
  components: {
    HeaderDiTesta,
    FiguresDc,
    CataLog,
    SectionTwo,
    SectionThree,
  }
}
</script>

<style lang="scss">
  @import './style/reset.scss';
</style>
