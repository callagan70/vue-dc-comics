<template>
    <div>
        <HeaderDiTesta />
        <FiguresDc />
        <CataLog />
        <SectionTwo />
    </div>

</template>

<script>
import HeaderDiTesta from './components/HeaderDiTesta.vue'
import FiguresDc from './components/FiguresDc.vue'
import CataLog from './components/CataLog.vue'
import SectionTwo from './components/SectionTwo.vue'

export default {
  components: {
    HeaderDiTesta,
    FiguresDc,
    CataLog,
    SectionTwo,
  }
}
</script>

<style lang="scss">
  @import './style/reset.scss';
</style>
